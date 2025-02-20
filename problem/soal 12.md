---
tags: [sma, looping, osn, kota]
options: 
answer: 118
difficulties:
  - medium
point: 5
max_point: 10
source: osk
---

Perhatikan program di bawah ini

```cpp
#include <iostream>
using namespace std;
int main() {
    int a = 13, b = 1, n;
    cin >> n;
    while (a < n) {
        a = a + b;
        b = b + 1;
    }
    cout << b << endl;
    return 0;
}
```

Berapa nilai `n` maksimal yang membuat keluaran program di layar adalah `15`
