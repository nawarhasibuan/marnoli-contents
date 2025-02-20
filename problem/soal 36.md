---
tags: [sma, osn, kota, series, modullo]
options: 
answer: 
difficulties:
  - medium
point: 8
max_point: 10
text: 
source: osk
---

Di hari ulang tahun Kwak, dia mengadakan permainan “Putaran Permen.” Permainan tersebut adalah sebagai berikut, misalnya ada $10$ orang yang ikut, termasuk Kwak. Mereka semua melingkar, dengan Kwak selalu di posisi pukul 12. Kwak yang membawa permen dengan jumlah yang sangat besar akan membagikannya kepada teman-temannya. Dimulai dari Kwak, mereka akan berhitung dari 1 (satu) hingga 2 (dua). Setiap orang yang berhitung 2 (dua) akan mendapatkan 1 (satu) buah permen, tapi setelah itu harus keluar dari lingkaran. Hal tersebut terus dilakukan hingga tersisa 1 (satu) orang, dan orang tersebut akan mendapatkan sisa permen yang tersedia.

Dalam kasus 10 orang, maka orang ke-5 (Kwak adalah orang bernomor 1) yang akan mendapatkan sisa permen.

- urutan awal, Kwak, no 2, no 3, no 4, no 5, $\dots$ , no 10. (**Kwak nomor 1**)
- putaran **pertama**, kwak berhitung 1, nomor 2 berhitung 2, nomor 3 berhitung 1, nomor 4 berhitung 1, dst $\dots$ nomor 10 berhitung 2
- no 2, no 4, no 6, no 8, no 10 dapat 1 permen dan keluar barisan.
- urutan putaran **kedua**: no 1, no 3, no 5, no 7, no 9
- karena urutan terakhir di putaran sebelumnya berhitung 2, no 1 berhitung 1, no 3 berhitung 2, no 5 berhitung 1, no 7 berhitung 2, no 9 berhitung 1
- no 3, no 7 dapat 1 permen dan keluar barisan.
- urutan putaran **ketiga**: no 1, no 5, no 9
- karena urutan terakhir di putaran sebelumnya berhitung 1, no 1 berhitung 2, no 5 berhitung 1, no 9 berhitung 2
- no 1 (Kwak), no 9 dapat 1 permen dan keluar barisan.
- tersisa no 5 di barisan, nomor 5 dapat sisa permen. **selesai**

Jika ada 31 orang yang datang ke pesta ulang tahun kwak, orang nomor berapa yang mendapat sisa permen?
