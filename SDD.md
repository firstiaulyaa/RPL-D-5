<h1 align="center" id="software-requirements-specification">SOFTWARE DESIGN DOCUMENT</h1>  
<p align="center"><strong>Version 1.0</strong><br> 
<p align="center"><strong> 15 Maret 2018<br>  </strong><br>
<p align="center"><strong>"APLIKASI BUDAYA DAN PARIWISATA KABUPATEN INDRAMAYU BERRBASIS ANDROID"<br><br></strong></p> 
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


<P><h3><strong>1. PENDAHULUAN</strong></h3></P>
<P><strong>1.1 Tujuan Penulisan Dokumen</strong></P>
<p>Dokumen ini bertujuan untuk menjelaskan secara detail mengenai aplikasi yang kami buat yang berjudul “Aplikasi Budaya dan Pariwisata Kabupaten Indramayu berbasis Android". Pada dokumen ini akan menjelaskan tentang DFD dan lain-lain.</p>  


<p><strong>1.2 Lingkup Masalah</strong></p>
<p>Aplikasi Budaya dan Pariwisata Indramayu adalah salah satu aplikasi berbasis android yang digunakan untuk seluruh masyarakat, khususnya masyarakat yang berada di daerah Indramayu untuk mengetahui kebudayaan yang ada di Indramayu dan event atau lomba yang akan diselenggarakan oleh Dinas Kebudayaan dan Pariwisata Kabupaten Indramayu.<br>  
Pada Proyek ini dibuat sistem berbasis android dimana pengolahan informasi dan data diakses melalui smartphone dengan sistem operasi android.</p>  

<p><strong>1.3 Definisi dan Istilah</strong></p>

<p><table>  
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
<td>SDD</td>  
<td> Software Design Description</td>  
</tr>  
<td>Pengaduan</td>  
<td> Berisi pengaduan dari user (Pengguna)</td>  
</tr>  
</tbody>  </p>
<br>

<p><strong>1.4 Referensi</strong></p>

 - <p>IEEE, IEEE Draft Standard for Software Design Descriptions. IEEE
   P1 01 6/D5.0; 1 2 December 2005</p>
   
 - <p>Eka Ismantohadi & Moh. Yani, Software Design Document (SDD).
   2018</p>
<p><strong>1.5 Ikhtisar Dokumen</strong></p>
<strong>Bab I Pendahuluan, terdiri dari :</strong><br>
1.1 Tujuan Penulisan Dokumen<br>
1.2 Lingkup Masalah<br>
1.3 Definisi dan Istilah<br>
1.4 Referensi<br>
1.5 Ikhtisar Dokumen<br>

<strong>Bab II Deskripsi Perancangan Global</strong>
2.1 Rancangan Lingkungan Implementasi

2.2 Deskripsi Data
2.2.1 Definisi Domain/type
2.2.2 Conceptual Data Model
2.2.3 Physical Data Model
2.2.4 Daftar Tabel Aplikasi
2.3 Deskripsi Modul

<strong>Bab III Deskripsi Perancangan Rinci</strong>
3.1 Diagram Konteks
3.1.1 DFD Level 0
3.1.2 DFD Level 1 Proses M
3.1.3 DFD Level 1 Proses N

3.2 Deskripsi Rinci Tabel
3.2.1 Table A
3.2.2 Table B

3.3 Deskripsi Rinci Modul
3.3.1 D Modul
3.3.1.1 Fungsi Modul
3.3.1.2 Spesifikasi Layar Utama
3.3.1.3 Spesifikasi Query
3.3.1.4 Spesifikasi Field Data Layar
3.3.1.5 Spesifikasi Obyek Pada Layer
3.3.1.6 Spesifikasi Proses/Algoritma
3.4 Matriks Keturunan


<p><strong><h3>2. DESKRIPSI PERANCANGAN GLOBAL</h3></strong></p>

<p><strong>2.1 Rancangan Lingkungan Implementasi</strong></p>

<p><table>  
<thead>  
<tr>  
<th>No.</th>  
<th>Rancangan Lingkungan Implementasi</th>  
<th>Keterangan</th>  
</tr>  
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
<ul>
<li>Firebase</li>
</ul>
</td>
</tr>  
<tr>  
<td>3.</td>  
<td>Filling System</td>
<td>
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
</thead>
</table>
<br>


