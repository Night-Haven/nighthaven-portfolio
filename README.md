# NightHaven Portfolio

Portofolio fotografi minimalis yang menampilkan keindahan malam, tekstur urban, dan momen-momen berharga melalui lensa.

## Fitur Utama
- **Desain Minimalis & Profesional:** Fokus pada karya visual dengan palet warna gelap yang estetik.
- **Galeri Responsif:** Grid foto yang menyesuaikan dengan berbagai ukuran layar (Mobile, Tablet, Desktop).
- **Performa Tinggi:** Menggunakan optimasi format **WebP** dan **Lazy Loading** untuk akses instan.
- **Animasi Sinematik:** Didukung oleh library **AOS** (Animate On Scroll) untuk transisi yang halus.
- **Slideshow Latar Belakang:** Menampilkan siluet karya terbaik pada halaman Beranda.

## Struktur Folder
- `index.html`: Halaman utama dengan animasi slideshow siluet.
- `gallery.html`: Koleksi lengkap karya fotografi dalam format grid.
- `about.html`: Profil fotografer, pengalaman (termasuk HIMASADA), dan kontak.
- `luts.html`: Halaman untuk preset warna (Coming Soon).
- `assets/optimized/`: Penyimpanan aset gambar yang telah dikompresi.

## Teknologi yang Digunakan
- **Frontend:** HTML5, CSS3, JavaScript.
- **Library:** [AOS](https://michalsnik.github.io/aos/) (Animate On Scroll).
- **Optimasi:** Python (Pillow Library) untuk kompresi gambar otomatis.
- **Hosting:** GitHub Pages.

## Cara Mengelola Proyek
1. **Optimasi Foto:** Pastikan setiap foto baru dikompresi ke format `.webp` menggunakan script Python yang tersedia.
2. **Update Galeri:** Tambahkan elemen `<div class="card">` baru di `gallery.html` dengan jalur gambar yang benar.
3. **Deploy:** Lakukan `commit` dan `push` ke branch `main` untuk memperbarui website secara otomatis.

---
© 2024 **NightHaven** - Capturing the essence through my lens.
