# Try Out OSK Informatika 2025

# Bagian A: Berpikir Komputasional

## Soal 1:

<div style="page-break-after: always;"></div>

## Soal 2:

<div style="page-break-after: always;"></div>

## Soal 3:

<div style="page-break-after: always;"></div>

## Soal 4:

<div style="page-break-after: always;"></div>

## Soal 5:

<div style="page-break-after: always;"></div>

## Soal 6:

<div style="page-break-after: always;"></div>

## Soal 7:

<div style="page-break-after: always;"></div>

## Soal 8:

<div style="page-break-after: always;"></div>

## Soal 9:

<div style="page-break-after: always;"></div>

## Soal 10:

<div style="page-break-after: always;"></div>

# Bagian B: Pemecahan Masalah

## Soal 11-13:

<div style="page-break-after: always;"></div>

## Soal 14-16:

<div style="page-break-after: always;"></div>

## Soal 17-19: Bebek Istimewa

Tahun ini banyak bebek Pak Dengklek yang bertelur, tetapi Pak Dengklek mandapati masalah. Karena bebek-bebek Pak Dengklek merasa selalu jadi yang istimewa, setiap bebek yang sedang bertelur harus berjarak minimal $sqrt(2)$ (akar 2) dari bebek yang sedang bertelur lainnya.

Pak Dengklek merasa persegi adalah bentuk yang istimewa dan kandang bebeknya juga berbentuk persegi.

---

Jika ukuran sisi kandang bebek 2 meter, berapa banyak bebek maksimal yang mau bertelur di kandang Pak Dengklek?

---

Jika tiap bebek yang bertelur butuh waktu 5 menit dan ukuran sisi kandang 2 meter. Pak Dengklek dapat pesanan 20 butir telur dari rumah makan langganannya. Berapa lama waktu minimal yang dibutuhkan Pak Dengklek untuk memenuhi permintaan tersebut?

---

Pak Dengklek ingin membesarkan kandangnya tetapi tetap mempertahankan bentuk persegi. Berapa ukuran kandang yang harus dibuat Pak Dengklek sehingga 20 bebek dapat bertelur secara bersamaan?

<div style="page-break-after: always;"></div>

## Soal 20-22:

<div style="page-break-after: always;"></div>

## Soal 23-25:

<div style="page-break-after: always;"></div>

# Bagian C: Algoritmika

## Soal 26-28: Timbre

Perhatikan potongan kode program berikut

```
int timbre(vector<int> A) {
	int n = A.size();
	int s = 1;
	int f = 1;
	for (int i = 1; i < n; i++) {
		if (A[i-1] == A[i]) {
			s++;
		} else {
			s = 1;
		}
		if (s > f) f = s;
	}
	return f;
}
```

---

Dari 5 pilihan berikut, mana yang mengembalikan nilai paling besar?

- A. `timbre({1, 1, 0, 0, -1, -1, 1, -1})`
- B. `timbre({0, 0, 0, 0, 1, 0, -1, 1})`
- C. `timbre({1, 1, -1, -1, 0, 1, 1, -1})`
- D. `timbre({1, 1, 1, 0, 1, 1, -1, 0})`
- E. `timbre({1, 0, 0, -1, 0, 1, 0, 1})`

---

Jika `A` adalah vector dengan panjang 3 dan hanya terdiri dari angka `0` hingga `9`, maka berapa banyak kemungkinan A sedemikian sehingga pemanggilan `timbre(A)` mengembalikan 1?

**Tuliskan jawaban dalam bentuk ANGKA.**

---

**Benar** atau **Salah**: Untuk vector `A` apapun, jika `N` adalah panjang dari `A` kembalian `timbre(A)` terbesar yang mungkin adalah `N`.

**Tuliskan jawaban dalam bentuk BENAR/SALAH dengan huruf kapital.**

<div style="page-break-after: always;"></div>

## Soal 29-31: Lowalangi

Perhatikan potongan kode program berikut

```
int lowalangi(int n, int m) {
	int i = 2;
	while (i < n || i < m) {
		if ((n % i == 0) && (m % i == 0)) return i;
		i++;
	}
	return -1;
}
```

---

Berapakah kembalian dari pemanggilan `lowalangi(78,36)`?

---

Berapa banyak `N` bilangan asli yang lebih kecil dari $20$ ($1<=N<=20$) yang menyebabkan pemanggilan `lowalangi(N,5)` mengembalikan `-1`?

---

**Benar** atau **Salah**: Jika `N` dan `M` lebih besar dari $100$, pada pemanggilan `lowalangi(N,M)` tidak pernah mengembalikan `-1`

**Tuliskan jawaban dalam bentuk BENAR/SALAH dengan huruf kapital.**
<div style="page-break-after: always;"></div>

## Soal 32-34:

Perhatikan potongan kode program berikut

<div style="page-break-after: always;"></div>

## Soal 35-37:

<div style="page-break-after: always;"></div>

## Soal 38-40:

<div style="page-break-after: always;"></div>

# Bagian D. Kunci Jawaban

Berikut jawabannya

- 43. t
- 26. B
- 27. 720
- 28. benar
- 29. 6
- 30. 17
- 31. salah
