---
layout: post
title: flashdiskinizi güvenle kaldırın
---

Flashdiskimizi bilgisayara taktık ve gerekli bilgi alış-verişini yaptık. Sıra çıkarmaya geldi. USB disk iconunun üzerine gelip `sağ click + güvenle kaldır` yapmayı herkes biliyor malum. 

Bu işlevi terminalden yapmayı istersek ne yapacağız? 

Çok basit. Hemen `xterm` ü ya da kullandığımız terminali açıyoruz ve komut satırına:

`$ sudo umount /dev/...`

yazıyoruz. ... olan kısmı `çift tab` yapınca görebiliriz. 

`Tab` ladıktan sonra karşımıza çıkan liste de `sda` sabit diskleri ifade ediyor. Onlara mümkünse dokunmuyoruz :) Bizim işimiz `sdb` olanlarla.

Tek bir usb disk takılıysa o anda `sdb1` olarak görünecektir. Komut satırına:

`$ sudo umount /dev/sdb1`

yazıyoruz ve flashdiskimizi bilgisayarımızdan güvenle kaldırmış oluyoruz.
