


<h1 align="center" id="software-requirements-specification">SOFTWARE REQUIREMENTS SPECIFICATION</h1>  
<p align="center"><strong>Version 1.8<br>28 Maret 2018</strong><br></p>

<p align="center">  
	<img src="https://lh3.googleusercontent.com/qEHYPVzo0kjd8ikhrCIF4cI_PhR8pmK5vDU14oEp9OPyVT-eA54cVp8C9iyJ8rKDfH8OR1dnT1zv=s300" alt="enter image description here" title="logo">  
</p>

<p align="center"><strong>Kelompok 5 D3TI2D</strong></p>  
<p align="center"><strong>Firsti Aulya K. K. (1603098)<br>  
Firmansyah (1603097) <br>  
Diyanti (1603094)<br>  
Rizky Alief Satria (1603111)</strong><br>  
</p>

<p align="center"><strong>Jurusan D3 Teknik Informatika<br>
Politeknik Negeri Indramayu<br>
2018</strong></p>

<h2><strong>1. PENDAHULUAN</strong></p></h2>
<h3><strong>1.1 Tujuan</strong></h3>  
<p>Tujuan dibuatnya dokumen SRS ini adalah untuk menjelaskan tentang spesifikasi kebutuhan apa saja yang digunakan pada Aplikasi BUSAYU (Budaya dan Pariwisata Kab. Indramayu) seperti Rancangan Sistem, Mockup, dan lain-lain.<br></p>

<h3><strong>1.2 Lingkup Masalah</strong></h3>  
<p>Sistem dari perangkat lunak ini akan menjadi Aplikasi Publik, yaitu aplikasi yang akan digunakan oleh masyarakat khusunya masyarakat Kab. Indramayu. BUSAYU (Aplikasi Budaya dan Pariwisata Kab, Indramayu) adalah salah satu aplikasi berbasis Android yang dirancang untuk mengetahui dan mempermudah pengguna untuk mencari informasi tentang kebudayaan, pariwisata, dan kegiatan yang ada di Indramayu. Lalu pengguna juga bisa mengajukan pengaduan tentang kebudayaan dan pariwisata di Indramayu.<br>  
</p> 

<h3><strong>1.3 Definisi, Akronim, Singkatan</strong></h3>  
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
<td>Sistem operasi berbasis Linux yang dirancang untuk perangkat bergerak layar sentuh seperti telepon pintar dan komputer tablet</td>  
</tr>  
<tr>  
<td>Kegiatan</td>  
<td>Sebuah rangkaian acara dalam rangka tujuan tertentu yang diadakan oleh pihak tertentu dalam waktu tertentu dan tempat tertentu dengan biaya tertentu</td>  
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
<td>Software Requirements Specification</td>  
</tr> 
<tr>  
<td>BUSAYU</td>  
<td>Aplikasi Budaya dan Pariwisata kab. Indramayu</td>  
</tr>
<tr>  
<td>IEEE</td>  
<td>(Singkatan : Institute of Electrical and Electronics Engineers) Sebuah organisasi profesi nirlaba yang terdiri dari banyak ahli di bidang teknik yang mempromosikan pengembangan standar-standar dan bertindak sebagai pihak yang mempercepat teknologi-teknologi baru dalam semua aspek dalam industri dan rekayasa (engineering), yang mencakup telekomunikasi, jaringan komputer, kelistrikan, antariksa, dan elektronika.</td>  
</tr>    
</tbody>  
</table>

<h3><strong>1.4 Referensi</strong><br></h3>
<ul>
	<li>IEEE. IEEE Std 830-1998 IEEE Recommended Practice for Software Requirements Specifications. IEEE Computer Society, 1998. 1.5 Overview
	</li>
</ul>

<h3><strong>1.5 Overview</strong><br></h3>  
<p>Dokumen ini dibagi menjadi tiga bagian utama. Bagian pertama berisi penjelasan tentang dokumen SRS yang mencakup tujuan pembuatan dokumen ini, lingkup masalah yang diselesaikan yang dikembangkan oleh kami yaitu definisi, referensi, dan deskripsi umum. Bagian kedua berisi penjelasan secara umum mengenai aplikasi yang akan di kembangkan meliputi fungsi, karakteristik pengguna, batasan dan asumsi yang diambil dalam pengembangan aplikasi.Bagian ke tiga berisi uraian aplikasi secara lebih rinci.<br><br></p>

<h2><strong>2. GAMBARAN UMUM</strong><br></h2>
<p>BUSAYU (Aplikasi Budaya dan Pariwisata Kab. Indramayu) Berbasis Android adalah aplikasi yang digunakan untuk mempermudah pengguna dalam pencarian informasi seputar kebudayaan, pariwisata, dan kegiatan di Kabupaten Indramayu.</p>

<h3><strong>2.1. Perspektif Produk</strong><br></h3>  
<p>Pada proyek ini dibuat dengan sistem berbasis Android dimana aplikasi ini bisa diakses hanya dengan smartphone dengan sistem operasinya adalah Android. Aplikasi ini dibangun dengan menggunakan Android Studio untuk aplikasi Android, Sublime Text untuk aplikasi web, dan XAMPP sebagai databasenya.<br></p>

<h4><strong>2.1.1 Antarmuka sistem</strong><br></h4>  
<p>
	<img src="https://4.bp.blogspot.com/-80n_0OxZZ_w/Wp-lcm-mUII/AAAAAAAAAEA/dLxdDnG38Z8zyk7PNIP3hgChXTJiDFZ4gCLcBGAs/s1600/sistem.png" alt="enter image description here"></p>
<p>Sistem dari perangkat lunak ini memiliki 2 aktor yaitu Admin dan User (Pengguna). Admin mengeloa aplikasi web sedangkan User menggunakan aplikasi Android. Setiap aktor mempunyai fungsi yang berbeda, dimana aplikasi web digunakan oleh Admin untuk mengelola data kebudayaan, pariwisata, kegiatan, dan lain-lain. Sedangkan Aplikasi Android digunakan oleh User untuk memperoleh informasi tentang kebudayaan, pariwisata, dan kegiatan serta mengajukan pengaduan.<br></p>  
</p>  

