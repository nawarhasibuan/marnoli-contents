---
tags: [kota, sma, recursive]
options: 
answer: 
difficulties:
  - medium
point: 6
max_point: 10
source: osk
---

Perhatikan fungsi berikut!

```cpp
int proses(int x) {
    if (x < 2)
        return x;
    else
        return proses((x / 2) * (x % 2)) + proses((x / 2) + (x % 2));
}
```

Berapa kembalian dari `proses(11)`?
