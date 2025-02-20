---
tags: [array, sma, looping, osn]
options:
  - AKITAMATIKA
answer: 0
difficulties:
  - medium
point: 5
max_point: 10
source: osk
---

```cpp
#include <iostream>
using namespace std;

int main() {
    char x[12] = {'I', 'N', 'F', 'O', 'R', 'M', 'A', 'T', 'I', 'K', 'A'};

    for (int i = 0; i < 11; i++) {
        x[i] = x[13 - (i + 3)];
        x[13 - (i + 3)] = x[10 - i];
        x[10 - i] = x[i];
    }

    cout << x << endl;

    return 0;
}
```

Jika program diatas dijalankan, seperti apa nilai outputnya?
