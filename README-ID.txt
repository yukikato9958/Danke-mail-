DANKE MAIL ANDROID - PETUNJUK MEMBUAT APK

Proyek ini membungkus website Danke Mail milik Anda menjadi aplikasi Android.
Aplikasi membuka server Railway:
https://imap-production-5bceae6f.up.railway.app/

CARA MEMBUAT APK (TANPA ANDROID STUDIO):
1. Ekstrak file ZIP ini.
2. Buat repository GitHub baru, misalnya DankeMail-Android.
3. Upload semua isi folder proyek ini ke repository (jangan upload folder ZIP-nya).
4. Buka tab Actions di repository GitHub.
5. Jalankan workflow "Build Danke Mail APK" dengan tombol Run workflow,
   atau tunggu workflow berjalan setelah file di-push.
6. Setelah status workflow hijau, buka hasil run tersebut.
7. Di bagian Artifacts, unduh "Danke-Mail-APK".
8. Ekstrak hasil unduhan, lalu buka app-debug.apk di HP Android untuk memasang.

CATATAN:
- APK ini versi debug untuk pemasangan pribadi dan belum ditandatangani sebagai
  rilis Play Store.
- HP mungkin meminta izin "Install unknown apps" untuk aplikasi browser/file manager.
- APK hanya menampilkan website Railway; backend email tetap berjalan di Railway.
- Pastikan website Railway masih aktif dan menggunakan HTTPS.
- Jangan bagikan APK atau perangkat yang menyimpan sesi email kepada orang lain.
