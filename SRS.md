---


---

<h1 id="software-requirements-specification">SOFTWARE REQUIREMENTS SPECIFICATION</h1>
<p>VERSION<br>
22 Februari 2018<br>
Kelompok 5 D3TI2D<br>
<img src="https://lh3.googleusercontent.com/qEHYPVzo0kjd8ikhrCIF4cI_PhR8pmK5vDU14oEp9OPyVT-eA54cVp8C9iyJ8rKDfH8OR1dnT1zv=s200" alt="enter image description here"></p>
<ol>
<li>Firsti Aulya K. K. (1603098)</li>
<li>Firmansyah (1603097)</li>
<li>Diyanti (1603094)</li>
</ol>
<p>Jurusan D3 Teknik Informatika<br>
Politeknik Negeri Indramayu</p>
<p>1. Pendahuluan</p>
<p>1.1 Tujuan</p>
<p>Dokumen ini bertujuan untuk menjelaskan secara detail mengenai aplikasi yang kami buat yang berjudul “Aplikasi Budaya dan Pariwisata Kabupaten Indramayu berbasis Android”,<br>
pada dokumen ini akan menjelaskan seperti : Mock-up, rancangan sistem, dan lain-lain.</p>
<p>1.2 Lingkup Masalah</p>
<p>Aplikasi Budaya dan Pariwisata Indramayu adalah salah satu aplikasi berbasis android yang digunakan untuk seluruh masyarakat, khususnya masyarakat yang berada di daerah Indramayu untuk mengetahui kebudayaan yang ada di Indramayu dan event atau lomba yang akan diselenggarakan oleh Dinas Kebudayaan dan Pariwisata Kabupaten Indramayu.<br>
Pada Proyek ini dibuat sistem berbasis android dimana pengolahan informasi dan data diakses melalui smartphone dengan sistem operasi android.</p>
<p>1.3 Definisi, Akronim, Singkatan</p>

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
<td>administrator</td>
<td>orang / orang-orang yang bertugas untuk mengurusi Hal-hal administrasi. Dalam dunia Internet, seorang administrator bertugas untuk mengelola hal- hal yang berhubungan dengan komputer.</td>
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
<td>Berita</td>
<td>Informasi baru atau informasi mengenai sesuatu yang sedang terjadi, disajikan lewat bentuk cetak, siaran, Internet, atau dari mulut ke mulut kepada orang ketiga atau orang banyak.</td>
</tr>
</tbody>
</table><p>1.4 Referensi<br>
<a href="https://id.wikipedia.org/wiki/Android_(sistem_operasi)">https://id.wikipedia.org/wiki/Android_(sistem_operasi)</a>, <a href="https://id.wikipedia.org/wiki/Berita">https://id.wikipedia.org/wiki/Berita</a>, <a href="https://id.wikipedia.org/wiki/Budaya">https://id.wikipedia.org/wiki/Budaya</a>.</p>
<p>1.5 Overview<br>
Dokumen ini dibagi menjadi tiga bagian utama. Bagian pertama berisi penjelasan tentang dokumen SRS yang mencakup tujuan pembuatan dokumen ini, lingkup masalah yang diselesaikan yang dikembangkan oleh kami yaitu definisi, referensi, dan deskripsi umum. Bagian kedua berisi penjelasan secara umum mengenai aplikasi yang akan di kembangkan meliputi fungsi, karakteristik pengguna, batasan dan asumsi yang diambil dalam pengembangan aplikasi.Bagian ke tiga berisi uraian aplikasi secara lebih rinci.</p>
<p>2. Gambaran Umum<br>
Aplikasi Budaya dan Pariwisata Kab. Indramayu Berbasis Android adalah aplikasi yang digunakan untuk mempermudah penggunaan dalam pencarian dan informasi seputar budaya dan pariwisata di Kabupaten Indramayu.</p>
<p>2.1. Perspektif Produk<br>
Pada proyek ini dibuat dengan sistem berbasis Android dimana aplikasi ini bisa diakses hanya dengan smartphone dengan Sistem operasinya adalah Android. Aplikasi ini dibangun dengan menggunakan aplikasi Android Studio dan Firebase sebagai databasenya.<br>
Aplikasi ini memungkinkan admin untuk menyebarkan informasi tentang lomba atau event yang diadakan oleh Dinas Kebudayaan dan Pariwisata Kabupaten Indramayu dan informasi seputar pariwisata apa saja yang berada di daerah Indramayu.<br>
2.1.1 Antarmuka sistem<br>
2.1.2 Antarmuka pengguna</p>
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
<p>2.1.3 Antarmuka perangkat keras</p>
<p><img src="https://lh3.googleusercontent.com/X0547VB1z0t-vmZLOnlvdFPOPRxi0gGhFNuIcLjDgQCUg8taYVmNEcdEvKxQey7bWaY6_co0WVQ=s300" alt="2.3"><br>
Sistem aplikasi ini memiliki 2 User yang aktif, yaitu Admin dan User. User dapat mengakses aplikasi melalui smartphone yang memiliki sistem operasi Android. Aplikasi ini bisa digunakan apabila terhubung ke internet. Data-data pada aplikasi ini selanjutnya disimpan di database (Server) dan selanjutnya dikelola oleh Admin.</p>
<p>2.1.4 Antarmuka perangkat lunak<br>
2.1.5 Antarmuka Komunikasi<br>
Aplikasi ini bekerja sama dengan Dinas Kebudayaan dan Pariwisata Kabupaten Indramayu.<br>
2.1.6 Batasan memori<br>
2.1.7 Operasi-operasi<br>
2.1.8 Kebutuhan adaptasi</p>
<p>2.2. Spesifikasi Kebutuhan Fungsional</p>
<p>2.3. Spesifikasi Kebutuhan Non-fungsional<br>
2.3.1 Spesifikasi User Interface<br>
User Interface yang ada pada aplikasi harus user-friendly, dan mudah untuk digunakan.<br>
2.3.2 Spesifikasi Kinerja<br>
Sistem ini diharapkan dapat di gunakan dalam jangka panjang dan dalam sistem ini dapat berfungsi secara optimal.<br>
2.3.3 Ketersediaan dan Keandalan<br>
Aplikasi dapat menyediakan backup pada database yang digunakan.<br>
2.3.4 Spesifikasi Keamanan</p>
<p>2.4. Karakteristik Pengguna<br>
2.5. Batasan-batasan<br>
Pada Aplikasi Budaya dan Pariwisata Kabupaten Indramayu harus menggunakan smartphone denga sistem operasi Android untuk dapat mengaksesnya atau menggunakannya. Pengguna dapat login dengan mendaftar terlebih dahulu.<br>
2.6. Asumsi-asumsi Keterkaitan<br>
2.7. Kebutuhan Penyeimbang</p>
<p>3. Requirement Specification</p>
<p>3.1 Persyaratan Antarmuka Eksternal<br>
Salah satu persyaratan untuk mengakses Aplikasi ini adalah dengan mendaftarkan diri dan melengkapi kolom data diri.</p>
<p>3.2 Functional Recruitment</p>

