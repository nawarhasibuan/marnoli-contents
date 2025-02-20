---
tags: [looping, function, searching, kota, osn]
options: 
answer: 
difficulties:
  - hard
point: 6
max_point: 10
source: osk
---

Perhatikan fungsi berikut

```cpp
int get(vector<int> arr) {
	if (arr[0] < arr.end()) return 1;
	else {
		int l = 0, r = arr.length()-1;
		while (l < r) {
			int m = (l+r)/2
			if (arr[l] <= arr[r]) l = m+1;
			else r = m;
		}
		return l;
	}
}
```

Berapa kembalian dari `get({303, 304, 365, 454, 487, 6, 12})`
