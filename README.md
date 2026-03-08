# 🛒  Registration Form (PART 5)

**Nama: Luthfi Daffa Purbaya**

**NIM: 2409116102**

---
### 📱 Tampilan Awal Aplikasi
<img width="1918" height="913" alt="image" src="https://github.com/user-attachments/assets/def6ee59-797c-4759-9494-fd4257719ebf" />



Berikut merupakan tampilan utama dari aplikasi Registration Form yang digunakan untuk melakukan pendaftaran event. Pada halaman ini pengguna dapat mengisi beberapa data seperti nama lengkap, email, password, jenis kelamin, program studi, dan tanggal lahir. Setiap field yang memiliki tanda bintang (*) menandakan bahwa data tersebut wajib diisi. Setelah semua data diisi, pengguna dapat menekan tombol Daftar Sekarang untuk mengirimkan data pendaftaran atau tombol Reset Form untuk menghapus semua data yang telah dimasukkan.

---
### 1. Isi form → Submit → Lihat success dialog
<img width="1919" height="913" alt="image" src="https://github.com/user-attachments/assets/efb2c324-7c4d-48f7-a80d-af78af6f4411" />

<img width="1919" height="911" alt="image" src="https://github.com/user-attachments/assets/7d399bb9-8f10-448c-93f6-68474ce72881" />

Gambar diatas menunjukkan tampilan ketika pengguna telah mengisi seluruh form pendaftaran dan menekan tombol Daftar Sekarang. Setelah data berhasil dikirim, sistem akan menampilkan dialog notifikasi registrasi berhasil di tengah layar. Dialog ini menampilkan pesan bahwa proses pendaftaran telah berhasil dilakukan. Di dalamnya juga tersedia dua pilihan tombol yaitu Daftar Lagi untuk melakukan pendaftaran baru dan Lihat Daftar untuk melihat data pendaftaran yang telah tersimpan.

---

### 2. Klik "Lihat Daftar" → Muncul di list

**klik lihat daftar**

<img width="384" height="288" alt="image" src="https://github.com/user-attachments/assets/12adc86d-34ec-4e38-993b-7e75a1f738e5" />

**Daftar Peserta**

<img width="1919" height="908" alt="image" src="https://github.com/user-attachments/assets/95d3a017-a963-45a8-920e-27ea99199107" />

Setelah melakukan registrasi dan menekan tombol "lihat daftar" maka kita akan dialihkan ke halaman yang menampilkan data pengguna yang telah berhasil melakukan pendaftaran. Pada halaman ini ditampilkan informasi peserta seperti nama, program studi, dan email. Selain itu terdapat juga ikon hapus di sisi kanan yang dapat digunakan untuk menghapus data peserta dari daftar. Di bagian kanan bawah terdapat tombol tambah (+) yang dapat digunakan untuk kembali ke halaman form pendaftaran dan menambahkan peserta baru.

---
### 3. Tap item → Detail page 

<img width="1919" height="912" alt="image" src="https://github.com/user-attachments/assets/3bad525f-1d21-4814-bba7-532109f694f8" />

Berikut merupakan tampilan halaman detail peserta yang muncul ketika pengguna menekan salah satu data pada halaman daftar peserta. Pada halaman ini ditampilkan informasi lengkap dari peserta yang telah melakukan pendaftaran, seperti nama, email, jenis kelamin, program studi, serta tanggal lahir. Halaman ini bertujuan untuk menampilkan detail data peserta secara lebih lengkap sehingga pengguna dapat melihat informasi pendaftaran dengan lebih jelas.

---

### 4. Badge di AppBar update

**Saat Jumlah Peserta Masih 1**

<img width="1919" height="73" alt="image" src="https://github.com/user-attachments/assets/644f164a-e81d-44b1-847d-227ab62d0a9b" />

**Saat Jumlah Peserta Bertambah**

<img width="1916" height="71" alt="image" src="https://github.com/user-attachments/assets/15805732-5cc8-43f9-bfa0-3431ff1dc12d" />

<img width="1919" height="391" alt="image" src="https://github.com/user-attachments/assets/f4753b27-ee6e-4580-ab14-0341a68f97c5" />

Dapat dilihat pada gambar, tampilan badge pada AppBar yang akan otomatis diperbarui sesuai dengan jumlah peserta yang telah terdaftar di dalam aplikasi. Badge ini ditampilkan pada ikon peserta di bagian kanan atas layar. Saat jumlah peserta masih sedikit, angka pada badge akan menampilkan jumlah peserta yang ada. Ketika peserta baru ditambahkan, angka pada badge akan otomatis bertambah sehingga pengguna dapat dengan mudah melihat jumlah total peserta yang sudah terdaftar.
---

### 5. Delete → Confirm → Removed

**Delete**

<img width="1919" height="282" alt="image" src="https://github.com/user-attachments/assets/681e492a-04d9-46cc-93ee-07f793eb1a69" />

Disini pengguna bisa memilih pendaftar mana yang mau dihapus dengan meng klik icon sampah

**Confirm**

<img width="350" height="218" alt="image" src="https://github.com/user-attachments/assets/fab1465a-ccd2-4442-ac31-53a91252b47d" />


Dapat dilihat pada gambar, gambar pertama menunjukkan beberapa daftar produk yang telah ditambahkan ke keranjang, lalu gambar kedua menunjukkan  produk sudah tidak ada lagi di keranjang karena dikurangi hingga 0 atau dihapus, lalu ketika sudah tidak ada produk dikeranjang maka akan ada tulisan "your cart is empty" pada halaman.

---

### 6. Clear all - Empty cart message

<img width="266" height="59" alt="image" src="https://github.com/user-attachments/assets/d3a11139-ba3c-473d-ae98-5f6ef81fe164" />

<img width="1919" height="909" alt="image" src="https://github.com/user-attachments/assets/e37bb9a2-edd1-49d9-bc69-fdff54ee2366" />

Dapat dilihat, jika kita menekan ikon sampah atau menghapus produk, akan ada notifikasi pesan yang akan menampilkan nama produk yang dihapus dan pada halaman keranjang akan ada tulisan "your cart is empty".

---

### 7. Navigate back - Badge still correct

**Daftar Produk yang Ada di Keranjang**

<img width="1919" height="534" alt="image" src="https://github.com/user-attachments/assets/509bbcb5-71b3-4d9d-9b41-d46a9d5345a5" />


**Kembali ke Halaman Awal**

<img width="1919" height="907" alt="image" src="https://github.com/user-attachments/assets/f75b61f4-ded8-4154-ac72-72d363f7ec7a" />


**Kembali keranjang & mengecek apakah produk yang sudah dtambahkan tadi masih tetap ada**

<img width="1919" height="546" alt="image" src="https://github.com/user-attachments/assets/f624ec1c-b7f6-407f-8d0d-879f551eceb9" />


Dapat dilihat, walaupun kita kembali ke halaman home/awal tetapi sudah ada menambahkan produk ke keranjang, maka akan tetap tersimpan.
