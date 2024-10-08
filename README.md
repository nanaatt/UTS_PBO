# LAPORAN UTS PEMROGRAMAN BERORIENTASI OBJEK

👨‍🏫 **Dosen Pembimbing**: Bayu Adi Nugroho, Ph.D  
🎓 **Program Studi**: Sistem Informasi

Laporan ini dibuat guna melengkapi tugas UTS pada nomor 6 mengenai CRUD dengan Java Swing dan menggunakan Database Mata Kuliah yang memiliki atribut 📚 **Kode Mata Kuliah**, 📖 **SKS**, 🗓️ **Nama Mata Kuliah**, dan 🏢 **Semester Ajaran**.

---

## A. Penjelasan Materi Secara Singkat

🔄 **CRUD** merupakan operasi query untuk melakukan relasional pada database serta perubahan data atau tampilan suatu informasi. CRUD adalah singkatan dari **Create**, **Read**, **Update**, dan **Delete**. Berikut penjelasan singkatnya:

- **Create (📝)**: Proses pembuatan data baru.
- **Read (🔍)**: Proses pengambilan data atau melakukan verifikasi dari data yang sudah diinputkan.
- **Update (✏️)**: Proses perubahan atau modifikasi data yang sudah ada.
- **Delete (🗑️)**: Proses penghapusan data yang sudah ada.

---

## B. Langkah-langkah

1. **Membuat Frame**  
   Membuat Class DbUtils dan frame form dengan nama sesuai kebutuhan, di sini saya menggunakan nama **MataKuliah**. Kemudian GUI dapat didesain sesuai keinginan. Untuk pembuatan tulisan data MataKuliah, Kode Mata Kuliah, SKS, Nama Mata Kuliah, dan Semester menggunakan **Swing Control Label** 🏷️. Untuk pembuatan kotak putih dibagian depan atau setelah Kode Mata Kuliah, SKS, Nama Mata Kuliah, dan Semester dibuat dengan **Swing Control Text Field** 📄. Untuk pembuatan tombol **Insert**, **Update**, dan **Delete** dibuat dengan **Swing Control Button** 🔘. Untuk pembuatan tabel bisa langsung menggunakan **Swing Control Tabel** 📊.
   
   ![image](https://github.com/user-attachments/assets/427153be-740a-4c01-87c7-1fe679504790)
   ![image](https://github.com/user-attachments/assets/ea14b820-6269-4a08-8d5b-b6bf4899be25)

3. **Penambahan Data (Insert)**  
   Setelah membuat desain kita dapat pergi ke source dengan menginputkan code pada GitHub yang bernama **Buku.java** sesuai tata letaknya di source code. Setelah itu dapat dilakukan operasi yang pertama yaitu **Insert** (penambahan data) 📝. Disini saya melakukan penambahan buku yang berjudul Hujan.
   
   ![image](https://github.com/user-attachments/assets/813d54f8-9448-4f33-968c-69657c693699)
   ![image](https://github.com/user-attachments/assets/86e7fd9e-72b6-41e4-816e-cd63a04204af)
   ![image](https://github.com/user-attachments/assets/747c6f6d-ed10-4f5d-9668-4811532c4e90)
   ![image](https://github.com/user-attachments/assets/c0a9362e-3992-4391-b5dd-aedc423d05aa)

5. **Perubahan Data (Update)**  
   Operasi kedua adalah melakukan **Update** (perubahan data) yang sudah ada ✏️. Disini saya melakukan update pada buku yang berjudul Algoritme Rasa dan mengubah tahun terbitnya saja yang semula 2019 menjadi 2020.
   
   ![image](https://github.com/user-attachments/assets/c46f3934-640e-465d-97d2-3c8b8b8caaf9)
   ![image](https://github.com/user-attachments/assets/f4243076-e873-4ac8-bd9b-b7e6ef8635e2)
   ![image](https://github.com/user-attachments/assets/adc70eb7-df5a-4d47-9580-3fb996cd0b58)
   ![image](https://github.com/user-attachments/assets/6253d8e5-0e53-4c26-aca8-d0e4bf458f85)

7. **Penghapusan Data (Delete)**  
   Operasi ketiga adalah **Delete** (penghapusan data) yang sudah ada 🗑️. Dalam operasi ini bisa melakukan delete hanya dengan menginputkan **ISBN** saja agar mempermudah saat memiliki data yang banyak. Disini saya melakukan delete pada buku yang berjudul Laut Bercerita.
   
   ![image](https://github.com/user-attachments/assets/79998e86-d5b8-4d1d-ae8f-a637d3a2d19e)
   ![image](https://github.com/user-attachments/assets/f253fbbd-7743-41d8-87f7-cea8dfbd0cd2)
   ![image](https://github.com/user-attachments/assets/12718b65-fbea-4474-b464-d074d27e280b)
