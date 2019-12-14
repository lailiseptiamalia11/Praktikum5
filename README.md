# Praktikum5
1.	Buatlah sebuah dictionary kosong seperti (data{})
2.	 Gunakan perulangan while True untuk memasukan menu pilihan, seperti : lihat, tambah, ubah, hapus, cari.
3.	Lalu gunakan kondisi if, elif, dan else untuk menjalankan menu pilihan tersebut.
4.	Gunakan looping for ( for x in data.items() ), lalu masukkan perintah print data dictionary.
5.	Untuk perintah Tambah inputkan data yang ingin Anda masukkan, seperti: Nama, Kelas, NIM, Nilai Tugas, Nilai UTS, Nilai UAS. Nilai Akhir dihitung dengan menggunakan rumus (Nilai Tugas * 30%) + (Nilai UTS * 35%) + (Nilai UAS * 35%).   
6.	Lalu menu untuk perintah Ubah. Inputkan data[nama] yang akan ubah. Gunakan kondisi if lagi ( if nama in                        data.keys() ), jika hasil ialah True maka Anda akan disuruh menginputkan data perubahannya. Tetapi jika hasilnya False, maka akan tercetak “Data ... tidak ada” dan muncul perintah untuk memasukkan inputan menu lagi.
7.	Menu dengan perintah Hapus. Inputkan data[nama] yang akan di hapus,dengan menggunakan kondisi if, jika hasilnya adalah True maka data akan terhapus dengan menggunakan perintah del data[nama], dan jika hasilnya False maka akan tercetak “data{0} tidak ada” dan muncul perintah untuk memasukkan inputan menu lagi.
8.	Yang terakhir adalah menu dengan perintah Cari. Inputkan data[nama] yang akan dicari. Gunakan kondisi if , jika hasilnya True maka akan tercetak data yang dicari dengan menggunakan perintah print data (nama, data[nama]). Dan jika hasilnya False maka akan tercetak “data{0} tidak ada” dan muncul perintah untuk memasukkan inputan menu lagi.
9.	Kondisi yang terakhir menggunakan else, jika menu yang Anda inputkan tidak ada pada menu maka Anda akan disuruh untuk menginputkan menu pilihan yang tersedia saja pada program. Jika menginputkan menu yang tidak ada dalam program maka akan tercetak “piilh data yang tersedia”
10.	Ini adalah menu pilihan yang berguna untuk :
    a.	(L)ihat = Untuk Menampilkan Tabel.
    b.	(T)ambah  = Untuk Menambahkan Data seperti : (Nim, Nama, Nilai Tugas, Nilai UTS, Nilai UAS, dan Nilai Akhir.
        Berikut contoh programnya:
        ![Screenshot (36)](https://user-images.githubusercontent.com/56987138/70382322-6d69fd80-198c-11ea-8282-ef26ba1785a1.png)
        
    c.	(U)bah = Untuk Mengubah Data yang telah Diinput.
         Berikut contoh programnya:
         ![Screenshot (37)](https://user-images.githubusercontent.com/56987138/70382323-6e029400-198c-11ea-94ba-6b32db1b38d7.png)

    d.	(H)apus = Untuk Menghapus Data yang diinput dengan mengetik (Nama)
    e.	(C)ari = Untuk Mencari Data yang Telah Diinput dengan mengetik (Nama)
         Berikut contoh programnya:
         ![Screenshot (38)](https://user-images.githubusercontent.com/56987138/70382346-ea957280-198c-11ea-828a-e2a9a3614e13.png)
         
    f.	(K)eluar Untuk Keluar dari Program
         Berikut contoh programnya:
         ![Screenshot (39)](https://user-images.githubusercontent.com/56987138/70382347-ea957280-198c-11ea-82fc-a17271279307.png)
         
     Berikut contoh flowchartnya:
     
     ![Screenshot (41)](https://user-images.githubusercontent.com/56987138/70842420-0cdc3400-1e56-11ea-960a-de1f020cb6f7.png)

