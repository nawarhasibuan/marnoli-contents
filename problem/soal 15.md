---
tags: [sma, osn, kota, recursive]
options: 
answer: 1
difficulties:
  - easy
point: 5
max_point: 10
text: 
source: osk
---

Perhatikan fungsi berikut

```cpp
int ndec(int n) {
	if (n == 0) return n * ndec(n - 1); 
	else return 1; 
}
```

Berapa hasil dari `ndec(5)`?
