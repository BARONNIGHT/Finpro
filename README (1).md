# Panduan Kustomisasi Proyek Web Anda

FinPro - https://g.co/gemini/share/24d8e133ee1a

Dokumen ini memberikan petunjuk langkah demi langkah untuk melakukan kustomisasi dasar seperti mengganti nama aplikasi web, detail kredit/hak cipta, favicon, dan deskripsi meta untuk SEO.

---

## Daftar Isi
- [1. Informasi Dasar Proyek](#1-informasi-dasar-proyek)
- [2. Langkah-Langkah Kustomisasi](#2-langkah-langkah-kustomisasi)
  - [2.1 Mengganti Nama Aplikasi Web](#21-mengganti-nama-aplikasi-web)
  - [2.2 Mengganti Teks Kredit dan Hak Cipta](#22-mengganti-teks-kredit-dan-hak-cipta)
  - [2.3 Mengganti Deskripsi Meta untuk SEO](#23-mengganti-deskripsi-meta-untuk-seo)
  - [2.4 Mengubah Tautan Media Sosial atau Kontak](#24-mengubah-tautan-media-sosial-atau-kontak)
- [3. Catatan Penting](#3-catatan-penting)

---

## 1. Informasi Dasar Proyek

| Kustomisasi            | Deskripsi                                                           | File yang Perlu Diperiksa                                   |
|------------------------|---------------------------------------------------------------------|--------------------------------------------------------------|
| **Nama Web/Aplikasi**  | Nama yang muncul di judul browser dan header utama.                | `index.html`, template header, file konfigurasi.             |
| **Kredit/Hak Cipta**   | Informasi pemilik hak cipta (biasanya di footer).                   | `index.html` atau template footer.                           |
| **Ikon Favicon**       | Ikon kecil di tab browser.                                          | Folder `assets/` atau tag `<link>` di `index.html`.          |
| **Deskripsi Meta**     | Deskripsi untuk keperluan SEO.                                      | Tag `<meta name="description">` di `index.html`.             |

---

## 2. Langkah-Langkah Kustomisasi

Ikuti langkah-langkah berikut untuk menyesuaikan proyek Anda.

---

### 2.1 Mengganti Nama Aplikasi Web

Nama ini muncul di tab browser dan berpengaruh pada SEO.

1. Buka file `index.html`.
2. Cari tag `<title>` di dalam `<head>`:

```html
<head>
    <meta charset="UTF-8">
    <!-- GANTI BAGIAN INI -->
    <title>Nama Web Lama | Slogan Keren</title>
</head>
```

3. Ganti dengan judul baru:

```html
<title>Nama Web Baru Anda | Solusi Terbaik</title>
```

---

### 2.2 Mengganti Teks Kredit dan Hak Cipta

1. Buka `index.html` atau `footer.html`.

2. Cari struktur footer seperti berikut:

```html
<footer class="text-center py-4">
    <p>© 2024 Nama Pengembang Lama. Semua Hak Cipta Dilindungi.</p>
</footer>
```

3. Ubah menjadi:

```html
<footer class="text-center py-4">
    <p>© 2025 [Nama Perusahaan/Anda]. Dibuat dengan ❤.</p>
</footer>
```

---

### 2.3 Mengganti Deskripsi Meta untuk SEO

1. Buka `index.html`.
2. Cari tag meta berikut:

```html
<meta name="description" content="Ini adalah deskripsi lama tentang web kami, layanan hebat, dan produk-produk kami.">
```

3. Ganti dengan deskripsi baru:

```html
<meta name="description" content="Platform resmi [Nama Web Baru]. Menyediakan [Layanan Utama] dengan kualitas dan performa terbaik.">
```

---

### 2.4 Mengubah Tautan Media Sosial atau Kontak

Contoh sebelum:

```html
<a href="https://twitter.com/PengembangLama" target="_blank" class="sosial-icon">
    Twitter
</a>
```

Contoh sesudah:

```html
<a href="https://twitter.com/AkunAndaYangBaru" target="_blank" class="sosial-icon">
    Twitter
</a>
```

---

## 3. Catatan Penting

- **Backup sebelum mengedit:** Selalu buat salinan proyek Anda.  
- **Perhatikan huruf besar/kecil (case sensitive):** Terutama saat mengubah nama file dan direktori.  
- **Tes setelah perubahan:** Buka proyek di browser untuk memastikan semuanya berjalan dengan benar.

---


---

# 4. Tutorial Implementasi Web App ke Gemini Canvas

## 4.1 Persiapan Ide & Aset
Pastikan Anda memiliki:
- Deskripsi singkat tujuan web app
- Aset seperti gambar/logo
- Contoh data jika diperlukan

## 4.2 Membuat Proyek di Gemini Canvas
1. Buka **gemini.google.com/canvas**.
2. Buat Canvas baru.
3. Berikan prompt:
   ```
   Buat prototype satu-halaman web app untuk [nama app]
   dengan fitur: [daftar fitur], gunakan HTML + CSS + JS.
   ```
4. Gemini akan menampilkan kode serta preview.

## 4.3 Mengedit & Merefine Kode
- Gunakan instruksi lanjutan seperti:
  - “Tambahkan validasi input”
  - “Ubah desain jadi lebih modern”
- Preview akan diperbarui otomatis.

## 4.4 Menyalin Kode & Mengekspor
- Salin seluruh kode yang diberikan Gemini.
- Simpan sebagai `index.html`.

## 4.5 Deploy ke Hosting Gratis
**Opsi A — Netlify**
1. Masuk ke Netlify.
2. Pilih *Deploy manually*.
3. Drag & drop file `index.html`.

**Opsi B — GitHub Pages**
1. Buat repo baru.
2. Upload `index.html`.
3. Aktifkan GitHub Pages di Settings.

## 4.6 Integrasi Kembali ke Gemini
Anda bisa:
- Menempelkan link live site ke Canvas
- Menempelkan kembali kode untuk diedit ulang

## 4.7 Checklist Penting
- Cek error di Console browser
- Pastikan layout responsif mobile
- Optimalkan meta tag & SEO

