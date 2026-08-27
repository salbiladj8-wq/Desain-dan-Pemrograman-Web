Bagian CSS
/* ===== Reset & Base ===== */ = Bagian untuk mengatur tampilan dasar website.
* = Memilih semua elemen HTML.
box-sizing: border-box; = Mengatur ukuran elemen agar lebih mudah dikontrol.
margin: 0; = Menghilangkan jarak luar bawaan.
padding: 0; = Menghilangkan jarak dalam bawaan.

body = Mengatur tampilan seluruh halaman.
font-family = Menentukan jenis tulisan.
color = Menentukan warna teks.
background-color = Menentukan warna latar belakang.
line-height = Mengatur jarak antarbaris teks.

a = Mengatur tampilan link.
color = Memberi warna pada link.
text-decoration: none; = Menghilangkan garis bawah link.
a:hover = Mengatur tampilan link saat mouse diarahkan.

header = Mengatur tampilan bagian header.
background-color = Memberi warna pink pada header.
color = Mengatur warna teks menjadi putih.
padding = Memberi jarak di dalam header.
display: flex; = Mengatur isi header menggunakan Flexbox.
align-items: center; = Membuat isi header sejajar di tengah.
justify-content: space-between; = Memberi jarak antara judul dan menu.
flex-wrap: wrap; = Membuat isi header turun jika ruang tidak cukup.
border-radius = Membuat sudut bawah header melengkung.
box-shadow = Memberi efek bayangan pada header.

header h1 = Mengatur judul di dalam header.
font-size = Mengatur ukuran tulisan judul.

header nav ul = Mengatur daftar menu.
list-style: none; = Menghilangkan tanda bullet pada daftar.
display: flex; = Membuat menu berjajar.
gap = Mengatur jarak antar menu.

header nav a = Mengatur link yang ada di menu.
font-weight: 500; = Membuat tulisan menu sedikit lebih tebal.
header nav a:hover = Mengatur menu saat mouse diarahkan.
text-decoration: none; = Menghilangkan garis bawah saat hover.

main = Mengatur bagian utama halaman.
max-width: 1000px; = Membatasi lebar halaman maksimal 1000px.
margin: 2rem auto; = Memberi jarak dan membuat halaman berada di tengah.
padding = Memberi jarak di dalam bagian utama.

section = Mengatur kotak bagian konten.
background-color: #fff; = Memberi warna putih pada section.
border-radius: 20px; = Membuat sudut kotak melengkung.
padding = Memberi jarak di dalam kotak.
margin-bottom = Memberi jarak antarsection.
box-shadow = Memberi bayangan lembut.
border-left = Memberi garis warna peach di sebelah kiri.

section h2 = Mengatur judul pada section.
color = Memberi warna pink pada judul.

main section:nth-of-type(2) = Mengatur section kedua pada main.
display: grid; = Mengatur isi menggunakan CSS Grid.
grid-template-columns = Membuat 3 kolom dengan ukuran sama.
gap = Mengatur jarak antar kolom.
border-left: none; = Menghilangkan garis kiri pada section statistik.

main section:nth-of-type(2) article = Mengatur kotak statistik.
background-color = Memberi warna peach pada kotak.
border-radius = Membuat sudut kotak melengkung.
padding = Memberi jarak di dalam kotak.
text-align: center; = Membuat teks berada di tengah.
box-shadow = Memberi bayangan pada kartu.
transition = Membuat perubahan tampilan lebih halus.

main section:nth-of-type(2) article.hover = Mengatur efek hover pada kartu.
transform: translateY(-5px); = Membuat kartu bergerak sedikit ke atas.
box-shadow = Membuat bayangan lebih terlihat saat hover.

main section:nth-of-type(2) article h3 = Mengatur judul pada kartu statistik.
font-size = Mengatur ukuran tulisan.
color = Memberi warna pink pada tulisan.
margin-bottom = Memberi jarak di bawah judul.

main section:nth-of-type(2) article p = Mengatur angka statistik.
font-size = Membuat angka lebih besar.
font-weight: 700; = Membuat angka lebih tebal.
color = Memberi warna pink pada angka.

