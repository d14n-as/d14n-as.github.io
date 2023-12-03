---
layout: post
comments: true
title: Cara Menghubungkan Tampilan Browser di Laptop ke Browser di Ponsel
categories: Website Development, Website, Developer, Front End Web Developer, Backend
---


![Cara Menghubungkan Tampilan Browser di Laptop ke Browser di Ponsel]({{ site.baseurl }}/images/webdev.jpg)

## Website Development

Apa Itu Website Development?

Website development adalah proses pembangunan dan pemeliharaan website. Mulai dari pembuatan website berisi teks sederhana hingga yang bentuknya kompleks seperti platform sosmed atau web app. 

Biasanya website development kerap dikaitkan dengan coding. Coding itu tak hanya bertujuan membangun antar muka website. Tapi juga masih ada proses pengembangan server, keamanan, dan manajemen konten website. 

Website development dilakukan untuk membuat website yang sesuai kebutuhan pengguna. Misalnya, web developer ingin membuat website toko online. Maka web developer perlu membuat fitur katalog produk, konfirmasi pembayaran, dan lainnya. 

## Seorang Front-End Web Developer

Front End adalah Bagian dari sebuah website yang langsung dilihat oleh pengguna.  Front end dibangun menggunakan beberapa bahasa pemrograman seperti HTML, CSS, dan JavaScript.

Orang yang bertanggung jawab atas front-end disebut front-end developer/front-end web developer. Sebagai seorang front-end web developer, dulu saya kerap menggunakan virtual machine/mobile untuk mengecheck tampilan mobile/handphone. Ternyata ada cara yang lebih mudah dan murah, yaitu menghubungkan tampilan browser di laptop ke browser di handphone.

## Cara Menghubungkan Tampilan Browser di Laptop ke Browser di Ponsel

- Pastikan laptop/PC dan ponsel menggunakan akses koneksi wifi yang sama
- Jalankan folder projek Anda di Visual Studio Code
- Kemudian jika Anda menggunakan extention "Live Server", maka silakan klik "Go Live" di pojok kanan bawah
- Secara otomatis direct ke browser lalu memuat folder projek Anda dengan domain kira-kira spt ini http://127.0.0.1:5500/
- Setelah itu, buka Command Prompt pada laptop/PC
- Lalu kemudian ketik "ipconfig"
- Selanjutnya cari "IPv4 Address" di bagian "Wireless LAN adapter Wi-Fi"
- Buka browser di ponsel Anda, lalu ketikan IPv4 Address tersebut + port :5500 seperti domain di atas
- Jadi ada 2 domain, di browser laptop/PC Anda adalah kira2 domain http://127.0.0.1:5500/
- Sedangkan di browser ponsel Anda adalah domain IPv4Address+:5500
- Maka tampilan di browser ponsel akan sama dengan browser laptop/PC Anda

CMIIW.


{% if page.comments %}
  <div id="disqus_thread"></div>
  <script>
      /**
      *  RECOMMENDED CONFIGURATION VARIABLES: EDIT AND UNCOMMENT THE SECTION BELOW TO INSERT DYNAMIC VALUES FROM YOUR PLATFORM OR CMS.
      *  LEARN WHY DEFINING THESE VARIABLES IS IMPORTANT: https://disqus.com/admin/universalcode/#configuration-variables    */
      /*
      var disqus_config = function () {
      this.page.url = PAGE_URL;  // Replace PAGE_URL with your page's canonical URL variable
      this.page.identifier = PAGE_IDENTIFIER; // Replace PAGE_IDENTIFIER with your page's unique identifier variable
      };
      */
      (function() { // DON'T EDIT BELOW THIS LINE
      var d = document, s = d.createElement('script');
      s.src = 'https://d14n-as-1.disqus.com/embed.js';
      s.setAttribute('data-timestamp', +new Date());
      (d.head || d.body).appendChild(s);
      })();
  </script>
  <noscript>Please enable JavaScript to view the <a href="https://disqus.com/?ref_noscript">comments powered by Disqus.</a></noscript>
  <script id="dsq-count-scr" src="//d14n-as-1.disqus.com/count.js" async></script>
{% endif %}