---
title: Fix Goal
problems:
  - soal 24
  - soal 25
---

Dari potongan program berikut

```cpp
int f(int a) {
	if (a == 0) return 1;
	else return 2 * f(a - 1);
}

int g(int b) {
	if (b == 0) return f(b);
	else return f(b) + g(b - 1);
}
```
