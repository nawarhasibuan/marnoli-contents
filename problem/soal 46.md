---
tags: [kota, sma, osn, conditional]
options: 
answer: 
difficulties:
  - medium
point: 7
max_point: 10
source: osk
---

```cpp
int main(){
    int A, B, C, D;
    cin >> A >> B >> C >> D;
    if (A >= B)    {
        if (A >= C)        {
            if (A >= D) {
                cout << D << endl;
            } else {
                cout << A << endl;
            }
        } else {
            if (C >= D) {
                cout << D << endl;
            } else {
                cout << C << endl;
            }
        }
    } else {
        if (B >= C) {
            if (B >= D) {
                cout << D << endl;
            } else {
                cout << B << endl;
            }
        } else {
            if (C >= D) {
                cout << D << endl;
            } else {
                cout << C << endl;
            }
        }
    }
    return 0;
}
```

Jika masukan yang diberikan `89 78 100 105`, keluaran dari program diatas adalah $...$
