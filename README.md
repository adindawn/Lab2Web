### PRAKTIKUM 2: CSS DASAR 

Nama  : Adinda Aulia Nabila Putri

Nim   : 312410309

Kelas : TI.24.A.4 

## LANGKAH PRAKTIKUM 

# 1. Membuat dokumen HTML 

   Membuat dokumen HTML dengan nama file lab2_css_dasar.HTML di VSCode. Pada elemen ```<header>``` yang dimana menampilkan judul utama menggunakan elemen ```<hi>```, lalu ada elemen ```<nav>``` yang dimana elemen ini berfungsi sebagai menu navigasi. 
   
<img width="790" height="527" alt="Screenshot 2025-10-02 203310" src="https://github.com/user-attachments/assets/b29b4811-7b7f-433f-b967-9119a305fa56" />

   Berikut Hasil pada Browser 

<img width="1341" height="367" alt="Screenshot 2025-10-02 213111" src="https://github.com/user-attachments/assets/2cede114-06d8-449c-87b0-42ee776b18df" />


# 2. Mendeklarasikan CSS Internal 

   CSS Internal terdapat tag <style> yang diletakkan pada bagian <head> berfungsi untuk memberikan tampilan pada elemen-elemen HTML secara langsung tanpa membuat file CSS terpisah. Misalnya, mengatur font, warna teks, dan ukuran heading.

  <img width="559" height="389" alt="Screenshot 2025-10-02 220007" src="https://github.com/user-attachments/assets/03fece86-3951-4993-8138-97282156e13f" />

    Berikut Hasil pada Browser 

<img width="1341" height="388" alt="Screenshot 2025-10-02 220142" src="https://github.com/user-attachments/assets/a0420096-b14a-4f1d-8ded-2e6829f9a3fc" />


# 3. Menambahkan inline CSS

  Inline CSS ditulis langsung di dalam tag HTML menggunakan atribut ```style```. Contohnya seperti <p style="text-align: center; color: #ccd8e4;">. Inline CSS berlaku pada satu elemene tempat ditulis. Misalnya, memberi warna pada satu paragraf. 

  <img width="594" height="68" alt="Screenshot 2025-10-02 221045" src="https://github.com/user-attachments/assets/7fb76afc-59f8-4a90-8157-a757561d6cb8" />

   Berikut Hasil pada Browser 

<img width="1329" height="371" alt="Screenshot 2025-10-02 221023" src="https://github.com/user-attachments/assets/82dbfd0c-5476-4b7d-acd9-b1de9a2213d1" />


