# HTML 'de Listeleme

Html ' de listeleme konusunda 3 çeşit listeleme vardır.Bunlar:

<ul style="list-style-type:square">
<li>Unordered Listeleme</li>
<li>Ordered Listeleme</li>
<li>HTML Descreption List</li>
</ul>

   > İlk olarak Unordered Listelemeyi inceleyelim
    Adından da anlaşılacağı gibi bu listeleme yönteminde belli bir order(sıralama) söz konusu değildir.Yani bir öncelik sırası falan yoktur.Öncelik sırasını ordered sıralamayı anlatırken ne demek istediğimi daha açık anlatacağım.Örnek vermek gerekirse ;

```sh
<ul style="list-style-type:disc">
  <li>Çay</li>
  <li>Ayran</li>
  <li>Türk Kahvesi</li>
</ul>
```
Kodun Çıktısı:

<ul style="list-style-type:disc">
  <li>Çay</li>
  <li>Ayran</li>
  <li>Türk Kahvesi</li>
</ul>
    
    
 > Sıra Ordered Listelemeyi inceleyelemeye geldi.
    Adından anlaşılacağı gibi bu listeleme yönteminde sıralama önemli bir listeleme türüdür.Yani maddelemede kullanılan ifadelerin sırası önemlidir.Örnek vermek gerekirse ;
   
```sh
<ol>
 <li>ELma</li>
 <li>Armut</li>
 <li>Limon</li>
 <li>Portakal</li>
</ol>  
```
Kodun Çıktısı:

<ol>
 <li>ELma</li>
 <li>Armut</li>
 <li>Limon</li>
 <li>Portakal</li>
</ol>  

>Ordered  listemede sıralama olarak hangi maddeleme işareti istersek seçebiliriz.Nasıl gelin bunu örneklerle açıklayalım;
>>Örnek 1:
```sh
<ol type="1">
 <li>ELma</li>
 <li>Armut</li>
 <li>Limon</li>
 <li>Portakal</li>
</ol>  
```
Kodun Çıktısı:

<ol type="1">
 <li>ELma</li>
 <li>Armut</li>
 <li>Limon</li>
 <li>Portakal</li>
</ol>  

>>Örnek 2:
```sh
<ol type="A">
 <li>ELma</li>
 <li>Armut</li>
 <li>Limon</li>
 <li>Portakal</li>
</ol> 
```
Kodun Çıktısı:

<ol type="A">
 <li>ELma</li>
 <li>Armut</li>
 <li>Limon</li>
 <li>Portakal</li>
</ol>  

>>Örnek 3:
```sh
<ol type="I">
 <li>ELma</li>
 <li>Armut</li>
 <li>Limon</li>
 <li>Portakal</li>
</ol> 
```
Kodun Çıktısı:

<ol type="I">
 <li>ELma</li>
 <li>Armut</li>
 <li>Limon</li>
 <li>Portakal</li>
</ol> 

>Gibi örneklerle anlaşılabilir.

> Ve son olarak HTML Descreption'a bakalım.Bunda ise tanımlama ve açıklama şeklinde liste oluşturulur.Bu gibi listeler `<dl>` etiketi ile başlar.Her terim için `<dt>` etiketiyle ve her tanım(açıklama) `<dd>` etiketi ile başlatılır.


```sh
<dl>
<dt>Çay</dt>
<dd>Sıcak içecek</dd>
<dt>Ayran</dt>
<dd>Beyaz soğuk içecek</dd>
</dl>
```

Kodun Çıktısı :

<dl>
<dt>Çay</dt>
<dd>Sıcak içecek</dd>
<dt>Ayran</dt>
<dd>Beyaz soğuk içecek</dd>
</dl>

>İç içe listeler iki tane `<ul>` kullanımıyla kolaylıkla oluşturulabilir.

```sh
<ul>
  <li>Kahve</li>
  <li>Çay
    <ul>
    <li>Yeşil çay</li>
    <li>Siyah çay</li>
    </ul>
  </li>
  <li>Kola</li>
</ul>
```
Kodun Çıktısı :

<ul>
  <li>Kahve</li>
  <li>Çay
    <ul>
    <li>Yeşil Çay</li>
    <li>Siyah Çay</li>
    </ul>
  </li>
  <li>Kola</li>
</ul>

>Bir diğer listeleme türü ise menu şeklinde bunun için ise `<ul id="menu">` etiketi kullanılarak yapılmaktadır.
````sh
<ul id="menu">
  <li>Elma</li>
  <li>Muz</li>
  <li>Portakal</li>
  <li>Kivi</li>
</ul> 
```
Kodun Çıktısı :
<ul id="menu">
  <li>Elma</li>
  <li>Muz</li>
  <li>Portakal</li>
  <li>Kivi</li>
</ul> 




