# Lab11Web
> Nama  : Fahmi Prayoga

> NIM   : 311910682

> Kelas : TI.19.A.2

# ========== Langkah Praktikum 11 ==========

### 1. Buat folder baru lab11_php_ci lalu Jalankan XAMPP Ubah file php.ini seperti berikut :

![1x](https://user-images.githubusercontent.com/56239989/121812591-94487480-cc92-11eb-8d77-74213a2ecd58.jpg)

### 2. Instal Codeigniter 4 dan Buka http://localhost/lab11_php_ci/ci4/public/ , hasilnya :

![1](https://user-images.githubusercontent.com/56239989/121812731-3a947a00-cc93-11eb-87fc-58b1379bc2ac.jpg)
 
### 3. Buka cmd pada XAMPP Shell lalu buka php spark, untuk menjalankan server ketik "php spark serve" :

![2](https://user-images.githubusercontent.com/56239989/121812816-8c3d0480-cc93-11eb-8ff9-47b717b8f5c0.jpg)

- Hasil error/kesalahan :

![2x](https://user-images.githubusercontent.com/56239989/121874541-a4636100-cd31-11eb-9d92-fd56483bbdd3.jpg)

### 4. Mengaktifkan mode Debugging dengan mengubah file .env menjadi = development, seperti berikut :

![3](https://user-images.githubusercontent.com/56239989/121873714-da541580-cd30-11eb-9205-7fa801544301.jpg)

### 5. Untuk mencoba Error hilangkan tanda ; (titik koma) pada Home.php, seperti berikut :

![5](https://user-images.githubusercontent.com/56239989/121874946-12a82380-cd32-11eb-9a11-85f28e785469.jpg)

- Contoh Eror saat diakses :

![24](https://user-images.githubusercontent.com/56239989/121996004-112e3800-cdd2-11eb-8291-58ed853bf886.jpg)

### 6. Struktur Direktori yang tersedia :

![5x](https://user-images.githubusercontent.com/56239989/121875277-76325100-cd32-11eb-812e-5a498bbaaaf6.jpg)

### 7. Mengarahkan router pada controller :

![6](https://user-images.githubusercontent.com/56239989/121875724-fc4e9780-cd32-11eb-90fd-fc19eec5fc69.jpg)

### 8. Cek pada CMD dengan memasukan "php spark routes",hasilnya akan seperti berikut :

![7x](https://user-images.githubusercontent.com/56239989/121875844-1be5c000-cd33-11eb-8240-8c084a1c3071.jpg)

### 9. Akses route yang telah dibuat dengan http://localhost:8080/about, hasilnya :

![8](https://user-images.githubusercontent.com/56239989/121877105-76cbe700-cd34-11eb-9a21-0084c2ac796c.jpg)

### 10. Membuat Controller Page, dengan membuat file baru bernama page.php seperti berikut :

![9](https://user-images.githubusercontent.com/56239989/121877676-0ec9d080-cd35-11eb-9f4f-a01eef869ca6.jpg)

- Hasilnya :

![10](https://user-images.githubusercontent.com/56239989/121877712-1b4e2900-cd35-11eb-820b-41ee82b0e6e0.jpg)

### 11. Mengaktifkan AutoRouting dengan men set nilai true/false, jika true maka fungsi akan aktif

![11](https://user-images.githubusercontent.com/56239989/121879152-bb588200-cd36-11eb-8824-168c8d807d60.jpg)

- Akses http://localhost:8080/page/tos karena halaman in belum masuk pada routing, hasilnya :

![12](https://user-images.githubusercontent.com/56239989/121880203-f0190900-cd37-11eb-9825-830ba341e3de.jpg)

### 12. Membuat View, dengan membuat file baru bernama about.php dan masukan kode berikut :

![13x](https://user-images.githubusercontent.com/56239989/121882649-0379a380-cd3b-11eb-972d-58d6d81e71c8.jpg)

- Hasilnya:

![14](https://user-images.githubusercontent.com/56239989/121882685-0c6a7500-cd3b-11eb-8114-37056eed8825.jpg)

### 13. Membuat Layout Web dengan CSS (bisa menggunakan css praktikum sebelumnya Lab4Web) :

![16](https://user-images.githubusercontent.com/56239989/121883887-7a636c00-cd3c-11eb-90af-2ade6a06e04a.jpg)

### 14. Buatlah folder baru dengan nama "template" pada direktori Views, kemudian buat file **header** dan **footer** sebagai berikut :

![17](https://user-images.githubusercontent.com/56239989/121884069-b0085500-cd3c-11eb-8f75-f7210d8b2bf2.jpg)
![18](https://user-images.githubusercontent.com/56239989/121884076-b26aaf00-cd3c-11eb-9ac0-3c8e664cfddd.jpg)

### 15. Kemudian ubah file app/view/about.php seperti berikut : 

![19](https://user-images.githubusercontent.com/56239989/121884178-ce6e5080-cd3c-11eb-9578-0bc0019bdf55.jpg)

- Berikut hasil Layout yang dibuat :

![22](https://user-images.githubusercontent.com/56239989/121885454-602a8d80-cd3e-11eb-9105-2b47a4ef795a.jpg)

# PERTANYAAN DAN TUGAS

![20](https://user-images.githubusercontent.com/56239989/121884396-0ecdce80-cd3d-11eb-975c-b4396112b8e8.jpg)

- Halaman artikel :

![21](https://user-images.githubusercontent.com/56239989/121885380-4db05400-cd3e-11eb-9115-102ae1a2fe9a.jpg)

- Halaman kontak :

![23](https://user-images.githubusercontent.com/56239989/121995779-b85e9f80-cdd1-11eb-8714-4a4943992756.jpg)

# Lab11Web
> Nama  : Fahmi Prayoga

> NIM   : 311910682

> Kelas : TI.19.A.2

# ========== Langkah Praktikum 12 ==========

### 1. Pastikan MySQL pada program XAMPP berjalan dan buat database seperti berikut :

![1](https://user-images.githubusercontent.com/56239989/122720515-c57c0280-d299-11eb-83bf-e5fc425d6758.jpg)

### 2. Mengkonfigurasi koneksi database pada file .env seperti berikut :

![2](https://user-images.githubusercontent.com/56239989/122720603-e2183a80-d299-11eb-9345-5bcf5981090b.jpg)

### 3. Membuat file Model pada direktori app/Models dengan nama ArtikelModel.php seperti berikut :

![3](https://user-images.githubusercontent.com/56239989/122720695-fd834580-d299-11eb-8307-948cb9947b23.jpg)

### 4. Membuat file Controller baru dengan nama Artikel.php pada direktori app/Controllers. seperti berikut :

![4](https://user-images.githubusercontent.com/56239989/122720903-3a4f3c80-d29a-11eb-91e5-e2a50b961673.jpg)

### 5. Membuat file Views baru dengan nama artikel pada direktori app/views, kemudian buat filebaru dengan nama index.php, seperti berikut :

![5](https://user-images.githubusercontent.com/56239989/122721195-93b76b80-d29a-11eb-837b-70de9294d90c.jpg)

- Lalu jalankan server dan akses link : http://localhost:8080/artikel  

![6](https://user-images.githubusercontent.com/56239989/122721651-1f30fc80-d29b-11eb-89cd-edd33eef0020.jpg)

### 6. Masukan data berikut pada database :

![7](https://user-images.githubusercontent.com/56239989/122730529-830bf300-d2a4-11eb-92a5-16a28ab38b2f.jpg)

- Refresh dan lihat kembali browser :

![8](https://user-images.githubusercontent.com/56239989/122730557-8f904b80-d2a4-11eb-9426-237aedd95880.jpg)

### 7. Menambahkan Detail pada Artikel.php seperti berikut :

![9](https://user-images.githubusercontent.com/56239989/122731105-278e3500-d2a5-11eb-9679-b607c40e3bb1.jpg)

### 8. Membuat file baru baru untuk halaman detail dengan nama app/views/artikel/detail.php. seperti berikut :

![10](https://user-images.githubusercontent.com/56239989/122731190-396fd800-d2a5-11eb-9297-c33ed1f88c95.jpg)

### 9. Tambahkan rute baru pada Routes.php :

![11](https://user-images.githubusercontent.com/56239989/122731415-7b991980-d2a5-11eb-8490-3cac4a8b6eaa.jpg)

- Tampilan Artikel setelah di Klik :

![12](https://user-images.githubusercontent.com/56239989/122731927-f2cead80-d2a5-11eb-9335-4d8a40aeefe5.jpg)

### 10. Membuat Menu Admin

- Buat method baru pada Controller Artikel dengan nama admin_index() :

![13](https://user-images.githubusercontent.com/56239989/122732178-388b7600-d2a6-11eb-8dc2-ccb98ee6ff4b.jpg)

- Buat file baru dengan nama admin_index.php pada folder artikel :

![14](https://user-images.githubusercontent.com/56239989/122732382-6c669b80-d2a6-11eb-8f04-1a74dbe861b4.jpg)

- Tambahkan Routing baru pada Routes.php seperti berikut :

![15](https://user-images.githubusercontent.com/56239989/122732583-a20b8480-d2a6-11eb-947d-7ea43b6bae7f.jpg)

- Akses menu admin dengan url http://localhost:8080/admin/artikel :

![16](https://user-images.githubusercontent.com/56239989/122734694-81442e80-d2a8-11eb-9174-5c9d53598ddc.jpg)

### 11. Menambah Data Artikel

- Tambahkan fungsi/method baru pada Controller Artikel dengan nama add() :

![17](https://user-images.githubusercontent.com/56239989/122735069-e26c0200-d2a8-11eb-8c4e-a41f1966eaa4.jpg)

- Lalu buat file baru dengan nama form_add.php pada folder artikel :

![18](https://user-images.githubusercontent.com/56239989/122735115-ee57c400-d2a8-11eb-8eb0-4a146c5f3e71.jpg)

- Tampilan jika mengklik Tambah Artikel :

![19](https://user-images.githubusercontent.com/56239989/122735281-16472780-d2a9-11eb-8816-88178acc3993.jpg)

### 12. Mengubah DAta Artikel

- Tambahkan fungsi/method baru pada Controller Artikel dengan nama edit() :

![20](https://user-images.githubusercontent.com/56239989/122735483-468ec600-d2a9-11eb-9ffa-1ebcf85845ee.jpg)

- Lalu buat file baru dengan nama edit_add.php pada folder artikel :

![21](https://user-images.githubusercontent.com/56239989/122735658-70e08380-d2a9-11eb-8334-68e51495d0c3.jpg)

- Tampilan saat mengubah artikel :

![22](https://user-images.githubusercontent.com/56239989/122735780-8eade880-d2a9-11eb-8c69-a4fbfa68e3e7.jpg)

### 13. Menghapus Data

- Tambahkan fungsi/method baru pada Controller Artikel dengan nama delete() :

![23](https://user-images.githubusercontent.com/56239989/122735923-ac7b4d80-d2a9-11eb-9a9b-08903b44127a.jpg)

# Lab11Web
> Nama  : Fahmi Prayoga

> NIM   : 311910682

> Kelas : TI.19.A.2

# ========== Langkah Praktikum 13 ==========


### 1. Persiapan
- Pastikan MySQL Server sudah dapat dijalankan melalui XAMPP.

### 2. Membuat Tabel User Login
- Masukan kode berikut pada database :

![1](https://user-images.githubusercontent.com/56239989/123211006-0e77c500-d4ed-11eb-9a6e-3e08440bbf40.jpg)

### 3. Membuat Model User
- Buat file baru pada direktori app/Models dengan nama UserModel.php, seperti berikut :

![3](https://user-images.githubusercontent.com/56239989/123211348-8b0aa380-d4ed-11eb-9397-c66c994be110.jpg)

### 4. Membuat Controller User
- Buat Controller baru dengan nama User.php pada direktori app/Controllers. kemudian tambahkan fungsi index() sebagai berikut :

![4](https://user-images.githubusercontent.com/56239989/123211358-9067ee00-d4ed-11eb-8879-640011ab7ac7.jpg)

### 5. Membuat View Login
- Buat direktori baru dengan nama user pada direktori app/views, kemudian buat file baru dengan nama login.php. Dengan kode berikut :

![5](https://user-images.githubusercontent.com/56239989/123211466-b2fa0700-d4ed-11eb-8fe5-05c311528671.jpg)

### 6. Membuat Database Seeder
- Buka CLI dan masukan kode "php spark make:seeder UserSeeder", Hasilnya :

![6](https://user-images.githubusercontent.com/56239989/123211629-e9378680-d4ed-11eb-8ab2-cd5ab8945377.jpg)

- Lalu buka file UserSeeder.php yang berada di lokasi direktori /app/Database/Seeds/UserSeeder.php kemudian isi dengan kode berikut:

![7](https://user-images.githubusercontent.com/56239989/123211686-fce2ed00-d4ed-11eb-8bcc-394fbc686856.jpg)

- Selanjutnya buka kembali CLI dan ketik perintah "php spark db:seed UserSeeder" , Hasilnya :

![8](https://user-images.githubusercontent.com/56239989/123211822-2c91f500-d4ee-11eb-87ea-1a20334c808a.jpg)

- Hasil Uji Coba Login :

![login](https://user-images.githubusercontent.com/56239989/123220848-87c8e500-d4f8-11eb-8a96-8f7cdf5ae317.jpg)

### 7. Menambahkan Auth Filter
- Selanjutnya membuat filer untuk halaman admin. Buat file baru dengan nama Auth.php pada direktori app/Filters. berikut :

![10](https://user-images.githubusercontent.com/56239989/123222043-be532f80-d4f9-11eb-9db1-cf76569b2a10.jpg)

- Selanjutnya buka file app/Config/Filters.php tambahkan kode berikut:

![11](https://user-images.githubusercontent.com/56239989/123222099-cb701e80-d4f9-11eb-9559-0f2165d632e3.jpg)

- Selanjutnya buka file app/Config/Routes.php dan sesuaikan kode berikut :

![12](https://user-images.githubusercontent.com/56239989/123222163-dc209480-d4f9-11eb-85e2-4b3359554a04.jpg)

### 8. Percobaan menu akses LOGIN
- Buka url dengan alamat http://localhost:8080/admin/artikel ketika alamat tersebut diakses maka akan ditarik ke halaman login berikut :

![artikellogin](https://user-images.githubusercontent.com/56239989/123224162-be542f00-d4fb-11eb-85aa-d07da7509e23.jpg)


### 9. Membuat Fungsi LOGOUT
- Tambahkan method logout pada Controller User seperti berikut :

![13](https://user-images.githubusercontent.com/56239989/123224525-15f29a80-d4fc-11eb-980e-2e5322c5137f.jpg)

- Setelah LOGOUT otomatis akan menampilkan halaman LOGIN kembali.














