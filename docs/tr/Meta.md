###Meta Etiketleri

Meta etiketleri, bir web sayfasında bilgi vermek ve browserları yönlendirmek amacıyla kullanılır ve <head>...</head> etiketleri arasına yazılır.İki unsuru sık kullanılır:

NAME: Sayfanın yazarı, sayfanın yayın tarihi, ve benzeri bilgileri içerir.

           <meta name="bilginin türü" content="bilgi">

şeklinde yazılır.

HTTP-EQUIV: İçinde yer aldığı sayfanın, web server tarafından ziyaretçiye gönderilmesinde oluşturulacak karşılık başlığı bölümünde yer alacak bilgiler içerir.

           <meta http-equiv="bilginin türü" content ="bilgi">

şeklinde yazılır.

Sıklıkla kullanılan meta etiketleri ve açıklamaları:

<meta http-equiv=Content-Type content="text/htm; charset=windows-1254">
<meta http-equiv=Content-Type content="text/htm; charset=iso-8859-9">
<meta http-equiv=Content-Type content="text/htm; charset=utf-8">
Bu etiketler türkçe karakter sorununu ortadan kaldırmak ve türkçe karakter desteği sağlamak için kullanılır.

<meta="keywords" content ="kelime1 kelime2 kelime3">
Hazırlanan dökümanla ilgili anahtar kelimeler content parametresine yazılır.İnternetteki belli başlı ara bul kurumları siteleri araştırırken bu kelimelere bakarak gruplandırır.

          <meta="keywords" content ="html, HTML, Html Dersleri,  html dersleri, web tasarımı, web tasarimi ">

<meta name ="description" content ="metin">
Hazırlanan döküman ile ilgili açıklamaları yazmak için kullanılır.

          <meta name ="description" content ="Bu sayfa html dersleri için hazırlanmıştır. ">

<meta http-equiv="expires" content ="Tarih">
Güncelleme için kullanılır.İnternette açılan bir sayfa bilgisayara kaydedilir.Bu sayfa tekrar açılamak istendiğinde, bilgisayardaki kayıtlı sayfa açılır.Bu etiket ile belirtilen tarihten sonra bu sayfa açılmak istenirse sayfanın tekrardan serverdan yüklenmesi sağlanır.

<meta http-equiv="expires" content ="Wed, 04 Apr 1999 23:59:59 GMT">

<meta http-equiv="refresh" content="5; url=yeni.htm">
Sayfanın belirtilen süre sonra yenilenmesini sağlar.Yukarıdaki örnekte sayfa 5 saniye sonra yenilenir ve url de belirtilen yeni.htm sayfası açılır.Eğer url boş bırakılırsa aynı sayfa tekrarlanır.

<meta name="robots" content="all veya none">
Hazırladığımız sayfanın arama motorlarının robotları tarafından taranmasına izin vermek veya engellemek için kullanılır.İzin için all, engelleme için none kullanılır.

Meta etiketleri <head> etiketleri arasına yazıldığı için sayfalarda görüntülenmez.İlgili sayfaya ait meta etiketlerinin neler olduğunu kaynak kodlarını görüntüleyerek bakabilirsiniz.
