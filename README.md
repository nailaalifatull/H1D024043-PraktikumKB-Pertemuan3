# H1D024043-PraktikumKB-Pertemuan3

Repository ini berisi implementasi **Logika Fuzzy (Fuzzy Logic)** menggunakan Python dengan library `scikit-fuzzy` untuk menyelesaikan dua studi kasus pada praktikum Kecerdasan Buatan.
- **Nama**  : Naila Alifatul Mabruroh 
- **NIM**   : H1D024043  
- **Mata Kuliah** : Kecerdasan Buatan  
- **Praktikum** : Pertemuan 3  

Program ini menggunakan:
- Python  
- numpy  
- scikit-fuzzy  
- matplotlib  

## STUDI KASUS 1  
### Penentuan Stok Makanan

#### Deskripsi
Sistem ini digunakan untuk menentukan jumlah stok makanan berdasarkan kondisi penjualan menggunakan metode logika fuzzy.

#### Input
- Barang Terjual (0 – 100)  
- Permintaan (0 – 300)  
- Harga Item (0 – 100.000)  
- Profit (0 – 4.000.000)  

#### Output
- Stok Makanan (0 – 1000)  

#### Metode
- Fuzzy Mamdani  
- Membership Function: Segitiga (`trimf`) dan Trapesium (`trapmf`)  
- Menggunakan 6 aturan fuzzy  

#### Contoh Input

```text
Barang Terjual = 80
Permintaan = 255
Harga Item = 25.000
Profit = 3.500.000
```

#### Output
Program menghasilkan jumlah stok makanan yang direkomendasikan berdasarkan perhitungan fuzzy.

---

## STUDI KASUS 2  
### Penentuan Kepuasan Pelayanan

#### Deskripsi
Sistem ini digunakan untuk menentukan tingkat kepuasan pelayanan berdasarkan kualitas layanan menggunakan logika fuzzy.

#### Input
- Kejelasan Informasi (0 – 100)  
- Kejelasan Prasyarat (0 – 100)  
- Kemampuan Petugas (0 – 100)  
- Ketersediaan Sarana & Prasarana (0 – 100)  

#### Output
- Kepuasan Pelayanan (0 – 400)  

#### Metode
- Fuzzy Mamdani  
- 3 kategori input:
  - Tidak Memuaskan  
  - Cukup Memuaskan  
  - Memuaskan  
- 5 kategori output:
  - Tidak Memuaskan  
  - Kurang Memuaskan  
  - Cukup Memuaskan  
  - Memuaskan  
  - Sangat Memuaskan  
- Menggunakan 81 aturan fuzzy  

#### Contoh Input

```text
Kejelasan Informasi = 80
Kejelasan Prasyarat = 60
Kemampuan Petugas = 50
Ketersediaan Sarpras = 90
```

#### Output
Program menghasilkan tingkat kepuasan pelayanan berdasarkan perhitungan fuzzy.

## Visualisasi
Program menampilkan:
- Grafik membership function  
- Visualisasi hasil output fuzzy  


---

## 👩‍💻 Author

**Naila Alifa**  
Mahasiswa Informatika UNSOED
