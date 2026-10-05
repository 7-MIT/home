# 7 MIT Opensource – Beranda

Situs statis (satu berkas `index.html`, tanpa build) tentang organisasi [7-MIT](https://github.com/7-MIT).
Daftar proyek diambil langsung dari GitHub API, dengan data cadangan bila API tidak terjangkau.

## Deploy ke GitHub Pages
1. Gabungkan perubahan ke branch `main`.
2. Settings → Pages → Source: **Deploy from a branch** → `main` / `/ (root)`.
3. Situs tersedia di `https://7-mit.github.io/home/`.

Untuk domain sendiri, tambahkan berkas `CNAME` berisi nama domain dan atur DNS sesuai
[dokumentasi GitHub Pages](https://docs.github.com/pages/configuring-a-custom-domain-for-your-github-pages-site).

## Pratinjau lokal
```
python3 -m http.server 8000
```
