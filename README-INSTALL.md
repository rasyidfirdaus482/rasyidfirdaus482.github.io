# KuroTech Company Profile — GitHub Pages Static

File ini dibuat agar tetap berjalan di GitHub Pages tanpa framework, tanpa build step, dan tanpa backend.

## Struktur file

```text
/
├── index.html
├── styles.css
└── script.js
```

## Cara pasang

1. Backup file lama terlebih dahulu.
2. Copy `index.html`, `styles.css`, dan `script.js` ke root repository GitHub Pages Anda.
3. Commit dan push ke branch yang dipakai GitHub Pages.
4. Buka ulang website, lalu hard refresh browser: `Ctrl + F5`.

## Catatan penting

- Fitur bahasa ID/EN sudah berjalan via JavaScript dan menyimpan pilihan user di `localStorage`.
- Tidak ada dependency CDN, jadi aman untuk GitHub Pages.
- Tombol WhatsApp memakai nomor dari website lama: `+62 831 6796 1562`.
- Email memakai alamat dari website lama: `info@kurotech.id`.
- Karena ini static site, form kontak tidak dibuat memakai backend. CTA diarahkan ke WhatsApp dan email.

## Bagian yang bisa Anda ubah cepat

- Nomor WhatsApp: cari `6283167961562` di `index.html`.
- Email: cari `info@kurotech.id` di `index.html`.
- Copywriting bahasa: edit object `translations` di `script.js`.
- Warna utama: edit variable CSS di bagian `:root` pada `styles.css`.
