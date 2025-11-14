# PT. Cipta Mas Jaya - Website Resmi

Website resmi PT. Cipta Mas Jaya - PJK3 Riksa Uji Tersertifikasi yang memberikan layanan inspeksi keselamatan profesional untuk pesawat angkat, bejana tekan, instalasi listrik dan K3.

🌐 **Live Site:** [https://ciptamasjaya.github.io](https://ciptamasjaya.github.io)

## Tentang

PT. Cipta Mas Jaya adalah Perusahaan Jasa Keselamatan dan Kesehatan Kerja (PJK3) tersertifikasi yang memberikan layanan riksa uji dan inspeksi keselamatan untuk berbagai peralatan dan instalasi industri di seluruh Indonesia.

## Layanan Kami

- **Pesawat Angkat & Angkut** - Riksa uji overhead crane, gantry crane, hoist
- **Pesawat Uap & Bejana Tekan** - Inspeksi boiler, pressure vessel, air receiver
- **Instalasi Listrik & Penangkal Petir** - Pengujian instalasi listrik dan grounding system
- **Instalasi Proteksi Kebakaran** - Inspeksi sistem fire alarm, hydrant, sprinkler
- **Elevator & Eskalator** - Riksa uji elevator, lift, escalator
- **Pesawat Tenaga & Produksi** - Inspeksi mesin produksi, kompresor, generator
- **Pengesahan Gambar Kemnaker** - Layanan pengesahan gambar instalasi K3

## Teknologi

Website ini dibangun menggunakan:

- **Jekyll** - Static site generator
- **GitHub Pages** - Hosting
- **Minimal Mistakes** - Jekyll theme
- **Markdown** - Content format

## Struktur Project

```
.
├── _config.yml          # Konfigurasi Jekyll
├── _data/
│   └── navigation.yml   # Menu navigasi
├── _includes/           # Template includes
├── _layouts/            # Template layouts
├── _pages/              # Halaman statis
├── _posts/              # Artikel blog
├── assets/
│   ├── css/            # Custom CSS
│   ├── images/         # Gambar
│   └── js/             # JavaScript
└── docs/               # Dokumentasi

```

## Development

### Prerequisites

- Ruby (2.7 atau lebih baru)
- Bundler
- Jekyll

### Instalasi

```bash
# Install dependencies
bundle install

# Jalankan local server
bundle exec jekyll serve

# Build site
bundle exec jekyll build
```

### Local Development

Setelah menjalankan `bundle exec jekyll serve`, buka browser di:

```
http://localhost:4000
```

## Menambah Konten

### Membuat Halaman Baru

Buat file baru di folder `_pages/`:

```markdown
---
layout: single
title: "Judul Halaman"
permalink: /url-halaman/
---

Konten halaman di sini...
```

### Membuat Artikel Baru

Buat file baru di folder `_posts/` dengan format nama: `YYYY-MM-DD-judul-artikel.md`

```markdown
---
layout: single
title: "Judul Artikel"
date: 2024-10-30
categories: [kategori]
tags: [tag1, tag2]
---

Konten artikel di sini...
```

## Konfigurasi

File `_config.yml` berisi konfigurasi utama:

- Site information (title, description, url)
- Theme settings (Minimal Mistakes)
- Plugins
- Author information
- Navigation settings
- SEO settings

## Deployment

Website ini otomatis di-deploy ke GitHub Pages setiap kali ada push ke branch `main`.

### Manual Deploy

```bash
# Add changes
git add .

# Commit
git commit -m "Update content"

# Push to GitHub
git push origin main
```

GitHub Pages akan otomatis rebuild dan deploy dalam beberapa menit.

## Kontak

- **Email:** info@ciptamasjaya.co.id
- **Telepon:** 08568258841
- **Website:** [www.ciptamasjaya.co.id](https://www.ciptamasjaya.co.id)

## License

© 2024 PT. Cipta Mas Jaya. All rights reserved.

---

**Keselamatan Kerja Dimulai dari Peralatan yang Terawat dan Teruji**
