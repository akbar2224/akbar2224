---
layout: post
title: "HTML LINK DAN LISTS"
date: 2025-02-21
---

<html lang="id">
<head>
  <meta charset="UTF-8">
  <title>Laporan HTML Link dan Lists</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 40px;
      line-height: 1.6;
    }
    h1, h2, h3, h4 {
      color: #2c3e50;
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
  </style>
</head>
<body>

  <h1>LAPORAN PRAKTIKUM </h1>
  <h2> HTML Link dan Lists</h2>

  <h3>I. Tujuan</h3>
  <ul>
    <li>Memahami cara membuat hyperlink (tautan) dalam HTML.</li>
    <li>Mempelajari pembuatan list (daftar) berurutan dan tidak berurutan.</li>
    <li>Mengimplementasikan penggunaan tag <code>&lt;a&gt;</code>, <code>&lt;ul&gt;</code>, <code>&lt;ol&gt;</code>, dan <code>&lt;li&gt;</code>.</li>
  </ul>

  <h3>II. Teori Dasar</h3>
  <h4>1. HTML Link</h4>
  <p>Link atau hyperlink digunakan untuk menghubungkan satu halaman ke halaman lain atau ke bagian tertentu dalam halaman yang sama. Tag yang digunakan adalah <code>&lt;a&gt;</code>.</p>
  <pre><code>&lt;a href="https://www.example.com"&gt;Kunjungi Website&lt;/a&gt;</code></pre>

  <h4>2. HTML Lists</h4>
  <p>HTML menyediakan dua jenis list utama:</p>
  <ul>
    <li><strong>Ordered List (<code>&lt;ol&gt;</code>)</strong>: daftar yang memiliki urutan (1, 2, 3...).</li>
    <li><strong>Unordered List (<code>&lt;ul&gt;</code>)</strong>: daftar tanpa urutan (bullet points).</li>
  </ul>

  <p><strong>Contoh Ordered List:</strong></p>
  <pre><code>&lt;ol&gt;
  &lt;li&gt;HTML&lt;/li&gt;
  &lt;li&gt;CSS&lt;/li&gt;
  &lt;li&gt;JavaScript&lt;/li&gt;
&lt;/ol&gt;</code></pre>

  <p><strong>Contoh Unordered List:</strong></p>
  <pre><code>&lt;ul&gt;
  &lt;li&gt;HTML&lt;/li&gt;
  &lt;li&gt;CSS&lt;/li&gt;
  &lt;li&gt;JavaScript&lt;/li&gt;
&lt;/ul&gt;</code></pre>

  <h3>III. Alat dan Bahan</h3>
  <ul>
    <li>Teks editor (Notepad, VS Code, Sublime Text)</li>
    <li>Browser web (Chrome, Firefox, dll)</li>
  </ul>

  <h3>IV. Langkah-Langkah Praktikum</h3>
  <ol>
    <li>Buka teks editor dan buat file HTML baru (misalnya: <em>link_lists.html</em>).</li>
    <li>Tambahkan struktur dasar HTML.</li>
    <li>Tambahkan kode untuk membuat hyperlink.</li>
    <li>Tambahkan kode untuk membuat ordered list dan unordered list.</li>
    <li>Simpan file dan buka di browser untuk melihat hasilnya.</li>
  </ol>

  <p><strong>Contoh kode lengkap:</strong></p>
  <pre><code>&lt;!DOCTYPE html&gt;
&lt;html&gt;
&lt;head&gt;
  &lt;title&gt;Contoh Link dan Lists&lt;/title&gt;
&lt;/head&gt;
&lt;body&gt;

  &lt;h1&gt;Contoh Link&lt;/h1&gt;
  &lt;p&gt;Klik di sini untuk membuka Google: &lt;a href="https://www.google.com"&gt;Google&lt;/a&gt;&lt;/p&gt;

  &lt;h2&gt;Ordered List&lt;/h2&gt;
  &lt;ol&gt;
    &lt;li&gt;Bangun Pagi&lt;/li&gt;
    &lt;li&gt;Olahraga&lt;/li&gt;
    &lt;li&gt;Sarapan&lt;/li&gt;
  &lt;/ol&gt;

  &lt;h2&gt;Unordered List&lt;/h2&gt;
  &lt;ul&gt;
    &lt;li&gt;Apel&lt;/li&gt;
    &lt;li&gt;Pisang&lt;/li&gt;
    &lt;li&gt;Jeruk&lt;/li&gt;
  &lt;/ul&gt;

&lt;/body&gt;
&lt;/html&gt;
</code></pre>

  <h3>V. Hasil Praktikum</h3>
  <p>File HTML berhasil dibuat dengan menampilkan satu hyperlink, satu ordered list, dan satu unordered list. Link dapat diklik dan mengarahkan ke halaman eksternal.</p>

  <h3>VI. Kesimpulan</h3>
  <p>Dengan menggunakan tag HTML seperti <code>&lt;a&gt;</code>, <code>&lt;ul&gt;</code>, <code>&lt;ol&gt;</code>, dan <code>&lt;li&gt;</code>, kita dapat membuat tautan antar halaman dan daftar informasi dengan format terstruktur. Fitur ini sangat penting dalam membangun navigasi dan penyajian konten pada website.</p>


</body>
</html>

<img src="/assets/images/html.png" style="width: 300px; height: auto;">

