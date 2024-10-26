## Tugas Praktikum 3 Bahasa Pemrograman 
## Nama: Alya Febrianti
## Kelas : TI 24.A.1
# 1. Program Mencari Bilangan Terbesar dari 3 Variabel
Program sederhana menentukan bilangan terbesar dari tiga angka yang dimasukkan

## Deskripsi Program
- Meminta user memasukkan 3 bilangan berbeda
- function tersebut menggunakan nested if-else statement untuk membandingkan angka yang di inputkan
- Kemudian akan menampilkan Mana bilangan terbesar
- Lalu kita panggil kembali function mencari_biilangan_terbesar
- Lalu Output bilangan terbesar dari ketiga bilangan yang di input akan muncul
  
 ## Flowchart Program 1
 ![Flowchart](Flowchart1.png)
 
## 2. Program Mencari Bilangan Terbesar 
Program sederhana untuk mencari nilai terbesar dari sekumpulan bilangan yang dimasukkan oleh pengguna menggunakan loop while True dan break statement.

## Deskripsi Program
Program ini dibuat menggunakan bahasa Python dengan fitur:
- Menggunakan while True untuk perulangan tak terbatas
- Menggunakan break statement untuk menghentikan program
- Membandingkan setiap input dengan nilai maksimum yang tersimpan
- Menampilkan bilangan terbesar yang ditemukan
  
 ## Flowchart Program 2
 ![Flowchart](Flowchart.png)

 ## Kode Programan 1
 ```python
a = int(input("Masukkan bilangan A: "))
b = int(input("Masukkan bilangan B: "))
c = int(input("Masukkan bilangan C: "))

if a > b:
    if a > c:
        print("Terbesar adalah A")
        terbesar = a
    else:
        print("Terbesar adalah c")
        terbesar = c
else:
    if b > c:
        print("Terbesar adalah B")
        terbesar = b
    else:
        print("Terbesar adalah C")

print(f"Bilangan terbesar adalah: {terbesar}")
```
## Contoh Output 1
````markdown
Masukkan bilangan A: 31
Masukkan bilangan B: 20
Masukkan bilangan C: 0
Terbesar adalah A
Bilangan terbesar adalah: 31
````

 ## Kode Programan 2
```python
max = 0
bilangan = int(input("masukan bilangan :"))
while bilangan != 0 :
    if bilangan > max :
        max = bilangan
    bilangan = int(input("masukan bilangan :"))

print (f"bilangan terbesar= {max}")
```

## Contoh Output 2
````markdown
masukan bilangan :
90
masukan bilangan
20
masukan bilangan
60
masukan bilangan
70
masukan bilangan
0
bilangan terbesar=90


** Process exited - Return Code: 0 **
Press Enter to exit terminal
````

## Cara Kerja Program 1
Menerima input 3 bilangan (A, B, C) dari user Melakukan pengecekan dengan urutan: Apakah A > B? Jika ya: cek apakah A > C? Jika ya: A adalah terbesar Jika tidak: C adalah terbesar Jika tidak: cek apakah B > C? Jika ya: B adalah terbesar Jika tidak: C adalah terbesar Menampilkan bilangan terbesar yang ditemukan.

Program ini dimulai dengan meminta pengguna untuk memasukkan tiga angka. Setelah angka-angka tersebut dimasukkan, program menggunakan fungsi max() untuk menentukan angka yang paling besar di antara ketiga angka tersebut. Fungsi max()  secara otomatis membandingkan semua angka dan mengembalikan yang terbesar. Setelah menemukan angka terbesar, program menampilkan hasilnya kepada pengguna dengan kalimat yang jelas. Dengan cara ini, kode menjadi lebih ringkas dan mudah dibaca, tanpa perlu membuat banyak kondisi untuk perbandingan.

Bagian output menunjukkan bahwa program berhasil. Setelah memasukkan angka 31, 20, dan 0 program dengan tepat menemukan bahwa angka terbesar adalah 31. Ini menunjukkan bahwa logika untuk mencari angka terbesar berfungsi dengan baik.

## Cara Kerja Program 2

Program yang saya buat berfungsi untuk mencari bilangan terbesar dari input yang diberikan pengguna. Pertama, program menginisialisasi variabel max dengan nilai 0. Kemudian, program meminta pengguna untuk memasukkan bilangan. Jika bilangan yang dimasukkan bukan 0, program akan memeriksa apakah bilangan itu lebih besar dari nilai max. Jika iya, nilai max akan diperbarui dengan bilangan tersebut. Proses ini berulang hingga pengguna memasukkan 0, yang menandakan akhir dari input. Setelah itu, program mencetak bilangan terbesar yang ditemukan. 

Bagian Output
dalam contoh ini, pengguna memasukkan beberapa bilangan, dan ketika memasukkan 0, program menghentikan input dan mencetak bilangan terbesar yang dimasukkan, yaitu 90. Setelah itu, proses selesai dengan kode pengembalian 0, yang menandakan tidak ada kesalahan. Pengguna kemudian diminta untuk menekan Enter untuk keluar dari terminal.



