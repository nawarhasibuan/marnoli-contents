---
title: Work at Height
problems:
  - soal 19
  - soal 20
  - soal 21
---

Berdasarkan fungsi `wah` dibawah ini

```cpp
int wah(int x, int y) {
	if (x == 0 && y == 0) return 0;
	else if (x > y) {
		if (x > -y) return wah(x - 1, y) + 1;
		else return wah(x, y + 1) + 1;
	} else {
		if (x > -y) return wah(x, y - 1) + 1;
		else return wah(x + 1, y) + 1;
	}
}
```
