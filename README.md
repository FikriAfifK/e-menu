Laravel 11, Filament, Midtrans: Bikin Web Buku Menu Online Multi-Toko
📝 About

Website yang memungkinkan pemilik usaha kuliner untuk membuat menu online secara profesional.
Setiap toko dapat menampilkan menu mereka melalui tautan unik atau QR Code.
Sistem ini mendukung banyak toko, kategori menu, gambar menu, dan fitur subscription untuk toko dengan kebutuhan lanjutan.

🚀 Features
🔐 Login Dashboard

Akses dashboard admin untuk mengelola data toko dan pengguna.

🧩 Content Management System

Dashboard area untuk melihat statistik dan data penting.

Kelola data toko (nama toko, deskripsi, logo).

Kelola data kategori menu (kategori spesifik untuk setiap toko).

Kelola data menu:

Tambah / edit / hapus menu.

Tambah banyak gambar untuk satu menu.

Kelola pengguna dan subscription.

Melacak status pembayaran subscription (integrasi dengan Midtrans).

🏪 Toko (Pemilik Usaha)
🔸 Pendaftaran & Login

Pemilik toko dapat mendaftarkan toko mereka melalui halaman khusus.

🔸 Pengelolaan Toko

Mengedit profil toko (nama, deskripsi, logo, QR code).

Menambah menu baru dengan kategori dan gambar pendukung.

Melihat statistik toko seperti jumlah kunjungan atau pengunduhan menu.

🔸 Fitur Subscription

Gratis untuk 10 menu pertama.

Berlangganan premium dengan biaya Rp50.000 per bulan untuk menambah lebih dari 10 menu.

Notifikasi pembaruan status langganan.

🧰 Tech Stack

Laravel 11 – Backend framework utama

Filament – Admin panel dan manajemen konten

Midtrans – Integrasi pembayaran online

MySQL – Database

TailwindCSS / Blade – Frontend styling

🧩 Entity Relationship Diagram (ERD)
📊 ERD E-Menu: Website Buku Menu Online

Struktur database dirancang untuk mendukung sistem multi-toko, manajemen menu, transaksi, dan subscription.
