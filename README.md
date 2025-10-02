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
    background: #1809e6;
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
    background: #1809e6;
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
    <link rel="stylesheet" href="style.css">
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
        <p style="text-align: center; color: #e6157d;">
            HALO <b>AFLAH ATHALLAH TAMAM KAPUKONG</b> DENGAN NIM <b>312410280</b> Saya sedang belajar HTML dan CSS
            dasar,
            pada mata kuliah <b>Pemrograman Web 1</b> di <i>Universitas Pelita Bangsa</i>.
            Hal pertama yang kami dapat adalah membuat tampilan web sederhana dalam rangka mengenal
            tag-tag dasar HTML dan CSS.
        </p>
    </div>

    <a class="button btn-primary" href="#intro">Informasi selengkapnya.</a>
</body>

</html>
```

# HASIL YANG TAMPIL DI WEB BROWSER SEBELUM MENGGUNAKAN STYLE CSS

![gambar](https://github.com/Abcdeflahhh/LAB2HTML-CSSWEB1/blob/500aadfb5b93a59af5d9efea9047a46c6c5f60ac/image/12025-10-02%2016_44_47-CSS%20Dasar%20-%20Personal%20-%20Microsoft%E2%80%8B%20Edge.png)

# SETELAH MENGGUNAKAN CSS PADA HTML EKSTERNAL

![gambar](https://github.com/Abcdeflahhh/LAB2HTML-CSSWEB1/blob/500aadfb5b93a59af5d9efea9047a46c6c5f60ac/image/22025-10-02%2016_46_50-CSS%20Dasar%20-%20Personal%20-%20Microsoft%E2%80%8B%20Edge.png)

# 5. MENAMBAHKAN CSS SELECTOR 

```
header {
    text-align: center;
    margin-bottom: 10px;
}

nav {
    background: #80A1BA;
    padding: 10px;
}

nav a {
    color: #432323;
    text-decoration: none;
    padding: 10px 20px;
    font-weight: bold;
}

nav a:hover {
    background: #432323;
}

#intro {
    background: #bebcbd;
    border: 1px solid #432323;
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
    background: #DD0303;
}
```

# HASIL DARI HTML MENGGUNAKAN CSS COLECTOR

![gambar](https://github.com/Abcdeflahhh/LAB2HTML-CSSWEB1/blob/e426f8244cbc96c46f735391d122b4643f66d391/image/2025-10-02%2017_02_00-CSS%20Dasar%20-%20Personal%20-%20Microsoft%E2%80%8B%20Edge.png)

# TUGAS 

![gambar](https://github.com/Abcdeflahhh/LAB2HTML-CSSWEB1/blob/1eee66845d301d2e187c9645517c2fbacc88cb5b/image/TUGAS%20%26%20SOAL%20.png)

# 1. EKSPERIMEN PROPERTI CSS

```
h1 i {
  color: #6d6a6b;
}

body {
  background-color: lightblue;
  font-family: Arial, sans-serif;
}

p {
  color: #a0522d; 
  font-size: 18px;
}
```

# HASILNYA

![gambar](https://github.com/Abcdeflahhh/LAB2HTML-CSSWEB1/blob/f573bda56c05e1b74fbea6459696f0d26ece3559/image/2025-10-02%2017_58_18-CSS%20Dasar%20-%20Personal%20-%20Microsoft%E2%80%8B%20Edge.png)

# 2. PERBEDAAN h1 {…} dengan #intro h1 {…}

h1 {} = global, semua <h1> di halaman.
#intro h1 {} = spesifik, hanya <h1> yang ada di dalam elemen dengan id="intro".

```
<div>
  <h1>Judul 1 (umum)</h1>
</div>

<div id="intro">
  <h1>Judul 2 (khusus di dalam #intro)</h1>
</div>
```

```
h1 {
  color: red;
}

#intro h1 {
  color: green;
}
```

# 3. PRIORITAS CSS (Internal, Eksternal, Inline)

Inline CSS (langsung di atribut elemen HTML) → prioritas tertinggi
Internal CSS (<style> di dalam file HTML) → prioritas menengah
Eksternal CSS (file .css yang dilink) → prioritas lebih rendah

```
<head>
  <!-- Eksternal CSS -->
  <link rel="stylesheet" href="style.css">
  <style>
    /* Internal CSS */
    p { color: blue; }
  </style>
</head>
<body>
  <p style="color: red;">Teks percobaan</p>
</body>
```

# 4. JIKA ELEMEN PUNYA ID & CLASS

Aturan prioritas selector:
Inline CSS > ID > Class > Elemen

```
<p id="paragraf-1" class="text-paragraph">Teks uji coba</p>
```

```
p {
  color: black;       /* paling lemah */
}

.text-paragraph {
  color: blue;        /* class */
}

#paragraf-1 {
  color: green;       /* id lebih kuat */
}
```
