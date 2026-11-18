=============================================================
PANDUAN MENGUBAH PROJECT INI MENJADI FILE INSTALLER .APK
=============================================================

Paket ini berisi aplikasi lengkap AutoPOS (Kasir Cuci Mobil & Bengkel)
yang sudah dilengkapi:
1. Kasir POS + Cetak Struk Thermal
2. Pengingat Ganti Oli / Servis Berkala (Odometer KM) + Kirim WhatsApp
3. Komisi Mekanik / Tukang Cuci Otomatis
4. Kartu Member / Loyalty Stamp (Gratis Cuci ke-N berdasarkan Plat Nomor)
5. Laporan Omzet + Export CSV (Excel) + Backup/Restore JSON

-------------------------------------------------------------
CARA 1: BUILD .APK OTOMATIS TANPA INSTALL ANDROID STUDIO (GRATIS)
-------------------------------------------------------------
1. Buat akun gratis di https://github.com dan buat repository baru.
2. Upload seluruh isi folder dalam ZIP ini ke repository tersebut
   (termasuk folder .github/workflows/build-apk.yml).
3. Buka tab "Actions" di repository GitHub Anda -> klik "Build AutoPOS Android APK" -> "Run workflow".
4. Tunggu ~2 menit, lalu download file "AutoPOS-Kasir-APK" yang berisi app-debug.apk siap install di HP/Tablet/Head Unit Android!

-------------------------------------------------------------
CARA 2: VIA ANDROID STUDIO DI PC / LAPTOP
-------------------------------------------------------------
1. Salin isi folder `www/` ke dalam folder:
   `android-studio-webview/app/src/main/assets/www/`
2. Buka folder `android-studio-webview` menggunakan Android Studio.
3. Klik menu Build -> Build Bundle(s) / APK(s) -> Build APK(s).

-------------------------------------------------------------
CARA 3: LANGSUNG PAKAI DI ANDROID TANPA KOMPILASI (PWA)
-------------------------------------------------------------
Buka file `www/index.html` melalui hosting gratis (Netlify Drop / Vercel / GitHub Pages)
di browser Chrome Android -> ketuk titik tiga di pojok kanan atas -> pilih
"Tambahkan ke Layar Utama / Install App". Aplikasi berjalan layar penuh seperti APK.
