---
tags: [sma, kota, bebras, dijkstra]
options: 
answer: 
difficulties:
  - medium
point: 6
max_point: 10
text: 
source:
---

Kwok akan mengunjungi Kwik sahabat lamanya yang sedang bertugas di kota $5$.

```mermaid
graph
e((1))
c((2))
g((3))
a((4))
f((5))
b((6))
d((7))

f o--1--o b
a o--3--o b
f o--4--o d
a o--5--o e
c o--1--o d
e o--2--o b
b o--4--o g
a o--2--o g
c o--1--o e
b o--3--o c
e o--2--o d
a o--2--o d
```

Karna tidak ada bandara di kota $5,6$ dan $1$, dimanakah Kwok mendarat supaya jaraknya lebih dekat ke tempat Kwik?

_**Jika lebih dari satu pilihan, tulis bilangan terkecil**_
