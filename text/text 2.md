---
title: You Only Live Once
problems:
  - soal 16
  - soal 17
---

Perhatikan fungsi berikut

```cpp
int yolo(int x, int y) {
	if (y == 0) return x; 
	else return yolo(y, x % y) * yolo(y % x, x % y) * y; 
}
```
