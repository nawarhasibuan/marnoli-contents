---
tags: [kota, osn, recursive, searching, array]
options: 
answer: 
difficulties:
  - hard
point: 8
max_point: 10
source: osk
---

```cpp
int x(int l, int r, int v, vector<int> isi){
	if (l == r) return isi[l];
	else {
		int m = (l+r)/2;
		if(isi[m] > v) return x(l,m,v,isi);
		else return x(m+1,r,v,isi);
	}
}
```

Jika dipanggil `x(0,9,3,{-4,1,7,9,0,1,2,4,3,-1})`, nilai kembaliannya adalah $...$
