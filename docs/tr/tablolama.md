# HTML 'de Tabloları

Html ' de tabloları oluşturmak için `<table>` etiketi kullanılır.Satırları oluşturmak için `<tr>` etiketi ve sütun için `<td>` etiketi kullanılır.
Örnek tablo oluşturmak gerekirse;
```sh
<table>
<tr>
<td>satır 1, hücre 1</td>
<td>satır 1, hücre 2</td>
</tr>
<tr>
<td>satır 2, hücre 1</td>
<td>satır 2, hücre 2</td>
</tr>
</table>
```
Kodun Çıktısı:

<table>
<tr>
<td>satır 1, hücre 1</td>
<td>satır 1, hücre 2</td>
</tr>
<tr>
<td>satır 2, hücre 1</td>
<td>satır 2, hücre 2</td>
</tr>
</table>
 
 
Tablolarda kenarlık göstermek isterseniz `<table border="1">` şeklinde yazmanız yeterli olacaktır.Tabloya başlık eklemek için ise `<th>` etiketi tr etiketi açılıp içine yazılımalıdır.İçinde veri olmayan kutunun kenarlıklarını görüntüleyebilmek için `<td>&nbsp;</td>` etiketinin içine yazılarak halledilmiş olur.

Örnek vermek gerekirse ;
```sh
<table border="1">
<tr>
<th>Başlık 1</th><th>Başlık 2</th>
</tr>
<tr>
<td>Satır 1, Hücre 1</td>
<td>Satır 1, Hücre 2</td>
</tr>
<tr>
<td>Satır 2, Hücre 1</td>
<td>&nbsp;</td>
</tr>
</table>
```

Kodun Çıktısı:

<table border="1">
<tr>
<th>Başlık 1</th><th>Başlık 2</th>
</tr>
<tr>
<td>Satır 1, Hücre 1</td>
<td>Satır 1, Hücre 2</td>
</tr>
<tr>
<td>Satır 2, Hücre 1</td>
<td>&nbsp;</td>
</tr>
</table>


