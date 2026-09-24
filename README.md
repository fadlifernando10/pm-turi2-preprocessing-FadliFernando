Praktikum 4: Preprocessing & Feature Engineering

Mata Kuliah: pembelajaran Mesin

Nama	     : Fadli Fernando

Nim	       : 2488010043

ringkasan praktikum preprocessing dan feature engineering:
- penanganan nilai hilang menggunakan imputasi median
- encoding variable kategorikal menggunakan ordinal encoding dan one-hot encoding
- pengskalaan fitur menggunakan MinMaxScaler/StandartScaler
- pembagian data latij dan data ujisebelum proses pengskalaan untuk mencegah terjadinya kebocoran data

isi repositori:
PM_P4_FadliFernando_2488010043.ipynb : Notebook Jupyter/Google Colab berisi seluruh tahapan prapemrosesan dan latihan mandiri.

Temuan dan catatan penting:

- Urutan pengerjaan (train test split dilakukan sebelum scaling) sangat krusial agar informasi statistic dari data uji tidak mencemari model

- Pengguna one-hot encoding berhasil mengubah kolom kategori nominal

seperti kota dan divisi menjadi representasi biner yang dapat diproses oleh algoritma machine learning

- Verifikasi akhir memastikan bahwa seluruh fata sudah bersih dari nilai hilang, berformat numerik dan memiliki skala yang seragam
