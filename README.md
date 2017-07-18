# OOPExam170717
Merupakan jawaban atas soal ujian OOP tgl 17 Juli 2017 dari Bp.AlfaIrawan

1. Dari list di bawah ini manakah yg tidak termasuk dalam bagian object  
[ ] private  
[ ] public  
[ ] classes  
[x] __contructor   

2. Manakah yang bukan merupakan visibility dalam sebuah object 
[ x] protect  
[ ] private 
 [ ] protected  
[ ] public   

3. Method apa yang digunakan untuk menginisialisasi / memberikan nilai pada sebuah Class  
[x] _constructor  
[ ] _destructor  
[ ] extend  
[ ] encapsulation   

4. Dari list di bawah ini manakah yang di gunakan sebagai penghubung object dengan object lain / frontend  
[ x] require & include  
[ ] include & using  
[ ] require & using  
[ ] require, include & using   

5. Manakah dari list di bawah ini yang benar dalam penulisan method  
[ ] public order($order_id) { }  
[ ] private function order { }  
[ ] protected order function() { }  
[x] private function order($order_id) { }  

Soal Cerita
Tentukan 5 object dari sebuah Bisnis yanga anda akan buat, yang dimana didalamnya terdapat satu atau lebih dari beberapa attribute dan method (Jika ada nilai yang di inisialisasi dalam contructor dan destructor akan menjadi menilai plus). Buatlah object-object tersebut dalam bentuk Class Diagram yang kemudian di ubah menjadi code yang terstruktur menjadi OOP.

KopKarPurwa :
Bisnis yang akan dibuat adalah berupa web apps untuk Koperasi Karyawan.
5 Object dengan masing-masing Attribut dan Methodnya adalah sebagai berikut :

1. Membership :
	- Atribut : Nama, Dept, nomor karyawan, status karyawan
	- Method : Verifikasi, Persetujuan, penolakan
2. Transaksi :
	- Atribut : produk, harga
	- Method : jumlah produk, kalkulasi  pembelanjaan, verifikasi limit pembelanjaan
3. Product :
	- Atribut : Produt list, product price, 
	- Method : product clasification, product summary
4. Payment :
	- Atribut : payment method (Salary deduction, Cash, Debit Card, Credit Card, Transfer) 
	- Method : Account verifikasi, Salary deduction, Account deduction, Payment rejection, Refund Payment
5. Delivery :
	- Atribut : alamat, method (will call, courier, shiping)
	- Method : Courier assigment, correspondence, delivery payment






