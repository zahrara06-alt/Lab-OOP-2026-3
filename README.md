# Lab-OOP-2026-3

# Repositori Tugas Pemrograman Berorientasi Objek 2026

## Requirements:
1. Buat akun GitHub (https://github.com/)
2. Download Git (https://git-scm.com/)

## Alur pengumpulan tugas ke repositori ini:

1. **Fork** repositori ini

2. **Clone** repositori hasil **fork** anda

   ```sh

   git clone https://github.com/YOUR_USERNAME/Lab-OOP-2026-3.git

   ```

3. Setelah anda **clone**, masuk ke folder hasil **clone** tersebut

   ```sh

   cd Lab-OOP-2026-3

   ```

4. Buat sebuah folder dengan nama **NIM** anda dan masuk ke folder tersebut.
   ```sh

   mkdir NIM_ANDA
   cd NIM_ANDA

   ```


5. Didalam folder tersebut, buat sebuah folder dengan nama **Tugas Praktikum n**, **n** = praktikum keberapa
   ```sh

   mkdir "Tugas Praktikum n"
   cd "Tugas Praktikum n"
   
   CATATAN: n DI SINI ADALAH NOMOR PRAKTIKUM KE BERAPA
   CONTOH: Tugas Praktikum 1

   ```

6. Semua _file_ untuk tugas praktikum ke-**n**, disimpan kedalam folder **soal_n**, di dalam folder **Tugas Praktikum n**
   ```sh

   CATATAN: soal_n ADALAH FOLDER UNTUK SETIAP SOAL DALAM SATU TUGAS PRAKTIKUM
   CONTOH: Tugas Praktikum 1 terdiri 3 soal, maka di dalam folder "Tugas Praktikum 1" terdapat 3 folder lagi, yaitu: "soal_1", "soal_2", "soal_3"

   ```

7. Masukkan seluruh file Java untuk satu soal di dalam folder **soal_n**

8. Setiap membuat _file_ atau melakukan perubahan, lakukan proses **commit** dengan pesan yang deskriptif

   ```sh
   CONTOH: NAMA FILE TUGAS ADALAH "tp1.py"
   
   git add . #perintah ini memilih seluruh file sekaligus
   # atau
   git add "NIM/Tugas Praktikum n/soal_n/tp1.py" #perintah ini memilih file tertentu
   
   DISARANKAN JANGAN PAKAI git add . UNTUK MENGHINDARI PENAMBAHAN UNTUK SEMUA FILE TERMASUK FILE YANG TIDAK DIINGINKAN
   LEBIH BAIK MEMAKAI git add "NIM/Tugas Praktikum n/soal_n/tp1.py" UNTUK MENAMBAHKAN FILE
   
   git status untuk mengecek apakah file sudah ter add atau tidak.
   Jika file yang ingin di add sudah berwarna hijau lanjut ke commit.
   Jika file yang ingin di add berwarna merah lakukan add terlebih dahulu
   
   git commit -m "pesan mengenai penambahan atau perubahan apa yang anda lakukan"
   
   ```

9. Setelah asistensi dan tugas anda disetujui, **push** seluruh _file_ jawaban yang telah anda buat

   ```sh

   # pastikan proses commit telah selesai terhadap setiap file
   git push

   ```
   
10. Masuk ke akun GitHub anda, dan buka repo yang telah anda **fork** dan **clone**. Lihat perubahan yang terjadi pada repo tersebut dan pastikan bahwa tugas yang
   telah anda **push** sesuai dan berada pada repo tersebut.
   
11. Pilih menu **Pull request** dan lakukan **pull request** pada tugas praktikum anda.
