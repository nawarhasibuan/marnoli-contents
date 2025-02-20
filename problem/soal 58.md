---
tags: [kota, sma, recursive, array, searching]
options: 
answer: 0
difficulties:
  - medium
point: 8
max_point: 10
source: osk
text:
---

perhatikan fungsi berikut!

```cpp
int modal(vector<int> tabungan, int idx, int x, int m, int n) {
    if (idx == tabungan.size()) return x;
    
    if (tabungan[idx] == tabungan[idx - 1]) {
        n++;
    } else {
        n = 1;
    }
    
    if (n > m) {
        m = n;
        x = tabungan[idx];
    }
    
    return modal(tabungan, idx + 1, x, m, n);
}
```

Berapa kembalian pada pemanggilan `modal({-1,0,1,0,-1,0,1},1,-1,1,1)`
