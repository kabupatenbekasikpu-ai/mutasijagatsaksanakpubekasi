# Publikasi Dashboard Online

Folder ini berisi versi publik dashboard yang siap dipakai untuk website atau hosting statis.

## File yang tersedia
- `public-dashboard.html` = halaman dashboard publik untuk dibuka di browser
- `index.html` = file utama aplikasi desktop

## Cara publikasi online
1. Upload semua file di folder `publish` ke hosting statis seperti GitHub Pages, Netlify, Vercel, atau hosting web lain.
2. Pastikan file `public-dashboard.html` dapat diakses via URL publik.
3. Dari aplikasi desktop, tombol `Buka dashboard publik` akan membuka URL tersebut.

## Contoh URL publik
https://namahosting.com/public-dashboard.html?data=...

## Catatan
- Data dibawa dalam query string `?data=...` dan disandikan dengan base64.
- Jika data terlalu besar untuk URL, gunakan backend atau endpoint API untuk menyimpan data publik.
