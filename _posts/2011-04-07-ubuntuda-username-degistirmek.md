---
layout: post
title:  "ubuntuda username değiştirmek"
date:   2011-04-07 23:56:45
description: username başta seçilmeli ve çok gerekmedikçe değiştirilmemelidir aslında. ama değiştirmek zorunda kalırsak şunları yapmalıyız.
categories:
- blog
---

bildiğiniz gibi linux kullananlar terminali açtıklarına karşılarına şöyle bir manzara çıkıyor:

`username@pc-name:~$`

username başta seçilmeli ve çok gerekmedikçe değiştirilmemelidir aslında. ama değiştirmek zorunda kalırsak şunları yapmalıyız.

- ilk önce farklı bir oturumda olmalıyız. username ini değiştirmek istediğimiz oturum açıkken üzerinde bir değişiklik yapamayız. bunun için 

`sistem-->yönetim-->kullanıcılar ve gruplar` 

kısmından yeni bir hesap oluşturmalı ya da varsa diğer bir hesapta oturum açmalıyız.

daha sonra:

kullandığımız terminali açıp komut satırına şunları yazmalıyız:

$ `sudo usermod -c "Tam İsim" -l yeniusername eskiusername`

daha sonra sizden oturumu açık olan kullanıcının parolasını isteyecektir.
parolanızı girdikten sonra kullanıcı adı başarıyla değiştirilmiş olacaktır.


