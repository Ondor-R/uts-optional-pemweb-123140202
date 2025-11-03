Nama: Reyhan Oktavian Putra
NIM: 123140202


## 01: Single-File Web Applications
1. Karena print('Incoming request') adalah standar python untuk menampilkan pesan

2. Saat mengembalikan string html, string di local hostnya akan diperlihatkan layaknya menggunakan html. Misal dengan h1 maka tulisannya akan jadi besar seperti menggunakan header 1 di html. Saat return diisi dengan integer, di yang saya coba menampilkan error

3. Saat memasukkan print(xyz) didlm method/function hellow_worldny, terdapat error NameError: name 'xyz' is not defined

4. Common Gateway Interface (CGI)

## 03: Application Configuration with .ini Files
1. Mungkin bisa

2. Bisa, kegunaan menggunakan beberapa .ini misalnya utk mengkonfigurasi environment yang berbeda

3. Karena Python otomatis menangani impor dari sebuah direktori paket yang memiliki file __init__.pynya.

4. ** digunakan untuk variable dictionary, mengambil key-value nya untuk argumen sebuah method/function.

## 04: Easier Development with debugtoolbar
1. karena pyramid_debugtoolbar digunakan hanya untuk pengembangan

2. Saat memasukkan request keluar: <Request at 0x2c140cc3230 GET http://localhost:6543/>, saat memasukkan Response keluar: <class 'pyramid.response.Response'>

## 05: Unit Tests and pytest
1. Saat diganti 404, terdapat pesan AssertionError: 200 != 404. Yang saya dapat berarti dari requestnya yang keluar 200 sedangkan yang kita minta 404. Karena tidak sama maka keluar error itu.

2. Lebih convenient karena tidak butuh server jadi tidak harus memberhentikan terminal, tidak butuh browser, lebih cepat overal.

3. Saat ditest dengan menambah 404 di Respone, terdapat error karena di tests.pynya memasukkan 200, dimana itu adalah nilai yang sudah diekspektasi(kontrakny).

4. dengan menambahkan misal self.assertEqual(response.body, b'<body><h1>Hello Worlp!</h1></body>') ke method/function test_hello_world.

5. Karena kita ingin mengetest method/function hello_world. Di import didalam test_hello_world agar terisolasi & tidak meng expect error dari tempat lain.