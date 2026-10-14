# 🛡️ K3Learn - Platform Pembelajaran & Kuis K3 Interaktif

K3Learn adalah aplikasi web edukasi modern untuk pembelajaran Keselamatan dan Kesehatan Kerja (K3) dengan sistem kuis interaktif dan skoring otomatis.

![K3Learn Preview](assets/images/hero-worker.jpg)

## ✨ Fitur Utama

- **📚 Katalog Kursus K3 Komprehensif:** Modul APD, K3 Dasar, Tanggap Darurat, Identifikasi Bahaya, Keselamatan Api, First Aid, dan Keselamatan Kimia.
- **📖 Pembelajaran Interaktif:** Modul materi lengkap dengan studi kasus nyata, tips keselamatan, dan checklist standar APD.
- **⏱️ Kuis Interaktif 10 Soal:** Dilengkapi dengan timer per soal (30 detik), visual progress bar, sistem lompat nomor soal, serta dialog konfirmasi submit.
- **📊 Skoring & Evaluasi Otomatis:** Perhitungan nilai real-time, lingkaran persentase animasi, status kelulusan (Lulus/Belum Lulus), review kunci jawaban dengan pembahasan lengkap, serta rekomendasi materi tindak lanjut.
- **🎨 Desain Modern & Responsif:** Tema warna Navy Blue & Safety Orange, tipografi Plus Jakarta Sans, glassmorphism card, dan mobile-friendly layout.

## 🚀 Struktur Direktori

```text
├── index.html              # Landing Page / Beranda
├── pages/
│   ├── kursus.html         # Halaman Katalog Kursus K3
│   ├── materi.html         # Halaman Detail Materi Pembelajaran (APD)
│   ├── kuis.html           # Halaman Kuis Interaktif 10 Soal
│   └── hasil.html          # Halaman Hasil Skoring & Evaluasi
├── assets/
│   ├── css/
│   │   └── style.css       # Design System & Styling K3Learn
│   ├── js/
│   │   ├── main.js         # Navigasi & interaktivitas global
│   │   ├── kuis.js         # Logika kuis, timer, & state jawaban
│   │   └── hasil.js        # Perhitungan skor, review jawaban, & grafik
│   └── images/             # Ilustrasi & visual materi keselamatan
└── README.md
```

## 💻 Cara Menjalankan Secara Lokal

Cukup buka file `index.html` langsung di browser, atau jalankan server lokal:

```bash
# Menggunakan Python
python -m http.server 8080

# Atau menggunakan npx serve
npx serve .
```

Akses di browser melalui: `http://localhost:8080`

## ☁️ Deploy ke Vercel

Proyek ini siap di-deploy langsung ke [Vercel](https://vercel.com):

1. Masuk ke [Vercel Dashboard](https://vercel.com/dashboard)
2. Klik **Add New...** -> **Project**
3. Hubungkan akun GitHub dan pilih repository `HelloWorld-ui0/quiz-k3`
4. Di bagian **Framework Preset**, biarkan **Other**
5. Klik **Deploy**! 🚀
