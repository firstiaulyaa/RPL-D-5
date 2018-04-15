
<h1 align="center" id="software-requirements-specification">SOFTWARE DESIGN DOCUMENT</h1>  
<p align="center"><strong>Version 1.0</strong><br> 
<p align="center"><strong> 15 Maret 2018<br>  </strong><br>
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


<h2><br><strong>1. PENDAHULUAN</strong></br></h3>
<h3><br><strong>1.1 Tujuan Penulisan Dokumen</strong></br></h2>
<p>Tujuan dibuatnya dokumen SDD ini adalah untuk menjelaskan tentang  -------- apa saja yang digunakan pada Aplikasi BUSAYU (Budaya dan Pariwisata Kab. Indramayu) seperti DFD dan lain-lain.</p>  


<h3><br><strong>1.2 Lingkup Masalah</strong></br></h2>
<p>Sistem dari perangkat lunak ini akan menjadi Aplikasi Publik, yaitu aplikasi yang akan digunakan oleh masyarakat khusunya masyarakat Kab. Indramayu. BUSAYU (Aplikasi Budaya dan Pariwisata Kab, Indramayu) adalah aplikasi berbasis Android yang dirancang untuk mengetahui dan mempermudah pengguna untuk mencari informasi tentang kebudayaan, pariwisata, dan kegiatan yang ada di Indramayu. Dan pengguna juga bisa mengajukan pengaduan tentang kebudayaan dan pariwisata di Indramayu.<br></p>  

<h3><br><strong>1.3 Definisi dan Istilah</strong></br></h3>
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
			<td>SDD</td>  
			<td> Software Design Document</td>  
		</tr>  
			<td>Pengaduan</td>  
			<td> Berisi pengaduan dari user (Pengguna)</td>  
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

<h3><br><strong>1.4 Referensi</strong></br></h3>
<ul>
	<li>IEEE, IEEE Draft Standard for Software Design Descriptions. IEEE
   P1 01 6/D5.0; 1 2 December 2005</li>
  	<li>Eka Ismantohadi & Moh. Yani, Software Design Document (SDD).
   2018</li>
</ul>

<h3><br><strong>1.5 Ikhtisar Dokumen</strong></h3></br>
<strong>Bab I Pendahuluan, terdiri dari :</strong><br>
1.1 Tujuan Penulisan Dokumen<br>
1.2 Lingkup Masalah<br>
1.3 Definisi dan Istilah<br>
1.4 Referensi<br>
1.5 Ikhtisar Dokumen<br>

<strong>Bab II Deskripsi Perancangan Global</strong><br>
2.1 Rancangan Lingkungan Implementasi<br>
2.2 Deskripsi Data<br>
2.2.1 Definisi Domain<br>
2.2.2 Conceptual Data Model<br>
2.2.3 Physical Data Model<br>
2.2.4 Daftar Tabel Aplikasi<br><br>
2.3 Deskripsi Modul<br>

<strong>Bab III Deskripsi Perancangan Rinci</strong><br>
3.1 Diagram Konteks<br>
3.1.1 DFD Level 0<br>
3.1.2 DFD Level 1 Proses M<br>
3.1.3 DFD Level 1 Proses N<br>
3.2 Deskripsi Rinci Tabel<br>
3.2.1 Table A<br>
3.2.2 Table B<br>
3.3 Deskripsi Rinci Modul<br>
3.3.1 D Modul<br>
3.3.1.1 Fungsi Modul<br>
3.3.1.2 Spesifikasi Layar Utama<br>
3.3.1.3 Spesifikasi Query<br>
3.3.1.4 Spesifikasi Field Data Layar<br>
3.3.1.5 Spesifikasi Obyek Pada Layer<br>
3.3.1.6 Spesifikasi Proses/Algoritma<br>
3.4 Matriks Keturunan<br>


