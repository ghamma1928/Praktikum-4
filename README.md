# Praktikum 4 Bahasa Pemograman Python

**Belajar Struktur Kondisi Dan Perulangan Pada Python**

1. Buat folder dengan nama Praktikum4 lalu didalamnya kita buat dua folder yaitu `Struktur-Kondisi` & `Perulangan` dan didalamnya buat file `Latihan 1.py` & `Latihan    2.py` dimasing masing folder. Berikut contohnya :

![Screenshot (84)](https://user-images.githubusercontent.com/115474950/199670798-2b8a5df1-3a3e-4fa5-9f0d-aa377249ebff.png)

2. Selanjutnya kita buka file `Struktur-Kondisi` > `Latihan 1.py` lalu ketik atau isi codingan berikut :

 `# menerima input yang diketik dan menyimpannya didalam variable`
 
 `bilanganSatu = input("Masukan bilangan Pertama : ")`
 
 `bilanganKedua = input("Masukan bilangan Kedua : ")`

 `# mengkonversi input string ke integer karena method input() selalu mengembalikan type data string`
 
 `bilanganSatu = int(bilanganSatu)`
 
 `bilanganKedua = int(bilanganKedua)`

 
 `# mengecek untuk menentukan bilangan terbesar dari kedua bilangan`
 
 `if bilanganSatu > bilanganKedua:`
 
     `print("Bilangan ", bilanganSatu, "lebih besar dari bilangan", bilanganKedua)`
 
 `else:`
     
     `print("Bilangan ", bilanganKedua, "lebih besar dari bilangan", bilanganSatu)`
     
![Screenshot (70)](https://user-images.githubusercontent.com/115474950/199671912-360aa116-27b4-43e4-8500-3e01258cafed.png)

Jika sudah lalu kita jalankan dengan cara ketikan diterminal yaitu `python Latihan1.py` !!! perlu diingat kita harus berada didirektor `struktur-kondisi`. Lalu akan tampil hasilnya seperti dibawah ini

![Screenshot (71)](https://user-images.githubusercontent.com/115474950/199672143-fa2f6a3a-d78b-4253-9750-7ef884f46da4.png)

3. Selanjutnya kita buka `Latihan2.py` pada folder `struktur-kondisi` lalu ketikan codingan berikut :

     `# variable angka untuk menampung jumlah angka yang diinputkan berupa array/list`
     
   `angka = []`
   
   `# variable bilangan untuk menentukan jumlah bilangan yang diinginkan bilangan = input("Masukan jumlah bilangan yang diinginkan : ")`

   `# mengkonversi input string ke integer karena method input() selalu mengembalikan type data string`
   
   `bilangan = int(bilangan)`

   `print("Program mengurutkan data ")`

   `# melakukan perulangan berdasarkan jumlah dari variable bilangan`

   `for i in range(0, bilangan):`
   
       `# melakukan perulangan  input sampai jumlah dari variable bilangan yang sudah ditentukan`
       
       `# misal bilangannya  sama dengan 4 maka akan dimunculkan input 4 kali lalu disimpan di variable => data`

       `data = int(input("Masukan Bilangan ke-" + str(i+1) + " : "))`

       `# menambahkan isi dari variable data ke variable angka yang type datanya berupa array`
       
       `# contoh input pertama [3] => input ke-dua [3,5] => input ke-tiga [3,5,2] => input ke-empat[3,5,2,9] dan seterusnya sesuai jumlah variable bilangan angka.append(data)`

   `# menampilkan hasil program`
   
   `# method sorted() berfungsi untuk mengurutkan nilai dari terkecil ke terbesar, print("Bilangan yang sudah diurutkan dari terkecil ke terbesar", sorted(angka))`

![Screenshot (72)](https://user-images.githubusercontent.com/115474950/199673560-fbfc2c32-ee58-45ef-9671-d5fa98fdcbdf.png)

Jika sudah lalu kita jalankan dengan cara ketikan diterminal yaitu python `Latihan2.py` !!! perlu diingat kita harus berada didirektor `struktur-kondisi`. Lalu akan tampil hasilnya seperti dibawah ini

![Screenshot (73)](https://user-images.githubusercontent.com/115474950/199673792-41df2a4a-a789-4e62-bc45-04c922c3083a.png)

4. Selanjutnya kita buka `Latihan1.py` pada folder `perulangan` lalu ketikan codingan berikut :

   `# melakukan perulangan dari 0 sampai 10`
   
   `for i in range(0, 10):`
   
     `# menampilkan variable i , (" " * 3) Artinya menambahkan spasi tiga kali lalu end => yaitu memulai baris baru setelah nilai terakhir`
     
       `print(i, " " * 3,  end='')`

       `# melakukan perulangan dari 1 sampai 10`
       
       `for j in range(1, 10):`
       
           `# menampilkan output j + i , (" " * 3) Artinya menambahkan spasi tiga kali lalu end => yaitu memulai baris baru setelah nilai terakhir`
           
           `print(j+i, " " * 3, end='')`
           
       `print()`

![Screenshot (79)](https://user-images.githubusercontent.com/115474950/199674701-a0cd9937-18ce-4982-87eb-d775fd6a9655.png)

Jika sudah lalu kita jalankan dengan cara ketikan diterminal yaitu `python Latihan1.py` !!! perlu diingat kita harus berada didirektor `perulangan`. Lalu akan tampil hasilnya seperti dibawah ini

![Screenshot (80)](https://user-images.githubusercontent.com/115474950/199674906-8f06a616-147f-49a5-a5a2-209917c77742.png)

5. Selanjutnya kita buka `Latihan2.py` pada folder `perulangan` lalu ketikan codingan berikut :

   `# import module random untuk mengenerate angka acak 0.3222...dst`
   
   `from random import random`

   `# variable jumlahNilai menampung input masukan lalu diconvert ke integer`
   
   `jumlahNilai = int(input('Masukan jumlah nilai yang ingin dicari : '))`

   `# variable nilaiRandom & kurangDariNolKomaLima berupa array/list untuk menyimpan data yang diperlukan nanti.`
   
   `nilaiRandom = []`
   
   `kurangDariNolKomaLima = []`

   `# looping data berdasarkan jumlahNilai,`
   
   `for i in range(0, jumlahNilai):`
   
       `# variable n = menyimpan angka random contoh: 0.9905112793033766`
       
       `n = random()`

       `# menambahkan n ke variable nilaiRandom`
       
       `# fungsi append() untuk menambahkan data ke dalam variable yang type datanya berupa array/list nilaiRandom.append(n)`

       `# apakah n < dari 0.5 ? jika iya tampilkan lalu break dan memulai ke angka random selanjutnya`
       
       `while n < 0.5:`

           `# menambahkan n jika kurang dari 0.5 ke variable kurangDariNolKomaLima`
           
           `kurangDariNolKomaLima.append(n)`

           `# menampilkan output n`
           
           `print("data ke -", str(i+1), " => ", n)`
           
           `break`

   `print()`
   
   `# menampilkan output keseluruhan nilai random`
   
   `print("Berikut keseluruhan nilai Random dari total ", jumlahNilai, "yaitu ", nilaiRandom)`

   `print()`
   
   `# menampilkan output keseluruhan nilai n < 0.5`
   
   `print("Berikut nilai yang kurang dari 0.5 berjumlah ", len(kurangDariNolKomaLima), "yaitu ", kurangDariNolKomaLima)`

![Screenshot (81)](https://user-images.githubusercontent.com/115474950/199676365-b7cabe8e-9507-4d15-b99b-ae637e8ce51d.png)

![Screenshot (82)](https://user-images.githubusercontent.com/115474950/199676390-78fd890d-f28f-414b-acf0-6ccb712c18a2.png)

Jika sudah lalu kita jalankan dengan cara ketikan diterminal yaitu `python Latihan2.py` !!! perlu diingat kita harus berada didirektor `perulangan`. Lalu akan tampil hasilnya seperti dibawah ini

![Screenshot (83)](https://user-images.githubusercontent.com/115474950/199676536-8695598c-6b08-43ec-87c1-11960622ca0f.png)

**Baik itu saja yang bisa saya kerjakan mengenai pembelajaran tentang kondisi dan perulangan pada bahasa pemograman bila ada kesalahan mohon di maafkan**

**Sekian Dan Terima Kasih**



