---
author = "masetio"
categories = ["blog"]
description = ""
linktitle = ""
type = "post"
title= "Console Linux Di Android"
date =2019-05-17T16:34:05Z
draft = false
---
## iseng
Sambil menunggu perjalanan kereta jalur selatan yang lama banget, kepikiran untuk ngeblog, seperti post sebelumnya xxxx kalau blog ini di tenagai oleh ++HUGO++ yang managenya harus dengan _console_. Untuk itu saya mengsetup Handphone saya ini versi Redmi 4A agar support console linux.
1. Install termux
   Pertama install aplikasi **termux** dadi playstore. Setelah terinstall perlu di konfigurasi agar _storage_ android dapat di akses oleh **termux** dengan cara menjalankan program 
   ```
   termux-setup-storage
   ```
   Akan muncul folder _storage_ pada folder _home_ **termux**. Semua storage Android sepweti image, DCIM dan lainnya dapat di akses dari folder _home_ - nya **termux**
2. Install hugo, git
   Selanjutnya install program hugo dan git
   ```
   pkg hugo & & pkg git
3. Install epsilon markdown editor
  HUGO menggunakan format _markdown_, dari pada manual belajar syntax nya.. Mending pake editor yang sudah support, beneran sangat membantu. Saya cukup pake yang free saja hehehee klo mau versi premium murah juga kok IDR 69.000