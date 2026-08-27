Bagian Halaman Beranda-index.html
<!DOCTYPE html> = Menandakan bahwa file menggunakan HTML5.
<html lang="id"> = Awal dokumen HTML dengan bahasa Indonesia.
<head> = Berisi informasi tentang halaman.
<meta charset="UTF-8"> = Mengatur karakter agar tulisan tampil dengan benar.
<title>SIMPUS-Mini | Beranda</title> = Menentukan judul pada tab browser.
</head> = Menutup bagian head.
<body> = Berisi semua isi yang tampil di halaman.
<header> = Membuat bagian kepala website.
<h1>SIMPUS-Mini</h1> = Menampilkan judul utama website.
<nav> = Membuat bagian navigasi atau menu.
<ul> = Membuat daftar menu.
<li> = Membuat item dalam daftar.
<a href="index.html">Beranda</a> = Membuat link menuju halaman Beranda.
<a href="buku/list.html">Daftar Buku</a> = Membuat link menuju halaman Daftar Buku.
<a href="buku/tambah.html">Tambah Buku</a> = Membuat link menuju halaman Tambah Buku.
<a href="anggota/list.html">Daftar Anggota</a> = Membuat link menuju halaman Daftar Anggota.
</ul> = Menutup daftar menu.
</nav> = Menutup bagian navigasi.
</header> = Menutup bagian header.
<main> = Membuat bagian utama halaman.
<section> = Membuat bagian atau kelompok konten.
<h2>Selamat Datang di Sistem Perpustakaan Mini</h2> = Menampilkan judul bagian selamat datang.
<p>Aplikasi sederhana untuk mengelola data buku dan anggota perpustakaan.</p> = Menampilkan penjelasan singkat tentang aplikasi.
</section> = Menutup bagian selamat datang.
<section> = Membuat bagian untuk ringkasan data.
<h2>Ringkasan</h2> = Menampilkan judul bagian ringkasan.
<article> = Membuat satu bagian informasi.
<h3>Total Buku</h3> = Menampilkan keterangan jumlah buku.
<p>12</p> = Menampilkan jumlah buku, yaitu 12.
</article> = Menutup informasi total buku.
<article> = Membuat bagian informasi berikutnya.
<h3>Total Anggota</h3> = Menampilkan keterangan jumlah anggota.
<p>8</p> = Menampilkan jumlah anggota, yaitu 8.
</article> = Menutup informasi total anggota.
<article> = Membuat bagian informasi berikutnya.
<h3>Sedang Dipinjam</h3> = Menampilkan keterangan buku yang sedang dipinjam.
<p>3</p> = Menampilkan jumlah buku yang sedang dipinjam, yaitu 3.
</article> = Menutup informasi buku yang dipinjam.
</section> = Menutup bagian ringkasan.</main> = Menutup bagian utama halaman
<footer> = Membuat bagian paling bawah website.
<p>&copy; 2026 SIMPUS-Mini &mdash; Jobsheet 1</p> = Menampilkan informasi copyright dan nama jobsheet.
&copy; = Menampilkan simbol ©.
&mdash; = Menampilkan tanda —.
</footer> = Menutup bagian footer.
</body> = Menutup seluruh isi halaman.
</html> = Menutup dokumen HTML.

