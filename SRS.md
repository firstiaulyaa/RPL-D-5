---


---

<h1 align="center" id="software-requirements-specification">SOFTWARE REQUIREMENTS SPECIFICATION</h1>  
<p align="center"><strong>Version 1.0<br>  
22 Februari 2018</strong><br>  
</p><p align="center">  
<img src="https://lh3.googleusercontent.com/qEHYPVzo0kjd8ikhrCIF4cI_PhR8pmK5vDU14oEp9OPyVT-eA54cVp8C9iyJ8rKDfH8OR1dnT1zv=s300" alt="enter image description here" title="logo">  
</p><p align="center"><strong>Kelompok 5 D3TI2D</strong></p>  
<p align="center"><strong>Firsti Aulya K. K. (1603098)<br>  
Firmansyah (1603097) <br>  
Diyanti (1603094)<br>  
Rizky Alief Satria (1603111)</strong><br>  
</p>  
<h2 align="center"><strong>Jurusan D3 Teknik Informatika</strong></h2>  
<h2 align="center"><strong>Politeknik Negeri Indramayu </strong></h2>  
<h2 align="center"><strong>2018</strong></h2>  
<p><strong>1. PENDAHULUAN</strong>  
</p><p><strong>1.1 Tujuan</strong></p>  
<p>Dokumen ini bertujuan untuk menjelaskan secara detail mengenai aplikasi yang kami buat yang berjudul “Aplikasi Budaya dan Pariwisata Kabupaten Indramayu berbasis Android”,<br>  
pada dokumen ini akan menjelaskan seperti : Mock-up, rancangan sistem, dan lain-lain.</p>  
<p><strong>1.2 Lingkup Masalah</strong></p>  
<p>Aplikasi Budaya dan Pariwisata Indramayu adalah salah satu aplikasi berbasis android yang digunakan untuk seluruh masyarakat, khususnya masyarakat yang berada di daerah Indramayu untuk mengetahui kebudayaan yang ada di Indramayu dan event atau lomba yang akan diselenggarakan oleh Dinas Kebudayaan dan Pariwisata Kabupaten Indramayu.<br>  
Pada Proyek ini dibuat sistem berbasis android dimana pengolahan informasi dan data diakses melalui smartphone dengan sistem operasi android.</p>  
<p><strong>1.3 Definisi, Akronim, Singkatan</strong></p>  
<table>  
<thead>  
<tr>  
<th>Istilah</th>  
<th>Definisi</th>  
</tr>  
</thead>  
<tbody>  
<tr>  
<td>Android</td>  
<td>sistem operasi berbasis Linux yang dirancang untuk perangkat bergerak layar sentuh seperti telepon pintar dan komputer tablet</td>  
</tr>  
<tr>  
<td>Event</td>  
<td>sebuah rangkaian kegiatan / acara dalam rangka tujuan tertentu yang diadakan oleh pihak tertentu dalam waktu tertentu dan tempat tertentu dengan biaya tertentu</td>  
</tr>  
<tr>  
<td>Budaya</td>  
<td>Hal-hal yang berkaitan dengan budi, dan akal manusia.</td>  
</tr>  
<tr>  
<td>Pariwisata</td>  
<td>Suatu perjalanan yang dilakukan untuk rekreasi atau liburan dan juga persiapan yang dilakukan untuk aktivitas ini.</td>  
</tr>  
<tr>  
<td>SRS</td>  
<td> Software Requirements Specification</td>  
</tr>  
</tbody>  
</table><p><strong>1.4 Referensi</strong><br>  
</p><ul><li><a href="https://id.wikipedia.org/wiki/Android_(sistem\\\_operasi)">https://id.wikipedia.org/wiki/Android\\\_(sistem_operasi)</a>,</li>
<li><a href="https://id.wikipedia.org/wiki/Berita">https://id.wikipedia.org/wiki/Berita</a>, </li>
<li><a href="https://id.wikipedia.org/wiki/Budaya">https://id.wikipedia.org/wiki/Budaya</a>.</li>
<li>IEEE. IEEE Std 830-1998 IEEE Recommended Practice for Software Requirements Specifications. IEEE Computer Society, 1998. 1.5 Overview</li><ul></ul></ul><p></p>  
<p><strong>1.5 Overview</strong><br>  
Dokumen ini dibagi menjadi tiga bagian utama. Bagian pertama berisi penjelasan tentang dokumen SRS yang mencakup tujuan pembuatan dokumen ini, lingkup masalah yang diselesaikan yang dikembangkan oleh kami yaitu definisi, referensi, dan deskripsi umum. Bagian kedua berisi penjelasan secara umum mengenai aplikasi yang akan di kembangkan meliputi fungsi, karakteristik pengguna, batasan dan asumsi yang diambil dalam pengembangan aplikasi.Bagian ke tiga berisi uraian aplikasi secara lebih rinci.</p>  
<p><strong>2. GAMBARAN UMUM</strong><br>  
</p><p>Aplikasi Budaya dan Pariwisata Kab. Indramayu Berbasis Android adalah aplikasi yang digunakan untuk mempermudah penggunaan dalam pencarian dan informasi seputar budaya dan pariwisata di Kabupaten Indramayu.</p>  
<p><strong>2.1. Perspektif Produk</strong><br>  
Pada proyek ini dibuat dengan sistem berbasis Android dimana aplikasi ini bisa diakses hanya dengan smartphone dengan Sistem operasinya adalah Android. Aplikasi ini dibangun dengan menggunakan aplikasi Android Studio dan Firebase sebagai databasenya.<br>  
Aplikasi ini memungkinkan admin untuk menyebarkan informasi tentang lomba atau event yang diadakan oleh Dinas Kebudayaan dan Pariwisata Kabupaten Indramayu dan informasi seputar pariwisata apa saja yang berada di daerah Indramayu.<br>  
</p><p><strong>2.1.1 Antarmuka sistem</strong></p><br>  
<p><img src="https://4.bp.blogspot.com/-80n_0OxZZ_w/Wp-lcm-mUII/AAAAAAAAAEA/dLxdDnG38Z8zyk7PNIP3hgChXTJiDFZ4gCLcBGAs/s1600/sistem.png" alt="enter image description here"></p>
<p>  
Sistem Aplikasi Budaya dan Pariwisata ini terdapat 2 aktor yaitu Admin dan User (Pengguna). Admin dan User (Pengguna) mempunyai fungsi yang berbeda dimana admin dapat mengolah data Pariwisata, data Budaya dan data Event juga dapat melihat ratting dari user. sedangkan user hanya dapat melihat data Pariwisata, data Budaya, dan data Event, user (pengguna) juga dapat menginputkan Pengaduan.  
</p>  
<p><strong>2.1.2 Antarmuka pengguna</strong></p>  
<ul>  
<li>  
<p>User (Android)</p>  
<ul>  
<li>  
<p>Start<br>  
<img src="https://lh3.googleusercontent.com/HAA09bkpYRhpoUKShgOB0Evi84PyQ-h0aWChqPBP2wN7us7MhDjDTzAqD0rd0pAoPX5IVyf-q8I=s200" alt="Start"><br>  
Tampilan Start hanya berupa gambar yang berfungsi sebagai tampilan awal pada saat membuka aplikasi.<br>  
Gambar yang ditampilkan berupa logo dan nama aplikasi.</p>  
</li>  
<li>  
<p>Sign In<br>  
<img src="https://lh3.googleusercontent.com/rpqP6jtwvm97wTBkkYBHty64W69Va2eQ4LONtGwQiuS-lMgxPnKakehUQgILa3kwQqx3y-z4SA4=s200" alt="SignIn" title="SignIn"><br>  
Tampilan Sign In merupakan tampilan bagi User untuk masuk ke aplikasi. Sign In berisi input text (username dan password) dan button Masuk.<br>  
Lalu terdapat link “Register disini” dan link “Lupa Password”.</p>  
</li>  
<li>  
<p>Register<br>  
<img src="https://lh3.googleusercontent.com/bfHffQ6CzGj72jtXyT_DawTfsENzn8y2iobnkn1apRT5uyroX05DXOnkVQpLLQCAcMJgJ_n-WGM=s200" alt="Register"><br>  
Tampilan Register merupakan tampilan untuk membuat User baru. Register berisi input text (username, e-mail, password, dan confirm password),<br>  
button Daftar, dan button berbentuk X yang terletak di pojok kiri atas.</p>  
</li>  
<li>  
<p>Home<br>  
<img src="https://lh3.googleusercontent.com/NwRFvTpGCi-5vlKvLpax2t3st6C9BFY8UmiQeo0pENDvJmZjwuJ99ng-9wwdkAszisvgz_EPg9E=s200" alt="HomeUser"><br>  
Tampilan Home merupakan tampilan utama pada aplikasi ini. Home berisi navigasi yang terletak di pojok kiri atas, input text “Cari Budaya/Pariwisata”,<br>  
dan menu yang terdiri dari beberapa button yang tersusun secara grid. Button tersebut adalah Budaya, Pariwisata, Event,<br>  
Berita, Profil Saya, dan Tentang Kami.</p>  
</li>  
</ul>  
</li>  
<li>  
<p>Admin (Web)</p>  
<ul>  
<li>  
<p>Sign In<br>  
<img src="https://lh3.googleusercontent.com/d9TdPqt4UcURXiaXZKX8mClUUkcG4YmTHKNrrKHQ-u8-yP_15HD9av5ztIw--DzLDxYKwiYUn1w=s300" alt="HomeAdmin"><br>  
Tampilan Sign In merupakan tampilan bagi Admin untuk masuk ke web. Sign In berisi input text (username dan password) dan button Masuk.<br>  
Lalu terdapat link “Lupa Password” yang terletak di bawah button masuk.</p>  
</li>  
<li>  
<p>Kategori<br>  
<img src="https://lh3.googleusercontent.com/h5s6GlIMPaKigo69-pO4TvHAfERMPhrkyfhuHAjPDD9j_n6mjkNeV88KNavWoVcos2x8Qg4ixXA=s300" alt="KategoriAdmin"><br>  
Tampilan Kategori merupakan tampilan bagi Admin untuk melihat menu. Kategori terdiri dari beberapa button yang tersusun secara grid.<br>  
Button tersebut adalah Budaya, Pariwisata, Event, Berita, Profil Saya, Data Admin, Data User, dan Lihat Komentar.</p>  
</li>  
</ul>  
</li>  
</ul>  
<p><strong>2.1.3 Antarmuka perangkat keras</strong><br>  
<br><img src="https://lh3.googleusercontent.com/X0547VB1z0t-vmZLOnlvdFPOPRxi0gGhFNuIcLjDgQCUg8taYVmNEcdEvKxQey7bWaY6_co0WVQ=s300" alt="2.3"><br>  
Sistem aplikasi ini memiliki 2 User yang aktif, yaitu Admin dan User. User dapat mengakses aplikasi melalui smartphone yang memiliki sistem operasi Android. Aplikasi ini bisa digunakan apabila terhubung ke internet. Data-data pada aplikasi ini selanjutnya disimpan di database (Server) dan selanjutnya dikelola oleh Admin.</p>  
<p><strong>2.1.4 Antarmuka perangkat lunak</strong><br>  
Untuk dapat menggunakan aplikasi budaya dan pariwisata Kabupaten Indramayu kita dapat mengakses lewat browser.<br>  
</p><p><strong>2.1.5 Antarmuka Komunikasi</strong></p>  
<p>Aplikasi ini bekerja sama dengan Dinas Kebudayaan dan Pariwisata Kabupaten Indramayu.</p><br>  
<p><strong>2.1.6 Batasan memori</strong></p><br>  
<p>Memori yang digunakan untuk aplikasi di usahakan tidak melebihi 100MB</p>  
<strong>2.1.7 Operasi-operasi</strong><br>  
<table>  
<thead>  
<tr>  
</tr>  
</thead>  
<tbody>  
<tr>  
<td><strong>Operasi</strong></td>  
<td><strong>Fungsi</strong></td>  
</tr>  
<tr>  
<td>Daftar</td>  
<td>Digunakan bagi user untuk mendaftar </td>  
</tr>  
<tr>  
<td>Login</td>  
<td>Digunakan untuk mengakses aplikasi </td>  
</tr>  
<tr>  
<td>Input Data</td>  
<td>Digunakan untuk memasukkan data</td>  
</tr>  
<tr>  
<td>Edit</td>  
<td>Digunakan untuk mengubah data</td>  
</tr>  
<tr>  
<td>Hapus</td>  
<td>Digunakan untuk menghapus data</td>  
</tr>  
<tr>  
<td>View</td>  
<td>Digunakan untuk menampilkan data</td>  
</tr>  
<tr>  
<td>Simpan</td>  
<td>Digunakan untuk menyimpan data</td>  
</tr>  
<tr>  
<td>Kembali</td>  
<td>Digunakan untuk kembali ke halaman sebelumnya</td>  
</tr>  
<tr><td>Pengaduan</td>  
<td>Digunakan untuk pengaduan pengguna</td>  
  
