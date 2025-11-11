# 🧩 Praktikum 7 – PHP Dasar

## Haikal Lukman Nur Hakim
## 312410142


## Mata Kuliah: Pemrograman Web
## Dosen: Agung Nugroho
## Universitas Pelita Bangsa, Bekasi

# 🎯 Tujuan Praktikum

Memahami konsep dasar Server-Side Scripting menggunakan PHP.

Mampu memahami dasar pemrograman PHP (variabel, tipe data, kondisi, dan perulangan).

Membuat program PHP sederhana dengan input dan output dinamis.

![Gambar](Lab7web.jpg)

# 💡 Langkah-Langkah Praktikum
## 1. Menjalankan Web Server

Jalankan Apache melalui XAMPP Control Panel
Lalu uji coba di browser dengan membuka:

http://localhost/


Jika muncul halaman XAMPP, berarti server sudah aktif ✅

## 2. Membuat File PHP Dasar

File: php_dasar.php
```html
<!DOCTYPE html>
<html>
<head><title>PHP Dasar</title></head>
<body>
    <h1>Belajar PHP Dasar</h1>
    <?php echo "Hello World!"; ?>
</body>
</html>
```

Hasil:
Menampilkan teks Hello World! di browser.

## 3. Membuat Variabel dan Menampilkan Nilainya
<?php
$nim = "0411500400";
$nama = "Abdullah";
echo "NIM: $nim <br>";
echo "Nama: $nama";
?>


Hasil:
Menampilkan NIM dan Nama di browser.

## 4. Form Input dengan Metode POST
```php
<form method="post">
    <label>Nama:</label>
    <input type="text" name="nama">
    <input type="submit" value="Kirim">
</form>
<?php
echo "Selamat Datang " . $_POST['nama'];
?>
```

Hasil:
Menampilkan input nama yang diketik pengguna.

# 🧮 Tugas Akhir Praktikum
Deskripsi

Buat program dengan form input nama, tanggal lahir, dan pekerjaan.
Tampilkan hasil berupa:

Nama

Umur (hasil perhitungan dari tanggal lahir)

Pekerjaan
