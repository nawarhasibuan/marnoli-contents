---
tags: [sma, kota, path, euler, bebras]
options: 
answer: 
difficulties:
  - easy
point: 8
max_point: 10
text: 
source:
---

```mermaid
flowchart TD
a((1))
b((2))
c((3))
d((4))
e((5))
f((6))
a o--o b
f o--o d
a o--o e
c o--o d
f o--o b
e o--o b
a o--o d
c o--o e
b o--o c
e o--o d
```

Graf diatas adalah peta tempat pariwisata yang sedang dibangun di ibukota baru. Terdapat 6 tempat wisata yang akan dipromosikan, ditandai dengan nomor dalam lingkaran. dan jalan yang sudah terhubung dengan beberapa tempat wisata lain.

Presiden akan melakukan kunjungan untuk melihat perkembangan pembangunan jalan. Karena jadwal yang sibuk, pemimpin proyek sudah menentukan rute paling efisien perjalanan sehingga semua jalan yang sudah dibangun dilewati minimal satu kali.

Jika pilot harus mendaratkan Presiden di tempat wisata nomor $X$, berapakah nilai $X$ terkecil?
