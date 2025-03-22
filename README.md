# Janji
Saya Klara Ollivviera Augustine Gunawan dengan NIM 2306205 mengerjakan soal Tugas Praktikum 4 dalam mata kuliah DPBO untuk keberkahanNya maka saya tidak melakukan kecurangan seperti yang telah dispesifikasikan. Aamiin

# Desain Program
Program merupakan form "Data Mahasiswa" yang mengimplementasikan CRUD. Program terdiri dari 2 class yaitu class Mahasiswa dan class Menu. Dengan detail berikut:
## 1. Class Mahasiswa
Class ini merepresentasikan data mahasiswa, dengan atribut berikut:
- NIM -> Nomor Induk Mahasiswa
- Nama -> Nama mahasiswa
- Jenis Kelamin -> Jenis kelamin mahasiswa
- Status -> Status perkuliahan mahasiswa

Di dalam class mahasiswa berisikan method getter dan setter dari masing-masing atribut.

## 2. Class Menu
Class ini bertanggung jawab untuk tampilan dan interaksi pengguna dengan aplikasi. Class ini menggunakan Java Swing untuk membuat GUI (Graphical User Interface).

### Komponen dalam Class Menu:
- Panel Utama (JPanel): Menampung semua elemen UI.
- Tabel Mahasiswa (JTable): Menampilkan daftar mahasiswa.
- Form Input (JTextField, JComboBox, JRadioButton): Digunakan untuk mengisi dan mengedit data mahasiswa.
- Tombol Aksi (JButton):
  - Add/Update: Menambahkan atau memperbarui data mahasiswa.
  - Delete: Menghapus data mahasiswa.
  - Cancel: Membersihkan form input.

### Method-Method dalam Class Menu:
- insertData(): Menambahkan data mahasiswa ke dalam list dan memperbarui tabel.
- updateData(): Memperbarui data mahasiswa yang dipilih.
- deleteData(): Menghapus data mahasiswa dari list.
- clearForm(): Mengosongkan semua input form.
- setTable(): Mengatur tampilan tabel berdasarkan data yang ada.
- getSelectedStatus(): Mengambil nilai status mahasiswa yang dipilih.
- populateList(): Mengisi daftar mahasiswa dengan data awal.

## 3. Desain Form
<img width="607" alt="DESAIN FORM" src="https://github.com/user-attachments/assets/d663dd6b-175b-48a8-b92d-4f9c22f12514" />

# Alur Program
1. Menjalankan Program: Program akan menampilkan GUI yang berisi daftar mahasiswa dalam tabel.
2. Menambahkan Data:
   - Pengguna mengisi form dengan NIM, Nama, Jenis Kelamin, dan Status.
   - Klik tombol "Add" untuk menambahkan data ke tabel. Data akan berhasil ditambahkan.
3. Mengupdate Data:
   - Pengguna memilih baris dalam tabel.
   - Data akan muncul di form dan tombol "Add" berubah menjadi "Update".
   - Setelah mengedit, pengguna klik "Update" untuk menyimpan perubahan. Data akan berhasil diubah.
4. Menghapus Data:
   - Pengguna memilih baris dalam tabel.
   - Klik tombol "Delete" untuk menghapus data.
   - Muncul konfirmasi sebelum penghapusan dilakukan. Jika "Yes" data akan terhapus dan jika "No" data tidak terhapus.
5. Membatalkan Input:
   - Klik tombol "Cancel" untuk menghapus isi form tanpa mengubah data di tabel.
   
# Dokumentasi
https://github.com/user-attachments/assets/04f6c53c-5496-4bdb-80b9-ca0e089cafaf
