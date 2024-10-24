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

Program yang saya buat berfungsi untuk mencari bilangan terbesar dari input yang diberikan pengguna. Pertama, program menginisialisasi variabel `max` dengan nilai 0. Kemudian, program meminta pengguna untuk memasukkan bilangan. Jika bilangan yang dimasukkan bukan 0, program akan memeriksa apakah bilangan itu lebih besar dari nilai `max`. Jika iya, nilai `max` akan diperbarui dengan bilangan tersebut. Proses ini berulang hingga pengguna memasukkan 0, yang menandakan akhir dari input. Setelah itu, program mencetak bilangan terbesar yang ditemukan. 

bagian output
Dalam contoh ini, pengguna memasukkan beberapa bilangan, dan ketika memasukkan 0, program menghentikan input dan mencetak bilangan terbesar yang dimasukkan, yaitu 90. Setelah itu, proses selesai dengan kode pengembalian 0, yang menandakan tidak ada kesalahan. Pengguna kemudian diminta untuk menekan Enter untuk keluar dari terminal.



