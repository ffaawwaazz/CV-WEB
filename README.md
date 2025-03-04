# CV-WEB Rafif Fawwaz Kartika

Kode HTML ini adalah struktur dasar untuk halaman web sederhana yang berfungsi sebagai CV (Curriculum Vitae) online dari **Rafif Fawwaz Kartika**. Berikut adalah penjelasan cara kerja kode ini:

---

### **1. Struktur Dasar HTML**
Dokumen ini dimulai dengan deklarasi `<!DOCTYPE html>` yang menandakan bahwa ini adalah dokumen HTML5.

- `<html lang="id">` → Menentukan bahwa bahasa utama halaman ini adalah **Bahasa Indonesia**.
- `<head>` → Berisi informasi meta seperti **encoding karakter**, **pengaturan tampilan responsif**, **judul halaman**, dan **CSS untuk styling**.
- `<body>` → Berisi semua elemen tampilan yang terlihat oleh pengguna.

---

### **2. CSS untuk Tampilan**
Di dalam `<style>` pada `<head>`, terdapat CSS yang mengatur tampilan halaman:

- **Warna latar belakang halaman** → `background-color: #6070d3;` (biru keunguan).
- **Container utama** (`.container`) 
  - Lebar **60%** dari layar.
  - Latar belakang **putih** dengan **padding** untuk memberikan ruang di dalamnya.
  - **Box-shadow** untuk efek bayangan agar terlihat lebih modern.
- **Header** (`.header`)  
  - Gambar profil dibuat **lingkaran** dengan `border-radius: 50%`.
  - Teks nama dibuat lebih besar dengan `<h1>`.
- **Bagian judul tiap section** (`.section h2`)  
  - Warna latar abu-abu gelap (`#9f9f9f`) dengan **teks putih** agar kontras.
  - Padding untuk memberikan ruang antar elemen.

---

### **3. Isi Halaman (Body)**
Halaman ini dibagi menjadi beberapa **section** dalam `.container`:

#### **a. Header Profil**
```html
<div class="header">
    <img src="FP2.jpeg" alt="Foto Profil">
    <h1>Rafif Fawwaz Kartika</h1>
    <p>Email: fawwazkartika@gmail.com | Telepon: 0813-7070-5335</p>
    <p>Alamat: Sidoarjo, Indonesia</p>
</div>
```
- **Menampilkan foto profil** dari file `FP2.jpeg`.
- **Menampilkan nama lengkap** dalam `<h1>`.
- **Menampilkan kontak** seperti email, nomor HP, dan alamat.

---

#### **b. Tentang Saya**
```html
<div class="section">
    <h2>Tentang Saya</h2>
    <p>Saat ini, saya sedang menempuh pendidikan di Institut Teknologi Sepuluh Nopember (ITS) ...
</div>
```
- Berisi **deskripsi singkat tentang diri** dan tujuan karier.

---

#### **c. Pengalaman Organisasi**
```html
<div class="section">
    <h2>Pengalaman Organisasi</h2>
    <ul>
        <li><strong>Expert Staff Finance - SCHEMATICS 2025</strong> (Jan 2025 - Sekarang)</li>
        <li><strong>Staff Finance - INI LHO ITS 2025</strong> (Oct 2024 - Jan 2025)</li>
    </ul>
</div>
```
- Menggunakan **list `<ul>`** untuk menampilkan daftar organisasi yang diikuti.
- **Teks organisasi dibuat tebal** dengan `<strong>`.

---

#### **d. Pendidikan**
```html
<div class="section">
    <h2>Pendidikan</h2>
    <ul>
        <li><strong>Rekayasa Kecerdasan Artifisial - ITS</strong> (2023 - Sekarang)</li>
    </ul>
</div>
```
- Menampilkan **riwayat pendidikan** dalam format daftar.

---

#### **e. Keahlian**
```html
<div class="section">
    <h2>Keahlian</h2>
    <ul>
        <li>Leadhership, Team Work, Time Management</li>
        <li>Finance & Enterpreneur Mind</li>
    </ul>
</div>
```
- Daftar **kemampuan dan keterampilan** yang dimiliki.

---

### **4. Cara Kerja Secara Keseluruhan**
1. **Browser membaca file HTML** → Memahami struktur halaman.
2. **Browser merender tampilan** dengan menerapkan **CSS styling**.
3. **Foto, teks, dan daftar informasi ditampilkan** sesuai dengan HTML yang telah ditulis.
4. **Interaksi pengguna**: Pengguna bisa membaca informasi yang tersedia, tetapi halaman ini statis (tidak ada interaktivitas seperti tombol atau form).
