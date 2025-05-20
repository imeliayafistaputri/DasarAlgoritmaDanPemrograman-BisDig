# DasarAlgoritmaDanPemrograman-BisDig
soal no 1: 
manfaat penggunaan fungsi : 
a) Modularitas : fungsi memungkinkan kita untuk memecahkan program yang kompleks menjadi bagian-bagian yang lebih kecil dan terkelola. setiap fungsi dapat fokus pada tugas tertentu, membuat kode lebih mudah dibaca, dipahammi, dan dipelihara. 
b) Reusabilitas : setelah mendefinisikan sebuah fungsi, kita dapat memanggilnya berkali-kali dari berbagai bagian program tanpa perlu menulis ulang kode yang sama. ini menghemat waktu dan mengurangi potensi kesalahan
c) Abstraksi : fungsi menyembunyikan detail implementasi dari pengguna. kita hanya perlu mengetahui apa yang dilakukan fungsi (input dan outputnya) tanpa perlu memahami bagaimana ia melakukannya didalam, ini menyederhanakan cara beerfikir tentang program
d) organisasi kode : fungsi membantu mengorganisis kode secara logis. kode yang terkait dengan tugas tertentu dikelmpokan bersama dalam sebu
ah fungsi, meningkatkan struktur dan keteraturan program. 
e) pengusjian dan debugging lebuh mudah : karena fungsi merupakan unit kode yang independen, lebih mudah untuk menguji dan melakukan debugging pada setiap fungsi secara terpisah. ini mempercepat proses pengembangan dan pemeliharaan.
Bagaimana Rekursi bekerja dalam menghitung Faktorial: 
Rekursi adalah teknik pemrograman di mana sebuah fungsi memanggil dirinya sendiri di dalam definisinya. Untuk menghitung faktorial menggunakan rekursi,
kita memanfaatkan definisi matematis faktorial:
n!=n×(n−1)! untuk n>0
0!=1

Berikut adalah bagaimana fungsi rekursif untuk menghitung faktorial bekerja langkah demi langkah:
Rekursi adalah teknik di mana sebuah fungsi memanggil dirinya sendiri secara langsung atau tidak langsung. Dalam menghitung faktorial, rekursi bekerja dengan cara berikut:
1. Kasus Dasar (Base Case): Faktorial dari 0 atau 1 adalah 1. Ini adalah kondisi yang menghentikan rekursi.
2. Kasus Rekursif (Recursive Case): Faktorial dari suatu bilangan n (di mana n > 1) adalah n dikalikan dengan faktorial dari n-1. Ini berarti masalah dipecah menjadi masalah yang lebih kecil.
Contoh perhitungan faktorial dari 5:
5! = 5 * 4!
4! = 4 * 3!
3! = 3 * 2!
2! = 2 * 1!
1! = 1
1! = 1
2! = 2 * 1 = 2
3! = 3 * 2 = 6
4! = 4 * 6 = 24
5! = 5 * 24 = 120

soal no 2 : 
Penggunaan Perulangan dan List (Array)
1. Perulangan (Looping)
Perulangan adalah konstruksi pemrograman yang memungkinkan kita mengeksekusi blok kode berulang kali. Dalam kasus ini, kita perlu mengulang proses input nilai untuk setiap siswa. Jika ada 5 siswa, kita akan mengulang proses meminta input nilai sebanyak 5 kali. Tanpa perulangan, kita harus menulis baris kode input secara manual untuk setiap siswa, yang akan sangat merepotkan jika jumlah siswanya banyak.
Ada beberapa jenis perulangan, tetapi yang paling umum digunakan untuk kasus seperti ini adalah for loop, yang memungkinkan kita mengulang sejumlah kali yang ditentukan.

2. List (Array)
Secara konseptual, array adalah struktur data yang menyimpan koleksi elemen-elemen dengan tipe data yang sama dalam urutan tertentu. Di Python, struktur data yang paling sering digunakan dan berfungsi seperti array dinamis adalah list.
Dalam kasus ini, kita akan menggunakan list untuk:
Menyimpan nilai-nilai dari 5 siswa. Setiap nilai yang diinput akan ditambahkan ke dalam list.
Mengakses nilai-nilai tersebut kemudian untuk menemukan nilai tertinggi. Dengan menyimpan semua nilai dalam satu tempat, kita bisa dengan mudah melakukan operasi seperti mencari maksimum atau menghitung rata-rata.

soal no 3 : 
Penggunaan Struktur Kontrol Percabangan untuk Logika Pemberian Diskon
Dalam pemrograman, struktur kontrol percabangan (conditional statements) atau sering disebut juga seleksi atau kondisional, adalah mekanisme yang memungkinkan program untuk membuat keputusan dan menjalankan blok kode yang berbeda berdasarkan kondisi tertentu. Logika ini sangat penting untuk skenario seperti pemberian diskon.

