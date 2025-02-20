---
tags: [kota, sma, recursive]
options: 
answer: 
difficulties:
  - medium
point: 8
max_point: 10
source: osk
text:
---

Dari fungsi berikut

```cpp
int kibo(int n) {
    if (n < 3)
        return n;
    else
        return kibo(n - 1) + kibo(n - 3);
}
```

Nilai kembalian dari pemanggilan `kibo(7)` adalah $...$
