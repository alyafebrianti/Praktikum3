tugas praktikum 3 bahasa pemrograman 
nama: alya febrianti
kelas : TI 24.A.1
# Program Mencari Bilangan Terbesar
Program sederhana untuk mencari nilai terbesar dari sekumpulan bilangan yang dimasukkan oleh pengguna menggunakan loop while True dan break statement.
## Deskripsi Program
Program ini dibuat menggunakan bahasa Python dengan fitur:
- Menggunakan while True untuk perulangan tak terbatas
- Menggunakan break statement untuk menghentikan program
- Membandingkan setiap input dengan nilai maksimum yang tersimpan
- Menampilkan bilangan terbesar yang ditemukan
 ## Flowchart Program
 ![Flowchart](Flowchart.png)

 ## Kode Programan 
```python
max = 0
bilangan = int(input("masukan bilangan :"))
while bilangan != 0 :
    if bilangan > max :
        max = bilangan
    bilangan = int(input("masukan bilangan :"))

print (f"bilangan terbesar= {max}")
```

## Contoh Output
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

## Cara Kerja Program

