---
ID: 40
post_title: 'Bitcoin Node: Aktualisasi Desentralisasi'
author: admin
post_excerpt: ""
layout: post
permalink: >
  https://nakamoto.id/blog/2020/05/21/bitcoin-node-aktualisasi-desentralisasi-2/
published: true
post_date: 2020-05-21 03:11:26
---
<!-- wp:image {"align":"center","className":"is-style-rounded"} -->
<div class="wp-block-image is-style-rounded"><figure class="aligncenter"><img src="https://nakamoto.id/wp-content/uploads/2020/05/peer-to-peer-network.jpg" alt="Introduction to Peer to Peer (P2P) Network | CodeSpot"/><figcaption><em>Berdaulat, adil, dan makmur: bukan sebatas slogan. <a href="https://www.codespot.org/introduction-to-peer-to-peer-network/">credit</a></em></figcaption></figure></div>
<!-- /wp:image -->

<!-- wp:paragraph -->
<p>Banyak yang bertanya-tanya, apa untungnya menjalankan bitcoin node? Toh kamu juga tidak dibayar untuk menjalankan node itu.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>Sebelum menjawab pertanyaan itu, kita lihat sebentar <em>trust model</em> dari Bitcoin. Bitcoin dibuat untuk menghilangkan <em>trust</em> (kepercayaan) pada pihak ketiga seperti perusahaan, bank, dan individu lainnya. Kedaulatan individu ini diwujudkan sepenuhnya dengan software Bitcoin Core.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>Untuk yang mempunyai kemampuan teknis yang cukup, kode sumber Bitcoin Core dapat dievaluasi secara mandiri tanpa bantuan pihak lain. Saat dijalankan, Bitcoin Core dapat memvalidasi transaksi yang masuk secara mandiri. Validasi mandiri ini adalah fungsi yang penting agar kamu bisa sepenuhnya tahu bahwa dana yang masuk ke wallet kamu telah benar-benar masuk, tanpa harus percaya pada pihak ketiga (seperti block explorer, exchange, pihak pengirim, dan sejenisnya). Validasi mandiri ini juga penting untuk yang peduli pada kerahasiaan transaksinya.</p>
<!-- /wp:paragraph -->

<!-- wp:image -->
<figure class="wp-block-image"><img src="https://nakamoto.id/wp-content/uploads/2020/05/iizkvnfrbf111.jpg" alt="And you thought the other glass stall was bad : CrappyDesign"/><figcaption><em>Banyak yang masih menganggap remeh privasi di Indonesia. (src: <a href="https://www.reddit.com/r/CrappyDesign/comments/8ntq2t/and_you_thought_the_other_glass_stall_was_bad/">reddit</a>)</em></figcaption></figure>
<!-- /wp:image -->

<!-- wp:paragraph -->
<p>Dalam jaringan Bitcoin, Bitcoin Core juga berfungsi sebagai media bagi <em>hodler </em>Bitcoin untuk menyetujui atau menolak pengajuan perubahan aturan main di dalam jaringan, yang disebut <em>Bitcoin Improvement Proposal</em> (BIP). Manfaat ini jelas terlihat di situasi <em>hardfork</em> Bitcoin/Bitcoin Cash pada 2017 yang lalu, ketika komplotan perusahaan mining dan exchange <em>ngotot </em>untuk menaikkan ukuran block menjadi 2MB dan lebih.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>Nah, dari semua keuntungan yang didapat, kenapa kita jarang menemukan orang yang menjalankan bitcoin node di Indonesia?</p>
<!-- /wp:paragraph -->

<!-- wp:heading -->
<h2>Cuma mau 'cuan'-nya saja</h2>
<!-- /wp:heading -->

<!-- wp:paragraph -->
<p>Kadang, kumpulan antara orang-orang yang punya uang dan orang-orang yang melek teknologi hampir tidak beririsan. Kebanyakan trader dan investor Bitcoin hanya numpang <em>nebeng</em> di volatilitas harganya. Alhasil <em>investor </em>dan <em>trader</em> Indonesia juga tidak terlalu peduli dengan pentingnya node itu sendiri. </p>
<!-- /wp:paragraph -->

