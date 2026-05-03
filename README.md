# 🌹 Kisah Abadi Website — Panduan Deploy ke cPanel

## Struktur File
```
kisahabadi_website/
├── index.html              ← Halaman Utama
├── .htaccess               ← Konfigurasi server (penting!)
├── assets/
│   ├── foto1.png
│   ├── foto2.jpg
│   ├── foto3.jpg
│   └── video.mp4
└── pages/
    ├── booking.html        ← Halaman Booking
    ├── konsultasi.html     ← Halaman Konsultasi
    ├── layanan.html        ← Halaman Layanan / About
    └── admin.html          ← Admin Panel (RAHASIA)
```

## Cara Upload ke cPanel

1. **Login ke cPanel** hosting kamu
2. Buka **File Manager**
3. Masuk ke folder `public_html`
4. Upload semua file dari zip ini
5. Pastikan struktur folder sama persis

## Admin Panel

Akses: `https://yourdomain.com/pages/admin.html`

| Credential | Value |
|---|---|
| Username | `kisahabadi_admin` |
| Password | `KA@dm1n#2025!` |

⚠️ **GANTI PASSWORD** setelah pertama kali login!

## Fitur Website

- ✅ Halaman utama dengan video loop (tanpa kontrol)
- ✅ 3 tombol di atas video: Booking Now, Konsultasi, Layanan
- ✅ Halaman Booking → kirim via WhatsApp otomatis
- ✅ Halaman Konsultasi → 3 jenis konsul dengan form accordion
- ✅ Halaman Layanan → lengkap sesuai PDF (paket, T&C, FAQ, album)
- ✅ FAQ dengan animasi accordion
- ✅ Admin panel untuk lihat & kelola konsultasi masuk
- ✅ Animasi halaman: loader, page transition, scroll reveal
- ✅ Custom cursor
- ✅ Fully responsive (mobile-friendly)
- ✅ .htaccess untuk performa & keamanan

## Setelah Live

1. Uncomment baris HTTPS di `.htaccess` setelah SSL aktif
2. Ganti `yourdomain.com` di .htaccess dengan domain asli kamu
3. Update link Instagram & TikTok di semua halaman
4. Ganti nomor WA jika perlu: `628999097703`

---
*Kisah Abadi — Wedding Content Creator · 2025*
