## Pertemuanke7Labspy02dan03
**NAMA      : VERONIKA DESNA ERNAYANTI FAU** <br>
**NIM       : 312010333** <br>
**KELAS 	  	: TI.20-A2** <br>
**MATKUL 	  : BAHASA PEMROGRAMAN** <br>

# Tugas Praktikum 2
<img width="397" alt="ss tugas prt 2" src="https://user-images.githubusercontent.com/73053784/98433061-862be780-20f6-11eb-9676-13ec9cfa9f1b.png">


### SYNTAX
berikut merupakan syntax untuk menampilkan program diatas

 ``` python
A = int(input("40"))
B = int(input("25"))
C = int(input("35"))
if A > B and A > C:
    print(A, "A")
elif B > A and B > C:
    print(B, "A")
else:
    print(C, "A")
```

#### OUTPUT
Dibawah ini merupakan hasil output dari syntax diatas

![1](https://user-images.githubusercontent.com/73016496/98446806-d6d12e00-2152-11eb-97e5-fac6671fd17c.png)z


#### Flowchart 

<img width="332" alt="ss 3(prkt 3)" src="https://user-images.githubusercontent.com/73053784/98434287-f3dd1100-2100-11eb-9acc-9b61c5149b62.png">


# Praktikum 3
<img width="334" alt="ss1 (prkt 3)" src="https://user-images.githubusercontent.com/73053784/98433884-7794fe80-20fd-11eb-94c1-f16262510bb3.png">

#### Latihan 1
<img width="332" alt="ss 3(prkt 3)" src="https://user-images.githubusercontent.com/73053784/98434287-f3dd1100-2100-11eb-9acc-9b61c5149b62.png">

### SYNTAX
berikut merupakan syntax untuk menampilkan program diatas

 ``` python
print('Bilangan Acak Yang Lebih Kecil Dari 0.5')
import random
n = int ( input ("Masukkan Nilai;"))
a = 0
for c in range (n):
    a+= 1
    b = random.uniform(.0, .5)
    print('data ke:', a, '==>', b)
    print("selesai")
```

Penjelasan program menampilkan n Bilangan acak yang lebih kecil dari 0.5
``` python
print('Bilangan Acak Yang Kecil Dari 0.5')
```
Untuk Menampilkan atau Mencetak kalimat Tampilkan n Bilangan Acak yang Lebih Kecil Dari 0.5.
``` python
n = int ( input ("Masukkan Nilai;"))
```
Untuk menentukan jumlah input yang di inginkan sesuai tipe data yaitu interger tipe data bilangan bulat import random Untuk pengulangan secara acak.
``` python
for c in range (n):
```
Untuk Pengulangan dengan range jumlah print.
``` python
 a+= 1
    b = random.uniform(.0, .5)
```
Untuk menampilkan atau mencetak urutan data sesuai jumlah inputan dengan hasil di bawah 0.5.