<h4><strong>2.1.2 Antarmuka pengguna</strong></h4>
<ul><li><strong>User (Android)</strong></li></ul>
<table>
<tr>
	<td>
		<ul><li>Login</li></ul> 
		<img src="https://lh3.googleusercontent.com/-v-t8IV4jr_8/WrxeBxxT9XI/AAAAAAAAFHw/4-hoVJHvdnsy-sYFAI50M9rJBzh_xTbAACL0BGAs/w323-d-h574-n-rw/login.PNG=s50" alt="Login">
		<p>Ini merupakan mockup dari halaman Login, dimana User harus menginputkan username dan password agar bisa Log In</p>
	</td>
	<td>
		<ul><li>Register</li></ul>
		<img src="https://lh3.googleusercontent.com/-Aok2SDQOz7A/WrxeGLffE3I/AAAAAAAAFII/lPAFORL5QgoBw70FcvM6gUsTjiY3Bi3mgCL0BGAs/w321-d-h571-n-rw/register.PNG=s50" alt="Register">
		<p>Ini merupakan mockup dari halaman Register, dimana jika User belum memiliki akun maka harus mengisi form Registrasi.</p>
	</td>
	<td>
		<ul><li>Home</li></ul>  
		<img src="https://lh3.googleusercontent.com/-MC1SiWHzI_I/WrxhLHgv5iI/AAAAAAAAFJw/B8SgdKkuQVA633uc4oOXAfpCsYBSsgM9gCL0BGAs/w321-d-h571-n-rw/home.PNG=s50" alt="Home">
		<p>Ini merupakan mockup dari halaman Home. Pada halama ini terdapat enam menu dan juga navigasi.</p>
	</td>
</tr>


<tr>
	<td> 
		<ul><li>Menu Pariwisata</li></ul> 
		<img src="https://lh3.googleusercontent.com/-G3t4tU0M-vY/WrxeLkfMMlI/AAAAAAAAFIg/NtfvaM9x4BgQp9xg72zZk2tNG627BMhegCL0BGAs/w324-d-h576-n-rw/menupariwisata.PNG=s50" alt="Menu Pariwisata">
		<p>Ini merupakan mockup dari halaman Menu Pariwisata. Pada halaman ini terdapat 6 menu dan juga navigasi.</p>
	</td>
	<td>
		<ul><li>Wisata Buatan</li></ul>  
		<img src="https://lh3.googleusercontent.com/-P2tbYWIjrf0/WrxmS7TBTEI/AAAAAAAAFRA/9qNvn9OpF-cfmqow1hBzkZAxQV0QSBeUgCL0BGAs/w325-d-h578-n-rw/wisatabuatan.PNG=s50" alt="Wisata Buatan">
		<p>Ini merupakan mockup dari halaman Wisata Buatan. Pada halaman ini menampilkan wisata buatan apa saja yang ada di Indramayu.</p>
	</td>
	<td>
		<ul><li>Wisata Alam</li></ul>  
		<img src="https://lh3.googleusercontent.com/-2ngpR7mOoc4/WrxmNYgl8GI/AAAAAAAAFQg/vUdVJzR0kFELpXSNi1j-bGa1RvGGNqzYgCL0BGAs/w325-d-h578-n-rw/wisataalam.PNG=s50" alt="Wisata Alam">
		<p>Ini merupakan mockup dari halaman Wisata Alam. Pada halaman ini menampilkan wisata alam apa saja yang ada di Indramayu.</p>
	</td>
</tr>


<tr>
	<td>
		<ul><li>Kuliner</li></ul>  
		<img src="https://lh3.googleusercontent.com/-oby_ANNDw8w/WrxltglVRUI/AAAAAAAAFO0/_pqT3PkayrEP-QXLuEgNLURQE7RGskW7ACL0BGAs/w326-d-h580-n-rw/kuliner.PNG=s50" alt="Kuliner">
		<p>Ini merupakan mockup dari halaman Kuliner. Pada halaman ini menampilkan kuliner apa saja yang ada di Indramayu.</p>
	</td>
	<td>
		<ul><li>Resto & Kafe</li></ul>  
		<img src="https://lh3.googleusercontent.com/-lpI_4v-I_pU/Wrxl8iwBXSI/AAAAAAAAFPs/6EbnVw0Jw3AndgNA4ob0xvB0nGYHIIvZQCL0BGAs/w326-d-h580-n-rw/restodankafe.PNG=s50" alt="Resto Kafe">
		<p>Ini merupakan mockup dari halaman Resto & Kafe. Pada halaman ini menampilkan resto dan kafe apa saja yang ada di Indramayu.</p>
	</td>
	<td>  
		<ul><li>Travel</li></ul>
		<img src="https://lh3.googleusercontent.com/-DJV9QCIrW9s/WrxmfRy3IBI/AAAAAAAAFRc/D_aZiy0fzQ0mwAFmt1HR_mCG2-zQVKZNwCL0BGAs/w319-d-h567-n-rw/travel.PNG=s50" alt="Travel">
		<p>Ini merupakan mockup dari halaman Travel. Pada halaman ini menampilkan travel apa saja yang ada di Indramayu.</p>
	</td>
</tr>


<tr>
	<td>
		<ul><li>Hotel</li></ul>  
		<img src="https://lh3.googleusercontent.com/-sz7Xx08oNQ0/WrxiFPC0j_I/AAAAAAAAFMI/wtOVuxiKMtoT9xQJIcjEek4UfuNnvSdLACL0BGAs/w325-d-h578-n-rw/hotel.PNG=s50" alt="Hotel">
		<p>Ini merupakan mockup dari halaman Hotel. Pada halaman ini menampilkan hotel apa saja yang ada di Indramayu.</p>
	</td>
	<td>
		<ul><li>Budaya</li></ul>  
		<img src="https://lh3.googleusercontent.com/-cOUIct6zf1g/WrxhYXMbvUI/AAAAAAAAFKg/N-PMpAzALIUhMZCpjNryO1h9V1pSXaFTwCL0BGAs/w325-d-h578-n-rw/budaya.PNG=s50" alt="Budaya">
		<p>Ini merupakan mockup dari halaman Budaya. Pada halaman ini menampilkan budaya apa saja yang ada di Indramayu.</p>
	</td>
	<td>
		<ul><li>Kegiatan</li></ul>
		<img src="https://lh3.googleusercontent.com/-D1sIPNSm-JQ/Wrxi6Zcq0aI/AAAAAAAAFN8/EEvClA8HMlQRNVq87xH1polstTeWfvTvgCL0BGAs/w327-d-h581-n-rw/kegiatan.PNG=s50" alt="Kegiatan">
		<p>Ini merupakan mockup dari halaman Kegiatan. Pada halaman ini menampilkan kegiatan apa saja yang ada di Indramayu.</p>
	</td>
