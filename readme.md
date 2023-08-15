HEAD Etiketinde kullanırız.
<title> Bu etiketi kullanmak şarttır.
<meta>
<style>
<script>
<noscript>
<link>
<base>
NOT: Bunlar dışındaki etiketler body için kullanılır.
------------------------------------------
BODY Etiketi
Site içeriği
------------------------------------------
exercise3:
!+Enter Kullanımı:Aşağıdaki Kodu Kısayoldan Oluşturur

<!DOCTYPE html> --------> Dökümanımızın HTML dili ile oluşturulduğunu tarayıcımıza bildirir
<html lang="en"> ------> Site dilini belirtir (en yerine tr yazılabilir)
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    
</body>
</html>
---------------------------------------------
exercise4:
H Etiketleri(Başlık)
<h1>
<h2>
<h3>
<h4>
<h5>
<h6>

P Etiketi(Paragraf)
<p>
-------------------------------------------
exercise5:
<br> satır atlatma etiketidir.
------------------------------------------
exercise6:
<a> etiketinin en önemli özelliği href özelliğidir. Bu etiket ile sayfaları linkleyebiliriz. Etiket içerisine yazılan içerik sayfa üzerinde gösterilecek içeriktir. href içine yazılan ise tıklandığında gideceği url dir.
------------------------------------------------------
exercise7:
<ul> ve <ol> etiketleri liste oluşturma etiketleridir.
Listeyi oluşturduktan sonra içeriğini oluşturmak için <li> etiketini kullanırız.
<ul>: "unordered list" (sırasız liste)
<ol> : "ordered list" (sıralı liste)

<ul> madde madde gösterir
<ol> 1-2-3-... diye gösterir

<hr> bu etiket paragrafın altına çizgi çeker.
-----------------------------------------------------
exercise8:
<strong> etiketi bir metnin arama motorlarına önemli olduğunu bildirmek için kullanılır. Kullanıldığı zaman metni kalın yapar.
<b> sadece metni kalınlaştırmak istersek kullanılır.
-----------------------------------------------------
exercise9:
<script> JavaScript kodlarını HTML içerisine yazabilmemizi sağlar.
------------------------------------------------------
<button> buton oluşturmak için kullanılır.
------------------------------------------------------
<img> resim eklemek için kullanılır. <img src="resim.jpg" alt="açıklama yazısı" /> 
src="" kısmına eklemek istediğimiz görselin yolunu ekliyoruz.
alt="" kısmına görselin açıklamasını yazıyoruz. fakat isterseniz boş bırakabilirsiniz. bu etiket kapanmaya ihtiyaç duymaz.
-------------------------------------------------------
<iframe> genelde başka sitedeki bir belgeyi kendi sayfamızda göstermek için kullanırız. örn: youtube da bir videoyu kendi sayfamızda göstermek istersek <iframe > etiketini kullanmamız yeterli.(video üzerine sağ tıklayıp yerleştirme kodunu kopyala diyerek iframe kodunu kopyalayabiliriz)
-------------------------------------------------------
<!-- YORUM SATIRI -->
-------------------------------------------------------
exercise12:
<title>Sekmede görünecek isim</title>
-------------------------------------------------------
<style> </style> -----> sayfamızı güzelleştiren renklendiren belli özellikler ekleriz. bu kısımlarda bir html dökümanında hangi alanın nerede ve nasıl gözükmesi gerektiğini tasarlayabiliriz. bu belirteçlere css diyoruz.
------------------------------------------------------
<script></script> ----> sayfamızı canlandıran javascript kodlarının programlamasıdır. html ve css programlama dili değilken burada programlama diline geçiş yapıyoruz.

#script etiketini kullanırken herhangi bir özellik eklemezsek browser sırası geldiğinde doğrudan işlenir. ve bu kısım işlenmeden sayfa yüklenmeye devam etmez. bu noktada async özelliği devreye girer. bu kısmın asenkron çalışmasını istiyorsak etiketimize bu özelliği ekleriz. herhangi bir değer girmeye gerek yoktur. şu şekilde kullanılır:

<script src="myJavascript.js" async></script>

eğer bu etiketin sayfa yüklendikten sonra çalışmasını istersek async özelliğinin yanında defer özelliğini eklemiz gerekir.
-------------------------------------------------------
sekmede görünen ismin yanına ikon ekler
<link rel="icon" href="/favicon.ico" type="image/x-icon">

