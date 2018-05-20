


<h1 align="center" id="software-requirements-specification">SOFTWARE TESTING DOCUMENT</h1>
<p align="center"><strong>Version 1.0</strong><br>   
<p align="center"><strong> 09 Mei 2018<br>  </strong><br>
<p align="center"><strong>" BUSAYU (APLIKASI BUDAYA DAN PARIWISATA KABUPATEN INDRAMAYU BERRBASIS ANDROID)"<br><br></strong></p> 
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

<h2><br><strong>1. PENDAHULUAN</strong></br></h2>
<h3><br><strong>1.1	Tujuan Pembuatan Dokumen </strong></br></h3>
<p>Dokumen ini digunakan sebagai panduan untuk melakukan pengujian terhadap Aplikasi BUSAYU (Budaya dan Pariwisata Kab. Indramayu). Dokumen ini dipakai untuk melihat kemampuan dari program yang telah dirancang agar sesuai dengan keinginan dari pengguna. Pembuatan dokumen ini ditujukan untuk menguji Aplikasi BUSAYU yang merupakan bagian dari tugas mata kuliah Rekayasa Perangkat Lunak.</p>

<h3><br><strong>1.2	Deskripsi Umum Sistem</strong></br></h3>
<p>Perangkat lunak yang akan diuji adalah Aplikasi BUSAYU. Aplikasi ini merupakan aplikasi berbasis Android yang digunakan untuk seluruh masyarakat, khususnya masyarakat yang berada di daerah Indramayu untuk mengetahui kebudayaan yang ada di Indramayu dan event atau lomba yang akan diselenggarakan oleh Dinas Kebudayaan dan Pariwisata Kabupaten Indramayu.</p>

<h3><br><strong>1.3	Deskripsi Dokumen (Ikhtisar) </strong></br></h3>
<p>Dalam dokumen ini berisi 4 bagian yaitu Pendahuluan, Lingkungan Pengujian Perangkat Lunak, Identifikasi dan Rencana Pengujian, Deskripsi dan Uji Hasil. </p>

<h3><br><strong>1.4	Definisi dan Singkatan </strong></br></h3>
<table>  
	<thead>  
<tr>
<td><strong>SRS</strong></td>
<td>(Software Requirements Spesification) merupakan dokumen yang dibuat untuk menjelaskan tentang spesifikasi kebutuhan apa saja yang digunakan dalam aplikasi</td>
</tr>
<tr>
<td><strong>SDD</strong></td>
<td>(Software Design Document) merupakan dokumen yang dibuat untuk menjelaskan langkah-langkah desain, spesifikasi kebutuhan fungsional, dan proses-proses dalam pembuatan sistem aplikasi yang akan diterapkan pada aplikasi.</td>
</tr>
<tr>
<td><strong>DFD</strong></td>
<td>(Data Flow Diagram) adalah diagram dan notasi yang digunakan untuk menunjukkan aliran data pada perangkat lunak. </td>
</tr>
<tr>
<td><strong>ERD</strong></td>
<td>(Entity Relationship Diagram) adalah diagram dan notasi yang digunakan untuk merepresentasikan struktur data statis pada perangkat lunak. </td>
</tr>
<tr>
<td><strong>BUSAYU</strong></td>
<td>Aplikasi Budaya dan Pariwisata Kab. Indramayu</td>
</tr>
</thead>  
</table> 

<h3><br><strong>1.5	Dokumen Referensi </strong></br></h3>
<ul>
	<li>Sistem Pentiketan Elektronik Konser.2013. Perencanaan, Deskripsi, Dan Hasil Uji Perangkat Lunak. Bogor.</li>
	<li>Aplikasi BUSAYU.2018.SRS.Indramayu</li>
	<li>Aplikasi BUSAYU.2018.SDD.Indramayu</li>
</ul>



<h2><br><strong>2.	LINGKUNGAN PENGUJIAN PERANGKAT LUNAK </strong></br></h2>
<h3><br><strong>2.1	Perangkat Lunak Pengujian </strong></br></h3>
<p>Perangkat lunak ini (BUSAYU) diujikan dengan beberapa perangkat lunak lain, yaitu: </p>

