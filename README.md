# PGSD UPI Serang — salinan offline (statis)

Salinan statis untuk uji coba lokal, dibuat dari halaman yang disimpan via SingleFile.
Sebuah bilah navigasi ditambahkan di atas tiap halaman agar navigasi antar-halaman jalan offline.

## Buka lokal
    python3 -m http.server 8080
    # lalu buka http://localhost:8080

## Deploy GitHub Pages
    git init && git add . && git commit -m "Salinan offline PGSD UPI Serang"
    git branch -M main
    git remote add origin git@github.com:dika-81/NAMA-REPO.git
    git push -u origin main
    # Settings > Pages: Source = main / root

Catatan: fitur dinamis (form kontak, pencarian, ganti bahasa) tidak berfungsi di versi statis.
Beberapa video/peta mungkin tidak tampil offline. Halaman = beranda (index.html).