table = Mengatur tampilan tabel.
width: 100%; = Membuat tabel memenuhi lebar yang tersedia.
border-collapse: separate; = Membuat jarak antarborder tabel tetap terpisah.
border-spacing: 0; = Menghilangkan jarak antar sel.
overflow: hidden; = Menyembunyikan bagian yang keluar dari batas tabel.
border-radius: 15px; = Membuat sudut tabel melengkung.

th, td = Mengatur semua judul dan isi tabel.
text-align: left; = Membuat teks rata kiri.
padding = Memberi jarak di dalam sel.
border-bottom = Memberi garis di bawah setiap baris.

thead = Mengatur bagian kepala tabel.
background-color = Memberi warna pink pada kepala tabel.
color = Membuat tulisan menjadi putih.

tbody tr:nth-child(even) = Mengatur baris tabel genap.
background-color = Memberi warna berbeda pada baris genap.

tbody tr:hover = Mengatur baris saat mouse diarahkan.
background-color = Memberi warna peach saat hover.

td button = Mengatur tombol di dalam tabel.
padding = Memberi jarak di dalam tombol.
margin-right = Memberi jarak antar tombol.
border: none; = Menghilangkan border tombol.
border-radius = Membuat tombol berbentuk bulat/kapsul.
cursor: pointer; = Mengubah cursor menjadi tangan.
font-size = Mengatur ukuran tulisan tombol.
transition = Membuat perubahan tombol lebih halus.

td button:first-of-type = Mengatur tombol pertama, yaitu Edit.
background-color = Memberi warna peach pada tombol Edit.
color = Membuat tulisan tombol menjadi putih.

td button:last-of-type = Mengatur tombol terakhir, yaitu Hapus.
background-color = Memberi warna pink pada tombol Hapus.
color = Membuat tulisan tombol menjadi putih.

td button:hover = Mengatur tombol saat mouse diarahkan.
transform: scale(1.05); = Membuat tombol sedikit membesar.
opacity: 0.85; = Membuat tombol sedikit transparan.

form p = Mengatur setiap bagian dalam form.
margin-bottom = Memberi jarak antarinput.

form label = Mengatur tulisan label form.
display: block; = Membuat label berada dalam satu baris sendiri.
margin-bottom = Memberi jarak antara label dan input.
font-weight: 600; = Membuat label lebih tebal.
color = Memberi warna pada label.

form input, form select = Mengatur kolom input dan pilihan.
width: 100%; = Membuat input memenuhi lebar yang tersedia.
max-width: 400px; = Membatasi lebar maksimal input.
padding = Memberi jarak di dalam input.
border = Memberi garis pada input.
border-radius = Membuat sudut input melengkung.
font-size = Mengatur ukuran tulisan.
background-color = Memberi warna latar input.
outline: none; = Menghilangkan garis bawaan saat input diklik.

form input:focus, form select:focus = Mengatur input saat sedang dipilih.
border-color = Mengubah warna border menjadi pink.
box-shadow = Memberi efek cahaya lembut di sekitar input.

form button[type="submit"] = Mengatur tombol Simpan.
background-color = Memberi warna pink pada tombol.
color = Membuat tulisan menjadi putih.
border: none; = Menghilangkan border tombol.
padding = Memberi jarak di dalam tombol.
border-radius = Membuat tombol melengkung.
font-size = Mengatur ukuran tulisan.
cursor: pointer; = Mengubah cursor menjadi tangan.
transition = Membuat perubahan tombol lebih halus.

form button[type="submit"]:hover = Mengatur tombol Simpan saat mouse diarahkan.
background-color = Mengubah warna tombol.
transform: translateY(-2px); = Membuat tombol sedikit naik.

footer = Mengatur bagian bawah website.
text-align: center; = Membuat tulisan berada di tengah.
padding = Memberi jarak di dalam footer.
color = Mengatur warna tulisan footer.
font-size = Mengatur ukuran tulisan footer.