<p><strong>2.2 Deskripsi Data</strong></p>

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
<td>Id_user</td>  
<td>Integer</td>  
<td>Nomor auto increment Id_user</td>    
</tr>  
<tr>  
<td>Username</td>  
</td> 
<td>Varchar</td>   
<td>Berisi Nama atau nomor untuk dapat mengakses aplikasi</td>   
</tr>  
<tr>  
<td>Password</td>  
</td> 
<td>Varchar</td>   
<td>Berisi password untuk dapat mengakses aplikasi </td>   
</tr>  
<tr>  
<td>Nama user</td>  
</td> 
<td>Varchar</td>   
<td>Untuk login dan mendaftar aplikasi </td>   
</tr>   
<tr>  
<td>Email</td>  
</td> 
<td>Varchar</td>   
<td>Berisi alamat email user  </td>   
</tr>   
<tr>  
<td>Kategori</td>  
</td> 
<td>Varchar</td>   
<td>Berisi kategori siapa yang akan login  apakah user atau admin</td>   
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
<td>Id_budaya</td>  
<td>Integer</td>  
<td>Nomor auto increment Id_budaya</td>    
</tr>    
<tr>  
<td>Nama Budaya</td>  
</td> 
<td>Varchar</td>   
<td>Berisi nama budaya </td>   
</tr>   
<tr>  
<td>Deskripsi</td>  
</td> 
<td>Varchar</td>   
<td>Berisi deskripsi tentang budaya  </td>   
</tr>   
<tr>  
<td>Gambar</td>  
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
<td>Id_pariwisata</td>  
<td>Integer</td>  
<td>Nomor auto increment Id_pariwisata</td>    
</tr>    
<tr>  
<td>Nama Pariwisata</td>  
</td> 
<td>Varchar</td>   
<td>Berisi nama pariwisata </td>   
</tr>   
<tr>  
<td>Deskripsi pariwisata</td>  
</td> 
<td>Varchar</td>   
<td>Berisi deskripsi tentang pariwisata  </td>   
</tr>   
<tr>  
<td>Gambar pariwisata</td>  
</td> 
<td>Varchar</td>   
<td>Berisi gambar pariwisata  </td>   
</tr>  
<tr>  
<td>id_Jenis</td>  
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
<td>id_Jenis</td>  
<td>Integer</td>   
<td> Nomor auto increment pada tabel jenis pariwisata  </td>   
</tr>  
<tr>
<td>Nama Jenis</td>  
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
<td>Id_Event</td>  
<td>Integer</td>  
<td>Nomor auto increment Id_event</td>    
</tr>    
<tr>  
<td>Nama Event</td>  
</td> 
<td>Varchar</td>   
<td>Berisi nama event </td>   
</tr>   
<tr>  
<td>Deskripsi event</td>  
</td> 
<td>Varchar</td>   
<td>Berisi deskripsi tentang event</td>   
</tr>   
<tr>  
<td>Tanggal</td>  
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
<td>Id_Pengaduan</td>  
<td>Integer</td>  
<td>Nomor auto increment Id_pengaduan</td>    
</tr>    
<tr>  
<td>Isi pengaduan</td>  
</td> 
<td>Varchar</td>   
<td>Berisi pengaduan dari user</td>   
</tr>   
</table>


<p><h3><strong>3. PENJELASAN DEKOMPOSISI</strong></h3></p>
<p><strong>3.1 Dekomposisi Model</strong></p>
<p><strong>3.1.1 Diagram Konteks</strong></p>
Diagram konteks merupakan tingkatan tertinggi dalam diagram aliran data dan hanya memuat satu proses, menunjukkan sistem secara keseluruhan. Berikut merupakan diagram konteks dari aplikasi ini. 
 </p><p align="center">  
<img src="https://lh3.googleusercontent.com/-L6CJeZHFHZQ/WqTi-IVUFZI/AAAAAAAAAKc/j44KbgZwpywg3PX7kgJXQlybxX4hodvXQCL0BGAs/w530-d-h288-n/diagram%2Bkonteks.png=s300" alt="enter image description here" title="diagram konteks">  
</p><p align="center">


<p><strong>3.1.2 Diagram Level 0</strong></p>
Diagram 0 adalah diagram yang menggambarkan proses dari data flow diagram. Diagram 0 memberikan pandangan secara menyeluruh mengenai sistem yang ditangani, menunjukkan tentang fungsi-fungsi utama atau proses yang ada, aliran data, dan eksternal entity. Berikut merupakan diagram 0 dari aplikasi ini.

 </p><p align="center">  
 
