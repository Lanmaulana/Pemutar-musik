# 🎵 Pemutar Musik Modern

Sebuah aplikasi pemutar musik front-end yang simpel dan modern, dibuat dengan teknologi web dasar: HTML, CSS, dan JavaScript. Proyek ini dilengkapi dengan antarmuka yang bersih, daftar putar interaktif, dan animasi latar belakang yang dinamis untuk pengalaman pengguna yang lebih menarik.

## 📸 Tampilan (Preview)

[![IMG-20250613-024302.jpg](https://i.postimg.cc/YS0dTtjd/IMG-20250613-024302.jpg)](https://postimg.cc/8F8d6QRv)

## ✨ Fitur-fitur

-   **Antarmuka Modern**: Desain gelap yang terinspirasi dari Spotify, nyaman di mata.
-   **Kontrol Pemutaran**: Fungsi dasar seperti Putar, Jeda, Lagu Berikutnya, dan Lagu Sebelumnya.
-   **Progress Bar Interaktif**: Menampilkan progres lagu dan dapat diklik untuk melompat ke bagian tertentu dari lagu.
-   **Tampilan Durasi**: Menunjukkan waktu lagu yang sedang berjalan dan total durasi.
-   **Daftar Putar (Playlist)**: Menampilkan semua lagu yang tersedia. Lagu yang sedang aktif akan ditandai.
-   **Pemilihan Lagu**: Klik pada lagu mana pun di daftar putar untuk langsung memutarnya.
-   **Latar Belakang Dinamis**:
    -   Latar belakang blur yang otomatis berganti sesuai dengan sampul album lagu yang diputar.
    -   Animasi partikel melayang yang modern untuk menambah estetika.
-   **Responsive**: Tampilan yang menyesuaikan dengan baik pada perangkat mobile.

## 🛠️ Teknologi yang Digunakan

Proyek ini dibangun murni menggunakan teknologi web front-end dasar, tanpa memerlukan framework atau library yang kompleks.

-   **HTML5**: Untuk struktur dasar konten.
-   **CSS3**: Untuk styling, layouting (Flexbox), dan animasi (`@keyframes`).
-   **JavaScript (Vanilla JS)**: Untuk semua logika fungsionalitas pemutar musik, manipulasi DOM, dan pembuatan partikel animasi.
-   **Font Awesome**: Untuk ikon-ikon pada tombol kontrol.

## 🚀 Instalasi dan Penggunaan

Untuk menjalankan proyek ini di komputer lokal Anda, ikuti langkah-langkah berikut:

1.  **Clone atau Unduh Proyek**
    ```bash
    # Jika Anda menggunakan Git, clone repositori ini
    git clone [https://github.com/Lanmaulana/pemutar-musik](https://github.com/Lanmaulana/pemutar-musik)
    ```
    Atau cukup unduh file ZIP dan ekstrak.

2.  **Siapkan File Musik dan Gambar**
    -   Letakkan semua file lagu Anda (format `.mp3`) di dalam folder `music/`.
    -   Letakkan semua file gambar sampul album (format `.png` atau `.jpg`) di dalam folder `images/`.

3.  **Kustomisasi Daftar Lagu**
    Buka file `script.js` dan edit array `songs` untuk menambahkan atau mengubah daftar lagu Anda. Pastikan path `src` dan `cover` sudah benar.

    ```javascript
    const songs = [
        {
            title: 'Judul Lagu Anda',
            artist: 'Nama Artis',
            src: 'music/nama-file-lagu.mp3',
            cover: 'images/nama-file-gambar.png'
        },
        {
            title: 'Judul Lagu Lainnya',
            artist: 'Artis Lain',
            src: 'music/lagu-lain.mp3',
            cover: 'images/cover-lain.png'
        }
        // ... tambahkan lagu lainnya di sini
    ];
    ```

4.  **Jalankan Aplikasi**
    Tidak perlu instalasi server. Cukup buka file `index.html` langsung di browser favorit Anda (seperti Google Chrome, Firefox, atau Edge).

## 📁 Struktur Folder
Struktur folder yang disarankan agar aplikasi berjalan dengan baik:
```
/
├── index.html
├── css/
│   └── style.css
├── js/
│   └── script.js
├── ms/                 # Folder untuk file musik
│   ├── Justin Bieber - Baby ft.mp3
│   ├── NEFFEX - Get Through.mp3
│   └── night changes - one direction nadine abigail.mp3
└── img/                # Folder untuk gambar sampul
    ├── Justin.jpg
    ├── Nadine.jpg
    └── Neffex.jpg
```

Dibuat oleh **Maulana Developer**.
