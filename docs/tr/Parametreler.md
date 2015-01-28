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

* < sup > yazacağımız yazı < /sup >  iki tag arasındaki yazı satırın birazcık üzeride görünür.
* < sub >  yazacağımız yazı < /sub >  iki tag arasındaki yazı satırın birazcık altında görünür.
* < strike > yazacağımız yazı < /strike >  iki tag arasındaki yazı üstü çizili olur 
* < em > yazacağımız yazı < /em >  vurguyu belirtmek için kullanılır dışarıya biraz eğik çıkar 
* < strong > yazacağımız yazı < /strong >  güçlü vurguyu belirtir dışarıya biraz koyu çıkar 
* < code >  yazacağımız yazı < /code >  yasa kural belirten yazılar için kullanılır 
* < samp >  yazacağımız yazı < /samp >  
* < var >  yazacağımız yazı < /var >  tam emin olmadığımız yazılar için kullanılır. 
* < dfn >  yazacağımız yazı < /dfn >  tanımlama belirten yazılar için kullanılır. 
* < cite > yazcağımız yazı < /cite >  alıntı olan yazıyı belirtmek için kullanılır. 
* < small >  yazacağımız yazı < /small >  bu iki tag arasındaki yazı dışarıya çok küçük çıkar.
* < big > yazacağımız yazı < /big >  bu iki tag arasına yazılan yazı dışarıya çok büyük çıkar. 
* < addres > yazağımız yazı < /addres >  bu iki tag adres belirtmek için kullanılır. 
* < kbd >  yazacağımız yazı < /kbd >  bu iki tag arasına yazacağımız yazı keyboard karakterleri gibi görünür. 
* < tt > yazacağımız yazı < /tt >  bu iki tag arasına yazılan yazı daktilo yazısı gibi olur. 
* < div align= center | left | right > yazacağımız yazı < /div >  yazının satırın neresinde görünmesini bu tag ile belirleriz < p align= left | center | right  >  < /p >  ile aynı görevdedir 
* < hr size="2" width="20" color="yellow" > bu tag çizgi çizdirmeye yarar width yatay uzunluğu color rengi size dikey uzunluğu belirler. 
* < marquee bgcolor="blue" loop="170" direction= up | down | right | left scrolldelay="100" scrollamount="30" width="400" height="15" behavior="alternate"  >  
yazıcağımız yazı veya ekleyeceğimiz resim bölümü 
===========

[Previous](Etiketler.md)|[Next](OzelKarakterler)
-----|-----
