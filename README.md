# MŌRA Caféé — Versi GitHub Pages (struktur datar, v16 responsif)

Semua file ada di satu folder (tanpa subfolder css/js/assets), jadi aman diunggah lewat tombol "Add file > Upload files" di GitHub.

## Cara deploy
1. Buat repository baru di GitHub (public).
2. Ekstrak zip ini, lalu upload SEMUA isi foldernya (semua .html, .css, .js, gambar, .pdf, dan file `.nojekyll`) ke root repository, bukan folder pembungkusnya.
   - Jika `.nojekyll` tidak terlihat di Finder/Explorer (file tersembunyi), buat file kosong bernama `.nojekyll` lewat "Add file > Create new file".
3. Settings > Pages > Deploy from a branch > main / (root) > Save.
4. Tunggu 1–2 menit, buka `https://USERNAME.github.io/NAMA-REPO/`.

## Catatan
- Perlu internet untuk Tailwind CDN, font, ikon, dan foto dari Stitch.
- Halaman utama: `index.html`. Gaya: `style.css`. Token desain: `tailwind.config.js`.
- Skrip: `layout.js` (header+footer), `features.js`, `main.js`, `data.js`; interaksi tiap halaman di `racik.js`, `menu.js`, `mood.js`, `promo.js`, `profil.js`, `kebun.js`, `gizi.js`, `galeri.js`, `keranjang.js`.
- Foto lokal: `menu-1..9.jpg`, `ruang-utama.jpg`, `creator-*.webp`, `logo.png`; poster di `poster-*.png`; katalog di `katalog-mora.pdf`.
- Panduan desain: `DESIGN.md`.
