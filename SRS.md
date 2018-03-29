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
<p>Dokumen ini bertujuan untuk menjelaskan secara detail mengenai aplikasi yang kami buat yang berjudul “Aplikasi Budaya dan Pariwisata Kabupaten Indramayu berbasis Android”,<br>  
pada dokumen ini akan menjelaskan seperti : Mock-up, rancangan sistem, dan lain-lain.</p>  
<p><strong>1.2 Lingkup Masalah</strong></p>  
<p>BUSAYU (Aplikasi Budaya dan Pariwisata Kab, Indramayu) adalah salah satu aplikasi berbasis android yang digunakan untuk seluruh masyarakat, khususnya masyarakat yang berada di daerah Indramayu untuk mengetahui kebudayaan yang ada di Indramayu dan event atau lomba yang akan diselenggarakan oleh Dinas Kebudayaan dan Pariwisata Kabupaten Indramayu.<br>  
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
</p><p>Aplikasi Budaya dan Pariwisata Kab. Indramayu Berbasis Android adalah aplikasi yang digunakan untuk mempermudah penggunaan dalam pencarian dan informasi seputar budaya dan pariwisata di Kabupaten Indramayu.</p>  
<p><strong>2.1. Perspektif Produk</strong><br>  
Pada proyek ini dibuat dengan sistem berbasis Android dimana aplikasi ini bisa diakses hanya dengan smartphone dengan Sistem operasinya adalah Android. Aplikasi ini dibangun dengan menggunakan aplikasi Android Studio dan Firebase sebagai databasenya.<br>  
Aplikasi ini memungkinkan admin untuk menyebarkan informasi tentang lomba atau event yang diadakan oleh Dinas Kebudayaan dan Pariwisata Kabupaten Indramayu dan informasi seputar pariwisata apa saja yang berada di daerah Indramayu.<br>  
</p><p><strong>2.1.1 Antarmuka sistem</strong></p><br>  
<p><img src="https://4.bp.blogspot.com/-80n_0OxZZ_w/Wp-lcm-mUII/AAAAAAAAAEA/dLxdDnG38Z8zyk7PNIP3hgChXTJiDFZ4gCLcBGAs/s1600/sistem.png" alt="enter image description here"></p>
<p>  
Sistem Aplikasi Budaya dan Pariwisata ini terdapat 2 aktor yaitu Admin dan User (Pengguna). Admin dan User (Pengguna) mempunyai fungsi yang berbeda dimana admin dapat mengolah data Pariwisata, data Budaya dan data Event juga dapat melihat ratting dari user. sedangkan user hanya dapat melihat data Pariwisata, data Budaya, dan data Event, user (pengguna) juga dapat menginputkan Pengaduan.  
</p>  
<p><strong>2.1.2 Antarmuka pengguna</strong></p>
<tabel>
<tbody>  
<tr>
<td> 
<img src="https://lh3.googleusercontent.com/-GF5X8JEZvEY/WrxhRrLdV_I/AAAAAAAAFKI/52M_V6KIwSENMvP472aaXQbFr7FW-jxQgCL0BGAs/w328-d-h583-n-rw/animasipembuka.PNG=s200" alt="Start">
</td>
<td>
<img src="https://lh3.googleusercontent.com/-v-t8IV4jr_8/WrxeBxxT9XI/AAAAAAAAFHw/4-hoVJHvdnsy-sYFAI50M9rJBzh_xTbAACL0BGAs/w323-d-h574-n-rw/login.PNG=s200" alt="SignIn" title="SignIn">
</td>
</tr>
<tr>
<td>  
<img src="https://lh3.googleusercontent.com/-Aok2SDQOz7A/WrxeGLffE3I/AAAAAAAAFII/lPAFORL5QgoBw70FcvM6gUsTjiY3Bi3mgCL0BGAs/w321-d-h571-n-rw/register.PNG=s200" alt="Register">
</td>
<td>  
<img src="https://lh3.googleusercontent.com/-MC1SiWHzI_I/WrxhLHgv5iI/AAAAAAAAFJw/B8SgdKkuQVA633uc4oOXAfpCsYBSsgM9gCL0BGAs/w321-d-h571-n-rw/home.PNG=s200" alt="Register">
</td>
</tr>
<tr>
<td>  
<img src="https://lh3.googleusercontent.com/-G3t4tU0M-vY/WrxeLkfMMlI/AAAAAAAAFIg/NtfvaM9x4BgQp9xg72zZk2tNG627BMhegCL0BGAs/w324-d-h576-n-rw/menupariwisata.PNG=s200" alt="Register">
</td>
<td>  
<img src="https://lh3.googleusercontent.com/-cOUIct6zf1g/WrxhYXMbvUI/AAAAAAAAFKg/N-PMpAzALIUhMZCpjNryO1h9V1pSXaFTwCL0BGAs/w325-d-h578-n-rw/budaya.PNG=s200" alt="Register">
</td>
</tr>
<tr>
<td>  
<img src="https://lh3.googleusercontent.com/-sz7Xx08oNQ0/WrxiFPC0j_I/AAAAAAAAFMI/wtOVuxiKMtoT9xQJIcjEek4UfuNnvSdLACL0BGAs/w325-d-h578-n-rw/hotel.PNG=s200" alt="Register">
</td>
<td>  
<img src="https://lh3.googleusercontent.com/-D1sIPNSm-JQ/Wrxi6Zcq0aI/AAAAAAAAFN8/EEvClA8HMlQRNVq87xH1polstTeWfvTvgCL0BGAs/w327-d-h581-n-rw/kegiatan.PNG=s200" alt="Register">
</td>
</tr>
<tr>
<td>  
<img src="https://lh3.googleusercontent.com/-oby_ANNDw8w/WrxltglVRUI/AAAAAAAAFO0/_pqT3PkayrEP-QXLuEgNLURQE7RGskW7ACL0BGAs/w326-d-h580-n-rw/kuliner.PNG=s200" alt="Register">
</td>
<td>  
<img src="https://lh3.googleusercontent.com/-lpI_4v-I_pU/Wrxl8iwBXSI/AAAAAAAAFPs/6EbnVw0Jw3AndgNA4ob0xvB0nGYHIIvZQCL0BGAs/w326-d-h580-n-rw/restodankafe.PNG=s200" alt="Register">
</td>
</tr>
<tr>
<td>  
<img src="https://lh3.googleusercontent.com/-P2tbYWIjrf0/WrxmS7TBTEI/AAAAAAAAFRA/9qNvn9OpF-cfmqow1hBzkZAxQV0QSBeUgCL0BGAs/w325-d-h578-n-rw/wisatabuatan.PNG=s200" alt="Register">
</td>
<td>  
<img src="https://lh3.googleusercontent.com/-2ngpR7mOoc4/WrxmNYgl8GI/AAAAAAAAFQg/vUdVJzR0kFELpXSNi1j-bGa1RvGGNqzYgCL0BGAs/w325-d-h578-n-rw/wisataalam.PNG=s200" alt="Register">
</td>
</tr>
<tr>
<td>  
<img src="https://lh3.googleusercontent.com/-fWT3tYKw-Nw/WrxlylWm78I/AAAAAAAAFPM/yfsT-UNYVpYaz7u65_TDLYYD2aBwOfgcQCL0BGAs/w318-d-h565-n-rw/navbar.PNG=s200" alt="Register">
</td>
<td>  
<img src="https://lh3.googleusercontent.com/-EoUFpmLvacY/WrxhsuuVHrI/AAAAAAAAFLo/I5Xf6THB_fon0PMwuUkSdX1av-uMegn2gCL0BGAs/w325-d-h578-n-rw/lihatdetail.PNG=s200" alt="Register">
</td>
</tr>
<tr>
<td>  
<img src="https://lh3.googleusercontent.com/-7qe8DcuSU1o/Wrxhi6RtElI/AAAAAAAAFLQ/FeT-6TXupZsXBoaCm29vi4p6b9eCK-G-ACL0BGAs/w324-d-h576-n-rw/disbudpar.PNG=s200" alt="Register">
</td>
<td>  
<img src="https://lh3.googleusercontent.com/-03pj6Uh6_Jg/WrxoM7jYqOI/AAAAAAAAFTM/3UoYbmZd9I02RV3hl7jKLalskjggS6M6gCL0BGAs/w324-d-h576-n-rw/profilsaya.PNG=s200" alt="Register">
</td>
</tr>
<tr>
<td>  
<img src="https://lh3.googleusercontent.com/-QULfNIB-2FQ/WrxoVVed3TI/AAAAAAAAFTk/wMe6Wrxa9bIIOioT37w3UKM93bvOaRn9QCL0BGAs/w328-d-h583-n-rw/ubahprofil.PNG=s200" alt="Register">
</td>
<td>  
<img src="https://lh3.googleusercontent.com/-v8Clqxh99Xc/Wrxoe-pMQ4I/AAAAAAAAFT8/RIvKjn6m1psm5kC4BQIY3_x3-8xbBLXegCL0BGAs/w326-d-h580-n-rw/pengaduan.PNG=s200" alt="Register">
</td>
</tr>
<tr>
<td>  
<img src="https://lh3.googleusercontent.com/-DJV9QCIrW9s/WrxmfRy3IBI/AAAAAAAAFRc/D_aZiy0fzQ0mwAFmt1HR_mCG2-zQVKZNwCL0BGAs/w319-d-h567-n-rw/travel.PNG=s200" alt="Register">
</td>
</tr>
</tbody>
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
<img src="https://lh3.googleusercontent.com/cVttEmlca1kO4bxDHvMb6T0A4DfEhNfaxFL1maDZCn6K72hgqtSsQKoDDqJEOmdpFbT_wEP2Kb6_gPEIBD4QVM0017u6PTvpNSIIoPtzPdvdFP8Z0YSgtDyXSnHqs1MQDgja8RtxyuQDacMaWdrO7coGSWfiRltkDKljNxP9iqimyGYWTtuU__7aqUshSP6sltos1QmykIx9WSIwwvgRgREEL0L9RLwrzB-IcPFGmbaK8Uf_9bHXO43XNdNipDtB0qi1SSBe3PNozpGvDEI536OtpfLs6d8cE6A2tnuWllydhhGSEOA0-DfC9DDnZqgbKFfOryj-p0j21jamt5lk1h6pM6-KeK37MCiey5SgT_yQn-F_xEWd3jQnyvbcNA9rE_SySpLRTPB8_Snr5cPfG5WRjNIaonqsYEIMxVfuVa61H2-VaMHL2w7q7msKCHMEhHLqITtzjEhSrneadDvGHIyf6Lybe7RJdxdm_TiABrpNtH04iIBEenJ-gUH3AkuyNiVSFSXFmjlu1FU6y68t8yMLUJzBvwOLZGtJWqUJvb92OsnFf4aLnu1WgusbBTk49DdOzFBQJ1flOThz3Q-3wvqanBMQNGCtDg2O17o=w816-h637-no" alt="usecase" title="usecase keseluruhan"><br>
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
<p><img src="https://lh3.googleusercontent.com/VX9Vqc030KkyvzhaZBFPAx1buYvuTEu6lnK6X3CaLb007EG_n8coFCK_jfM40ZyqfIVs_ROgOrGlqy9XzfjYXYUZKpnbFBDDm2i8aXjyMFqWdisCREgDlcGfhL9IARo4u31Edv-Wv6SbveCny5H6KzNBz3FZcpVZCqLuJk3zlHdekW213AJI5jS0dh667iHpdXXoJamiMHQIfCE-4mPbNNxVN0FjVdaixjzIzQ67u-EbEjWBrB4oZZKo08XiTFbSP6e0h1mTPgZjXN4pD6mhZcqaTh2mIdliSVAioJoyHziYAgJpD8qY5lveLBPUgE4GXt1lsDd1fkXnje3cLHZc3D7naQ0ZV9PVQ8OnRgPVDZRiheOne-XH0tmpDz56Pjy86Dr0KCJyhYEo1_rIToqHF4WWBkAJcLEmLk5i0J-h1EfkaXGNHW1pD_5AeOoh6yaQiYZ0aRgdZCCb8EMvpa_qwus74MzqkH8TIsCQYHCffK5NxwN8G0Pi8QnFLB8e7yJQLScLIplFphtqV8HeiqVAX3hH_QNDJcLzkdHvltlbFCSkhbediTH76MOS6s6iwhBxbUDN1eUsPYCvsED9oAwXWXOnVn9TU8cVU9aZ_j8=w179-h105-no" title="userkegiatan"></p>
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
<p><img src="https://lh3.googleusercontent.com/oxV-MqM49qhcPS9TpUT7qO6YMX3lST1bNgWDD_gBby0FFmvRoUs8QZTFB8J2-f7xcpZvaImv0ekpZo9U11UneZnlZSEcjIKLMYzaTxB0Xz43sn_PuhVXknLjbbKM_QPG5mie9RXnR0Bqs-6Yif8zKjGyBg2lwFpRcT9S0asEpE0Knv7oUNi9dZIyltTrPCYiK9OKBBoS_8JW2LfjYDMbGL_67ZeryIBbjX_T3qBs5TSD5gDt3q4ciHkDuMFilak5T96N6GDiGHMvOyzHfZcfzgvfx9VwEnCFPPKpzrG1sF60oCW2qMWgcL3uwozNM7Bmr3BvRF_zpUboiUCKsFPjYEkU23nsqPP6kMOz14IHPrTL3kHiuXsKRwWbJy8rdk4x0gGPLGrJN0sQjNiVjnkP74bSlvWr-unWsMbPZ21vENv2bSXtKeXsSa5tj5-f66GL0Ges3X_tPICm1kYfrG2Sm0reB3MKVqxH77sL6ih_ARLuRpSQNqZ7lNIfeW4NTeBD86UafaG0cZWsVP91l0L1ePLx8ydVOCXed3efrwheTBjzazyUu2EKxMOyGu5TkSTItCQy0KW6eAycxxlTee8lL1mbis6oChFWGmOqnl4=w162-h94-no" alt="enter image description here" title="adminbuat"></p>
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
<p><img src="https://lh3.googleusercontent.com/_mz-RDKhSUY0IA24GVsBDYiSWDoZ7Kfr_VBNQLMeMez2BjsiGVG-J5rdn-4Ya0kn0QPY4GR8Gq9l5ZTDjUyunu5qBAsiQImmuHPLuKDz9g_ZQxzIOs5PeMBhX9Yf2QHakorw-RXGc5SoIiLGlp-qJllI6bq1haPbR7zM0yY6BlrD0kdqPnunZ8MxmUubUV0LOUCCrQAvg1C_ysFE3f11Tmom7Frh69pFhrBlRSsOJ8ojeR8nSNjn6uhuhxDU9uA4wdMgRQWeekZBpR3PvzoVMH3NJP_BrSoT9zvNYkAJKT9JkQUoUG-Hj5snPFMSFvo9bg1YdxUpyrz_X44IqHbPJpqXfjif2pfycMuoR8dk4DW83zLVpwM3puq15e7LChGOKwDy0QKZup-fa6oEytfjAoJPN_IfF3uOw9RCkFgNrORmKjxJNTuTMefJ7uh5OZhxCVP5wXIAxNV6myaVgKwZ1gOJiLMl-MT27iOA1Suln_3ZaAwHYecRH66_ucyMzSVoNGWt9N3PuP3VJe2ZusGQsTGwk7QfeVMZrkpszFBPiNR7nn-dhgHLmzd5n7yvvh3nqtlWYMWz6CnfpDO2Pa75Hcno6Qd-g4fS-_CoD-c=w169-h99-no" alt="enter image description here" title="adminedit"></p>
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
<p><img src="https://lh3.googleusercontent.com/edlkmlqnFj0A7vsuHXFVnkTCUVMaFW3pU5s0oSIvUDksTJrlLkcPuntfBIGiuDEJKQo0KLtPaOrlndm8dGxtzbnT4pYMxf1Tcfhh2SRvxAzs4ymi62ZM8yOP2m7oHi2zlB7o9kuxkfUONAl8q6P-g1LUXrDWbUKmF9dWo3fKoWXeHB2NEDn9OBDisTDsud6JydVSi9GX66nph5a-NMP7vSEU6X-sh-6iCJ8PmICOT-E2HrnoRqC6jPVs2oDG5319xZ-tQ1u3XCgIthmODR5t9fpkyikuCpLJBSuFg2wyymc3tfL7E3a6HmbWVL45frLiERGNxIcxJK6nOs8ikdfJ8zGR4wGVL_Oc9gptx31j_-BNc71qPHtkoM4km16zT7_MqzY1ThZpE8WQywlRPASkPueIo65fGlcvICCe1iX9wS9tj25McLXBCmkmcR6gnZXNoRgF2Cug3R_y5hLjy1gZca24CP7b1I8t337sw2x3WY3FynJiUlwwpSBF8PZvG5Yn47xURHsrSLMcd9D1Gelme8cyzQVJNYvUhivl3KxqJYIuq3dUh8P0w17yRzY-eDAFVAx88XcT3ZqWaU_G54oekAfuy2xih22X2aiKJQQ=w174-h94-no" alt="enter image description here" title="adminhapus"></p>
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

