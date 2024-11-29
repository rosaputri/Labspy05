# Labspy05
Nama : Rosa Putri Eka Yetsi

Kelas : IE.23.C12

NIM : 352310841

Praktikum 5

Program ini merupakan program yang dibuat mengguanakan Dictionary untuk mengolah data nilai akhir mahasiswa. 

Program ini dibuat untuk mengelola data mahasiswa termasuk menampilkan, menambah, mengubah, menghapus, dan mencari data nilai mereka. 

Program ini dibuat dengan menggunakan NIM sebagai Key dan data mahasiswa (Nama, Nilai Tugas, Nilai UTS, Nilai UAS) sebagai Value. 

Program ini menggunakan perhitungan nilai akhir dengan bobot sebesar Nilai Tugas 30%, Nilai UTS 35% dan Nilai UAS 35%


**Menu Program**
 
 Program ini mempunyai beberapa menu yang akan ditampilkan di awal ketika dijalankan, diantaranya "
 
 L: Melihat daftar nilai mahasiswa.
 
 T: Menambahkan data mahasiswa baru.
 
 U: Mengubah data mahasiswa berdasarkan NIM.
 
 H: Menghapus data mahasiswa berdasarkan NIM.
 
 C: Mencari data mahasiswa berdasarkan NIM.
 
 K: Keluar dari program.
 
 **Fungsi Program**
1. Menghitung Nilai
Program ini menghitung Nilai Akhir berdasarkan formula :

<img width="422" alt="image" src="https://github.com/user-attachments/assets/bf7edd2f-b59f-492c-8b78-fa9f525d292a">

2. Menampilkan Data
Program ini menampilkan data mahasiswa dalam bentuk tabel. Apabila data di dalam program kosong maka tampilan tabel tersebut juga kosong

<img width="469" alt="image" src="https://github.com/user-attachments/assets/3158b787-923c-4848-9c4c-e8da2fcb63f8">

3. Menambahkan Data
Program ini akan meminta untuk memasukan data mahasiswa (Nama, Nilai Tugas, Nilai UTS, Nilai UAS) untuk selanjutnya akan dihitung menjadi data nilai akhir. Apabila program ini berhasil maka program akan menampilkan "Data berhasil ditambahkan!" dan program akan kembali ke menu awal 

<img width="309" alt="image" src="https://github.com/user-attachments/assets/08470e7c-233a-4cd1-8b48-6516baeb2580">

4. Mengubah Data
Program ini akan meminta untuk memasukan NIM mahasiswa sebagai Key. Selanjutnya program akan meminta untuk memasukan data (Nama, Nilai Tugas, Nilai UTS, Nilai UAS) untuk kemudian akan diganti menjadi data yang baru. Apabila program ini berhasil maka program akan menampilkan "Data berhasil diubah!", namun apabila NIM yang dimasukan salah maka tambilan program "Data tidak ditemukan!"

<img width="302" alt="image" src="https://github.com/user-attachments/assets/c53a2bd5-cc89-4b06-b438-5a8a149d2883">

5. Menghapus Data
Program ini akan meminta untuk memasukan NIM mahasiswa sebagai Key. Selanjutnya apabila program ini berhasil maka program akan menampilkan "Data berhasil dihapus!", namun apabila NIM yang dimasukan salah maka tambilan program "Data tidak ditemukan!"

<img width="307" alt="image" src="https://github.com/user-attachments/assets/da160c6e-cb61-4e86-8076-cac3c685715c"> 

 6. Mencari Data
 Program ini akan meminta untuk memasukan NIM mahasiswa sebagai Key. Selanjutnya apabila program ini berhasil maka program akan menampilkan data yang dicari, namun apabila NIM yang dimasukan salah maka tampilan program "Data tidak ditemukan!".

<img width="345" alt="image" src="https://github.com/user-attachments/assets/5ec7fd92-ea7e-4f36-9321-202cf70612be"> 

7. Keluar Program
Apabila selesai menjalankan program maka pilih menu K dan akan keluar hasil sebagai berikut

<img width="626" alt="image" src="https://github.com/user-attachments/assets/2fa7a1b0-dd51-41bd-b17e-dd4c58f2ef1f">




**ALUR PENGGUNAAN PROGRAM**

<img width="674" alt="image" src="https://github.com/user-attachments/assets/e0c793b0-b73f-4985-985d-38b239733c43">

1. Menjalankan Program
 Program akan menampilkan menu ketika dijalankan.
 Ketika menu yang dipilih salah maka akan menampilkan "Pilihan tidak valid! Silakan coba lagi."
 
 2. Memilih Menu
 
 Ketik huruf sesuai pilihan menu:
 
 L: Melihat daftar nilai mahasiswa.
 
 T: Menambahkan data mahasiswa baru.
 
 U: Mengubah data mahasiswa berdasarkan NIM.
 
 H: Menghapus data mahasiswa berdasarkan NIM.
 
 C: Mencari data mahasiswa berdasarkan NIM.
 
 K: Keluar dari program.
 
 3. Menambahkan Data
 
 Pilih menu T (Tambah).
 
 Masukkan informasi berikut:
 
 NIM: Nomor Induk Mahasiswa.
 
 Nama: Nama mahasiswa.
 
 Nilai Tugas, UTS, UAS: Nilai numerik.
 
 Program akan otomatis menghitung nilai akhir dan menyimpan data.
 
 4. Melihat Data
 
 Pilih menu L (Lihat).
 
 Data akan ditampilkan dalam tabel, termasuk NIM, nama, nilai tugas, UTS, UAS, dan nilai akhir.
 
 5. Mengubah Data
 
 Pilih menu U (Ubah).
 
 Masukkan NIM mahasiswa yang ingin diubah.
 
 Jika ditemukan, masukkan data baru (nama, nilai tugas, UTS, UAS).
 
 Data akan diperbarui.
 
 6. Menghapus Data
 
 Pilih menu H (Hapus).
 
 Masukkan NIM mahasiswa yang ingin dihapus.
 
 Jika ditemukan, data akan dihapus dari daftar.
 
 7. Mencari Data
 
 Pilih menu C (Cari).
 
 Masukkan NIM mahasiswa yang dicari.
 
 Jika ditemukan, data akan ditampilkan.
 
 8. Keluar dari Program
 
 Pilih menu K (Keluar).
 
 Program akan berhenti dengan pesan terima kasih.

 
 **Kesimpulan**
 
 Program ini sangat cocok untuk mengelola data sederhana, seperti nilai akhir semester, dengan fitur CRUD (Create, Read, Update, Delete). Dengan mengikuti alur di atas, pengguna dapat dengan mudah mengelola data mahasiswa
