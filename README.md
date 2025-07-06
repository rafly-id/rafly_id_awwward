# rafly\_id\_awwward

Demo portofolio interaktif berbasis **React** dan **Vite** untuk menampilkan efek ala Awwwards, terinspirasi dari desain dan animasi modern di [Zentry](https://zentry.com/).

---

## Fitur

* ✨ **Animasi Dinamis**: Efek transisi dan scroll-driven animation menggunakan **GSAP**.
* 🎨 **Desain Responsif**: Layout yang mendukung berbagai ukuran layar dengan **Tailwind CSS**.
* 🔗 **Routing Ringan**: Navigasi halaman tanpa refresh menggunakan **React Router**.
* ⚙️ **Ikon Modular**: Ikon fleksibel dengan **React Icons**.

---

## Teknologi

* **Vite** - Build tool ultra-fast untuk React
* **React** (v18) - Library UI
* **Tailwind CSS** - Utility-first CSS framework
* **GSAP** - Library animasi JavaScript
* **React Icons** - Koleksi ikon SVG untuk React

---

## Demo

> Link demo (jika sudah dideploy):
> [https://rafly-id-awwward.vercel.app](https://rafly-id-awwward.vercel.app)

---

## Prasyarat

* Node.js v16 atau lebih baru
* npm atau yarn

---

## Instalasi & Konfigurasi

1. **Clone repository**

   ```bash
   git clone https://github.com/rafly-id/rafly_id_awwward.git
   cd rafly_id_awwward
   ```
2. **Install dependencies**

   ```bash
   npm install
   # atau
   yarn install
   ```
3. **(Opsional) Konfigurasi**

   * Tidak ada variabel environment khusus; edit `vite.config.js` atau setup `.env` jika diperlukan.

---

## Menjalankan Aplikasi

* **Development**

  ```bash
  npm run dev
  ```

  Akses di: [http://localhost:5173](http://localhost:5173)

* **Build untuk Production**

  ```bash
  npm run build
  ```

  Hasil build ada di folder `dist/`.

* **Preview Production**

  ```bash
  npm run preview
  ```

---

## Struktur Direktori

```
rafly_id_awwward/
├── public/                  # Aset statis (favicon, robots, demo-screenshot.png)
├── src/                     # Kode sumber aplikasi
│   ├── assets/              # Gambar, font, media
│   ├── components/          # Komponen React terpisah
│   │   ├── Header.jsx       # Komponen header dan navigasi
│   │   ├── Hero.jsx         # Bagian hero dengan animasi GSAP
│   │   └── Footer.jsx       # Komponen footer
│   ├── App.jsx              # Root component dengan routing
│   └── main.jsx             # Mount React ke DOM
├── index.html               # Template HTML
├── package.json             # Metadata & script npm
├── vite.config.js           # Konfigurasi Vite
├── tailwind.config.js       # Konfigurasi Tailwind CSS
├── postcss.config.js        # Konfigurasi PostCSS
└── README.md                # Dokumentasi proyek
```
