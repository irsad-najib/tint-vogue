# Nama Kelompok

Kelompok 10 - 2223

## Anggota Kelompok

- Nibroos Aurore Majiid H -- 22/494882/TK/54329
- Irsad Najib Eka Putra -- 23/518119/TK/57005
- Rahma Putri Anjani -- 23/519131/TK/57233

## Project

"Project Senior Project TI"

## Instansi

Departemen Teknologi Elektro dan Teknologi Informasi  
Fakultas Teknik  
Universitas Gadjah Mada

---

# Modul Praktikum Senior Project TI

## Nama Produk

tint-vogue

## Jenis Produk

Web-based AI Fashion Recommendation System

## Latar Belakang & Permasalahan

### Latar Belakang:

Pemilihan warna pakaian bukan sekadar masalah estetika, melainkan fenomena fisika interaksi cahaya atau optik [1]. Kulit manusia mengandung pigmen kompleks seperti melanin, hemoglobin, dan karoten yang menciptakan spektrum pantulan unik atau biometric undertone.
Ketika sebuah warna diletakkan dekat dengan wajah, terjadi pantulan cahaya ke permukaan kulit. Warna yang "salah" (tidak harmonis) akan menciptakan bayangan abu-abu atau menonjolkan diskolorasi kulit melalui kontras yang tajam. Sebaliknya, warna yang harmonis menciptakan chromatic balance yang meratakan tekstur kulit secara visual. Dalam hal ini manusia dikategorikan ke dalam palet musim (Spring, Summer, Autumn, Winter) berdasarkan kontras antara iris mata, rambut, dan nilai hue kulit [2].
Analisis color theory lazimnya dilakukan secara manual oleh konsultan profesional menggunakan kain draping. Namun, dengan adanya Computer Vision dapat dapat dilakukan ekstraksi nilai heksadesimal warna kulit secara presisi dan mencocokkannya dengan database palet warna menggunakan AI [3] [4].

### Rumusan Permasalahan:

Inakurasi Persepsi Visual Manusia
Kompleksitas Parameter Biometrik Kulit
Ketidakmampuan E-commerce dalam Personalisasi Kromatik
Eksklusivitas Layanan Konsultasi Profesional

### Daftar Pustaka:

[1] R. R. Anderson and J. A. Parrish, "The optics of human skin," Journal of Investigative Dermatology, vol. 77, no. 1, pp. 13-19, 1981.
[4] M. Spillane, Color Your World. Pennsylvania, PA: PBI Books, 1991.
[5] S. J. Kim and S. J. Cho, "Personal Color Analysis System using Face Image Processing," International Journal of Multimedia and Ubiquitous Engineering, vol. 11, no. 4, pp. 317-326, 2016.
[6] J. Zhao, Y. Li, and J. Chen, "Automatic Personal Color Analysis Based on Computer Vision and Machine Learning," in Proc. International Conference on Image Processing and Pattern Recognition, 2021, pp. 45-58.

## Ide Solusi

### Solusi:

Aplikasi berbasis web yang memberikan rekomendasi outfit (atasan, bawahan, sepatu, dan kombinasi warna) berdasarkan analisis warna kulit (skintone) pengguna dari foto yang diunggah.
Sistem akan:

- Mendeteksi warna kulit dari foto
- Mengklasifikasikan ke kategori skintone (warm, cool, neutral, deep, dll
- Memberikan rekomendasi warna pakaian dan kombinasi outfit yang sesuai
- Menghindari warna yang membuat tampilan terlihat kusam
  Tujuan:
- Mengurangi kesalahan dalam memilih warna pakaian saat belanja online/offline.

### Rancangan Fitur Solusi:

| Fitur                      | Keterangan                                                            |
| :------------------------- | :-------------------------------------------------------------------- |
| Upload Foto Wajah          | User mengunggah foto selfie dengan pencahayaan cukup untuk dianalisis |
| Pilih Occasion             | User memilih tujuan pemakaian outfit                                  |
| Skintone Detection         | Sistem mendeteksi warna kulit menggunakan computer vision             |
| Klasifikasi Undertone      | Mengklasifikasikan ke warm / cool / neutral                           |
| Rekomendasi Warna          | Memberikan warna pakaian yang cocok dengan skintone                   |
| Rekomendasi Outfit Set     | Kombinasi atasan + bawahan + sepatu yang serasi                       |
| Warna yang Harus Dihindari | Memberikan warna yang membuat wajah terlihat pucat/kusam              |

## Analisis Kompetitor

### KOMPETITOR 1

| Kategori             | Deskripsi                                                                      |
| -------------------- | ------------------------------------------------------------------------------ |
| **Nama**             | Dressika                                                                       |
| **Jenis Kompetitor** | Direct                                                                         |
| **Jenis Produk**     | Mobile app berbasis AI yang mengotomasi proses analisis 12-Season Color Theory |
| **Target Customer**  | Fashion Enthusiast                                                             |

---

#### Kelebihan vs Kekurangan

| Kelebihan                                      | Kekurangan                                         |
| ---------------------------------------------- | -------------------------------------------------- |
| - Memiliki database 12 musim warna yang detail | - Antarmuka (UI) cukup kompleks bagi pengguna awam |
| - Fitur Virtual Dressing Room                  | - Akurasi bergantung pada kualitas kamera          |
| - Integrasi dengan rekomendasi makeup          | - Banyak fitur terkunci (Paywall)                  |

---

#### Key Competitive Advantage & Unique Value

Dressika menggunakan sistem 12 sub-musim seperti deep autumn, light spring, cool summer, dll.  
Fitur yang cukup lengkap meliputi virtual makeup, hair color changer, dan smart wardrobe.

### KOMPETITOR 2

| Kategori             | Deskripsi                                                                                                                        |
| -------------------- | -------------------------------------------------------------------------------------------------------------------------------- |
| **Nama**             | Maybelline Shade Finder Experience                                                                                               |
| **Jenis Kompetitor** | Indirect                                                                                                                         |
| **Jenis Produk**     | AI-powered shade finder untuk memilih warna makeup foundation sesuai skin tone                                                   |
| **Target Customer**  | Pengguna makeup yang ingin menemukan foundation/shade yang cocok dengan warna kulit mereka (beauty shoppers, usia remaja–dewasa) |

---

#### Kelebihan vs Kekurangan

| Kelebihan                                                                                       | Kekurangan                                                                                  |
| ----------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------- |
| - Dikelola oleh brand kosmetik besar dengan banyak pengguna loyal.                              | - Fokus hanya pada produk makeup (foundation), bukan rekomendasi outfit atau warna pakaian. |
| - Menggunakan kamera atau upload foto untuk membantu menemukan foundation shade secara virtual. |                                                                                             |
| - Sudah terintegrasi dengan produk makeup Maybelline.                                           |                                                                                             |

---

#### Key Competitive Advantage & Unique Value

Teknologi **virtual try-on** yang sudah terimplementasi secara praktis dalam e-commerce untuk membantu pengguna menemukan shade makeup mereka.

## Lean Canvas

![Lean Canvas ](/file/belajar_program/tint-vogue/src/LeanCanvas-senproKel10.jpeg)
