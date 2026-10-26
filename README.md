
Versi HTML + CSS + JavaScript **tanpa Bootstrap dan tanpa PHP**, untuk tugas bagian 2.a Dashboard Pengelola, 2.b Eksplorasi Ruang, dan 2.c Form Maintenance.

## Menjalankan

- Ekstrak folder `atlas_ruang_tanpa_php`.
- Buka folder di VS Code (`File > Open Folder`).
- Klik dua kali `index.html`, atau buka lewat Live Server.
- Tidak perlu Laragon, Apache, MySQL, atau impor SQL.

## Cara tes benturan

1. Buka **Blokir & Perawatan**, pilih A-101, atur jadwal misalnya besok pukul 08:00–10:00, masukkan alasan lalu simpan.
2. Buka **Uji Benturan Booking**, pilih A-101 pada tanggal yang sama pukul 09:00–11:00. Booking **ditolak** karena bertabrakan.
3. Coba booking 10:00–11:00 untuk A-101. Booking bisa masuk karena tidak tumpang tindih.
4. Jika booking sudah masuk, maintenance pada jam yang sama juga ditolak.

## Perhatian penting

Ini **prototype single-browser**. Data disimpan dalam `localStorage` browser (bukan MySQL), sehingga tidak tersinkron antar komputer atau browser dan bukan validasi server yang aman untuk penggunaan nyata. Konten dan tombol berfungsi lokal untuk demonstrasi. Untuk integrasi dengan situs anggota 1 dan 2 pada banyak komputer, diperlukan backend bersama sesuai aturan tugas/dosen.

Folder `assets/css/` berisi desain, `assets/js/` berisi seluruh interaksi, `index.html` berisi struktur utama. Tidak ada password/API key.
