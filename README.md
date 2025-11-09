# 🗞️ Landing Page News

Landing Page **News** adalah halaman arahan (landing) sederhana untuk menampilkan informasi portal berita. Dibuat menggunakan **HTML**, **CSS**, dan **Bootstrap**, fokus pada tampilan yang **ringan**, **responsif**, dan mudah dikembangkan.

> Repo: `YoKYa/Landing-Page-News`

---

## ✨ Fitur Utama

- ✅ **Responsive layout** (mobile–tablet–desktop) berbasis Bootstrap Grid
- ✅ **Hero section** (headline/cta)
- ✅ **Section kategori/fitur** untuk highlight topik berita
- ✅ **Daftar artikel ringkas** (judul, tanggal, ringkasan)
- ✅ **Footer** sederhana (tautan singkat, sosmed)
- ✅ **Tanpa framework JS** — murni HTML, CSS, Bootstrap

> *Opsional:* dapat ditambahkan integrasi API berita (mis. NewsAPI) dengan JavaScript tanpa mengubah struktur utama.

---

## 🧱 Teknologi

- **HTML5**
- **CSS3**
- **Bootstrap 5** (Grid, Utilities, Components)

---

## 🚀 Cara Menjalankan

Tidak memerlukan server. Cukup buka `index.html` di browser.

```bash
# 1) Clone repository
git clone https://github.com/YoKYa/Landing-Page-News.git
cd Landing-Page-News

# 2) Buka file index.html
# Double-click index.html atau (opsional) gunakan Live Server di VS Code
```

---

## 📂 Struktur Direktori (Ringkas)

```
Landing-Page-News/
├─ index.html
├─ /assets
│  ├─ /css/        # stylesheet kustom (mis. style.css)
│  ├─ /img/        # logo/hero/thumbnail
│  └─ /js/         # (opsional) script tambahan
└─ README.md
```

> Penamaan folder bebas, pastikan path di `index.html` sesuai.

---

## 🧩 Kustomisasi Cepat

1. Ubah **judul/brand** di hero (file `index.html`)
2. Atur **warna/typography/spacing** di `assets/css/style.css`
3. Ganti **gambar/ikon** di `assets/img/`
4. *(Opsional)* Tambahkan `assets/js/news.js` untuk fetch data API

**CDN Bootstrap (contoh di `<head>`):**

```html
<!-- Bootstrap CSS -->
<link
  href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css"
  rel="stylesheet">

<!-- Bootstrap JS (opsional untuk komponen interaktif) -->
<script
  src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js">
</script>
```

---

## 📄 Lisensi

Proyek ini bersifat **open-source**. Silakan gunakan, modifikasi, dan kembangkan sesuai kebutuhan.

---

Jika repo ini bermanfaat, jangan lupa beri ⭐ di GitHub!