Bagian Anggota
A. list.html
<!DOCTYPE html> = Menandakan bahwa file menggunakan HTML5.
<html lang="id"> = Awal dokumen HTML dengan bahasa Indonesia.
<head> = Berisi informasi tentang halaman.
<meta charset="UTF-8"> = Mengatur karakter agar tulisan tampil dengan benar.
<tittle>SIMPUS-Mini | Daftar Anggota</tittle> = Menentukan judul halaman pada tab browser.
Catatan: seharusnya <title>, bukan <tittle>, cuman keburu sudah dicommit tidak menyadari typo.
</head> = Menutup bagian head.
<body> = Berisi semua isi yang tampil di halaman.
<header> = Membuat bagian kepala website.
<h1>SIMPUS-Mini</h1> = Menampilkan nama utama website.
<nav> = Membuat bagian navigasi atau menu.
<ul> = Membuat daftar menu.
<li> = Membuat satu item dalam daftar.
<a href="../index.html">Beranda</a> = Link menuju halaman Beranda.
<a href="../buku/list.html">Daftar Buku</a> = Link menuju halaman Daftar Buku.
<a href="list.html">Daftar Anggota</a> = Link menuju halaman Daftar Anggota.
<a href="tambah.html">Tambah Anggota</a> = Link menuju halaman Tambah Anggota.
</ul> = Menutup daftar menu.
</nav> = Menutup navigasi.
</header> = Menutup header.
<main> = Membuat bagian utama halaman.
<section> = Membuat bagian atau kelompok konten.
<h2>Daftar Anggota</h2> = Menampilkan judul halaman.
<table> = Membuat tabel untuk menampilkan data anggota.
<thead> = Membuat bagian kepala tabel.
<tr> = Membuat satu baris tabel.
<th>No. Anggota</th> = Membuat judul kolom nomor anggota.
<th>Nama</th> = Membuat judul kolom nama.
<th>Alamat</th> = Membuat judul kolom alamat.
<th>No. HP</th> = Membuat judul kolom nomor HP.
<th>Aksi</th> = Membuat judul kolom untuk tombol tindakan.
</tr> = Menutup baris tabel.
</thead> = Menutup kepala tabel.
<tbody> = Berisi data anggota dalam tabel.
<tr> = Membuat satu baris data anggota.
<td>A001</td> = Menampilkan nomor anggota A001.
<td>Siti Aminah</td> = Menampilkan nama anggota.
<td>Malang</td> = Menampilkan alamat anggota.
<td>0812xxxx</td> = Menampilkan nomor HP anggota.
<button type="button">Edit</button> = Membuat tombol Edit.
<button type="button">Hapus</button> = Membuat tombol Hapus.
</tr> = Menutup satu baris data.
<tr> = Membuat baris data anggota berikutnya.
<td>A002</td> = Menampilkan nomor anggota A002.
<td>Budi Sentoso</td> = Menampilkan nama anggota.
<td>0813xxxx</td> = Menampilkan data nomor HP.
</tr> = Menutup baris data.
A003 sampai A007 = Menampilkan data anggota lainnya dengan struktur yang sama.
</tbody> = Menutup isi tabel.
</table> = Menutup tabel.
</section> = Menutup bagian konten.
</main> = Menutup bagian utama halaman.
<footer> = Membuat bagian bawah website.
<p>&copy; 2026 SIMPUS-Mini &mdash; Jobsheet</p> = Menampilkan copyright dan nama jobsheet.
&copy; = Menampilkan simbol ©.
&mdash; = Menampilkan tanda —.
</footer> = Menutup footer.
</body> = Menutup isi halaman.
</html> = Menutup dokumen HTML.

B. tambah.html
<!DOCTYPE html> = Menandakan file menggunakan HTML5.
<html lang="id"> = Awal dokumen HTML dengan bahasa Indonesia.
<head> = Berisi informasi tentang halaman.
<meta charset="UTF-8"> = Mengatur karakter agar tulisan tampil dengan benar.
<title>SIMPUS-Mini | Daftar Anggota</title> = Menentukan judul halaman pada tab browser.
</head> = Menutup bagian head.
<body> = Berisi semua isi yang tampil di halaman.
<header> = Membuat bagian kepala website.
<h1>SIMPUS-Mini</h1> = Menampilkan nama utama website.
<nav> = Membuat bagian menu navigasi.
<ul> = Membuat daftar menu.
<li> = Membuat satu item dalam daftar.
<a href="../index.html">Beranda</a> = Link menuju halaman Beranda.
<a href="../buku/list.html">Daftar Buku</a> = Link menuju halaman Daftar Buku.
<a href="list.html">Daftar Anggota</a> = Link menuju halaman Daftar Anggota.
<a href="tambah.html">Tambah Anggota</a> = Link menuju halaman Tambah Anggota.
</ul> = Menutup daftar menu.
</nav> = Menutup navigasi.
</header> = Menutup header.
<main> = Membuat bagian utama halaman.
<section> = Membuat bagian atau kelompok konten.
<h2>Daftar Anggota</h2> = Menampilkan judul halaman.
<table> = Membuat tabel untuk menampilkan data anggota.
<thead> = Membuat bagian kepala tabel.
<tr> = Membuat satu baris tabel.
<th>No. Anggota</th> = Membuat judul kolom nomor anggota.
<th>Nama</th> = Membuat judul kolom nama.
<th>Alamat</th> = Membuat judul kolom alamat.
<th>No. HP</th> = Membuat judul kolom nomor HP.
<th>Aksi</th> = Membuat judul kolom untuk tombol tindakan.
</tr> = Menutup baris tabel.
</thead> = Menutup kepala tabel.
<tbody> = Berisi data-data anggota.
<td>A001</td> = Menampilkan nomor anggota.
<td>Siti Aminah</td> = Menampilkan nama anggota.
<td>Malang</td> = Menampilkan alamat anggota.
<td>0812xxxx</td> = Menampilkan nomor HP anggota.
<button type="button">Edit</button> = Membuat tombol Edit.
<button type="button">Hapus</button> = Membuat tombol Hapus.
<tr> = Membuat baris anggota berikutnya.
A002 sampai A007 = Menampilkan data anggota lainnya dengan struktur yang sama.
</tbody> = Menutup isi tabel.
</table> = Menutup tabel.
</section> = Menutup bagian konten.
</main> = Menutup bagian utama.
<footer> = Membuat bagian paling bawah website.
<p>&copy; 2026 SIMPUS-Mini &mdash; Jobsheet 1</p> = Menampilkan copyright dan nama jobsheet.
&copy; = Menampilkan simbol ©.
&mdash; = Menampilkan tanda —.
</footer> = Menutup footer.
</body> = Menutup isi halaman.
</html> = Menutup dokumen HTML.