![enter image description here](https://3.bp.blogspot.com/-hNd4NI8q9H0/WrYO9X72pqI/AAAAAAAAAGA/vLy5oHTnjo8t5ru4H_zpE2DAsbkwbX3QACLcBGAs/s1600/nol.png)

</p><p align="center">

<p><strong>3.2 Dekompoaisi Proses Konkuren</strong></p>
<p><strong>3.2.1 Diagram Level 1 </strong></p>
<ul>
<li><p><strong>User</p></li>
</ul>
DFD Level 1 : Merupakan penjelasan dari DFD Level 0  dan berisi tentang Data User.<br>

![enter image description here](https://2.bp.blogspot.com/-cDJy2hE-c9U/WrHOLmYQ1LI/AAAAAAAAAE4/TinICzT4038Y0ZLbUHCVm7QpY4DJEzT3ACLcBGAs/s1600/level+1+user.png)
</p><p align="center">

<p><strong>3.2.2 Diagram Level 1 </strong></p>
<ul>
<li><strong>Pengaduan</strong></li>
</li>

DFD Level 1 : Merupakan penjelasan dari DFD Level 0  dan berisi tentang Data Pengaduan.<br><br>

![enter image description here](https://4.bp.blogspot.com/-P7HHtqTi8d4/WrHPMZLghNI/AAAAAAAAAFA/r7TfauEEYkcnYsdyfr30yEZwv2ZgCHTCwCLcBGAs/s1600/level+1+pengaduan.png)
</p><p align="center">

<p><strong>3.2.3 Diagram Level 1 </strong></p>
<ul>
<li><strong>Budaya</strong></li>
DFD Level 1 : Merupakan penjelasan dari DFD Level 0  dan berisi tentang Data Budaya.<br><br>

![enter image description here](https://1.bp.blogspot.com/-AQCtqUkeVuI/WrHP3jCPu-I/AAAAAAAAAFI/MolwQYQTxIMVuhTFaz4wY38VRvoqH2-FgCLcBGAs/s1600/level+1+budaya.png)
</p><p align="center"><br>

<p><strong>3.2.4 Diagram Level 1</strong></p>
<ul>
<li><strong>Pariwisata</strong></li>
</ul>
DFD Level 1 : Merupakan penjelasan dari DFD Level 0  dan berisi tentang Data Pariwisata.<br><br>


![enter image description here](https://1.bp.blogspot.com/-oIDmo9ECu4E/WrYPgYN70lI/AAAAAAAAAGI/UiAjccjFbN8TVkEYdLGu6VIZaBYtAZXaQCLcBGAs/s1600/1+pariwisata.png)

</p><p align="center">

<p><strong>3.2.5 Diagram Level 1 </strong></p>
<ul>
<li><strong>Event</strong></li>
</ul>
DFD Level 1 : Merupakan penjelasan dari DFD Level 0  dan berisi tentang Data Event.<br><br>

![enter image description here](https://4.bp.blogspot.com/-bnMlxNGfBIU/WrHR9AAnH4I/AAAAAAAAAFc/MMb643b_TUMqS5OGemAKiNCmALOpPF2kQCLcBGAs/s1600/level+1+event.png)

<p><strong>3.2.6 Diagram Level 2 </strong></p>
<ul>
<li><strong>Daftar Pariwisata</strong></li>
</ul>
DFD Level 2 : Merupakan penjelasan dari DFD Level 1 (Pariwisata) dan berisi tentang Data Daftar Pariwisata<br><br>

![enter image description here](https://4.bp.blogspot.com/-qBBwV2Y0oTg/WrHSzEZtxpI/AAAAAAAAAFk/jdZafO48Nn49ZX-OJNjl2MUJ-AOWufBNgCLcBGAs/s1600/level+2+daftar+pariwisata.png)


<p><strong>3.2.7 Diagram Level 2 </strong></p>
<ul>
<li><strong>Jenis Pariwisata</strong></li>
</ul>
DFD Level 2 : Merupakan penjelasan dari DFD Level 1 (Pariwisata) dan berisi tentang Data Jenis Pariwisata<br><br>

![enter image description here](https://1.bp.blogspot.com/-rASx0Mw4IaU/WrHRGaQUREI/AAAAAAAAAFU/4Y3x1oZYmtI_n62zZPLgMwKQHIaH-IZcQCLcBGAs/s1600/level+2+daftar+pariwisata.png)

