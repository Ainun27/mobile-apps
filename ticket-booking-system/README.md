# 🎫 Ticket Booking System (Versi Awal)

Project ini adalah aplikasi mobile sederhana untuk **pemesanan tiket** transportasi & hotel.  
Dibuat sebagai bentuk **implementasi hasil belajar pemrograman mobile (semester 3)** menggunakan **Kotlin + Room Database**.  

---

## 🚀 Fitur
- Pemesanan tiket (pesawat, kereta, kapal, hotel)  
- Input data: nama, tujuan, jumlah tiket, kelas, tanggal, nomor HP  
- Menyimpan riwayat transaksi  
- CRUD data transaksi (create, read, update, delete)  

---

## 🛠️ Tech Stack
- **Bahasa**: Kotlin  
- **Database**: Room (SQLite)  
- **Tools**: Android Studio Dolphin  

---

## 🎨 Dokumentasi UI/UX
- 📌 **Figma Mockup**: [Lihat Desain di Figma](https://www.figma.com/design/rk9v64AwHnms9J6Gwew5N3/Untitled?node-id=20-369&p=f&t=6slvcD7JxE2pORdX-0)

---

## 👨‍💻 Pengembang
- **Ainun Dwi Permana** – *Founder & Creator*  

---

### STORY BOARD 
#### Storyboard untuk Aplikasi Pemesanan Tiket & Hotel

1. Menu Utama
   
- Tujuan: Memungkinkan pengguna memilih jenis tiket yang ingin dipesan.
- Elemen:
- Judul: "Pemesanan Tiket"
- Tombol/Item Daftar:
   > Pemesanan Tiket Pesawat
   > Pemesanan Tiket Kapal Laut
   > Pemesanan Tiket Kereta
   > Pemesanan Hotel
-	Navigasi: Klik tombol akan menuju ke Form Pemesanan.
  
2. Form Pemesanan
-	Tujuan: Pengguna mengisi detail untuk memesan tiket.
-	Elemen:
-	Judul: "Form Pemesanan Tiket"
-	Kolom Input:
   > Nama (EditText)
   > Tujuan (EditText)
   > Jumlah Pemesan Tiket (EditText)
   > Kelas (EditText)
   > Tanggal (EditText)
   > Nomor Telepon (EditText)
- Tombol: "Pesan Sekarang"
- Judul: "Form Pemesanan Hotel"
- Kolom Input:
   > Nama (EditText)
   > Nomer KTP
   > Jumlah Pemesan Hotel (EditText)
   > Kelas (EditText)
   > Tanggal (EditText)
   > Nomor Telepon (EditText)
   > Tombol: "Pesan Sekarang"
-	Navigasi:
-	Mengklik "Pesan Sekarang" menyimpan pemesanan dan kembali ke Menu Utama atau menampilkan pesan konfirmasi.
  
3. Layar Konfirmasi
-	Tujuan: Mengonfirmasi bahwa pemesanan tiket berhasil.
-	Elemen:
   -	Pesan: "Pemesanan Tiket Berhasil!"
   -	Menampilkan detail pemesanan (misalnya, Nama, Tujuan, Tanggal).
   -	Tombol: "Kembali ke Menu Utama"
   -	Navigasi: Kembali ke Menu Utama.
  
4. Layar Profil
-	Tujuan: Menampilkan riwayat pemesanan pengguna.
-	Elemen:
   -	Judul: "Riwayat Pemesanan"
   -	RecyclerView/Daftar yang menunjukkan pemesanan sebelumnya.
   -	Setiap item menampilkan:
   > Nama pengguna
   > pesan tiket (Pesawat/Kapal/Kereta)
   > Tujuan
   > Tanggal
   > History Harga Pesanan
- Gestur gesek untuk menghapus.
   -	Navigasi:
-	Mengklik item dapat menuju ke layar detail (opsional) atau mengizinkan pengeditan.

---

📌 *Project ini adalah karya individu, dikerjakan sepenuhnya oleh Ainun Dwi Permana sebagai latihan pemrograman mobile.*
