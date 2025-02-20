---
tags: [kota, sma, recursive]
options: 
answer: 2025
difficulties:
  - medium
point: 6
max_point: 10
source: osk
text:
---

Dari potongan program di bawah ini:

```cpp
int hap(int x, int t) {
    if (t == 1)
        return x % 5;
    else
        return 5 * x;
}
int hip(int x, int y) {
    if (x < y)
        return hip(y, x);
    else
        return hap(x, 1) + hap(y, 2);
} 

int hop(int x, int y, int z) {
    if (y > z)
        return hop(x, z, y);
    else if (x > y)
        return hop(y, x, z);
    else
        return hip(x, y) + z;
}
```

Apakah output dari pemanggilan `hop(18, 3, 2007)` ?