<table>  
	<thead>  
<tr>
<td><strong>Sistem Operasi</strong></td>
<td>Windows 10 </td>
</tr>
<tr>
<td><strong>Bahasa Pemrograman</strong></td>
<td>PHP</td>
</tr>
<tr>
<td><strong>DBMS</strong></td>
<td>MySQL</td>
</tr>
<tr>
<td><strong>Web Browser</strong></td>
<td>Mozzila Firefox</td>
</tr>
<td><strong>Web Server</strong></td>
<td>XAMPP</td>
</tr>
</thead>  
</table>


<h3><br><strong>2.2	Perangkat Keras Pengujian </strong></br></h3>
<p>Perangkat keras yang diperlukan untuk menguji aplikasi BUSAYU ini adalah satu set komputer dan smartphone dengan spesifikasi : </p>

<ul><li>Web (Admin)</li></ul>
<table>  
	<thead>  
<tr>
<td><strong>Processor</strong></td>
<td>Intel® Core i3-4005U @1.70Ghz</td>
</tr>
<tr>
<td><strong>Memory</strong></td>
<td>6 GB DDR3</td>
</tr>
<tr>
<td><strong>Harddisk</strong></td>
<td>500 GB</td>
</tr>
</thead>  
</table>

<br><ul><li>Android (User)</li></ul>
<table>  
	<thead>  
<tr>
<td><strong>Processor</strong></td>
<td>Processor Octa-core 1.4 GHz Cortex-A53</td>
</tr>
<tr>
<td><strong>Memory</strong></td>
<td>2GB</td>
</tr>
<tr>
<td><strong>API</strong></td>
<td>25</td>
</tr>
</thead>  
</table>  


<h3><br><strong>2.3	Material Pengujian </strong></br></h3>
<p>Pada Aplikasi BUSAYU ini seorang User dapat mengakses informasi tentang budaya dan pariwisata di Kabupaten Indramayu melalui smartphone dengan sistem operasi Android. User dapat langsung menggunakan aplikasi dengan memasukkan username dan password yang didapat saat mendaftar. Setelah mendapatkan akun, User dapat memilih menu apa saja yang diinginkan, serta bisa mengajukan pengaduan tentang budaya dan pariwisata Kabupaten Indramayu yang selanjutnya data tersebut dikirim ke website yang dikelola oleh Admin.</p>

<h3><br><strong>2.4	Sumber Daya Manusia</strong></br></h3>
<p>Persyaratan sumber daya manusia yang akan terlibat dalam proses pengujian aplikasi ini adalah :</p>
<ul>
	<li>Memahami konsep pemrograman berorientasi objek dalam bahasa Java, HTML, CSS, dan PHP</li>
	<li>Memahami konsep database MySQL</li>
</ul>

<h3><br><strong>2.5	Prosedur Umum Pengujian </strong></br></h3>
<h4><br><strong>2.5.1	Pengenalan dan Latihan </strong></br></h4>
<p>Penguji aplikasi ini hanya diberikan latihan kembali tentang Java dan PHP. Pada dasarnya penguji telah memiliki pengetahuan tentang hal yang sudah disebutkan sebelumnya tetapi latihan yang diberikan hanya bersifat penyegaran kembali.</p>

<h4><br><strong>2.5.2 Persiapan Awal </strong></br></h4>
<p>Persiapan awal untuk menguji aplikasi adalah mempersiapkan perangkat keras dan perangkat lunak yang akan dignakan.</p>
<h5><br><strong>2.5.2.1 Persiapan Prosedural</strong></br></h5>
<p>Pengujian ini dilakukan diluar jam perkuliahan dan diluar lingkungan kampus.</p>

<h5><br><strong>2.5.2.2 Persiapan Perangkat Keras </strong></br></h5>
<p>Perangkat keras yang perlu dipersiapkan adalah satu set laptop dan sebuah smartphone dengan spesifikasi :</p>

<ul><li>Web (Admin)</li></ul>
<table>  
	<thead>  
