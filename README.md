# labspy02
Tugas Pertemuan ke-7

#Lab2 Latihan 1 (Program Menentukan bilangan terbesar dari 2 buah bilangan):
    1. langkah pertama membuat fungsi main() agar kode nudah dipelihara dan reusable
    2. kita membutuhkan 3 variabel dalam kasus ini adalah ‘a‘, ‘b‘, ‘maks‘ untuk menampung nilai yang akan diinput oleh user lalu input yang tadinya string di konversi ke integer menggunakan fungsi build-in int() & menentukan input user
langkah selanjutnya kita bandingkan dengan operator ‘ > ‘ lalu kita cek dengan if else seperti ini:
Menentukan Nilai Bilangan  dengan if else
   if a > b:
       maks = a
   else:
       maks = b

nah nilai yang tadi kita bandingkan kita tampung di variabel ‘maks’ yang nilainya berubah ubah berdasarkan nilai a dan b:
mencetak nilai maksimum
print('Nilai Terbesar adalah %d' % maks)


#Lab2 Latihan 2 (Program Mengurutkan Data dari yag Terkecil hingga Terbesar Berdasarkan 3 Inputan):
def menunjukan fungsi mengurutkan data yang diinput
def pengulangan():
    print ('Program Mengurutkan Data')
    a=int(input('bilangan ke 1 = '))
    b=int(input('bilangan ke 2 = '))
    c=int(input('bilangan ke 3 = '))
if digunakan untuk pengecekan kondisi tertentu
if a<b and a<c:
        if b<c:
            print(a, b, c)
        else:
            print(a, c, b)
    elif b<a and b<c:
        if a<c:
            print(b, a, c)
        else:
            print(b, c, a)
    else:
        if a<b:
            print(c, a, b)
        else:
            print(c, b, a)
    print('')
    
pengulangan()


#Lab3 Latihan 1 (Program Perulangan Bertingkat):
1. Dalam program ini, loop for terluar adalah angka iterasi dari 1 hingga 10. Range() mengembalikan 10 angka. Jadi jumlah iterasi dari loop luar adalah 10
2. Pada iterasi pertama dari loop bersarang, jumlahnya adalah 1. Pada iterasi berikutnya, itu 2. dan seterusnya hingga 10
3. Selanjutnya, Untuk setiap iterasi loop luar, loop dalam akan dieksekusi sepuluh kali. Loop dalam juga akan dieksekusi sepuluh kali karena kita mencetak tabel perkalian hingga sepuluh
4. Dalam setiap iterasi loop dalam, kami menghitung perkalian dua angka


#Lab3 Latihan 2 (Program Menampilkan Bilangan Acak yang lebih kecil dari 0,5):
1.Memasukan/ import fungsi RANDOM terlebih dahulu

2.Deklarasi integer , masukkan jumlah n :

3.Memasukan deskripsi kombinasi for untuk menyelesaikannya.

4.Memasukan nilai jumlah (n) : 5

5.Mencetak data ke 1 sampai 5 dengan hasil nilai kurang dari 0,5.

6.Selesai
    
