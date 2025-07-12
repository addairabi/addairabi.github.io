---
layout: post
title: "Layout dan navigation"
date: 2025-03-13
---

##  HTML Layout dan Navigation

###  Apa Itu Layout dan Navigation?

**Layout** dalam HTML adalah cara kita menyusun elemen-elemen dalam halaman web agar terlihat terstruktur dan mudah dibaca. Biasanya kita menggunakan elemen seperti:
- `<div>`: wadah umum untuk mengelompokkan elemen
- `<header>`: bagian atas halaman (biasanya berisi logo, judul, dan menu)
- `<main>`: isi utama dari halaman
- `<footer>`: bagian bawah halaman (biasanya berisi copyright, kontak, dll.)
- `<section>`, `<article>`, `<aside>`: untuk pengelompokan konten secara semantik

Sementara itu, **navigation** (navigasi) adalah menu atau tautan yang membantu pengguna berpindah antar halaman atau bagian dalam website. Biasanya dibungkus dalam elemen `<nav>`.

---

### Contoh Layout dan Navigation

<!DOCTYPE html>
<html>
  <head>
    <title>Contoh Layout & Navigasi</title>
  </head>
  <body>

    <header>
      <h1>Website Saya</h1>
      <nav>
        <a href="#beranda">Beranda</a> |
        <a href="#tentang">Tentang</a> |
        <a href="#kontak">Kontak</a>
      </nav>
    </header>

    <main>
      <section id="beranda">
        <h2>Selamat Datang</h2>
        <p>Ini adalah halaman utama dari website saya.</p>
      </section>

      <section id="tentang">
        <h2>Tentang Saya</h2>
        <p>Saya sedang belajar HTML & Web Development.</p>
      </section>
    </main>

    <footer>
      <p>© 2025 Website Saya</p>
    </footer>

  </body>
</html>

## Kesimpulan
- Elemen layout seperti <header>, <main>, <footer>, <section>, dan <div> digunakan untuk menyusun tampilan halaman agar rapi dan semantik.
- Navigasi dibuat dengan tag <nav> dan isi link <a> di dalamnya.
- Struktur layout yang baik memudahkan pengguna dan pengembang memahami isi halaman.
- Kombinasi layout dan navigasi adalah fondasi dari semua website modern.
- Gunakan elemen semantik untuk membuat kode HTML kamu lebih terstruktur dan mudah dipahami — baik oleh manusia maupun mesin pencari (SEO)!