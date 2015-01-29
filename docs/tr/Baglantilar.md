#Html'de Bağlantılar
Bir HTML belgesinde bağlantı (link) verme işini `<a href="adres">` koduyla yapmaktayız. Link verdiğimiz kelime ortaya gelecek şekilde yine `</a>` ile bağlantı verme işini sonlandırmaktayız. Bu şekilde başka bir sayfaya ya da web sitesie bağlantı veririz. Aynı zamanda bu yolla bir müzik dosyası, bir zip arşivi vb. de link vermeniz mümkün.
###Örnek:
```sh
<html>
   <head>
      <title>Bağlantı Ekleme</title>
   </head>
   <body>
  <a href="www.google.com" target="_blank"> Google sitesine gitmek için tıklayın </a>
   </body>
</html>
```
Not:`target` =>Bağlantımızın yeni sekmede mi yoksa  içinde bulunduğumuz sitenin yerine mi açılacağını gösterir.

##Bir Resime Link Vermek
```sh
<html>
<body>
<p>
Bir resimi ayrıca link olarak kullanabilirsiniz:
<a href="sonsayfa.htm">
<img border="0" src="buttonnext.gif" width="65" height="38">
</a>
</p>

</body>
</html>
```
