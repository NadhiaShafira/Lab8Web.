# Lab8Web.

**NAMA                : NADHIA SHAFIRA**

**NIM                 : 312410498**

**KELAS               : TI.24.A.5**

**MATKUL              : PEMOGRAMAN WEB 1**

**Dosen Pengampu      : Agung Nugroho, S.Kom., M.Kom.**

## 📌 Tujuan Praktikum
Praktikum ini bertujuan untuk mempelajari:
- Menghubungkan PHP dengan database MySQL menggunakan `mysqli`
- Melakukan operasi **CRUD** (Create, Read, Update, Delete)
- Menggunakan form HTML untuk input data
- Upload file (gambar) menggunakan `enctype="multipart/form-data"`
- Menampilkan data dalam bentuk tabel
- Mengatur struktur folder pada XAMPP (`htdocs`)

---

## 🗄️ 1. Membuat Database & Tabel
Database dibuat melalui phpMyAdmin:

```sql
CREATE DATABASE latihan1;
USE latihan1;

CREATE TABLE data_barang (
  id_barang INT(10) AUTO_INCREMENT PRIMARY KEY,
  kategori VARCHAR(30),
  nama VARCHAR(30),
  gambar VARCHAR(100),
  harga_beli DECIMAL(10,0),
  harga_jual DECIMAL(10,0),
  stok INT(4)
);

```
**Hasil :**
![foto](