</tr>


<tr>
	<td> 
		 <ul><li>Navigtion Bar</li></ul>
		<img src="https://lh3.googleusercontent.com/-fWT3tYKw-Nw/WrxlylWm78I/AAAAAAAAFPM/yfsT-UNYVpYaz7u65_TDLYYD2aBwOfgcQCL0BGAs/w318-d-h565-n-rw/navbar.PNG=s50" alt="Navbar">
		<p>Ini merupakan mockup dari Navigtion Bar, dimana terdapat Username serta button Profil Saya untuk melihat profil user dan button Log Out untuk keluar dari akun yang sedang digunakan.</p>
	</td>
	<td>
		<ul><li>Lihat Detail</li></ul>  
		<img src="https://lh3.googleusercontent.com/-EoUFpmLvacY/WrxhsuuVHrI/AAAAAAAAFLo/I5Xf6THB_fon0PMwuUkSdX1av-uMegn2gCL0BGAs/w325-d-h578-n-rw/lihatdetail.PNG=s50" alt="Lihat Detail">
		<p>Ini merupakan mockup dari halaman Lihat Detail, dimana dalam halaman ini ditampilkan secara rinci tentang konten yang dipilih. Halaman ini merupakan salah satu contoh dari Lihat Detail pada Budaya.</p>
	</td>
	<td> 
		<ul><li>Pengaduan</li></ul>  
		<img src="https://lh3.googleusercontent.com/-8xZsmNVuW0A/WtNW7XPDAaI/AAAAAAAAF4c/LnxpJS5TttAypV_iPUIodwFYHvTNDpz_QCL0BGAs/w318-d-h565-n-rw/pengaduan.PNG=s50" alt="Pengaduan">
		<p>Ini merupakan mockup dari halaman Pengaduan, dimana dalam halaman ini User dapat mengajukan pengaduan melalui form yang harus diisi. Data pengaduan yang telah terisi lalu terkirim ke Admin (Website).</p>
	</td>
</tr>


<tr>
	<td>
		<ul><li>Profil Saya</li></ul>   
		<img src="https://lh3.googleusercontent.com/-03pj6Uh6_Jg/WrxoM7jYqOI/AAAAAAAAFTM/3UoYbmZd9I02RV3hl7jKLalskjggS6M6gCL0BGAs/w324-d-h576-n-rw/profilsaya.PNG=s50" alt="Profil User">
		<p>Ini merupakan mockup dari halaman Profil Saya, dimana dalam halaman ini ditampilkan informasi tentang User.</p>
	</td>
	<td>
		<td>
			<ul><li>Ubah Profil</li></ul>   
			<img src="https://lh3.googleusercontent.com/-QULfNIB-2FQ/WrxoVVed3TI/AAAAAAAAFTk/wMe6Wrxa9bIIOioT37w3UKM93bvOaRn9QCL0BGAs/w328-d-h583-n-rw/ubahprofil.PNG=s50" alt="Ubah Profil">
		<p>Ini merupakan mockup dari halaman Ubah Profil, dimana dalam halaman ini User dapat mengelola data profil.</p>
	</td>
	<td> 
		<td>
			<ul><li>Tetang Disbudpar</li></ul>  
			<img src="https://lh3.googleusercontent.com/-7qe8DcuSU1o/Wrxhi6RtElI/AAAAAAAAFLQ/FeT-6TXupZsXBoaCm29vi4p6b9eCK-G-ACL0BGAs/w324-d-h576-n-rw/disbudpar.PNG=s50" alt="Disbudpar">
			<p>Ini merupakan mockup dari halaman Tetang Disbudpar, dimana dalam halaman ini ditampilkan informasi mengenai Dinas Kebudayaan dan Pariwisata Kabupaten Indramayu.</p>
	</td>
</tr>

<tr>
	<td>
		<ul><li>Tetang Kami</li></ul>
		<img src="https://lh3.googleusercontent.com/-qTLl_LVRI_c/Wrxhchx9rFI/AAAAAAAAFNM/UvtrnvuQVMcTFdFoFAHtsMEhz98IFT3tACJoC/w323-h574-n-rw/busayu.PNG">
		<p>Ini merupakan mockup dari halaman Tetang Kami, dimana dalam halaman ini ditampilkan informasi mengenai profil Aplikasi Busayu</p>
	</td>
</tr>
</table>

<ul><li><strong>Admin (Web)</strong></li></ul>  
<table>
<tr>
	<td>
		<ul><li>Login</li></ul> 
		<img src="https://lh3.googleusercontent.com/-V5CSPnKtScY/WtNAclDqyCI/AAAAAAAAFuI/XWnLvGqlw-g_MuclX5XPTd2_ySPotN0sQCL0BGAs/w530-d-h352-n-rw/login.PNG=s100" alt="Login">
		<p>Ini merupakan mockup dari halaman Login, dimana Admin harus menginputkan username dan password agar bisa Log in</p>
	</td>
	<td>
		<ul><li>Dashboard</li></ul> 
		<img src="https://lh3.googleusercontent.com/-EKiX7NcnRcA/WtNAEvrJnFI/AAAAAAAAFsM/sCvuETFqCCM2q-z7CPwpirOzm6Wf7-mmACL0BGAs/w530-d-h399-n-rw/dashboard.PNG=s100" alt="Dashboard">
		<p>Ini merupakan mockup dari Dashboard, dimana terdapat navigasi yang terletak di sebelah kiri. Jika ingin melihat data maka memilih menu yang ada di navigasi. Lalu di pojok kanan atas terdapat 2 icon yaitu icon Notifikasi untuk Pengaduan yang masuk dari User dan icon user admin yang berisi menu Tambah Admin dan Logout </p>
	</td>
</tr>