# 4. Membuat CSS eksternal 

  Membuat file baru dengan nama ```style_eksternal.css```. lalu dihubungkan ke HTML dengan tag <link>,  dibagian <head>, dengan ini tampilan HTML akan mengikuti aturan dari file CSS Eksternal. 

   <img width="422" height="272" alt="Screenshot 2025-10-02 221935" src="https://github.com/user-attachments/assets/cb22b8b1-9c14-411b-a93e-0ffc9d0f2bc7" />

   <img width="522" height="41" alt="Screenshot 2025-10-02 224938" src="https://github.com/user-attachments/assets/8993d5ef-279a-4cec-bc4a-302bb8b5714c" />

    Berikut Hasil pada Browser 

 <img width="1357" height="388" alt="Screenshot 2025-10-02 223539" src="https://github.com/user-attachments/assets/30c776f1-b9df-4ad0-a291-53ee78524c90" />

 
 # 5. Meenambahkan CSS selector 

    CSS Selector digunakan untuk memilih elemen HTML yang ingin diatur tampilannya.
    
     * ID selector (#id), hanya beelaku untuk satu elemen dengan id tertentu.
    
     * Class selector (.class), bisa dipakai dibanyak elemen. 

   <img width="505" height="422" alt="Screenshot 2025-10-02 223804" src="https://github.com/user-attachments/assets/f0c8b2a5-dacc-42c0-a4b1-7bbf0d3b33e5" />

     Berikut Hasil pada Browser 

<img width="1358" height="481" alt="Screenshot 2025-10-02 223849" src="https://github.com/user-attachments/assets/e82bbf36-9c18-4aff-9e38-1c9408d73aee" />


## Pertanyaan dan tugas 

# 1. Lakukan eksperimen dengan mengubah dan menambah properti dan nilai pada kode CSS dengan mengacu pada CSS Cheat Sheet yang diberikan pada file terpisah dari modul ini. 

   Saya mencoba menambahkan beberapa properti CSS, contonya:

<img width="562" height="548" alt="Screenshot 2025-10-02 230607" src="https://github.com/user-attachments/assets/ece5b0bd-f7c0-4853-9884-41ab14bc0d66" />

  Berikut Outputnya 

<img width="843" height="247" alt="Screenshot 2025-10-02 230553" src="https://github.com/user-attachments/assets/d5f0fd0b-db1d-4347-8b35-50776e33e01b" />


# 2. Apa perbedaan pendeklarasian CSS elemen h1 {...} dengan #intro h1 {...}? berikan penjelasannya!

<img width="567" height="488" alt="Screenshot 2025-10-02 231432" src="https://github.com/user-attachments/assets/da1eb1dc-150b-402a-bc8f-1229f9b6f3e8" />

   Berikut Outputnya 

<img width="648" height="249" alt="Screenshot 2025-10-02 231459" src="https://github.com/user-attachments/assets/5b57a8b8-f2a6-4dd3-b2ba-aa377ca16953" />

Penjelasannya : 
Perbedaan antara h1 { ... } dengan #intro h1 { ... } terletak pada jangkauan pengaruhnya. Jika kita menuliskan h1 { ... }, maka aturan CSS tersebut berlaku untuk semua elemen heading <h1> di dalam halaman HTML. Jadi setiap judul dengan tag <h1> akan otomatis mengikuti style yang sudah ditentukan, misalnya warna, ukuran font, atau tata letak. Lalu jika, #intro h1 { ... } jauh lebih spesifik karena hanya akan diterapkan pada elemen <h1> yang berada di dalam suatu elemen yang memiliki atribut id="intro". Artinya, tidak semua <h1> akan berubah tampilannya, melainkan hanya <h1> yang ada di dalam bagian tertentu, yaitu yang dibungkus oleh elemen dengan id tersebut.


# 3. Apabila ada deklarasi CSS secara internal, lalu ditambahkan CSS eksternal dan inline CSS pada elemen yang sama. Deklarasi manakah yang akan ditampilkan pada browser? Berikan penjelasan dan contohnya! 

  <img width="580" height="476" alt="Screenshot 2025-10-02 233308" src="https://github.com/user-attachments/assets/1bb0fe7d-7377-4299-8ad4-7f2cba212cef" />

  <img width="359" height="107" alt="Screenshot 2025-10-02 233430" src="https://github.com/user-attachments/assets/6e8687d0-9ea5-4fd4-a1ed-cb4dac8440a4" />

       Berikut Outputnya

 <img width="469" height="196" alt="Screenshot 2025-10-02 233251" src="https://github.com/user-attachments/assets/b15d7eb4-b9ef-4304-aa08-1c01d486eec2" />

Penjelasannya : 

 Kalau elemen HTML mendapat aturan dari internal CSS, eksternal CSS, dan inline CSS sekaligus, maka yang ditampilkan browser adalah aturan dari inline CSS.karena CSS bekerja berdasarkan prinsip cascading atau urutan prioritas. Prioritas paling rendah ada pada eksternal CSS, lalu di atasnya internal CSS, dan yang paling tinggi adalah inline CSS. Jadi meskipun sebuah elemen sudah diatur tampilannya melalui file CSS eksternal atau bagian <style> internal, jika pada tag elemen tersebut ditambahkan atribut style, maka inline CSS-lah yang akan dipakai browser untuk menampilkan tampilan akhir.


# 4. Pada sebuah elemen HTML terdapat ID dan Class, apabila masing-masing selector tersebut terdapat deklarasi CSS, maka deklarasi manakah yang akan ditampilkan pada browser? Berikan penjelasan dan contohnya!  ( <p id="paragraf-1" class="text-paragraf"> ) 

   <img width="691" height="569" alt="Screenshot 2025-10-02 235039" src="https://github.com/user-attachments/assets/f160a53e-725b-4118-940f-03a434dc106c" />

   Berikut Outputnya 

<img width="795" height="295" alt="Screenshot 2025-10-02 235024" src="https://github.com/user-attachments/assets/49746321-efbb-4829-8f8d-0bb03b5cf8db" />

Penjelasannya :

Jika sebuah elemen HTML diberi ID dan juga Class, lalu keduanya memiliki deklarasi CSS yang berbeda, maka aturan yang berasal dari ID akan lebih diutamakan oleh browser. Hal ini karena selector ID memiliki tingkat spesifisitas yang lebih tinggi dibandingkan dengan selector Class. I


   
