# Vcourse

Proyek ini adalah aplikasi antarmuka web bernama Vcourse. Pada pengaturan markah utama, aplikasi ini juga dikenal dengan judul halaman "vourse".

## 🛠 Teknologi Utama

Aplikasi ini dibangun menggunakan ekosistem pengembangan modern berikut:

* **Framework Inti**: Proyek ini menggunakan React versi 19.2.6.


* **Build Tool**: Proses pengembangan lokal dan kompilasi ditangani oleh Vite versi 8.0.12.


* **Pengaturan Gaya**: Tata letak dan desain visual dikelola dengan Tailwind CSS versi 4.3.1.


* **Navigasi**: Rute antar halaman diatur menggunakan pustaka `react-router-dom` versi 7.18.0.


* **Peringatan Visual**: Interaksi notifikasi (pesan toast) memanfaatkan `react-toastify` versi 11.1.0.


* **Standar Kode**: Kode sumber diawasi oleh ESLint. Aturan ESLint secara khusus menargetkan berkas berekstensi `.js` dan `.jsx`. Pengecekan ini diatur untuk mengabaikan direktori hasil kompilasi `dist`. Pengaturan ini diperkuat dengan aturan tambahan dari `eslint-plugin-react-hooks` dan `eslint-plugin-react-refresh`.



## 📂 Struktur Dasar

* **Titik Masuk (Entry Point)**: Alur jalannya aplikasi dimulai dari pemanggilan modul `/src/main.jsx`.


* **Elemen Induk (Root)**: Seluruh struktur React akan disuntikkan ke dalam pembungkus DOM yang memiliki atribut ID `root`.
