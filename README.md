NAMA : AAS NOVITASARI
NIM : 312210167
KELAS : TI.22.A1
Latihan

Buat sebuah list sebanyak 5 elemen dengan nilai bebas

Akses list :

Tampilkan elemen ke 3
Ambil nilai elemen ke 2 sampai elemen ke 4
Ambil elemen terakhir
Ubah elemen list :

Ubah elemen ke 4 dengan nilai lainnya
Ubah elemen ke 4 sampai dengan elemen terakhir
Tambah elemen list :

Ambil 2 bagian dari list pertama (A) dan jadikan list ke 2 (B)
Tambah list B dengan nilai string
Tambah list B dengan 3 nilai
Gabungkan list B dengan list A
Latihan
    print("Nama : Aas novitasari")
    print("NIM  : 312210167")

    print("Membuat List sebanyak 5 elemen dengan nilai bebas")
    # akses list
    a = [20, 40, 50, 60, 100]
    print(a) #Menampilkan semua elemen
    print(a[2]) #Menampilkan elemen ke 3
    print(a[1:3]) #Menampilkan elemen ke 2 sampai dengan ke 4
    print(a[4]) #Menampilkan elemen terakhir

    print("------------------------------------------")
    # ubah elemen list
    a[3] = 80 # Mengubah elemen ke 4 dengan nilai lainnya
    print(a[3]) # Menampilkan elemen ke 4 yang sudah diubah nilainya
    a[3:4] = 80, 90 # Mengubah elemen ke 4 sampai dengan elemen terakhir
    print(a[3:5]) # menampilkan elemen ke 4 sampai dengan elemen terakhir

    print("------------------------------------------")
    # tambah elemen list
    b = a[0:2] # Mengambil 2 bagian dari list pertama (a) dan jadikan list kedua (b)
    print(b)
    b.append(45) # Menambah list dengan nilai string
    print(b)
    b.extend([85, 90, 95]) # Menambah list b dengan 3 nilai
    print(b)
    c = a+b # Menggabungkan list b dengan list a
    print(c)

![Praktikum-5](https://user-images.githubusercontent.com/116045324/203505289-31deb066-f86c-4e19-817c-be25d711c36b.PNG)

Hasil run

![Hasil run praktikum-5](https://user-images.githubusercontent.com/116045324/203505440-947671f5-4d5c-4e9b-b663-1e257bdc7a5d.PNG)


#Tugas Praktikum

Buat program sederhana untuk menambahkan data kedalam sebuah
list dengan rincian sebagai berikut:
  • Progam meminta memasukkan data sebanyak-banyaknya (gunakan perulangan)
  • Tampilkan pertanyaan untuk menambah data (y/t?), apabila jawaban t (Tidak), maka program akan menampilkan daftar datanya. 
  • Nilai Akhir diambil dari perhitungan komponen nilai (tugas: 30%, uts: 35%, uas: 35%)
  • Buat flowchart dan penjelasan programnya
![image](https://user-images.githubusercontent.com/116045324/203505750-1530bedf-feb5-499b-b946-c5d8021c007f.png)


![image](https://user-images.githubusercontent.com/116045324/203505799-b2950613-f812-4806-8985-59f6bba4f57b.png)
Hasil run

![image](https://user-images.githubusercontent.com/116045324/203505870-d953d8c7-134a-42b8-87c1-03cbeac6e98d.png)


Flowchart
![image](https://user-images.githubusercontent.com/116045324/203505609-a358cede-0b98-44a2-8cf8-5f3b2ebb0cdd.png)



Penjelasan

Buatlah list berupa Nama, NIM, Nilai Tugas, Nilai UTS, Nilai UAS.
Lalu inputlah Nama, NIM, Nilai Tugas, Nilai UTS, Nilai UAS.
Lalu mencari nilai akhir dengan perhitungan nilai tugas 30%, nilai uts 35% dan uas 35% , dengan perintah float
Gunakan perintah append pada Nama, NIM, Nilai tugas, Nilai UTS, Nilai UAS untuk menambahkan 1 item ke elemen terakhir.
Jika ingin menambah list data ketik "ya" dan jika tidak ingin menambahkan list data ketik "tidak". Dengan perintah while jawab =="ya" dan if jawab =="tidak". Jawab input("Tambah data (ya/tidak)").
Gunakanlah perulangan for, dengan perintah for i in range(len(Nama)):. Fungsi "len" ialah untuk mengembalikan panjang (jumlah anggota) dari suatu objek.
Lalu cetak dengan perintah print
Selesai
