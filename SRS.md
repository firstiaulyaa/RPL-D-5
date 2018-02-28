# SOFTWARE REQUIREMENTS SPECIFICATION
VERSION 
22 Februari 2018
Kelompok 5 D3TI2D
1. Firsti Aulya K. K. (1603098)
2. Firmansyah (1603097)
3. Diyanti (1603094)

Jurusan D3 Teknik Informatika
Politeknik Negeri Indramayu

1. Pendahuluan

1.1 Tujuan 

Dokumen ini bertujuan untuk menjelaskan secara detail mengenai aplikasi yang kami buat yang berjudul "Aplikasi Budaya dan Pariwisata Kabupaten Indramayu berbasis Android",
pada dokumen ini akan menjelaskan seperti : Mock-up, rancangan sistem, dan lain-lain.

1.2 Lingkup Masalah

Aplikasi Budaya dan Pariwisata Indramayu adalah salah satu aplikasi berbasis android yang digunakan untuk seluruh masyarakat, khususnya masyarakat yang berada di daerah Indramayu untuk mengetahui kebudayaan yang ada di Indramayu dan event atau lomba yang akan diselenggarakan oleh Dinas Kebudayaan dan Pariwisata Kabupaten Indramayu.
Pada Proyek ini dibuat sistem berbasis android dimana pengolahan informasi dan data diakses melalui smartphone dengan sistem operasi android.

1.3 Definisi, Akronim, Singkatan
|Istilah		|Definisi																																		|
|--				|--																																				|
| Android 		|sistem operasi berbasis Linux yang dirancang untuk perangkat bergerak layar sentuh seperti telepon pintar dan komputer tablet |
|administrator  |orang / orang-orang yang bertugas untuk mengurusi Hal-hal administrasi. Dalam dunia Internet, seorang administrator bertugas untuk mengelola hal- 	 				 hal yang berhubungan dengan komputer.|
|Event 			|sebuah rangkaian kegiatan / acara dalam rangka tujuan tertentu yang diadakan oleh pihak tertentu dalam waktu tertentu dan tempat tertentu dengan 					 biaya tertentu|
|Budaya			|Hal-hal yang berkaitan dengan budi, dan akal manusia.|
|Pariwisata		|Suatu perjalanan yang dilakukan untuk rekreasi atau liburan dan juga persiapan yang dilakukan untuk aktivitas ini.|
|Berita 		|Informasi baru atau informasi mengenai sesuatu yang sedang terjadi, disajikan lewat bentuk cetak, siaran, Internet, atau dari mulut ke mulut 						 kepada orang ketiga atau orang banyak.|

1.4 Referensi
https://id.wikipedia.org/wiki/Android_(sistem_operasi), https://id.wikipedia.org/wiki/Berita, https://id.wikipedia.org/wiki/Budaya.

1.5 Overview
Dokumen ini dibagi menjadi tiga bagian utama. Bagian pertama berisi penjelasan tentang dokumen SRS yang mencakup tujuan pembuatan dokumen ini, lingkup masalah yang diselesaikan yang dikembangkan oleh kami yaitu definisi, referensi, dan deskripsi umum. Bagian kedua berisi penjelasan secara umum mengenai aplikasi yang akan di kembangkan meliputi fungsi, karakteristik pengguna, batasan dan asumsi yang diambil dalam pengembangan aplikasi.Bagian ke tiga berisi uraian aplikasi secara lebih rinci.

2. Gambaran Umum
Aplikasi Budaya dan Pariwisata Kab. Indramayu Berbasis Android adalah aplikasi yang digunakan untuk mempermudah penggunaan dalam pencarian dan informasi seputar budaya dan pariwisata di Kabupaten Indramayu.

	2.1. Perspektif Produk
	Pada proyek ini dibuat dengan sistem berbasis Android dimana aplikasi ini bisa diakses hanya dengan smartphone dengan Sistem operasinya adalah Android. Aplikasi ini dibangun dengan menggunakan aplikasi Android Studio dan Firebase sebagai databasenya.
