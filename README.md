# TUGAS-ALGORITMA-PEMOGRAMAN-PERTEMUAN-14

## ORDER COFFEE APP

Aplikasi sederhana berbasis CLI (Command Line Interface) untuk pesan kopi.
Dibuat dengan Python menggunakan konsep Object-Oriented Programming (OOP).

## FITUR

- Pilih kopi dari menu.

- Tambah kopi ke daftar pesanan.

- Lihat ringkasan pesanan.

- Checkout dengan konfirmasi.

- Pesan dan tampilan menggunakan bahasa santai khas lokal.


## CARA MENGERJAKAN 
1. Pastikan sudah install Python minimal versi 3.x.

2. Clone repository ini atau download file.py-nya.

3. Jalankan lewat terminal atau CMD:

kode :

python coffee_order.py

## MENU KOPI

1. Espresso Mantap Jiwa - Rp300
2. Latte - Rp350
3. Cappuccino bukan cina - Rp450
4. Americano Bikin Melek - Rp330

## STRUKTUR KODE

Struktur Kode

- Coffee class

Menyimpan data nama dan harga kopi.

- Order class

1. add_item(): nambah kopi ke pesanan.

2. show_order(): nunjukin daftar pesanan sama total harga.

3. checkout(): konfirmasi beli dan reset pesanan.

5. total(): hitung total harga.

- main() function

coffee-inventory/
├── coffee.py              # File utama program
├── inventory.json         # Data menu & stok (otomatis dibuat)
├── backup_inventory.json  # Backup data
└── README.md              # Penjelasan project

Tempat program jalan, nampilin menu, dan nerima input dari pengguna.

## CONTOH SAAT DIPAKAI

--- Menu Kopi Kita ---
1. Espresso Mantap Jiwa - Rp300 (Stok: 9)
2. Latte - Rp350 (Stok: 10)
3. Cappuccino bukan cina - Rp450 (Stok: 10)
4. Americano Bikin Melek - Rp330 (Stok: 9)
5. Lihat keranjang pesanan
6. Checkout
7. Laporan penjualan
8. Backup data
9. Keluar
Pilih nomor menu: 9
Makasih banyak udah mampir Bang! Sampai jumpa lagi.


Kwtika checkout tapi belum ada pesanan, bakal muncul:

Your cart is empty.
