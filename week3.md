# **Lesson Week 3**

# JavaScript Array

## Definisi Array

Array adalah sebuah jenis tipe data yang dapat menampung tipe data apapun termasuk array itu sendiri. Array pada JS data yang ada di dalamnya dihitung mulai dari index ke-0, atau data pertamanya adalah index ke-0.

  &nbsp;

## Array Methods

Array memiliki method atau biasa disebut built-in methods, yang sama dengan function yang dapat digunakan kapan saja kita membutuhkannya.

  &nbsp;

  - .push()

    menambahkan array pada index terakhir

  - .pop()

    Menghapus array pada index terakhir

  - .shift()

    Menghapus array pada index pertama

  - .unshift()

    Menambahkan array pada index pertama

  - .sort()

    Mengurutkan array secara ascending maupun descending

  &nbsp;

## Looping Array

  &nbsp;

  Array memiliki 2 macam cara untuk melakukan looping

  - .forEach()
  - .map()

  &nbsp;

  Letak perbedaannya hanya jika .forEach akan melakukan perulangan pada setiap element array tanpa membuat array baru, sedangkan .map() akan melakukan perulangan dan menghasilkan nilai balik berupa array baru

  &nbsp;

## Multidimensional Array

Multidimensional array bisa bisa dianalogikan dengan array of array. Artinya array di dalam sebuah array.

  &nbsp;

# Rekursif

Rekursif adalah sebuah function yang memanggil dirinya sendiri sampai kondisi tertentu. Biasanya digunakan untuk kasus yang melibatkan operasi matematika di dalamnya. Adapun ciri-ciri dari rekursif adalah selalu memiliki kondisi yang menyatakan kapan fungsi tersebut akan berhenti. Tujuan utama dari rekursif adalah memecahkan masalah dengan mengurangi masalah tersebut menjadi masalah-masalah kecil.

![gambar](Gambar/Capture.PNG)

&nbsp;

# Modules

Modules adalah reusable code, artinya data atau kodingan yang dapat digunakan berkali-kali. Ada beberapa tindakan yang ada di dalam modules.

    - Export
    - Import
    - Export as
    - Import as
    - Export Default

&nbsp;

# Object

Object adalah sebuah tipe data yang pada variabelnya dapat menyimpan properti maupun function/method. Sama seperti Array dalam sebuah object dapat menyimpan segala jenis tipe data. Object pun dapat mengupdate nilai pada variabelnya dengan cara menambahkan atau menghapusnya.

&nbsp;

# OOP (Object Oriented Programming)

Merupakan suatu paradigma dalam pemrograman. Sama halnya seperti function yang fungsinya agar tidak membuat kode yang sama secara berulang, OOP juga mempunyai fungsi agar objek yang memiliki properti dan method yang sama akan menjadi lebih efektif dan powerfull.

&nbsp;

OOP mempunyai 4 pilar, yaitu

    - Encapsulation
    - Abstraction
    - Inheritance
    - Polymorpishm

&nbsp;

# Web Storage

Web storage terdapat di dalam website yang bersangkutan dan datanya mengikat terhadap web browser. Web Storage yang umumnya digunakan oleh FE developer adalah : local, session dan indexDB

## Local Storage

Local storage adalah tempat penyimpanan data yang memiliki karateristik :

  - Menyimpan data tanpa kadaluarsa
  - Data tidak akan dihapus walaupun web browsernya ditutup sekalipun
  - Hanya menyimpan data berupa string

&nbsp;

## Session Storage

  Berbeda dengan local storage yang datanya akan tetap tersimpan walaupun web browsernya ditutup, data yang tersimpan di dalam session storage akan hilang ketika web browsernya ditutup. Session storage memiliki karateristik :

  - Data yang disimpan pada session storage akan terus tersimpan selama browser terbuka
  - Membuka banyak tab/window dengan URL yang sama, akan menciptakan session storage yang berbeda di masing-masing tab/window.
  - Menutup tab/window akan mengakhiri session dan menghapus data yang tersimpan di session storage pada tab/window tersebut.
  - Data yang tersimpan dalam session storage harus berbentuk string.

  &nbsp;

# Asynchronous

Langkah yang dijalankan akan berjalan secara paralel atau bisa dijalankan dalam waktu yang bersamaan. Artinya kita mengizinkan program untuk menjalankan perintah lain sambil menunggu proses yang lain sedang dijalankan.

&nbsp;

Namun asynchronous memiliki kelemahan yaitu ada satu perintah yang bergantung pada output eksekusi proses sebelumnya. Dengan kata lain fungsi akan berjalan secara kejar-kejaran, sehingga datang yang diinginkan akan menjadi kosong. Untuk mengatasinya kita dapat menggunakan cara dibawah ini:

- Callback
- Promise
- Async/await
- Fetch

&nbsp;

# Sekian dan Terimakasih