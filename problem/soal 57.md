---
tags:
  - kota
  - sma
  - recursive
  - array
  - sorting
options: []
answer: 135789101829100
difficulties:
  - medium
point: 7
max_point: 10
source: osk
text:
---

Apa yang tertulis di layar saat program berikut dijalankan

```cpp
#include <iostream>
using namespace std;

int isi[10] = {5, 10, 18, 1, 7, 9, 3, 8, 100, 29};

void Whatsup(int l, int r) {
    int X = isi[l];
    isi[l] = isi[r];
    isi[r] = X;
}

void naoooon(int l, int r) {
    if (l < r) {
        int kiri = l, kanan = r;
        int ini = isi[(kiri + kanan) / 2];
        while (kiri < kanan) {
            while (isi[kiri] > ini) kiri++;
            while (isi[kanan] < ini) kanan--;
            if (kiri < kanan) Whatsup(kiri, kanan);
        }
        naoooon(l, kanan);
        naoooon(kanan + 1, r);
    }
}

int main() {
    naoooon(0, 9);
    for (int i = 0; i < 9; i++) {
        cout << isi[i] << " ";
    }
    cout << isi[9] << endl;
    return 0;
}
```
