

<h1 align="center" id="software-requirements-specification">SOFTWARE REQUIREMENTS SPECIFICATION</h1>  
<p align="center"><strong>Version 1.3<br> 
29 Maret 2018</strong><br>  
</p><p align="center">  
<img src="https://lh3.googleusercontent.com/qEHYPVzo0kjd8ikhrCIF4cI_PhR8pmK5vDU14oEp9OPyVT-eA54cVp8C9iyJ8rKDfH8OR1dnT1zv=s300" alt="enter image description here" title="logo">  
</p><p align="center"><strong>Kelompok 5 D3TI2D</strong></p>  
<p align="center"><strong>Firsti Aulya K. K. (1603098)<br>  
Firmansyah (1603097) <br>  
Diyanti (1603094)<br>  
Rizky Alief Satria (1603111)</strong><br>  
</p>  
<p align="center"><strong>Jurusan D3 Teknik Informatika<br>
Politeknik Negeri Indramayu<br>
2018</strong></p>  
<p><strong>1. PENDAHULUAN</strong>  
</p><p><strong>1.1 Tujuan</strong></p>  
<p>Dokumen ini bertujuan untuk menjelaskan secara detail mengenai aplikasi yang kami buat yang berjudul “BUSAYU (Aplikasi Budaya dan Pariwisata Kab. Indramayu) berbasis Android”,<br>  
pada dokumen ini akan menjelaskan seperti : Mock-up, rancangan sistem, dan lain-lain.</p>  
<p><strong>1.2 Lingkup Masalah</strong></p>  
<p>BUSAYU (Aplikasi Budaya dan Pariwisata Kab, Indramayu) adalah salah satu aplikasi berbasis Android yang digunakan untuk seluruh masyarakat, khususnya masyarakat yang berada di daerah Indramayu untuk mengetahui kebudayaan yang ada di Indramayu dan event atau lomba yang akan diselenggarakan oleh Dinas Kebudayaan dan Pariwisata Kabupaten Indramayu.<br>  
Pada Proyek ini dibuat sistem berbasis Android dimana pengolahan informasi dan data diakses melalui smartphone dengan sistem operasi Android.</p>  
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
<td>Kegiatan</td>  
<td>sebuah rangkaian acara dalam rangka tujuan tertentu yang diadakan oleh pihak tertentu dalam waktu tertentu dan tempat tertentu dengan biaya tertentu</td>  
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
<tr>  
<td>BUSAYU</td>  
<td> Aplikasi Budaya dan Pariwisata kab. Indramayu</td>  
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
</p><p>BUSAYU (Aplikasi Budaya dan Pariwisata Kab. Indramayu) Berbasis Android adalah aplikasi yang digunakan untuk mempermudah penggunaan dalam pencarian dan informasi seputar budaya dan pariwisata di Kabupaten Indramayu.</p>  
<p><strong>2.1. Perspektif Produk</strong><br>  
Pada proyek ini dibuat dengan sistem berbasis Android dimana aplikasi ini bisa diakses hanya dengan smartphone dengan Sistem operasinya adalah Android. Aplikasi ini dibangun dengan menggunakan aplikasi Android Studio dan XAMPP sebagai databasenya.<br>  
Aplikasi ini memungkinkan admin untuk menyebarkan informasi tentang lomba atau event yang diadakan oleh Dinas Kebudayaan dan Pariwisata Kabupaten Indramayu dan informasi seputar pariwisata apa saja yang berada di daerah Indramayu.<br>  
Aplikasi ini memungkinkan pengguna untuk mengajukan pengaduan tentang kebudayaan dan pariwisata yang ada di Indramayu.<br>
</p><p><strong>2.1.1 Antarmuka sistem</strong></p><br>  
<p><img src="https://4.bp.blogspot.com/-80n_0OxZZ_w/Wp-lcm-mUII/AAAAAAAAAEA/dLxdDnG38Z8zyk7PNIP3hgChXTJiDFZ4gCLcBGAs/s1600/sistem.png" alt="enter image description here"></p>
<p>  
Sistem Aplikasi Budaya dan Pariwisata ini terdapat 2 aktor yaitu Admin dan User (Pengguna). Admin dan User (Pengguna) mempunyai fungsi yang berbeda dimana admin dapat mengolah data Pariwisata, data Budaya dan data Kegiatan juga dapat melihat rating dari user. Sedangkan user hanya dapat melihat data Pariwisata, data Budaya, dan data Kegiatan, user (pengguna) juga dapat menginputkan Pengaduan.  
</p>  

<p><strong>2.1.2 Antarmuka pengguna</strong></p>
<tabel>

<tr>
	<td> 
		<img src="https://lh3.googleusercontent.com/-v-t8IV4jr_8/WrxeBxxT9XI/AAAAAAAAFHw/4-hoVJHvdnsy-sYFAI50M9rJBzh_xTbAACL0BGAs/w323-d-h574-n-rw/login.PNG=s50" alt="Login">
	</td>
	<td>
		<img src="https://lh3.googleusercontent.com/-Aok2SDQOz7A/WrxeGLffE3I/AAAAAAAAFII/lPAFORL5QgoBw70FcvM6gUsTjiY3Bi3mgCL0BGAs/w321-d-h571-n-rw/register.PNG=50" alt="Register">
	</td>
	<td>  
		<img src="https://lh3.googleusercontent.com/-MC1SiWHzI_I/WrxhLHgv5iI/AAAAAAAAFJw/B8SgdKkuQVA633uc4oOXAfpCsYBSsgM9gCL0BGAs/w321-d-h571-n-rw/home.PNG=s50" alt="Home">
	</td>
