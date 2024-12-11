Segmentasi Produk UMKM YIC Cafe
Repository ini berisi kodingan untuk Analisa Penjualan YIC Coffe menggunakan algoritma Linear Regression. Kami menggunakan algoritma ini untuk membantu memprediksi hasil jual produk pada tahun berikutnya berdasarkan jumlah penjualan (Quantity) di masa depan berdasarkan waktu (tanggal) dengan menggunakan rata-rata nilai harga dari data pelatihan.
Dengan kata lain, Kita sedang mencoba memprediksi jumlah penjualan di masa depan untuk periode tertentu (misalnya 12 bulan ke depan) berdasarkan data historis waktu dan harga produk..

Terdapat 2 file dalam repository ini, yaitu:

YIC cafe Revisi.xlsx
Merupakan dataset yang belum di processing.
Finpro_Big_Data .ipynb
Merupakan kode untuk jupyter notebook menggunakan colab




Deskripsi Proyek
Tujuan: 
- mengidentifikasi produk terlaris
- pola penjualan harian
- pembelian berdasarkan gender
- memprediksi penjualan masa depan

Bahasa Pemrograman: Python

Dataset yang kita gunakan Merupakan dataset real dari UMKN tersebut.

Teknologi yang kita pakai : 
 pandas as pd
 train_test_split
andomForestRegressor 
fromean_squared_error, r2_score
LabelEncoder
