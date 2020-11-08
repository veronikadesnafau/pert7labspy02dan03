## Pertemuanke7Labspy02dan03
**NAMA      : VERONIKA DESNA ERNAYANTI FAU** <br>
**NIM       : 312010333** <br>
**KELAS 	  	: TI 20-A2** <br>
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

![1](https://user-images.githubusercontent.com/73016496/98446806-d6d12e00-2152-11eb-97e5-fac6671fd17c.png)


#### Flowchart 

![flowchat](https://user-images.githubusercontent.com/73016496/98447816-6201f200-215a-11eb-97b7-53e2a1f416a6.png)


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

#### OUTPUT
Dibawah ini merupakan hasil output dari syntax diatas

![2](https://user-images.githubusercontent.com/73016496/98447818-69290000-215a-11eb-89b7-095022ad3a18.png)


#### Latihan 2
<img width="368" alt="ss 4(prkt 3)" src="https://user-images.githubusercontent.com/73053784/98434416-de1c1b80-2101-11eb-910b-3c0b64e654c1.png">

### SYNTAX
berikut merupakan syntax untuk menampilkan program diatas
``` python
print('===== Menentukan Bilangan Terbesar =====')

max=0

while True:

    a=int(input('Masukkan Bilangan = '))

    if max < a:

        max = a

    if a==0:

        break

print('Bilangan Terbesar adalah = ',max)
```

Penjelasan Program Bilangan Terbesar Dari n Buah Data Yang Dimasukkan.
``` python
print('===== Menentukan Bilangan Terbesar =====')
```
Untuk menampilkan kalimat Menampilkan Bilangan Terbesar Dari n Buah Data Yang Diinputkan.
``` python
max=0
```
untuk menentukan nilai max nya adalah 0.
``` python
while True:
```
Untuk perulangan hingga waktu yang tidak di tentukan atau selamanya.
``` python
a=int(input('Masukkan Bilangan = '))
```
untuk menginput tipe data interger ( bilangan bulat ).
``` python
 if max < a:
```
jika max kurang dari a maka
``` python
 max = a

    if a==0:

        break
```
jika a= 0 maka akan berhenti dengan syarat break yang terpenuhi.
``` python
print('Bilangan Terbesar adalah = ',max)
```
Menampilkan Bilangan Terbesar Adalah : Nilai maximumnya.


#### OUTPUT
Dibawah ini merupakan hasil output dari syntax diatas

![3](https://user-images.githubusercontent.com/73016496/98457097-c5217200-21b6-11eb-8305-452ef7c11326.png)


#### Program 1
### SYNTAX
berikut merupakan syntax untuk menampilkan program diatas
``` python
x=100000000

sum=0

y=0
lb = [int(0), int(0), int(x) * .1, int(x) * .1, int(x) * .5, int(x) * .5, int(x) * .5, int(x) * .2]

print('modal awal seorang pengusaha:', x)

for i in lb :

    sum=sum+i

    y+=1

    print('laba bulan ke-', y, 'sebesar :', i)

print('total laba yang didapat adalah:', sum)
```
Penjelasan Program
``` python
x=100000000
```
Menampilkan kalimat Modal Awal : dan data yang berisi di n yaitu 100000000.
``` python
lb = [int(0), int(0), int(x) * .1, int(x) * .1, int(x) * .5, int(x) * .5, int(x) * .5, int(x) * .2]
```
Untuk Mendeklarasikan presentase laba tiap bulan dan di kali dengan x atau data inputan modal investasi yaitu 100000000.
``` python
print('laba bulan ke-', y, 'sebesar :', i)
```
untuk perulangan data dengan isi data yaitu Y dengan menampilkan urutan laba perbulan sesuai range yang di tentukan dengan hasil ke untukan yang di inpput dari data Y.
``` python
print('total laba yang didapat adalah:', sum)
```
berisi data penjumlahan data angka yang ada didalam kode A,B,C,D,E,F,G,H yang akan di tampilakan atau dicetak di jumlah laba selama 8 bulan.

#### OUTPUT
Dibawah ini merupakan hasil output dari syntax diatas
