# Alat Peraga Edukatif Digital — Nilai Budaya Lokal Kediri

Prototipe ini dibuat untuk penelitian: *Model Pengembangan Alat Peraga Edukatif Digital berbasis Nilai Budaya Lokal* (PAUD/TK).

## Konten
- `index.html` — Halaman utama (story, mini-game drag & drop, kuis, panduan).
- `assets/` — Ilustrasi SVG dan logo.
- Desain: responsif, sederhana, ramah anak PAUD/TK.

## Cara deploy (GitHub + Vercel)
1. Inisialisasi repo:
```bash
git init
git add .
git commit -m "Initial prototype alat peraga kediri"
```
2. Buat repository di GitHub, lalu:
```bash
git remote add origin https://github.com/USERNAME/REPO.git
git push -u origin main
```
3. Vercel:
- Masuk ke https://vercel.com, klik "Import Project", pilih repo GitHub Anda.
- Untuk static HTML tidak perlu build step. Deploy dan Vercel akan mem-publish.

## Kustomisasi yang direkomendasikan
- Ganti SVG di `assets/` dengan ilustrasi karya lokal/ilustrator.
- Sesuaikan teks cerita (PATH: di file `index.html` pada variabel `STORY`).
- Tambahkan lebih banyak scene, dan rubrik observasi di `README` atau file terpisah.

## Lisensi
Gunakan bebas untuk tujuan penelitian dan pendidikan. Mohon cantumkan sumber jika dipublikasikan.