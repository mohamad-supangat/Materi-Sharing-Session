# Teknologi Frontend Moderan (SPA)

### Berkenalan dengan arsitektur dan teknik di dalam Frontend Aplikasi Web di era Moderen

Mohamad Supangat
18 Juli 2025

## Kenapa memilih menggunakan dan membuat aplikasi WEB ?

- Dapat di akses dengan mudah di semua perangkat
- Mudah dalam pembaruan aplikasi (ketika ada bug bisa langsung di perbaiki di server dan pengguna bisa langsung melihat perubahan)
- Efisiensi Biaya (Biaya dalam pengembangan, maintenance, (Hardware, Personil))
- Skalabilitas (Infrastruktur yang mudah di expansi dan juga penambahan penambahan fitur)
- Pemeliharaan Terpusat (Semua Pembatasan di Server)

## Tantangan Umum Dalam Pembuatan Aplikasi Web

- Performa Aplikasi (waktu loading yang lama, Ukuran Aplikasi yang terlalu besar)
- Kompleksitas dalam menyimpan data (data yang berubah dan juga bagaimana interaksi dengan pengguna)
- Kompatibilitas Jenis Perangkat
- Search Engine Optimization / SEO (mendapatkan peringkat yang lebih tinggi di hasil pencarian mesin seperti Google)

## Problem Statement

Secara umum infrastruktur aplikasi terutama aplikasi web terbagi menjadi 2, backend dan frontend.

1. Backend: Integrasi dengan Central Database
2. Frontend: UI / UX, antarmuka dan interaksi dari pengguna

Frontend merupakan bagian yang paling penting dikarenakan sebagai daya tarik aplikasi untuk pengguna,

Tujuan Pembelajaran:

1. Menjadi titik awal Teknologi apa yang akan kita gunakan untuk membangun aplikasi
2. Sejauh mana jangkauan / interaksi pengguna dengan aplikasi yang kita kembangkan

## Single Page Application (SPA)

### Apa itu SPA ?

SPA merupakan salah satu User Experience dalam sebuah aplikasi web dimana sebagai pengguna kita tidak perlu melakukan load seluruh halaman ketika ketika kita melakukan klik suatu link / melakukan sebuah aksi

### Apa perbedaan SPA dengan web biasa ?

- **Pemuatan Halaman:**
  - **SPA:** Hanya memuat satu kali halaman HTML saat pertama kali diakses. Setelah itu, semua konten dan tampilan diperbarui secara dinamis oleh JavaScript tanpa memuat ulang seluruh halaman dari server.
  - **MPA:** Setiap kali pengguna berpindah ke halaman baru (misalnya, mengklik tautan atau mengirim formulir), seluruh halaman HTML baru akan dimuat ulang dari server.

- **Pengalaman Pengguna (User Experience):**
  - **SPA:** Memberikan pengalaman yang lebih mulus dan cepat karena tidak ada "blink" atau jeda saat halaman dimuat ulang. Terasa lebih responsif seperti aplikasi desktop.
  - **MPA:** Ada jeda atau _loading screen_ setiap kali halaman baru dimuat, yang bisa membuat pengalaman terasa kurang mulus.

- **Peran Server:**
  - **SPA:** Setelah pemuatan awal, server bertindak lebih seperti API (Application Programming Interface) yang hanya menyediakan data (misalnya dalam format JSON), bukan seluruh halaman HTML.
  - **MPA:** Server bertanggung jawab untuk merender dan mengirimkan seluruh halaman HTML baru untuk setiap permintaan.

- **Pengembangan:**
  - **SPA:** Cenderung lebih kompleks dalam pengembangan karena membutuhkan lebih banyak logika sisi klien (client-side) dan penggunaan framework JavaScript seperti React, Angular, atau Vue.js.
  - **MPA:** Umumnya lebih sederhana dalam struktur karena setiap halaman adalah entitas terpisah.

- **SEO (Search Engine Optimization):**
  - **SPA:** Secara tradisional memiliki tantangan SEO karena konten dimuat secara dinamis oleh JavaScript, yang mungkin tidak selalu diindeks dengan baik oleh crawler search engine (meskipun ini telah banyak ditingkatkan dengan teknik seperti pre-rendering atau SSR/Server-Side Rendering).
  - **MPA:** Lebih ramah SEO secara _out-of-the-box_ karena setiap halaman memiliki URL unik dan konten HTML lengkap yang mudah diindeks oleh search engine.
