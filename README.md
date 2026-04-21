# Gallery - dairewahandi

Proyek ini adalah galeri foto minimalis yang dibangun menggunakan **Astro** dan **Tailwind CSS**. Proyek ini menampilkan grid gambar dengan fitur lightbox (zoomin) untuk melihat gambar lebih detail dan opsi untuk mengunduhnya.

## 🚀 Fitur Utama

- **Responsive Image Grid**: Tata letak grid yang menyesuaikan dengan ukuran layar (Mobile, Tablet, Desktop).
- **Interactive Lightbox (Zoomin)**: Klik pada gambar untuk melihat tampilan penuh dengan efek *backdrop blur*.
- **Download Image**: Fitur untuk mengunduh gambar langsung dari tampilan lightbox.
- **Modern Tech Stack**: Menggunakan Astro 6 dan Tailwind CSS 4 untuk performa maksimal.
- **Custom Typography**: Integrasi Google Fonts (IBM Plex Sans & Merriweather).

## 🛠️ Teknologi yang Digunakan

- **Framework**: [Astro](https://astro.build/)
- **Styling**: [Tailwind CSS v4](https://tailwindcss.com/)
- **Icons**: [Astro Icon](https://github.com/natemoo-re/astro-icon) (Iconify & Lucide)
- **Runtime**: Node.js / Bun

## 📂 Struktur Proyek

```text
src/
├── components/     # Komponen UI (Header, Footer, Hero, Zoomin)
├── layouts/        # Layout utama (MainLayout)
├── pages/          # Halaman (Index, PnP)
└── styles/         # Global CSS
```

## 🏁 Memulai

### Prasyarat

Pastikan Anda sudah menginstal Node.js (versi 22 ke atas) atau Bun.

### Instalasi

1. Clone repositori ini:
   ```bash
   git clone <repository-url>
   ```
2. Masuk ke direktori proyek:
   ```bash
   cd gallery
   ```
3. Instal dependensi:
   ```bash
   npm install
   # atau jika menggunakan bun
   bun install
   ```

### Pengembangan

Jalankan server pengembangan lokal:

```bash
npm run dev
# atau
bun dev
```

Buka `http://localhost:4321` di browser Anda.

### Build untuk Produksi

Untuk membuat build produksi:

```bash
npm run build
# atau
bun build
```

Hasil build akan berada di direktori `dist/`.

## 📜 Lisensi

Proyek ini dibuat oleh [dairewahandi](https://github.com/dai-rewahandi).