<tr>
<td><strong>Processor</strong></td>
<td>Intel® Core i3-4005U @1.70Ghz</td>
</tr>
<tr>
<td><strong>Memory</strong></td>
<td>6 GB DDR3</td>
</tr>
<tr>
<td><strong>Harddisk</strong></td>
<td>500 GB</td>
</tr>
</thead>  
</table>

<br>

<ul><li>Android (User)</li></ul>
<table>  
	<thead>  
<tr>
<td><strong>Processor</strong></td>
<td>Processor Octa-core 1.4 GHz Cortex-A53</td>
</tr>
<tr>
<td><strong>Memory</strong></td>
<td>2GB</td>
</tr>
<tr>
<td><strong>API</strong></td>
<td>25</td>
</tr>
</thead>  
</table> 



<h5><br><strong>2.5.2.3 Persiapan Perangkat Lunak </strong></br></h5>
<p>Persiapan yang harus dilakukan adalah :
	<ul><li>Web</li></ul>
	<ol>
		<li>Aplikasi disimpan di C:\XAMPP\htdocs\busayu</li>
		<li>Database diimport ke phpMyAdmin</li>
		<li>Jalankan server Apache dan MySQL yang ada di XAMPP Control Panel</li>
		<li>Buka Mozzila Firefox dan ketik http://localhost/busayu.</li>
	</ol>
</p> 
<br>
	<ul><li>Android</li></ul>
	<ol>
		<li>Aplikasi diinstall dan disimpan pada Smartphone</li>
		<li>Koneksi internet diaktifkan</li>
		<li>Buka aplikasi yang sudah terinstall</li>
	</ol> 


<h4><br><strong>2.5.3 Pelaksanaan</strong></br></h4>
<p>Pelaksanaan pengujian dilakukan sesuai dengan persiapan sebelumnya. Dan pengujian dilaksanakan berdasarkan skenario yang telah disediakan.</p>

<h4><br><strong>2.5.4 Pelaporan Hasil Dokumen </strong></br></h4>
<p>Setelah aplikasi diuji, laporan hasil dari pengujian tersebut akan diberikan kepada dosen pengampu Rekayasa Perangkat Lunak (RPL)</p>



<h2><br><strong>3 IDENTIFIKASI DAN RENCANA PENGUJIAN</strong></br></h2>
<table>  
	<thead>  
<tr>
	<td rowspan="2" align="center"><strong>Kelas Uji</td>
	<td rowspan="2" align="center"><strong>Butir Uji </td>
	<td colspan="2" align="center"><strong>Identifikasi</td>
	<td rowspan="2" align="center"><strong>Jenis Pengujian</td>
	<td rowspan="2" align="center"><strong>Teknik Pengujian</td>
	<td rowspan="2" align="center"><strong>Penguji</td>
</tr>
		<tr>
			<td align="center"><strong>SRS/SDD</td>
			<td align="center"><strong>SPMP</td>
		</tr>

<!-- user melakukan login -->		
<tr>
	<td rowspan="3" align="center"><strong>Pengujian Login User</td>
	<td>Pengisian Username dan Password benar (User)</td>
	<td>SRS-2.2.1</td>
	<td>-</td>
	<td>Sistem</td>
	<td>Black Box</td>
	<td rowspan="3" align="center">Firmansyah</td>
<tr>
	<td>Pengisian Username atau Password salah (User)</td>
	<td>-</td>
	<td>STD-1.1</td>
	<td>Sistem</td>
	<td>Black Box</td>
</tr>
<tr>
	<td>Tidak mengisi Username dan Password (User)</td>
	<td>-</td>
	<td>STD-1.2</td>
	<td>Sistem</td>
	<td>Black Box</td>
</tr>

<!-- user melihat budaya -->
<tr>
	<td rowspan="3" align="center"><strong>Pengujian melihat Budaya pada Android (User)</td>
	<td>Kebenaran dalam menampilkan Budaya dengan meng-klik Ikon Budaya</td>
	<td>SRS-2.2.2</td>
	<td>-</td>
	<td>Sistem</td>
	<td>Black Box</td>
	<td rowspan="3" align="center">Firmansyah</td>
<tr>
	<td>Halaman Budaya tidak muncul karena server error</td>
	<td>-</td>
	<td>STD-2.1</td>
	<td>Sistem</td>
	<td>Black Box</td>
