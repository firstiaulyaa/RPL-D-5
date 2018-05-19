


<h1 align="center" id="software-requirements-specification">SOFTWARE TESTING DOCUMENT</h1>  
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
<p>Dalam dokumen ini berisi 3 bagian utama yaitu Pendahuluan, Identifikasi dan Rencana Pengujian, Deskripsi dan Uji Hasil. </p>

<h3><br><strong>1.4	Definisi dan Singkatan </strong></br></h3>
<table>  
	<thead>  
<tr>
<td><strong>SRS</strong></td>
<td>(Software Requirements Spesification) merupakan dokumen yang dibuat untuk menjelaskan tentang spesifikasi kebutuhan apa saja yang digunakan dalam aplikasi</td>
</tr>
<tr>
<td><strong>DFD</strong></td>
<td>(Data Flow Diagram) adalah diagram dan notasi yang digunakan untuk menunjukkan aliran data pada perangkat lunak. </td>
</tr>
<tr>
<td><strong>ERD</strong></td>
<td>(Entity Relationship Diagram) adalah diagram dan notasi yang digunakan untuk merepresentasikan struktur data statis pada perangkat lunak. </td>
</tr>
</thead>  
</table> 

<h3><br><strong>1.5	Dokumen Referensi </strong></br></h3>
<ul>
	<li>Sistem Pentiketan Elektronik Konser.2013. Perencanaan, Deskripsi, Dan Hasil Uji Perangkat Lunak. Bogor.</li>
	<li>SPMP</li>
	<li>SDD</li>
</ul>



<h2><br><strong>2.	LINGKUNGAN PENGUJIAN PERANGKAT LUNAK </strong></br></h2>
<h3><br><strong>2.1	Perangkat Lunak Pengujian </strong></br></h3>
<p>Perangkat lunak ini (BUSAYU) diujikan dengan beberapa perangkat lunak lain, yaitu: </p>

<table>  
	<thead>  
<tr>
<td><strong>Sistem Operasi</strong></td>
<td>
	<ul>
	<li>Web : Windows 10 </li>
	<li>Android : </li></td>
</tr>
<tr>
<td><strong>Bahasa Pemrograman</strong></td>
<td>Java, PHP</td>
</tr>
<tr>
<td><strong>Database</strong></td>
<td>MySQL</td>
</tr>
</thead>  
</table>


<h3><br><strong>2.2	Perangkat Keras Pengujian </strong></br></h3>
<p>Perangkat keras yang diperlukan untuk menguji aplikasi BUSAYU ini adalah satu set komputer dengan spesifikasi : </p>

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
<td><strong>Devices</strong></td>
<td>--------</td>
</tr>
<tr>
<td><strong>RAM</strong></td>
<td>-------</td>
</tr>
<tr>
<td><strong>Internal Memory</strong></td>
<td>------</td>
</tr>
</thead>  
</table>  


<h3><br><strong>2.3	Material Pengujian </strong></br></h3>
<p>Pada Aplikasi BUSAYU ini seorang User dapat mengakses informasi tentang budaya dan pariwisata di Kabupaten Indramayu melalui smartphone dengan sistem operasi Android. User dapat langsung menggunakan aplikasi dengan memasukkan username dan password yang didapat saat mendaftar. Setelah mendapatkan akun, User dapat memilih menu apa saja yang diinginkan, serta bisa mengajukan pengaduan tentang budaya dan pariwisata Kabupaten Indramayu yang selanjutnya data tersebut dikirim ke website yang dikelola oleh Admin.</p>

<h3><br><strong>2.4	Sumber Daya Manusia</strong></br></h3>
<p>Persyaratan sumber daya manusia yang akan terlibat dalam proses pengujian aplikasi ini adalah :</p>
<ul>
	<li>Memahami konsep pemrograman berorientasi objek dalam bahasa Java dan PHP</li>
	<li>Memahami konsep database MySQL</li>
