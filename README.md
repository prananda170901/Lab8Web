# Lab8Web

## Nama : Prananda Aditya

## NIM : 312010130

## Kelas : TI.20.A1

## Mata Kuliah : Pemograman Web

# Langkah - langkah Praktikum

## Persiapan

<br>Untuk memulai membuat aplikasi CRUD sederhana, yang perlu disiapkan adalah server menggunakan MySQL. Pastikan MySQL Server sudah dapat dijalankan melalui Xampp.

# 1. Menjalankan MySQL

<br>Untuk Menjalankan MySQL server dari menu XAMPP control.
![p](img/xampp.png)

## Mengakses MySQL Client menggunakan PHP Myadmin

<br>Pastikan webserver Apache dan MySQL server sudah dijalankan. Kemudian buka Browser: http://localhost/phpmyadmin/
![p](img/php%20myadmin.png)

# 2. Membuat Database: Studi Kasus Data Barang

![p](img/contoh%20data%20base.png)

## Membuat Database

```
CREATE DATABASE latihan1;
```

![p](img/data%20base%20latihan%201.png)

## Membuat Tabel

```
CREATE TABLE data_barang (
 id_barang int(10) auto_increment Primary Key,
 kategori varchar(30),
 nama varchar(30),
 gambar varchar(100),
 harga_beli decimal(10,0),
 harga_jual decimal(10,0),
 stok int(4)
);
```

![p](img/create%20table.png)

## Menambahkan data

```
INSERT INTO data_barang (kategori, nama, gambar, harga_beli, harga_jual, stok)
VALUES ('Elektronik', 'HP Samsung Android', 'hp_samsung.jpg', 2000000, 2400000, 5),
('Elektronik', 'HP Xiaomi Android', 'hp_xiaomi.jpg', 1000000, 1400000, 5),
('Elektronik', 'HP OPPO Android', 'hp_oppo.jpg', 1800000, 2300000, 5);
```

![p](img/menambahkan%20data.png)
