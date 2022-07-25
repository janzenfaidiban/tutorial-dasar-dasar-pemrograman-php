# Tutorial Dasar-Dasar Bahasa Pemrograman PHP (1)

## Tutorial Video

[Dasar-Dasar Bahasa Pemrograman PHP (1)](url_here)

## Garis Besar

✅ Menjalankan server lokal (Apache pada XAMPP) <br>
✅ Folder htdocs <br>
✅ Folder proyek php <br>
✅ Folder proyek dari  repository GitHub <br>
✅ File PHP <br>
✅ PHP Syntax <br>
✅ Kombinasi PHP dan HTML <br>
✅ PHP Comments <br>
✅ PHP Variables <br>
✅ PHP Echo / Print <br>

## Folder htdocs

Htdocs merupakan folder untuk menyimpan file-file PHP dan folder project php.
Folder ```htdocs``` ada di dalam folder ```C:/xampp/htdocs```.

## Folder proyek PHP

Folder proyek PHP ditempatkan di dalam folder htdocs dengan susunan  ```C:/xampp/htdocs/sacode-project01```

## Folder proyek PHP dari repository GitHub 

Buat repository di GitHub dan kemudian clone ke dalam folder htdocs.


## File PHP

File PHP memiliki eksetensi ```.php```. 
Di dalam file php kita bisa menulis code HTML, CSS, JavaScript dan code PHP.
Code PHP diproses pada server dan hasilnya ditampilkan lewat web browser sebagai teks biasa.

Buat file php dengan nama ```index.php``` di dalam folder proyek


📄 index.php

```php
<?php 
	echo "Hello World!";
?>
```

## PHP Syntax

PHP Script dimulai dengan ```<?php``` dan diakhiri dengan ```?>```

📄 syntax.php

```php
<?php 
	// code PHP ditulis di sini
	echo "Hello PHP!";
?>
```

## Kombinasi PHP dan HTML

Sebuah file PHP bisa dikombinasikan dengan tag HTML dan script PHP.

📄 php-html.php

```php
<!DOCTYPE html>
<html>
<head>
	<title>Kombinasi PHP & HTML</title>
</head>
<body>

	<h1>Kombinasi PHP & HTML</h1>

	<?php
		echo "Hello PHP!";
	?>

</body>
</html>
```


## PHP Comments

Komentar di PHP merupakan baris code yang tidak dieksekusi dalam program dan biasa digunakan untuk menerangkan bagian-bagian tertentu pada program.

📄 comments.php

```php
<?php 
	// contoh komentar single-line di php

	# ini juga contoh komentar single-line di php

	/*
	Kalau yang ini merupakan contoh 
	komentar multiple-lines
	yang bisa diterapkan
	di dalam sebuah file PHP
	*/

	echo "PHP Comments";
?>
```

## PHP Variables

Variable dapat diilustrasikan sebagai wadah untuk menyimpan informasi tertentu.

Sebuah variable dimulai dengan simbol ```$```.

📄 variables.php

```php
<?php 
	// Contoh penulisan variables di dalam file PHP
	$title = "SaCode";
	$tag_line = "Papua Coding School";
	$tahun = "2022";

	// Menampilkan data dari dalam variable
	echo $title;
	echo "<br>";

	echo $tag_line;
	echo "<br>";

	echo $tahun;
?>
```

## PHP Echo / Print

Ada dua cara mendasar dalam mencetak atau menampilkan hasil yaitu ```echo``` dan ```print```.
Sekilas ``echo`` lebih cepat dalam menampilkan deibanding dengan ```print```.


📄 echo-print.php

```php
<?php 
	// Contoh penggunaan echo
	echo "<h1>Papua Tech Community</h1>";
	echo "<p>Berbagi dan belajar bersama di komunitas.</p>";

	// Contoh penggunaan print
	print "<h1>Papua Coding School</h1>";
	print "<p>Belajar coding dari dasar dengan mengikuti kursus.</p>";
?>
```