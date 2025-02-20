---
tags: [kota, osn, recursive]
options: 
answer: 
difficulties:
  - medium
point: 7
max_point: 10
source: osk
---

keluaran dari `meong(888)` adalah

```cpp
int meong(int x){
	if (x == 0) return 0;
	else if (x % 2 == 0 && (x / 2) % 2 == 1){
		return meong((x / 2) / 2) + 1;
	} else meong(x + 1) + 1;
}
```
