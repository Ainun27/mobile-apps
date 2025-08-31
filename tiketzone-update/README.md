# 🎫 TiketZone – Updated Version

TiketZone adalah versi pengembangan dari project **Ticket Booking System**.  
Aplikasi ini tetap berfokus pada sistem **pemesanan tiket transportasi & hotel**, namun dengan **penyempurnaan UI/UX** serta peningkatan performa.  

---

## 📌 Catatan Penting
💡 **Ide dan konsep aplikasi berasal dari Ainun Dwi Permana**, terinspirasi dari aplikasi serupa yang sudah ada.  
Aplikasi ini dibuat sebagai **implementasi pembelajaran pemrograman mobile semester 4**, dengan pengembangan dilakukan secara kolaboratif bersama tim.  

---

## 🚀 Fitur Baru (dibanding versi awal)
- Desain UI/UX lebih modern & responsif  
- Swipe untuk menghapus data riwayat  
- Ikon profil untuk akses cepat ke history  
- Validasi form input lebih baik  
- Performa aplikasi lebih optimal
- Edit Profile
- Menu registrasi dan login

---

## 🛠️ Tech Stack
- **Bahasa**: Kotlin  
- **Database**: Room (SQLite)  
- **Tools**: Android Studio Dolphin  

---

## 👨‍💻 Pengembang
- **Ainun Dwi Permana (312310013)** – *Founder & Project Lead* (Ide, Konsep, Fullstack Dev)  
- **Dita Tiara Putri (312310131)** – Frontend Developer (kontributor)  
- **Nur Laila (312310149)** – Frontend Developer (kontributor)  
- **Suci Maolia (312310004)** – Backend Developer (kontributor)  

---

## 🎨 Dokumentasi UI/UX
- 📌 **Figma Mockup**: [Lihat Desain di Figma](https://www.figma.com) *(ganti dengan link asli figma)*  

---

## Story Board
```sh
1. Splash / Welcome Screen
Tujuan:
Tampilan awal aplikasi.
Elemen:
•	Logo / Nama Aplikasi
•	Tombol: "Masuk"
Navigasi:
•	Klik tombol "Masuk" → ke halaman Login & Daftar
________________________________________
2. Login & Daftar
Login:
•	Email
•	Password
•	Tombol: "Masuk"
•	Link: "Belum punya akun? Daftar"
Daftar:
•	Nama
•	Email
•	Password
•	Konfirmasi Password
•	Tombol: "Daftar"
Navigasi:
•	Login/Daftar berhasil → ke Menu Utama
________________________________________
3. Menu Utama
Tujuan:
Pengguna memilih layanan yang tersedia.
Elemen:
•	Judul: "Pemesanan Tiket"
•	Tombol/Menu:
o	Tiket Pesawat
o	Tiket Kapal Laut
o	Tiket Kereta
o	Sewa Mobil
o	Profil ← (tombol baru)
________________________________________
4. Form Pemesanan
A. Tiket:
•	Nama
•	Tujuan
•	Jumlah Pemesan
•	Kelas
•	Tanggal
•	Nomor Telepon
•	Tombol: "Pesan Sekarang"
B. Sewa Mobil:
•	Nama
•	Nomor KTP
•	Jumlah Penumpang
•	Tipe Mobil
•	Tanggal
•	Nomor Telepon
•	Tombol: "Pesan Sekarang"
________________________________________
5. Layar Konfirmasi
Elemen:
•	Pesan: "Pemesanan Berhasil!"
•	Detail pemesanan
•	Tombol: "Kembali ke Menu Utama"
________________________________________
6. Layar Profil
Tujuan:
Menampilkan dan mengelola data akun pengguna.
Elemen:
•	Judul: "Profil Saya"
•	Kolom:
o	Nama (EditText – bisa diubah)
o	Email (tidak bisa diubah)
•	Tombol:
o	"Edit Nama" (mengaktifkan EditText jika disabled)
o	"Simpan" (untuk menyimpan perubahan nama)
Catatan:
•	Data nama yang diedit bisa disimpan ke database atau SharedPreferences sesuai implementasi.
________________________________________
7. Riwayat Pemesanan (Bagian dari Profil atau Menu Sendiri)
Elemen:
•	Judul: "Riwayat Pemesanan"
•	List Pemesanan (RecyclerView):
o	Nama
o	Jenis Tiket / Mobil
o	Tujuan / Tipe Mobil
o	Tanggal
o	Harga
Fitur Tambahan:
•	Geser item untuk hapus
•	Klik item untuk detail/edit (opsional)


```

---

## Ui   
![Kelompok_Mobile 1](https://github.com/user-attachments/assets/38cba1be-c452-4080-9165-146621f2eeb8)  

## Mockup
![Kelompok Mobile (1) 1](https://github.com/user-attachments/assets/438703e1-cd40-4bbc-b97b-ed86ef5a9ba8)

## Trello  
#### Ainun Dwi Permana https://trello.com/b/iEpLAWDm/projek-mobile-2   
#### Dita Tiara Putri https://trello.com/b/wxZ2YSwr/project-mobile
#### Nur Laila https://trello.com/b/xzs5F1AY/project-mobile-2   
#### Suci Maolia https://trello.com/b/w0Ugvf1k/project-mobile 

---

📌 *TiketZone adalah implementasi hasil belajar. Ide berasal dari Ainun Dwi Permana (terinspirasi dari aplikasi serupa), sementara pengembangan teknis dilakukan secara kolaboratif bersama tim.*

---

