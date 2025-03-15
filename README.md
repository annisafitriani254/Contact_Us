<?php
$koneksi = new mysqli("localhost", "annsaftrnii254", "Kazana15", "database");

$sql = "CREATE TABLE users (
    id INT AUTO_INCREMENT PRIMARY KEY,
    nama VARCHAR(50),
    email VARCHAR(50)
)";
$koneksi->query($sql);
?>

