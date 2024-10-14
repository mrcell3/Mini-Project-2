# Mini-Project-2

Nama : Marcela Persa Linthin

NIM : 2409116072

# Flowchart

![flowchart minpro 2 drawio (1)](https://github.com/user-attachments/assets/d296c802-7375-4e4a-99e3-aca821c3a087)

# Output
![Screenshot 2024-10-15 052225](https://github.com/user-attachments/assets/ffce5607-f175-419d-8fc0-93e0f9908214)

![Screenshot 2024-10-15 052243](https://github.com/user-attachments/assets/539d357b-11c6-4e50-b838-4eaa2d096ff1)

![Screenshot 2024-10-15 052258](https://github.com/user-attachments/assets/87933740-0fad-45d5-aae7-bbb72708c788)

![Screenshot 2024-10-15 052315](https://github.com/user-attachments/assets/c6691a86-a9fa-497e-877e-3a0a0d5d1cee)

![Screenshot 2024-10-15 052328](https://github.com/user-attachments/assets/1387447b-4d44-4d48-afd9-22f237085e4d)

![Screenshot 2024-10-15 052424](https://github.com/user-attachments/assets/b1b4b254-81e6-4f8b-8e60-099c6bd91cb8)

![Screenshot 2024-10-15 052432](https://github.com/user-attachments/assets/7e0cc5b5-131d-4523-af39-1da374adeb07)

# Code

![Screenshot 2024-10-14 072057](https://github.com/user-attachments/assets/789830cc-353b-4dad-bf34-370f8a3e84a0)

![Screenshot 2024-10-14 072121](https://github.com/user-attachments/assets/ecad40c4-8e57-4b7e-bb37-4ad4d4d1a007)

![Screenshot 2024-10-14 072155](https://github.com/user-attachments/assets/7eb3b0cb-30ad-4e6a-8d67-0a56ebd69f6e)

# Penjelasan

1. Login Sistem

-Saat program dijalankan, pengguna dihadapkan dengan sistem login.

-Pengguna diminta untuk memasukkan username dan password sesuai dengan rolenya.

-Jika cocok, program akan memeriksa apakah pengguna adalah admin atau penyewa, dan akan menampilkan menu yang sesuai berdasarkan peran pengguna.

-Jika username & password salah, program akan mengembalikan pesan "Login gagal: Username atau password salah.

2. Menu untuk Penyewa

Jika login sebagai penyewa, pengguna disajikan beberapa opsi dalam menu:

-Opsi 1: Lihat semua kamar – Penyewa dapat melihat semua kamar kost yang tersedia dengan harga, status (kosong/terisi), dan tipe kamar (A/B).

-Opsi 2: Pesan kamar – Penyewa diminta memasukkan nomor kamar yang ingin dipesan. Jika kamar tersebut masih kosong, penyewa harus mengonfirmasi pemesanan dan memilih metode pembayaran (transfer atau tunai). Status kamar akan berubah menjadi "terisi" setelah kamar dipesan.

-Opsi 3: Keluar – Setelah penyewa selesai menggunakan menu ini, mereka bisa keluar dari program atau kembali ke menu utama.

3. Menu untuk Admin

Jika login sebagai admin, pengguna akan memiliki lebih banyak kontrol atas sistem dengan beberapa opsi tambahan:

-Opsi 1: Tambah kamar baru – Admin dapat menambah kamar baru ke dalam daftar. Admin memasukkan nomor kamar, harga, dan tipe kamar.

-Opsi 2: Ubah harga kamar – Admin dapat mengubah harga sewa dari kamar tertentu. Admin memasukkan nomor kamar yang ingin diubah dan harga baru.

-Opsi 3: Ubah status kamar – Admin dapat mengubah status kamar dari "kosong" ke "terisi" atau sebaliknya.

-Opsi 4: Hapus kamar – Admin dapat menghapus kamar dari sistem dengan memasukkan nomor kamar yang akan dihapus.

-Opsi 5: Keluar – Setelah admin selesai melakukan tugasnya, mereka dapat kembali ke menu utama atau keluar dari program.

4. Main Program

-Setelah login berhasil, program akan memanggil fungsi menu yang sesuai dengan peran pengguna.

-Jika pengguna adalah penyewa, akan dipanggil fungsi penyewa_menu() yang memberikan akses ke opsi-opsi penyewa.

-Jika pengguna adalah admin, akan dipanggil fungsi admin_menu() yang memberikan kontrol penuh atas pengelolaan kamar.

-Program akan terus berjalan hingga pengguna memilih untuk keluar dengan memilih opsi "Keluar".

Setelah pengguna selesai menggunakan menu dan memilih opsi untuk keluar, program akan berhenti.
