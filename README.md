# SEMANTIC-HTML
Latihan Praktikum 1 Semantic Html
# Syahrulreza2205101079

### 1. Tag <html> dan <body>
### Codingan 1 (HTML)
-**Tidak Memakai Tag <html> dan <body>**:
Struktur halaman langsung dimulai dengan tag <header>, yang berarti kode tersebut belum sepenuhnya mengikuti standar HTML5.

### Codingan 2 (HTML)
-**Menggunakan Tag <html> dan <body>**:
Kode ini memanfaatkan tag <html> yang dilengkapi atribut lang="en" untuk menunjukkan bahwa bahasa halaman adalah bahasa Inggris. Selain itu, tag <body> juga digunakan untuk membungkus seluruh konten halaman, termasuk <header>, <nav>, <section>, dan <footer>.

### 2. Tag <head>
### Codingan 1 (HTML)
-**Tidak Ada Tag <head>**:
Tidak adanya tag <head> membuat informasi penting, seperti meta tag dan tautan ke file eksternal seperti CSS, tidak tercantum. Hal ini dapat memengaruhi aksesibilitas dan performa halaman.

### Codingan 2 (HTML)
-**Memiliki Tag <head> Lengkap**:
Tag <head> dilengkapi elemen-elemen penting untuk optimasi dan kompatibilitas, seperti:
<meta charset="UTF-8"> untuk menentukan pengkodean karakter.
<meta name="viewport" content="width=device-width, initial-scale=1.0"> untuk menyesuaikan tampilan responsif di perangkat mobile.
<title>HTML5 Semantic</title> untuk menetapkan judul halaman.
<link rel="stylesheet" href="./assets/styles/styles.css"> untuk menghubungkan file CSS eksternal.

### 3. Penutupan Tag
### Codingan 1 (HTML)
-**Tag Penutup Tidak Lengkap**:
Tag penutup seperti </html> atau </body> tidak disertakan, sehingga struktur HTML menjadi tidak lengkap dan tidak sesuai dengan standar HTML5.

### Codingan 2 (HTML)
-**Tag Penutup Lengkap**:
Memiliki tag penutup </html> dan </body> yang lengkap, yang menjadikan struktur HTML sesuai dengan standar HTML5.

### 4.Penggunaan lang="en" pada Tag <html>
### Codingan 1 (HTML)
-**Tidak Ada Atribut lang pada Tag <html>**:
Tidak adanya atribut lang dapat menyebabkan halaman sulit dipahami oleh mesin pencari atau pembaca layar.

### Codingan 2 (HTML)
-**Ada Atribut lang="en" pada Tag <html>**:
Atribut ini menandakan bahwa bahasa yang digunakan pada halaman adalah bahasa Inggris, sehingga dapat membantu mesin pencari dan pembaca layar untuk memahami bahasa halaman serta meningkatkan aksesibilitas.

### 5.Penyusunan Struktur Halaman
### Codingan 1 (HTML)
-**Struktur HTML Minimal**:
Struktur HTML hanya mencakup elemen-elemen dasar seperti <header>, <nav>, <section>, dan <footer>, tanpa menyertakan elemen penting lainnya seperti <head> dan <body>.

### Codingan 2 (HTML)
-**Struktur HTML Lengkap**:
Struktur HTML pada kode ini lebih lengkap dengan adanya elemen <head> dan <body>, yang mengikuti standar HTML5 dan praktik pengkodean yang lebih baik.

### 6.grid-template-columns
### Codingan 1 (CSS)
-**Kesalahan pada Penulisan grid-template-columns**:
grid-template-columns: 20% 1fr 18;
Penulisan ini menetapkan lebar kolom grid dengan 20%, 1fr, dan 18 tanpa satuan ukuran yang sesuai, yang dapat dianggap tidak valid atau menghasilkan layout yang tidak diinginkan.

### Codingan 2 (CSS)
-**Penulisan grid-template-columns yang Benar**:
grid-template-columns: 20% 1fr 18%;
Pada kode ini, lebar kolom ketiga ditentukan dengan satuan ukuran yang benar, yaitu 18%, sehingga ketiga kolom memiliki ukuran yang valid.

### 7.Margin pada <body>
### Codingan 1 (CSS)
-**Tidak Ada Margin pada <body>**:
Tidak adanya properti margin pada elemen <body> membuat konten halaman menempel pada tepi jendela browser.

### Codingan 2 (CSS)
-**Penambahan Margin pada <body>**:
margin: 10px;
Pada kode ini, margin sebesar 10px ditambahkan pada elemen <body>, memberikan jarak antara konten halaman dan tepi jendela browser.

### 8.Kesalahan Penulisan pada Footer di Codingan 1
### Codingan 1 (CSS)
-**Kesalahan pada Penulisan Selector Footer**:
I footer { ... }
Kode ini salah dalam menuliskan selector untuk elemen footer, yaitu dengan menggunakan "I footer" (harusnya tanpa huruf "I" di depan footer), sehingga aturan CSS tidak berlaku pada elemen footer.

### Codingan 2 (CSS)
-**Penulisan Selector Footer yang Benar**:
footer { ... }
Pada kode ini, selector CSS untuk elemen footer ditulis dengan benar (tanpa huruf "I"), sehingga aturan CSS dapat diterapkan pada elemen footer dengan benar.
