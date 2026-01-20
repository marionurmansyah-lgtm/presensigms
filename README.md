# 🏢 Presensi Online GMS (Klase Auto Graha)

Aplikasi manajemen kehadiran (absensi) berbasis web yang ringan, responsif, dan terintegrasi dengan Google Sheets sebagai database.

## ✨ Fitur Utama
* **📍 Geofencing & GPS**: Memastikan karyawan melakukan absen di lokasi yang telah ditentukan.
* **📸 Upload Bukti**: Fitur kompresi gambar otomatis untuk unggah surat izin/sakit/cuti tanpa membebani kuota server.
* **📊 Dashboard Admin**: Monitoring kehadiran real-time, statistik keterlambatan, dan manajemen data karyawan.
* **📱 Mobile Friendly**: Antarmuka yang dioptimalkan untuk perangkat smartphone (Android/iOS).
* **☁️ Google Apps Script Integration**: Menggunakan infrastruktur Google untuk penyimpanan data yang aman dan gratis.

## 🛠️ Teknologi yang Digunakan
- **Frontend**: HTML5, CSS3 (Tailwind CSS), JavaScript (Vanilla)
- **Maps**: OpenStreetMap & Nominatim API
- **Backend**: Google Apps Script (JavaScript)
- **Database**: Google Sheets

## 🚀 Cara Instalasi (Development)
1. Clone atau download repository ini.
2. Pastikan Anda sudah memiliki URL Deployment dari **Google Apps Script**.
3. Buka file `index.html` dan ganti variabel `API_URL` dengan URL milik Anda:
   ```javascript
   const API_URL = 'https://script.google.com/macros/s/AKfycbzbzJfAys4lMRv3THcA8NwKfThmhRiwRVEmZIdqxDfFXGB4LI3wPdvE3ikwM5DuzDn8Vw/exec';
