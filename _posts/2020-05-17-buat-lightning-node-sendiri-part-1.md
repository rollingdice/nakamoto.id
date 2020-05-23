---
ID: 38
post_title: 'Buat Lightning Node Sendiri: Part 1'
author: admin
post_excerpt: ""
layout: post
permalink: >
  https://nakamoto.id/blog/2020/05/17/buat-lightning-node-sendiri-part-1/
published: true
post_date: 2020-05-17 14:40:47
---
<!-- wp:core-embed/youtube {"url":"https://www.youtube.com/watch?v=rrr_zPmEiME","type":"video","providerNameSlug":"youtube","className":"wp-embed-aspect-16-9 wp-has-aspect-ratio"} -->
<figure class="wp-block-embed-youtube wp-block-embed is-type-video is-provider-youtube wp-embed-aspect-16-9 wp-has-aspect-ratio"><div class="wp-block-embed__wrapper">
https://www.youtube.com/watch?v=rrr_zPmEiME
</div><figcaption>Untuk kamu yang lebih suka menonton video 5 menit dibanding membaca artikel.</figcaption></figure>
<!-- /wp:core-embed/youtube -->

<!-- wp:paragraph -->
<p>Kalau kamu punya laptop atau netbook <em>nganggur</em>, punya skill yang cukup (atau mau belajar) Linux, dan mau bereksperimen dengan jaringan Bitcoin, ada baiknya untuk mencoba membuat <em>lightning node</em> sendiri.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>Lightning Network adalah jaringan yang berdiri di atas blockchain Bitcoin. Seperti namanya, Lightning Network mampu membuat transaksi Bitcoin berlangsung secepat kilat!</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>Rahasianya adalah dengan <em>tidak mem-publish transaksi yang terjadi di Lightning Network</em>. Sifat blockchain yang <em>immutable</em> (data apapun yang sudah masuk tidak akan bisa diubah lagi) dan ukuran blockchain yang relatif konstan membuat pembayaran-pembayaran kecil menjadi lebih praktis jika dilaksanakan secara privat. Bayangkan, dari nilai transaksi satu block yang bisa mencapai puluhan juta dolar, seberapa penting sih transaksi kecil seperti pembelian pulsa 100 ribu? </p>
<!-- /wp:paragraph -->

<!-- wp:image -->
<figure class="wp-block-image"><img src="https://nakamoto.id/wp-content/uploads/2020/05/toptal-blog-image-1553776681427-148ecfebc6e86f97e30ae83ba27863d9.png" alt="Illustration of two nodes creating a channel on the Bitcoin Lightning Network"/></figure>
<!-- /wp:image -->

<!-- wp:paragraph -->
<p>Maka, kedua belah pihak saling membuat dompet bersama yang kepemilikan saldonya dapat berpindah ketika ada transaksi. Bahasa teknisnya, sebuah dompet multi-signature dibuat dan dipublikasi ke blockchain ketika kamu ingin bertransaksi untuk pertama kali. Transaksi berikutnya tidak memerlukan publikasi ke blockchain, selama nominal transaksi tidak melebihi nominal dompet multi-sig. Nah, dalam bahasa teknisnya kamu sudah membuat <em>payment channel</em> dengan kapasitas tertentu.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>Contohnya, kamu akan bertransaksi dengan BitRefill untuk membeli pulsa. Kamu harus membuat <em>channel</em> terlebih dahulu dengan kapasitas yang menurutmu cukup, katakanlah 0.01 BTC. Maka, kamu dapat bertransaksi secara instan dengan Bitrefill sebanyak 0.01BTC, kapanpun kamu mau tanpa harus menunggu konfirmasi blockchain di setiap transaksi.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>Untuk mulai bertransaksi, kamu bisa memulai dengan menginstall dompet yang mendukung Lightning. Cara yang paling mudah adalah dengan menggunakan dompet <em>custodial</em> (kamu menggunakan server pihak penyedia wallet sehingga tidak perlu repot membuat server sendiri). Ada dua dompet yang saat ini cocok digunakan:</p>
<!-- /wp:paragraph -->

<!-- wp:list -->
<ul><li><a rel="noreferrer noopener" href="https://bluewallet.io/" target="_blank">BlueWallet</a>, cocok untuk yang belum mempunyai wallet Bitcoin sama sekali. Wallet Bitcoin dan Lightning terintegrasi dalam satu aplikasi</li><li><a href="https://www.walletofsatoshi.com/">https://www.walletofsatoshi.com/</a>, untuk yang sudah mempunyai wallet Bitcoin tetapi ingin merasakan fitur Lightning</li></ul>
<!-- /wp:list -->

<!-- wp:paragraph -->
<p>Kekurangan dompet <em>custodial</em> ini tentu saja adalah kamu harus percaya penuh kepada provider wallet, yang sedikit bertentangan dengan moto Bitcoin: <em>don't trust, verify</em>.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>Proses pembuatan Lightning Node akan dijelaskan di part 2.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p><em>Follow Instagram </em><a href="https://www.instagram.com/nakamoto.id/">nakamoto.id</a> <em>untuk update dan tutorial tentang bitcoin, event, dan info terbaru.</em></p>
<!-- /wp:paragraph -->