# LATIHAN5DPBO2023
Saya Ade Mulyana NIM 2108799 mengerjakan soal Latihan 5 dalam mata kuliah Desain dan Pemrograman Berorientasi Objek untuk keberkahanNya maka saya tidak melakukan kecurangan seperti yang telah dispesifikasikan. Aamiin.
# Desain Program
<img width="500" src="https://user-images.githubusercontent.com/100661834/226823857-7211e87e-9e5f-4ef0-b112-7ad3d16afb27.png" >

> Gambar di atas merupakan desain program / tampilan awal, ketika program di eksekusi

Program ini dijalankan menggunakan GUI(Graphical User Interface), salah satu keuntungan penggunaan GUI adalah memudahkan user untuk berinteraksi dengan program secara visual melalui interface yang mudah di pahami.
Program ini terdiri dari dua kelas, kelas **Mahasiswa** dan **Menu**. Kelas **Mahasiswa**  memiliki beberapa atribut, diantaranya:
- nim
- nama
- nilai
- gender
- usia

Serta terdapat beberapa method getter & setter. <br />
Sedangkan kelas **Menu** merupakan kelas utama sehingga program ini dapat berjalan, di dalamnya terdapat beberapa method seperti untuk menambah, mengupdate, mendelete dan lain-lain.

# Penjelasan Alur
Ketika program ini di eksekusi pertama kali akan muncul seperti gambar diatas di mana kita dapat melakukan apapun sesuai fitur yang terdapat di program tersebut. <br />
### Add
Ketika sudah mengisi seluruh field dari form dan tombol `add` di klik maka data akan tersedia di table, dan ketika `cancel` data tidak akan di input, form kembali kosong. <br />

<img width="500" src="https://user-images.githubusercontent.com/100661834/226827019-6173a5fb-38f2-496b-b891-73573e256e72.png" >


### Update
Pertama pilih data mana yang tersedia di table, yang akan di update, lalu isi ulang form untuk mengupdate nya, dan klik `update`.

<img width="500" src="https://user-images.githubusercontent.com/100661834/226828277-8b654c47-ec0b-4dc3-a110-7502d90894d7.png" >

> Data dengan nama Luffy yang sebelumnya nilai C dan usia 21, telah di update menjadi nilai A dan usia 22

### Delete
Seperti pada **update** pilih terlebih dahulu data mana yang akan di hapus yang tersedia di table. ketika klik tombol `delete` program akan memunculkan prompt warning untuk konfirmasi data di hapus.

<div>
  <img width="500" src="https://user-images.githubusercontent.com/100661834/226828839-be793af1-bcde-4e1f-8fce-fbf8e9d31d5d.png" >
  <img width="500" src="https://user-images.githubusercontent.com/100661834/226833681-be5a3032-3c4f-4c00-879e-96e668e13470.png" >
</div>

### Reset data
Sama seperti **Delete** ketika klik tombol `Reset Data` program akan memunculkan prompt warning untuk konfirmasi seluruh data akan di reset.

<div>
  <img width="500" src="https://user-images.githubusercontent.com/100661834/226836125-8e661817-6bb5-4731-9a5d-3d9857586048.png" >
  <img width="500" src="https://user-images.githubusercontent.com/100661834/226836158-55ea54bd-18a9-4713-8a47-f5d8132e575b.png" >
</div>
