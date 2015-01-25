# HTML 'de Stil 

Bütün HTML sitelerinin varsayılan ayarları siyah yazı rengi ve beyaz arkaplan rengidir.Biz bu bölümde bu gibi buna benzer ayarları değiştirmeyi anlatacağız.
İlk olarak arka plan renk ayarı için `<body style="background-color:lightgrey"` etiketini,Metin rengine gelecek olursak `<h1 style="color:blue"> ve  <p style="color:red"> ` etiketlerini,Yazı aileleri için ise `<h1 style="font-family:verdana"> ve <p style="font-family:courier"> ` gibi etiketleri,Metin boyutunu ayarlamak istersek ` <h1 style="font-size:300%"> ve <p style="font-size:160%">` etiketleri,hizalama yapmak için `<h1 style="text-align:center">` etiketi ortalama yapmak için kullanılabilir.Örnek vermek gerekirse ;

```sh
<h2 style="color:red">Kırmızı</h2>
<h2 style="color:blue">Mavi</h2>
```

Kodun Çıktısı :
<h2 style="color:red">Kırmızı</h2>
<h2 style="color:blue">Mavi</h2>

```sh
<body style="background-color:lightgrey">
<h1>Başlık</h1>
<p>Paragraf.</p>
</body>
```

Kodun Çıktısı:

<body style="background-color:lightgrey">
<h1>Başlık</h1>
<p>Paragraf.</p>
</body>

```sh
<h1 style="font-family:Comic Sans MS">
Başlık</h1>

<p style="font-family:courier">
Paragraf.</p>
```

Kodun Çıktısı:

<h1 style="font-family:Comic Sans MS">
Başlık</h1>

<p style="font-family:courier">
Paragraf.</p>
```sh
<body>
  <h1 style="font-size:300%">Başlık</h1>
  <p style="font-size:160%">Html' de text boyutu.</p>
</body>
```

Kodun Çıktısı :

<body>
  <h1 style="font-size:300%">Başlık</h1>
  <p style="font-size:160%">Html' de text boyutu.</p>
</body>

```sh
<body>
  <h1 style="text-align:center">Başlık Ortalama</h1>
  <p>Paragraf.</p>
</body>
```

Kodun Çıktısı: 
<body>
  <h1 style="text-align:center">Başlık Ortalama</h1>
  <p>Paragraf.</p>
</body>
