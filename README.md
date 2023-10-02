# Praktikum 1 - Pemograman Web
### Friston Purba
### 312210595
### TI.22.A1

## Langkah Praktikum
Pertama buka VS Code terlebih dahulu.
![gambar-1][def-1]

[def-1]: /image/ss0.jpg

Lalu buatlah file baru dengan nama `lab1_tag_dasar.html`dan buat struktur HTML- nya lalu pada bagian title ganti dengan `TagHTML dasar`.
![gambar-2][def-2]

[def-2]: /image/ss2.jpg

Nah selanjutnya, buka file yang sudah dibuat tadi pada web browser.
![gambar-3][def-3]

[def-3]: /image/ss3.jpg

Kenapa halamannya kosong karena didalam file `lab1_tag_dasar.html` hanya ada tag title yang hanya menampilkan judul sebuah halaman.

Selanjutnya membuat judul dan pargraf, dalam membuat judul menggunakan `tag h1 - h6` untuk membuat paragrafnya menggunakan tag `<p>`.
![gambar-4][def-4]

[def-4]: /image/ss4.jpg

Lalu juga bisa mengubah-ubah nilai atributnya pada bagian paragraf dengan menggunakan nilai atribut `(align="right", align="left")`
![gambar-5][def-5]

[def-5]: /image/ss5.jpg

Selanjutnya juga bisa `memformat teks` pada paragraf dengan tag `<b>`, `<strong>`, `<i>`, `<em>`, `<mark>`, `<small>`, `<del>`, `<ins>`, `<sub>` dan `<sup>`.
![gambar-6][def-6]

[def-6]: /image/ss6.jpg

Selanjutnya akan menampilkan gambar pada halaman web, untuk menampilkan gambar/foto pastikan sudah memiliki gambar/foto yang ingin ditampilkan, kemudian buat folder baru yang berada didalam folder `Lab1Web` atau juga bisa simpan file gambar satu folder dengan file dokumen html.
![gambar-7][def-7]

[def-7]: /image/ss7.jpg

Atau bisa seperti ini.
![gambar-8][def-8]

[def-8]: /image/ss8.jpg

Nah selanjutnya menambahkan gambar pada halam web yang sudah di save sebelumnya dengan memanggil gambar menggunakan tag `<img src="logo_UPB.png" title="Logo Universitas Pelita Bangsa">`.
![gambar-9][def-9]

[def-9]: /image/ss9.jpg

Selanjutnya membuat `Hyperlink` untuk menghubungkan halam satu dengan halaman lain, tambahkan hyperlink sebelum heading 1 seperti berikut dan buat dokumen HTML baru didalam folder Lab1Wb.
![gambar-10][def-10]

[def-10]: /image/ss11.jpg

Halaman ke-2
![gambar-11][def-11]

[def-11]: /image/ss10.jpg

## Jawab Pertanyaan Berikut
1. Lakukan perubahan pada kode sesuai dengan keinginan anda, amati perubahannya adakah _error_ ketika terjadi kesalahan punulisan tag?
```
Pada saat saya menuliskan kode tag <p> namun lupa memberikan tag penutup </p> maka terjadi error senggingga bahasa mesin tidak dapat mengenalinya tetapi teks akan tetap ditampilkan dalam tampilan halaman web.
```
2. Apa perbedaan dari tag `<p>` dengan tag `<br>` berikan penjelasannya!
```
Tag <p> digunakan untuk membuat paragraf teks yang terstruktur, sementara tag <br> digunakan untuk membuat jeda baris di dalam teks.
```
3. Apa perbedaan atribut `title` dan `alt` pada tag `<img>`, berikan penjelasannya!
```
Atribut alt digunakan untuk memberikan teks alternatif untuk gambar, sementara atribut title digunakan untuk memberikan informasi tambahan atau tooltip saat kursor mouse mengarah ke gambar.
```
4. Untuk mengatur ukuran gambar, digunakan atribut `width` dan `height`. Agar tampilan gambar proporsional sebaiknya kedua atribut tersebut diisi semua atau tidak? Berikan penjelasannya!
```
Jika ingin menjaga proporsional gambar lebih baik mengisi hanya satu dari kedua atribut tersebut atau bisa juga menggunakan resaiz pada gambar seuai yang diinginkan 
```
5. Pada `link` tambahkan atribut `target` dengan nilai atribut bervariasi ( `_blank`, `_self`, `_top`, `_parent` ), apa yang terjadi pada masing-masing nilai antribut tersebut?
```
target _blank membuka halaman baru
target _self membuka halam ini dijendela/ditab yang sama
target _top buka halaman utama
target _parent buka halaman di frame induk
```
