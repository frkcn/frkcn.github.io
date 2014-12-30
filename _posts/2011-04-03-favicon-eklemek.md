---
layout: post
title:  "favicon eklemek"
date:   2010-04-03 22:48:45
description: favicon sitenizin adres çubuğunda görünen resimdir. `16x16` boyutunda olmalıdır. `.ico` uzantısına sahiptir.
categories:
- blog
---

- favicon nedir?

favicon sitenizin adres çubuğunda görünen resimdir. `16x16` boyutunda olmalıdır. `.ico` uzantısına sahiptir.

peki sitemize favicon eklemek için ne yapmamız gerekir.

sayfamızın `<head> </head>` tagları arasına aşağıdaki kodları eklemeliyiz:

- `<link rel="favicon" href="favicon.ico" type="image/icon">`

`favion.ico` ismiyle kaydettiğimiz faviconumuzu sayfayla aynı dizine yüklemeliyiz. eğer faviconu `images` klasörünün altına koymak istersek kodu şu şekilde değiştirmeliyiz:

- `<link rel="favicon" href="/images/favicon.ico" type="image/icon">`







