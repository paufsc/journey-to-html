#HTML Etiketleri

HTML dilindeki en önemli etiketler, başlıklar, paragraflar ve satır atlama etiketleridir.Bunların kullanım şekillerini görelim.

###Başlıklar
```sh
<h1>Bu bir başlık</h1>
<h2>Bu bir başlık</h2>
<h3>Bu bir başlık</h3>
<h4>Bu bir başlık</h4>
<h5>Bu bir başlık</h5>
<h6>Bu bir başlık</h6>
```
`<h1>` en büyük puntoyu belirtirken, `<h6>` ise en küçük puntoyu belirtir.

###Paragraf
```sh
<p>Bu bir paragraf</p>
```
`<p>` etiketinin bileşenleri
 

* align = "left"          Paragrafı sola dayalı olarak yazar.

* align = "right"         Paragrafı sağa dayalı olarak yazar.

* align = "center"        Paragrafı ortalar.

* align = "justify"       Paragrafı sola ve sağa dayalı olarak yazabilmek için sözcüklerin ara boşluklarını değiştirir.

* class = "css_etiketi"   Önceden tanımlı bir CSS dosyasındaki font-size, color... gibi özellikleri paragrafa uygular.


###Satır Atlama
```sh
<p>Bu <br>bir <br>çok satırlı paragraftır.</p>
```
`<br>` tagından itibaren bir alt satıra geçer

###`<center>` `</center>` Etiketi

Kendi yorum aralığında bulunan tüm etiketlerin ekran çıktılarını browser penceresine ekranı ortalayacak şekilde basar.
`<center>`
....
Burası etiketin yorum aralığı
.....
`</center>`
...

###Temel HTML Etiketleri
```sh
Etiket(Tag)	     Açıklama
-------          --------
<html>	        Bir HTML dökümanını belirtir
<body>	        Dökümanın görüntülenecek kısmını berlitir.
<h1> to <h6>    Başlıkları belirtir.
<p>           	Bir paragraf belirtir
<br>          	Boş bir satır bırakır.
<hr>          	Sayfada yatay bir çizgi çizer
<!-->	        Yorum satırı olduğunu belirtir.
```




===========

[Previous](Elementler.md)|[Next](Parametreler.md)
-----|-----
