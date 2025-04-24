---
layout: post
title: "Instalasi Ruby dan Jekyll"
date: 2025-02-20
---

📘 Panduan Instalasi Jekyll dan Ruby untuk Pemula
💎 Mengenal Ruby & Jekyll
Ruby: Bahasa pemrograman dinamis yang powerfull

Jekyll: Tools untuk generate website statis secara otomatis, sering dipakai untuk:

Blog pribadi

Dokumentasi proyek

Website portofolio

Situs GitHub Pages

🔧 Langkah Persiapan
1. Instalasi Ruby
▶ Untuk Pengguna Windows
Download installer terbaru di: https://rubyinstaller.org

Rekomendasi pilih versi Ruby+DevKit (misal: Ruby 3.1.4)

Tips instalasi:

Centang "Add Ruby to PATH"

Jalankan ridk install saat diminta

Pilih opsi 1-3 saat instalasi MSYS2

▶ Untuk Pengguna macOS
Buka Terminal dan jalankan:

bash
Copy
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
brew install ruby
▶ Untuk Pengguna Linux (Debian/Ubuntu)
bash
Copy
sudo apt update
sudo apt install ruby-full build-essential
Tambahkan ini di .bashrc:

bash
Copy
export GEM_HOME="$HOME/gems"
export PATH="$HOME/gems/bin:$PATH"
Lalu jalankan:

bash
Copy
source ~/.bashrc
⚡ Instalasi Jekyll
Setelah Ruby sukses terinstall:

bash
Copy
gem install jekyll bundler
💡 Tips: Jika ada error permission, coba dengan:

bash
Copy
sudo gem install jekyll bundler
🚀 Memulai Proyek Jekyll Pertama
Buat proyek baru:

bash
Copy
jekyll new blog-saya
cd blog-saya
Jalankan server development:

bash
Copy
bundle exec jekyll serve
Buka browser ke:

Copy
http://localhost:4000
🔍 Troubleshooting:

Jika ada error dependency, coba:

bash
Copy
bundle install
🧰 Perintah Penting
bash
Copy
ruby -v          # Cek versi Ruby
jekyll -v        # Cek versi Jekyll
jekyll serve     # Jalankan server (auto reload)
jekyll build     # Build situs ke folder _site
🎉 Selamat!
Anda sudah berhasil:

Menginstall Ruby dan Jekyll

Membuat proyek Jekyll pertama

Menjalankan server lokal

Langkah selanjutnya:

Eksplor tema Jekyll di jekyllthemes.org

Pelajari struktur folder Jekyll

Deploy ke GitHub Pages

Happy Coding! 👨💻👩💻