<tr>
	<td>
		<ul><li>Data Budaya</li></ul>   
		<img src="https://lh3.googleusercontent.com/-1sY_KfUhHao/WtM_9NS24OI/AAAAAAAAFr0/JvlgyB3WaNIMEC6wF0ecV8dIy_5SFBwKgCL0BGAs/w530-d-h332-n-rw/budaya.PNG=s100" alt="Budaya">
		<p>Ini merupakan mockup dari halaman Data Budaya. Pada halaman ini terdapat tabel data budaya, button refresh, tambah data, edit, hapus, dan pencarian.</p>
	</td>
	<td> 
		<ul><li>Data Wisata Alam</li></ul> 
		<img src="https://lh3.googleusercontent.com/-rSN5o6Yedfs/WtNBAvegvrI/AAAAAAAAFxQ/FU2vjsiHzPAUv-SHuDkoPh1MBHZE8flVwCL0BGAs/w530-d-h456-n-rw/wisata%2Balam.PNG=s100" alt="wisata alam">
		<p>Ini merupakan mockup dari halaman Pariwisata > Wisata Alam. Pada halaman ini terdapat tabel data wisata alam, button refresh, tambah data, edit, hapus, dan pencarian.</p>
	</td>
</tr>

<tr>
	<td>
		<ul><li>Data Wisata Buatan</li></ul>  
		<img src="https://lh3.googleusercontent.com/-KS91S4f42Ds/WtNBFrBHzEI/AAAAAAAAFx0/vulwYrMMJKERNc7cd2SR5_R6P_Sn76KOgCL0BGAs/w530-d-h449-n-rw/wisata%2Bbuatan.PNG=s100" alt="Wisata Buatan">
		<p>Ini merupakan mockup dari halaman Pariwisata > Wisata Buatan. Pada halaman ini terdapat tabel data wisata buatan, button refresh, tambah data, edit, hapus, dan pencarian.</p>
	</td>
	<td>
		<ul><li>Data Kuliner</li></ul>   
		<img src="https://lh3.googleusercontent.com/-JwwmIeyHtW4/WtNAYafsqNI/AAAAAAAAFts/LTYNWZh7rBQlfaphv_02VY8H7DBjP99BwCL0BGAs/w530-d-h455-n-rw/kuliner.PNG=s100" alt="kuliner">
		<p>Ini merupakan mockup dari halaman Pariwisata > Kuliner. Pada halaman ini terdapat tabel data kuliner, button refresh, tambah data, edit, hapus, dan pencarian.</p>
	</td>
</tr>


<tr>
	<td>
		<ul><li>Data Resto & Kafe</li></ul>  
		<img src="https://lh3.googleusercontent.com/-DiZKwnSmFVk/WtNAhZFq39I/AAAAAAAAFug/VulQcbXsYzUXh7jDID3d-eBQL-KxL2VfwCL0BGAs/w530-d-h452-n-rw/restokafe.PNG=s100" alt="restokafe">
		<p>Ini merupakan mockup dari halaman Pariwisata > Resto & Kafe. Pada halaman ini terdapat tabel data resto & kafe, button refresh, tambah data, edit, dan hapus.</p>
	</td>
	<td>  
		<ul><li>Data Hotel</li></ul> 
		<img src="https://lh3.googleusercontent.com/-tLJZp8_z1IM/WtNAPMx57iI/AAAAAAAAFs8/4oY1IFbdI_gXRyGRU7gjFr0_reDoOkKlQCL0BGAs/w530-d-h455-n-rw/hotel.PNG=s100" alt="hotel">
		<p>Ini merupakan mockup dari halaman Pariwisata > Hotel. Pada halaman ini terdapat tabel data hotel, button refresh, tambah data, edit, hapus, dan pencarian.</p>
	</td>
</tr>

<tr>
	<td> 
		<ul><li>Data Travel</li></ul> 
		<img src="https://lh3.googleusercontent.com/-JlQYkY2TTWs/WtNA7EfeKmI/AAAAAAAAFwo/lxcRWm0Keb8EDJEaNnCggwsVhVGXwPwwgCL0BGAs/w530-d-h446-n-rw/travel.PNG=s100" alt="Travel">
		<p>Ini merupakan mockup dari halaman Pariwisata > Travel. Pada halaman ini terdapat tabel data travel, button refresh, tambah data, edit, hapus, dan pencarian.</p>
	</td>
	<td>
		<ul><li>Data Travel</li></ul>  
		<img src="https://lh3.googleusercontent.com/--M8_QqOVQ4c/WtNFTZ-o8jI/AAAAAAAAF1E/pfrnjLOCnk48Nbr-nSdhGD6F7njpV-pxACL0BGAs/w530-d-h327-n-rw/kegiatan.PNG=s100" alt="kegiatan">
		<p>Ini merupakan mockup dari halaman Kegiatan. Pada halaman ini terdapat tabel data kegiatan, button refresh, tambah data, edit, hapus, dan pencarian.</p>
	</td>
</tr>

<tr>
	<td>
		<ul><li>Data User</li></ul>  
		<img src="https://lh3.googleusercontent.com/-pRfDTiQRJog/WtNWhEx1YPI/AAAAAAAAF4E/Yu98fdyMqjAoYOPGmg-oynOUhTgelFZrwCL0BGAs/w530-d-h332-n-rw/data%2Buser.PNG=s100" alt="data user">
		<p>Ini merupakan mockup dari halaman User. Pada halaman ini terdapat tabel data user. Untuk data admin dan user dijadikan dalam satu tabel. Admin hanya bisa melihat data user dan admin.</p>
	</td>
	<td>
		<ul><li>Data Pengaduan</li></ul>   
		<img src="https://lh3.googleusercontent.com/-hj3EoEM1Dco/WtNJtTd6lcI/AAAAAAAAF3E/qVeGj3LtbuwdwnZ_HZ2_G0R8NgEEavW4ACL0BGAs/w530-d-h327-n-rw/pengaduan.PNG=s100" alt="pengaduan">
		<p>Ini merupakan mockup dari halaman Pengaduan. Pada halaman ini terdapat tabel data pengaduan. Data pengaduan yang dikirim User melalui aplikasi Android terkirim dan tersimpan di data pengaduan yang ada di web (Admin).</p>
	</td>
