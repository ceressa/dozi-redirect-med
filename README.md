# med.dozi.app -> med.bardino.app

Bu depo yalnizca eski adresi yeni adrese yonlendirir. Sitenin kendisi
https://med.bardino.app adresinde, kaynagi dozi-app-pages deposunda.

- Her eski sayfa ayni yoldaki yeni sayfaya gider (JS + meta refresh); sorgu ve # korunur.
- Bilinmeyen yollar 404.html uzerinden ayni yol ve sorguyla yonlenir (iOS universal link yollari /i/* ve /invite/* dahil).
- .well-known/assetlinks.json ve .well-known/apple-app-site-association bayt bayt
  kaynaktaki gibi (com.bardino.dozi, com.bardino.dozi.ios). Yonlendirilirlerse dogrulama duser.

Uygulamalardaki ve magaza kayitlarindaki linkler yeni adrese gecip dozi.app devredildiginde
bu depo silinebilir.