</ul>

<h3><br><strong>2.5	Prosedur Umum Pengujian </strong></br></h3>
<h4><br><strong>2.5.1	Pengenalan dan Latihan </strong></br></h4>
<p>Penguji aplikasi ini hanya diberikan latihan kembali tentang MySQL dan PHP, dan pengenalan lebih lanjut tentang Java. Pada dasarnya penguji telah memiliki pengetahuan tentang hal yang sudah disebutkan sebelumnya tetapi latihan yang diberikan hanya bersifat penyegaran kembali.</p>

<h4><br><strong>2.5.2 Persiapan Awal </strong></br></h4>
<h5><br><strong>2.5.2.1 Persiapan Prosedural</strong></br></h5>
<p>Pengujian ini dilakukan diluar jam perkuliahan. </p>

<h5><br><strong>2.5.2.2 Persiapan Perangkat Keras </strong></br></h5>
<p>Perangkat keras yang perlu dipersiapkan adalah sebuah laptop yang dilengkapi dengan :</p>
<ul>
	<li>Processor : Intel® Core i3-4005U @1.70Ghz</li>
	<li>Memory : 6 GB DDR3</li>
	<li>Harddisk : 500 GB</li>
</ul>

<h5><br><strong>2.5.2.3 Persiapan Perangkat Lunak </strong></br></h5>
<p>Persiapan yang harus dilakukan untuk menyiapkan aplikasi yang diuji di lingkungan sistem operasi Microsoft Windows 10 dan Android adalah sebagai berikut :<p>
	<ul>
		<li>Persiapkan sistem operasi Microsoft Windows dan Android .</li>
		<li>Aplikasi yang akan di uji untuk Web disimpan di dalam C:\XAMPP\htdocs\busayu. Sedangkan untuk Android disimpan di smarthphone.</li>
		<li>Browser Google Chrome.</li>
		<li>Database di import ke phpMyAdmin di database busayu.sql.</li>
		<li>Sublime Text untuk melihat source code pada website dan Android Studio untuk melihat source code pada aplikasi.</li>
	</ul> 


<h4><br><strong>2.5.3 Pelaksanaan Pelaksanaan </strong></br></h4>
<h4><br><strong>2.5.4 Pelaporan Hasil Dokumen </strong></br></h4>



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
	<td>Pengisian Username atau password benar</td>
	<td>SRS-2.2.1</td>
	<td>-</td>
	<td>Sistem</td>
	<td>--------</td>
	<td>--------</td>
<tr>
	<td>Pengisian Username atau Password salah</td>
	<td>-</td>
	<td>STD-01</td>
	<td>Sistem</td>
	<td>--------</td>
	<td>--------</td>
</tr>
<tr>
	<td>Tidak ada koneksi internet</td>
	<td>-</td>
	<td>STD-02</td>
	<td>Sistem</td>
	<td>--------</td>
	<td>--------</td>
</tr>

<!-- user melakukan registrasi -->
<tr>
	<td rowspan="3" align="center"><strong>Pengujian Register User</td>
	<td>Pengisian Nama User, Username, Email, dan Password benar</td>
	<td>--------</td>
	<td>-</td>
	<td>Sistem</td>
	<td>--------</td>
	<td>--------</td>
<tr>
	<td>Pengisian Nama User, Username, Email, dan Password salah (tidak terisi)</td>
	<td>-</td>
	<td>STD-03</td>
	<td>Sistem</td>
	<td>--------</td>
	<td>--------</td>
</tr>
<tr>
	<td>Tidak ada koneksi internet</td>
	<td>-</td>
	<td>STD-04</td>
	<td>Sistem</td>
	<td>--------</td>
	<td>--------</td>
</tr>


<!-- user melihat budaya -->
<tr>
	<td rowspan="3" align="center"><strong>Pengujian melihat Budaya pada Android (User)</td>
	<td>Kebenaran dalam menampilkan Budaya dengan meng-klik Ikon Budaya</td>
	<td>SRS-2.2.2</td>
	<td>-</td>
	<td>Sistem</td>
	<td>--------</td>
	<td>--------</td>
