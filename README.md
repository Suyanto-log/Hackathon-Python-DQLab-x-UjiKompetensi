# Hackathon-Python-DQLab-x-UjiKompetensi
Lomba membuat kode Python yang dilaksanakan pada Sabtu, 9 Mei 2026, mulai pukul 13.00 WIB hingga 23.00 WIB

# Credits / Acknowledgment
- [dqlab](https://dqlab.id/)
- [ujikompetensi](https://ujikompetensi.com/)

Hackathon Python DQLab x UjiKompetensi DQFresh Mart Retail adalah sebuah toko retail (mini mart) dengan satu cabang saja. Selama bertahun-tahun, perusahaan sangat sukses dalam penjualan dengan produkproduk andalan tradisional. Namun dalam 6 bulan terakhir, manajemen mulai menghadapi masalah serius: total nilai penjualan terus menurun. Secara kasat mata memang jumlah pengunjung terlihat turun. Manajer toko awalnya menganggap kondisi ini hanya akibat pelemahan ekonomi. Karena itu strategi awal toko adalah: markdown

- mempertahankan produk bestseller
- mengurangi eksperimen produk baru
- emperbesar stok produk historis terbaik
- nekan risiko inventory

Tetapi setelah beberapa saat Sophia, manajer toko tersebut mulai merasa ada sesuatu yang tidak sesuai. Sophia mulai melakukan investigasi sendiri dengan menganalisa data internal toko: markdown

- Data transaksi penjualan
- Data stock harian
Saat melakukan analisis lebih dalam, ia menemukan pola yang tidak terlihat di dashboard utama toko. Beberapa SKU yang tidak terlihat ternyata menunjukkan pertumbuhan penjualan yang konsisten. Namun karena kontribusi revenue totalnya masih kecil, sistem tetap menganggap produk-produk tersebut sebagai produk yang tidak perlu diperhatikan. Dan sku tersebut luput dari perhatian dari kasir ketika diinterview, karena sering habis stoknya. Dari penemuan ini, akhirnya Sophia membuat keputusan untuk memperbaiki keadaan tersebut dengan menambah stok dari produk yang ada, dan membuat paket produk tersebut bersama produk lain – yang secara historis sering dibeli barengan. Peserta diharapkan secara teknis menghasikan analisa yang sama dengan Sophia dengan script Python dengan detil (namun tanpa data stock harian) dijelaskan pada bagian berikut ini.

Apa yang Perlu Dibuat dan Dikirimkan?
Peserta perlu mengirimkan satu script Python dengan nama solusi-retail.py yang ketika dijalankan dengan command python solusi-retail.py akan menghasilkan tiga file pada working folder ketika script itu dijalankan: markdown

- retail_insight.xlsx
- rising_star_index.png
- rising_star_actual.png

Script tersebut dikirimkan dalam bentuk email dengan nama subjek Solusi hackathon untuk soal 'HACK-2026-PYTHON-01' Dan hanya satu script yang boleh dikirimkan bersama email tersebut dalam bentuk attachment. File lain, termasuk ketiga file hasil output tidak boleh disertakan dalam email. Dataset yang Disediakan Peserta akan menerima beberapa file dataset yang metadatanya sama dengan yang diolah oleh Sophia, yaitu:

Sales Transaction Data Nama File: data_penjualan.csv
Untuk hackathon kali ini, tidak ada yang perlu dicleansing dari dataset ini, dan untuk penyederhanaan kasus maka periode datanya hanya 30 hari

nomor_struk: nomor struk atau invoice dari transaksi yang dilakukan
tgl_transaksi: merupakan tanggal transaksi dilakukan
kode_produk: kode produk yang dijual
nama_produk: nama produk yang dijual
jumlah_terjual: jumlah / qty dari produk yang dijual
harga: harga satuan produk
total_nilai: adalah total nilai penjualan dari harga dikalikan dengan jumlah terjual
Versi Python dan Library yang Boleh Digunakan

1. python versi 3.10 – 3.14
2. matplotlib versi 3.10.7
3. pandas versi 2.3.1
4. mlxtend versi 0.23.4
5. openpyxl versi 3.1.5

# Eksekusi .py
Untuk eksekusi letakan file solusi-retail.py dan data_penjualan.csv di folder yang sama python solusi-retail.py