Aplikasi ini memungkinkan admin untuk menyebarkan informasi tentang lomba atau event yang diadakan oleh Dinas Kebudayaan dan Pariwisata Kabupaten Indramayu dan informasi seputar pariwisata apa saja yang berada di daerah Indramayu.
		2.1.1 Antarmuka sistem
	   	2.1.2 Antarmuka pengguna
	 
	 * User (Android)
	- Start
	![Start](https://lh3.googleusercontent.com/HAA09bkpYRhpoUKShgOB0Evi84PyQ-h0aWChqPBP2wN7us7MhDjDTzAqD0rd0pAoPX5IVyf-q8I=s200)
		Tampilan Start hanya berupa gambar yang berfungsi sebagai tampilan awal pada saat membuka aplikasi.
		Gambar yang ditampilkan berupa logo dan nama aplikasi.
	
	- Sign In
	![SignIn](https://lh3.googleusercontent.com/rpqP6jtwvm97wTBkkYBHty64W69Va2eQ4LONtGwQiuS-lMgxPnKakehUQgILa3kwQqx3y-z4SA4=s200 "SignIn")
		Tampilan Sign In merupakan tampilan bagi User untuk masuk ke aplikasi. Sign In berisi input text (username dan password) dan button Masuk.
		Lalu terdapat link "Register disini" dan link "Lupa Password".

	- Register
	![Register](https://lh3.googleusercontent.com/bfHffQ6CzGj72jtXyT_DawTfsENzn8y2iobnkn1apRT5uyroX05DXOnkVQpLLQCAcMJgJ_n-WGM=s200)
		Tampilan Register merupakan tampilan untuk membuat User baru. Register berisi input text (username, e-mail, password, dan confirm password),
		button Daftar, dan button berbentuk X yang terletak di pojok kiri atas.

	- Home
	![HomeUser](https://lh3.googleusercontent.com/NwRFvTpGCi-5vlKvLpax2t3st6C9BFY8UmiQeo0pENDvJmZjwuJ99ng-9wwdkAszisvgz_EPg9E=s200)
		Tampilan Home merupakan tampilan utama pada aplikasi ini. Home berisi navigasi yang terletak di pojok kiri atas, input text "Cari Budaya/Pariwisata",
		dan menu yang terdiri dari beberapa button yang tersusun secara grid. Button tersebut adalah Budaya, Pariwisata, Event,
		Berita, Profil Saya, dan Tentang Kami.

	* Admin (Web)
	- Sign In
	![HomeAdmin](https://lh3.googleusercontent.com/d9TdPqt4UcURXiaXZKX8mClUUkcG4YmTHKNrrKHQ-u8-yP_15HD9av5ztIw--DzLDxYKwiYUn1w=s300)
		Tampilan Sign In merupakan tampilan bagi Admin untuk masuk ke web. Sign In berisi input text (username dan password) dan button Masuk.
		Lalu terdapat link "Lupa Password" yang terletak di bawah button masuk.

	- Kategori
	![KategoriAdmin](https://lh3.googleusercontent.com/h5s6GlIMPaKigo69-pO4TvHAfERMPhrkyfhuHAjPDD9j_n6mjkNeV88KNavWoVcos2x8Qg4ixXA=s300)
		Tampilan Kategori merupakan tampilan bagi Admin untuk melihat menu. Kategori terdiri dari beberapa button yang tersusun secara grid. 
		Button tersebut adalah Budaya, Pariwisata, Event, Berita, Profil Saya, Data Admin, Data User, dan Lihat Komentar.


	   	2.1.3 Antarmuka perangkat keras
![2.3](https://lh3.googleusercontent.com/X0547VB1z0t-vmZLOnlvdFPOPRxi0gGhFNuIcLjDgQCUg8taYVmNEcdEvKxQey7bWaY6_co0WVQ=s300)
Sistem aplikasi ini memiliki 2 User yang aktif, yaitu Admin dan User. User dapat mengakses aplikasi melalui smartphone yang memiliki sistem operasi Android. Aplikasi ini bisa digunakan apabila terhubung ke internet. Data-data pada aplikasi ini selanjutnya disimpan di database (Server) dan selanjutnya dikelola oleh Admin.
		
	   	2.1.4 Antarmuka perangkat lunak
	   	2.1.5 Antarmuka Komunikasi
		   	Aplikasi ini bekerja sama dengan Dinas Kebudayaan dan Pariwisata Kabupaten Indramayu. 
	   	2.1.6 Batasan memori
	   	2.1.7 Operasi-operasi
	   	2.1.8 Kebutuhan adaptasi

	2.2. Spesifikasi Kebutuhan Fungsional
	
	2.3. Spesifikasi Kebutuhan Non-fungsional
		2.3.1 Spesifikasi User Interface
			   User Interface yang ada pada aplikasi harus user-friendly, dan mudah untuk digunakan.
		2.3.2 Spesifikasi Kinerja
			  Sistem ini diharapkan dapat di gunakan dalam jangka panjang dan dalam sistem ini dapat berfungsi secara optimal.
		2.3.3 Ketersediaan dan Keandalan
			  Aplikasi dapat menyediakan backup pada database yang digunakan.
		2.3.4 Spesifikasi Keamanan

	2.4. Karakteristik Pengguna
	2.5. Batasan-batasan
		 Pada Aplikasi Budaya dan Pariwisata Kabupaten Indramayu harus menggunakan smartphone denga sistem operasi Android untuk dapat mengaksesnya atau menggunakannya. Pengguna dapat login dengan mendaftar terlebih dahulu.
	2.6. Asumsi-asumsi Keterkaitan
	2.7. Kebutuhan Penyeimbang

3. Requirement Specification

	3.1 Persyaratan Antarmuka Eksternal
	    Salah satu persyaratan untuk mengakses Aplikasi ini adalah dengan mendaftarkan diri dan melengkapi kolom data diri.

	3.2 Functional Recruitment

