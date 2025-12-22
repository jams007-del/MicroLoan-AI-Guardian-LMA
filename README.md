# MicroLoan-AI-Guardian-LMA

MicroLoan-AI-Guardian-LMA adalah aplikasi contoh untuk manajemen pinjaman kecil dengan sinkronisasi realtime menggunakan Firebase.

Demo (Firebase):  
https://9000-firebase-studio-1766117780432.cluster-yylgzpipxrar4v4a72liastuqy.cloudworkstations.dev

## Fitur utama
- Sinkronisasi realtime menggunakan Firebase Realtime Database / Firestore  
- Dashboard sederhana untuk melihat data pinjaman  
- Form input pinjaman dengan validasi dasar

## Menjalankan secara lokal (contoh Node.js / Vite)
1. Clone repository:
   ```bash
   git clone https://github.com/jams007-del/MicroLoan-AI-Guardian-LMA.git
   ```
2. Masuk folder project:
   ```bash
   cd MicroLoan-AI-Guardian-LMA
   ```
3. Install dependency:
   ```bash
   npm install
   ```
4. Jalankan:
   ```bash
   npm run dev
   ```
5. Buka browser ke `http://localhost:3000` (atau port yang muncul di terminal)

## Catatan penting
- Jangan commit kredensial (file `.env`, API keys). Pastikan file sensitif ada di `.gitignore`.  
- Demo Firebase hanya untuk testing. Untuk production, gunakan Firebase Hosting atau deploy sesuai panduan.  
- Jika butuh panduan langkah demi langkah di workstation Anda, sebutkan OS (Linux / Windows).
