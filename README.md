# lab2web

# Tampilan Web 
<img width="1366" height="768" src="https://github.com/dnrprsty/lab02Web/blob/1f0e248a5906d0eeee629fbf873bcf50a9f1a457/TampilanWeb.png" />



#  contoh kode html
```
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <!-- Internal CSS -->
    <link rel="stylesheet" href="style_eksternal.css" type="text/css">
    <link rel="stylesheet" href="style.css">
    <style>
        body {
            background-color: white;
        }
        
        p {
            font-size: 20px;
            color: mediumblue;
        }
    </style>
    <link rel="stylesheet" href="styles.css">
    <title>CSS Dasar</title>
    <style>
        body {
            font-family: open-sans, sans-serif;
        }
        
        header {
            min-height: 80px;
            border-bottom: 1px solid #77CCFF;
        }
        
        h1 {
            font-size: 24px;
            color: #3333CC;
            text-align: center;
            padding: 20px;
        }
        
        h1 i {
            color: #6d6a6b;
        }
    </style>
</head>

<body>
    <header>
        <h1>CSS internal dan <i> Inline CSS</i></h1>
    </header>
    <nav>
        <a href="lab2_css_dasar.html">CSS Dasar</a>
        <a href="lab2_css_eksternal.html">CSS Eksternal</a>
        <a href="lab1_tag_dasar.html">HTML Dasar</a>
    </nav>
    <!-- Inline CSS -->
    <div id="intro">
        <h1>Hello World</h1>
        <p style="text-align: center; color: #ccd8e4;">Kami sedang belajar HTML dan CSS dasar, pada mata kuliah <b>Pemrograman
Web</b> di <i>Universitas Pelita Bangsa</i>. Pelajaran pertama yang kami dapat adalah membuat tampilan web sederhana dalam rangka mengenal tag-tag dasar HTML dan CSS.</p>
        <!-- Inline CSS -->
        <a class="button btn-primary" href="#intro">Informasi selengkapnya</a>
    </div>
</body>

</html>
```

#  contoh kode css
```
nav {
    background: #20a759;
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


/* ID Selector */

#intro {
    background: #418fb1;
    border: 1px solid #099249;
    min-height: 100px;
    padding: 10px;
}

#intro h1 {
    color: #fff;
    text-align: left;
    border: 0;
}


/* Class Selector */

.button {
    text-decoration: none;
    padding: 15px 20px;
    background: #bebcbd;
    color: #fff;
    display: inline-block;
    margin: 10px;
}

.btn-primary {
    background: #E42A42;
}
```
