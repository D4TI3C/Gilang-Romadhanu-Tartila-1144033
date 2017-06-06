**Rangkuman Pertemuan 6 Kecerdasan Buatan**
<p align="center">
  	<img src="/img/pertemuan6.jpg">
</p>

Latar Belakang Masalah

1. Apa itu Depth-First Search (DPS)?
2. Apa kelebihan Depth-First Search (DPS)?
3. Apa kelemahan Depth-First Search (DPS)?

Depth-First Search (DPS) merupakan Pencarian dilakukan pada satu node dalam setiap level dari yang paling kiri. Jika pada level yang paling dalam, solusi belum ditemukan, maka pencarian dilanjutkan pada node sebelah kanan. Node yang kiri dapat dihapus dari memori. Jika pada level yang paling dalam tidak ditemukan solusi, maka pencarian dilanjutkan pada level sebelumnya. Demikian seterusnya sampai ditemukan solusi. Jika solusi  ditemukan maka tidak diperlukan proses backtracking (penelusuran balik untuk mendapatkan jalur yang dinginkan).

Kelebihan Depth-First Search  (DPS) :

- --Pemakain memori hanya sedikit, berbeda jauh dengan BFS yang harus menyimpan semua node yang pernah dibangkitkan.
- --Jika solusi yang dicari berada pada level yang dalam dan paling kiri, maka DFS akan menemukannya secara cepat.

Kelemahan Depth-First Search (DPS) :

- --Jika pohon yang dibangkitkan mempunyai level yang dalam (tak terhingga), maka tidak ada jaminan untuk menemukan solusi (Tidak Complete).
- --Jika terdapat lebih dari satu solusi yang sama tetapi berada pada level yang berbeda, maka pada DFS tidak ada jaminan untuk menemukan solusi yang paling baik (Tidak Optimal).

Penutup

Kesimpulan

Dari pernyataan diatas dapat disimpulkan bahwa Depth-First Search (DPS) suatu algoritma pencarian yang dilakukan pada satu node dalam setiap level dari yang paling kiri.

Saran

Sebaiknya algoritma Depth-First Search ini dapat diimplementasikan ke aplikasi untuk latihan kita

* Nama : Gilang Romadhanu Tartila
* NPM : 1144033
* Kelas : 3C
* Prodi : D4 Teknik Informatika
* Mata Kuliah : Kecerdasan Buatan

Link Github : https://github.com/D4TI3C/Gilang-Romadhanu-Tartila-1144033

Scan Plagiarisme

1.searchenginereport - Link https://drive.google.com/open?id=0B5gySyqZ4GGoYUZ6TGJLd0hhOWs

2.duplichecker - Link https://drive.google.com/open?id=0B5gySyqZ4GGocU5oSWlhWmltSms