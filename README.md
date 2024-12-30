# String

## Penjelasan kode 

![Gambar 1](SS/ss1.png)

- Fungsi ini berguna untuk menangani seluruh proses validasi form. Dengan hal ini kita bisa memanggil validasi_form() kapan saja dalam program untuk memeriksa input 

- Program akan meminta kita untuk memasukkan tiga input yaitu nama, nomor telepon dan email. 


![Gambar 2](SS/ss2.png)

- replace(" ", ""): Menghapus semua spasi dalam string 

- isalpha(): Memeriksa apakah semua karakter dalam string adalah huruf.

- not: Digunakan untuk membalikkan hasil dari isalpha(). Jika nama tidak valid, program mencetak pesan error dan keluar dari fungsi dengan return.


![Gambar 3](SS/ss3.png)

- isdigit(): Memeriksa apakah string hanya berisi angka. Jika nomor telepon berisi karakter selain angka, validasi gagal.

- not: Membalikkan hasil untuk menangani input yang tidak valid.


![Gambar 4](SS/ss4.png)

- "@" not in email: Memastikan bahwa karakter @ ada dalam email.

- "." not in email: Memastikan bahwa karakter . juga ada dalam email.

- or: Jika salah satu kondisi tidak terpenuhi, validasi gagal.


![Gambar 5](SS/ss5.png)

- Jika semua validasi lolos, program mencetak pesan bahwa data pendaftaran valid.

- Fungsi validasi_form() dipanggil untuk memulai proses validasi. Anda dapat menempatkannya di berbagai bagian program jika diperlukan


# HASIL 

### Semua Input Valid

![Gambar 6](SS/ss6.png)

### Nama Tidak valid

![Gambar 7](SS/ss7.png)

### Nomor Telepon Tidak Valid

![Gambar 8](SS/ss8.png)

### Email Tidak Valid 

![Gambar 9](SS/ss9.png)