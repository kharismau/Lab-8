# Lab 8
Program ini bertujuan untuk mengelola data nilai mahasiswa menggunakan konsep class dan object, dengan tampilan perintah sebagai berikut :

![Screenshot 2024-12-13 150322](https://github.com/user-attachments/assets/0185588e-e9fc-491f-8a39-691d9afd4721)

![Screenshot 2024-12-13 150337](https://github.com/user-attachments/assets/a6fe8d97-a8d4-4e9c-a3bd-fe05f7181ecc)

# Struktur Program
Program ini terdiri dari satu class bernama Mahasiswa, yang bertugas mengelola data mahasiswa seperti nama dan nilai mereka. Ada juga logika utama di bawah blok if __name__ == "__main__" untuk menjalankan aplikasi secara interaktif.

# Class Mahasiswa
Class ini berisi atribut dan metode sebagai berikut:

A. Atribut:

- data: Sebuah dictionary (dict) untuk menyimpan data mahasiswa.
- Key: Nama mahasiswa (str).
- Value: Nilai mahasiswa (float).

B. Method:

- __init__():
    > Konstruktor untuk menginisialisasi atribut data sebagai dictionary kosong.
- tambah(nama, nilai):
    > Menambahkan data mahasiswa ke dalam atribut data.
    > Jika mahasiswa sudah ada, nilainya akan diperbarui secara otomatis.
- tampilkan():
    > Menampilkan semua data mahasiswa dalam format yang rapi.
    > Jika tidak ada data, mencetak pesan "Tidak ada data mahasiswa."
- hapus(nama):
    > Menghapus data mahasiswa berdasarkan nama.
    > Jika nama tidak ditemukan, mencetak pesan "Data tidak ditemukan."
- ubah(nama, nilai):
    > Mengubah nilai mahasiswa berdasarkan nama.
    > Jika nama tidak ditemukan, mencetak pesan "Data tidak ditemukan."


# Program Utama:

   A) Menu Utama
      Menampilkan pilihan operasi
       1. Tambah Data
       2. Tampilkan Data
       3. Hapus Data
       4. Ubah Data
       5. Keluar dari program.

    B) Operasi
       - Tambah Data:
         > Meminta input nama dan nilai mahasiswa untuk ditambahkan. 
       - Tampilkan Data:
         > Menampilkan seluruh daftar mahasiswa dan nilai mereka.
       - Hapus Data:
         > Meminta input nama mahasiswa untuk menghapus data mereka.
       - Ubah Data:
         > Meminta input nama mahasiswa dan nilai baru untuk memperbarui data mereka.
       - Keluar:
         > Mengakhiri program.
   C) Validasi Input:
      - Program memeriksa validitas input (misalnya, apakah nama ditemukan atau tidak) dan memberikan pesan yang sesuai.

# Diagram Class:

+---------------------+
|      Mahasiswa      |
+---------------------+
| - data: dict        |
+---------------------+
| + __init__() : None                         |
| + tambah(nama: str, nilai: float) : None    |
| + tampilkan() : None                        |
| + hapus(nama: str) : None                   |
| + ubah(nama: str, nilai: float) : None      |
+---------------------+

![diagram class](https://github.com/user-attachments/assets/0e5eaf50-4555-46e8-8e63-593bf2b91510)

# Contoh Hasil Output dari Program:

![Screenshot 2024-12-13 150238](https://github.com/user-attachments/assets/5d7c9039-7506-4548-b908-5d144a8e3c25)

![Screenshot 2024-12-13 150247](https://github.com/user-attachments/assets/c2dbe792-3d40-44f7-aaae-c2d3a4552440)

# Flowchart

![flowchart lab 8](https://github.com/user-attachments/assets/5a166e37-c4fc-482c-8259-50e5ce4ea5a3)


