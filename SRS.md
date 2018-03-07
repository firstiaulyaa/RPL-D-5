---


---

<p align="center"></p><h1 id="software-requirements-specification">SOFTWARE REQUIREMENTS SPECIFICATION</h1><p></p>  
<p align="center">VERSION<br>  
22 Februari 2018<br>  
</p><p align="center">  
<img src="https://lh3.googleusercontent.com/qEHYPVzo0kjd8ikhrCIF4cI_PhR8pmK5vDU14oEp9OPyVT-eA54cVp8C9iyJ8rKDfH8OR1dnT1zv=s300" alt="enter image description here" title="logo">  
</p><p align="center">Kelompok 5 D3TI2D</p>  
<ol>  
<p align="center"></p><li>Firsti Aulya K. K. (1603098)</li>  
<li>Firmansyah (1603097)</li>  
<li>Diyanti (1603094)<br>  
</li><li>Rizky Alief Satria (1603111)<br>  
</li><p></p>  
<h2 align="center"><strong>Jurusan D3 Teknik Informatika</strong></h2>  
<h2 align="center"><strong>Politeknik Negeri Indramayu </strong></h2>  
<h2 align="center"><strong>2018</strong></h2>  
  
</ol>  
  
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
<a href="https://id.wikipedia.org/wiki/Android_(sistem\_operasi)">https://id.wikipedia.org/wiki/Android\_(sistem_operasi)</a>, <a href="https://id.wikipedia.org/wiki/Berita">https://id.wikipedia.org/wiki/Berita</a>, <a href="https://id.wikipedia.org/wiki/Budaya">https://id.wikipedia.org/wiki/Budaya</a>.</p>  
<p><strong>1.5 Overview</strong><br>  
Dokumen ini dibagi menjadi tiga bagian utama. Bagian pertama berisi penjelasan tentang dokumen SRS yang mencakup tujuan pembuatan dokumen ini, lingkup masalah yang diselesaikan yang dikembangkan oleh kami yaitu definisi, referensi, dan deskripsi umum. Bagian kedua berisi penjelasan secara umum mengenai aplikasi yang akan di kembangkan meliputi fungsi, karakteristik pengguna, batasan dan asumsi yang diambil dalam pengembangan aplikasi.Bagian ke tiga berisi uraian aplikasi secara lebih rinci.</p>  
<p><strong>2. GAMBARAN UMUM</strong><br>  
Aplikasi Budaya dan Pariwisata Kab. Indramayu Berbasis Android adalah aplikasi yang digunakan untuk mempermudah penggunaan dalam pencarian dan informasi seputar budaya dan pariwisata di Kabupaten Indramayu.</p>  
<p><strong>2.1. Perspektif Produk</strong><br>  
Pada proyek ini dibuat dengan sistem berbasis Android dimana aplikasi ini bisa diakses hanya dengan smartphone dengan Sistem operasinya adalah Android. Aplikasi ini dibangun dengan menggunakan aplikasi Android Studio dan Firebase sebagai databasenya.<br>  
Aplikasi ini memungkinkan admin untuk menyebarkan informasi tentang lomba atau event yang diadakan oleh Dinas Kebudayaan dan Pariwisata Kabupaten Indramayu dan informasi seputar pariwisata apa saja yang berada di daerah Indramayu.<br>  
<strong>2.1.1 Antarmuka sistem</strong><br>  
</p><p><img src="https://lh3.googleusercontent.com/-CNjbNaTNhmQ/WpuJ5kDQf5I/AAAAAAAAACA/kSVSESncFRQPHkvo011uQkTwp8ULKoktQCJoC/w530-h350-n-rw/Screenshot_10.png" alt="enter image description here"></p>
<p>  
Sistem Aplikasi Budaya dan Pariwisata ini terdapat 2 aktor yaitu Admin dan User (Pengguna). Admin dan User (Pengguna) mempunyai fungsi yang berbeda dimana admin dapat mengolah data Pariwisata, data Budaya dan data Event juga dapat melihat ratting dari user. sedangkan user hanya dapat melihat data Pariwisata, data Budaya, dan data Event, user (pengguna) juga dapat menginputkan ratting.  
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
<img src="https://lh3.googleusercontent.com/X0547VB1z0t-vmZLOnlvdFPOPRxi0gGhFNuIcLjDgQCUg8taYVmNEcdEvKxQey7bWaY6_co0WVQ=s300" alt="2.3"><br>  
Sistem aplikasi ini memiliki 2 User yang aktif, yaitu Admin dan User. User dapat mengakses aplikasi melalui smartphone yang memiliki sistem operasi Android. Aplikasi ini bisa digunakan apabila terhubung ke internet. Data-data pada aplikasi ini selanjutnya disimpan di database (Server) dan selanjutnya dikelola oleh Admin.</p>  
<p><strong>2.1.4 Antarmuka perangkat lunak</strong><br>  
Untuk dapat menggunakan aplikasi budaya dan pariwisata Kabupaten Indramayu kita dapat mengakses lewat browser.<br>  
<strong>2.1.5 Antarmuka Komunikasi</strong><br>  
Aplikasi ini bekerja sama dengan Dinas Kebudayaan dan Pariwisata Kabupaten Indramayu.<br>  
<strong>2.1.6 Batasan memori</strong> (skip)<br>  
<strong>2.1.7 Operasi-operasi</strong><br>  
Perangkat lunak yang dibutuhkan adalah :</p>  
<ul>  
<li>Sistem Operasi : Microsoft Windows 10</li>  
<li>DBMS : Firebase</li>  
<li>Bahasa pemrograman : Java, Php</li>  
</ul>  
<p><strong>2.1.8 Kebutuhan adaptasi</strong> (skip)</p>  
<p><strong>2.2. Spesifikasi Kebutuhan Fungsional</strong><br>  
<img src="https://lh3.googleusercontent.com/aq2ARLrncTWCZ4ZOEiLrj4bwxnRXCzYJZO25W3-RsnjAoRAHMA29QJpLzSyrEcZYctmNToCazYsB" alt="usecase" title="usecase keseluruhan"><br>  
<strong>2.3. Spesifikasi Kebutuhan Non-fungsional</strong><br>  
<strong>2.3.1 Spesifikasi User Interface</strong><br>  
User Interface yang ada pada aplikasi harus user-friendly, dan mudah untuk digunakan.<br>  
<strong>2.3.2 Spesifikasi Kinerja</strong><br>  
Sistem ini diharapkan dapat di gunakan dalam jangka panjang dan sistem ini dapat berfungsi secara optimal.<br>  
<strong>2.3.3 Ketersediaan dan Keandalan</strong><br>  
Aplikasi dapat menyediakan backup pada database yang digunakan.<br>  
<strong>2.3.4 Spesifikasi Keamanan</strong><br>  
Keamanan data akan terjaga karena menerapkan validasi pada saat pengguna mulai login.</p>  
<p><strong>2.4. Karakteristik Pengguna</strong><br></p>  
<p>  
Dengnan adanya aplikasi ini diharapkan dapat membantu admin mengolah data pariwisata, data kebudayaan, data event dan pendaftaran untuk mengikuti event. kemudian bagi pengguna sendiri diharapkan dapat mempermudah pengguna untuk mendapatkan informasi tentang pariwisata, kebudayaan dan event yang di adakan oleh dinas kebudayaan dan pariwisata kabupaten Indramayu menggunakan aplikasi mobile ini.  
</p>  
<strong>2.5. Batasan-batasan</strong><br>  
Pada Aplikasi Budaya dan Pariwisata Kabupaten Indramayu harus menggunakan smartphone denga sistem operasi Android untuk dapat mengaksesnya atau menggunakannya. Pengguna dapat login dengan mendaftar terlebih dahulu.<br>  
<p><strong>3. Requirement Specification</strong></p>  
<p><strong>3.1 Persyaratan Antarmuka Eksternal</strong><br>  
Salah satu persyaratan untuk mengakses Aplikasi ini adalah dengan mendaftarkan diri dan melengkapi kolom data diri.</p>  
<p><strong>3.2 Functional Reqruitment</strong><br>  
</p><p><strong>3.2.1 Sign In<strong></strong></strong></p>  
<br><table>  
<thead>  
<tr>  
</tr>  
</thead>  
<tbody>  
<tr>  
<td>Nama Fungsi</td>  
<td>Sign In</td>  
</tr>  
<tr>  
<td>Ref</td>  
<td>Bag 2.1.2 Sign In</td>  
</tr>  
<tr>  
<td>Trigger</td>  
<td>Membuka Aplikasi Budaya dan Pariwisata </td>  
</tr>  
<tr>  
<td>Precondision</td>  
<td>Halaman Utama Aplikasi</td>  
</tr>  
<tr>  
<td>Basic Path</td>  
<td> User membuka aplikasi budaya dan pariwisata </td>  
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
<td> Tidak ada koneksi</td>  
</tr>  
</tbody>  
  