Bagian Buku
A. list.html
<!DOCTYPE html> = Menandakan file menggunakan HTML5.
<html kang="id"> = Awal dokumen HTML. Catatan: seharusnya menggunakan lang="id", bukan kang="id", cuman keburu dicommit, tidak menyadari ada typo.
<head> = Berisi informasi tentang halaman.
<meta charset="UTF-8"> = Mengatur karakter agar tulisan tampil dengan benar.
<title>SIMPUS-Mini | Daftar Buku</title> = Menentukan judul halaman pada tab browser.
</head> = Menutup bagian head.
<body> = Berisi semua isi yang tampil di halaman.
<header> = Membuat bagian kepala website.
<h1>SIMPUS-Mini</h1> = Menampilkan nama utama website.
<nav> = Membuat bagian menu navigasi.
<ul> = Membuat daftar menu.
<li> = Membuat satu item dalam daftar.
<a href="../index.html">Beranda</a> = Link menuju halaman Beranda.
<a href="../buku/list.html">Daftar Buku</a> = Link menuju halaman Daftar Buku.
<a href="tambah.html">Tambah Buku</a> = Link menuju halaman Tambah Buku.
<a href="../anggota/list.html">Daftar Anggota</a> = Link menuju halaman Daftar Anggota.
</ul> = Menutup daftar menu.
</nav> = Menutup navigasi.
</header> = Menutup header.
<main> = Membuat bagian utama halaman.
<section> = Membuat bagian atau kelompok konten.
<h2>Daftar Buku</h2> = Menampilkan judul halaman.
<table> = Membuat tabel untuk menampilkan data buku.
<thead> = Membuat bagian kepala tabel.
<tr> = Membuat satu baris tabel.
<th>Judul</th> = Membuat kolom judul buku.
<th>Pengarang</th> = Membuat kolom nama pengarang.
<th>Tahun</th> = Membuat kolom tahun terbit.
<th>Stok</th> = Membuat kolom jumlah stok buku.
<th>Aksi</th> = Membuat kolom untuk tombol tindakan.
</tr> = Menutup baris kepala tabel.
</thead> = Menutup kepala tabel.
<tbody> = Berisi data-data buku.
<td>Laskar Pelangi</td> = Menampilkan judul buku.
<td>Andrea Hirata</td> = Menampilkan nama pengarang.
<td>2005</td> = Menampilkan tahun terbit buku.
<td>4</td> = Menampilkan jumlah stok buku.
<button type="button">Edit</button> = Membuat tombol Edit.
<button type="button">Hapus</button> = Membuat tombol Hapus.
<tr> = Membuat baris data buku berikutnya.
Bumi Manusia sampai Garis Waktu = Menampilkan data buku lainnya dengan struktur yang sama.
</tbody> = Menutup isi tabel.
</table> = Menutup tabel.
</section> = Menutup bagian konten.
</main> = Menutup bagian utama.
<footer> = Membuat bagian bawah website.
<p>&copy; 2026 SIMPUS-Mini &mdash; Jobsheet 1</p> = Menampilkan copyright dan nama jobsheet.
&copy; = Menampilkan simbol ©.
&mdash; = Menampilkan tanda —.
</footer> = Menutup footer.
</body> = Menutup isi halaman.
</html> = Menutup dokumen HTML.

