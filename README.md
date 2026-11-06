# Saka Timepiece — Website Demo

Website demo katalog jam vintage Saka Timepiece. Dioptimalkan untuk iPhone, tetap rapi di desktop.

## Isi folder

- `index.html` — seluruh halaman (tampilan, gaya, dan fungsi ada di satu file)
- `assets/hourglass.png` — ikon logo jam pasir
- `assets/favicon.png`, `assets/apple-touch-icon.png` — ikon tab browser dan ikon saat disimpan ke layar utama iPhone
- `.nojekyll` — file kosong agar GitHub Pages menampilkan file apa adanya

## Cara upload ke GitHub Pages (gratis)

1. Masuk ke github.com, klik tombol **+** di kanan atas, pilih **New repository**.
2. Beri nama, misalnya `saka-timepiece`. Pilih **Public**, lalu klik **Create repository**.
3. Di halaman repository baru, klik tautan **uploading an existing file**.
4. Seret **seluruh isi** folder ini (bukan foldernya) ke halaman upload: `index.html`, folder `assets`, `README.md`, dan `.nojekyll`.
   - Kalau `.nojekyll` tidak ikut terseret (file berawalan titik kadang tersembunyi), lewati saja. Website tetap jalan tanpanya.
5. Klik **Commit changes**.
6. Buka **Settings → Pages**. Di bagian **Branch**, pilih `main` dan folder `/ (root)`, lalu klik **Save**.
7. Tunggu 1–2 menit. Alamat website muncul di halaman yang sama, formatnya `https://NAMA-AKUN.github.io/saka-timepiece/`.

## Yang perlu diganti sebelum dipakai sungguhan

- **Nomor WhatsApp** — cari baris `const WA = "6281234567890"` di `index.html`, ganti dengan nomor asli (format 62..., tanpa tanda +).
- **Produk** — daftar jam ada di bagian `const P = [ ... ]`. Semua nama, harga, dan detail di sana adalah contoh.
- **Gambar produk** — saat ini jam digambar otomatis sebagai ilustrasi. Untuk foto asli, ganti dengan file gambar milik toko.
- **Tautan media sosial** — di bagian footer dan menu, tautan masih `#`.

## Fitur yang sudah berfungsi

- Menu samping, pencarian langsung, filter merek dan jenis mesin, urutan harga/tahun
- Wishlist (tersimpan di browser pengunjung)
- Keranjang dengan progress bar gratis ongkir dan saran tali jam
- Detail produk dalam panel geser dari bawah, tombol **Tanya via WhatsApp**
- Checkout mengirim ringkasan pesanan ke WhatsApp
- Arsip jam terjual, panduan merek, formulir email (belum terhubung ke layanan email)
