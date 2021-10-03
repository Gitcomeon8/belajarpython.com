---
layout: article
title: Memparsing api dengan method GET
date: 2021-10-03
categories: artikel
---
---
Terimakasih untuk belajarpython.com untuk bisa berbagi ilmu untuk seluruh insan yang mau belajar bahasa python ini,
Ke hadiran saya ini ingin mengeshare cara memparsing data api...
## step
Melakukan install 'requests' terlebih dahulu di terminal anda.
> __$__ pip install requests<br>
Setelah sudah melakukan insta requests, mari kita mainkan apinya hehe,
semisal kita ingin memparsing data api dnslookup.
> __ import requests
> __ Url = 'https://api.hackertarget.com/dnslookup/?q={www.site.com}'
> __ req = requests.get(Url).text
> __ for x in req:
> __    print (x)

Gimana mudah kan?, sekian dan terimakasih semoga admin di limpahkan rezekinya.
