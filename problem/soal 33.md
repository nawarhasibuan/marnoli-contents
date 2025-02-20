---
tags: [kota, osn, array, function, looping]
options: 
answer: 500
difficulties:
  - medium
point: 7
max_point: 10
source:
---

Perhatikan program berikut!

```cpp
int c_true(vector<bool> arr){
	int c = 0;
	for (int i = 0; i < arr.length(); i++){
		if (arr[i]) c++;
	}
	return c;
}
int main(){
	bool ar[1000];
	for (int i = 0; i < 1000; i++){
		ar[i] = false;
	}
	for (int i = 0; i < 1000; i++){
		int j = i;
		while(j < 1000) {
			ar[j] = !ar[j];
			j++;
		}
	}
	cout << c_true(ar) << endln;
	return 0;
}
```

Apa yang tertulis di layar setelah program dijalankan