B. tambah.html
<!DOCTYPE html> = Menandakan file menggunakan HTML5.
<html lang="id"> = Awal dokumen HTML dengan bahasa Indonesia.
<head> = Berisi informasi tentang halaman.
<meta charset="UTF-8"> = Mengatur karakter agar tulisan tampil dengan benar.
<title>SIMPUS-Mini | Tambah Buku</title> = Menentukan judul halaman pada tab browser.
</head> = Menutup bagian head.
<body> = Berisi semua isi yang tampil di halaman.
<header> = Membuat bagian kepala website.
<h1>SIMPUS-Mini</h1> = Menampilkan nama utama website.
<nav> = Membuat bagian menu navigasi.
<ul> = Membuat daftar menu.
<li> = Membuat satu item dalam daftar.
<a href="../index.html">Beranda</a> = Link menuju halaman Beranda.
<a href="list.html">Daftar Buku</a> = Link menuju halaman Daftar Buku.
<a href="tambah.html">Tambah Buku</a> = Link menuju halaman Tambah Buku.
<a href="../anggota/list.html">Daftar Anggota</a> = Link menuju halaman Daftar Anggota.
</ul> = Menutup daftar menu.
</nav> = Menutup navigasi.
</header> = Menutup header.
<main> = Membuat bagian utama halaman.
<section> = Membuat bagian atau kelompok konten.
<h2>Tambah Buku</h2> = Menampilkan judul halaman.
<form> = Membuat formulir untuk memasukkan data.
<p> = Membuat bagian untuk setiap input.
<label for="judul">Judul</label> = Memberi nama pada kolom input judul.
<br> = Membuat pindah baris.
<input type="text" id="judul" name="judul" required> = Membuat kolom untuk memasukkan judul buku dan wajib diisi.
<label for="pengarang">Pengarang</label> = Memberi nama pada kolom pengarang.
<input type="text" id="pengarang" name="pengarang" required> = Membuat kolom untuk memasukkan nama pengarang dan wajib diisi.
<label for="tahun">Tahun Terbit</label> = Memberi nama pada kolom tahun terbit.
<input type="number" id="tahun" name="tahun" min="1900" max="2026" required> = Membuat kolom angka untuk tahun terbit dengan batas 1900–2026.
<label for="isbn">ISBN</label> = Memberi nama pada kolom ISBN.
<input type="text" id="isbn" name="isbn"> = Membuat kolom untuk memasukkan ISBN.
<label for="stok">Stok</label> = Memberi nama pada kolom jumlah stok.
<input type="number" id="stok" name="stok" min="0" required> = Membuat kolom angka untuk stok dan tidak boleh kurang dari 0.
<label for="kategori">Kategori</label> = Memberi nama pada pilihan kategori buku.
<select id="kategori" name="kategori"> = Membuat menu pilihan kategori.
<option value="fiksi">Fiksi</option> = Pilihan kategori Fiksi.
<option value="non-fiksi">Non-Fiksi</option> = Pilihan kategori Non-Fiksi.
<option value="referensi">Referensi</option> = Pilihan kategori Referensi.
</select> = Menutup menu pilihan kategori.
<button type="submit">Simpan</button> = Membuat tombol untuk mengirim atau menyimpan data.
</p> = Menutup bagian input.
</form> = Menutup formulir.
</section> = Menutup bagian konten.
</main> = Menutup bagian utama.
<footer> = Membuat bagian bawah website.
<p>&copy; 2026 SIMPUS-Mini &mdash; Jobsheet 1</p> = Menampilkan copyright dan nama jobsheet.
&copy; = Menampilkan simbol ©.
&mdash; = Menampilkan tanda —.
</footer> = Menutup footer.
</body> = Menutup isi halaman.
</html> = Menutup dokumen HTML.