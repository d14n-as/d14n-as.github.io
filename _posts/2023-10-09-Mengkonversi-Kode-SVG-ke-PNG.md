---
layout: post
comments: true
title: Mengkonversi Kode SVG ke PNG
categories: SVG, SVG Code, Convert SVG to PNG
---


![Mengkonversi Kode SVG ke PNG]({{ site.baseurl }}/images/svg1.jpg)

## Apa itu SVG?

Menurut https://id.wikipedia.org/wiki/Scalable_Vector_Graphics: Scalable Vector Graphics (SVG) adalah format gambar yang menggunakan XML (Extensible Markup Language) sebagai dasar untuk membentuk gambar vektor dua dimensi. SVG adalah format gambar yang dikembangkan oleh World Wide Web Consortium (W3C) sejak tahun 1999.

Sebuah gambar dengan format SVG disimpan dalam bentuk file XML. Ini berarti, SVG dapat dicari, di-index, ditulis dengan bahasa pemograman dan dikompres. Karena berbasis XML, SVG dapat dibuat dan disunting dengan aplikasi teks apa saja.

Sejumlah peramban web populer seperti Mozilla Firefox, Internet Explorer, Google Chrome, Opera, dan Safari sudah mulai mendukung penggunakan format SVG.

SVG telah direkomendasikan oleh World Wide Web Consortium (W3C) untuk menampilkan grafik serta mendeskripsikan gambar 2 dimensi dalam pengembangan web yang berbasis XML. SVG memperbolehkan tiga tipe dari objek grafis, yaitu bentuk vektor grafis (misalkan jalur yang terdiri dari garis lurus dan kurva), gambar dan teks. Hasil dari SVG dapat juga interaktif dan dinamis. Animasi dapat didefinisikan dan ditimbulkan secara menempelkan elemen animasi SVG pada isi SVG) atau dengan menggunakan skripting. SVG dapat digunakan untuk menghasilkan berbagai macam variasi dari objek grafis, dan juga menyediakan bentuk dasar umum seperti bujur sangkar dan elips. SVG memberikan pengendalian kualitas melalui sistem koordinat dari objek grafis yang telah didefinisikan dan transformasi yang akan digunakan selama proses render.

Penyimpanan berkas (file) SVG dilakukan dengan cara memberi nama ekstensinya dengan “.svg” (memakai huruf kecil semua), dan untuk menyimpan file SVG yang terkompresi memakai ekstensi “.svgz” (semua memakai huruf kecil).

## Keuntungan Penggunaan SVG

Keuntungan penggunaan SVG dibanding format gambar yang lain:
- File sumber SVG dapat dibaca dan modifikasi dengan menggunakan hampir semua tool/text (misalnya Notepad).
- File sumber SVG berukuran lebih kecil dan dapat dikompresi dibanding dengan format gambar JPEG dan GIF.
- Gambar dalam format SVG bersifat scalable/di-resizing.
- Gambar dalam format SVG dapat dicetak dengan kualitas yang tinggi dan sama baiknya pada berbagai resolusi.
- Gambar dalam format SVG bersifat zoomable. Setiap bagian dari gambar dapat di zoom tanpa mengurangi mutu.
- Text dalam SVG “selectable” dan “searchable” (sangat berguna dalam peta).
- SVG dapat bekerja dengan Teknologi Java.
- SVG merupakan “open standard”.
- SVG merupakan murni XML.

## Bagaimana cara convert SVG ke PNG?

- Buka browser Anda, lalu masuk ke alamat domain ini: https://www.svgviewer.dev/

![Mengkonversi Kode SVG ke PNG]({{ site.baseurl }}/images/svg1.jpg)

- Silakan ubah kode yang ada didalam editor dengan kode yang Anda punya

![Mengkonversi Kode SVG ke PNG]({{ site.baseurl }}/images/svg2.jpg)

- Tampilan kosong ketika kode sebelumnya dihapus seperti di bawah ini

![Mengkonversi Kode SVG ke PNG]({{ site.baseurl }}/images/svg3.jpg)

- Lalu paste SVG code yang Anda punya untuk di convert ke PNG

![Mengkonversi Kode SVG ke PNG]({{ site.baseurl }}/images/svg4.jpg)

- Kemudian klik "Download PNG" di pojok kanan atas

![Mengkonversi Kode SVG ke PNG]({{ site.baseurl }}/images/svg4.jpg)

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