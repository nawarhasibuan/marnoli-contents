---
tags: [sma, osn, kota, recursive]
options: 
answer: 
difficulties:
  - hard
point: 8
max_point: 6
text: 
source: osk
---

Apa output program dibawah ini

```cpp
#include <iostream>

using namespace std;

void callfoo(int &a, int b) {
    int p, q;
    if (b <= 2)
        a = 1;
    else {
        callfoo(p, b - 1);
        callfoo(q, b - 2);
        a = p + q;
    }
}

int main() {
    int x=0, y=5;
    callfoo(x, y);
    cout << x << endl;
    
    return 0;
}
```