</table><p><strong>3.2.2 Register</strong></p>  
  
  
<br><table>  
<thead>  
<tr>  
</tr>  
</thead>  
<tbody>  
<tr>  
<td>Nama Fungsi</td>  
<td>Register</td>  
</tr>  
<tr>  
<td>Ref</td>  
<td>Bag 2.1.2 Register</td>  
</tr>  
<tr>  
<td>Trigger</td>  
<td>Membuka Aplikasi Budaya dan Pariwisata </td>  
</tr>  
<tr>  
<td>Precondision</td>  
<td>Halaman Utama Aplikasi Budaya dan Pariwisata</td>  
</tr>  
<tr>  
<td>Basic Path</td>  
<td>1. User membuka aplikasi  
<p>2.User klik daftar</p></td>  
</tr>  
<tr>  
<td>Alternative</td>  
<td> Tidak ada</td>  
</tr>  
<tr>  
<td>Post Condition</td>  
<td>User dapat Daftar dan mengakses aplikasi budaya dan pariwisata </td>  
</tr>  
<tr>  
<td>Exception Push</td>  
<td> Tidak ada koneksi</td>  
</tr>  
</tbody>  
  
</table><p><strong>3.2.3 Home</strong></p>  
  
  
<br><table>  
<thead>  
<tr>  
</tr>  
</thead>  
<tbody>  
<tr>  
<td>Nama Fungsi</td>  
<td>Home</td>  
</tr>  
<tr>  
<td>Ref</td>  
<td>Bag 2.1.2 Home</td>  
</tr>  
<tr>  
<td>Trigger</td>  
<td>Membuka Aplikasi Budaya dan Pariwisata </td>  
</tr>  
<tr>  
<td>Precondision</td>  
<td>Halaman Login atau Daftar</td>  
</tr>  
<tr>  
<td>Basic Path</td>  
<td> 1. Admin mengisi username dan password  
<p>2. Admin klik button Sign In</p></td>  
</tr>  
<tr>  
<td>Alternative</td>  
<td> Tidak ada</td>  
</tr>  
<tr>  
<td>Post Condition</td>  
<td>User dapat memilih menu kategori apa yang ingin di pilih seperti menu Pariwisata, menu Budaya dan menu Event </td>  
</tr>  
<tr>  
<td>Exception Push</td>  
<td> Tidak ada koneksi</td>  
</tr>  
</tbody>  
  