</tr>

<tr>
	<td>
		<ul><li>Tambah Admin</li></ul>   
		<img src="https://lh3.googleusercontent.com/-CbWNz5BGRKw/WtNAmGlSmlI/AAAAAAAAFu4/61UnLVQMRw8IF99Y-DBJDgHqkZr_BeWtQCL0BGAs/w530-d-h342-n-rw/tambah%2Badmin.PNG=s100" alt="tambah admin">
		<p>Ini merupakan mockup dari halaman Tambah Admin. Pada halaman ini terdapat form untuk menambahkan admin. Dan juga terdapat button Simpan untuk menyimpan data dan Batal untuk kembali ke Data User</p>
	</td>
	<td>  
		<ul><li>Tambah Data Pariwisata</li></ul>
		<img src="https://lh3.googleusercontent.com/-Y7YlxHNsT7w/WtNA18JZsRI/AAAAAAAAFwM/c8WfJAr7xrUEQ98ggLs19Xy-hBQ5xYaewCL0BGAs/w530-d-h350-n-rw/tambah%2Bpariwisata.PNG=s100" alt="tambah pariwisata">
		<p>Ini merupakan mockup dari halaman Tambah Data Pariwisata. Pada halaman ini terdapat form untuk menambahkan pariwisata. Dan juga terdapat button Simpan untuk menyimpan data dan Batal untuk kembali ke halaman sebelumnya</p>
	</td>
</tr>

<tr>
	<td> 
		<ul><li>Tambah Data Budaya</li></ul> 
		<img src="https://lh3.googleusercontent.com/-P_hkx-GffVs/WtNArO9ATkI/AAAAAAAAFvU/CMyGQ_SjKI4svHlYgzbMftDd0uw7a6qJQCL0BGAs/w530-d-h349-n-rw/tambah%2Bbudaya.PNG=s100" alt="tambah budaya">
		<p>Ini merupakan mockup dari halaman Tambah Data Budaya. Pada halaman ini terdapat form untuk menambahkan budaya. Dan juga terdapat button Simpan untuk menyimpan data dan Batal untuk kembali ke halaman sebelumnya</p>
	</td>
	<td>
		<ul><li>Tambah Data Kegiatan</li></ul>  
		<img src="https://lh3.googleusercontent.com/-rU4MBt3qe44/WtNAwxU5w5I/AAAAAAAAFvw/NxQfp4G2RWQ1pLxMYO0HXwaKmjuJ3e0cgCL0BGAs/w530-d-h352-n-rw/tambah%2Bkegiatan.PNG=s100" alt="tambah kegiatan">
		<p>Ini merupakan mockup dari halaman Tambah Data Kegiatan. Pada halaman ini terdapat form untuk menambahkan kegiatan. Dan juga terdapat button Simpan untuk menyimpan data dan Batal untuk kembali ke halaman sebelumnya.</p>
	</td>
</tr>
</table>




<h4><strong>2.1.3 Antarmuka perangkat keras</strong><br></h4>  
<p>
	<img src="https://lh3.googleusercontent.com/X0547VB1z0t-vmZLOnlvdFPOPRxi0gGhFNuIcLjDgQCUg8taYVmNEcdEvKxQey7bWaY6_co0WVQ=s300" alt="2.3">
</p>
<p>Sistem aplikasi ini memiliki 2 User yang aktif, yaitu Admin dan User. User dapat mengakses aplikasi melalui smartphone yang memiliki sistem operasi Android dan Admin dapat mengakses aplikasi web melalui browse. Aplikasi ini bisa digunakan apabila terhubung ke internet. Data-data pada aplikasi ini selanjutnya disimpan di database (Server) dan selanjutnya dikelola oleh Admin.</p>

<h4><strong>2.1.4 Antarmuka perangkat lunak</strong><br></h4>  
<p>Untuk dapat menggunakan aplikasi budaya dan pariwisata Kabupaten Indramayu kita dapat mengakses lewat browser.<br></p>

<h4><strong>2.1.5 Antarmuka Komunikasi</strong></h4>  
<p>Aplikasi ini bekerja sama dengan Dinas Kebudayaan dan Pariwisata Kabupaten Indramayu.<br></p>

<h4><strong>2.1.6 Batasan memori</strong><br></h4> 
<p>Memori yang digunakan untuk aplikasi di usahakan tidak melebihi 100MB</p>  

<h4><strong>2.1.7 Operasi-operasi</strong><br></h4>  
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
		<tr>
			<td>Pengaduan</td>  
			<td>Digunakan untuk pengaduan pengguna</td>  
  		</tr>
  	</tbody>
</table>

<h4><strong>2.1.8 Kebutuhan adaptasi</strong></h4>
<p>Tidak ada.</p>

<h3><strong>2.2. Spesifikasi Kebutuhan Fungsional</strong><br></h3>

