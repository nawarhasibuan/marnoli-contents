---
tags: [sma, osn, kota, recursive]
options: 
answer: 
difficulties:
  - medium
point: 5
max_point: 10
text: 
source: osk
---

Perhatikan fungsi berikut!

```cpp
int t(int a, int b){
	if (a < b) return t(b,a);
	else if (b == 0) return a;
	else {
		 int x =t(b, a % b);
		 return x*x;
	}
}
```

Tentukan kembalian `t(30,6)`
