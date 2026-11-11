# Build Statis Web Pengeluaran Bisnis (HTML, JS, CSS)

Folder ini berisi hasil kompilasi produksi siap pakai (Production Static Build):

## Struktur File:
- **`index.html`** : File halaman utama web statis.
- **`style.css`** : File styling tampilan CSS murni (Tailwind CSS terkompilasi & minified).
- **`app.js`** : File logika aplikasi JavaScript murni (React application bundle).
- **`manifest.webmanifest` & `sw.js`** : Service Worker untuk caching dan instalasi Progressive Web App (PWA) offline.
- **`icon.svg`, `favicon.svg`, `pwa-*.png`, `apple-touch-icon.png`** : Ikon dan logo aplikasi.

## Cara Menggunakan:
1. **Hosting Statis (cPanel, Netlify, Vercel, GitHub Pages)**:
   - Cukup salin / unggah seluruh isi folder `static_build` ini ke folder `public_html` atau root hosting Anda.
   - Tidak memerlukan Node.js ataupun backend server di hosting produksi.
2. **Offline & Lokal**:
   - Seluruh data transaksi pengguna disimpan secara lokal di browser melalui IndexedDB, sehingga aplikasi dapat berjalan penuh bahkan tanpa koneksi internet.
