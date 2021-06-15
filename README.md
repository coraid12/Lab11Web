# Lab11Web
- Nama  : Fahmi Prayoga
- NIM   : 311910682
- Kelas : TI.19.A.2

# Langkah Praktikum

### 1. Jalankan XAMPP Ubah file php.ini seperti berikut :

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
