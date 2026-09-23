# Praktikum 1: HTML Dasar

Nama: Febryvia Deya Nur Havidtar Murti Aqsa

NIM: 312510194

Mata Kuliah: Pemrograman Web

Kelas: I251B

## Deskripsi
Repository berisi hasil praktikum HTML Dasar, meliputi struktur dokumen,
heading, paragraf, pemformatan teks, gambar, hyperlink, list, dan komentar HTML.

## Langkah-langkah yang Dikerjakan

1. **Struktur Dasar HTML** : Membuat file `index.html` dengan struktur `<!DOCTYPE html>`, `<head>`, dan `<body>`.
2. **Membuat Paragraf** : Menambahkan dua paragraf berisi penjelasan tentang HTML.
3. **Menambahkan Judul** : Menambahkan heading `<h1>` dan `<h2>`.
4. **Memformat Teks** : Menggunakan tag `<b>`, `<i>`, `<strong>`, `<sub>`, `<sup>`.
5. **Menyisipkan Gambar** : Menambahkan gambar profil dengan tag `<img>` di folder `images/`.
6. **Mengatur Ukuran Gambar** : Mengatur atribut `width` pada gambar.
7. **Menambahkan Hyperlink** : Membuat `halaman2.html` dan menghubungkannya dengan `<nav>` dan tag `<a>`.
8. **Menambahkan List** : Membuat unordered list (`<ul>`) untuk keahlian dan ordered list (`<ol>`) untuk target belajar.
9. **Menambahkan Komentar** : Menambahkan komentar `<!-- ... -->` sebagai penanda bagian kode.
10. **Menggabungkan Semua Elemen** : Menggabungkan semua elemen di atas menjadi satu halaman Profil Mahasiswa (`index.html`).

## Screenshot

![alt text](image-01.png)
![alt text](image-02.png)
![alt text](image-03.png)
![alt text](image-04.png)

## Struktur Folder

```
Lab1Web/
├── index.html
├── halaman2.html
├── README.md
├── images/
│   └── profil.jpg
└── screenshots/
    ├── image-01.png
    ├── image-02.png
    ├── image-03.png
    └── image-04.png
```


## Jawaban Pertanyaan

1. **Fungsi `<!DOCTYPE html>`** : Mendeklarasikan bahwa dokumen menggunakan standar HTML5, ditulis di awal dokumen.
2. **Perbedaan tag, elemen, atribut** : Tag adalah penanda pembuka/penutup (`<p>`), elemen adalah gabungan tag pembuka + isi + tag penutup, atribut adalah informasi tambahan pada tag pembuka (`href`, `src`).
3. **Perbedaan `<p>` dan `<br>`** — `<p>` membuat paragraf baru dengan jarak/margin, `<br>` hanya memindahkan ke baris baru tanpa membuat paragraf baru.
4. **Fungsi atribut `href`** : Menentukan URL atau tujuan tautan pada tag `<a>`.
5. **Hyperlink internal vs eksternal** : Internal menuju file/halaman dalam website yang sama, eksternal menuju website lain.
6. **Fungsi `src` dan `alt` pada `<img>`**, `src` menentukan lokasi/path gambar, `alt` menampilkan teks alternatif jika gambar gagal dimuat.
7. **Perbedaan `<ul>` dan `<ol>`**, `<ul>` membuat daftar tanpa urutan (bullet), `<ol>` membuat daftar berurutan (bernomor).
8. **Jika path gambar salah** : Gambar tidak akan tampil, browser hanya menampilkan ikon gambar rusak dan teks `alt`.
9. **Mengapa heading harus terstruktur** : Agar dokumen mudah dibaca, terorganisir, dan baik untuk aksesibilitas serta SEO.
10. **Fungsi komentar `<!-- -->`** : Memberi catatan pada kode tanpa ditampilkan di browser, atau menonaktifkan kode sementara.
