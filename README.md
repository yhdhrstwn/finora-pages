# finora-pages

Situs statis Finora (beranda + kebijakan privasi ID/EN) untuk GitHub Pages. Tanpa build, tanpa paket.

## Isi
- `index.html` beranda, `privasi.html` kebijakan privasi, `logo.svg` logo 4 batang miring, `.nojekyll`.
- Semua tautan relatif, jadi aman di subpath `/finora-pages/`.

## Lihat di lokal
- Cara cepat: klik dua kali `index.html`.
- Atau dari folder ini: `python -m http.server 8000` lalu buka http://localhost:8000/ dan http://localhost:8000/privasi.html

## Online (GitHub Pages)
Settings > Pages > Deploy from a branch > `main` / root. Alamat:
- https://yhdhrstwn.github.io/finora-pages/
- https://yhdhrstwn.github.io/finora-pages/privasi.html (alamat ini dipakai aplikasi, `privacyUrl`)

Sumber asli: `docs/` di repo Finora. Setiap `privasi.html` berubah, salin ke sini dan naikkan `privacyVersion` di aplikasi.
