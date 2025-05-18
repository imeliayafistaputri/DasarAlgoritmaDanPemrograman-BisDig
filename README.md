# DasarAlgoritmaDanPemrograman-BisDig
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
1) Kasus Dasar (Base Case): Setiap fungsi rekursif harus memiliki satu atau lebih "kasus dasar" yang menghentikan rekursi. Dalam perhitungan faktorial, kasus dasarnya adalah ketika input (n) adalah 0. Ketika n sama dengan 0, fungsi mengembalikan 1 (karena 0! = 1). Ini adalah kondisi yang mengakhiri rangkaian pemanggilan fungsi rekursif.
2) angkah Rekursif (Recursive Step): Jika input n bukan 0, fungsi akan melakukan dua hal:
a) Mengalikan n dengan hasil dari pemanggilan fungsi faktorial itu sendiri dengan input yang lebih kecil, yaitu n-1.
b) Mengembalikan hasil perkalian tersebut.


