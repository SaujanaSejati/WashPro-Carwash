# WashPro Carwash — Demo

Pratonton interaktif WashPro untuk satu kedai carwash.

## Cuba demo

Laman ini menggunakan data contoh dalam browser sahaja. Pesanan yang ditambah atau status yang diubah tidak disimpan ke pangkalan data dan boleh hilang apabila laman dimuat semula. Jangan masukkan data pelanggan sebenar.

## Fungsi pratonton

- Dashboard ringkasan jualan dan pesanan contoh
- Senarai pesanan
- Borang pesanan baharu
- Pakej servis contoh
- Status pekerja dan kemas kini aliran cucian

## Penerbitan

Workflow GitHub Pages berada di `.github/workflows/pages.yml`. Dalam GitHub, buka **Settings → Pages** dan tetapkan **Build and deployment → Source** kepada **GitHub Actions** jika belum dipilih. Kemudian buka tab **Actions** untuk melihat status deployment. URL dijangka berbentuk:

https://saujanasejati.github.io/WashPro-Carwash/

URL itu hanya akan berfungsi selepas GitHub Pages deployment berjaya.

## Untuk kegunaan sebenar

Demo ini belum disambungkan kepada Supabase atau sistem login. Ia bukan sistem operasi sebenar dan tidak merekod bayaran secara kekal. Sebelum digunakan di kedai, perlu konfigurasi database, login/role, polisi keselamatan dan ujian aliran pesanan.