</tr>
<tr>
	<td>Tidak ada koneksi internet</td>
	<td>-</td>
	<td>STD-2.2</td>
	<td>Sistem</td>
	<td>Black Box</td>
</tr>


<!-- admin melakukan login -->
<tr>
	<td rowspan="3" align="center"><strong>Pengujian Login Admin</td>
	<td>Pengisian Username dan Password benar (Admin)</td>
	<td>SRS-2.2.6</td>
	<td>-</td>
	<td>Sistem</td>
	<td>Black Box</td>
	<td rowspan="3" align="center">Diyanti</td>
<tr>
	<td>Pengisian Username atau Password salah (Admin)</td>
	<td>-</td>
	<td>STD-3.1</td>
	<td>Sistem</td>
	<td>Black Box</td>
</tr>
<tr>
	<td>Tidak mengisi Username dan Password (Admin)</td>
	<td>-</td>
	<td>STD-3.2</td>
	<td>Sistem</td>
	<td>Black Box</td>
</tr>
</thead>  
</table>


<h2><br><strong>4 DESKRIPSI DAN HASIL UJI</strong></br></h2>
<table>  
	<thead> 
		<tr>
			<td rowspan="1"><strong>Identifikasi</td>
			<td colspan="3">SRS-2.2.1</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Nama Butir Uji</td>
			<td colspan="3">Pengisian Username atau password benar</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tujuan</td>
			<td colspan="3">Memeriksa apakah User bisa Login dengan mengisi Username dan Password yang sesuai (benar)</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Kondisi Awal</td>
			<td colspan="3">
				<ul>
					<li>Data User sudah terekam pada database (Tabel User)</li>
					<li>User sudah membuka aplikasi dan berada pada halaman Login</li>
				</ul>
			</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tanggal Pengujian</td>
			<td colspan="3">20 Mei 2018</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Penguji</td>
			<td colspan="3">Firmansyah</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Skenario</td>
		</tr>
		<tr>
			<td colspan="4">
				<ul>
					<li>Isi Username dan Password sesuai dengan data (benar)</li>
					<li>Klik tombol Masuk jika Username dan Password sudah diisi</li>
				</ul>
			</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Hasil</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Data yang Diberikan</td>
			<td rowspan="1"><strong>Yang Diharapkan</td>
			<td rowspan="1"><strong>Pengamatan</td>
			<td rowspan="1"><strong>Kesimpulan</td>
		</tr>
		<tr>
			<td rowspan="1">
				<ul>
					<li>Username : Firman</li>
					<li>Password : Firman</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>User bisa masuk ke Halaman Utama</li>
					<li>Data yang diisi benar</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>User bisa masuk ke Halaman Utama jika Login dengan mengisi Username dan Password secara benar dan sesuai data</li>
				</ul>
			</td>
			<td rowspan="1">OK</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Catatan</td>
		</tr>
		<tr>
			<td colspan="4" align="center"> - </td>
		</tr>
	</thead>
</table>

<br></br>

<table>
	<thead>
		<tr>
			<td rowspan="1"><strong>Identifikasi</td>
			<td colspan="3">STD-1.1</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Nama Butir Uji</td>
			<td colspan="3">Pengisian Username atau Password salah</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tujuan</td>
			<td colspan="3">Memeriksa apakah User bisa Login dengan mengisi Username dan Password yang tidak sesuai (salah)</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Kondisi Awal</td>
			<td colspan="3">
				<ul>
					<li>Data User sudah terekam pada database (Tabel User)</li>
					<li>User sudah membuka aplikasi dan berada pada halaman Login</li>
				</ul>
			</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tanggal Pengujian</td>
			<td colspan="3">20 Mei 2018</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Penguji</td>
			<td colspan="3">Firmansyah</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Skenario</td>
		</tr>
		<tr>
			<td colspan="4">
				<ul>
					<li>Isi Username dan Password. Untuk password diisi dengan data yang salah</li>
					<li>Klik tombol Masuk jika Username dan Password sudah diisi</li>
				</ul>
			</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Hasil</td>
		</tr>
		<tr>
			<td rowspan="1" align="center"><strong>Data yang Diberikan</td>
			<td rowspan="1" align="center"><strong>Yang Diharapkan</td>
			<td rowspan="1" align="center"><strong>Pengamatan</td>
			<td rowspan="1" align="center"><strong>Kesimpulan</td>
		</tr>
		<tr>
			<td rowspan="1">
				<ul>
					<li>Username : Firman</li>
					<li>Password : 123</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>User tidak bisa masuk ke Halaman Utama</li>
					<li>Muncul Pesan Error</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>User tidak bisa masuk ke Halaman Utama karena salah dalam mengisi password</li>
					<li>Muncul Toast yang berisi "Username atau Password Salah"</li>
				</ul>
			</td>
			<td rowspan="1">OK</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Catatan</td>
		</tr>
		<tr>
			<td colspan="4" align="center"> - </td>
		</tr>
	</thead>
