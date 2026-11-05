# SonicForge Studio Pro v1.5 — Paket Deploy Vercel (Web & Android PWA)

Paket ini sudah dikonfigurasi lengkap agar langsung siap di-deploy ke **Vercel** dan bisa diinstal sebagai aplikasi (**PWA**) di **Android** maupun **PC (Windows/Mac/Linux)**.

## Isi File di Dalam ZIP Ini
1. `index.html` — Aplikasi utama SonicForge Studio Pro (otomatis terbuka saat link Vercel diakses).
2. `sonicforge_studio_web.html` — Salinan file mandiri aplikasi.
3. `manifest.json` — Konfigurasi Web App Manifest untuk instalasi PWA di Android & PC.
4. `sw.js` — Service Worker agar aplikasi bisa diinstal ke Layar Utama (Home Screen) dan berjalan secara offline.
5. `icon-192.png`, `icon-512.png`, `favicon.ico` — Ikon resmi aplikasi beresolusi tinggi.
6. `vercel.json` & `package.json` — Konfigurasi otomatis server Vercel.

---

## Cara Membuat Link Pribadi di Vercel (Sangat Mudah)

### Cara 1: Lewat GitHub + Dashboard Vercel (Direkomendasikan)
1. Ekstrak (Unzip) file `SonicForge_Studio_Pro_Vercel_PWA.zip` ini ke sebuah folder di PC/HP Anda.
2. Buat repository baru (bisa Private atau Public) di GitHub, lalu upload semua isi folder hasil ekstrak tadi (`index.html`, `manifest.json`, `sw.js`, `vercel.json`, `icon-192.png`, `icon-512.png`, dll).
3. Buka [https://vercel.com/new](https://vercel.com/new), pilih repository GitHub tersebut, lalu klik **Deploy**.
4. Dalam ~10 detik, link pribadi Anda (misalnya `https://sonicforge-anda.vercel.app`) langsung aktif!

### Cara 2: Langsung Drag & Drop / Vercel CLI Tanpa GitHub
1. Ekstrak (Unzip) file ZIP ini ke sebuah folder.
2. Jika menggunakan terminal di PC:
   - Jalankan `npx vercel` di dalam folder tersebut.
   - Ikuti petunjuk singkat di layar, maka Vercel akan langsung memberikan link `https://...vercel.app` milik Anda.

---

## Cara Instal Aplikasi dari Link Vercel Anda
- **Di Android (Chrome / Edge)**: Buka link Vercel Anda, lalu klik tombol **`📲 Instal Aplikasi (PC / Android)`** di pojok kanan atas aplikasi (atau ketuk menu pojok kanan atas Chrome `⋮` -> **Instal aplikasi / Tambahkan ke Layar utama**).
- **Di PC (Chrome / Edge)**: Buka link Vercel Anda, lalu klik tombol **`📲 Instal Aplikasi (PC / Android)`** atau ikon **Instal (+)** di sebelah kanan kolom URL browser.
