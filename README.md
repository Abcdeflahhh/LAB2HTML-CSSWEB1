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

# CODE HTML DI VSCODE

![gambar](https://github.com/Abcdeflahhh/LAB2HTML-CSSWEB1/blob/a482927d5f8cb1a850e74a526a78fb5d60e08e9a/image/htmlcss1.png)

# GAMBAR HASIL HTML YANG DIJALANKAN PADA BROWSER :

![GAMBAR](https://github.com/Abcdeflahhh/LAB2HTML-CSSWEB1/blob/a482927d5f8cb1a850e74a526a78fb5d60e08e9a/image/htmlcss2.png)

# 2. MEMBUAT STYLE UNTUK HTML MENGGUNAKAN INTERNAL CSS

TAMBAHKAN INTERNAL CSS PADA BAGIAN HEAD DOKUMEN
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>CSS Dasar</title>
  <style>
    body {
      font-family: 'Open Sans', sans-serif;
    }
    header {
      min-height: 80px;
      border-bottom: 1px solid #77CCEF;
    }
    h1 {
      font-size: 24px;
      color: #0F189F;
      text-align: center;
      padding: 20px 10px;
    }
    h1 i {
      color: #6d6a6b;
    }
  </style>
</head>
<body>
  <header>
    <h1>CSS Internal dan <i>Inline CSS</i></h1>
  </header>
  
  <nav>
    <a href="lab2_css_dasar.html">CSS Dasar</a>
    <a href="lab2_css_eksternal.html">CSS Eksternal</a>
    <a href="lab1_tag_dasar.html">HTML Dasar</a>
  </nav>

  <div id="intro">
    <h1>Hello World</h1>
    <p>
      HALO <b>AFLAH ATHALLAH TAMAM KAPUKONG</b> DENGAN NIM <b>312410280</b> Saya sedang belajar HTML dan CSS dasar, 
      pada mata kuliah <b>Pemrograman Web 1</b> di <i>Universitas Pelita Bangsa</i>. 
      Hal pertama yang kami dapat adalah membuat tampilan web sederhana dalam rangka mengenal 
      tag-tag dasar HTML dan CSS.
    </p>

    <a class="button btn-primary" href="#intro">Informasi selengkapnya.</a>
  </div>
</body>
</html>
```

# CODE HTML INTERNAL CSS DI VSCODE

![gambar](https://github.com/Abcdeflahhh/LAB2HTML-CSSWEB1/blob/92b47e34a01b944061a06b4b3d786fb7379a3f8c/image/pp2025-10-02%2016_21_39-index.html%20-%20LAB2HTML%20-%20Visual%20Studio%20Code.png)

# HASIL HTML INTERNAL CSS DI BROWSER 

![gambar](https://github.com/Abcdeflahhh/LAB2HTML-CSSWEB1/blob/92b47e34a01b944061a06b4b3d786fb7379a3f8c/image/222025-10-02%2016_22_04-CSS%20Dasar%20-%20Personal%20-%20Microsoft%E2%80%8B%20Edge.png)

# 3. MENAMBAHKAN INLINE CSS 

```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>CSS Dasar</title>
  <style>
    body {
      font-family: 'Open Sans', sans-serif;
    }
    header {
      min-height: 80px;
      border-bottom: 1px solid #77CCEF;
    }
    h1 {
      font-size: 24px;
      color: #0F189F;
      text-align: center;
      padding: 20px 10px;
    }
    h1 i {
      color: #6d6a6b;
    }

    #intro p {
      text-align: center;
      color: #ccd8e4;
      line-height: 1.6;
    }
    nav a {
      margin-right: 15px;
      text-decoration: none;
      color: #0F189F;
    }
    nav a:hover {
      color: #77CCEF;
    }
  </style>
</head>
<body>
  <header>
    <h1>CSS Internal dan <i>Inline CSS</i></h1>
  </header>
  
  <nav>
    <a href="lab2_css_dasar.html">CSS Dasar</a>
    <a href="lab2_css_eksternal.html">CSS Eksternal</a>
    <a href="lab1_tag_dasar.html">HTML Dasar</a>
  </nav>

  <div id="intro">
    <h1>Hello World</h1>
    <p>
      HALO <b>AFLAH ATHALLAH TAMAM KAPUKONG</b> DENGAN NIM <b>312410280</b> Saya sedang belajar HTML dan CSS dasar, 
      pada mata kuliah <b>Pemrograman Web 1</b> di <i>Universitas Pelita Bangsa</i>. 
      Hal pertama yang kami dapat adalah membuat tampilan web sederhana dalam rangka mengenal 
      tag-tag dasar HTML dan CSS.
    </p>

    <a class="button btn-primary" href="#intro">Informasi selengkapnya.</a>
  </div>
</body>
</html>
```
# INLINE HTML CSS DI VSCODE

![gambar](https://github.com/Abcdeflahhh/LAB2HTML-CSSWEB1/blob/c8d933fe29369a5933457fa87d519c9e9343daff/image/ngok2025-10-02%2016_30_27-index.html%20-%20LAB2HTML%20-%20Visual%20Studio%20Code.png)

# HASIL INLINE HTML CSS DI BROWSER

![gambar](https://github.com/Abcdeflahhh/LAB2HTML-CSSWEB1/blob/c8d933fe29369a5933457fa87d519c9e9343daff/image/ngokk2025-10-02%2016_30_45-CSS%20Dasar%20-%20Personal%20-%20Microsoft%E2%80%8B%20Edge.png)

# 4. MEMBUAT CSS EKSTERNAL UNTUK HTML

```
nav {
  background: #20A759;
  color: #fff;
  padding: 10px;
}

nav a {
  color: #fff;
  text-decoration: none;
  padding: 10px 20px;
}

nav .active,
nav a:hover {
  background: #0B6B3A;
}
```

# LALU TAMBAHKAN KE BAGIAN HTML MENJADI 

```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>CSS Dasar</title>
  <link rel="stylesheet" href="lat2web1.css" type="text/css">
  <style>
    body {
      font-family: 'Open Sans', sans-serif;
    }
    header {
      min-height: 80px;
      border-bottom: 1px solid #77CCEF;
    }
    h1 {
      font-size: 24px;
      color: #0F189F;
      text-align: center;
      padding: 20px 10px;
    }
    h1 i {
      color: #6d6a6b;
    }
  </style>
</head>
<body>
  <header>
    <h1>CSS Internal dan <i>Inline CSS</i></h1>
  </header>

  <nav>
    <a href="lab2_css_dasar.html">CSS Dasar</a>
    <a href="lab2_css_eksternal.html">CSS Eksternal</a>
    <a href="lab1_tag_dasar.html">HTML Dasar</a>
  </nav>

  <div id="intro">
    <h1>Hello World</h1>
    <p style="text-align: center; color: #cc6d4e;">
      SAYA <b>ANDREAN PUTRA ARYA</b> DENGAN NIM <b>312410341</b> kami sedang belajar HTML dan CSS dasar, 
      pada mata kuliah <b>Pemrograman Web</b> di <i>Universitas Pelita Bangsa</i>. 
      Pelajaran pertama yang kami dapat adalah membuat tampilan web sederhana dalam rangka mengenal 
      tag-tag dasar HTML dan CSS.
    </p>
  </div>

  <a class="button btn-primary" href="#intro">Informasi selengkapnya.</a>
</body>
</html>
```
