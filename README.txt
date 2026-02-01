
CHEAT PANEL NEON — Siap Deploy ke GitHub Pages (Panduan Lengkap untuk Pemula, iPhone)

Isi folder:
- index.html
- manifest.json
- service-worker.js
- /icons/icon-192.png
- /icons/icon-512.png

Langkah-langkah upload ke GitHub Pages pakai iPhone (Safari):
1) Siapkan akun GitHub. Kalau belum ada, buka https://github.com dan daftar.
2) Buat repository baru:
   - Di GitHub, tap tombol '+' -> 'New repository'.
   - Nama repo: misalnya 'cheat-panel-neon'.
   - Pilih 'Public' dan centang 'Add a README' lalu 'Create repository'.
3) Upload file ke repo (metode lewat browser Safari – gunakan Desktop Site untuk pengalaman terbaik):
   A. Di Safari buka repo yang baru saja dibuat.
   B. Tap ikon 'aA' di kiri address bar -> pilih 'Request Desktop Website' (atau 'Request Desktop Site').
   C. Klik tombol 'Add file' -> 'Upload files'.
   D. Di halaman upload, tap 'Choose your files' -> pilih 'Browse'. 
      - Jika kamu membuka ZIP, ekstrak dulu di app 'Files' (tekan lama pada ZIP -> pilih 'Uncompress').
      - Masuk ke folder hasil ekstrak, pilih semua file (index.html, manifest.json, service-worker.js, folder icons) — biasanya tekan 'Select' lalu tap file satu per satu.
   E. Setelah semua file terpilih, scroll ke bawah -> 'Commit changes' (isi pesan commit jika mau) -> 'Commit changes'.
4) Aktifkan GitHub Pages:
   - Di repo, tap tab 'Settings' -> scroll ke bagian 'Pages' (atau cari 'Pages' di Settings).
   - Pada 'Source', pilih branch 'main' (atau 'master' jika itu default) dan folder '/ (root)' lalu 'Save'.
   - Tunggu ~1 menit. GitHub akan menampilkan URL: https://USERNAME.github.io/REPOSITORY_NAME/
5) Buka URL tersebut di Safari iPhone. Jika tampil, sekarang PWA siap diinstall:
   - Tap icon 'Share' (kotak dengan panah) -> 'Add to Home Screen' -> konfirmasi.
   - Sekarang ada ikon app di Home Screen; buka, dan app akan berjalan full-screen (tanpa address bar) dengan offline support.
6) Troubleshooting cepat:
   - Jika halaman kosong setelah deploy: tunggu 1-2 menit lalu refresh.
   - Jika icon tidak muncul saat 'Add to Home Screen': pastikan manifest.json benar dan icons tersedia di root/icons.
   - Kalau upload via browser bermasalah, coba install 'GitHub' app dan lakukan fork/commit via app, atau gunakan layanan hosting alternatif (Netlify, Vercel).
7) Alternatif mudah (tanpa GitHub):
   - Netlify Drop: buka https://app.netlify.com/drop, login, lalu drag & drop folder hasil ekstrak. Netlify langsung hosting dan berikan URL. (Perlu akun GitHub atau email).

Kalau kamu mau, aku bisa bantu langkah demi langkah saat kamu upload (kamu bilang saat mulai, dan aku pandu tiap langkah).
