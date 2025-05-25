# Tugas-4-6

|Nama|NIM|Kelas|Matkul|
|----|---|-----|------|
|Restu sayidina ahmad|312310431|TI.23.A4|Pemograman Web 2|

1. Buat tabel user menggunakan Mysql

![437063149-77bf533c-41c6-4fed-a1e1-e68c2cb7584d](https://github.com/user-attachments/assets/65dcc9de-9991-49a8-991d-cea2d790a49b)

2. Buat file baru bernama UserModel.php di Direktori app/Models. File ini dibuat untuk memproses database login yg telah dibuat sebelumnya

![437063596-29d89ff6-9e1b-4beb-93d9-303496963ca0](https://github.com/user-attachments/assets/b072dd49-5388-46e8-990e-7085abf9f045)

3. Buat Controller baru di direktori app/Controller dan diberi nama User.php. Lalu tambahkan method index() untuk menampilkan daftar user, dan method login() untuk proses login.

![437064151-100a9083-d5b9-4c30-9d3d-44c31fc4bf11](https://github.com/user-attachments/assets/2c706ed9-478a-4a49-9ea8-923e569d2f1d)
![437064299-6c26f7d9-eac0-46b2-9172-3917b499f0f5](https://github.com/user-attachments/assets/ed2ceb43-ce4a-4ad8-b46c-812d97bbe265)

4. Buatlah direktori baru bernama User di drektori app/Views, lalu buat program login.php
![437064791-5a6aed90-e960-4c41-9f3e-7b53f26bdc1a](https://github.com/user-attachments/assets/395dee6a-2381-4731-bca6-d53d1a4f69de)
![437064901-051c7c4e-87d2-48b9-85c7-0e8ab0548fc9](https://github.com/user-attachments/assets/e2fa8d81-86ad-4ae1-9bb9-d3fd9bbf1444)
![437064991-17081386-dc45-4382-a67f-c4c4617be971](https://github.com/user-attachments/assets/4352702a-9e15-4617-aa87-9262f7353cb3)
![437065090-80749c2e-9cb5-4295-bd20-096058d34185](https://github.com/user-attachments/assets/1748b688-578a-4596-9679-3410ba6a6064)

5. Buat Database seeder menggunakan CLI
![437065607-ed4bb94c-cf4b-4814-8dd8-6b71281f5149](https://github.com/user-attachments/assets/4e74b0bd-e156-4570-b8e5-9b83a8031312)

6. Buka file UserSeeder.php di direktori app/Database/Seeds lalu isi dengan program seperti ini
![437065995-d2621563-64b9-4bfc-98a1-070c03cbe6f5](https://github.com/user-attachments/assets/f130ad30-5c1c-413e-bbd5-1f3073580823)

7. Buka CLI dan jalankan perintah ini
![437066378-71e30440-daf0-41e5-a6ef-e67f86a16b47](https://github.com/user-attachments/assets/be468ea1-3754-4825-afa4-d321360cb2f4)
8. Hasilnya akan seperti ini
![437066712-aa033f48-247e-4eea-9b28-68c239e2c595](https://github.com/user-attachments/assets/04fef0a1-e568-42fd-b8e1-22785f07b1ec)

9. Buat file baru dengan nama Auth.php pada direktori app/Filters
![437067061-978980e0-29ab-4c4d-822a-da66edcc8769](https://github.com/user-attachments/assets/fbb756b5-345d-4d9a-bb53-0c29094ab6da)

10. buka file app/Config/Routes.php
![437067891-99f74673-662f-4603-ad58-daf2dcf3041d](https://github.com/user-attachments/assets/89744ece-94fb-4abb-9a1a-58629985d026)

11. Tambahkan Method Logout

![437068554-f9feadfc-55d8-45c3-b577-d271d20f2e5c](https://github.com/user-attachments/assets/543e17f8-d2c5-4907-9368-0492342887ac)

# Pertemuan 5

1. Buat Pagination di Codeigniter 4, untuk membuat pagination, buka Kembali Controller Artikel, kemudian modifikasi kode pada method admin_index seperti berikut.
![437069644-8a847c0a-d825-4a72-8214-753d4f86cb47](https://github.com/user-attachments/assets/f3c938ad-d91d-491e-b0a8-c4573dccae08)

2. Buka file views/artikel/admin_index.php dan tambahkan kode berikut dibawah deklarasi tabel data.
![437070570-68b94114-b716-4fa9-beb7-70a5a792a152](https://github.com/user-attachments/assets/1f1f5c5c-853f-4cac-9568-85d5c18d334e)

3. Buka Kembali daftar artikel dan lihat hasilnya

![437070910-c757b864-0bef-4a7e-8c5c-026a0f8fdd03](https://github.com/user-attachments/assets/2915c1ea-6483-4c7c-9d84-7d42f4b8b2ab)

4. Buat fitur pencarian data di Controller Artikel, pada method admin_index ubah kodenya seperti berikut
![437071621-5a9941cb-660c-4e0e-b71f-a4c3d74ca30a](https://github.com/user-attachments/assets/b63614ab-e63c-4c9a-a906-c066a159eced)

5. Buka kembali file views/artikel/admin_index.php dan tambahkan form pencarian sebelum deklarasi tabel seperti  berikut
![437072330-f7c958da-ad7a-45b5-8a44-9dcbd2247e38](https://github.com/user-attachments/assets/0fa04309-c284-45ca-b7a6-c8f497554c10)

6. Buka kembali halaman admin artikel
![437074226-9d41ee1f-14c9-4abc-a5c6-e7b31dfaa412](https://github.com/user-attachments/assets/d9d93b7a-5b5b-4699-a460-8a8eac9ea9dd)

# Pertemuan 6
1. Buat Fitur memngunggah Gambar pada artuikel, Buka Controller Artikel dan buat program seperti ini
![437074989-21bc13bb-ca15-401a-95cb-f36b98424940](https://github.com/user-attachments/assets/d4faef08-1a6c-46be-bfe8-f96b3ab16947)

2. Pada file views/artikel/form_add.php tambahkan field input file seperti berikut
![437075799-9354d4ed-f97f-4778-8510-ffb64d6b9422](https://github.com/user-attachments/assets/7527212e-ca1a-4f46-bda7-2ba512a35e80)
![437076212-8ab19c09-fc41-4f4e-aa50-2de8d3d2fd66](https://github.com/user-attachments/assets/da2f48ac-58c4-4935-8143-46dcccc90094)

![437078895-2e991a3d-2e26-44f8-8fbb-00ac9fc2ed22](https://github.com/user-attachments/assets/a1d7a368-46bf-496d-9ace-3e587dbe0fa1)
