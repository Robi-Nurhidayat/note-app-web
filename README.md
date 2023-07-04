# note-app-web

tampilkan nya mirip admin panel
sebelah kiri ada sidebar atas topbar tengah konten nya.
sidebar ada menu:
1. Dashboard
2. Buat catatan
3. Profile

Model nya
1. Auth / user -> email, username, pwd -> pake json web token
2. Catatan -> nama, jumlah pengeluaran, tanggal, kategori pengeluaran (Makan, belanja, Pembayaran) -> tambahin lg


[Trello](https://trello.com/invite/b/sdZXjPZv/ATTIa0c99287438f555a90326622aec5095fAB7EFF80/toko-online-note-app)


Run Laravel:
Masuk Folder -> backend
```bash
cd backend
```

```bash
php artisan serve
```

Migrate Database

```bash
php artisan migrate:refresh --seed
```