</table><p><strong>3.2.4 Sign In (web)</strong></p>  
  
  
<br><table>  
<thead>  
<tr>  
</tr>  
</thead>  
<tbody>  
<tr>  
<td>Nama Fungsi</td>  
<td>Sign In (web)</td>  
</tr>  
<tr>  
<td>Ref</td>  
<td>Bag 2.1.2 Sign In</td>  
</tr>  
<tr>  
<td>Trigger</td>  
<td>Membuka Aplikasi Budaya dan Pariwisata pada website</td>  
</tr>  
<tr>  
<td>Precondision</td>  
<td>Halaman Login </td>  
</tr>  
<tr>  
<td>Basic Path</td>  
<td> User membuka aplikasi pada website</td>  
</tr>  
<tr>  
<td>Alternative</td>  
<td> Tidak ada</td>  
</tr>  
<tr>  
<td>Post Condition</td>  
<td>Admin dapat login </td>  
</tr>  
<tr>  
<td>Exception Push</td>  
<td> Tidak ada koneksi</td>  
</tr>  
</tbody>  
  
</table><p><strong>3.2.5 Kategori</strong></p>  
<br><br><br><table>  
<thead>  
<tr>  
</tr>  
</thead>  
<tbody>  
<tr>  
<td>Nama Fungsi</td>  
<td>Kategori</td>  
</tr>  
<tr>  
<td>Ref</td>  
<td>Bag 2.1.2 Kategori</td>  
</tr>  
<tr>  
<td>Trigger</td>  
<td>Membuka Aplikasi Budaya dan Pariwisata pada website</td>  
</tr>  
<tr>  
<td>Precondision</td>  
<td>Halaman Login </td>  
</tr>  
<tr>  
<td>Basic Path</td>  
<td> 1. Admin mengisi username dan password  
<p>2. Admin klik button sign in</p></td>  
</tr><tr>  
</tr><tr>  
<td>Alternative</td>  
<td> Tidak ada</td>  
</tr>  
<tr>  
<td>Post Condition</td>  
<td>Admin dapat memilih menu apa yang akan di akses pada aplikasi budaya dan pariwisata </td>  
</tr>  
<tr>  
<td>Exception Push</td>  
<td> Tidak ada koneksi</td>  
</tr>  
</tbody>  
  
  
  
</table><p><strong>3.3 Struktur Detail Kebutuhan Non Functional</strong><br>  
</p><p><strong>3.3.1 Logika Struktur Data</strong><br>  
</p><p>Struktur data logika pada sistem Aplikasi Budaya dan Pariwisata terdapat struktur Database yang dijelaskan menggunakan ERD.  
</p><p><img src="https://1.bp.blogspot.com/-Wwz2A0ULTEA/Wpu3d82p1NI/AAAAAAAAADg/irPmAVKe5rMZzWTABoXiqvz1jdRIsg7cACLcBGAs/s1600/ERD.jpg" alt="enter image description here"></p>
<p>Pada ERD terdapat tabel admin, tabel user, tabel pariwisata, tabel budaya, tabel event dan tabel ratting.  
Dimana admin menginputkan data Budaya, data Pariwisata, dan data Event.Admin juga dapat mengolah data Budaya, data Pariwisata dan data Event dan admin juga dapat mengolah data user.  
Sementara User dapat melihat data Budaya, melihat data Pariwisata, dan data Event. User dapat menginputkan ratting untuk memberikan penilaian.</p>

