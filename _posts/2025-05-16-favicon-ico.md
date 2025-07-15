
<html lang="id">
<head>
    <meta charset="UTF-8">
    <title>Laporan Favicon</title>
    <link rel="icon" type="image/x-icon" href="favicon.ico">
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #eef2f5;
            color: #333;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #003366;
            color: white;
            padding: 25px;
            text-align: center;
        }
        main {
            max-width: 900px;
            margin: 30px auto;
            padding: 30px;
            background-color: white;
            border-radius: 12px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }
        h1, h2 {
            color: #003366;
        }
        p {
            text-align: justify;
            line-height: 1.7;
        }
        ul {
            padding-left: 25px;
        }
        li {
            margin-bottom: 10px;
        }
        code {
            background-color: #f2f2f2;
            padding: 4px 8px;
            border-radius: 4px;
            display: inline-block;
            margin: 5px 0;
        }
        footer {
            text-align: center;
            font-size: 14px;
            color: #666;
            margin: 40px 0 20px;
        }
        a {
            color: #005ea6;
            text-decoration: none;
        }
        a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>

<header>
    <h1>Laporan Praktikum Desain Web</h1>
    <h2>Topik: Penerapan dan Fungsi Favicon</h2>
</header>

<main>

    <h2>1. Pendahuluan</h2>
    <p>
        Dalam pengembangan antarmuka pengguna website, salah satu elemen kecil namun penting adalah <strong>favicon</strong>. 
        Pada praktikum ini, kita belajar bagaimana cara menambahkan favicon agar tampilan website menjadi lebih profesional 
        dan mudah dikenali oleh pengguna.
    </p>

    <h2>2. Apa Itu Favicon?</h2>
    <p>
        Favicon adalah singkatan dari <strong>favorite icon</strong>, yaitu ikon kecil berukuran 16x16 piksel atau 32x32 piksel 
        yang muncul di tab browser, bookmark, atau shortcut. Favicon berfungsi sebagai representasi visual dari sebuah situs web. 
        Format umum yang digunakan adalah <code>.ico</code>, <code>.png</code>, dan <code>.svg</code>.
    </p>

    <h2>3. Fungsi dan Manfaat Favicon</h2>
    <ul>
        <?php
        $fungsi = [
            "Menampilkan ikon situs di tab browser.",
            "Memudahkan pengguna mengenali dan membedakan situs saat membuka banyak tab.",
            "Ditampilkan saat situs disimpan sebagai bookmark atau shortcut.",
            "Meningkatkan kesan profesional dan branding website.",
            "Ditampilkan saat disimpan di layar utama perangkat mobile."
        ];
        foreach ($fungsi as $item) {
            echo "<li>✅ $item</li>";
        }
        ?>
    </ul>

    <h2>4. Cara Menambahkan Favicon ke Website</h2>
    <p>Berikut adalah langkah sederhana untuk menambahkan favicon:</p>
    <ol>
        <li>Siapkan file gambar favicon (contohnya <code>favicon.ico</code>) dan simpan di folder utama website.</li>
        <li>Tambahkan tag berikut di bagian <code>&lt;head&gt;</code> pada HTML:</li>
    </ol>
    <code>&lt;link rel="icon" type="image/x-icon" href="favicon.ico"&gt;</code>
    <p>Untuk dukungan lebih luas, bisa ditambahkan:</p>
    <code>&lt;link rel="icon" href="favicon.png" type="image/png"&gt;<br>
&lt;link rel="apple-touch-icon" href="apple-touch-icon.png"&gt;<br>
&lt;link rel="shortcut icon" href="favicon.ico" type="image/x-icon"&gt;</code>

    <h2>5. Kesimpulan</h2>
    <p>
        Favicon meskipun kecil, memiliki pengaruh besar terhadap identitas visual website. Dengan menambahkan favicon, situs menjadi 
        lebih mudah dikenali, terlihat profesional, dan memberikan pengalaman pengguna yang lebih baik. Praktikum ini menunjukkan bahwa 
        detail kecil dalam desain web dapat memberikan dampak yang signifikan.
    </p>

    <h2>6. Referensi</h2>
    <ul>
        <li><a href="https://developer.mozilla.org/en-US/docs/Glossary/Favicon" target="_blank">MDN Web Docs - Favicon</a></li>
        <li><a href="https://www.w3schools.com/html/html_favicon.asp" target="_blank">W3Schools - Favicon</a></li>
    </ul>

</main>

<footer>
    &copy; <?php echo date("Y"); ?> Laporan Desain Web - Praktikum Favicon
</footer>

</body>
</html>
