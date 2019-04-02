
# Class vs Object

Kelas merupakan kerangka untuk menampung semua properti dan metode untuk menghasilkan sebuah objek. Struktur data yang bisa kita gunakan untuk mendefinisikan objek yang menyimpan data bersama-sama nilai-nilai dan perilaku (behavior). Kelas adalah suatu entitas yang merupakan bentuk program dari suatu abstraksi untuk permasalahan dunia nyata, dan instans dari class merupakan realisasi dari beberapa objek. Jika class secara umum merepresentasikan (template) sebuah object, maka sebuah instance adalah representasi nyata dari class itu sendiri.

![image.png](attachment:image.png)

#### Contoh membuat kelas :


```python
class kubus:
    def __init__(self,sisi):
        self.sisi=sisi
    def tampilkan(self):
        print("Luas =",self.sisi**2)
```

constructor menggunakan method bawaan Python yang bernama init. Metode __init__() adalah metode konstruktor, yaitu metode khusus yang digunakan Python untuk menginisialisasi pembuatan objek dari kelas tersebut. Setiap method harus memiliki parameter "(self)" yang artinya method tersebut dimiliki dan terdaftar ke class tersebut untuk membedakan dari method atau fungsi yang ada di luar class. Dari contoh kelas diatas, terdiri dari properti "sisi" dan metode "tampilkan". 

#### Contoh membuat objek :


```python
class kubus:
    def __init__(self,sisi):
        self.sisi=sisi
    def tampilkan(self):
        print("Panjang Sisi =",self.sisi,"\nLuas =",self.sisi**2)
objek=kubus(4)
objek.tampilkan()
```

    Panjang Sisi = 4 
    Luas = 16
    

untuk membuat objek, kita perlu membuat variabel yg sesuai dengan keinginan kita dan merupakan objek dari kelas yg ingin dibuat.
