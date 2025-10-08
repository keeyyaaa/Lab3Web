# Lab3Web - Pemrograman Web - Praktikum 3 - Membuat List, Table, dan Form

Nama : Ica Rizqiah

Nim : 312410554

Kelas : TI.24.A.5

# Langkah - langkah Praktikum 3

## 1. Membuat Dokumen HTML kemudian membuat Ordered List
![foto](https://github.com/keeyyaaa/Lab3Web/blob/main/Kode%20membuat%20ordered%20list.png)

## Penjelasan:

#### Langkah 1: Membuat Dokumen HTML Baru

Saya membuat file baru dengan nama `Lab3Web.html` yang berisi struktur dasar HTML5.
Tag `<!DOCTYPE html>` digunakan untuk menandai bahwa dokumen ini memakai standar HTML versi 5.
Di dalam tag `<head>` saya menambahkan `<title>` dengan judul “HTML Lanjutan”.
Tujuannya supaya halaman web punya kerangka dasar yang lengkap.

#### Langkah 2: Menambahkan Header

Saya menambahkan elemen `<header>` yang berisi `<h1>` dengan teks “Membuat List”.
Bagian ini berfungsi sebagai judul utama halaman web, jadi pengunjung langsung tahu isi halamannya tentang apa.

#### Langkah 3: Membuat Ordered List (Daftar Berurutan)

Selanjutnya, saya menambahkan tag `<ol>` untuk membuat daftar berurutan (ordered list).
Setiap item daftar saya tulis menggunakan tag `<li>` (list item).
Tag `<ol>` otomatis memberi nomor pada setiap itemnya.

#### Langkah 4: Menyimpan dan Menjalankan di Browser

Saya menyimpan file tersebut, lalu membuka di browser.
Hasilnya muncul daftar bernomor sesuai isi yang saya tulis.

## Hasilnya:
![foto](https://github.com/keeyyaaa/Lab3Web/blob/main/Hasil%20pembuatan%20list.png)

## 2. Membuat Unordered List
![foto](https://github.com/keeyyaaa/Lab3Web/blob/main/Kode%20dan%20hasil%20pembuatan%20Unordered%20List.png
)

## Penjelasan:

#### Langkah: Membuat Unordered List (Daftar Tidak Berurutan)

Setelah membuat ordered list, pada langkah ini saya menambahkan bagian baru untuk menampilkan daftar tidak berurutan (unordered list).

Saya menggunakan tag `<section>` dengan `id="unorder-list"` agar bagian ini bisa dibedakan dari bagian sebelumnya.

Di dalamnya terdapat tag `<h2>` untuk memberikan judul bagian, yaitu “Unordered List”.
Lalu saya menambahkan tag `<ul>` (unordered list) untuk membuat daftar dengan tanda bullet (titik atau simbol), bukan angka seperti `<ol>`.

Pada tag `<ul>` saya tambahkan atribut `type="square"` supaya bentuk bullet-nya menjadi kotak (⬛), bukan bulat.
Setiap item daftar ditulis menggunakan tag `<li>` (list item).

#### Berikut potongan kodenya:

```html
<section id="unorder-list">
  <h2>Unordered List</h2>
  <ul type="square">
    <li>Jaringan Komputer</li>
    <li>Struktur Data</li>
    <li>Algoritma &amp; Pemrograman</li>
  </ul>
</section>
```

#### Penjelasan fungsi tiap tag:

`<section>` → Membuat bagian baru di halaman web.

`<h2>` → Subjudul bagian list.

`<ul>` → Membuat daftar tanpa urutan angka (pakai simbol bullet).

`type="square"` → Mengubah bentuk bullet jadi kotak.

`<li>` → Menuliskan setiap item di daftar.

## 3. Membuat Description List
![foto](https://github.com/keeyyaaa/Lab3Web/blob/main/Kode%20dan%20hasil%20pembuatan%20Description%20List.png)

## Penjelasan:

Elemen `<dl>` digunakan untuk membuat daftar deskripsi.

- `<dt>` (Definition Term) menandai istilah atau judul.

- `<dd>` (Definition Description) berisi penjelasan atau daftar dari istilah tersebut.
  
## 4. Membuat Table
![foto](https://github.com/keeyyaaa/Lab3Web/blob/main/Kode%20dan%20hasil%20Pembuatan%20Table.png)

## Penjelasan:

1. Membuat File HTML Baru

Buat file baru dengan nama `lab3_tabel.html`.

Tambahkan struktur dasar HTML sebagai berikut:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML Lanjutan</title>
</head>
<body>
    <header>
        <h1>Membuat Table</h1>
    </header>
</body>
</html>
```

`<header>` : Menandai bagian kepala halaman.

`<h1>` : Judul utama halaman.

2. Menambahkan Tabel Sederhana
Di dalam `<body>`, setelah `<header>`, tambahkan kode tabel:

```html
<table border="1" cellpadding="4" cellspacing="0">
    <thead>
        <tr>
            <th>No.</th>
            <th>Fakultas</th>
            <th>Program Studi</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>1.</td>
            <td>Teknik</td>
            <td>Teknik Informatika</td>
        </tr>
        <tr>
            <td>2.</td>
            <td>Teknik</td>
            <td>Teknik Industri</td>
        </tr>
        <tr>
            <td>3.</td>
            <td>Teknik</td>
            <td>Teknik Lingkungan</td>
        </tr>
    </tbody>
</table>
```
Penjelasan Elemen Tabel:

`<table>` : Container utama tabel.

`border="1"` → Memberikan garis tepi tabel.

`cellpadding="4"` → Memberikan jarak antara teks dan tepi sel.

`cellspacing="0"` → Menghapus jarak antar sel.

`<thead>` : Bagian kepala tabel yang biasanya berisi judul kolom.

`<tr>` : Baris tabel.

`<th>` : Sel judul kolom (teks tebal, rata tengah).

`<tbody>` : Bagian isi tabel.

`<td>` : Sel isi data.

## 5. Menggabungkan Sel Data
![foto](https://github.com/keeyyaaa/Lab3Web/blob/main/Kode%20dan%20hasil%20Penggabungan%20Table.png)

## Penjelasan:

1. Membuat Tabel Dasar

Gunakan struktur tabel seperti pada praktikum sebelumnya.

Tambahkan `<table>` dengan atribut:

```html
<table border="1" cellpadding="6" cellspacing="0">
    <thead>
        <tr>
            <th>No.</th>
            <th>Fakultas</th>
            <th>Program Studi</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>1.</td>
            <td rowspan="3">Teknik</td>
            <td>Teknik Informatika</td>
        </tr>
        <tr>
            <td>2.</td>
            <td>Teknik Industri</td>
        </tr>
        <tr>
            <td>3.</td>
            <td>Teknik Lingkungan</td>
        </tr>
    </tbody>
</table>
```
2. Penjelasan Atribut rowspan dan colspan

- `rowspan`

Digunakan untuk menggabungkan sel secara vertikal (menyatu ke bawah beberapa baris).

Contoh: `<td rowspan="3">Teknik</td>` → sel “Teknik” mencakup 3 baris sehingga tidak perlu menulis “Teknik” pada setiap baris.

- `colspan`

Digunakan untuk menggabungkan sel secara horizontal (menyatu ke samping beberapa kolom).

Contoh (jika digunakan):

````html
<td colspan="2">Informasi Fakultas</td>
````

→ sel ini akan menempati dua kolom sekaligus.

3. Penjelasan Hasil:

Sel “Teknik” terlihat menyatu vertikal untuk 3 baris, sehingga tampilan lebih ringkas dan rapi.

Jika menggunakan `colspan`, kolom tertentu bisa digabung secara horizontal, misal untuk judul yang mencakup beberapa kolom.

## 6. Membuat Form
![foto](https://github.com/keeyyaaa/Lab3Web/blob/main/Kode%20dan%20hasil%20Pembuatan%20Form.png)

## Penjelasan:

1. Membuat File HTML Baru

Buat file baru dengan nama `lab3_form.html`.

Tambahkan struktur dasar HTML berikut:

````html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML Lanjutan</title>
</head>
<body>
    <header>
        <h1>Membuat Form</h1>
    </header>
</body>
</html>
````

Penjelasan:

`<header>` : Bagian kepala halaman.

`<h1>` : Judul utama halaman.

2. Menambahkan Formulir Input

Tambahkan kode form di dalam `<body>`:

```html
<form action="proses.php" method="post">
    <fieldset>
        <legend>Data Pelanggan</legend>

        <p>
            <label for="nama">Nama</label>
            <input type="text" id="nama" name="nama">
        </p>

        <p>
            <label for="alamat">Alamat</label>
            <textarea id="alamat" name="alamat" cols="20" rows="3"></textarea>
        </p>

        <p>
            <label>Jenis Kelamin</label>
            <input id="jk_l" type="radio" name="kelamin" value="L">
            <label for="jk_l">Laki-laki</label>

            <input id="jk_p" type="radio" name="kelamin" value="P">
            <label for="jk_p">Perempuan</label>
        </p>

        <p>
            <input type="submit" value="Login">
        </p>

    </fieldset>
</form>
```

3. Penjelasan Elemen Form

- `<form>`

Container utama form.

`action="proses.php"` → alamat file yang akan memproses data ketika tombol submit diklik.

`method="post"` → metode pengiriman data ke server.

- `<fieldset>` dan `<legend>`

`<fieldset>` : Mengelompokkan elemen form menjadi satu kotak.

`<legend>` : Judul kelompok form.

- `<label>`

Memberikan label pada input, memudahkan pengguna dan aksesibilitas.

Atribut `for="id_input"` menghubungkan label dengan input terkait.

- `<input>`

`type="text"` → untuk input teks satu baris.

`type="radio"` → pilihan radio button (pilih salah satu).

`type="submit"` → tombol untuk mengirim data.

- `<textarea>`

Untuk input teks multiline (lebih dari satu baris).

`cols` dan `rows` menentukan lebar dan tinggi area teks.

4. Menyimpan dan Menjalankan Form

Simpan file `lab3_form.html`.

Buka file di browser, maka akan terlihat form input data pelanggan dengan:

- Kolom Nama

- Kolom Alamat

- Pilihan Jenis Kelamin

- Tombol Login
  
## 7. Menambahkan Style CSS pada Form
![foto](https://github.com/keeyyaaa/Lab3Web/blob/main/Kode%20dan%20hasil%20penambahan%20Sttyle%20dengan%20CSS.png)

## Penjelasan:

```css
form p > label {
    display: inline-block;
    width: 100px;
}
```

Memilih `<label>` yang langsung berada di dalam `<p>` dalam form (`p > label`).

`display: inline-block;` → membuat label bisa diberi lebar tanpa pindah baris.

`width: 100px;` → label akan selalu memiliki lebar 100px, sehingga semua input sejajar rapi di samping label.

```css
form input[type="text"], form textarea {
    border: 1px solid #197a43;
}
```

Memilih input teks dan textarea di dalam form.

`border: 1px solid #197a43;` → memberi garis tepi berwarna hijau (#197a43) dengan ketebalan 1px.

Membuat kotak input terlihat jelas dan konsisten.

```css
form input[type="submit"] {
    border: 1px solid #197a43;
    background-color: #197a43;
    color: #ffffff;
    font-weight: bold;
    padding: 5px 15px;
}
```

Memilih tombol submit di dalam form.

`border: 1px solid #197a43;` → garis tepi hijau seperti input.

`background-color: #197a43;` → memberi latar hijau pada tombol.

`color: #ffffff;` → teks tombol berwarna putih agar kontras.

`font-weight: bold;` → teks tombol menjadi tebal.

`padding: 5px 15px;` → memberi jarak di dalam tombol, sehingga tombol terlihat lebih nyaman diklik.

Hasil Tampilan Form

- Label dan input akan rapi sejajar.

- Input teks dan textarea punya border hijau yang konsisten.

- Tombol submit terlihat menonjol dengan warna hijau dan teks putih.
  
## Pertanyaan dan Tugas
### 1. Buatlah form yang menampilkan dropdown menu dan listbox dengan multiple selection.

![foto](https://github.com/keeyyaaa/Lab3Web/blob/main/dropdown%20menu%20dan%20listbox.png)





