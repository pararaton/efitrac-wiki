# Access Control List Advance
Halaman ini akan membahas tentang Access Control List secara lebih lanjut dan
disertai gambar yang mempunyai tujuan agar Anda dapat memahaminya dengan
lebih mudah.

---

## Menus
Pengaturan sekuritas dari menu memerlukan ketelitian yang cukup tinggi, apalagi
beberapa menu yang ada mempunyai nama yang sama atau hampir sama. Jika ingin 
memperbolehkan user untuk dapat mengakses menu yang mempunyai hierarki yang 
paling bawah (yang mempunyai *action*), maka menu atasnya (parent menu) juga
harus diberikan ijin.

![Groups - Menus](img/menus-adv.png)

---

## Access Rights
Bagian ini akan mengatur tentang *permission* untuk model. Permission yang 
dimaksud ada empat (4) jenis, yaitu **Read**, **Write**, **Create**, dan
**Delete**. Jangan lupa untuk mencantumkan nama dari permission yang dibuat.

### Read Access
Jika seorang user tidak mempunyai permission ini untuk sebuah model, maka user
tersebut sama sekali tidak diperbolehkan untuk membaca data dari model tersebut. 
Jika User diperbolehkan untuk melihat view dari model, tetapi jika dilakukan, 
maka tidak akan ada data yang tampil dalam view tersebut.

![Groups - Read Access](img/read-access.png)

### Write Access
User tidak diperbolehkan untuk mengubah data yang ada ketika user tersebut tidak
mempunyai permission ini. Biasanya pada bagian atas tampilan, ada tombol 
**edit**, jika tidak mempunyai persmission ini, maka tombol edit akan tidak
terlihat.

![Groups - Write Access](img/write-access.png)

### Create Access
Hampir sama dengan *Write Access*, Create Access memberikan pengaturan agar
user yang tidak mempunyai permission ini tidak dapat menambahkan data baru.
Dapat dilihat dari tombol merah dengan bertuliskan **Create** di atas tampilan
sebuah model.

![Groups - Create Access](img/create-access.png)

### Delete Access
Permission untuk Delete Access diguanakan untuk mengatur siapa saja yang 
diperbolehkan untuk menghapus sebuah data dalam model. Jika diperbolehkan,
maka akan ada pilihan **Delete** pada seleksi *More*. Seleksi tersebut hanya ada
ketika masuk ke mode **form**.

---

## Record Rules
Jika Access Right digunakan untuk mengatur perijinan seorang user mengakses
sebuah model, **Record Rule** digunakan untuk mengatur perijinan pada level
lebih dalam lagi, yaitu bagian data dari sebuah model.



[Menu]: ../menu.md