<tr>
	<td>Halaman Budaya tidak muncul karena server error</td>
	<td>-</td>
	<td>STD-05</td>
	<td>Sistem</td>
	<td>--------</td>
	<td>--------</td>
</tr>
<tr>
	<td>Tidak ada koneksi internet</td>
	<td>-</td>
	<td>STD-06</td>
	<td>Sistem</td>
	<td>--------</td>
	<td>--------</td>
</tr>

<!-- user melihat menu pariwisata -->
<tr>
	<td rowspan="3" align="center"><strong>Pengujian melihat menu pariwisata pada Android (User)</td>
	<td>Kebenaran dalam menampilkan Menu Pariwisata dengan meng-klik Ikon Pariwisata</td>
	<td>SRS-2.2.3</td>
	<td>-</td>
	<td>Sistem</td>
	<td>--------</td>
	<td>--------</td>
<tr>
	<td>Menu pariwisata tidak muncul karena server error</td>
	<td>-</td>
	<td>STD-07</td>
	<td>Sistem</td>
	<td>--------</td>
	<td>--------</td>
</tr>
<tr>
	<td>Tidak ada koneksi internet</td>
	<td>-</td>
	<td>STD-08</td>
	<td>Sistem</td>
	<td>--------</td>
	<td>--------</td>
</tr>

<!-- user melihat kegiatan -->
<tr>
	<td rowspan="3" align="center"><strong>Pengujian melihat Kegiatan pada Android (User)</td>
	<td>Kebenaran dalam menampilkan Halaman Kegiatan dengan meng-klik Ikon Kegiatan</td>
	<td>SRS-2.2.4</td>
	<td>-</td>
	<td>Sistem</td>
	<td>--------</td>
	<td>--------</td>
<tr>
	<td>Menu pariwisata tidak muncul karena server error</td>
	<td>-</td>
	<td>STD-09</td>
	<td>Sistem</td>
	<td>--------</td>
	<td>--------</td>
</tr>
<tr>
	<td>Tidak ada koneksi internet</td>
	<td>-</td>
	<td>STD-10</td>
	<td>Sistem</td>
	<td>--------</td>
	<td>--------</td>
</tr>

<!-- user mengisi form pengaduan -->
<tr>
	<td rowspan="3" align="center"><strong>Pengujian mengajukan pengaduan pada Android (User)</td>
	<td>Pengisian form Pengaduan benar</td>
	<td>SRS-2.2.5</td>
	<td>-</td>
	<td>Sistem</td>
	<td>--------</td>
	<td>--------</td>
<tr>
	<td>Pengisian form Pengaduan salah</td>
	<td>-</td>
	<td>STD-11</td>
	<td>Sistem</td>
	<td>--------</td>
	<td>--------</td>
</tr>
<tr>
	<td>Tidak ada koneksi internet</td>
	<td>-</td>
	<td>STD-12</td>
	<td>Sistem</td>
	<td>--------</td>
	<td>--------</td>
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
			<td colspan="3">-------</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Penguji</td>
			<td colspan="3">-------</td>
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
					<li>Username : </li>
					<li>Password : </li>
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
					<li>------</li>
					<li>------</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>------</li>
					<li>------</li>
				</ul>
			</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Catatan</td>
		</tr>
		<tr>
			<td colspan="4">
				<ul>
					<li>------</li>
					<li>------</li>
				</ul>
			</td>
		</tr>
	</thead>
</table>

<br></br>