</tr></tbody></table><p><strong>2.1.8 Kebutuhan adaptasi</strong></p>  
<p><strong>2.2. Spesifikasi Kebutuhan Fungsional</strong><br>  
<img src="https://lh3.googleusercontent.com/aq2ARLrncTWCZ4ZOEiLrj4bwxnRXCzYJZO25W3-RsnjAoRAHMA29QJpLzSyrEcZYctmNToCazYsB" alt="usecase" title="usecase keseluruhan"><br>
</p><p><strong>2.2.1 User Login</strong></p>  
<p>Use Case: Login<br>
Diagram:</p>
<p><img src="https://lh3.googleusercontent.com/i-F1NFPY-xV7ejGrqxV7QLFH83dROOfA2xJqVtyiXEPTgO2c0V6Gz1Co9XBAEHNUzIm7t0Yf7NGR" alt="enter image description here"></p>
<p>Deskripsi singkat user melakukan login sebelum masuk ke halaman utama:
</p><ol>
<li>User melakukan login dengan username dan password.</li>
<li>Sistem melakukan validasi.</li>
<li>Bila user benar memasukkan username dan password maka sistem akan mengarahkan user ke halamanutama</li>
<li>Bila user salah memasukkan username dan password maka sistem akan menampilkan eror</li>
</ol>
Xref: Bagian 3.2.1, User login<p></p>
<strong>2.2.2 User Melihat Budaya</strong><br>
<p>Use case: melihat budaya<br>
Diagram:</p>
<p><img src="https://lh3.googleusercontent.com/aJvMtPpo98MB3LB-uN9TY421p30GDaX0DbHimOQdhrf--_M6iH8vhxwdiRbT5rThn4ZtLHXggco7" alt="enter image description here" title="userbudaya"></p>
<p>Deskripsi singkat ketika user melihat budaya:
</p><ol>
<li>Sistem menampilkan halaman utama yang berisi button budaya</li>
<li>User dapat mengklik tombol button budaya</li>
<li>Sistem menampilkan data budaya</li>
</ol>
Xref: Bagian 3.2.2, User lihat budaya<p></p>
<strong>2.2.3 User Melihat Wisata</strong><br>
<p>Use case: melihat wisata<br>
Diagram:</p>
<p><img src="https://lh3.googleusercontent.com/kDGYT_tryNcLBWRvT2ahCJJGpUWXkjcivLp50wzawgjyPO4ZWHJoSjIt1RXTwFyuZEmyqNgnCXan" alt="enter image description here" title="userlihatwisata"></p>
<p>Deskripsi singkat ketika user melihat wisata:
</p><ol>
<li>Sistem menampilkan halaman utama yang berisi button wisata</li>
<li>User dapat mengklik tombol button wisata</li>
<li>Sistem menampilkan data wisata</li>
</ol>
Xref: Bagian 3.2.3, User lihat wisata<p></p>
<strong>2.2.4 User Melihat Event</strong><br>
<p>Use case: melihat event<br>
Diagram:</p>
<p><img src="https://lh3.googleusercontent.com/rIO3jYt1ySvRwEriG3NPsP0rGrPABFj_P8QFuhuXkwDVJEjL8nMNhxfCriQ6qaIknL7lm31h1zdN" alt="enter image description here" title="userevent"></p>
<p>Deskripsi singkat ketika user melihat event:
</p><ol>
<li>Sistem menampilkan halaman utama yang berisi button event</li>
<li>User dapat mengklik tombol button event</li>
<li>Sistem menampilkan data event</li>
</ol>
Xref: Bagian 3.2.4, User lihat event<p></p>
<strong>2.2.5 User Mengajukan Pengaduan</strong><br>
<p>Use case: mengajukan pengaduan<br>
Diagram:</p>
<p><img src="https://lh3.googleusercontent.com/9fkLEPEU73UZRVCxTIV5mGCjmx48yOGGocaACpASJA6sDRdbDfSdAauKa9abyHyiQd2T98XXJB-5" alt="enter image description here" title="userpengaduan"></p>
<p>Deskripsi singkat ketika user mengajukan pengaduan:
</p><ol>
<li>Sistem menampilkan halaman utama yang berisi button pengaduan</li>
<li>User dapat mengklik tombol button pengaduan</li>
<li>User mengisi form pengaduan ke sistem</li>
<li>Sistem akan mengirim ke admin</li>
</ol>
Xref: Bagian 3.2.5, User mengajukan pengaduan<p></p>
<strong>2.2.6 Admin Login</strong><br>
<p>Use case: login<br>
Diagram:</p>
<p><img src="https://lh3.googleusercontent.com/hySM59sWo0DwaotyC5t4Zqr3lyXxRaGe6CwzzNccqkQ5Si8n612LfM22MnORBzA7sXNlqHVCHFNE" alt="enter image description here"></p>
<p>Deskripsi singkat ketika admin login:
</p><ol>
<li>Admin melakukan login dengan username dan password.</li>
<li>Sistem melakukan validasi.</li>
<li>Bila admin benar memasukkan username dan password maka sistem akan mengarahkan user ke halaman utama</li>
<li>Bila admin salah memasukkan username dan password maka sistem akan menampilkan eror</li>
</ol>
Xref: Bagian 3.2.6, Admin login<p></p>
<strong>2.2.7 Admin Membuat Artikel</strong><br>
<p>Use case: membuat artikel<br>
Diagram:</p>
<p><img src="https://lh3.googleusercontent.com/ovjoU2qy8-T6pJpf-0GogYPbkewd5rWeaPnNWZ0-GM1v04x_rvoqkTWUhS0NYnhlWNcO098rmfcW" alt="enter image description here" title="adminbuat"></p>
<p>Deskripsi singkat ketika admin membuat artikel:
</p><ol>
<li>Sistem menampilkan dasboard admin</li>
<li>Admin memilih menu artikel pada sidebar</li>
<li>Admin mengklik button tambah</li>
<li>Admin mengisi form artikel dan mengklik button simpan </li>
<li>Sistem akan mengirim data ke database</li>
</ol>
Xref: Bagian 3.2.7, Admin membuat artikel<p></p>
<strong>2.2.8 Admin Mengedit Artikel</strong><br>
<p>Use case: mengedit artikel<br>
Diagram:</p>
<p><img src="https://lh3.googleusercontent.com/0hjIhyUnQIBgGJnFvcIZIu2CbXcXjA1tFFqKl-LwYrEjW4Ov2axVfLDJlxq65MiYxu9wZq2Zkld2" alt="enter image description here" title="adminedit"></p>
<p>Deskripsi singkat ketika admin mengedit artikel:
</p><ol>
<li>Sistem menampilkan dasboard admin</li>
<li>Admin memilih menu artikel pada sidebar</li>
<li>Admin mengklik button edit</li>
<li>Admin mengedit form artikel  dan mengklik button simpan </li>
<li>Sistem akan mengirim data ke database</li>
</ol>
Xref: Bagian 3.2.8, Admin mengedit artikel<p></p>
<strong>2.2.9 Admin Menghapus Artikel</strong><br>
<p>Use case: menghapus artikel<br>
Diagram:</p>
<p><img src="https://lh3.googleusercontent.com/yYRKH_rWIGBDhoof0hqCEU94pN6nh-caz2LOTOvLtBd4mZHo-BtnopkiUojKG1z6UHBHs5JmGIiq" alt="enter image description here" title="adminhapus"></p>
<p>Deskripsi singkat ketika admin menghapus artikel:
</p><ol>
<li>Sistem menampilkan dasboard admin</li>
<li>Admin memilih menu artikel pada sidebar</li>
<li>Admin mengklik button hapus</li>
<li>Sistem mengirim notif peringatan ke admin dan mengklik button ya</li>
<li>Sistem akan mengirim data ke database</li>
</ol>
Xref: Bagian 3.2.9, Admin menghapus artikel<p></p>
<strong>2.2.10 Admin Menampilkan Pengaduan</strong><br>
<p>Use case: menampilkan pengaduan<br>
Diagram:</p>
<p><img src="https://lh3.googleusercontent.com/6-fbcLQWgRGQYrUb10NttqaazmythuCsACa7CtpuWeT3v4uo9PzEwW7KzFEjzOJLK0c-jeaHB03O" alt="enter image description here" title="adminpengaduan"></p>
<p>Deskripsi singkat ketika admin menampilkan pengaduan:
</p><ol>
<li>Sistem menampilkan dasboard admin</li>
<li>Admin memilih menu pengaduan pada sidebar</li>
<li>Admin memilih pengaduan yang ingin ditampilkan</li>
<li>Admin memilih menu artikel pada sidebar</li>
<li>Admin mengklik button tambah</li>
<li>Sistem mengirim notif peringatan ke admin dan mengklik button ya</li>
<li>Sistem akan mengirim data ke database</li>
</ol>
Xref: Bagian 3.2.10, Admin menampilkan artikel<p></p>
<strong>2.3. Spesifikasi Kebutuhan Non-fungsional</strong><br>  
<strong>2.3.1 Spesifikasi User Interface</strong><br>  
User Interface yang ada pada aplikasi harus user-friendly, dan mudah untuk digunakan.<br>  
<strong>2.3.2 Spesifikasi Kinerja</strong><br>  
Sistem ini diharapkan dapat di gunakan dalam jangka panjang dan sistem ini dapat berfungsi secara optimal.<br>  
<strong>2.3.3 Ketersediaan dan Keandalan</strong><br>  
Aplikasi dapat menyediakan backup pada database yang digunakan.<br>  
<strong>2.3.4 Spesifikasi Keamanan</strong><br>  
Keamanan data akan terjaga karena menerapkan validasi pada saat pengguna mulai login.  
<p><strong>2.4. Karakteristik Pengguna</strong><br></p>  
<p>  
Dengan adanya aplikasi ini diharapkan dapat membantu admin mengolah data pariwisata, data kebudayaan, data event dan pendaftaran untuk mengikuti event. kemudian bagi pengguna sendiri diharapkan dapat mempermudah pengguna untuk mendapatkan informasi tentang pariwisata, kebudayaan dan event yang di adakan oleh dinas kebudayaan dan pariwisata kabupaten Indramayu menggunakan aplikasi mobile ini.  
</p>  
<strong>2.5. Batasan-batasan</strong><br>  
Pada Aplikasi Budaya dan Pariwisata Kabupaten Indramayu harus menggunakan smartphone denga sistem operasi Android untuk dapat mengaksesnya atau menggunakannya. Pengguna dapat login dengan mendaftar terlebih dahulu.<br>  
<p><strong>3. Requirement Specification</strong></p>  
<p><strong>3.1 Persyaratan Antarmuka Eksternal</strong><br>  
Salah satu persyaratan untuk mengakses Aplikasi ini adalah dengan mendaftarkan diri dan melengkapi kolom data diri.</p>  
<p><strong>3.2 Functional Requirnment</strong><br>  
</p><p><strong>3.2.1 User Login</strong></p>  
<table>  
<thead>  
<tr>  
</tr>  
</thead>  
<tbody>  
<tr>  
<td>Nama Fungsi</td>  
<td>User Login</td>  
</tr>  
<tr>  
<td>Ref</td>  
<td>Bag 2.2.1 User Login</td>  
</tr>  
<tr>  
<td>Trigger</td>  
<td>Membuka Aplikasi Budaya dan Pariwisata </td>  
</tr>  
<tr>  
<td>Precondision</td>  
<td>Halaman Utama Login</td>  
</tr>  
<tr>  
<td>Basic Path</td>  
<td>
<ol>
<li>User mengisi form login dengan username dan password dan mengklik button login</li>
<li>sistem melakukan validasi login</li>
<li>bila sukses sistem akan mengarahkan ke halaman utama</li>
<li>bila gagal sistem akan menampilkan notif peringatan</li>
</ol>
</td>  
</tr>  
<tr>  
<td>Alternative</td>  
<td> Tidak ada</td>  
</tr>  
<tr>  
<td>Post Condition</td>  
<td>User dapat login dan dapat mengakses aplikasi budaya dan pariwisata </td>  
</tr>  
<tr>  
<td>Exception Push</td>  
<td>Username dan password salah</td>  
</tr>  
</tbody>  
</table>  
<p><strong>3.2.2 User Melihat Budaya</strong></p>  
<table>  
<thead>  
<tr>  
</tr>  
</thead>  
<tbody>  
<tr>  
<td>Nama Fungsi</td>  
<td>User Melihat Budaya</td>  
</tr>  
<tr>  
<td>Ref</td>  
<td>Bag 2.2.2 User Melihat Budaya</td>  
</tr>  
<tr>  
<td>Trigger</td>  
<td>Membuka Aplikasi Budaya dan Pariwisata </td>  
</tr>  
<tr>  
<td>Precondision</td>  
<td>Halaman Utama Login</td>  
</tr>  
<tr>  
<td>Basic Path</td>  
<td>
<ol>
<li>Sistem menampilkan halaman utama</li>
<li>User mengklik button budaya</li>
<li>Sistem menampilkan data budaya</li>
</ol>
</td>  
</tr>  
<tr>  
<td>Alternative</td>  
<td> Tidak ada</td>  
</tr>  
<tr>  
<td>Post Condition</td>  
<td>User melihat budaya</td>  
</tr>  
<tr>  
<td>Exception Push</td>  
<td> Tidak ada koneksi</td>  
</tr>  
</tbody>   
</table>
<p><strong>3.2.3 User Melihat Wisata</strong></p>  
<table>  
<thead>  
<tr>  
</tr>  
</thead>  
<tbody>  
<tr>  
<td>Nama Fungsi</td>  
<td>User Melihat Wisata</td>  
</tr>  
<tr>  
<td>Ref</td>  
<td>Bag 2.2.3 User Melihat Wisata</td>  
</tr>  
<tr>  
<td>Trigger</td>  
<td>Membuka Aplikasi Budaya dan Pariwisata </td>  
</tr>  
<tr>  
<td>Precondision</td>  
<td>Halaman Utama Login</td>  
</tr>  
<tr>  
<td>Basic Path</td>  
<td>
<ol>
<li>Sistem menampilkan halaman utama</li>
<li>User mengklik button wisata</li>
<li>Sistem menampilkan data wisata</li>
</ol>
</td>  
</tr>  
<tr>  
<td>Alternative</td>  
<td> Tidak ada</td>  
</tr>  
<tr>  
<td>Post Condition</td>  
<td>User melihat wisata</td>  
</tr>  
<tr>  
<td>Exception Push</td>  
<td> Tidak ada koneksi</td>  
</tr>  
</tbody>   
</table>
<p><strong>3.2.4 User Melihat Event</strong></p>  
<table>  
<thead>  
<tr>  
</tr>  
</thead>  
<tbody>  
<tr>  
<td>Nama Fungsi</td>  
<td>User Melihat Event</td>  
</tr>  
<tr>  
<td>Ref</td>  
<td>Bag 2.2.4 User Melihat Event</td>  
</tr>  
<tr>  
<td>Trigger</td>  
<td>Membuka Aplikasi Budaya dan Pariwisata </td>  
</tr>  
<tr>  
<td>Precondision</td>  
<td>Halaman Utama Login</td>  
</tr>  
<tr>  
<td>Basic Path</td>  
<td>
<ol>
<li>Sistem menampilkan halaman utama</li>
<li>User mengklik button event</li>
<li>Sistem menampilkan data event</li>
</ol>
</td>  
</tr>  
<tr>  
<td>Alternative</td>  
<td> Tidak ada</td>  
</tr>  
<tr>  
<td>Post Condition</td>  
<td>User melihat event</td>  
</tr>  
<tr>  
<td>Exception Push</td>  
<td> Tidak ada koneksi</td>  
</tr>  
</tbody>   
</table>
<p><strong>3.2.5 User Mengajukan Pengaduan</strong></p>  
<table>  
<thead>  
<tr>  
</tr>  
</thead>  
<tbody>  
<tr>  
<td>Nama Fungsi</td>  
<td>User Mengajukan Pengaduan</td>  
</tr>  
<tr>  
<td>Ref</td>  
<td>Bag 2.2.5 User Mengajukan Pengaduan</td>  
</tr>  
<tr>  
<td>Trigger</td>  
<td>Membuka Aplikasi Budaya dan Pariwisata </td>  
</tr>  
<tr>  
<td>Precondision</td>  
<td>Halaman Utama Login</td>  
</tr>  
<tr>  
<td>Basic Path</td>  
<td>
<ol>
<li>Sistem menampilkan halaman utama</li>
<li>User mengklik button pengaduan</li>
<li>User mengisi form pengaduan dan mengklik button kirim</li>
<li>Sistem mengirim data ke admin</li>
</ol>
</td>  
</tr>  
<tr>  
<td>Alternative</td>  
<td> Tidak ada</td>  
</tr>  
<tr>  
<td>Post Condition</td>  
<td>Halaman pengaduan</td>  
</tr>  
<tr>  
<td>Exception Push</td>  
<td> Tidak ada koneksi</td>  
</tr>  
</tbody>   
</table>
<p><strong>3.3 Struktur Detail Kebutuhan Non Functional</strong><br>  
</p><p><strong>3.3.1 Logika Struktur Data</strong><br>  
</p><p>Struktur data logika pada sistem Aplikasi Budaya dan Pariwisata terdapat struktur Database yang dijelaskan menggunakan ERD.  
</p><p>

![enter image description here](https://2.bp.blogspot.com/-oHNJmz4bqIU/Wp_vwODHFFI/AAAAAAAAAEQ/p7xITowij_cWG7QfqIYlJmuO2WckR423gCLcBGAs/s1600/ERD222.jpg)

<p>Pada ERD terdapat tabel admin, tabel user, tabel pariwisata, tabel budaya, tabel event dan tabel pengaduan.</p>


