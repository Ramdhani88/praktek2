# praktek2
## Belajar Dasar CSS
### Membuat Halaman Pertama
Kodingan hasil halaman pertama seperti gambar dibawah ini <img width="960" alt="ss1" src="https://user-images.githubusercontent.com/81758035/114271772-56826200-9a3d-11eb-9e06-57c43c1a47a2.png">
Selanjutnya hasil dari codingan dibuka dibrowser dan hasilnya seperti gambar dibawah ini <img width="960" alt="ss9" src="https://user-images.githubusercontent.com/81758035/114272452-6cdded00-9a40-11eb-8372-4906e3643493.png">
### Mendeklarasikan CSS Internal
Kemudian masukkan css internal pada kolom head ![ss3](https://user-images.githubusercontent.com/81758035/114272188-4e2b2680-9a3f-11eb-9334-40e95485f19f.jpg)
### Modul Praktikum Web
Dan hasil css internal yang kita buat akan menjadi seperti ini ![ss4](https://user-images.githubusercontent.com/81758035/114273156-45d4ea80-9a43-11eb-82e1-8aea0bf362d7.jpg)
### Membuat CSS Eksternal
Buatlah dengan cara berikut ini dengan membuat file baru dengan format .css <img width="960" alt="ss10" src="https://user-images.githubusercontent.com/81758035/114272858-ffcb5700-9a41-11eb-9263-ed4f533bfb42.png">
dan buatlah tag link untuk merujuk file css yang sudah dibuat contoh<img width="960" alt="ss11" src="https://user-images.githubusercontent.com/81758035/114273375-fe029300-9a43-11eb-8ac9-638c0a40b5e5.png">
Lakukan save pada vs.code dan selanjutnya refresh browser dan hasilnya akan seperti berikut <img width="640" alt="ss12" src="https://user-images.githubusercontent.com/81758035/114273530-91d45f00-9a44-11eb-9efe-7b901006220a.png">

1 Lakukan eksperimen dengan mengubah dan menambah properti dan nilai pada kode CSS
dengan mengacu pada CSS Cheat Sheet yang diberikan pada file terpisah dari modul ini.
Jawab : Sudah dan berhasil

2 Apa perbedaan pendeklarasian CSS elemen h1 {...} dengan #intro h1 {...}? berikan
penjelasannya!
Jawab : perbedaannya adalah elemen didalam h1 berisi {
            font-size: 24px;
            color: #0F189F;
            text-align: center;
            padding: 20px 10px;
        Sedangkan #intro h1 berisi
            text-align: left;
            border: 0;
            color: #fff;


3 Apabila ada deklarasi CSS secara internal, lalu ditambahkan CSS eksternal dan inline CSS pada
elemen yang sama. Deklarasi manakah yang akan ditampilkan pada browser? Berikan
penjelasan dan contohnya!
Jawab : Deklarasi dibagian background CSS eksternal akan berubah warna

4 Pada sebuah elemen HTML terdapat ID dan Class, apabila masing-masing selector tersebut
terdapat deklarasi CSS, maka deklarasi manakah yang akan ditampilkan pada browser?
Berikan penjelasan dan contohnya! ( < p id="paragraf-1" class="text-paragraf"> )
Jawab : Deklarasi keduanya dapat ditampilkan di web browser

