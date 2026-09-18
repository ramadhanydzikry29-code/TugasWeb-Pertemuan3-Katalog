# DZIKRYSTORE — Katalog Laptop Responsif

## Deskripsi

DZIKRYSTORE adalah website katalog laptop sederhana yang dibuat untuk memenuhi tugas **Pemrograman Web Pertemuan 3**.

Website ini menampilkan beberapa produk laptop dari berbagai merek seperti ASUS, Acer, Lenovo, HP, dan Axioo.

Website dibuat dengan konsep **mobile-first**, menggunakan **Bootstrap 5** dan CSS untuk menghasilkan tampilan yang responsif pada berbagai ukuran perangkat.

---

## Fitur Website

Website memiliki beberapa bagian utama:

### 1. Navbar Responsif

Navbar menyediakan beberapa menu, yaitu:

- Beranda
- Produk
- Tentang
- Kontak
- Menu hamburger pada perangkat mobile

Navbar dapat menyesuaikan tampilan berdasarkan ukuran layar.

### 2. Hero Section

Hero section berisi:

- Judul utama website
- Deskripsi katalog
- Tombol Lihat Produk
- Tombol Tentang Toko
- Informasi jumlah model laptop
- Informasi breakpoint
- Informasi bahwa website responsif
- Gambar laptop

### 3. Katalog Produk

Website memiliki **8 produk laptop**.

Setiap card produk memiliki:

- Gambar produk
- Merek laptop
- Nama produk
- Deskripsi produk
- Spesifikasi
- Harga
- Tombol Detail

Produk yang ditampilkan berasal dari beberapa merek seperti:

- MacBook
- Acer
- Lenovo
- HP
- Axioo

### 4. Tentang DZIKRYSTORE

Bagian ini berisi penjelasan singkat mengenai website dan penerapan konsep responsive design pada katalog produk.

### 5. Form Kontak

Form kontak memiliki beberapa input:

- Nama
- Email
- Pesan
- Tombol Kirim Pertanyaan

### 6. Footer

Footer berisi:

- Copyright DZIKRYSTORE
- Keterangan tugas Pemrograman Web

---

## Requirements yang Diterapkan

Website dibuat berdasarkan requirements tugas, yaitu:

1. **Mobile-first approach**
2. **Minimal 3 breakpoint**
3. **Grid responsif**
4. **Card produk**
5. **Navbar responsif dengan hamburger pada mobile**
6. **Responsive images**
7. **Penggunaan `clamp()` untuk typography**
8. **Footer**
9. **Dokumentasi testing pada 3 breakpoint**

---

## Responsive Grid

Grid produk menggunakan Bootstrap 5 dengan sistem responsive grid.

Pada ukuran layar yang berbeda, jumlah kolom produk akan menyesuaikan:

- **Mobile:** 1 kolom
- **Tablet:** 2 kolom
- **Laptop/Desktop:** 3 kolom
- **Layar besar:** 4 kolom

Dengan demikian, tampilan katalog tetap rapi pada berbagai ukuran layar.

---

## Breakpoint

Website menggunakan beberapa breakpoint untuk menyesuaikan tampilan:

### 1. Desktop

Digunakan untuk tampilan layar desktop dengan ukuran besar.

Pada ukuran ini:

- Hero menggunakan dua kolom
- Produk dapat ditampilkan dalam beberapa kolom
- Navbar tampil secara horizontal

### 2. Tablet

Pada ukuran tablet:

- Hero berubah menjadi satu kolom
- Bagian About dan Contact menyesuaikan menjadi satu kolom
- Jumlah kolom produk menyesuaikan ukuran layar

### 3. Mobile

Pada ukuran smartphone:

- Navbar berubah menjadi menu hamburger
- Hero menggunakan satu kolom
- Produk ditampilkan satu kolom
- Ukuran typography menyesuaikan layar
- Tombol dan elemen lainnya menyesuaikan lebar layar

---

## Dokumentasi Testing Responsive

Testing dilakukan menggunakan tiga ukuran tampilan untuk memastikan website dapat menyesuaikan ukuran layar.

### 1. Testing Desktop

Ukuran layar:

**1920 × 1080**

Hasil testing:

- Navbar tampil horizontal
- Hero tampil dalam dua kolom
- Produk tampil dalam beberapa kolom
- Gambar dan card produk tampil dengan baik
- Footer tampil dengan baik

**Screenshot:**
![alt text](darilaptop.png)
![alt text](darilaptop-1.png)
Tambahkan screenshot hasil testing desktop di sini.

```text
![Testing Desktop](screenshot/desktop.png)