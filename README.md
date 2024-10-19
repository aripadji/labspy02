# LATIHAN1_P5

![image](https://github.com/user-attachments/assets/37001fa5-86ed-45b2-9b0b-328568a73e4c)

Perulangan luar (for i in range(10)):
Perulangan ini mengontrol baris (dari 0 sampai 9). Jadi, ada 10 iterasi dari nilai i, di mana i akan bernilai mulai dari 0 hingga 9.

Perulangan dalam (for j in range(10)):
Perulangan ini mengontrol kolom (dari 0 sampai 9) di setiap baris. Setiap kali perulangan luar berjalan satu kali (setiap baris), perulangan dalam berjalan 10 kali (mencetak nilai dalam satu baris).

print(i + j, end=" "):
Ini mencetak hasil penjumlahan dari i (nilai dari perulangan luar) dan j (nilai dari perulangan dalam) di setiap iterasi. Parameter end=" " memastikan bahwa hasil penjumlahan tidak dipisahkan oleh baris baru, melainkan oleh spasi, sehingga setiap baris akan mencetak angka secara horizontal.

print() di luar perulangan dalam:
Perintah ini digunakan untuk pindah ke baris baru setelah setiap baris selesai dicetak. Ini memastikan bahwa setelah 10 angka dicetak dalam satu baris, program pindah ke baris baru untuk iterasi berikutnya.
#
HASIL OUTPUTNYA

![image](https://github.com/user-attachments/assets/e37545fa-9bdf-412a-81b6-c3b446640dfb)

#

# LATIHAN2_P5

![image](https://github.com/user-attachments/assets/5198d7d4-0bfe-4d33-a665-b5f92288b3d2)

PENJELASAN KODE :

import random:
Mengimpor modul random untuk menghasilkan bilangan acak.

n = int(input("Masukkan jumlah n: ")):
Meminta input dari pengguna berupa jumlah bilangan acak n yang ingin dihasilkan.

count = 0:
Inisialisasi variabel count untuk melacak jumlah bilangan acak yang dicetak (dimulai dari 0).

while count < n::
Loop while berjalan sampai count mencapai n.

random_number = random.random():
Menghasilkan bilangan acak antara 0 dan 1.

if random_number < 0.5::
Memeriksa apakah bilangan acak tersebut kurang dari 0.5.

print(random_number):
Mencetak bilangan acak jika memenuhi syarat (kurang dari 0.5).

count += 1:
Menambahkan 1 ke variabel count setiap kali bilangan acak kurang dari 0.5 dicetak.
#
HASIL OUTPUTNYA

![image](https://github.com/user-attachments/assets/81503d2c-c9fe-4e52-8fdd-7bd674e14b1a)

#

# PROGRAM SEDERHANA DENGAN INPUT TIGA BILANGAN, DAN MENAMPILKAN BILANGAN TERBESARNYA.

1.ALGORITMA


