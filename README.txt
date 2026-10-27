A LITTLE WORLD FOR KHOLIS — README
===================================

ISI PAKET
- index.html: website interaktif (HTML + CSS + JavaScript dalam satu file)
- assets/photos/: taruh foto kenangan di sini
- assets/music/: taruh file musik di sini

SEBELUM DIPUBLIKASIKAN
1. Buka index.html dengan editor teks/kode.
2. Cari bagian CONFIGURATION di dekat bagian bawah file:
   BIRTHDAY: "",
   Isi tanggal ulang tahun dalam format YYYY-MM-DD, misalnya "2005-11-08".
   Jika tanggal belum diketahui, biarkan "".
3. Foto: taruh enam gambar di assets/photos/ dengan nama:
   memory-1.jpg, memory-2.jpg, memory-3.jpg, memory-4.jpg, memory-5.jpg, memory-6.jpg
   Atau ubah src gambar di index.html sesuai nama file foto kamu.
4. Musik: taruh file audio MP3 yang kamu punya izin untuk digunakan di:
   assets/music/hingga-tua-bersama.mp3
   File lagu tidak disertakan dalam paket.
5. Sesuaikan surat, caption foto, dan pertanyaan quiz langsung di index.html.

PUBLIKASI GRATIS DENGAN NETLIFY DROP
1. Ekstrak ZIP ini.
2. Buka https://app.netlify.com/drop melalui browser.
3. Seret folder happy_birthday_kholis yang berisi index.html dan assets ke halaman tersebut
   (jika ponsel tidak mendukung drag-and-drop, gunakan komputer atau fitur unggah folder).
4. Tunggu situs dipublikasikan. Salin URL publik yang diberikan Netlify.
5. Buka URL itu di mode incognito atau ponsel lain untuk menguji semua bagian.

ALTERNATIF GITHUB PAGES
1. Buat repository baru di https://github.com/new.
2. Unggah index.html dan folder assets.
3. Buka Settings > Pages, pilih deployment dari branch utama dan folder root, lalu Save.
4. Tunggu URL Pages tersedia.

QR CODE
1. Buka website yang sudah dipublikasikan.
2. Gulir ke bagian “QR code buat Kholis”.
3. Tempel URL publik dan tekan “Buat QR code”.
4. QR dibuat menggunakan layanan QR Server eksternal, jadi bagian QR membutuhkan internet.
   Uji hasil scan sebelum dicetak.

CATATAN PENTING
- Countdown dan kalender akan aktif setelah tanggal diatur.
- Tanggal di kolom pada halaman bisa disimpan secara lokal di browser tersebut.
  Untuk tanggal default yang sama bagi semua pengunjung, edit CONFIG.BIRTHDAY di kode sebelum upload.
- Musik tidak autoplay; pengunjung harus menekan play karena aturan browser.
- Gunakan file foto/audio yang kamu punya hak atau izin untuk dibagikan.
- Jangan mengunggah foto pribadi yang tidak disetujui orang di dalam foto.
- Ini adalah situs statis; tidak mengumpulkan jawaban quiz atau data pengunjung ke server.
