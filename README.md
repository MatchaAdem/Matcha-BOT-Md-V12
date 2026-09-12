
# Matcha BOT Md V12 (Telegram Bot)

Selamat datang di repositori resmi **Matcha BOT Md V12**. Ini adalah proyek bot Telegram berbasis *open source* yang dikembangkan dan dimodifikasi untuk memberikan performa maksimal tanpa batasan.

## ✨ Keunggulan Utama

* 🔓 **No Encryption (No Enc):** Kode 100% terbuka, bebas dibaca, dipelajari, dan dimodifikasi sesuai kreativitas Anda dari versi awal hingga versi V12 ini.
* 🚀 **No Limit API:** Berjalan tanpa batasan limit API, memastikan respon bot tetap cepat dan stabil saat digunakan
  
* 📱 **Multi-Device (Md):** ada downloader tiktok, AI Ramah + AI Toxic, serta pengoperasian yang fleksibel karena di setel pake settingan javascript

## 🛠️ Fitur & Menu Bot

* **Automated Group Manager:** Mengatur dan menjaga grup Telegram dari gangguan spam.
* **Smart Commands:** Kumpulan perintah kustom yang responsif untuk membantu kebutuhan pengguna.
* **Open Source Framework:** Struktur kode yang ramah bagi pemula yang ingin belajar memodifikasi skrip bot.

---
*Dibuat serta dikembangkan langsung oleh developer **MatchaAdem**.*

## 🚀 Cara run skrip di termux:

Bagi lu yang mau jalanin script **Matcha BOT Md V12** ini di HP lu pake aplikasi **Termux**, lu harus ikutin perintah di bawah ini langkah demi langkah:

### 1. Persiapan Awal Sistem
Ketik perintah ini satu per satu di Termux untuk memperbarui sistem dan menginstal *tools* yang dibutuhkan:
```bash
pkg update && pkg upgrade -y
pkg install git nodejs ffmpeg unzip -y
```
(ini yg belum pernah install node sm upgrade termux, kalo yg udah pernah dah kaga perlu lagi)

### 2. Cara Kloning script dari github ini ke termux lu:
Ikutin intruksi ini biar lu bisa pasang ke Termux:
```bash
git clone https://github.com/MatchaAdem/Matcha-BOT-Md-V12.git
```
Terus buat folder nya di termux lu:
```bash
cd Matcha-BOT-Md-V12
```

### 3. Extract file ke termux:
Karena file utama berbentuk ZIP, lu kudu ekstrak dulu coyy file nya pake perintah ini:
```bash
unzip "Matcha BOT Md v12 (No Enc No Limit API).zip"
```

### 4. Instalasi Dependensi & Menjalankan Bot
Masuk ke folder hasil ekstrak (sesuaikan nama foldernya yang lu buat kalo lu ngemasukin sendiri script yang udah di clone), terus lu install semua modul dulu buat jalanin bot nya disini:
```bash
npm install
node index.js
```

### 5. Pastiin klon-an github nya udah masuk ke dalam termux lu:
Pake command ini dan cari sendiri skrip nya di termux lu:
```bash
$ ls
```

> ⚠️ **Catatan penting buat lu:** Jangan lupa lu ganti/masukin token bot tele dan semua hal yang wajib lu masukin ke dalam di dalem file  (`index.js`). kalo udah ganti? langsung ae coyy eksekusi pake perintah ini🔥 `node index.js`
>
> ❗ **DILARANG KERAS MENJUAL-BELIKAN/KLAIM SCRIPT/MENGUBAH LISENSI KEPEMILIKAN YANG ADA DI SOURCE, TOLONG HARGAI PENCIPTA SCRIPT INI**
