---
layout: post
title: jpg to ascii
---

Bir fotoğrafı ascii karakterlerine dönüştürmek mümkün. Bunun için **jp2a** yı kullanabiliriz.

Öncelikle debian veya debian tabanlı işletim sistemimize bu programı nasıl kuracağımıza bakalım.
Komut satırına:

`apt-get install jp2a`

yazarak kurulum işlemini gerçekleştiriyoruz.

Bir çok kullanım fonksiyonu mevcut ben bir tane örneği göstereceğim.

`$ jp2a -b --chars="   ...',;:clodxkO0KXNWM" fotograf_adi_ya_da_linki`

komut satırına yazdıktan sonra fotoğrafın ascii karakterlerine dönüşmüş halini ekranda görebiliyoruz.

**Örnek Resimler**

![orijinal resim](/images/jp2a1.jpg)

![dönüştürülmüş resim](/images/jp2a2.jpg)

Daha ayrıntılı bilgi için komut satırınıza:

`$ jp2a --help` ya da `$ man jp2a` yazabilirsiniz.

İlgili web sitesi: [http://csl.sublevel3.org/jp2a/](http://csl.sublevel3.org/jp2a/)
