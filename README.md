# LATIHAN3DPBO2023!

Saya Muhammad Rizki NIM 2107922 mengerjakan Latihan 4 dalam mata kuliah Desain dan Pemrograman Berorientasi Objek untuk keberkahanNya maka saya tidak melakukan kecurangan seperti yang telah dispesifikasikan. Aamiin.

![latihan3dpbo drawio](https://user-images.githubusercontent.com/100481579/222139405-5c817f12-f23a-4efc-9c40-8a6334a7b648.png)

### Deskripsi Kelas
1. Class Human
- Class ini merupakan parent class dari SivitasAkademik, Mahasiswa, dan Dosen
- Memiliki atribut private berupa nik, nama, dan jenis_kelamin
- Memiliki constructor default dan constructor dengan parameter nik, nama, dan jenis_kelamin
- Memiliki getter dan setter untuk setiap atribut
- Memiliki destructor default

2. Class SivitasAkademik
- Class ini merupakan child class dari Human dan parent class dari Mahasiswa dan Dosen
- Memiliki atribut private berupa asal_universitas dan email_edu
- Memiliki constructor default dan constructor dengan parameter nik, nama, jenis_kelamin, asal_universitas, dan email_edu
- Memiliki getter dan setter untuk setiap atribut
- Memiliki destructor default

3. Class Mahasiswa
- Class ini merupakan child class dari SivitasAkademik
- Memiliki atribut private berupa nim, fakultas, dan prodi
- Memiliki constructor dengan parameter nik, nim, nama, jenis_kelamin, fakultas, asal_universitas, dan email_edu yang memanggil constructor parent class
- Memiliki getter dan setter untuk setiap atribut
- Memiliki destructor default

4. Class Dosen
- Class ini merupakan child class dari SivitasAkademik
- Memiliki atribut private berupa nip, fakultas, pend_terakhir, dan keahlian
- Memiliki constructor dengan parameter nik, nip, nama, jenis_kelamin, fakultas, pend_terakhir, keahlian, asal_universitas, dan email_edu yang memanggil constructor  -- parent class dengan nik kosong
- Memiliki getter dan setter untuk setiap atribut
- Memiliki destructor default

5. Class Course
- Class ini memiliki atribut private berupa nama_matakuliah, dosen, dan vector mahasiswa
- Memiliki constructor dengan parameter nama_matakuliah dan dosen
- Memiliki destructor yang akan membersihkan vector mahasiswa
- Memiliki getter dan setter untuk setiap atribut
- Memiliki fungsi add_mahasiswa untuk menambahkan mahasiswa ke dalam vector mahasiswa

6. Class ProgramStudi
- Class ini memiliki atribut private berupa nama_prodi, kode, dan vector course
- Memiliki constructor dengan parameter nama_prodi dan kode
- Memiliki destructor yang akan membersihkan vector course
- Memiliki getter dan setter untuk setiap atribut
- Memiliki fungsi add_course untuk menambahkan mahasiswa ke dalam vector course

### Alur Program
Pada awal program, objek-objek mahasiswa, dosen, dan course dibuat dan diinisialisasi dengan data yang diinginkan. Kemudian mahasiswa dimasukkan ke dalam course dan course dimasukkan ke dalam program studi.

Setelah itu, data dari semua objek tersebut ditampilkan menggunakan perulangan dan beberapa metode dari kelas-kelas yang sudah didefinisikan sebelumnya. Data mahasiswa ditampilkan dengan NIM, Nama, Program Studi, Fakultas, dan Universitas asal. Data dosen ditampilkan dengan NIP, Nama, Jenis Kelamin, Fakultas, Pendidikan Terakhir, dan Keahlian. Sedangkan data course ditampilkan dengan Nama Mata Kuliah, Dosen Pengampu, dan Daftar Mahasiswa yang mengikuti matakuliah tersebut.

Akhirnya, program ini menggunakan vector untuk menyimpan objek-objek mahasiswa, dosen, course, dan program studi. Dengan demikian, program ini memungkinkan pengguna untuk menambah dan mengelola data mahasiswa, dosen, course, dan program studi dengan mudah.
![1](https://user-images.githubusercontent.com/100481579/223431925-004fc1aa-68b4-46aa-98bf-23a61b82bf1a.png)
![2](https://user-images.githubusercontent.com/100481579/223431937-9969178c-256e-4194-ae11-ca656d09cbc4.png)
![3](https://user-images.githubusercontent.com/100481579/223431940-d7db6fbb-d99c-4ee4-ba06-c7e25273c6d6.png)

