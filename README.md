# Extension Browser with GPT - Generate Cover Letter

## Deskripsi

Proyek ini bertujuan untuk menyediakan [deskripsi singkat proyek].

## Daftar Isi

- [Instalasi](#instalasi)
- [Penggunaan](#penggunaan)
- [Ketergantungan](#ketergantungan)
- [Konfigurasi](#konfigurasi)
- [Lisensi](#lisensi)

## Instalasi

Untuk memulai dengan proyek ini, ikuti langkah-langkah berikut:

Clone repositori ke mesin lokal Anda:

```bash
git clone https://github.com/tantowi-17/extension-generator-gpt.git
```

Instal ketergantungan yang diperlukan:

```bash
npm install
```

## Penggunaan

Untuk menjalankan proyek secara lokal, gunakan perintah berikut:

```bash
npm run start
```
Untuk prodaction proyek secara lokal, gunakan perintah berikut:

```bash
npm run build
```

Ini akan memulai server pengembangan dan membuka proyek di peramban web default Anda.

## Ketergantungan

Proyek bergantung pada ketergantungan berikut:

- **@testing-library/jest-dom**: ^5.17.0
- **@testing-library/react**: ^13.4.0
- **@testing-library/user-event**: ^13.5.0
- **autoprefixer**: ^10.4.18
- **axios**: ^1.6.8
- **flowbite**: ^2.3.0
- **flowbite-react**: ^0.7.3
- **postcss**: ^8.4.37
- **react**: ^18.2.0
- **react-dom**: ^18.2.0
- **react-icons**: ^5.0.1
- **react-scripts**: 5.0.1
- **react-toastify**: ^10.0.5
- **tailwindcss**: ^3.4.1
- **web-vitals**: ^2.1.4

## Konfigurasi

Proyek menggunakan Tailwind CSS untuk styling. Di bawah ini adalah konfigurasi untuk Tailwind CSS:

```javascript
module.exports = {
  content: [
    "./public/**/*.html",
    "./src/**/*.{js,jsx,ts,tsx}",
    "./node_modules/flowbite/**/*.{js,jsx}",
  ],
  theme: {
    extend: {},
  },
  plugins: [require("flowbite/plugin")],
}
```

## Lisensi

Proyek ini dilisensikan di bawah [nama lisensi]. Lihat file [LICENSE](LICENSE) untuk detailnya.
