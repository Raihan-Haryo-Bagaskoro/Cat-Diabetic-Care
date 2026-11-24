# Cat-Diabetic-Care
Aplikasi web pemantauan harian terapi diabetes kucing berbasis 7 hari dengan akses QR Code tag kalung, lampiran media kondisi klinis, dan portal evaluasi khusus dokter hewan.

# 🐱 CAT DIABETIC CARE

**CAT DIABETIC CARE** adalah aplikasi web pemantauan harian terapi diabetes pada kucing selama siklus 7 hari yang menghubungkan pemilik kucing (*owner*) dengan dokter hewan penanggung jawab.

## ✨ Fitur Utama

### 1. Portal Pemilik Kucing (Pasien)
* **Akses 2 Jalur (Link & QR Tag Kalung):** Anggota keluarga di rumah dapat memindai QR Code yang dicetak/diukir pada kalung kucing untuk langsung membuka kartu pemantauan tanpa mencari tautan ulang.
* **Jadwal Otomatis 7 Hari (24 Jam):** Formulir aktif mulai keesokan hari setelah registrasi pasca diagnosa, otomatis menyimpan laporan dan berpindah ke formulir hari berikutnya setiap 24 jam hingga Hari ke-7.
* **Berhenti Otomatis pada Hari Kontrol:** Setelah 7 hari selesai, sistem menampilkan pengingat jadwal kontrol klinik dan menjeda formulir sementara menunggu keputusan dokter.
* **Checklist Harian Terstruktur:** Pencatatan nafsu makan pagi & malam (habis/sisa), jam & dosis insulin (`U`), total air minum (`ml`), frekuensi pipis, kondisi BAB, tingkat aktivitas, serta indikator **Tanda Bahaya**.
* **Lampiran Foto & Video:** Pemilik dapat melampirkan foto atau video kondisi klinis (seperti muntah atau luka/borok) langsung pada catatan harian.

### 2. Portal Dokter Hewan (Terisolasi per Dokter)
* **Privasi Pasien Terisolasi:** Setiap dokter memiliki akun masing-masing dan hanya dapat mengakses serta memantau pasien kucing yang terdaftar di bawah namanya.
* **Otoritas Kendali Pemantauan (`[Mulai Pantau]` & `[Stop Pantau]`):** Dokter memegang kendali penuh untuk memulai siklus pemantauan minggu berikutnya setelah pemeriksaan kontrol atau menghentikan pemantauan apabila kondisi kucing telah stabil.
* **Grafik Tren & Evaluasi Medis:** Visualisasi tren konsumsi air minum dan frekuensi pipis harian (H1–H7) disertai kolom arahan medis yang langsung tampil di layar pemilik kucing.

## 🚀 Cara Menjalankan & Deploy
Aplikasi ini dibangun menggunakan HTML5, Tailwind CSS, Lucide Icons, dan QRCode.js tanpa memerlukan server backend lokal (`XAMPP`).
1. Unggah `index.html` ke repository GitHub.
2. Aktifkan **GitHub Pages** pada branch `main` folder `/root`.
3. Akses tautan publik yang dihasilkan melalui browser HP Android maupun iOS.
