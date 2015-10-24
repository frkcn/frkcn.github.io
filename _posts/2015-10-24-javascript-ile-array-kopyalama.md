---
layout: post
title:  "Javascript array kopyalama"
date:   2015-10-24 22:47:45
description: Javascript kullanarak bir arrayin değerlerini başka bir arraye...
categories:
- blog
---

Javascript ile array kullanarak bazı işlemler yapıyoruz. Bir arrayin elemanlarını yeni oluşturduğumuz başka bir arraye aktarıp yeni 
oluşturduğumuz array üzerinden işlem yapmaya devam etmek istiyoruz. 

Aklımıza ilk gelen yöntem şöyle olacaktır:

    var newArray = oldArray;
    
Ancak bu şekilde bir atama yaptığımızda artık bu iki array birbiriyle senkron bir hal alır ve birinde yapılan değişiklik diğerini de etkiler.
Bunu engellemek için yapmamız gereken ise:

    var newArray = oldArray.slice();
    
Slice methodu hakkında daha fazla bilgi almak için: [Slice()](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/slice)
