---
layout: post
title:  "ubuntu'da dns ayarlarını değiştirme"
date:   2010-11-29 22:48:45
description: Ubuntu kullanıyoruz ve bir sebepten dolayı dns ayarlarımızı değiştirmek istiyoruz. Bunu yapmanın birçok...
categories:
- blog
---

Ubuntu kullanıyoruz ve bir sebepten dolayı dns ayarlarımızı değiştirmek istiyoruz. Bunu yapmanın birçok yolu var tabi ki, ben sadece bunlardan bir tanesini göstereceğim. Öncelikle:

Panelimizden internet bağlantısını gösteren icon'un üzerine sağ tıklıyoruz.

![icon](/images/wireless-nq8.png)

Üstteki resimde gördüğümüz gibi `Bağlantıları düzenle...` tıklıyoruz. Sonra karşımıza çıkan pencereden;

Bağlantımız kablolu ise `Auto eth0` yu seçip düzenle diyoruz. Kablosuz bağlantı kullanıyorsak `--> Kablosuz` sekmesine tıklayıp bağlantımızı seçiyoruz ve düzenle diyoruz.

![ağ bağlantıları](/images/agbaglantilari-nq8.png)

Açılan pencereden `IPv4 Ayarları` nı tıklıyoruz. `Yöntem` kısmını `Sadece otomatik (DHCP) adresler` e getiriyoruz. Ve aşağıdaki resimde görülen ayarlara göre düzenliyoruz.

![ipv4](/images/ipv4-nq8.png)

Eğer bağlantı otomatik olarak yenilenmediyse bağlantıyı koparıp yeniden bağlanıyoruz ve dns ayarlarımız değişmiş oluyor.

Yukarıdaki anlatımda `Google DNS` ayarları gösterilmiştir. İsterseniz başka dns ayarlarını da kullanabilirsiniz.

**Open DNS**
- `208.67.222.222`
- `208.67.220.220`




 