</tr>


<tr>
	<td>  
		<img src="https://lh3.googleusercontent.com/-G3t4tU0M-vY/WrxeLkfMMlI/AAAAAAAAFIg/NtfvaM9x4BgQp9xg72zZk2tNG627BMhegCL0BGAs/w324-d-h576-n-rw/menupariwisata.PNG=s50" alt="Menu Pariwisata">
	</td>
	<td>  
		<img src="https://lh3.googleusercontent.com/-P2tbYWIjrf0/WrxmS7TBTEI/AAAAAAAAFRA/9qNvn9OpF-cfmqow1hBzkZAxQV0QSBeUgCL0BGAs/w325-d-h578-n-rw/wisatabuatan.PNG=s50" alt="Wisata Buatan">
	</td>
	<td>  
		<img src="https://lh3.googleusercontent.com/-2ngpR7mOoc4/WrxmNYgl8GI/AAAAAAAAFQg/vUdVJzR0kFELpXSNi1j-bGa1RvGGNqzYgCL0BGAs/w325-d-h578-n-rw/wisataalam.PNG=s50" alt="Wisata Alam">
	</td>
</tr>


<tr>
	<td>  
		<img src="https://lh3.googleusercontent.com/-oby_ANNDw8w/WrxltglVRUI/AAAAAAAAFO0/_pqT3PkayrEP-QXLuEgNLURQE7RGskW7ACL0BGAs/w326-d-h580-n-rw/kuliner.PNG=s50" alt="Kuliner">
	</td>
	<td>  
		<img src="https://lh3.googleusercontent.com/-lpI_4v-I_pU/Wrxl8iwBXSI/AAAAAAAAFPs/6EbnVw0Jw3AndgNA4ob0xvB0nGYHIIvZQCL0BGAs/w326-d-h580-n-rw/restodankafe.PNG=s50" alt="Resto Kafe">
	</td>
	<td>  
		<img src="https://lh3.googleusercontent.com/-DJV9QCIrW9s/WrxmfRy3IBI/AAAAAAAAFRc/D_aZiy0fzQ0mwAFmt1HR_mCG2-zQVKZNwCL0BGAs/w319-d-h567-n-rw/travel.PNG=s50" alt="Travel">
	</td>
</tr>


<tr>
	<td>  
		<img src="https://lh3.googleusercontent.com/-sz7Xx08oNQ0/WrxiFPC0j_I/AAAAAAAAFMI/wtOVuxiKMtoT9xQJIcjEek4UfuNnvSdLACL0BGAs/w325-d-h578-n-rw/hotel.PNG=s50" alt="Hotel">
	</td>
	<td>  
		<img src="https://lh3.googleusercontent.com/-cOUIct6zf1g/WrxhYXMbvUI/AAAAAAAAFKg/N-PMpAzALIUhMZCpjNryO1h9V1pSXaFTwCL0BGAs/w325-d-h578-n-rw/budaya.PNG=s50" alt="Budaya">
	</td>
	<td>  
		<img src="https://lh3.googleusercontent.com/-D1sIPNSm-JQ/Wrxi6Zcq0aI/AAAAAAAAFN8/EEvClA8HMlQRNVq87xH1polstTeWfvTvgCL0BGAs/w327-d-h581-n-rw/kegiatan.PNG=s50" alt="Kegiatan">
	</td>
</tr>


<tr>
	<td>  
		<img src="https://lh3.googleusercontent.com/-fWT3tYKw-Nw/WrxlylWm78I/AAAAAAAAFPM/yfsT-UNYVpYaz7u65_TDLYYD2aBwOfgcQCL0BGAs/w318-d-h565-n-rw/navbar.PNG=s50" alt="Navbar">
	</td>
	<td>  
		<img src="https://lh3.googleusercontent.com/-EoUFpmLvacY/WrxhsuuVHrI/AAAAAAAAFLo/I5Xf6THB_fon0PMwuUkSdX1av-uMegn2gCL0BGAs/w325-d-h578-n-rw/lihatdetail.PNG=s50" alt="Lihat Detail">
	</td>
	<td>  
		<img src="https://lh3.googleusercontent.com/-7qe8DcuSU1o/Wrxhi6RtElI/AAAAAAAAFLQ/FeT-6TXupZsXBoaCm29vi4p6b9eCK-G-ACL0BGAs/w324-d-h576-n-rw/disbudpar.PNG=s50" alt="Disbudpar">
	</td>
</tr>


<tr>
	<td>  
		<img src="https://lh3.googleusercontent.com/-03pj6Uh6_Jg/WrxoM7jYqOI/AAAAAAAAFTM/3UoYbmZd9I02RV3hl7jKLalskjggS6M6gCL0BGAs/w324-d-h576-n-rw/profilsaya.PNG=s50" alt="Profil User">
	</td>
	<td>  
		<img src="https://lh3.googleusercontent.com/-QULfNIB-2FQ/WrxoVVed3TI/AAAAAAAAFTk/wMe6Wrxa9bIIOioT37w3UKM93bvOaRn9QCL0BGAs/w328-d-h583-n-rw/ubahprofil.PNG=s50" alt="Ubah Profil">
	</td>
	<td>  
		<img src="https://lh3.googleusercontent.com/-v8Clqxh99Xc/Wrxoe-pMQ4I/AAAAAAAAFT8/RIvKjn6m1psm5kC4BQIY3_x3-8xbBLXegCL0BGAs/w326-d-h580-n-rw/pengaduan.PNG=s50" alt="Pengaduan">
	</td>
</tr>
</tabel>

<p>Admin (Web)</p>  
<ul>  
<li>  

