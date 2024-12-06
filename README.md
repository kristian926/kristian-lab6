Penjelasannya
Tujuan Program
Program ini digunakan untuk mengelola data mahasiswa, termasuk menyimpan, menampilkan, menghapus, dan mengubah data. Setiap mahasiswa memiliki atribut:
NIM: Nomor Induk Mahasiswa (unik untuk setiap mahasiswa)
Nama: Nama mahasiswa
Nilai: Nilai UTS, UAS, dan Tugas

Struktur Program
1. Data Mahasiswa
Program menyimpan data mahasiswa dalam sebuah dictionary bernama data_mahasiswa
Key: NIM mahasiswa (unik)
Value: Dictionary yang berisi nama mahasiswa dan nilai mereka

Fungsi Program
a. tambah(nim, nama, nilai)
Fungsi ini menambahkan data mahasiswa ke dictionary
Jika NIM sudah ada, program menampilkan pesan bahwa data sudah ada
Jika NIM belum ada, data akan ditambahkan ke dictionary

b. tampilkan()
Fungsi ini menampilkan semua data mahasiswa:

Jika ada data, semua NIM, nama, dan nilai (UTS, UAS, Tugas) akan dicetak ke layar
Jika tidak ada data, program menampilkan pesan bahwa data kosong

c. hapus(nama)
Fungsi ini menghapus data mahasiswa berdasarkan nama:

Jika nama ditemukan, data mahasiswa tersebut akan dihapus
Jika nama tidak ditemukan, program menampilkan pesan bahwa nama tidak ditemukan

d. ubah(nama, nilai_baru)
Fungsi ini mengubah nilai mahasiswa berdasarkan nama:
Jika nama ditemukan, nilai mahasiswa akan diperbarui dengan nilai baru
Jika nama tidak ditemukan, program menampilkan pesan bahwa nama tidak ditemukan

3. Menu Utama
Program memiliki menu utama yang menawarkan 5 pilihan:

Tambah Data Mahasiswa: Meminta input NIM, nama, dan nilai (UTS, UAS, Tugas), lalu menambahkan ke dictionary
Tampilkan Data Mahasiswa: Menampilkan semua data mahasiswa yang tersimpan
Hapus Data Mahasiswa: Meminta input nama mahasiswa, lalu menghapus data tersebut jika ditemukan
Ubah Data Mahasiswa: Meminta input nama mahasiswa dan nilai baru, lalu memperbarui nilai jika nama ditemukan
Keluar: Mengakhiri program

Cara Kerja Program
Program meminta pengguna memilih menu
Berdasarkan pilihan, program memanggil fungsi yang sesuai.
Program akan terus berjalan hingga pengguna memilih opsi "Keluar"

Keunggulan Program
Interaktif: Program meminta input dari pengguna untuk menjalankan setiap fitur
Fleksibel: Data dapat ditambahkan, ditampilkan, dihapus, atau diubah sesuai kebutuhan
Sederhana: Logika dan struktur program mudah dipahami dan diperluas

flowchart
![Diagram Tanpa Judul drawio (7)](https://github.com/user-attachments/assets/a93cdaa9-4dae-4c46-8b5d-68f1336b1bfb)

kode program
![Capture6](https://github.com/user-attachments/assets/a7712eec-ddd3-4c1e-b870-3bc53f55b529)
![Capture66](https://github.com/user-attachments/assets/5adce076-6458-4085-950c-b7b2839d1fe3)

Hasil Program
![6](https://github.com/user-attachments/assets/49fad65d-8057-4062-9f7c-182e3431207b)
![66](https://github.com/user-attachments/assets/e8a6f774-8d6e-4eb9-b247-ae5561cf2206)
