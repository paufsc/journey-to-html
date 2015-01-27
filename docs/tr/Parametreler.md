#Html'de Parametreler
Html'de parametre adıyla adlandırdığımız bazı nitelikler vardır.Etiketlerin kendi içerisinde parametre tanımlayıp onlara bazı basit özellikler verebiliriz.
```sh
  <h1>Büyük başlık</h1>  ----->   Bu html dilinde etikettir.

  <h1 align="center">Büyük başlık</h1>  ----->  Bu ise html de Parametredir. 
```

* BGCOLOR Arka plan rengini belirler 
* BACKGROUND Arka plana resim ekler 
* TEXT Yazı rengini belirler 
* LINK Sayfadaki linklerin(bağlantıların) rengini belirler 
* ALINK Aktif link rengini belirler 
* VLINK Ziyaret edilmiş linklerin rengini belirler 
* LEFTMARGIN Sayfanın sol ve sağından ne kadar içeriye doğru kayacağını belirler. 
* TOPMARGIN Sayfanın üst kısmından ne kadar içeriye doğru kayacağını belirler. 

`Örnek:`
```sh

< bOdy bgcolor="red" >  veya < bOdy bgcolor="#FF0000" >  
Arka plan rengini değiştirmek için rengin ingilizce adını (red gibi) yada hexadecimal kodunu (#FF0000 gibi) girmeliyiz. Dikkat ettiyseniz hexadecimal kodu girerken kodun başına # işareti ekliyoruz Eğer kod kullanacaksak bu işareti kullanmalıyız yoksa yanlış olur.

< bOdy background="banner.JPG" >  
Artalan resim eklemek için bu komutu kullanırız " " iki tırnak işareti arasına resmin bulundugu yeri ,resmin adını ve resmin uzantısını yazarız "banner.JPG" örneğinde banner resmin adı JPG ise resmin uzantısı (türü) resim eğer html belgemiz ile aynı klasörde ise yolu yazmıyoruz 
Eğer banner adlı resmimiz resimler klasörü altında ise < bOdy background="resimler/banner.JPG" >  şeklinde belirtiyoruz. 

< bOdy text="yellow" >  yazı rengini sarı yaptık 

< bOdy link="blue" alink="red" vlink="#CC33FF" >  linkler mavi aktif link kırmızı ziyaret edilmiş linkler mor oldu. 

< bOdy leftmargin="50" topmargin="50" >  sayfa içeriği kenara yapışık olmadı belirttiğimiz miktarda içeriye kaydı.
```