![enter image description here](https://1.bp.blogspot.com/-nvGn9mg6Xuk/Wrx7p98XJ5I/AAAAAAAAAGg/mCrwzN3lrcQuy-bTpMZM-1Nq2sKIXOqfwCLcBGAs/s1600/mockup+admin.png)

</li>  
<li>   

![enter image description here](https://3.bp.blogspot.com/-hyHUGcT59XU/Wrx7u8FvvoI/AAAAAAAAAGk/_T1XweYaAlYEw311WQIE53sUayoeRf3OACLcBGAs/s1600/mock+up+admin+register.png)


![enter image description here](https://3.bp.blogspot.com/-GTj7yXPAFgc/Wrx7zAmpQaI/AAAAAAAAAGo/eEUwwlL_oFQstjThwmNzkWhZ13l5CyDGgCLcBGAs/s1600/mock+up+admin+dashboard.png)

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
<img src="https://lh3.googleusercontent.com/ehBEvX4NdXWCtnGhlGEnP_VxTDyeZNUbVIH75Y9GSg-HNMU90e8VDJGy9wCEH2Vzhj53agFiIi_55FuT4-jV_eV8nK5O2M0A6NB7gDmm4XrjH3ujSIkk1R3z7ByJquaLrZ5WPwkTkuLcJSGrb00r1For9J9Ha0kjh2ug8HMb1spHZquslruF3r0YHco6DSvO8HhFR8hAJdvJEw3GNYPI_iz66tgx__A0hh_rmO-IDbAJm2k03PICacQ84109dqHZquiRu3HvA3xOA4UQ9l3wzcbhDEIn_n2fGA8vPEj5dsh0ZVl6zEFrT3Qdap5mZxyRV2rqTfRGakG4X-TvLkxSZCYY-5Jf5QAMZuf3D7ZDOvHzuHjs34fviX_a6kmRovCdqVETHIjlh7678H_LGtsOmyYZ8U6XRkmnoRQo7VLlMXPwaYnDtNku80w-vcrXWnYPs8tPwjDyid2vQH-Z71y61_9X7WvMPYwNwEHUuhkN5Rdb6rlrk0qiRuEx_g_F7jJ-ZjgSNgeeRs_2QMg5P-WbY0VUw1AWRPqLegZvL2oGwsvt_B9Oeg6p5IQzQZfqcFZTEHbF-EGiXfx4tgMyMD-eYqWMKinBVW_pKP0rz-k=w848-h662-no" alt="usecase" title="usecase keseluruhan"><br>
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
<strong>2.2.4 User Melihat Kegiatan</strong><br>
<p>Use case: melihat kegiatan<br>
Diagram:</p>
<p><img src="https://lh3.googleusercontent.com/lyNCYrzxpvZ9qBUOtZ3yco75f11lEAJOpGd_Pjv9Vn8dB_k9dOTs-zE1xoZzhM2jXTREY0eQVwVBPnuPcfGyPwQL-0S6m7g53b2YADKt2K275vFQAktXWB6HMDVL0l51Z2CPftd2ighvId3JJM2gSYMKWg-sPjj2tp7Vzc5Wf3WLZifNjzSwfUo5_S2zZ0tCiJiX2XZR0oYJ3f89Fu_dHPSir1_9uDZWtlQ6ndKwp5xt6SDdatPon2f-ewlhgAv2uN3RyFIiEYz14bjueTfsq_E4RkUbACBBpVPqkalcq2WwN0YYXAtXic3oXvmt2ZaqcNNoxqpszSSL6SGXLnHNdc8DfZ4MFkDeyprzZZOwVhUkk2K_ZACFMvwKtHgZ6YZbaUudHG_KdC1GEndSDT2l3jg5BmNS9fyPanNQRspZHC3aSJxvD9Ha6vPt6gjR0f39NTBdRn1sD9TYOs9VyNtgq3xJw2IDgdbj-nbsVOoK4QXca-xQp4oORrxAE5TVmFXwk6M1ZVWZkLsACFa4IkA8YU-9MxOHmkrwBdTMG6afi2NMpAmPWMQ-MuMPd5H8OoEFnFUTWMoQdK4vRgH-ilJg3G41itKYI35Fdd2pyfM=w179-h105-no" title="userkegiatan"></p>
<p>Deskripsi singkat ketika user melihat kegiatan:
</p><ol>
<li>Sistem menampilkan halaman utama yang berisi button kegiatan</li>
<li>User dapat mengklik tombol button kegiatan</li>
<li>Sistem menampilkan data kegiatan</li>
</ol>
Xref: Bagian 3.2.4, User lihat kegiatan<p></p>
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
<strong>2.2.7 Admin Mengelola Budaya</strong><br>
<p>Use case: mengelola budaya<br>
Diagram:</p>
<p><img src="https://lh3.googleusercontent.com/xSS8q_wIeplS5M-OcYlWfEq271VOWEf4cHrRfzlNdmubHjA9ddjss8Znh9fbJF-t2SXqK3Jcd1TDrJn-3scsylV6ClVY3D9sebCiwPlTko_vQ14GETwd94c3mx5r-HHv3_GfUYursL4j7cpq8Q3f9YYhepnEGx8vR0Otkvc6Nt0A_kqewV9QyYxyWUBRiamm6MFUJyu-ARPg4tZYyQHJH-Rk81XFJiLZNlWYZkzlDVMqKNNO_EC0MWVOe9wi8htgYglPnh9Upu-VCW8i-Z75VhTVK8xWUbNBUJonCtkOoFaz_4N8cjQVEyOODB5BtPEYC53xKkSMUvTdnIfmccn2ud0QMghCBHehWvMf-GYVKmPkk-ic1jZbkCd5J7RWd6MBIWclMoZmYL0OAhGMRo0hORaGT9o65E1IHkAjuUvDTEy1WmLIFTtsFe7t5wXXBZLLS3moOIHFxNr6p4zpUtWahmbuZhlkiR_SgW1iQPL4o9JpdE76_aVVmBuscvpor-OyyZ63N9izyK6LCrQnDeyh1qJKzuetZK3pbup0U7xhPNK8HPev3rIILayGc9fjW141XUpv4foFy1F3lu6OdeKK4oiGGWJKjfAhSP0vt4E=w162-h94-no" alt="enter image description here" title="adminbuat"></p>
<p>Deskripsi singkat ketika admin mengelola budaya:
</p><ol>
<li>Sistem menampilkan dasboard admin</li>
<li>Admin memilih menu budaya pada sidebar</li>
<li>Admin mengelola data budaya</li>
<li>Sistem akan mengirim data ke database</li>
</ol>
Xref: Bagian 3.2.7, Admin mengelola budaya<p></p>
<strong>2.2.8 Admin Mengelola Pariwisata</strong><br>
<p>Use case: mengelola pariwisata<br>
Diagram:</p>
<p><img src="https://lh3.googleusercontent.com/B2XfAkVd4a5v2kGHOJ4MXapAhDcALgrCNxIcNHMk5-AG8j91rQUYhc5YDVYceK4M-CUt4bMu-K48wBvHDJeA9Ozlei-d-jJGpvLftS_wseE_yK4034IxX38iJkrJ6eleKSrDtHDpE3Q09-Bg9NtwMWn-1f0harkuaaQnnAvYV6glIpEMmMxyx4_G0mH6tgpM5J198m6yeeK9UvWc00H7cTJI18EpCCMHwPtAt_TFyGMEWc5gJNHovoO3e3DuZKoG9H7_1Kgr6RyEm1WEh6rUfvvH-zKfMb882kMfBV8RfBuFX8scaD1_Is5jN7Hh2z3vUlTnLLWTycC6D4FZKwv-MclvsCQM58SMG1Hua260U9qxI9BOplLs2cHgM-7ka1vdVrH36NMO6Kl7-JL3Mi2bdRRyPkozfIOglY-_2inbcQafUuGUE_VLxiVyfDQjYsg5ixlodpRxeZSRx_i4VUy3fKyMdjB38nGtmeDUg0Ru4Hn3F3eRr16NCNl2QWSjdblJIcU8D04UUxoz_t93JYuvEhg30MS6Fu6YIV6tRkhS8RFw-s4eplwePWUfQCPXuNGNgzCQ9oGNkdji363Q_RoTuZwZs2PzbScVqrcJv88=w169-h99-no" alt="enter image description here" title="adminedit"></p>
<p>Deskripsi singkat ketika admin mengelola pariwisata:
</p><ol>
<li>Sistem menampilkan dasboard admin</li>
<li>Admin memilih menu pariwisata pada sidebar</li>
<li>Admin mengelola data pariwisata</li>
<li>Sistem akan mengirim data ke database</li>
</ol>
Xref: Bagian 3.2.8, Admin Mengelola Pariwisata<p></p>
<strong>2.2.9 Admin Mengelola Kegiatan</strong><br>
<p>Use case: mengelola kegiatan<br>
Diagram:</p>
<p><img src="https://lh3.googleusercontent.com/9qeCLeGOA7QEl7FcPbgmsHlXbsbRrzfeJ9UI6eZAET_0KWogt9-MfICAc7YzQvQE5K4DrIM5CVToMtCrvg3YZkyWo0qz8URZkcTRMMsCKGlBobRb5xmlEQR-O1ZycZyOL-rUBm4nk5D_FnqmOLOljwCltsgLu-_B4FGPIid24DaYA3_5Lj0qXYKOB9JdM4LpsmTOIsQPRjAN06x9n1cw_cQSs_9wWDCtiz7rRa_48wXzdPS8QnbnpnJKX-qIl46kZyIZSc98fvVnXfJ-uPygArIS1hVvgNQ27b5P_-dATtkUlj2wTram_cdcynI28QlxdZDjhoERhcXY_Xs50y8QMk5CFc6Wj-GkH1UEwCMLWl__NIyRWZLSnmsBi_bQcEoivp-jx1gR3pWKH-T6_yeOl9lzD4XW5L-U3IB0A5BvWn-0iLFXcnONL_ELbAiaah71pe2w_H4hUnONieHCFsaRouz_BSxu3r0Z7Iwva35Pw2ntrfMHuSvxo9kV7XD1PJKR-O1gQOCkK8MD_3JSPxp_9WVV0_J_mULFwz7EngibqXTRvH3b5oPrXsWdy2-P9cS2sDIbLEqqAXITShmIEZlZ3TOJSCmwp1fJSCNY4hM=w174-h94-no" alt="enter image description here" title="adminhapus"></p>
<p>Deskripsi singkat ketika admin mengelola kegiatan:
</p><ol>
<li>Sistem menampilkan dasboard admin</li>
<li>Admin memilih menu kegiatan pada sidebar</li>
<li>Admin mengelola data kegiatan</li>
<li>Sistem akan mengirim data ke database</li>
</ol>
Xref: Bagian 3.2.9, Admin mengelola kegiatan<p></p>
<strong>2.2.10 Admin Mengelola Pengaduan</strong><br>
<p>Use case: mengelola pengaduan<br>
Diagram:</p>

<p><img src="https://lh3.googleusercontent.com/u7H0T2YsqO9p9TIoz1cMo0x-5UKLvE79iNkzOvieNoU_GNzHYGyZM0NiTz_-C6UsP-KZzpvaPYwFcgel8-fL3HhFROZNE8o4y8Jc_M6p5An_sS8AqhcAajCVYgYJ4SNckJnFGCv6t6SOIFPlz9T0IOj5r2uKLgpRsYc3V-KxtY1vRZ1pNioAHF2oGi0v-6dZPTzkVtZB2_1v4lzK1VwV6mdt2rFHwVkhTpol-3RdcE1z1F-2h_3k7QTRwBLXmLX5rWRZJR_62GY4nYLtMAc25sK7Vp3Uqiy9YzWiilDadFHRqTn2WqYdclm1bWYBkkCogB73gdBO9rK0nxwGN94we57O0vMZLjjQZ632aj7T6pgev-oYP6qa3LoGhmEsjV9UgxwGYd-_f7HSQ3Ci1Trn7bWpSrjoW2-_7MGgnhBlSB6A5z73N_II2D6bkaAd_Z-A4FBWdH9KjCDeopJBeEXKTXxRmKZEUd0pn2MlVKgQppWdtgXBypEMuubERz6rI8X6Q3NcKffvuHY9Jt5Rvhw8X_oq3jwLwlQ90YfDK9gnjjQH1OlHh65on40MEJIx_DF5FLlCl3c5GK2YPuX1nOt1Z_ZztyRBbIWN4MHMV0w=w173-h98-no" alt="enter image description here" title="adminpengaduan"></p>

<p>Deskripsi singkat ketika admin mengelola pengaduan:
</p><ol>
<li>Sistem menampilkan dasboard admin</li>
<li>Admin memilih menu pengaduan pada sidebar</li>
<li>Admin mengelola data pengaduan</li>
<li>Sistem akan mengirim data ke database</li>
</ol>
Xref: Bagian 3.2.10, Admin mengelola pengaduan<p></p>
<strong>2.2.11 Admin Mengelola user</strong><br>
<p>Use case: mengelola user<br>
Diagram:</p>
<p><img src="https://lh3.googleusercontent.com/Jce_-au0vBFu-iMwrQjD2DHAuepDksWesLzKQ95BW7nwae_etvKHbwRwi_Ayp52wVjyupUxLbYCQ8LYUrrVsP5QX4C-tvmwFnJWemGE3_9LG19tkaV6kWxjeD7-ivYOWa3l8uTuDwa9xUj2fm4fnijwjIJZP37f_anF-VyXEtKw6SFkcOIwqmznRE3aIJLEIorQB0Dt2-sI9UkbTgiNfp226K3Fi2-xrSwYjTYSAJNUqXC1uD5BNBFPBZ12AnxHVpx7qIhjwiSh7buA4WizADphRTOrNNONieajsLyO-KlT0iz702iqUkJ-gGYm_NNdZUPKXRFCHK2pUx25Q-o_6Ae1ZTNELJ8bLitD5_yEC22komnmVUa7M-5EjMgyE0iZlxae5GPfjCeKjcyJkxAxzegdrU29UoIKsu2ViVo6Hp9ifKgFW8B2N7B1aQwdpdk_T-Y1leaAYDTqj6xRxX76t6Rn2TuhcD4g3uGIIU-KY14qF8vD5m9NCbR4enRH-eFLZDUhWKR7Xl7z4NrjK9G-OXV-toa-BnxCT2vpVBtRH4p0TmNCLr9k4tJh0uv1U1WOTXYwEWM0sJ5HrgBD_9FR_oFRoJO6vnQBOfLvN91k=w191-h104-no" title="adminmengelolauser"></p>
<p>Deskripsi singkat ketika admin mengelola user:
</p><ol>
<li>Sistem menampilkan dasboard admin</li>
<li>Admin memilih menu user pada sidebar</li>
<li>Admin mengelola data user</li>
<li>Sistem akan mengirim data ke database</li>
</ol>
Xref: Bagian 3.2.11, Admin mengelola user<p></p>
<strong>2.2.12 User Mengedit User</strong><br>
<p>Use case: mengedit user<br>
Diagram:</p>
<p><img src="https://lh3.googleusercontent.com/ZolJVxjQqbIUZIWxUglZOgRQfu6EHtApsMXX7mW4Nx6Qyrg6e_pxp7qsIBE96-db4Hkgb6DOMLWDJyxxf3dU2U-lUSl5ijrevVfEvCEgQJVpZ_TGgo92hqv4IbYHtwa0qCUNBWtqzam-KUCgI_rZzhqcVywBlMmcKnEYVcpoI3SZIweS4_U4pk537otoRZhDczRQAcmSr4wn-N-Oc8x6UthoDqb_k5hPblX7fihc3NPC6j_RP-HGRNkcO6LQ2Ypqts9ahsyN2uy42sRTV-VG1oN8j6EKrG9RKRNjF_9Nr6DgjH0L1uPfwz-G5lSLCkgdCiTEZgqM7xGVUWECK57iLk2gC_yoigpH-LCwPkoPs2wQhfp6LlhIWhVQtmeq2zoTJgav7b4g6PEP3DEimohowuwI2_E0Bzp_iXRt-iWFOXYTWx1oN_DDHPMtjSwfSwJIUxK30a5d9JSKmZKbDfJJG5p0w3T6t1ShMJM_5D2OZgypxQ1ad3NCqUngLt7vqVLajqz5cZNaHZBqFBnkxgTHcRELfMUCwCFMGQBVS-nT3QoW5BIgWU4l_WnaIG6Qadx7yfjcQspv6Pv4ovQqxUypvq09BYUZKVQIwXCgBbU=w190-h102-no" title="adminmengelolauser"></p>
<p>Deskripsi singkat ketika user mengedit user:
</p><ol>
<li>Sistem menampilkan halaman utama yang berisi button budaya</li>
<li>user menekan tombol navigasi</li>
<li>User memilih profil saya</li>
<li>User memilih ubah profil</li>
<li>User mengedit dat profil</li>
<li>Sistem akan mengirim data ke database</li>
</ol>
Xref: Bagian 3.2.12, User Mengedit User<p></p>
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
<p><strong>3.2.4 User Melihat Kegiatan</strong></p>  
<table>  
<thead>  
<tr>  
</tr>  
</thead>  
<tbody>  
<tr>  
<td>Nama Fungsi</td>  
<td>User Melihat Kegiatan</td>  
</tr>  
<tr>  
<td>Ref</td>  
<td>Bag 2.2.4 User Melihat Kegiatan</td>  
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
<li>User mengklik button kegiatan</li>
<li>Sistem menampilkan data kegiatan</li>
</ol>
</td>  
</tr>  
<tr>  
<td>Alternative</td>  
<td> Tidak ada</td>  
</tr>  
<tr>  
<td>Post Condition</td>  
<td>User melihat kegiatan</td>  
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
<p><strong>3.2.6 Admin Login</strong></p>  
<table>  
<thead>  
<tr>  
</tr>  
</thead>  
<tbody>  
<tr>  
<td>Nama Fungsi</td>  
<td>Admin Login</td>  
</tr>  
<tr>  
<td>Ref</td>  
<td>Bag 2.2.6 Admin Login</td>  
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
</p><ol>
<li>Sistem menampilkan dasboard admin</li>
<li>Admin memilih menu budaya pada sidebar</li>
<li>Admin mengelola data budaya</li>
<li>Sistem akan mengirim data ke database</li>
</ol>
</ol>
</td>  
</tr>  
<tr>  
<td>Alternative</td>  
<td> Tidak ada</td>  
</tr>  
<tr>  
<td>Post Condition</td>  
<td>Halaman Dashboard Admin</td>  
</tr>  
<tr>  
<td>Exception Push</td>  
<td> Tidak ada koneksi</td>  
</tr>  
</tbody>   
</table>
<p><strong>3.2.7 Admin Mengelola Budaya</strong></p>  
<table>  
<thead>  
<tr>  
</tr>  
</thead>  
<tbody>  
<tr>  
<td>Nama Fungsi</td>  
<td>Admin Mengelola Budaya</td>  
</tr>  
<tr>  
<td>Ref</td>  
<td>Bag 2.2.7 Admin Mengelola Budaya</td>  
</tr>  
<tr>  
<td>Trigger</td>  
<td>Admin masuk Aplikasi Budaya dan Pariwisata </td>  
</tr>  
<tr>  
<td>Precondision</td>  
<td>Halaman Dashboard Admin</td>  
</tr>  
<tr>  
<td>Basic Path</td>  
<td>
<p><ol>
<li>Sistem menampilkan dasboard admin</li>
<li>Admin memilih menu pariwisata pada sidebar</li>
<li>Admin mengelola data pariwisata</li>
<li>Sistem akan mengirim data ke database</li>
</ol>
</ol>
</td>  
</tr>  
<tr>  
<td>Alternative</td>  
<td> Tidak ada</td>  
</tr>  
<tr>  
<td>Post Condition</td>  
<td>Mengklik menu Budaya</td>  
</tr>  
<tr>  
<td>Exception Push</td>  
<td> Tidak ada koneksi</td>  
</tr>  
</tbody>   
</table>
<p><strong>3.2.8 Admin Mengelola Pariwisata</strong></p>  
<table>  
<thead>  
<tr>  
</tr>  
</thead>  
<tbody>  
<tr>  
<td>Nama Fungsi</td>  
<td>Admin Mengelola Pariwisata</td>  
</tr>  
<tr>  
<td>Ref</td>  
<td>Bag 2.2.8 Admin Mengelola Pariwisata</td>  
</tr>  
<tr>  
<td>Trigger</td>  
<td>Admin masuk Aplikasi Budaya dan Pariwisata </td>  
</tr>  
<tr>  
<td>Precondision</td>  
<td>Halaman Dashboard Admin</td>  
</tr>  
<tr>  
<td>Basic Path</td>  
<td>
</p><ol>
<li>Sistem menampilkan dasboard admin</li>
<li>Admin memilih menu kegiatan pada sidebar</li>
<li>Admin mengelola data kegiatan</li>
<li>Sistem akan mengirim data ke database</li>
</ol>
</ol>
</td>  
</tr>  
<tr>  
<td>Alternative</td>  
<td> Tidak ada</td>  
</tr>  
<tr>  
<td>Post Condition</td>  
<td>Mengklik menu Pariwisata</td>  
</tr>  
<tr>  
<td>Exception Push</td>  
<td> Tidak ada koneksi</td>  
</tr>  
</tbody>   
</table>
<p><strong>3.2.9 Admin Mengelola Kegiatan</strong></p>  
<table>  
<thead>  
<tr>  
</tr>  
</thead>  
<tbody>  
<tr>  
<td>Nama Fungsi</td>  
<td>Admin Mengelola Kegiatan</td>  
</tr>  
<tr>  
<td>Ref</td>  
<td>Bag 2.2.9 Admin Mengelola Kegiatan</td>  
</tr>  
<tr>  
<td>Trigger</td>  
<td>Admin masuk Aplikasi Budaya dan Pariwisata </td>  
</tr>  
<tr>  
<td>Precondision</td>  
<td>Halaman Dashboard Admin</td>  
</tr>  
<tr>  
<td>Basic Path</td>  
<td>
</p><ol>
<li>Sistem menampilkan dasboard admin</li>
<li>Admin memilih menu kegiatan pada sidebar</li>
<li>Admin mengelola data kegiatan</li>
<li>Sistem akan mengirim data ke database</li>
</ol>
</ol>
</td>  
</tr>  
<tr>  
<td>Alternative</td>  
<td> Tidak ada</td>  
</tr>  
<tr>  
<td>Post Condition</td>  
<td>Mengklik menu Kegiatan</td>  
</tr>  
<tr>  
<td>Exception Push</td>  
<td> Tidak ada koneksi</td>  
</tr>  
</tbody>   
</table>

<p><strong>3.2.10 Admin Mengelola Pengaduan</strong></p>  
<table>  
<thead>  
<tr>  
</tr>  
</thead>  
<tbody>  
<tr>  
<td>Nama Fungsi</td>  
<td>Admin Mengelola Pengaduan</td>  
</tr>  
<tr>  
<td>Ref</td>  
<td>Bag 2.2.10 Admin Mengelola Pengaduan</td>  
</tr>  
<tr>  
<td>Trigger</td>  
<td>Admin masuk Aplikasi Budaya dan Pariwisata </td>  
</tr>  
<tr>  
<td>Precondision</td>  
<td>Halaman Dashboard Admin</td>  
</tr>  
<tr>  
<td>Basic Path</td>  
<td>
</p><ol>
<li>Sistem menampilkan dasboard admin</li>
<li>Admin memilih menu pengaduan pada sidebar</li>
<li>Admin mengelola data pengaduan</li>
<li>Sistem akan mengirim data ke database</li>
</ol>
</ol>
</td>  
</tr>  
<tr>  
<td>Alternative</td>  
<td> Tidak ada</td>  
</tr>  
<tr>  
<td>Post Condition</td>  
<td>Mengklik menu Pengaduan</td>  
</tr>  
<tr>  
<td>Exception Push</td>  
<td> Tidak ada koneksi</td>  
</tr>  
</tbody>   
</table>
<p><strong>3.2.11 Admin Mengelola User</strong></p>  
<table>  
<thead>  
<tr>  
</tr>  
</thead>  
<tbody>  
<tr>  
<td>Nama Fungsi</td>  
<td>Admin Mengelola User</td>  
</tr>  
<tr>  
<td>Ref</td>  
<td>Bag 2.2.11 Admin Mengelola User</td>  
</tr>  
<tr>  
<td>Trigger</td>  
<td>Admin masuk Aplikasi Budaya dan Pariwisata </td>  
</tr>  
<tr>  
<td>Precondision</td>  
<td>Halaman Dashboard Admin</td>  
</tr>  
<tr>  
<td>Basic Path</td>  
<td>
</p><ol>
<li>Sistem menampilkan dasboard admin</li>
<li>Admin memilih menu user pada sidebar</li>
<li>Admin mengelola data user</li>
<li>Sistem akan mengirim data ke database</li>
</ol>
</ol>
</td>  
</tr>  
<tr>  
<td>Alternative</td>  
<td> Tidak ada</td>  
</tr>  
<tr>  
<td>Post Condition</td>  
<td>Mengklik menu User</td>  
</tr>  
<tr>  
<td>Exception Push</td>  
<td> Tidak ada koneksi</td>  
</tr>  
</tbody>   
</table>
<p><strong>3.2.12 User Mengedit User </strong></p>  
<table>  
<thead>  
<tr>  
</tr>  
</thead>  
<tbody>  
<tr>  
<td>Nama Fungsi</td>  
<td>User Mengedit User</td>  
</tr>  
<tr>  
<td>Ref</td>  
<td>Bag 2.2.12 User Mengedit User</td>  
</tr>  
<tr>  
<td>Trigger</td>  
<td>Admin masuk Aplikasi Budaya dan Pariwisata </td>  
</tr>  
<tr>  
<td>Precondision</td>  
<td>Halaman Dashboard</td>  
</tr>  
<tr>  
<td>Basic Path</td>  
<td>
</p><ol>
<li>Sistem menampilkan halaman utama yang berisi button budaya</li>
<li>user menekan tombol navigasi</li>
<li>User memilih profil saya</li>
<li>User memilih ubah profil</li>
<li>User mengedit dat profil</li>
<li>Sistem akan mengirim data ke database</li>
</ol>
</ol>
</td>  
</tr>  
<tr>  
<td>Alternative</td>  
<td> Tidak ada</td>  
</tr>  
<tr>  
<td>Post Condition</td>  
<td>Mengklik menu User</td>  
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

![enter image description here](https://2.bp.blogspot.com/-hfelCSzK5rI/Wrx6v882vbI/AAAAAAAAAGY/B5uJQnEl3QcOlqK3IpiNAGmo0CLzY0yYgCLcBGAs/s1600/ERD00000000.jpg)


<p>Pada ERD terdapat tabel admin, tabel user, tabel pariwisata, tabel budaya, tabel event dan tabel ratting.  </p>

<ul>
<li>
<p><strong>Tabel admin</strong></p>
</li>
</ul>
<table>
<tr>  
<td><strong>Data Item</strong></td>  
<td><strong>Type</strong></td>  
<td><strong>Deskripsi</strong></td>
</tr>  
<tr>  
<td>id_admin</td>  
<td>Integer</td>  
<td>Nomor auto increment Id_admin</td>    
</tr>  
<tr>  
<td>username</td>  
</td> 
<td>Varchar</td>   
<td>Nama atau nomor untuk dapat mengakses aplikasi</td>   
</tr>  
<tr>  
<td>password</td>  
</td> 
<td>Varchar</td>   
<td>Berisi password untuk dapat mengakses aplikasi </td>   
</tr>  
<tr>  
<td>nama_admin</td>  
</td> 
<td>Varchar</td>   
<td>Untuk login dan mengetahui nama admin </td>   
</tr>   
</table>

<ul>
<li>
<p><strong>Tabel User</strong></p>
</li>
</ul>
<table>
<tr>  
<td><strong>Data Item</strong></td>  
<td><strong>Type</strong></td>  
<td><strong>Deskripsi</strong></td>
</tr>  
<tr>  
<td>id_user</td>  
<td>Integer</td>  
<td>Nomor auto increment Id_user</td>    
</tr>  
<tr>  
<td>username</td>  
</td> 
<td>Varchar</td>   
<td>Berisi Nama atau nomor untuk dapat mengakses aplikasi</td>   
</tr>  
<tr>  
<td>password</td>  
</td> 
<td>Varchar</td>   
<td>Berisi password untuk dapat mengakses aplikasi </td>   
</tr>  
<tr>  
<td>nama_user</td>  
</td> 
<td>Varchar</td>   
<td>Untuk login dan mendaftar aplikasi </td>   
</tr>   
<tr>  
<td>email</td>  
</td> 
<td>Varchar</td>   
<td>Berisi alamat email user  </td>   
</tr>   
</table>

<ul>
<li>
<p><strong>Tabel Budaya</strong></p>
</li>
</ul>
<table>
<tr>  
<td><strong>Data Item</strong></td>  
<td><strong>Type</strong></td>  
<td><strong>Deskripsi</strong></td>
</tr>  
<tr>  
<td>id_budaya</td>  
<td>Integer</td>  
<td>Nomor auto increment Id_budaya</td>    
</tr>    
<tr>  
<td>nama</td>  
</td> 
<td>Varchar</td>   
<td>Berisi nama budaya </td>   
</tr>   
<tr>  
<td>deskripsi</td>  
</td> 
<td>Varchar</td>   
<td>Berisi deskripsi tentang budaya  </td>   
</tr>   
<tr>  
<td>gambar</td>  
</td> 
<td>Varchar</td>   
<td>Berisi gambar kebudayaan  </td>   
</tr>   
</table>

<ul>
<li>
<p><strong>Tabel Pariwisata</strong></p>
</li>
</ul>
<table>
<tr>  
<td><strong>Data Item</strong></td>  
<td><strong>Type</strong></td>  
<td><strong>Deskripsi</strong></td>
</tr>  
<tr>  
<td>id_pariwisata</td>  
<td>Integer</td>  
<td>Nomor auto increment Id_pariwisata</td>    
</tr>    
<tr>  
<td>nama</td>  
</td> 
<td>Varchar</td>   
<td>Berisi nama pariwisata </td>   
</tr>   
<tr>  
<td>deskripsi</td>  
</td> 
<td>Varchar</td>   
<td>Berisi deskripsi tentang pariwisata  </td>   
</tr>   
<tr>  
<td>gambar</td>  
</td> 
<td>Varchar</td>   
<td>Berisi gambar pariwisata  </td>   
</tr>  
<tr>  
<td>id_jenis</td>  
</td> 
<td>Integer</td>   
<td>Sebagai foreign key pada tabel pariwisata  </td>   
</tr>   
</table>


<ul>
<li>
<p><strong>Tabel Jenis Pariwisata</strong></p>
</li>
</ul>
<table>
<tr>  
<td><strong>Data Item</strong></td>  
<td><strong>Type</strong></td>  
<td><strong>Deskripsi</strong></td>
</tr>  
<tr>
<td>id_jenis</td>  
<td>Integer</td>   
<td> Nomor auto increment pada tabel jenis pariwisata  </td>   
</tr>  
<tr>
<td>nama</td>  
<td>Varchar</td>   
<td>Sebagai foreign key pada tabel pariwisata </td>   
</tr>   
</table>

<ul>
<li>
<p><strong>Tabel Event</strong></p>
</li>
</ul>
<table>
<tr>  
<td><strong>Data Item</strong></td>  
<td><strong>Type</strong></td>  
<td><strong>Deskripsi</strong></td>
</tr>  
<tr>  
<td>Id_event</td>  
<td>Integer</td>  
<td>Nomor auto increment Id_event</td>    
</tr>    
<tr>  
<td>nama</td>  
</td> 
<td>Varchar</td>   
<td>Berisi nama event </td>   
</tr>   
<tr>  
<td>deskripsi</td>  
</td> 
<td>Varchar</td>   
<td>Berisi deskripsi tentang event</td>   
</tr>   
<tr>  
<td>tanggal</td>  
</td> 
<td>Date</td>   
<td>Berisi tanggal di adakannnya event  </td>   
</tr>   
</table>


<ul>
<li>
<p><strong>Tabel Pengaduan</strong></p>
</li>
</ul>
<table>
<tr>  
<td><strong>Data Item</strong></td>  
<td><strong>Type</strong></td>  
<td><strong>Deskripsi</strong></td>
</tr>  
<tr>  
<td>id_pengaduan</td>  
<td>Integer</td>  
<td>Nomor auto increment Id_pengaduan</td>    
</tr>    
<tr>  
<td>isi</td>  
</td> 
<td>Varchar</td>   
<td>Berisi pengaduan dari user</td>   
</tr>   
</table> 



