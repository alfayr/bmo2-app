# BMO2 Platform — aplikasi HP

Aplikasi (PWA) untuk membuka **BMO2 One Platform** (PT Berau Coal, BMO2) di HP seperti aplikasi biasa:
ikon BMO2 di layar utama, layar pembuka, layar penuh tanpa bilah alamat.

Isi dashboard, login, dan data tetap dari BMO2 Platform online (Google Apps Script) — aplikasi ini hanya bingkainya.

## Pasang di HP
- **Android (Chrome):** buka alamat aplikasi → ketuk **Instal aplikasi** / menu ⋮ → **Instal aplikasi**.
- **iPhone (Safari):** buka alamat aplikasi → **Bagikan** → **Tambahkan ke Layar Utama**.

## File
- `index.html` — bingkai aplikasi + layar pembuka
- `manifest.webmanifest` — nama, ikon, warna, pintasan (Operation, K3, Lingkungan)
- `sw.js` — penyimpan kerangka aplikasi
- `icons/` — ikon aplikasi

Alamat BMO2 Platform online diatur di `index.html` (konstanta `EXEC`).
