---
title: Pesan Pasti Benar
problems:
  - soal 51
  - soal 52
---

Bebek Kwak mengirimkan pesan kepada temannya menggunakan $8$ karakter, setiap karakter bisa bernilai `0` atau `1`. Kwak menggunakan `5` karakter pertama untuk menunjukkan pesan yang dikirimkan. Untuk menunjukkan bahwa pesan itu benar, Kwak memakai $2$ karakter sisanya sebagai berikut:

- Karakter 6 bernilai `0` jika banyaknya `0` di antara $5$ karakter pertama adalah genap; jika tidak maka karakter ke $6$ bernilai `1`.
- Karakter ke $7$ bernilai `1` jika banyaknya `1` di antara enam karakter pertama adalah genap; jika tidak maka karakter ke $7$ bernilai `0`.
- karakter ke 8 adalah karakter yang paling sedikit diantara `0` atau `1` pada $7$ karakter pertama

Sebagai contoh, jika Kwak ingin mengirimkan pesan `01101`, maka:

- karakter ke $6$ haruslah `0`, $2$ (genap) karakter `0` di $5$ karakter pertama. `011010` adalah $6$ karakter pertama
- karakter ke $7$ haruslah `0`, 3 (ganjil) karakter `1` di $6$ karakter pertama. `0110100` adalah $7$ karakter pertama
- karakter ke $8$ haruslah `1`
yang harus dikirimkan oleh Kwak adalah `01101001`
