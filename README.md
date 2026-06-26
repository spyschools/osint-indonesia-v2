# 🇮🇩 OSINT Indonesia V2

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python">
  <img src="https://img.shields.io/badge/OSINT-Public%20Sources-success?style=for-the-badge">
  <img src="https://img.shields.io/badge/Platform-Linux-orange?style=for-the-badge">
  <img src="https://img.shields.io/github/license/spyschools/osint-indonesiav2?style=for-the-badge">
</p>

<p align="center">
<b>Open Source Intelligence Toolkit Indonesia</b><br>
Mencari informasi publik berdasarkan <b>NIK</b> dan <b>Nomor HP</b> menggunakan sumber <b>OSINT (Open Source Intelligence)</b>.
</p>

---

## ✨ Fitur

* 🔍 Pencarian berdasarkan **NIK**
* 📱 Pencarian berdasarkan **Nomor HP**
* 🌐 Menggunakan sumber **OSINT Publik**
* 📄 Otomatis membuat laporan **report.html**
* ⚡ Cepat, ringan, dan mudah digunakan
* 🐍 Dibuat menggunakan Python 3

---

## ⚠️ Disclaimer

> **Tools ini TIDAK mengambil data dari database ilegal ataupun hasil kebocoran data.**

Seluruh informasi yang ditampilkan berasal dari **Open Source Intelligence (OSINT)** atau sumber informasi publik yang tersedia di internet.

Project ini dibuat hanya untuk:

* 🎓 Edukasi
* 🔬 Penelitian (Research)
* 🛠️ Pengembangan
* 🧪 Pengetesan

**Pengguna bertanggung jawab penuh atas penggunaan tools ini.**

---

# 📦 Instalasi

## Install dependensi

```bash
sudo apt update && sudo apt install python3-pip
```

Upgrade pip

```bash
pip3 install --upgrade pip
```

Install library

```bash
pip3 install requests bs4 colorama
```

---

# 🚀 Menjalankan

Clone repository

```bash
git clone https://github.com/spyschools/osint-indonesia-v2.git
```

Masuk ke folder project

```bash
cd osint-indonesia-v2
```

Berikan izin eksekusi

```bash
chmod +x osint_v2.py
```

Jalankan

```bash
python3 osint_v2.py 3275124308050003 +6281234567890
```

---

# 📋 Output

Hasil pencarian akan ditampilkan pada:

✅ Terminal

dan otomatis disimpan menjadi:

```text
report.html
```

---

# 📖 Contoh

```bash
python3 osint_v2.py 3275124308050003 +6281234567890
```

Output

```text
====================================
        OSINT INDONESIA V2
====================================

NIK        : 3275124308050003
Nomor HP   : +6281234567890

Status     : Data ditemukan dari sumber OSINT publik

Laporan berhasil disimpan ke report.html
```

---

# 📁 Struktur Project

```text
osint-indonesiav2/
│
├── osint_v2.py
├── report.html
├── README.md
└── requirements.txt
```

---

# 🛡️ Legal Notice

Project ini:

* ❌ Tidak menyimpan database pribadi
* ❌ Tidak menggunakan database bocor
* ❌ Tidak mengambil data dari sumber ilegal
* ✅ Hanya mengumpulkan informasi dari sumber publik (OSINT)

Harap gunakan tools ini secara bertanggung jawab dan sesuai dengan hukum yang berlaku.

---

# 🤝 Kontribusi

Kontribusi sangat diterima.

Silakan membuat:

* ⭐ Star
* 🍴 Fork
* 🐛 Issue
* 🔧 Pull Request

untuk membantu pengembangan project ini.

---

# ⭐ Dukungan

Jika project ini bermanfaat, jangan lupa berikan **Star** pada repository ini.

```text
⭐ Star repository ini untuk mendukung pengembangan Tools OSINT Indonesia V2.
```

---

<p align="center">

### ❤️ Made with Python by SpySchools

*"Knowledge comes from Open Source Intelligence."*

</p>
