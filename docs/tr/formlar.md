Etkileşimli web siteleri (yani kullanıcıdan veri alan web sitelerinde) tek satırlık verilerin alınmasında kullanılan html tagı ``` <form></form>``` elemanıdır.

Etkileşimli web sitelerinin vazgeçilmezlerinden olan form yapısının kıllanımı aşağıda verildiği gibidir.
```
<form>
Adınız:<br>
<input type="text" name="firstname">
<br>
Soyadınız:<br>
<input type="text" name="lastname">
</form>
```

radio button kavramı 
```
<form>
<input type="radio" name="sex" value="male" checked>Bay
<br>
<input type="radio" name="sex" value="female">Bayan
</form>
```

Submit button kavramı sayesinde alınan bilgilerin backend kısmına gönderimi sağlanacaktır.
```
<form action="action_page.php">
<input type="submit" value="Kayıt ol">
</form>
```

Submit button kavramında method kullanımı

POST ve GET metotları bulunmaktadır.Backend tarafında formdan veri almak için kullanılan iki yöntemdir.

POST metodunda gönderilen bilgi bir daha kullanıcı tarafından görülmez iken GET metodunda gönderilen bilgi adres çubuğunda görülür ve müdahale edilebilir. Bu ise bazı güvenlik açıklarına sebep olabilmektedir.
```
<form action="action_page.php" method="GET">

<form action="action_page.php" method="POST">
```


kaynaklar

"http://www.w3schools.com/html/html_forms.asp"

"http://www.baskent.edu.tr/~tkaracay/etudio/ders/internet/html/forms/form/form_01.html"

"http://bilgisayar-muhendisleri.blogspot.com.tr/2013/01/php-get-ve-post-metotlari.html"
