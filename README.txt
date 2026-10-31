VINZZZ - VERSI WEBSITE

Isi folder:
- index.html   : seluruh aplikasi (HTML, CSS, dan JavaScript jadi satu)
- logo.jpg     : logo di header dan favicon
- ikon-vinzzz.png : ikon (opsional, untuk dipakai di tempat lain)

Website ini statis: tidak perlu server atau database. Lagu, playlist, dan
statistik disimpan di browser pengunjung masing-masing (IndexedDB), jadi
tiap orang melihat pustaka lagunya sendiri.

PENTING: harus dibuka lewat alamat https:// (hosting). Kalau index.html
dibuka langsung dari penyimpanan HP, penyimpanan browser tidak aktif dan
lagu hilang saat halaman ditutup.

CARA TERCEPAT (pilih salah satu)

A. GitHub Pages (gratis)
   1. Buat repo baru, misalnya "vinzzz-web", Public.
   2. Upload index.html dan logo.jpg ke repo (di root, bukan di dalam folder).
   3. Settings > Pages > Source: "Deploy from a branch" > Branch: main > folder: / (root) > Save.
   4. Tunggu 1-2 menit. Alamatnya: https://NAMA-GITHUB.github.io/vinzzz-web/

B. Netlify Drop (gratis, paling mudah)
   1. Buka app.netlify.com/drop
   2. Tarik folder ini (atau zip-nya) ke halaman itu.
   3. Alamat https langsung jadi.

C. Cloudflare Pages / Vercel
   Buat project baru, upload folder ini, tanpa build command.

Catatan fitur:
- Cari album online dan deteksi lirik otomatis butuh internet, dan jalan di website https.
- Tombol "Cari lirik (AI)" dan "Rapikan (AI)" hanya aktif di claude.ai, jadi di website
  sendiri akan menampilkan pesan tidak tersedia.
- Untuk membuat website bisa dipasang seperti aplikasi di layar utama HP
  (Add to Home screen), minta ditambahkan manifest PWA.
