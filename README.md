# developer.7mit – Beranda

Sub-divisi dari [7mit.org](https://7mit.org); desain mengikuti portal 7 MIT lainnya (sidebar navy, aksen biru-cyan, tema gelap/terang).

Situs statis (satu berkas `index.html`, tanpa build) tentang organisasi [7-MIT](https://github.com/7-MIT).
Daftar proyek diambil langsung dari GitHub API, dengan data cadangan bila API tidak terjangkau.

## Deploy ke GitHub Pages
Dipublikasikan dari branch `main` (root) dengan domain khusus **developer.7mit.org** (lihat berkas `CNAME`).

1. Settings → Pages → Source: **Deploy from a branch** → `main` / `/ (root)`.
2. Custom domain: `developer.7mit.org`, lalu aktifkan **Enforce HTTPS** setelah sertifikat siap.
3. DNS untuk `7mit.org`: tambah rekor `CNAME` dengan host `developer` ke `7-mit.github.io`.

Alamat bawaan: `https://7-mit.github.io/home/` (akan mengalihkan ke domain khusus).

## Pratinjau lokal
```
python3 -m http.server 8000
```
