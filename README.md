![image](https://github.com/user-attachments/assets/0e98a3d8-771f-4ddd-a68d-da1ef6079538)Kelompok 11
Muhammad Rizky Febrianto (2409116045)
Abdurrahman Al Farissy (2409116055)
Dinda Aulia Rizky (2409116076)

# **E-Commerce**

Program ini merupakan program berbasis python yang dapat membantu para UMKM dan juga konsumen. Dengan adanya program ini, para UMKM dan konsumen agar dapat melakukan pencatatan, pengelolaan, dan penghitungan transaksi secara praktis dan efisien. Selain itu, program ini juga telah kami rancang sedemikian rupa sehingga tidak hanya memudahkan para UMKM untuk melakukan pengelolaan, tetapi juga memudahkan para konsumen untuk melakukan pembelian makanan ataupun barang.

# **Alur program**

## A. USER

### 1. Tampilan awal
  
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

### 2. Tampilan menu layanan pada user

![image](https://github.com/user-attachments/assets/0ea8174c-de9b-47ab-af86-283c5580975c)

#### Order makanan

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

2.	Order barang
   
 ![image](https://github.com/user-attachments/assets/05625a07-e7f6-4bab-a160-e2e1e5b3c58f)

Gambar 3. 14 Order barang sorting (asc)

![image](https://github.com/user-attachments/assets/7d6d50b0-9407-4d34-9bc1-fac8d0bf44c8)

Gambar 3. 15 Order Barang Sorting (desc)

User akan diminta untuk memilih apakah ingin mengurutkan barang berdasarkan harga. Jika user memilih ya, maka program akan kembali memberikan pilihan apakah ingin mengurutkan berdasarkan harga termurah (asc) atau termahal (desc). Lalu program akan mengeksekusi sesuai inputan yang diberikan user. 

![image](https://github.com/user-attachments/assets/e1b6dcd7-d8b2-4d6f-8b83-01562ed79f14)

Namun, apabila user memilih untuk tidak mengurutkan harga maka program akan langsung memberikan pilihan untuk ‘searching menu barang yang tersedia. Jika user memilih ya, fitur searching akan memudahkan user mencari menu barang yang diinginkan dengan memasukkan kata kunci. Jika memilih tidak, akan diarahkan untuk melakukan transaksi

![image](https://github.com/user-attachments/assets/50ca5f11-2f80-4e9d-a229-84c670e71c48)

Setelah itu user akan diberikan pilihan untuk bayar sekarang atau masukkan pesanan ke dalam keranjang. Apabila user memilih opsi 1 : Beli sekarang, user akan diberikan pilihan lagi apakah ingin menggunakan kode voucher atau tidak. Setelah memilih, program akan menampilkan invoice dari menu barang yang dibeli.

Setelah itu, program akan memberikan pilihan apakah ingin memesan barang yang lainnya. Jika user memilih ya, program akan kembali menerimpa input untuk order barang. Jika, tidak maka akan menampilkan output.
Tampilan apabila voucher sudah tidak berlaku atau sudah digunakan
 
![image](https://github.com/user-attachments/assets/b0765d6b-0d34-4824-818e-8a2d8b2e0763)

![image](https://github.com/user-attachments/assets/cae99d9d-23f9-4c8f-a422-b88e18c958e3)

Tetapi, jika kita memilih opsi 2 : masukkan ke keranjang. Maka menu makanan akan di masukkan ke dalam keranjang yang terhubung dengan csv.

![Uploading image.png…]()