<!-- wp:heading -->
<h2>Internet lambat</h2>
<!-- /wp:heading -->

<!-- wp:image {"align":"center"} -->
<div class="wp-block-image"><figure class="aligncenter"><img src="https://nakamoto.id/wp-content/uploads/2020/05/Tifatul_Sembiring-2.jpg" alt="Tifatul Sembiring: PKS Tetap di Koalisi | metrobali.com"/><figcaption>"<em>Internet cepat, buat apa?</em>"</figcaption></figure></div>
<!-- /wp:image -->

<!-- wp:paragraph -->
<p>Memang instalasi Bitcoin Core cuma sebentar, tapi proses pengunduhan blockchain memerlukan koneksi yang memadai karena data yang diunduh bisa mencapai 300GB (!). Selain itu, bandwidth yang diperlukan bisa membuat ISP di Indonesia lumpuh karena terkadang node kamu perlu mengirim data blockchain ke node lain.</p>
<!-- /wp:paragraph -->

<!-- wp:heading -->
<h2>Komputer perlu menyala 24 jam</h2>
<!-- /wp:heading -->

<!-- wp:paragraph -->
<p>Salah satu fungsi node adalah memperkuat jaringan Bitcoin. Semakin banyak node, titik lemah dalam jaringan Bitcoin semakin terdesentralisasi (<em>no single point of failure</em>). Jadi <strong>idealnya</strong> sebuah node perlu menyala 24 jam. Namun tidak semua orang mau menjalankannya karena berbagai pertimbangan, seperti konsumsi listrik, <em>daleman</em> komputer yang akan berdebu lebih cepat, dan sebagainya.</p>
<!-- /wp:paragraph -->

<!-- wp:heading -->
<h2>Solusinya?</h2>
<!-- /wp:heading -->

<!-- wp:paragraph -->
<p>Hal pertama yang terpenting adalah perubahan pola pikir. Tidak seperti sistem moneter tertutup yang dijalankan negara, Bitcoin adalah sistem ekonomi terbuka di mana semua orang dapat turut serta mengambil keputusan dalam kebijakan moneter. Tidak menjalankan node sama saja dengan menyerahkan nasib Bitcoin yang dipegang ke orang lain.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>Lalu, siapkan komputer/laptop dengan RAM minimal 2GB dan HDD 500GB. Laptop tua bisa menjadi pilihan yang ekonomis untuk menjalankan node karena hemat daya, hemat tempat, dibekali dengan Wi-Fi, dan baterainya bisa berfungsi sebagai UPS. Alternatif lain adalah memakai Raspberry Pi, tapi ini khusus untuk yang mengerti Linux dan mempunyai alokasi dana khusus.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>Sisanya, pastikan internet <em>unlimited</em> karena proses sinkronisasi blockchain akan memakan bandwidth yang sangat besar. Dan tentu saja tidak usah terburu-buru karena proses sinkronisasi juga akan memakan waktu yang lama (2 minggu sampai 1 bulan).</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>Menjalankan bitcoin node adalah investasi pertama yang harus dilakukan saat orang membeli bitcoin. Tanpa investasi ini, titik terlemah bitcoin ada di kamu.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p><strong>Sumber:</strong></p>
<!-- /wp:paragraph -->

<!-- wp:list -->
<ul><li><a href="https://bitcoin.org/bitcoin.pdf">https://bitcoin.org/bitcoin.pdf</a></li><li><a href="https://medium.com/bitstamp-blog/should-i-run-my-own-node-13c3f6a21627">Should I run my own node?</a></li><li><a href="https://bitcointalk.org/index.php?topic=5196950.0">Bitcoin Core - Bitcointalk Bahasa Indonesia</a></li></ul>
<!-- /wp:list -->