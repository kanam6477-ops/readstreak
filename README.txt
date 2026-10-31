READSTREAK OFFLINE — panduan singkat

MULAI DI LAPTOP
1. Ekstrak ZIP ini.
2. Buka folder hasil ekstrak.
3. Klik dua kali index.html. Aplikasi terbuka di Chrome/Edge dan bisa dipakai offline.
4. Data otomatis tersimpan di browser laptop tersebut.

PAKAI DI ANDROID
- Cara termudah: salin folder hasil ekstrak ke HP, lalu buka index.html melalui browser/file manager. Dukungan membuka file lokal berbeda-beda antar-browser.
- Untuk pengalaman seperti aplikasi yang bisa dipasang (PWA), host folder ini satu kali ke hosting HTTPS statis gratis (misalnya GitHub Pages/Netlify), buka URL-nya di Chrome Android, pilih "Tambahkan ke layar utama". Setelah file aplikasi tercache, aplikasi dapat dibuka offline.
- Tidak ada akun/login dan tidak ada server database.

PINDAH / SAMA KAN DATA ANTAR PERANGKAT
1. Di perangkat asal, buka tab "Backup data" lalu tekan "Export backup".
2. Kirim file .json ke perangkat tujuan (kabel, Drive, email, dll).
3. Di perangkat tujuan, buka READSTREAK, tab "Backup data", tekan "Import backup".
4. Pilih gabungkan atau ganti data.
Catatan: data tidak sinkron otomatis. Export/import adalah cara memindahkan salinan data.

PENTING
- Jangan hapus data browser/cache sebelum membuat backup.
- Kalau membuka index.html langsung, service worker/PWA tidak aktif karena browser membatasi file://. Aplikasi tetap dapat dipakai offline; penyimpanan tetap lokal.
- Semua data bacaan berada di localStorage browser perangkat yang digunakan.