<h2><br><strong>2. DESKRIPSI PERANCANGAN GLOBAL</strong></br></h2>
<h3><strong>2.1 Rancangan Lingkungan Implementasi</strong></h3>

<table>  
	<thead>  
		<tr>  
			<th>No.</th>  
			<th>Rancangan Lingkungan Implementasi</th>  
			<th>Keterangan</th>  
		</tr>
	</thead>  
	<tbody>  
		<tr>  
			<td>1.</td>  
			<td>Sistem Operasi</td>
			<td>
				<ul>
					<li>Pada Aplikasi Server menggunakan Sublime Text untuk membuat web</li>
					<li>Pada Aplikasi client menggunakan Android Studio untuk membuat aplikasi berbasis mobile</li>
					<li>Pembuatan proposal menggunakan aplikasi Microsoft Word 2010</li>
				</ul>
			</td>
		</tr>  
		<tr>  
			<td>2.</td>  
			<td>DBMS</td>
			<td>
				MySQL
			</td>
		</tr>  
		<tr>  
			<td>3.</td>  
			<td>Filling System</td>
			<td>
				-----------
			</td>
		</tr>
		<tr>  
			<td>4.</td>  
			<td>Bahasa Pemrograman</td>
			<td>
				<ul>
					<li>Java untuk bahasa pemrograman yang digunakan pada platfom android</li>
					<li>Php untuk bahasa pemrograman yang digunakan pada web</li>
				</ul>
			</td>
		</tr>
	</tbody>  
</table>
<br>


<h3><br><strong>2.2 Deskripsi Data</strong></br></h3>

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
	<tr>  
		<td>gambar</td>  
		<td>Varchar</td>   
		<td>Berisi gambar pariwisata  </td>   
	</tr>
</table> 


<h2><br><strong>3. PENJELASAN DEKOMPOSISI</strong></br></h2>
<h3><strong>3.1 Dekomposisi Model</strong></h3>
<h4><strong>3.1.1 Diagram Konteks</strong></h4>
<p>Diagram konteks merupakan tingkatan tertinggi dalam diagram aliran data dan hanya memuat satu proses, menunjukkan sistem secara keseluruhan. Berikut merupakan diagram konteks dari aplikasi ini. </p>
<p align="center">  
	<img src="https://lh3.googleusercontent.com/-L6CJeZHFHZQ/WqTi-IVUFZI/AAAAAAAAAKc/j44KbgZwpywg3PX7kgJXQlybxX4hodvXQCL0BGAs/w530-d-h288-n/diagram%2Bkonteks.png=s300" alt="enter image description here" title="diagram konteks"></p>
<p align="center">

<h4><br><strong>3.1.2 Diagram Level 0</strong></br></h4>
<p>Diagram 0 adalah diagram yang menggambarkan proses dari data flow diagram. Diagram 0 memberikan pandangan secara menyeluruh mengenai sistem yang ditangani, menunjukkan tentang fungsi-fungsi utama atau proses yang ada, aliran data, dan eksternal entity. Berikut merupakan diagram 0 dari aplikasi ini.</p>
<p align="center">
<img src="https://3.bp.blogspot.com/-hNd4NI8q9H0/WrYO9X72pqI/AAAAAAAAAGA/vLy5oHTnjo8t5ru4H_zpE2DAsbkwbX3QACLcBGAs/s1600/nol.png=s300" alt="diagram0" title="diagram0">
<p align="center">

<h3><br><strong>3.2 Dekomposisi Proses Konkuren</strong></br></h3>
<h4><strong>3.2.1 Diagram Level 1 </strong></h4>
<ul>
	<li><p><strong>User</p></li>
</ul>
<p>DFD Level 1 : Merupakan penjelasan dari DFD Level 0  dan berisi tentang Data User.<br></p>

