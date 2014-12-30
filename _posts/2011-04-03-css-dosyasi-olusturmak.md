---
layout: post
title:  "css dosyası oluşturmak"
date:   2011-04-03 22:48:45
description: css dosyası sitemizin yazı tipi, tablo, menü gibi özellikleri düzenleyebileceğimiz dosyadır. Bize çok...
categories:
- blog
---


- css dosyası nedir?

css dosyası sitemizin yazı tipi, tablo, menü gibi özellikleri düzenleyebileceğimiz dosyadır. bize çok büyük kolaylıklar sağlayabilir. bir buton yapabilir, bir menü üretebilir bu dosyada yazacağımız kodlarla.

genellikle `style.css` ya da `styles.css` olarak kullanılır.

- css kodlarını index sayfasından ayrı tutabilmek için ne yapmalıyız?

`<head> </head>` tagları arasına aşağıdaki kodları ekliyoruz:

- `<link rel="stylesheet" type="text/css" href="style.css" />`

bu linki eklersek style.css dosyasıyla anasayfamız aynı dizinde olmalıdır. 

css dosyasını farklı bir dizinde tutmak istersek:

- `href="/.../style.css"`

... yazan kısma css dosyasını tuttuğumuz klasörün ismini yazarız.