</table>

<br></br>

<table>
	<thead>	
		<tr>
			<td rowspan="1"><strong>Identifikasi</td>
			<td colspan="3">STD-1.2</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Nama Butir Uji</td>
			<td colspan="3">Tidak mengisi Username dan Password</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tujuan</td>
			<td colspan="3">Memeriksa apakah User bisa Login dengan tidak mengisi Username dan Password</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Kondisi Awal</td>
			<td colspan="3">
				<ul>
					<li>User sudah membuka aplikasi dan berada pada halaman Login</li>
				</ul>
			</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tanggal Pengujian</td>
			<td colspan="3">20 Mei 2018</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Penguji</td>
			<td colspan="3">Firmansyah</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Skenario</td>
		</tr>
		<tr>
			<td colspan="4">
				<ul>
					<li>Langsung klik tombol Masuk tanpa mengisi Username dan Password</li>
				</ul>
			</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Hasil</td>
		</tr>
		<tr>
			<td rowspan="1" align="center"><strong>Data yang Diberikan</td>
			<td rowspan="1" align="center"><strong>Yang Diharapkan</td>
			<td rowspan="1" align="center"><strong>Pengamatan</td>
			<td rowspan="1" align="center"><strong>Kesimpulan</td>
		</tr>
		<tr>
			<td rowspan="1">
				<ul>
					<li>Username : </li>
					<li>Password : </li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>User tidak bisa masuk ke Halaman Utama</li>
					<li>Muncul Pesan Error</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>User tidak bisa masuk ke Halaman Utama karena tidak mengisi Username dan Password</li>
					<li>Muncul Toast yang berisi "Username atau Password Harus Diisi"</li>
				</ul>
			</td>
			<td rowspan="1">OK</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Catatan</td>
		</tr>
		<tr>
			<td colspan="4" align="center">-</td>
		</tr>
	</thead>
</table>

<br></br>

<table>
	<thead>	
		<tr>
			<td rowspan="1"><strong>Identifikasi</td>
			<td colspan="3">SRS-2.2.2</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Nama Butir Uji</td>
			<td colspan="3">Kebenaran dalam menampilkan Budaya dengan meng-klik Ikon Budaya</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tujuan</td>
			<td colspan="3">Memeriksa apakah bisa menampilkan Halaman Budaya</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Kondisi Awal</td>
			<td colspan="3">
				<ul>
					<li>User sudah melakukan Login</li>
					<li>User sedang berada pada Halaman Utama</li>
				</ul>
			</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tanggal Pengujian</td>
			<td colspan="3">20 Mei 2018</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Penguji</td>
			<td colspan="3">Firmansyah</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Skenario</td>
		</tr>
		<tr>
			<td colspan="4">
				<ul>
					<li>Pada Halaman Utama, klik ikon Budaya </li>
				</ul>
			</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Hasil</td>
		</tr>
		<tr>
			<td rowspan="1" align="center"><strong>Data yang Diberikan</td>
			<td rowspan="1" align="center"><strong>Yang Diharapkan</td>
			<td rowspan="1" align="center"><strong>Pengamatan</td>
			<td rowspan="1" align="center"><strong>Kesimpulan</td>
		</tr>
		<tr>
			<td rowspan="1"></td>
			<td rowspan="1">
				<ul>
					<li>Aplikasi bisa menampilkan Halaman Budaya</li>
					<li>Data Budaya muncul pada Halaman Budaya</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>Halaman Budaya bisa ditampilkan jika meng-klik ikon Budaya</li>
				</ul>
			</td>
			<td rowspan="1">OK</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Catatan</td>
		</tr>
		<tr>
			<td colspan="4" align="center"> - </td>
		</tr>
	</thead>
