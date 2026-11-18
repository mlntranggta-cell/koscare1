KOSCARE — WEBSITE PRESENTASI

Isi:
- index.html: halaman presentasi KosCare
- assets/style.css: desain responsif dan animasi
- assets/script.js: scroll reveal, smooth scroll, tombol kembali ke atas, menu mobile

CARA MEMBUKA DI LAPTOP:
1. Ekstrak folder KosCare_Presentasi.
2. Buka index.html menggunakan Chrome.
3. Gulir ke bawah untuk melihat animasi setiap bagian.

CARA MENGHUBUNGKAN KE WEBSITE UTAMA:
1. Setelah website aplikasi KosCare di InfinityFree aktif, salin URL-nya.
2. Buka assets/script.js.
3. Isi nilai KOSCARE_APP_URL dengan URL aplikasi, contoh:
   const KOSCARE_APP_URL = "https://alamat-aplikasi-koscare.infinityfreeapp.com";
4. Simpan file dan uji tombol Login / Buka KosCare.

CARA PUBLIKASI KE NETLIFY:
1. Buka Netlify dan login.
2. Pilih Add new site / Deploy manually (nama menu dapat berubah).
3. Unggah folder hasil ekstrak yang berisi index.html dan folder assets.
4. Tunggu proses deploy selesai, lalu buka URL Netlify yang diberikan.

Catatan:
- Ini website presentasi statis, jadi tidak membutuhkan database.
- Aplikasi utama PHP + MySQL tetap di InfinityFree.
- Pastikan mengunggah folder yang berisi index.html di bagian teratas (root).

UPDATE: Bagian 'Perjalanan Membangun KosCare' sudah ditambahkan dengan 6 tahapan pengerjaan dan animasi saat digulir.