![all](https://lh3.googleusercontent.com/wpQS-zqzpbn2W7g44oenr9h9X7NoxJqeN9T2u6DzDNg64dzquSMJJlst9Eh8GtGNRrnFfxr9DYU2 "all")

<h4><strong>2.2.1 User Login</strong></h4>  
<p>Use Case: Login<br>
Diagram:</p>
<p><img src="https://lh3.googleusercontent.com/i-F1NFPY-xV7ejGrqxV7QLFH83dROOfA2xJqVtyiXEPTgO2c0V6Gz1Co9XBAEHNUzIm7t0Yf7NGR=s300" alt="use case login"></p>
<p>Deskripsi singkat user melakukan login sebelum masuk ke halaman utama:</p>
<ol>
	<li>User melakukan login dengan username dan password.</li>
	<li>Sistem melakukan validasi.</li>
	<li>Bila user benar memasukkan username dan password maka sistem akan mengarahkan user ke halaman utama</li>
	<li>Bila user salah memasukkan username dan password maka sistem akan menampilkan eror</li>
</ol>
Xref: Bagian 3.2.1, User login</p></p>

<h4><strong>2.2.2 User Melihat Budaya</strong><br></h4>
<p>Use case: melihat budaya<br>
Diagram:</p>
<p><img src="https://lh3.googleusercontent.com/aJvMtPpo98MB3LB-uN9TY421p30GDaX0DbHimOQdhrf--_M6iH8vhxwdiRbT5rThn4ZtLHXggco7=s300" alt="use case budaya" title="userbudaya"></p>
<p>Deskripsi singkat ketika user melihat budaya:</p>
<ol>
	<li>Sistem menampilkan halaman utama yang berisi button budaya</li>
	<li>User dapat mengklik tombol button budaya</li>
	<li>Sistem menampilkan data budaya</li>
</ol>
Xref: Bagian 3.2.2, User lihat budaya<p></p>

<h4><strong>2.2.3 User Melihat Wisata</strong><br></h4>
<p>Use case: melihat wisata<br>
Diagram:</p>
<p><img src="https://lh3.googleusercontent.com/kDGYT_tryNcLBWRvT2ahCJJGpUWXkjcivLp50wzawgjyPO4ZWHJoSjIt1RXTwFyuZEmyqNgnCXan=s300" alt="use case wisata" title="userlihatwisata"></p>
<p>Deskripsi singkat ketika user melihat wisata:</p>
<ol>
<li>Sistem menampilkan halaman utama yang berisi button wisata</li>
<li>User dapat mengklik tombol button wisata</li>
<li>Sistem menampilkan data wisata</li>
</ol>
Xref: Bagian 3.2.3, User lihat wisata<p></p>

<h4><strong>2.2.4 User Melihat Kegiatan</strong><br></h4>
<p>Use case: melihat kegiatan<br>
Diagram:</p>


![ukeg](https://lh3.googleusercontent.com/rSl87Vh0WZdSz34FM2nkWN-1O0qArkneKY3wBlqoEfedVW5K0e_9wVwRoiA_43j00-828Hdm1sRG "ukeg")

<p>Deskripsi singkat ketika user melihat kegiatan:</p>
<ol>
<li>Sistem menampilkan halaman utama yang berisi button kegiatan</li>
<li>User dapat mengklik tombol button kegiatan</li>
<li>Sistem menampilkan data kegiatan</li>
</ol>
Xref: Bagian 3.2.4, User lihat kegiatan<p></p>

<h4><strong>2.2.5 User Mengajukan Pengaduan</strong><br></h4>
<p>Use case: mengajukan pengaduan<br>
Diagram:</p>
<p><img src="https://lh3.googleusercontent.com/9fkLEPEU73UZRVCxTIV5mGCjmx48yOGGocaACpASJA6sDRdbDfSdAauKa9abyHyiQd2T98XXJB-5=s300" alt="use case pengaduan" title="userpengaduan"></p>
<p>Deskripsi singkat ketika user mengajukan pengaduan:</p>
<ol>
<li>Sistem menampilkan halaman utama yang berisi button pengaduan</li>
<li>User dapat mengklik tombol button pengaduan</li>
<li>User mengisi form pengaduan ke sistem</li>
<li>Sistem akan mengirim ke admin</li>
</ol>
Xref: Bagian 3.2.5, User mengajukan pengaduan<p></p>

<h4><strong>2.2.6 Admin Login</strong><br></h4>
<p>Use case: login<br>
Diagram:</p>
<p><img src="https://lh3.googleusercontent.com/hySM59sWo0DwaotyC5t4Zqr3lyXxRaGe6CwzzNccqkQ5Si8n612LfM22MnORBzA7sXNlqHVCHFNE=s300" alt="use case login admin"></p>
<p>Deskripsi singkat ketika admin login:</p>
<ol>
<li>Admin melakukan login dengan username dan password.</li>
<li>Sistem melakukan validasi.</li>
<li>Bila admin benar memasukkan username dan password maka sistem akan mengarahkan user ke halaman utama</li>
<li>Bila admin salah memasukkan username dan password maka sistem akan menampilkan eror</li>
</ol>
Xref: Bagian 3.2.6, Admin login<p></p>

<h4><strong>2.2.7 Admin Mengelola Budaya</strong><br></h4>
<p>Use case: mengelola budaya<br>
Diagram:</p>

![abud](https://lh3.googleusercontent.com/LXbhmHH2PctH9yFvYL1Axx9DxdBNxkDpEe7aMzNpFji2n_GREHHjaXiQQROvj5G-KHpf3ZMlr8B6 "abud")

<p>Deskripsi singkat ketika admin mengelola budaya:</p>
<ol>
<li>Sistem menampilkan dasboard admin</li>
<li>Admin memilih menu budaya pada sidebar</li>
<li>Admin mengelola data budaya</li>
<li>Sistem akan mengirim data ke database</li>
</ol>
Xref: Bagian 3.2.7, Admin mengelola budaya<p></p>

<h4><strong>2.2.8 Admin Mengelola Pariwisata</strong><br></h4>
<p>Use case: mengelola pariwisata<br>
Diagram:</p>

![apar](https://lh3.googleusercontent.com/8TmSjbZU85jYjuelTeYgMTjRu3b6k8yLXt9GNJu2J-5J2KAaDAphiuM1mW8zJOlOPJuCNfbHW2wB "apar")


<p>Deskripsi singkat ketika admin mengelola pariwisata:
</p><ol>
<li>Sistem menampilkan dasboard admin</li>
<li>Admin memilih menu pariwisata pada sidebar</li>
<li>Admin mengelola data pariwisata</li>
<li>Sistem akan mengirim data ke database</li>
</ol>
Xref: Bagian 3.2.8, Admin Mengelola Pariwisata<p></p>

<h4><strong>2.2.9 Admin Mengelola Kegiatan</strong><br></h4>
<p>Use case: mengelola kegiatan<br>
Diagram:</p>

![akeg](https://lh3.googleusercontent.com/zBWG8SoLz5oPrbz4nXXFqtfcLggTm2p8peYUgHt_1Cpxp7CWDA1hLawloygaPC4Ox_xVu-xjDtlE "akeg")

<p>Deskripsi singkat ketika admin mengelola kegiatan:</p>
<ol>
<li>Sistem menampilkan dasboard admin</li>
<li>Admin memilih menu kegiatan pada sidebar</li>
<li>Admin mengelola data kegiatan</li>
<li>Sistem akan mengirim data ke database</li>
</ol>
Xref: Bagian 3.2.9, Admin mengelola kegiatan<p></p>

<h4><strong>2.2.10 Admin Mengelola Pengaduan</strong><br></h4>
<p>Use case: mengelola pengaduan<br>
Diagram:</p>

![apeng](https://lh3.googleusercontent.com/pB1q0wjsbT6rQq2wvnK6-7HN1vocePQaqli-OO10TtW9kJyW0mWid7IEAq0DB49klHHj3oBjYNX7 "apeng")

<p>Deskripsi singkat ketika admin mengelola pengaduan:</p>
<ol>
<li>Sistem menampilkan dashboard admin</li>
<li>Admin memilih menu pengaduan pada sidebar</li>
<li>Admin mengelola data pengaduan</li>
<li>Sistem akan mengirim data ke database</li>
</ol>
Xref: Bagian 3.2.10, Admin mengelola pengaduan<p></p>

<h4><strong>2.2.11 Admin Mengelola user</strong><br></h4>
<p>Use case: mengelola user<br>
Diagram:</p>

![aus](https://lh3.googleusercontent.com/9DjF0AaQrCQuJUJjqHTMKbv89YPboBLN4yEbDtZ1LxWDT3NS8vymF2qf7L932GpBIfUhSLYBFbEq "aus")

<p>Deskripsi singkat ketika admin mengelola user:</p>
<ol>
<li>Sistem menampilkan dasboard admin</li>
<li>Admin memilih menu user pada sidebar</li>
<li>Admin mengelola data user</li>
<li>Sistem akan mengirim data ke database</li>
</ol>
Xref: Bagian 3.2.11, Admin mengelola user<p></p>

<h4><strong>2.2.12 User Mengedit User</strong><br></h4>
<p>Use case: mengedit user<br>
Diagram:</p>

![usus](https://lh3.googleusercontent.com/97Ljeg-5s2qLDKmSEbqkGdK7f4rvpopZUnjFVkldo_MW67EB_xL8J1Vg3cw5bsBfM1_i5u95QycT "usus")

<p>Deskripsi singkat ketika user mengedit user:</p>
<ol>
<li>Sistem menampilkan halaman utama yang berisi button budaya</li>
<li>user menekan tombol navigasi</li>
<li>User memilih profil saya</li>
<li>User memilih ubah profil</li>
<li>User mengedit dat profil</li>
<li>Sistem akan mengirim data ke database</li>
</ol>
Xref: Bagian 3.2.12, User Mengedit User<p></p>


<h3><strong>2.3. Spesifikasi Kebutuhan Non-fungsional</strong><br></h3>

<h4><strong>2.3.1 Spesifikasi User Interface</strong><br></h4>  
<p>User Interface yang ada pada aplikasi harus user-friendly, dan mudah untuk digunakan.<br></p>

<h4><strong>2.3.2 Spesifikasi Kinerja</strong><br></h4>  
<p>Sistem ini diharapkan dapat di gunakan dalam jangka panjang dan sistem ini dapat berfungsi secara optimal.<br></p>  

<h4><strong>2.3.3 Ketersediaan dan Keandalan</strong><br></h4>  
<p>Aplikasi dapat menyediakan backup pada database yang digunakan.<br></p>  

<h4><strong>2.3.4 Spesifikasi Keamanan</strong><br></h4>  
<p>Keamanan data akan terjaga karena menerapkan validasi pada saat pengguna mulai login.</p>

<h3><strong>2.4. Karakteristik Pengguna</strong><br></h3>  
<p>  Dengan adanya aplikasi ini diharapkan dapat membantu admin mengolah data pariwisata, data kebudayaan, data event dan pendaftaran untuk mengikuti event. kemudian bagi pengguna sendiri diharapkan dapat mempermudah pengguna untuk mendapatkan informasi tentang pariwisata, kebudayaan dan event yang di adakan oleh dinas kebudayaan dan pariwisata kabupaten Indramayu menggunakan aplikasi mobile ini.</p>

<h3><strong>2.5. Batasan-batasan</strong><br></h3>  
<p>Pada Aplikasi Budaya dan Pariwisata Kabupaten Indramayu harus menggunakan smartphone denga sistem operasi Android untuk dapat mengaksesnya atau menggunakannya. Pengguna dapat login dengan mendaftar terlebih dahulu.<br><br><br></p>


<h2><strong>3. Requirement Specification</strong></h2>  
<h3><strong>3.1 Persyaratan Antarmuka Eksternal</strong><br></h3>  
<p>Salah satu persyaratan untuk mengakses Aplikasi ini adalah dengan mendaftarkan diri dan melengkapi kolom data diri.</p> 

<h3><strong>3.2 Functional Requirnment</strong><br></h3>
<h4><strong>3.2.1 User Login</strong></h4>  
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
				<li>jika login cocok dengan database maka sistem akan mengarahkan ke halaman utama</li>
				<li>jika tidak maka sistem akan menampilkan notif peringatan</li>
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

<h4><strong>3.2.2 User Melihat Budaya</strong></h4>  
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
				<li>User mengklik menu budaya</li>
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

<h4><strong>3.2.3 User Melihat Wisata</strong></h4>  
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
					<li>User mengklik menu pariwisata</li>
					<li>Sistem menampilkan menu pariwisata</li>
					<li>User memilih menu pariwisata</li>
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

<h4><strong>3.2.4 User Melihat Kegiatan</strong></h4>  
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
					<li>User mengklik menu kegiatan</li>
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

<h4><strong>3.2.5 User Mengajukan Pengaduan</strong></h4>  
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
				<li>User mengklik menu pengaduan</li>
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

<h4><strong>3.2.6 Admin Login</strong></h4>  
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
					<ol>
					<li>Sistem menampilkan dasboard admin</li>
					<li>Admin memilih menu budaya pada sidebar</li>
					<li>Admin mengelola data budaya</li>
					<li>Sistem akan mengirim data ke database</li>
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

<h4><strong>3.2.7 Admin Mengelola Budaya</strong></h4>  
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
					<ol>
					<li>Sistem menampilkan dasboard admin</li>
					<li>Admin memilih menu pariwisata pada sidebar</li>
					<li>Admin mengelola data pariwisata</li>
					<li>Sistem akan mengirim data ke database</li>
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

<h4><strong>3.2.8 Admin Mengelola Pariwisata</strong></h4>  
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
				<ol>
				<li>Sistem menampilkan dasboard admin</li>
				<li>Admin memilih menu kegiatan pada sidebar</li>
				<li>Admin mengelola data kegiatan</li>
				<li>Sistem akan mengirim data ke database</li>
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

<h4><strong>3.2.9 Admin Mengelola Kegiatan</strong></h4>  
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
				<ol>
				<li>Sistem menampilkan dasboard admin</li>
				<li>Admin memilih menu kegiatan pada sidebar</li>
				<li>Admin mengelola data kegiatan</li>
				<li>Sistem akan mengirim data ke database</li>
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

<h4><strong>3.2.10 Admin Mengelola Pengaduan</strong></h4>  
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
				<ol>
				<li>Sistem menampilkan dasboard admin</li>
				<li>Admin memilih menu pengaduan pada sidebar</li>
				<li>Admin mengelola data pengaduan</li>
				<li>Sistem akan mengirim data ke database</li>
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

<h4><strong>3.2.11 Admin Mengelola User</strong></h4>  
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
				<ol>
				<li>Sistem menampilkan dasboard admin</li>
				<li>Admin memilih menu user pada sidebar</li>
				<li>Admin mengelola data user</li>
				<li>Sistem akan mengirim data ke database</li>
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

<h4><strong>3.2.12 User Mengedit User </strong></h4>  
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
				<ol>
				<li>Sistem menampilkan halaman utama yang berisi button budaya</li>
				<li>user menekan tombol navigasi</li>
				<li>User memilih profil saya</li>
				<li>User memilih ubah profil</li>
				<li>User mengedit dat profil</li>
				<li>Sistem akan mengirim data ke database</li>
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

<h3><br><strong>3.3 Struktur Detail Kebutuhan Non Functional</strong><br></h3>
<h4><strong>3.3.1 Logika Struktur Data</strong><br></h4>
<p>Struktur data logika pada sistem Aplikasi Budaya dan Pariwisata terdapat struktur Database yang dijelaskan menggunakan ERD.  
</p><p>

![enter image description here](https://1.bp.blogspot.com/-hkYea_zGdL4/WtNJdhP-n5I/AAAAAAAAAIs/5_ZVWO5vu6wx8GGiDGUFr1TsOleaCP3owCLcBGAs/s1600/ERD.jpg)

<p>Pada ERD terdapat tabel admin, tabel user, tabel pariwisata, tabel budaya, tabel event dan tabel pengaduan.  </p>

<ul>
	<li>
		<p><strong>Tabel User (Admin dan User)</strong></p>
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
		<td>Nomor auto increment id_user</td>    
	</tr>  
	<tr>  
		<td>username</td>  
		<td>Varchar</td>   
		<td>Berisi nama atau nomor untuk dapat mengakses aplikasi</td>   
	</tr>  
	<tr>  
		<td>password</td>  
		<td>Varchar</td>   
		<td>Berisi password untuk dapat mengakses aplikasi </td>   
	</tr>  
	<tr>  
		<td>nama_user</td>  
		<td>Varchar</td>   
		<td>Untuk login dan mendaftar aplikasi </td>   
	</tr>   
	<tr>  
		<td>email</td>   
		<td>Varchar</td>   
		<td>Berisi alamat email user</td>   
	</tr>
	<tr>  
		<td>gambar</td>  
		<td>Varchar</td>   
		<td>Berisi gambar user</td>   
	</tr>   
	<tr>
		<td>kategori</td>
		<td>varchar</td>
		<td>Berisi kategori sebagai siapa pada saat login (sebagai admin atau user)</td>
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
		<td>Nomor auto increment id_budaya</td>    
	</tr>    
	<tr>  
		<td>nama</td>   
		<td>Varchar</td>   
		<td>Berisi nama budaya </td>   
	</tr>   
	<tr>  
		<td>deskripsi</td>   
		<td>Varchar</td>   
		<td>Berisi deskripsi tentang budaya  </td>   
	</tr>   
	<tr>  
		<td>gambar</td>  
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
		<td>Nomor auto increment id_pariwisata</td>    
	</tr>    
	<tr>  
		<td>nama</td>  
		<td>Varchar</td>   
		<td>Berisi nama pariwisata </td>   
	</tr>   
	<tr>  
		<td>deskripsi</td>  
		<td>Varchar</td>   
		<td>Berisi deskripsi tentang pariwisata  </td>   
	</tr>   
	<tr>  
		<td>gambar</td>  
		<td>Varchar</td>   
		<td>Berisi gambar pariwisata  </td>   
	</tr>  
	<tr>  
		<td>id_jenis</td>  
		<td>Integer</td>   
		<td>Sebagai foreign key pada tabel pariwisata</td>   
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
		<p><strong>Tabel Kegiatan</strong></p>
	</li>
</ul>

<table>
	<tr>  
		<td><strong>Data Item</strong></td>  
		<td><strong>Type</strong></td>  
		<td><strong>Deskripsi</strong></td>
	</tr>  
	<tr>  
		<td>id_kegiatan</td>  
		<td>Integer</td>  
		<td>Nomor auto increment id_kegiatan</td>    
	</tr>    
	<tr>  
		<td>nama</td>  
		<td>Varchar</td>   
		<td>Berisi nama event </td>   
	</tr>   
	<tr>  
		<td>deskripsi</td>  
		<td>Varchar</td>   
		<td>Berisi deskripsi tentang event</td>   
	</tr>   
	<tr>  
		<td>tanggal</td>  
		<td>Date</td>   
		<td>Berisi tanggal di adakannnya event  </td>   
	</tr>
	<tr>  
		<td>tempat</td>  
		<td>Varchar</td>   
		<td>Berisi tempat di adakannnya event  </td>   
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
		<td>Nomor auto increment id_pengaduan</td>    
	</tr>    
	<tr>  
		<td>id_user</td>  
		<td>Integer</td>   
		<td>nomor auto increment id_user</td>   
	</tr>
	<tr>  
		<td>judul</td>  
		<td>Varchar</td>   
		<td>Berisi judul tentang event</td>   
	</tr>
	<tr>  
		<td>deskripsi</td>  
		<td>Varchar</td>   
		<td>Berisi deskripsi tentang pengaduan</td>   
	</tr>
</table> 