</table>

<br></br>

<table>
	<thead>	
		<tr>
			<td rowspan="1"><strong>Identifikasi</td>
			<td colspan="3">STD-2.1</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Nama Butir Uji</td>
			<td colspan="3">Tidak ada koneksi internet</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tujuan</td>
			<td colspan="3">Memeriksa apakah bisa menampilkan Halaman Budaya dengan internet tidak terkoneksi</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Kondisi Awal</td>
			<td colspan="3">
				<ul>
					<li>User sudah melakukan Login</li>
					<li>User sedang berada pada Halaman Utama</li>
					<li>Data seluler dimatikan</li>
				</ul>
			</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tanggal Pengujian</td>
			<td colspan="3">20 Mei 2018</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Penguji</td>
			<td colspan="3">Firmansyah</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Skenario</td>
		</tr>
		<tr>
			<td colspan="4">
				<ul>
					<li>Pada Halaman Utama, klik ikon Budaya </li>
				</ul>
			</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Hasil</td>
		</tr>
		<tr>
			<td rowspan="1" align="center"><strong>Data yang Diberikan</td>
			<td rowspan="1" align="center"><strong>Yang Diharapkan</td>
			<td rowspan="1" align="center"><strong>Pengamatan</td>
			<td rowspan="1" align="center"><strong>Kesimpulan</td>
		</tr>
		<tr>
			<td rowspan="1"> - </td>
			<td rowspan="1">
				<ul>
					<li>Aplikasi tidak bisa menampilkan Halaman Budaya</li>
					<li>Muncul pesan error "Tidak Ada Koneksi"</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>Halaman Budaya tidak bisa ditampilkan jika koneksi internet dimatikan</li>
					<li>Jika tidak ada koneksi internet, maka akan muncul pesan error</li>
				</ul>
			</td>
			<td rowspan="1">OK</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Catatan</td>
		</tr>
		<tr>
			<td colspan="4" align="center"> - </td>
		</tr>
	</thead>
</table>

<br></br>

<table>  
	<thead> 
		<tr>
			<td rowspan="1"><strong>Identifikasi</td>
			<td colspan="3">SRS-2.2.6</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Nama Butir Uji</td>
			<td colspan="3">Pengisian Username atau password benar (Admin)</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tujuan</td>
			<td colspan="3">Memeriksa apakah Admin bisa Login dengan mengisi Username dan Password yang sesuai (benar)</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Kondisi Awal</td>
			<td colspan="3">
				<ul>
					<li>Data Admin sudah terekam pada database (Tabel User)</li>
					<li>Admin sudah membuka website dan berada pada Halaman Login</li>
				</ul>
			</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tanggal Pengujian</td>
			<td colspan="3">20 Mei 2018</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Penguji</td>
			<td colspan="3">Diyanti</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Skenario</td>
		</tr>
		<tr>
			<td colspan="4">
				<ul>
					<li>Isi Username dan Password sesuai dengan data (benar)</li>
					<li>Klik tombol Masuk jika Username dan Password sudah diisi</li>
				</ul>
			</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Hasil</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Data yang Diberikan</td>
			<td rowspan="1"><strong>Yang Diharapkan</td>
			<td rowspan="1"><strong>Pengamatan</td>
			<td rowspan="1"><strong>Kesimpulan</td>
		</tr>
		<tr>
			<td rowspan="1">
				<ul>
					<li>Username : Admin</li>
					<li>Password : admin</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>User bisa masuk ke Halaman Utama</li>
					<li>Data yang diisi benar</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>Admin bisa masuk ke Halaman Dashboard jika Login dengan mengisi Username dan Password secara benar dan sesuai data</li>
				</ul>
			</td>
			<td rowspan="1">OK</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Catatan</td>
		</tr>
		<tr>
			<td colspan="4" align="center"> - </td>
		</tr>
	</thead>