![enter image description here](https://2.bp.blogspot.com/-cDJy2hE-c9U/WrHOLmYQ1LI/AAAAAAAAAE4/TinICzT4038Y0ZLbUHCVm7QpY4DJEzT3ACLcBGAs/s1600/level+1+user.png)
</p><p align="center">

<h4><br><strong>3.2.2 Diagram Level 1 </strong></br></h4>
<ul>
	<li><strong>Pengaduan</strong></li>
</ul>
<p>DFD Level 1 : Merupakan penjelasan dari DFD Level 0  dan berisi tentang Data Pengaduan.<br></p>

![enter image description here](https://4.bp.blogspot.com/-P7HHtqTi8d4/WrHPMZLghNI/AAAAAAAAAFA/r7TfauEEYkcnYsdyfr30yEZwv2ZgCHTCwCLcBGAs/s1600/level+1+pengaduan.png)
</p><p align="center">

<h4><br><strong>3.2.3 Diagram Level 1 </strong></br></h4>
<ul>
	<li><strong>Budaya</strong></li>
</ul>
<p>DFD Level 1 : Merupakan penjelasan dari DFD Level 0  dan berisi tentang Data Budaya.<br></p>

![enter image description here](https://1.bp.blogspot.com/-AQCtqUkeVuI/WrHP3jCPu-I/AAAAAAAAAFI/MolwQYQTxIMVuhTFaz4wY38VRvoqH2-FgCLcBGAs/s1600/level+1+budaya.png)
</p><p align="center">=

<h4><br><strong>3.2.4 Diagram Level 1</strong></br></h4>
<ul>
	<li><strong>Pariwisata</strong></li>
</ul>
<p>DFD Level 1 : Merupakan penjelasan dari DFD Level 0  dan berisi tentang Data Pariwisata.<br></p>

![enter image description here](https://1.bp.blogspot.com/-oIDmo9ECu4E/WrYPgYN70lI/AAAAAAAAAGI/UiAjccjFbN8TVkEYdLGu6VIZaBYtAZXaQCLcBGAs/s1600/1+pariwisata.png)
</p><p align="center">

<h4><br><strong>3.2.5 Diagram Level 1 </strong></br></h4>
<ul>
	<li><strong>Kegiatan</strong></li>
</ul>
<p>DFD Level 1 : Merupakan penjelasan dari DFD Level 0  dan berisi tentang Data Kegiatan.<br></p>

![enter image description here](https://4.bp.blogspot.com/-bnMlxNGfBIU/WrHR9AAnH4I/AAAAAAAAAFc/MMb643b_TUMqS5OGemAKiNCmALOpPF2kQCLcBGAs/s1600/level+1+event.png)
</p><p align="center">

<h4><br><strong>3.2.6 Diagram Level 2 </strong></br></h4>
<ul>
	<li><strong>Daftar Pariwisata</strong></li>
</ul>
<p>DFD Level 2 : Merupakan penjelasan dari DFD Level 1 (Pariwisata) dan berisi tentang Data Daftar Pariwisata<br></p>

![enter image description here](https://4.bp.blogspot.com/-qBBwV2Y0oTg/WrHSzEZtxpI/AAAAAAAAAFk/jdZafO48Nn49ZX-OJNjl2MUJ-AOWufBNgCLcBGAs/s1600/level+2+daftar+pariwisata.png)
</p><p align="center">

<h4><br><strong>3.2.7 Diagram Level 2 </strong></br></h4>
<ul>
	<li><strong>Jenis Pariwisata</strong></li>
</ul>
<p>DFD Level 2 : Merupakan penjelasan dari DFD Level 1 (Pariwisata) dan berisi tentang Data Jenis Pariwisata<br></p>

![enter image description here](https://1.bp.blogspot.com/-rASx0Mw4IaU/WrHRGaQUREI/AAAAAAAAAFU/4Y3x1oZYmtI_n62zZPLgMwKQHIaH-IZcQCLcBGAs/s1600/level+2+daftar+pariwisata.png)
</p><p align="center">

