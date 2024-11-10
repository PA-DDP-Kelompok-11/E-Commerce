Kelompok 11
Muhammad Rizky Febrianto (2409116045)
Abdurrahman Al Farissy (2409116055)
Dinda Aulia Rizky (2409116076)

# **E-Commerce**

Program ini merupakan program berbasis python yang dapat membantu para UMKM dan juga konsumen. Dengan adanya program ini, para UMKM dan konsumen agar dapat melakukan pencatatan, pengelolaan, dan penghitungan transaksi secara praktis dan efisien. Selain itu, program ini juga telah kami rancang sedemikian rupa sehingga tidak hanya memudahkan para UMKM untuk melakukan pengelolaan, tetapi juga memudahkan para konsumen untuk melakukan pembelian makanan ataupun barang.

# **Alur program**

## A. USER

### Tampilan awal
  
- Ketika user memilih opsi 1 : register 

![image](https://github.com/user-attachments/assets/dfe17397-dce5-46de-87f9-aaaf4efb31f9)

User akan diminta untuk input username dan password ketika berhasil akan tersimpan ke users.csv dan diarahkan untuk login ke dalam program.

Tampilan Ketika username sudah ada

![image](https://github.com/user-attachments/assets/e7213d7a-aa11-46ae-84b8-7d49691e0437)

-  Ketika user memilih opsi 2 : login

![image](https://github.com/user-attachments/assets/4f162fc3-fdb6-4199-a27b-83420b612ee9)

User akan diminta untuk menginput username dan password yang sudah dibuat, ketika berhasil akan diarahkan untuk memilih layanan yang tersedia dalam program.

Tampilan ketika input tidak sesuai atau username salah

![image](https://github.com/user-attachments/assets/cadadb48-3dc5-47e3-84db-df0efeaef275)

-  Ketika user memilih opsi 3 : keluar

![image](https://github.com/user-attachments/assets/d70d9056-0da2-4ef7-9e81-7fee80c0ad35)

Akan mengarahkan user untuk keluar dari program dan program akan berhenti untuk dijalankan.

### Tampilan menu layanan pada user

![image](https://github.com/user-attachments/assets/0ea8174c-de9b-47ab-af86-283c5580975c)

#### 1. Order makanan

-  Ketika user memilih opsi 1 : Order makanan

![image](https://github.com/user-attachments/assets/82c68f63-af53-4dd9-b18e-4a8c087d3ea4)

Gambar Order Makanan Fitur Sorting (asc)

![image](https://github.com/user-attachments/assets/3ae0f787-0f68-47b3-a02a-e00b942e4ca3)

Gambar Order Makanan Fitur Sorting (desc)

User akan diminta untuk memilih apakah ingin mengurutkan makanan berdasarkan harga. Jika user memilih ya, 

maka program akan kembali memberikan pilihan apakah ingin mengurutkan berdasarkan harga termurah (asc) atau termahal (desc). 

Lalu program akan mengeksekusi sesuai inputan yang diberikan user.

![image](https://github.com/user-attachments/assets/8d722d74-f974-4215-bbdb-e04147ea9198)

Namun, apabila user memilih untuk tidak mengurutkan harga maka program akan langsung memberikan pilihan untuk ‘searching menu makanan’ yang tersedia. Jika user memilih ya, 

fitur searching akan memudahkan user mencari menu makanan yang diinginkan dengan memasukkan kata kunci. Jika memilih tidak, akan diarahkan untuk melakukan transaksi

![image](https://github.com/user-attachments/assets/48fa34f0-ae1f-49eb-9366-2cc45b353958)

Setelah itu user akan diberikan pilihan untuk bayar sekarang atau masukkan pesanan ke dalam keranjang. Apabila user memilih opsi 1 : Beli sekarang. 

user akan diberikan pilihan lagi apakah ingin menggunakan kode voucher atau tidak. Setelah memilih, program akan menampilkan invoice dari menu barang yang dibeli.

Setelah itu, program akan memberikan pilihan apakah ingin memesan makanan yang lainnya. Jika user memilih ya, program akan kembali menerimpa input untuk order makanan. Jika, tidak maka akan menampilkan output.

Tampilan apabila voucher sudah tidak berlaku apabila sudah digunakan

![image](https://github.com/user-attachments/assets/2360670d-8df8-4e93-bf37-050e6dbdebfc)

Invoice order makanan

![image](https://github.com/user-attachments/assets/9329d8c9-4639-4190-ad0e-c78394dc7168)

Tetapi, jika kita memilih opsi 2 : masukkan ke keranjang. Maka menu makanan akan di masukkan ke dalam keranjang yang terhubung dengan csv.

![image](https://github.com/user-attachments/assets/44b26ad1-6d08-4b1b-aa33-c40653fe32d1)

#### 2. Order barang
   
![image](https://github.com/user-attachments/assets/05625a07-e7f6-4bab-a160-e2e1e5b3c58f)

Gambar Order barang sorting (asc)

![image](https://github.com/user-attachments/assets/7d6d50b0-9407-4d34-9bc1-fac8d0bf44c8)

Gambar Order Barang Sorting (desc)

User akan diminta untuk memilih apakah ingin mengurutkan barang berdasarkan harga. Jika user memilih ya, maka program akan kembali memberikan pilihan apakah ingin mengurutkan berdasarkan harga termurah (asc) atau termahal (desc). Lalu program akan mengeksekusi sesuai inputan yang diberikan user. 

![image](https://github.com/user-attachments/assets/e1b6dcd7-d8b2-4d6f-8b83-01562ed79f14)

Namun, apabila user memilih untuk tidak mengurutkan harga maka program akan langsung memberikan pilihan untuk ‘searching menu barang yang tersedia. Jika user memilih ya, fitur searching akan memudahkan user mencari menu barang yang diinginkan dengan memasukkan kata kunci. Jika memilih tidak, akan diarahkan untuk melakukan transaksi

![image](https://github.com/user-attachments/assets/50ca5f11-2f80-4e9d-a229-84c670e71c48)

Setelah itu user akan diberikan pilihan untuk bayar sekarang atau masukkan pesanan ke dalam keranjang. Apabila user memilih opsi 1 : Beli sekarang, user akan diberikan pilihan lagi apakah ingin menggunakan kode voucher atau tidak. Setelah memilih, program akan menampilkan invoice dari menu barang yang dibeli.

Setelah itu, program akan memberikan pilihan apakah ingin memesan barang yang lainnya. Jika user memilih ya, program akan kembali menerimpa input untuk order barang. Jika, tidak maka akan menampilkan output.

Tampilan apabila voucher sudah tidak berlaku atau sudah digunakan
 
![image](https://github.com/user-attachments/assets/b0765d6b-0d34-4824-818e-8a2d8b2e0763)

Invoice order barang

![image](https://github.com/user-attachments/assets/cae99d9d-23f9-4c8f-a422-b88e18c958e3)

Tetapi, jika kita memilih opsi 2 : masukkan ke keranjang. Maka menu makanan akan di masukkan ke dalam keranjang yang terhubung dengan csv.

![image](https://github.com/user-attachments/assets/6c2aec12-90d5-4f0e-a61b-b3b1ca0f2cb5)

#### 3. Cek voucher
 
![image](https://github.com/user-attachments/assets/bbf0e47f-4be5-4f88-9bcd-780c720d55b7)

Ketika user memilih opsi 3 : Cek voucher, akan menampilkan seluruh voucher yang tersedia. 

#### 4. Cek keranjang

![image](https://github.com/user-attachments/assets/5a334818-b4d4-4fd8-a0c2-5f78eb9e664f)
 
Gambar Cek Keranjang Check Out (semua)

Ketika user memilih opsi 4 : Cek keranjang dan memilih untuk check out ‘semua’,maka semua item pada keranjang akan segera terbeli dan saldo akan terpotong sesuia jumlah barang yang ada.

 ![image](https://github.com/user-attachments/assets/48a6f8f7-c642-45cc-bf0a-a1018d194dba)

Gambar 3. 23 Cek Keranjang Check Out (pilih)

Ketika user menginput untuk ‘pilih’, user akan diminta untuk memilih nomor item yang ingin di check out. Kemudian, jika user selesai memilih item, inputkan 0 untuk membeli barang/makanan tersebut.

#### 5. Cek saldo
 
![image](https://github.com/user-attachments/assets/1e090bf0-582f-4974-8840-7fcf9256d653)

Ketika user memilih opsi 5 : Cek saldo, akan menampilkan saldo yang dimiliki user saat ini.

### 6. Top up saldo
 
![image](https://github.com/user-attachments/assets/6237326f-43ad-493c-8acd-3763f6abd426)

Ketika user memilih opsi 6 : Top up saldo, user akan diminta untuk mengisi nominal saldo yang ingin di tambahkan agar bisa membeli barang atau makanan dari layanan yang tersedia

### 7. Kembali
 
![image](https://github.com/user-attachments/assets/53f9f208-d08a-4945-b1ed-830862753e60)

Ketika user memilih opsi 7 : Kembali, user akan kembali ke menu login.

## B. Admin

Tampilan login sebagai admin

![image](https://github.com/user-attachments/assets/54d25cb0-b0f1-4432-9a90-96b6deeb7f95)

Jika login sebagai admin, maka masukkan username dan password yang sudah fix sesuai gambar diatas.

![image](https://github.com/user-attachments/assets/f184925e-46a1-400e-be4c-1baf757a98ca)

Menu layanan pada admin

1. Menu makanan
 
![image](https://github.com/user-attachments/assets/e80c5ad3-8e64-4976-a876-8abb95f1e23a)

-	Ketika admin memilih opsi 1 : Menu makanan

![image](https://github.com/user-attachments/assets/265c6dd7-d9b5-4638-ae4e-6c9844c60e7c)

Admin akan diarahkan menuju layanan yang mengatur menu makanan pada tampilan user. Untuk menambah makanan, admin akan diminta untuk menginput nama, harga, dan stok makanan, sehingga akan menambah pilihan makanan yang tersedia pada menu user.

-	Ketika admin memilih opsi 2 : Lihat makanan
  
![image](https://github.com/user-attachments/assets/4e401252-9901-4110-8e93-b38285682464)

Perintah untuk menampilkan pilihan menu makanan yang tersedia

-	Ketika admin memilih opsi 3 : Update makanan
  
![image](https://github.com/user-attachments/assets/c7f9784b-4793-4097-a567-e5c9f44d139e)

Untuk mengupdate makanan, admin akan diminta untuk menginput nama, harga, stok makanan yang ingin di update, sehingga akan memperbaharui pilihan menu makanan yang tersedia pada menu user.

-	Ketika admin memilih opsi 4 : Hapus makanan
  
![image](https://github.com/user-attachments/assets/85f546f4-d543-486b-801f-375297cfb7e7)

Untuk menghapus makanan, admin akan diminta untuk menginput nomor makanan yang ingin dihapus

2.	Menu barang

![image](https://github.com/user-attachments/assets/da2f6011-d336-4ec4-8e57-f3eea3ff6a6c)

-	Ketika admin memilih opsi 1 : Tambah barang

![image](https://github.com/user-attachments/assets/4e374bf6-f6cf-4795-9d24-248a88ed9605)

Untuk menambah barang, admin akan diminta untuk menginput nama, harga, dan stok barang yang ingin di update, sehingga akan menambah barang yang tersedia pada menu user

-	Ketika admin memilih opsi 2 : Lihat barang

![image](https://github.com/user-attachments/assets/f6b7aa0b-489f-4f5a-8ea9-dece4c0d3149)

Perintah untuk menampilkan pilihan barang yang tersedia

-	Ketika admin memilih opsi 3 : Update barang

![image](https://github.com/user-attachments/assets/88195a5b-35c9-4ab7-9894-173a17fc9c43)

Untuk mengupdate barang, admin akan diminta untuk menginput nama, harga, stok barang yang ingin di update, sehingga akan memperbaharui pilihan barang yang tersedia pada menu user.

-	Ketika admin memilih opsi 4 : Hapus barang

![image](https://github.com/user-attachments/assets/0a5e01fa-167a-4d0a-93d9-a7079d22ebf9)

Untuk menghapus barang, admin akan diminta untuk menginput nomor barang yang ingin dihapus

3.  Menu Voucher

![image](https://github.com/user-attachments/assets/7e914b29-736a-4570-b00c-3aec2b4ec36f)

-	Ketika admin memilih opsi 1 : Tambah Voucher

![image](https://github.com/user-attachments/assets/cc692f40-966f-4cdf-88cb-b0544b87ef7a)

Untuk menambah voucher, admin akan diminta untuk menginput kode dan besaran diskon yang nantinya akan diberikan kepada user 

-	Ketika admin memilih opsi 2 : Lihat Voucher

![image](https://github.com/user-attachments/assets/384b2123-3cf5-4759-9624-973b30d3593f)

Perintah untuk menampilkan pilihan voucher yang tersedia

-	Ketika admin memilih opsi 3 : Update Voucher
 
![image](https://github.com/user-attachments/assets/0dc8350d-7d22-4b02-b858-c21a54857815)

Untuk mengupdate voucher, admin akan diminta untuk menginput nomor voucher yang ingin di update, selanjutnya menginput kode dan diskon baru untuk memperbarui voucher yang tersedia.

-	Ketika admin memilih opsi 4 : Hapus Voucher
 
![image](https://github.com/user-attachments/assets/9e5dc5a3-eedb-40fd-8bc4-bcbdb3b6f440)

Untuk menghapus voucher, admin akan diminta untuk menginput nomor voucher yang ingin di hapus, maka akan hilang dari data voucher yang tersedia.

4.	Keluar program

![image](https://github.com/user-attachments/assets/e875ebdd-243f-4eee-a8ee-6dec07436e92)

Program akan berhenti dijalankan.



   


