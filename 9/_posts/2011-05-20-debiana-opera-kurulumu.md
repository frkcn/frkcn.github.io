---
layout: post
title: debiana opera kurulumu
---

İlk yapmamız gereken sudo yetkileri almak. 

Sistemde `superuser` olmak için terminale: `sudo -s` yazıyoruz.

daha sonra **sudo** yetkisiyle `/etc/apt/source.list` dosyasına kullandığımız debian sürümüne göre depo ekliyoruz. Aşağıdaki depolardan sadece kullandığımız debian sürümününkini seçip ekliyoruz.

`# Opera Browser - Production release
deb http://deb.opera.com/opera/ potato non-free
deb http://deb.opera.com/opera/ woody non-free
deb http://deb.opera.com/opera/ sarge non-free
deb http://deb.opera.com/opera/ etch non-free
deb http://deb.opera.com/opera/ lenny non-free
deb http://deb.opera.com/opera/ squeeze non-free
deb http://deb.opera.com/opera/ sid non-free`

Ben squeeze sürümü için bunu ekliyorum:

`deb http://deb.opera.com/opera/ squeeze non-free`

Ardından depo anahtarını sisteme tanıtmak için konsoldan aşağıda ki komutu veriyoruz.

`wget -O - http://deb.opera.com/archive.key | apt-key add -`

Depoyu güncelliyoruz.

`apt-get update`

Operayı kuruyoruz.

`apt-get install opera`








