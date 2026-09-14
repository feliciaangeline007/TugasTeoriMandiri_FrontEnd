# TugasTeoriMandiri_FrontEnd

Repositori kumpulan tugas teori mandiri mata kuliah Pemrograman Front-End oleh **Felicia Angeline** (NIM: **535250029**), Universitas Tarumanagara.

---

## 📁 Struktur Direktori

```text
.
├── index.html                   # Hub navigasi utama tugas mandiri
├── Tugas Mandiri 1/             # Tugas Mandiri 1: Profil Mahasiswa
│   ├── index.html               # Halaman Profil Mahasiswa dengan elemen semantik HTML5
│   └── style.css                # Styling CSS Tugas Mandiri 1
└── Tugas Mandiri 2/             # Tugas Mandiri 2: Praktik Studi Kasus Mini (Kartu Profil)
    ├── avatar.png               # Asset foto profil
    ├── index.html               # Halaman kartu profil responsif
    └── style.css                # CSS Flexbox, Grid, & 2 Media Query Breakpoints
```

---

## 📋 Rincian Tugas

### 1. Tugas Mandiri 1: Profil Mahasiswa
- Menampilkan profil biodata mahasiswa Universitas Tarumanagara.
- Menggunakan struktur semantik HTML5 (`<header>`, `<nav>`, `<article>`, `<footer>`).
- Navigasi internal dan tautan profil GitHub.

### 2. Tugas Mandiri 2: Saatnya Praktik - Studi Kasus Mini
Membuat kartu profil sederhana (foto, nama, deskripsi singkat) yang rapi di layar mobile, tablet, dan desktop.

**Kriteria yang Dipenuhi:**
1. ✅ **Viewport meta tag**: `<meta name="viewport" content="width=device-width, initial-scale=1.0">`.
2. ✅ **Min. 2 breakpoint**:
   - Breakpoint Tablet: `min-width: 640px` (penataan grid metadata 3 kolom & tombol horizontal).
   - Breakpoint Desktop: `min-width: 992px` (tata letak horizontal foto di samping bio).
3. ✅ **Flexbox / Grid**:
   - **Flexbox**: Kontainer utama halaman, alignment isi kartu profil, badge skills, action buttons.
   - **CSS Grid**: Metadata ringkasan profil (Fokus Minat, Angkatan, Lokasi).
4. ✅ **Uji di DevTools**: Layout teruji responsif dan fluid dari mobile (320px+), tablet (768px), hingga layar desktop lebar.
