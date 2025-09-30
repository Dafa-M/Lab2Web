# LAPORAN PRAKTIKUM 2

## SOAL DAN JAWABAN

### Soal
![gambar]()

### Jawaban
  1. Eksperimen Mengubah dan Menambah Properti CSS

CSS (Cascading Style Sheets) berfungsi untuk mengatur tampilan halaman web agar lebih menarik dan terstruktur. Dengan CSS, kita dapat mengubah warna teks, ukuran huruf, tata letak, margin, padding, hingga efek transisi. Eksperimen dilakukan dengan menambahkan berbagai properti ke elemen HTML. Elemen h1 akan memiliki teks berwarna biru, ukuran besar, rata tengah, huruf kapital semua, serta jarak antar huruf. Elemen p akan berwarna hijau, memiliki latar belakang abu-abu, diberi padding 15px, garis tepi abu-abu, dan jarak antarbaris lebih longgar.

![gambar]()

  2. Perbedaan h1 {…} dengan #intro h1 {…}

Selector h1 {…} adalah selector elemen yang berlaku untuk semua heading h1 di dalam dokumen HTML. Artinya, setiap kali ada <h1> maka styling tersebut akan diterapkan. Sementara itu, #intro h1 {…} adalah selector gabungan antara ID dan elemen. Selector ini berarti hanya <h1> yang berada di dalam elemen dengan id="intro" yang akan terpengaruh. Dengan kata lain, selector ini lebih spesifik dibanding selector umum h1.


  3. Perbedaan Internal, Eksternal, dan Inline CSS

Terdapat tiga cara untuk menambahkan CSS ke dalam dokumen HTML, yaitu eksternal, internal, dan inline. Eksternal CSS → CSS ditulis di file terpisah dengan ekstensi .css, lalu dihubungkan menggunakan tag link. Ini adalah cara terbaik untuk proyek besar karena memisahkan logika struktur (HTML) dengan desain (CSS). Internal CSS → CSS ditulis di dalam tag style yang diletakkan pada bagian <head>. Cara ini baik untuk styling sederhana yang hanya berlaku di satu halaman. Inline CSS → CSS ditulis langsung di dalam atribut style pada elemen HTML. Cara ini hanya cocok untuk uji coba cepat karena sulit dikelola dalam proyek besar.


  4. Perbedaan ID dan Class dalam CSS

Selector ID (#id) dan selector Class (.class) memiliki fungsi yang berbeda. ID → digunakan untuk elemen unik. Dalam satu halaman, sebaiknya hanya ada satu elemen dengan ID tertentu. Class → dapat digunakan berulang kali pada banyak elemen. Cocok untuk mengatur sekelompok elemen dengan gaya yang sama. Ketika sebuah elemen HTML memiliki ID dan Class sekaligus, maka jika keduanya memiliki aturan CSS berbeda, aturan dari ID yang akan ditampilkan. Hal ini karena spesifisitas selector ID lebih tinggi dibanding Class.