<table>
	<thead>
		<tr>
			<td rowspan="1"><strong>Identifikasi</td>
			<td colspan="3">STD-01</td>
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
			<td colspan="3">-------</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Penguji</td>
			<td colspan="3">-------</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Skenario</td>
		</tr>
		<tr>
			<td colspan="4">
				<ul>
					<li>Isi Username dan Password tidak sesuai dengan data (salah)</li>
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
					<li>Username : </li>
					<li>Password : </li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>User tidak bisa masuk ke Halaman Utama</li>
					<li>------</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>------</li>
					<li>------</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>------</li>
					<li>------</li>
				</ul>
			</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Catatan</td>
		</tr>
		<tr>
			<td colspan="4">
				<ul>
					<li>------</li>
					<li>------</li>
				</ul>
			</td>
		</tr>
	</thead>
</table>

<table>
	<thead>	
		<tr>
			<td rowspan="1"><strong>Identifikasi</td>
			<td colspan="3">STD-02</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Nama Butir Uji</td>
			<td colspan="3">Tidak ada koneksi internet</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tujuan</td>
			<td colspan="3">-------</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Kondisi Awal</td>
			<td colspan="3">
				<ul>
					<li>-------</li>
					<li>-------</li>
				</ul>
			</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tanggal Pengujian</td>
			<td colspan="3">-------</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Penguji</td>
			<td colspan="3">-------</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Skenario</td>
		</tr>
		<tr>
			<td colspan="4">
				<ul>
					<li>------</li>
					<li>------</li>
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
					<li>------</li>
					<li>------</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>------</li>
					<li>------</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>------</li>
					<li>------</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>------</li>
					<li>------</li>
				</ul>
			</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Catatan</td>
		</tr>
		<tr>
			<td colspan="4">
				<ul>
					<li>------</li>
					<li>------</li>
				</ul>
			</td>
		</tr>
	</thead>
</table>

<br></br>

<table>
	<thead>	
		<tr>
			<td rowspan="1"><strong>Identifikasi</td>
			<td colspan="3">---------</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Nama Butir Uji</td>
			<td colspan="3">Pengisian Nama User, Username, Email, dan Password benar</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tujuan</td>
			<td colspan="3">-------</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Kondisi Awal</td>
			<td colspan="3">
				<ul>
					<li>-------</li>
					<li>-------</li>
				</ul>
			</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tanggal Pengujian</td>
			<td colspan="3">-------</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Penguji</td>
			<td colspan="3">-------</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Skenario</td>
		</tr>
		<tr>
			<td colspan="4">
				<ul>
					<li>------</li>
					<li>------</li>
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
					<li>------</li>
					<li>------</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>------</li>
					<li>------</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>------</li>
					<li>------</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>------</li>
					<li>------</li>
				</ul>
			</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Catatan</td>
		</tr>
		<tr>
			<td colspan="4">
				<ul>
					<li>------</li>
					<li>------</li>
				</ul>
			</td>
		</tr>
	</thead>
</table>

<br></br>

<table>
	<thead>	
		<tr>
			<td rowspan="1"><strong>Identifikasi</td>
			<td colspan="3">STD-03</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Nama Butir Uji</td>
			<td colspan="3">Pengisian Nama User, Username, Email, dan Password salah</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tujuan</td>
			<td colspan="3">-------</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Kondisi Awal</td>
			<td colspan="3">
				<ul>
					<li>-------</li>
					<li>-------</li>
				</ul>
			</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tanggal Pengujian</td>
			<td colspan="3">-------</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Penguji</td>
			<td colspan="3">-------</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Skenario</td>
		</tr>
		<tr>
			<td colspan="4">
				<ul>
					<li>------</li>
					<li>------</li>
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
					<li>------</li>
					<li>------</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>------</li>
					<li>------</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>------</li>
					<li>------</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>------</li>
					<li>------</li>
				</ul>
			</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Catatan</td>
		</tr>
		<tr>
			<td colspan="4">
				<ul>
					<li>------</li>
					<li>------</li>
				</ul>
			</td>
		</tr>
	</thead>
</table>

<br></br>