<p><img src="https://lh3.googleusercontent.com/GlpVAaHE6_EQM3cjPAMMDl80KGzyc0iiH0UrNXZYH91JBZ4LjixBWXQrYMOjGAmRn9y9KV7icINruKwbA8_t8-3FQXtk8_zfse61uDGjqY8_NyKdHHN49FqO4wwX2wmFz2RsWMmO4fwFqy6TOd-y0cwEn6GuLFVzjjYQKQPApePiEf_QWa4lwzRC4LtCWnffNnAM7r8XHsRZHQ2knDSiE6CCDrWL3JhVkXJT4VwzgzJ7vIa8GAdB1WhHzsP41UpDYtz-BdmApVJv6J66rcQ2Bweu2xFEOF95bW3Wgu8IwT56CNSePiWac4mOong4-IaEyW5hWmLkP-pMBPbZ6P2gIvMBXD-ECWnMWksoNE_xTBbPMCZpeASgAz1Pm66DWKIXEMUZcEGQSD3a6fe9DE_MqzxtIvaxVxqZIhk9vOdpHSlhCGKtpPmjoeCNvuhDvoLxtVgWBB0rBD9xNO0JSRZbZ9lggLm3SWjSQaEugKWTuXgWzZxL_o1N-adkpQfQUyKuyvL7W8MWBppYT4APIyIXYbPSwXGpxPZNxpNRNEWjpUdD0LX0nPbN42CM_CEdoO_opBqu2GT0tPpFEJzbElywxe_osj-5PqgmahZWKfg=w173-h98-no" alt="enter image description here" title="adminpengaduan"></p>

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
<p><img src="https://lh3.googleusercontent.com/Rej0OVjGwh3zr60xSnjRhLo2teUAMS3sx3LBZT73mKy093YC-wqnyRNNUGjIRa6rBKOh-UTMUsSH_2RBxUiDg6NrFQRlO3aFZbN8jbGgjbunwnuhw_8u-x6Zw5zZUs4mP8M3fWOMA4ZxdFn6hYc10zzTWA-5Ze1NkFBfesm4upZqsX2QFkmfQhwqPFad-n9hhTczDMFBXRo_g96go8LgZlTaNhjLTvuhYR-5tlOh0GVRvRtlE5_gioNQ1kW4DamVGG9Qr6WaxnxJDUiavONnhkDM3yscXgo38hlELA2AAP8XC0he-u7lhr592VKFBoggSH3eTni_2EWxTF0aEKipV6f1GBvjPhw1P2Ii2Sgcyl0qF7yXXukRZIbqfwle-j6GoI7RXEPB7neDaMogvHkeKcrew5h37FncYOaAdjg4s5tgNpGBOuCFUi47-ja0-MNECVHxhumf9Rt9UOLdnMww1xIRceHa90-ucm5lfa44xX6Cl2g0DWmLUz-4gaLcNf_lgIHCSJOszDS4y7Rpu_qUya5rhSZMM60VqX39h0HYGpjxaqJ0RorpBKkhcEVIqLCV0VAz1ZRRLFVJnb5t6rbWg-Tv8mmh35deFViuXyM=w191-h104-no" title="adminmengelolauser"></p>
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
<p><img src="https://lh3.googleusercontent.com/M-nVX_YBuyMHit2tInEH9GgxDFJUY9RqNh1gWueyaCaN1MRDkj1Y9w00E6S2_U7i44tGlrmMSUwIZRgr7Gt7klnpxPNt8SmCzW5J0E5nXdgSZCtjsgUbVp4HxznayCxaPgTPSMUnAGg7DvoOSibbAR6nathYlLl8TJ4Q1IhuHPaYLAFPRTKvkF50KO_XV7VDoGzZqkpeGTj3EkGpQNu0cwkKa_OUNjXqExXIcGBUa_2sgmcvSUE1L_RMCtcmNUJNCfdj0OTx1Iyuxd6kMfahK37kuu2sLscjs-sGZfYC5mgwiuY0gCvwGHRAGpsqr5Z08hk2P22mgpm3swuPwb0euyLzaHpJv_14tSEIYsHY4RCsAy1C9IQDXgO7OT0BSCYzoMaca_HBmcS2uzqX5R6SfHs5tgT7WWq7MtQNgXnYlZiq2t5T01d-A_WhUNZstbQgjEIh2WtM-k7YnUPt0crQKvtZOeeZL89OwzeuSYdAq0PmRiiDrkyZRfatHCs895hqL3IELztg_ah6QQQvpdoLhelVCsQ5D2jNHCwFFmX4Su6QSkwzOXTSm7ThX6O1MF7j2R-o2-RrU_Dz9p0uy5Si0FJvphxgfKbXd4FcjUA=w190-h102-no" title="adminmengelolauser"></p>
<p>Deskripsi singkat ketika user mengedit user:
</p><ol>
<li>Sistem menampilkan halaman utama yang berisi button budaya</li>
<li>user menekan tombol navigasi</li>
<li>User memilih profil saya</li>
<li>User memilih ubah profil</li>
<li>User mengedit dat profil</li>
<li>Sistem akan mengirim data ke database</li>
</ol>
Xref: Bagian 3.2.12, user mengedit user<p></p>
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



