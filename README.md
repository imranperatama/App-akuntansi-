# Buku Kerja Akuntansi

Aplikasi belajar akuntansi: soal dari AI + kunci jawaban, persamaan dasar, jurnal (umum, penyesuaian,
penutup, pembalik), buku besar otomatis, neraca saldo, neraca lajur, laporan keuangan (laba rugi,
perubahan modal, neraca, arus kas), bagan akun yang bisa ditambah.

## Jadi APK lewat GitHub
1. Buat repo baru di GitHub.
2. Tambah 1 file workflow (Add file > Create new file), ketik nama persis lalu tempel isinya:
   - `.github/workflows/main.yml`
3. Upload ZIP ini (jangan diekstrak) ke root repo.
4. Tab Actions: job 1 mengekstrak ZIP, lalu job 2 otomatis build APK (sekitar 5-10 menit).
5. Unduh APK dari menu Releases di halaman repo, atau dari Artifacts pada run workflow 2.

## Versi web (tanpa APK)
Isi folder `www/` bisa langsung di-drag ke Netlify Drop. Semua file di dalam `www/` harus ikut.

## AI
Buka ikon gerigi, pilih provider, tempel API key. Tombol "Ambil model terbaru dari provider"
mendeteksi model terbaru. Default Gemini: `gemini-3.8-flash`.
