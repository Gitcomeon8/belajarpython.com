---
layout: article
title: Memparsing api dengan method GET
date: 2021-10-03
categories: artikel
---
---
**_Terimakasih untuk belajarpython.com untuk bisa berbagi ilmu untuk seluruh insan yang mau belajar bahasa python ini,
Ke hadiran saya ini ingin mengeshare cara memparsing data api...**
## step
**Melakukan install 'requests' terlebih dahulu di terminal anda.**
> __$__ pip install requests<br>
Setelah sudah melakukan insta requests, mari kita mainkan apinya hehe,
semisal kita ingin memparsing data api dnslookup.
> import requests<br>
> Url = 'https://api.hackertarget.com/dnslookup/?q={www.site.com}'<br>
> req = requests.get(Url).text<br>
> for x in req:<br>
>    print (x)<br>

**_Gimana mudah kan?, sekian dan terimakasih semoga admin di limpahkan rezekinya.**