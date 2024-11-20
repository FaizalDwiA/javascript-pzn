# Kode server 

pastikan aktifkan xampp

```php
<?php 

if($_SERVER["REQUEST_METHOD"] === "POST") {
    $data = $_POST["data"];
    var_dump($POST);
    // lakukan apa pun yang ingin anda lakukan dengan data, seperti menyimpan ke database / melakukan tindakan lain di server

    // contoh kirim balik ke client (opsional)
    echo "Data yang dikirimkan: " . $data;
}
?>
```