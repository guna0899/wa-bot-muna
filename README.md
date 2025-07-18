# 🤖 WhatsApp Bot Muna-kun 🤖

Selamat datang di repositori Bot WhatsApp Muna-kun! Ini adalah proyek bot multifungsi yang dibuat dengan Node.js dan Baileys, dirancang untuk menjadi asisten pribadi dan teman seru di grup WhatsApp.

---

## ✨ Fitur Andalan

Berikut adalah daftar fitur stabil yang saat ini tersedia:

* **`.menu`**: Menampilkan daftar semua perintah yang tersedia dengan tampilan yang rapi.
* **`.s`**: Mengubah gambar atau video (maks 5 detik) menjadi stiker berkualitas tinggi. Cukup kirim media dengan caption atau balas media yang sudah ada.
* **`.tt <link>`**: Mendownload video TikTok tanpa watermark, langsung dikirim ke chat.
* **`.ai <pertanyaan>`**: Mengajukan pertanyaan apa saja ke AI Google Gemini dan mendapatkan jawaban cerdas langsung di WhatsApp.
* **`.tagall`**: Mention semua anggota yang ada di dalam grup, cocok untuk pengumuman penting.

---

## 🚀 Cara Instalasi & Menjalankan

Ikuti langkah-langkah berikut untuk menjalankan bot ini di komputermu.

### 1. Prasyarat (Wajib Diinstall Dulu!)

Pastikan komputermu sudah terinstall tiga hal ini:

1.  **[Node.js](https://nodejs.org/en)** (Pilih versi LTS)
2.  **[Git](https://git-scm.com/downloads)**
3.  **[FFmpeg](https://ffmpeg.org/download.html)** (Penting untuk fitur stiker!)

> #### **Cara Cepat Install FFmpeg di Windows:**
> 1.  Download dari sini: **[gyan.dev](https://www.gyan.dev/ffmpeg/builds/)** (pilih `ffmpeg-release-full.7z`).
> 2.  Ekstrak file `.7z` itu ke lokasi yang gampang, misalnya `C:\ffmpeg`.
> 3.  Buka "Edit the system environment variables" di Windows Search.
> 4.  Klik `Environment Variables...` -> di bagian `System variables`, pilih `Path` -> `Edit...`.
> 5.  Klik `New`, lalu masukkan path ke folder `bin` di dalam folder ffmpeg-mu. Contoh: `C:\ffmpeg\bin`.
> 6.  Klik `OK` di semua jendela, lalu **restart komputermu**.

### 2. Clone Repository
Buka terminal atau Git Bash, lalu salin proyek ini ke komputermu:
```bash
git clone [https://github.com/guna0899/wa-bot-muna.git](https://github.com/guna0899/wa-bot-muna.git)
cd wa-bot-muna

Ganti guna0899 dan wa-bot-muna dengan username dan nama repositori GitHub-mu jika berbeda.

3. Install Dependensi
Setelah masuk ke dalam folder proyek, jalankan perintah ini untuk menginstall semua "alat" yang dibutuhkan bot:

npm install

4. Jalankan Bot
Untuk memulai bot, jalankan perintah berikut di terminal:

node index.js

5. Scan QR Code
Saat bot berjalan pertama kali, akan muncul QR Code di terminal. Scan QR Code tersebut menggunakan aplikasi WhatsApp di HP-mu (Setelan > Perangkat tertaut > Tautkan perangkat) untuk menghubungkan bot.

Selamat