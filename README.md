# Mufradat Quest — مغامرة المفردات

Game petualangan belajar kosakata bahasa Arab untuk anak SD/MI. Dibuat dengan HTML, CSS, dan JavaScript biasa sehingga tidak membutuhkan proses build.

## Menjalankan di komputer
1. Ekstrak folder `mufradat-quest`.
2. Buka `index.html` di browser (Chrome, Edge, atau Firefox).
3. Untuk audio, izinkan browser menggunakan speech synthesis jika tersedia.

## Fitur
- Peta petualangan dengan empat dunia: sekolah, rumah, taman, dan pasar.
- Belajar mufradat dengan tulisan Arab, arti, contoh kalimat, ilustrasi emoji, dan audio browser.
- Kuis pilihan ganda, skor, XP, koin, serta hasil dan pengulangan kata.
- Pembukaan dunia berdasarkan pencapaian.
- Kamus dengan pencarian dan filter tema.
- Profil, badge, dan penyimpanan progres dengan `localStorage`.
- Desain responsif untuk ponsel dan laptop.

## Deploy ke GitHub dan Vercel
1. Buat repository GitHub baru bernama `mufradat-quest`.
2. Unggah isi folder ini (file `index.html`, `style.css`, `script.js`, `README.md`, dan folder `assets`).
3. Di Vercel, pilih **Add New → Project**, lalu impor repository tersebut.
4. Karena ini HTML/CSS/JS statis, pilih **Other** jika diminta framework preset. Tidak perlu build command; biarkan build command kosong. Output directory juga bisa dikosongkan.
5. Klik **Deploy**.

## Catatan
- Progres tersimpan di browser/perangkat yang sama, bukan tersinkron antarperangkat.
- Audio memakai fitur speech synthesis browser; suara Arab bergantung pada suara bahasa yang tersedia di perangkat.
- Ilustrasi konsep awal ada di `assets/referensi-desain.png`.