</table>

<br></br>

<table>
	<thead>
		<tr>
			<td rowspan="1"><strong>Identifikasi</td>
			<td colspan="3">STD-3.1</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Nama Butir Uji</td>
			<td colspan="3">Pengisian Username atau Password salah (Admin)</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tujuan</td>
			<td colspan="3">Memeriksa apakah Admin bisa Login dengan mengisi Username dan Password yang tidak sesuai (salah)</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Kondisi Awal</td>
			<td colspan="3">
				<ul>
					<li>Data Admin sudah terekam pada database (Tabel User)</li>
					<li>Admin sudah membuka website dan berada pada Halaman Login</li>
				</ul>
			</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tanggal Pengujian</td>
			<td colspan="3">20 Mei 2018</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Penguji</td>
			<td colspan="3">Diyanti</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Skenario</td>
		</tr>
		<tr>
			<td colspan="4">
				<ul>
					<li>Isi Username dan Password. Untuk password diisi dengan data yang salah</li>
					<li>Klik tombol Masuk jika Username dan Password sudah diisi</li>
				</ul>
			</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Hasil</td>
		</tr>
		<tr>
			<td rowspan="1" align="center"><strong>Data yang Diberikan</td>
			<td rowspan="1" align="center"><strong>Yang Diharapkan</td>
			<td rowspan="1" align="center"><strong>Pengamatan</td>
			<td rowspan="1" align="center"><strong>Kesimpulan</td>
		</tr>
		<tr>
			<td rowspan="1">
				<ul>
					<li>Username : Admin</li>
					<li>Password : 123</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>Admin tidak bisa masuk ke Halaman Dashboard</li>
					<li>Muncul Pesan Error</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>Admin tidak bisa masuk ke Halaman Dashboard karena salah dalam mengisi password</li>
					<li>Muncul Pesan yang berisi "Username atau Password Salah"</li>
				</ul>
			</td>
			<td rowspan="1">OK</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Catatan</td>
		</tr>
		<tr>
			<td colspan="4" align="center"> - </td>
		</tr>
	</thead>
</table>

<br></br>

<table>
	<thead>	
		<tr>
			<td rowspan="1"><strong>Identifikasi</td>
			<td colspan="3">STD-3.2</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Nama Butir Uji</td>
			<td colspan="3">Tidak mengisi Username dan Password (Admin)</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tujuan</td>
			<td colspan="3">Memeriksa apakah Admin bisa Login dengan tidak mengisi Username dan Password</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Kondisi Awal</td>
			<td colspan="3">
				<ul>
					<li>Admin sudah membuka website dan berada pada Halaman Login</li>
				</ul>
			</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tanggal Pengujian</td>
			<td colspan="3">20 Mei 2018</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Penguji</td>
			<td colspan="3">Diyanti</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Skenario</td>
		</tr>
		<tr>
			<td colspan="4">
				<ul>
					<li>Langsung klik tombol Masuk tanpa mengisi Username dan Password</li>
				</ul>
			</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Hasil</td>
		</tr>
		<tr>
			<td rowspan="1" align="center"><strong>Data yang Diberikan</td>
			<td rowspan="1" align="center"><strong>Yang Diharapkan</td>
			<td rowspan="1" align="center"><strong>Pengamatan</td>
			<td rowspan="1" align="center"><strong>Kesimpulan</td>
		</tr>
		<tr>
			<td rowspan="1">
				<ul>
					<li>Username : </li>
					<li>Password : </li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>Admin tidak bisa masuk ke Halaman Utama</li>
					<li>Muncul Pesan Error</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>Admin tidak bisa masuk ke Halaman Dashboard karena tidak mengisi Username dan Password</li>
					<li>Muncul pesan yang berisi "Username atau Password Harus Diisi"</li>
				</ul>
			</td>
			<td rowspan="1">OK</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Catatan</td>
		</tr>
		<tr>
			<td colspan="4" align="center">-</td>
		</tr>
	</thead>
</table>

<br></br>