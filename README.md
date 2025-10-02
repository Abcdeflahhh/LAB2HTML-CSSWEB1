# MODUL PRAKTIKUM PEMROGRAMAN WEB

NAMA : AFLAH ATHALLAH TAMAM KAPUKONG 

Nim : 312410280

Kelas : TI.24.A4

# INSTRUKSI PRAKTIKUM 

1. Persiapkan text editor misalnya VSCode.
2. Buat file baru dengan nama lat2web1.html
3. Buat struktur dasar dari dokumen HTML.
4. Ikuti langkah-langkah praktikum yang akan dijelaskan berikutnya.

# 1. MEMBUAT DOKUMEN HTML

CODE HTML SEPERTI BERIKUT :
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CSS PEMULA 1</title>
</head>
<body>
    <header>
        <h1>CSS Internal dan <i>Inline CSS</i></h1>
    </header>
    <nav>
        <a href="lab2_css_dasar.html">CSS Basic</a>
        <a href="lab2_css_eksternal.html">CSS Eksternal</a>
        <a href="lab1_tag_dasar.html">HTML Dasar</a>
    </nav>
    
    <div id="intro">
        <h1>Hello World</h1>
        <p>AKU<b>AFLAH ATHALLAH TAMAM KAPUKONG</b> DENGAN NIM <b>312410280</b> saya sedang mencoba belajar HTML dan CSS dasar, pada mata
            kuliah <b>Pemrograman Web 1</b> di
            <i>Universitas Pelita Bangsa</i>. hal pertama yang kami dapat adalah membuat
            tampilan web sederhana dalam mengenal tag-tag dasar HTML dan CSS.
        </p>
    
        <a class="button btn-primary" href="#intro">Informasi selengkapnya.</a>
    </div>
</body>
</html>
```

GAMBAR HASIL HTML YANG DIJALANKAN PADA BROWSER :

# 2. MEMBUAT STYLE UNTUK HTML MENGGUNAKAN CSS

TAMBAHKAN INTERNAL CSS PADA BAGIAN HEAD DOKUMEN
```
header {
  text-align: center;
  margin-bottom: 10px;
}

nav {
  background: #2ecc71;
  padding: 10px;
}

nav a {
  color: white;
  text-decoration: none;
  padding: 10px 20px;
  font-weight: bold;
}

nav a:hover {
  background: #27ae60;
}

#intro {
  background: #418fb1;
  border: 1px solid #099249;
  min-height: 200px;
  padding: 20px;
}

#intro h1 {
  text-align: left;
  border: 0;
  color: #fff !important;
}

#intro p {
  color: #fff !important;
}

.button {
  padding: 15px 20px;
  background: #bebcbd;
  color: #fff;
  display: inline-block;
  margin: 10px 0;
  text-decoration: none;
}

.btn-primary {
  background: #E42A42;
}
```