<table>
	<thead>	
		<tr>
			<td rowspan="1"><strong>Identifikasi</td>
			<td colspan="3">STD-04</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Nama Butir Uji</td>
			<td colspan="3">Tidak ada koneksi internet</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tujuan</td>
			<td colspan="3">-------</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Kondisi Awal</td>
			<td colspan="3">
				<ul>
					<li>-------</li>
					<li>-------</li>
				</ul>
			</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tanggal Pengujian</td>
			<td colspan="3">-------</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Penguji</td>
			<td colspan="3">-------</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Skenario</td>
		</tr>
		<tr>
			<td colspan="4">
				<ul>
					<li>------</li>
					<li>------</li>
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
					<li>------</li>
					<li>------</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>------</li>
					<li>------</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>------</li>
					<li>------</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>------</li>
					<li>------</li>
				</ul>
			</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Catatan</td>
		</tr>
		<tr>
			<td colspan="4">
				<ul>
					<li>------</li>
					<li>------</li>
				</ul>
			</td>
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
			<td colspan="3">-------</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Kondisi Awal</td>
			<td colspan="3">
				<ul>
					<li>-------</li>
					<li>-------</li>
				</ul>
			</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tanggal Pengujian</td>
			<td colspan="3">-------</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Penguji</td>
			<td colspan="3">-------</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Skenario</td>
		</tr>
		<tr>
			<td colspan="4">
				<ul>
					<li>------</li>
					<li>------</li>
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
					<li>------</li>
					<li>------</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>------</li>
					<li>------</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>------</li>
					<li>------</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>------</li>
					<li>------</li>
				</ul>
			</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Catatan</td>
		</tr>
		<tr>
			<td colspan="4">
				<ul>
					<li>------</li>
					<li>------</li>
				</ul>
			</td>
		</tr>
	</thead>
</table>

<br></br>

<table>
	<thead>	
		<tr>
			<td rowspan="1"><strong>Identifikasi</td>
			<td colspan="3">STD-05</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Nama Butir Uji</td>
			<td colspan="3">Tidak ada koneksi internet</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tujuan</td>
			<td colspan="3">-------</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Kondisi Awal</td>
			<td colspan="3">
				<ul>
					<li>-------</li>
					<li>-------</li>
				</ul>
			</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tanggal Pengujian</td>
			<td colspan="3">-------</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Penguji</td>
			<td colspan="3">-------</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Skenario</td>
		</tr>
		<tr>
			<td colspan="4">
				<ul>
					<li>------</li>
					<li>------</li>
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
					<li>------</li>
					<li>------</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>------</li>
					<li>------</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>------</li>
					<li>------</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>------</li>
					<li>------</li>
				</ul>
			</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Catatan</td>
		</tr>
		<tr>
			<td colspan="4">
				<ul>
					<li>------</li>
					<li>------</li>
				</ul>
			</td>
		</tr>
	</thead>
</table>

<br></br>

<table>
	<thead>	
		<tr>
			<td rowspan="1"><strong>Identifikasi</td>
			<td colspan="3">STD-06</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Nama Butir Uji</td>
			<td colspan="3">Halaman Budaya tidak muncul karena server error</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tujuan</td>
			<td colspan="3">-------</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Kondisi Awal</td>
			<td colspan="3">
				<ul>
					<li>-------</li>
					<li>-------</li>
				</ul>
			</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tanggal Pengujian</td>
			<td colspan="3">-------</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Penguji</td>
			<td colspan="3">-------</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Skenario</td>
		</tr>
		<tr>
			<td colspan="4">
				<ul>
					<li>------</li>
					<li>------</li>
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
					<li>------</li>
					<li>------</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>------</li>
					<li>------</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>------</li>
					<li>------</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>------</li>
					<li>------</li>
				</ul>
			</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Catatan</td>
		</tr>
		<tr>
			<td colspan="4">
				<ul>
					<li>------</li>
					<li>------</li>
				</ul>
			</td>
		</tr>
	</thead>
</table>