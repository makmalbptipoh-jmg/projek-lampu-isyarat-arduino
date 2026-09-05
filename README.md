# Sistem Kawalan Lampu Isyarat Arduino — IKBN Seri Iskandar

Projek Elektronik Industri oleh **Mohammad Harussani bin Khatib** dan **Adam Haiqal bin Abdul Rahman**.
Simpang tiga hala (9 LED, 9 perintang 220 Ω) dikawal oleh satu Arduino Uno, kitaran 21 saat.

| Fail | Kandungan |
| --- | --- |
| `index.html` | Laman web interaktif — simulasi lampu isyarat langsung, komponen, litar & kod, video demo, pengesanan kerosakan |
| `demo.mp4` | Rakaman litar sebenar berjalan, dimuatkan oleh `index.html` |

Semua gambar projek tertanam di dalam `index.html`. Pastikan `demo.mp4` berada dalam folder yang sama supaya video demonstrasi berfungsi.

## Cara deploy ke GitHub Pages

1. Buka <https://github.com/new>, namakan repo (contoh `projek-lampu-isyarat-arduino`), pilih **Public**, klik **Create repository**.
2. Pada halaman repo, klik **uploading an existing file**, seret masuk `index.html`, `demo.mp4` dan `README.md`, kemudian **Commit changes**.
3. Pergi ke **Settings → Pages**. Di bahagian *Build and deployment*, pilih Source: **Deploy from a branch**, Branch: **main** / **root**, klik **Save**.
4. Tunggu 1–2 minit. Laman anda terbit di:
   `https://<nama-pengguna>.github.io/<nama-repo>/`

## Nota

Empat gambar aplikasi industri dimuatkan terus dari Wikimedia Commons, jadi bahagian itu memerlukan sambungan internet. Gambar projek sendiri tertanam dalam `index.html`; video demonstrasi dimuatkan dari `demo.mp4`.
