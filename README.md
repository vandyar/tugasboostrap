1. Pengertian Bootstrap
Kegunaan: Membantu pengembang web dalam mempercepat proses desain halaman karena menyediakan komponen siap pakai (seperti tombol, form, navigasi, kartu, dll.). Bootstrap juga dirancang menggunakan pendekatan mobile-first, sehingga memastikan situs web yang dibuat secara otomatis menjadi responsif (tampil rapi di layar HP, tablet, maupun komputer).
2. memasang boostrap
Ada beberapa cara untuk mengimpor atau menggunakan Bootstrap pada project. Sebutkan caracaranya!
• Menggunakan CDN (Content Delivery Network): Memanggil file CSS dan JavaScript Bootstrap secara langsung melalui tautan online (URL) yang diletakkan di dalam tag <head> dan sebelum penutup <body>. Cara ini paling praktis karena tidak perlu mengunduh file berkas.
• Mengunduh Berkas Secara Lokal (Compiled CSS & JS): Mengunduh dokumen master CSS dan JS dari situs resmi Bootstrap, lalu menyimpannya ke dalam direktori folder proyek lokal dan menghubungkannya menggunakan jalur relatif (relative path).
• Melalui Package Manager (NPM / Yarn): Menginstal Bootstrap menggunakan perintah baris terminal (misalnya npm install bootstrap) untuk proyek-proyek berbasis modern JavaScript Node.js seperti React, Vue, atau Angular.

3.  Grid dan Breakpoint
Jelaskan mengenai class grid dan kegunaan breakpoint!
• Class Grid: Sistem tata letak (layout) bawaan Bootstrap yang membagi lebar halaman menjadi 12 kolom fleksibel menggunakan modul Flexbox. Elemen dibungkus di dalam kelas .row (baris) dan dipotong menggunakan kelas .col-* (kolom) untuk menentukan seberapa lebar sebuah elemen akan tampil.
• Kegunaan Breakpoint: Batas dimensi lebar layar (dalam satuan piksel) yang ditentukan oleh Bootstrap (seperti sm, md, lg, xl) untuk mengubah perilaku tata letak halaman. Kegunaannya adalah untuk mengatur kapan konfigurasi kolom harus berubah bentuk atau bertumpuk vertikal menyesuaikan ruang ukuran gawai pembaca.
4. Class Bootstrap
Sebutkan minimal lima class yang disediakan oleh Bootstrap beserta kegunaannya!
• .container: Berfungsi sebagai pembungkus utama konten halaman untuk memberikan ruang pembatas/jarak (padding) di sisi kiri dan kanan secara responsif.
• .btn & .btn-primary: Digunakan untuk mengubah tag tautan atau tombol biasa menjadi komponen tombol modern Bootstrap dengan pewarnaan tema utama (biasanya biru).
• .form-control: Diterapkan pada elemen input teks, email, atau password agar memiliki ukuran penuh, sudut melengkung, serta efek fokus yang konsisten.
• .d-flex: Mengaktifkan mode tata letak Flexbox pada sebuah elemen kontainer agar elemen anak di dalamnya bisa diatur posisinya dengan sangat mudah (sejajar horizontal/vertikal).
• .mb-3: Kelas utilitas margin-bottom untuk memberikan jarak renggang vertikal ke arah bawah sebesar tingkatan skala 3 (setara sekitar 1rem atau 16px).
5. Gambar Responsif
Agar foto atau gambar pada website dapat otomatis menyesuaikan ukuran ruang layar berbagai perangkat secara proporsional, Anda cukup menambahkan kelas .img-fluid pada tag <img>.
Di balik layar, kelas .img-fluid ini menerapkan formula CSS kustom berupa max-width: 100%; dan height: auto;. Formula ini memastikan gambar tidak akan pernah keluar melampaui batas lebar elemen induknya, namun tetap mempertahankan rasio aspek gambar aslinya agar tidak terlihat gepeng atau pecah.
