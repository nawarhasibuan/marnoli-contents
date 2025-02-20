---
title: Maaf, Otak Vakum Elegan
problems:
  - soal 22
  - soal 23
---

Perhatikan potongan program berikut

```cpp
int move(int n) {
	if (n == 1) return 1;
	else return 2 * move(n - 1) + 1;
}
```
