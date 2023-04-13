---
layout: post
comments: true
title: Transfer File Engga Perlu Install Aplikasi, Hanya Dengan Ini!
---


![Cara Menggunakan ShareDrop]({{ site.baseurl }}/images/sharedrop-1.jpg)

## Apa Itu ShareDrop?

Dikutip dari https://github.com/szimek/sharedrop, ShareDrop adalah aplikasi web yang terinspirasi oleh layanan AirDrop Apple. Ini memungkinkan Anda untuk mentransfer file secara langsung antar perangkat, tanpa harus mengunggahnya ke server mana pun terlebih dahulu. Ini menggunakan WebRTC untuk transfer file peer-to-peer yang aman dan Firebase untuk manajemen kehadiran dan pensinyalan WebRTC.

ShareDrop memungkinkan Anda mengirim file ke perangkat lain di jaringan lokal yang sama (yaitu perangkat dengan alamat IP publik yang sama) tanpa konfigurasi apa pun - cukup buka https://www.sharedrop.io di semua perangkat dan mereka akan melihat satu sama lain. Ini juga memungkinkan Anda mengirim file antar jaringan - cukup klik tombol + di sudut kanan atas halaman untuk membuat ruang dengan URL unik dan bagikan URL ini dengan orang lain yang ingin Anda kirimi file. Begitu mereka membuka halaman ini di browser di perangkat mereka, Anda akan melihat avatar masing-masing.

Perbedaan utama antara ShareDrop dan AirDrop adalah bahwa ShareDrop memerlukan koneksi Internet untuk menemukan perangkat lain, sedangkan AirDrop tidak memerlukannya, karena menciptakan jaringan nirkabel ad-hoc di antara keduanya. Di sisi lain, ShareDrop memungkinkan Anda berbagi file antara perangkat seluler (Android dan iOS) dan desktop dan bahkan antar jaringan.

## Langkah-langkah menggunakan ShareDrop

- Kunjungi https://www.sharedrop.io pada browser di perangkat Android/iOS/Windows Anda
- Di sini saya menggunakan PC Windows (Penerima File) dan ponsel iPhone (Pengirim File)

![Cara Menggunakan ShareDrop]({{ site.baseurl }}/images/sharedrop-2.jpg)

- Klik simbol + di pojok kanan atas (Create a room. You'll leave the room you're currently in)

![Cara Menggunakan ShareDrop]({{ site.baseurl }}/images/sharedrop-3.jpg)

- Kemudian scan/pindai QR code menggunakan kamera ponsel
- Berikut tampilan di perangkat ponsel

![Cara Menggunakan ShareDrop]({{ site.baseurl }}/images/sharedrop-4.jpg)

- Klik link yang muncul ketika scan QR code
- Selanjutnya, akan tampil Avatar di Ponsel

![Cara Menggunakan ShareDrop]({{ site.baseurl }}/images/sharedrop-5.jpg)

- Dan avatar di PC Windows

![Cara Menggunakan ShareDrop]({{ site.baseurl }}/images/sharedrop-6.jpg)

- Klik pada avatar PC Windows untuk transfer file 

![Cara Menggunakan ShareDrop]({{ site.baseurl }}/images/sharedrop-7.jpg)

- Saya akan transfer file berupa image

![Cara Menggunakan ShareDrop]({{ site.baseurl }}/images/sharedrop-8.jpg)

- Setelah klik Send, maka file tersebut akan diterima oleh PC Windows seperti berikut

![Cara Menggunakan ShareDrop]({{ site.baseurl }}/images/sharedrop-9.jpg)

- Kemudian silakan klik Save

Note: ponsel dan PC diharapkan menggunakan koneksi internet yang sama

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