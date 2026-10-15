# XAUUSD Drawdown Calculator

Kalkulator untuk menghitung **drawdown floating di posisi ke-x** dan **profit bila TP basket** pada strategi averaging XAUUSD (logika mengikuti EA Tunggak Semi).

- 1 pip XAUUSD = 0,01 harga (sesuai EA), bisa diganti ke 0,10
- 1 lot = 100 oz, jadi 1 pip per 1 lot = 1 USD
- Mendukung akun Standard (USD) dan Cent (USC)
- Opsional: harga entry, balance, leverage → margin, margin level, harga TP
- PWA: bisa di-install / "Add to Home Screen" di HP, jalan offline

## Deploy ke GitHub Pages
1. Upload semua isi folder ini ke repository (index.html harus di root).
2. Settings → Pages → Source: *Deploy from a branch* → `main` / `(root)`.
3. Buka `https://USERNAME.github.io/NAMA-REPO/`.

## Pasang shortcut di HP
- **Android (Chrome):** menu ⋮ → *Install app* / *Add to Home screen*
- **iPhone (Safari):** Share → *Add to Home Screen*

## Catatan
Hasil adalah estimasi: tidak memperhitungkan spread, swap, komisi, dan slippage.
