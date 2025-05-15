---
layout: post
title: "JAVASCRIPT"
date: 2025-04-25
---


<html lang="id">
<head>
  <meta charset="UTF-8">
  <title>Laporan JavaScript</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 40px;
      line-height: 1.6;
      color: #2c3e50;
    }
    h1, h2, h3 {
      color: #34495e;
    }
    code {
      background-color: #f4f4f4;
      padding: 2px 4px;
      border-radius: 4px;
      font-family: Consolas, monospace;
    }
    pre {
      background-color: #f4f4f4;
      padding: 10px;
      border-left: 4px solid #3498db;
      overflow-x: auto;
    }
    ul {
      margin-left: 20px;
    }
    img {
      margin-top: 20px;
      border: 1px solid #ddd;
      border-radius: 4px;
    }
  </style>
</head>
<body>

  <h1>Laporan Tentang JavaScript</h1>

  <h2>1. Pendahuluan</h2>
  <p>
    JavaScript adalah salah satu bahasa pemrograman paling populer dan banyak digunakan di dunia, 
    terutama dalam pengembangan web. Bahasa ini pertama kali dikembangkan oleh <strong>Brendan Eich</strong> pada tahun 1995. 
    Kini, JavaScript menjadi bagian tak terpisahkan dari pengembangan aplikasi web modern bersama HTML dan CSS.
  </p>

  <h2>2. Pengertian JavaScript</h2>
  <p>
    JavaScript adalah bahasa pemrograman tingkat tinggi, bersifat dinamis, dan berorientasi objek. 
    Awalnya dijalankan di sisi klien (client-side), namun sekarang juga dapat berjalan di sisi server 
    menggunakan lingkungan seperti <strong>Node.js</strong>.
  </p>

  <h2>3. Fungsi dan Kegunaan</h2>
  <p>JavaScript dapat digunakan untuk:</p>
  <ul>
    <li>Membuat halaman web menjadi interaktif (misalnya animasi, validasi form, slideshow, dll).</li>
    <li>Mengontrol elemen HTML dan CSS secara dinamis.</li>
    <li>Membangun aplikasi web modern (Single Page Applications) menggunakan framework seperti React, Vue, dan Angular.</li>
    <li>Membangun backend (server-side) menggunakan Node.js.</li>
    <li>Mengembangkan aplikasi mobile dan desktop lintas platform.</li>
  </ul>

  <h2>4. Fitur Utama</h2>
  <ul>
    <li><strong>Interaktif:</strong> Memberikan pengalaman pengguna yang dinamis.</li>
    <li><strong>DOM Manipulation:</strong> Dapat memodifikasi dokumen HTML/CSS secara langsung.</li>
    <li><strong>Asynchronous Programming:</strong> Mendukung AJAX, Fetch API, dan Promise.</li>
    <li><strong>Event-Driven:</strong> Merespon interaksi pengguna seperti klik, input, dll.</li>
    <li><strong>Cross-Platform:</strong> Dapat dijalankan di berbagai perangkat dan browser.</li>
  </ul>

  <h2>5. Contoh Kode Sederhana</h2>
  <p>Contoh JavaScript untuk menampilkan alert saat tombol diklik:</p>

  <pre><code class="language-js">
// HTML
&lt;button id="btn"&gt;Klik Saya&lt;/button&gt;

// JavaScript
document.getElementById("btn").addEventListener("click", function() {
  alert("Tombol diklik!");
});
  </code></pre>

  <h2>6. Keunggulan dan Kekurangan</h2>

  <h3>Keunggulan:</h3>
  <ul>
    <li>Didukung oleh semua browser modern.</li>
    <li>Komunitas besar dan banyak dokumentasi.</li>
    <li>Ekosistem luas (tersedia banyak library dan framework).</li>
  </ul>

  <h3>Kekurangan:</h3>
  <ul>
    <li>Tidak cocok untuk aplikasi dengan komputasi berat.</li>
    <li>Keamanan sangat tergantung pada implementasi kode.</li>
    <li>Sintaks fleksibel kadang membingungkan bagi pemula.</li>
  </ul>

  <h2>7. Kesimpulan</h2>
  <p>
    JavaScript merupakan komponen penting dalam pengembangan web modern. 
    Dengan kemampuannya yang luas dan dukungan komunitas yang besar, 
    JavaScript tidak hanya digunakan di sisi klien, tetapi juga berkembang menjadi 
    bahasa serbaguna untuk server-side dan aplikasi lintas platform.
  </p>

  <img src="/assets/images/javascritp.png" alt="Ilustrasi JavaScript" style="width: 300px; height: auto;">

</body>
</html>
