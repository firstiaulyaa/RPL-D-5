


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
</tr>
		<tr>
			<td align="center"><strong>SRS/SDD</td>
			<td align="center"><strong>SPMP</td>
		</tr>
<tr>
<td rowspan="2" align="center"><strong>Jenis Pengujian</td>
<td rowspan="2" align="center"><strong>Teknik Pengujian</td>
<td rowspan="2" align="center"><strong>Penguji</td>
</tr>

</thead>  
</table>


<h2><br><strong>4 DESKRIPSI DAN HASIL UJI</strong></br></h2>
<table>  
	<thead> 
		<tr>
			<td>Identifikasi</td>
			<td>-------</td>
		</tr>
		<tr>
			<td>Nama Butir Uji</td>
			<td>-------</td>
		</tr>
		<tr>
			<td>Tujuan</td>
			<td>-------</td>
		</tr>
		<tr>
			<td>Kondisi Awal</td>
			<td>-------</td>
		</tr>
		<tr>
			<td>Tanggal Pengujian</td>
			<td>-------</td>
		</tr>
		<tr>
			<td>Penguji</td>
			<td>-------</td>
		</tr>
		<tr>
			<td colspan="2">Skenario</td>
		</tr>
		<tr>
			<td colspan="2">
				<ul>
					<li>------</li>
					<li>------</li>
				</ul>
			</td>
		</tr>
		<tr>
			<td colspan="2">Hasil</td>
		</tr>
		<tr >
			<td colspan="2">
				<ul>
					<li>------</li>
					<li>------</li>
				</ul>
			</td>
		</tr>
		<tr>
			<td colspan="2">Catatan</td>
		</tr>
		<tr>
			<td>
				<ul>
					<li>------</li>
					<li>------</li>
				</ul>
			</td>
		</tr>
	</thead>
</table>