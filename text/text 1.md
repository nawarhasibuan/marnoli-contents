---
title: Ping Pong
problems:
  - soal 13
  - soal 14
---

Dari fungsi berikut

```cpp
int pingpong(int x) {
	int ping, pong, tenis, meja; 
	meja = 0;
	for (ping = 1; ping <= x; ping++) {
		for (pong = 1; pong <= ping; pong++) {
			for (tenis = ping; tenis >= pong; tenis--){
				meja += tenis; 
			}
		}
	}
	return tenis + meja;
}
```
