# Praktikum 1
# Pemrograman Web
```
Muhammad Rizkiansyah
311910071
TI19C1
UNIVERSITAS PELITA BANGSA
```
## Langkah 1
Buka VSCode dan buat file HTML baru. Setelah itu buat struktur dasar HTML.
```
<!DOCTYPE html>
<html>
<head>
    <title>Tag HTML Dasar</title>
</head>
<body>

</body>
```
![Langkah 1](https://user-images.githubusercontent.com/81818687/113466967-1c77f580-946a-11eb-9ff1-91f6a06a0ccb.png)
## Langkah 2
Selanjutnya buatlah beberapa paragraf sederhana sebagai berikut.
```
<!-- Ini adalah paragraf pertama -->
<p>Kami sedang belajar HTML dasar, pada matakuliah Pemrograman Web di Prodi 
    Teknik Informatika Universitas Pelita Bangsa. Pelajaran pertama yang kami dapat 
    adalah membuat tampilan web sederhana dalam rangka mengenal tag-tag dasar 
    HTML.</p>
    
<!-- Ini adalah paragraf kedua -->
<p>Ini merupakan sebuah paragraf yang terdiri dari beberapa 
    kalimat yang saling mendukung sehingga menjadi satu kesatuan. Paragraf dibuat 
    dengan menggunakan tag dasar html.</p>
```
![Langkah 2](https://user-images.githubusercontent.com/81818687/113467032-8bede500-946a-11eb-984f-bb4f07272868.png)
## Langkah 3
Selanjutnya silakan ubah-ubah nilai atributnya (align => justify, left, right, dan center) untuk melihat perbedaan lainnya.
```
<!-- Ini adalah paragraf pertama -->
<p style=text-align:center;>Kami sedang belajar HTML dasar, pada matakuliah Pemrograman 
    Web di Prodi Teknik Informatika Universitas Pelita Bangsa. Pelajaran pertama 
    yang kami dapat adalah membuat tampilan web sederhana dalam rangka mengenal 
    tag-tag dasar HTML.</p>
 <!-- Ini adalah paragraf kedua -->
<p style=text-align:right;>Ini merupakan sebuah paragraf yang terdiri dari beberapa 
    kalimat yang saling mendukung sehingga menjadi satu kesatuan. Paragraf dibuat 
    dengan menggunakan tag dasar html.</p>
 ```
 ![Langkah 3](https://user-images.githubusercontent.com/81818687/113467091-f2730300-946a-11eb-8b8a-83092f2f5605.png)
 Kemudian tambahkan judul h1 sebelum paragraf pertama dan tambahkan sub judul h2 sebelum paragraf kedua.
```
<!-- judul paragraf pertama -->
<h1>Belajar Dasar HTML</h1>
<!-- judul paragraf kedua -->
<h2>Paragraf pada HTML</h2>
```
![Screenshot 2021-04-03 095128](https://user-images.githubusercontent.com/81818687/113467555-cdcc5a80-946d-11eb-8637-a852cc1b72b0.png)

## Langkah 4
Lakukan pemformatan teks yang ada pada paragraf yang sudah ada sebelumnya, mengacu kepada penjelasan materi pemformatan teks, sehingga tampilannya seperti berikut.
```
<p style=text-align:left;>Kami sedang belajar <mark>HTML dasar</mark>, pada matakuliah <b>Pemrograman
    Web</b> di Prodi <i>Teknik Informatika</i> <ins>Universitas Pelita Bangsa</ins>. Pelajaran pertama
    yang kami dapat adalah membuat tampilan web sederhana dalam rangka mengenal
    tag-tag dasar HTML.</p>
 ```
 ![Langkah 4](https://user-images.githubusercontent.com/81818687/113467644-8c887a80-946e-11eb-924c-101aa0b68d3e.png)
 
 ## Langkah 5
 Untuk menyisipkan gambar, siapkan gambar yang akan disisipkan pada halaman web, kemudian simpan file gambar tersebut satu folder dengan file dokumen html.

![Langkah 5](https://user-images.githubusercontent.com/81818687/113467685-cf4a5280-946e-11eb-9708-12917c04c8f1.png)
Kemudian tambahkan tag img setelah paragraf yang kedua, dengan menambahkan heading 3 sebelumnya.
```
<!-- sub judul paragraf -->
<h3>Menambahkan Gambar</h3>
<!-- menambahkan gambar pada dokumen -->
<img src="logo_upb.png" width="200" title="Logo Univeritas Pelita Bangsa">
```
![Screenshot 2021-04-03 095600](https://user-images.githubusercontent.com/81818687/113468370-f48b9080-946f-11eb-8bb8-979c42dad25c.png)

## Langkah 6
Tambahkan hyperlink pada dokumen sebelum heading 1 seperti berikut.
```
<!-- menambahkan link navigasi -->
<nav>
    <a href="lab1_tag_dasar.html">Dasar HTML</a>
    <a href="lab1_halaman2.html">Halaman 2</a>
    <a href="http://www.google.com">Halaman Web Eksternal Google</a>
    </nav>
    <hr>  
```
![Langkah 6](https://user-images.githubusercontent.com/81818687/113468407-2b61a680-9470-11eb-8387-f27f6d388736.png)

## Langkah 7 
Membuat halaman ke 2 yg akan terhubung dengan halaman pertama menggunakan Hyperlink.
```
!DOCTYPE html>
<html>
<head>
    <title>Tag HTML Dasar</title>
</head>
<body>

<h1>Halaman Ke 2</h1>

<img src="Foto.PNG" width="200" title="Logo Univeritas Pelita Bangsa">


<p align="justify">Muhammad Rizkiansyah </p>
<p align="justify">311910071</p>
<p align="justify">TI.19.c1</p>

</body>
</html>
```
![Langkah 7](https://user-images.githubusercontent.com/81818687/113468428-59df8180-9470-11eb-8c14-266ec311f157.png)

# Jawaban Pertanyaan soal 

1. Lakukan perubahan pada kode sesuai dengan keinginan anda, amati perubahannya adakah error ketika terjadi kesalahan penulisan tag?
``` 
ya karena , dalam bahasa pemrograman terdapat sensitive case/ jadi kalo ada sedikit kesalahan dalam penulisan akan terjadi eror/ tidak bisa tereksekusi.
```
2.Apa perbedaan dari tag <p> dengan tag <br>, berikan penjelasannya!

```
tag <p> adalah tag untuk menunjukan/membuat paragrhap
sedangkan tag <br> adalah tag untuk memberikan jeda antara paragrhrap 1 dengan paraghrap lainya 
```
3.Apa perbedaan atribut title dan alt pada tag <img>, berikan penjelasannya!
```
Ketika gambar di tampilkan akan terlihat sebuah title. sedangkan, jika gambar gagal ditampilkan akan menampilkan teks atribut alt.
```
4.Untuk mengatur ukuran gambar, digunakan atribut width dan height. Agar tampilan gambar 
proporsional sebaiknya kedua atribut tersebut diisi semua atau tidak? Berikan penjelasannya!
```
kedua atribut harus di isi semua, karena jika hanya salah satunya maka gambar tersebut akan terlihat terlalu lebar atau tinggi.
```
5.Pada link tambahkan atribut target dengan nilai atribut bervariasi ( _blank, _self, _top, 
_parent ), apa yang terjadi pada masing-masing nilai antribut tersebut?
 ```
 Menambah hyperlink baru dan menampilkan yg telah di tentukan, untuk blank akan menambah tab baru terlebih dahulu maka akan menampilkan link yang dituju.
 ```