Dalam kasus diskon 10% jika belanja di atas Rp500.000, logikanya dapat dipecah menjadi beberapa langkah:
Mengecek Kondisi: Program perlu mengecek apakah "total belanja" pelanggan lebih besar dari Rp500.000. Ini adalah kondisi utama.
Aksi Berdasarkan Kondisi Benar: Jika kondisi tersebut True (total belanja memang di atas Rp500.000), maka program akan menjalankan serangkaian instruksi untuk:
Menghitung jumlah diskon (10% dari total belanja).
Menghitung total bayar setelah diskon (total belanja dikurangi diskon).
Aksi Berdasarkan Kondisi Salah (Opsional): Jika kondisi tersebut False (total belanja tidak di atas Rp500.000), maka program akan menjalankan serangkaian instruksi yang berbeda, yaitu:
Tidak ada diskon yang diberikan.
Total bayar adalah sama dengan total belanja awal.
Struktur kontrol percabangan yang paling umum digunakan untuk ini adalah if-else (atau if-elif-else untuk kondisi yang lebih kompleks).

if: Digunakan untuk mengeksekusi blok kode jika suatu kondisi bernilai True.
else: Digunakan untuk mengeksekusi blok kode alternatif jika kondisi if bernilai False.
Dengan if-else, kita bisa secara efektif membagi alur program menjadi dua jalur berbeda berdasarkan apakah syarat diskon terpenuhi atau tidak.

soal no 4 :
Inisialisasi Variabel: Siapkan variabel untuk menyimpan harga masing-masing barang. Misalnya, harga_barang1, harga_barang2, dan harga_barang3. Siapkan variabel untuk menyimpan total harga, misalnya total_harga. Input Harga Barang:
Minta pengguna untuk memasukkan harga barang ke-1. Simpan harga ke dalam variabel harga_barang1. Minta pengguna untuk memasukkan harga barang ke-2. Simpan harga ke dalam variabel harga_barang2. Minta pengguna untuk memasukkan harga barang ke-3. Simpan harga ke dalam variabel harga_barang3. Hitung Total Harga: Jumlahkan harga ketiga barang untuk mendapatkan total harga. Total_harga = harga_barang1 + harga_barang2 + harga_barang3. Tampilkan Total Harga: Tampilkan hasil total harga kepada pengguna.

soal no 5 : 
Peran Tipe Data dan Operator dalam Perhitungan Rata-rata dan Status Kelulusan
Tipe Data (Data Types)
Tipe data mendefinisikan jenis nilai yang dapat disimpan oleh suatu variabel dan operasi apa yang dapat dilakukan padanya. Dalam kasus perhitungan rata-rata nilai ujian:

1. Integer (int) atau Floating-Point (float):
int (Bilangan Bulat): Digunakan jika nilai ujian diasumsikan selalu bilangan bulat (misalnya, 80, 95, 70).
float (Bilangan Pecahan/Desimal): Lebih disarankan untuk nilai ujian dan rata-rata. Nilai ujian mungkin saja memiliki desimal (misalnya, 82.5, 78.75), dan hasil rata-rata hampir pasti akan memiliki desimal. Menggunakan float memastikan presisi dalam perhitungan.
Contoh: nilai_matematika = 85.0, rata_rata = 78.33.

2. Boolean (bool):

Digunakan untuk merepresentasikan nilai kebenaran (True atau False).
Hasil dari perbandingan (misalnya, rata_rata >= 75) akan menghasilkan nilai Boolean.
Contoh: status_lulus = True atau status_lulus = False.

3. Operator (Operators)
Operator adalah simbol khusus yang melakukan operasi pada satu atau lebih nilai (disebut operand). Dalam perhitungan ini, operator yang berperan adalah:
a. Operator Aritmatika: Digunakan untuk melakukan perhitungan matematis.
+ (Penjumlahan): Digunakan untuk menjumlahkan semua nilai mata pelajaran.
Contoh: total_nilai = nilai_matematika + nilai_fisika + nilai_kimia
/ (Pembagian): Digunakan untuk menghitung rata-rata dengan membagi total nilai dengan jumlah mata pelajaran.
Contoh: rata_rata = total_nilai / 3
b. Operator Perbandingan (Relational Operators): Digunakan untuk membandingkan dua nilai dan menghasilkan nilai Boolean (True atau False).
>= (Lebih Besar Sama Dengan): Digunakan untuk mengecek apakah rata-rata nilai lebih besar dari atau sama dengan batas kelulusan (75).
Contoh: rata_rata >= 75
c. Operator Penugasan (Assignment Operators):
= (Penugasan Sederhana): Digunakan untuk memberikan nilai ke suatu variabel.
Contoh: nilai_matematika = 85.0, rata_rata = hasil_perhitungan.

