# Praktikum 2: CSS Dasar
```
Ridho Prasetya
311910621
TI.19.A2
```
## Langkah 1
### Membuat Dokumen HTML seperti berikut.
![1](https://user-images.githubusercontent.com/56241745/113596730-efdbfd80-9664-11eb-9465-ed41afa63cf0.png)
## Langkah 2
### Kemudian tambahkan deklarasi CSS internal seperti berikut pada bagian `head` dokumen.
![2](https://user-images.githubusercontent.com/56241745/113596901-2285f600-9665-11eb-87b5-e766be0da373.png)
## Langkah 3
### Kemudian tambahkan deklarasi inline CSS pada tag `<p>` seperti berikut.
![3](https://user-images.githubusercontent.com/56241745/113596927-287bd700-9665-11eb-9ded-7eaef6b6c744.png)
## Langkah 4
### Membuat CSS eksternal dan Kemudian tambahkan tag `<link>` untuk merujuk file css yang sudah dibuat pada bagian `<head>`.
![4](https://user-images.githubusercontent.com/56241745/113596974-3598c600-9665-11eb-8485-a8001fc7a76c.png)
## Langkah 5
### Selanjutnya menambahkan CSS Selector menggunakan ID dan Class Selector, Pada file style_eksternal.css.
![5](https://user-images.githubusercontent.com/56241745/113597004-434e4b80-9665-11eb-826b-8dbec817231b.png)
## Pertanyaan dan Tugas
### 1. Lakukan eksperimen dengan mengubah dan menambah properti dan nilai pada kode CSS dengan mengacu pada CSS Cheat Sheet yang diberikan pada file terpisah dari modul ini.
#### Saya melakukan beberapa eksperimen seperti mengubah nilai yang hasilnya mengubah ukuran ataupun warna dan mengganti background.
![6](https://user-images.githubusercontent.com/56241745/113597057-5b25cf80-9665-11eb-878e-0317ae898c91.png)
### 2. Apa perbedaan pendeklarasian CSS elemen h1 {...} dengan #intro h1 {...}? berikan penjelasannya!
#### Pendeklarasian CSS elemen h1 mengubah tampilan seluruh elemen yang memiliki tag h1, sedangkan #intro h1 hanya mengubah tampilan elemen h1 yang memiliki id #intro.
### 3. Apabila ada deklarasi CSS secara internal, lalu ditambahkan CSS eksternal dan inline CSS pada elemen yang sama. Deklarasi manakah yang akan ditampilkan pada browser?Berikan penjelasan dan contohnya!
#### Setelah saya mencoba, jika mendeklarasikan CSS pada elemen yang sama namun dengan isi deklarasi yang berbeda, maka semua deklarasi CSS tersebut akan ditampilkan. Contohnya:
![7](https://user-images.githubusercontent.com/56241745/113597849-7fce7700-9666-11eb-9305-29cc6a611f68.png)
#### Namun jika isi dari ketiga deklarasi CSSnya sama semua, maka browser hanya akan menampilkan salah satunya, dengan urutan Inline CSS, Eksternal CSS, dan yang terakhir Internal CSS.
![8](https://user-images.githubusercontent.com/56241745/113597896-91b01a00-9666-11eb-8adb-9dc19629eaea.png)
### 4. Pada sebuah elemen HTML terdapat ID dan Class, apabila masing-masing selector tersebut terdapat deklarasi CSS, maka deklarasi manakah yang akan ditampilkan pada browser? Berikan penjelasan dan contohnya!
#### Kedua deklarasi tersebut akan tampil, namun selector ID yang akan tampil jika deklarasinya ada yang sama antara ID dan Class.
![9](https://user-images.githubusercontent.com/56241745/113597962-a55b8080-9666-11eb-8fa0-baa4b217b667.png)
