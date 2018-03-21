<h1 align="center" id="software-requirements-specification">SOFTWARE DESIGN DOCUMENT</h1>  
<p align="center"><strong>Version 1.0</strong><br> 
<p align="center"><strong>11 Maret 2018<br>  </strong><br>
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
<P><strong>1.1 Tujuan</strong></P>
<p>Dokumen ini bertujuan untuk menjelaskan secara detail mengenai aplikasi yang kami buat yang berjudul “Aplikasi Budaya dan Pariwisata Kabupaten Indramayu berbasis Android". Pada dokumen ini akan menjelaskan tentang DFD dan lain-lain.</p>  


<p><strong>1.2 Lingkup</strong></p>
<p>Aplikasi Budaya dan Pariwisata Indramayu adalah salah satu aplikasi berbasis android yang digunakan untuk seluruh masyarakat, khususnya masyarakat yang berada di daerah Indramayu untuk mengetahui kebudayaan yang ada di Indramayu dan event atau lomba yang akan diselenggarakan oleh Dinas Kebudayaan dan Pariwisata Kabupaten Indramayu.<br>  
Pada Proyek ini dibuat sistem berbasis android dimana pengolahan informasi dan data diakses melalui smartphone dengan sistem operasi android.</p>  

<p><strong>1.3 Audien yang dituju</strong></p>
<p>Aplikasi ini dibuat berdasarkan studi kasus pada Dinas Kebudayaan dan pariwisata Kab. Indramayu yang ditujukan untuk masyarakat, dimana aplikasi ini mempunyai fungsi 
untuk menyebarkan informasi kepada masyarakat luas agar informasi dapat tersampaikan.
selain itu pengguna juga dapat mengirimkan pengaduan.</p>

<p><strong>1.4 Kesesuaian</strong></p>
<p>SDD ini mengacu pada IEEE Draft Standard for Software Design Descriptions. IEEE P1 01 6/D5.0; 1 2 December 2005</p>

<br>
<p><h3><strong>2. REFERENSI</strong></h3></p>

 - <p>IEEE, IEEE Draft Standard for Software Design Descriptions. IEEE
   P1 01 6/D5.0; 1 2 December 2005</p>
   
 - <p>Eka Ismantohadi & Moh. Yani, Software Design Document (SDD).
   2018</p>

<br>
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
 
![Diagram Nol](https://3.bp.blogspot.com/-7TnuFmK9hmw/WrHLCM9DPgI/AAAAAAAAAEs/QVVbAmTI4r4i0W__SemA-ccKZDUmnH4qQCLcBGAs/s1600/diagram+nol.png)

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

![enter image description here](https://1.bp.blogspot.com/-rASx0Mw4IaU/WrHRGaQUREI/AAAAAAAAAFU/4Y3x1oZYmtI_n62zZPLgMwKQHIaH-IZcQCLcBGAs/s1600/level+2+daftar+pariwisata.png)
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

<p><strong>3.3 Dekomposisi Data</strong></p>
<p><strong>3.3.1 Deskripsi Entri Data 1</strong></p>
<p><strong>3.3.2 Deskripsi Entri Data 2</strong></p>
<p><strong><h3>4. DESKRIPSI KETERGANTUNGAN / KETERKAITAN</h3></strong></p>
<p><strong>4.1 Keterkaitan Inter Modul</strong></p>
<p><strong>4.2 Keterkaitan Inter Proses</strong></p>
<p><strong>4.3 Keterkaitan Data</strong></p>
<p><strong><h3>5. DESKRIPSI ANTARMUKA</h3></strong></p>
<p><strong>5.1 Antarmuka Modul</strong></p>
<p><strong>5.1.1 Deskripsi Modul 1</strong></p>
<p><strong>5.1.2 Deskripsi Modul 2</strong></p>
<p><strong>5.2 Antarmuka Proses</strong></p>
<p><strong>5.2.1 Deskripsi Proses 1</strong></p>
<p><strong>5.2.2 Deskripsi Proses 2</strong></p>
<p><strong><h3>6. DESAIN DETIL/RINCI</h3></strong></p>
<p><strong>6.1 Rinci Modul</strong></p>
<p><strong>6.1.1 Rinci Modul 1</strong></p>
<p><strong>6.1.2 Rinci Modul 2</strong></p>
<p><strong>6.2 Desain Data Secara Rinci</strong></p>
<p><strong>6.2.1 Rinci Entiti Data 1</strong></p>
<p><strong>6.2.2 Rinci Entiti Data 2</strong></p>