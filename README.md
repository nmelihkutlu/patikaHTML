# SQL - patika.dev - Soru ve Cevapları
>**[patika.dev](https://app.patika.dev/courses/html) platformu HTML öğrenme amaçlı soruların cevaplanması projesidir.** \
> **Profil için tıklayınız: [app.patika.dev/nmelihkutlu](https://app.patika.dev/nmelihkutlu)**


![](https://raw.githubusercontent.com/nmelihkutlu/patikaHTML/main/patikaHTML.png)



[Ödev1](#ödev-1)[Ödev2](#ödev-2)

## Ödev 1

### Soru
İlk Web Sayfamızı Oluşturmak

Eveet harika konular öğrendikten sonra sıra geldi ödevimize. Bu ödevimizde ilk web sayfamızı tasarlayacağız. Çok heyecanlı değil mi? Sizlerden istediğimiz çok basit bir şekilde öğrendiklerinizle bir web sayfası tasarlamanız.

- Siteyi açtığımızda adınız ve soyadınızı başlık şeklinde göstermeniz gerekiyor.
- Ad-Soyadın altında alt başlık olarak Hakkımda yazmalıdır.
- Altına paragraf içerisinde neler yaptığınızı ve nelerden hoşlandığınızı yazabilirsiniz.
- Web sitenizi kaydederken dosya adı olarak 'index.html' seçmeniz gerekmektedir.
- Yazdığınız kodları açıklayan yorum satırları eklemeyi unutmayın.

### Cevap
**Dosya için tıklayınız: [odev1.html](https://github.com/nmelihkutlu/patikaHTML/blob/main/odev1.html)**

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <h1>N.Melih KUTLU</h1>
    <h2>Hakkımda:</h2>
    <p>Freelancer olarak çalışmaktayım. Hızlıca eksik bilgilerimi tamamlayıp iş alıp para kazanmak istiyorum.</p>
    <!-- Eski öğretmenim. Ortaokuldan beri yazılım işi ile uğraşıyorum aslında. -->
    <h2>Bazı freelance siteleri</h2>
    <li>www.freelancer.com</li>
    <li>www.fiverr.com</li>
    <p></p>
</body>
</html>
```



## Ödev 2

### Soru
Kişisel Sayfamızı Detaylandırmaya Devam Etmek

Bir önceki ödevimizde ilk web sayfamızı yapıp bunu kişisel sayfamız olarak tasarlamıştık. Yeni öğrendiğimiz bilgiler dahilinde bu sayfayı geliştirmeye devam edelim. Hazır mısınız? E hadi buyurun o zaman.

- Sayfanıza bir adet resim ekleyin ve bu resime bir açıklama yazın.
- Sevdiğiniz film, dizi ve kitapları bunlar başlıklar olacak şekilde sıralayınız. (Film, dizi, kitap sıralı liste, içerikleri bullet liste olacak şekilde)
- Bunları sıralarken film ve dizilerin en az bir tanesine IMDb linki, kitapların bir tanesine de** Goodreads linkini** yazınız.
- Kurduğunuz yapılarda block, inline gibi elementler kullanmaya çalışın.

### Cevap
**Dosya için tıklayınız: [odev2.html](https://github.com/nmelihkutlu/patikaHTML/blob/main/odev2.html)**

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <img src="https://avatars.githubusercontent.com/u/113768580?v=4" alt="nmelihkutlu profil resmi">
    <h1>N.Melih KUTLU</h1>
    <h2>Hakkımda:</h2>
    <p>Freelancer olarak çalışmaktayım. Hızlıca eksik bilgilerimi tamamlayıp iş alıp para kazanmak istiyorum.</p>
    <!-- Eski öğretmenim. Ortaokuldan beri yazılım işi ile uğraşıyorum aslında. -->
    <h2>Bazı freelance siteleri</h2>
    <li>www.freelancer.com</li>
    <li>www.fiverr.com</li>
    <h2>Film, Dizi ve Kitaplar</h2>
    <ol>
        <li>En iyi 3 film:
            <ul> 
                <li><a href="https://www.imdb.com/title/tt0111161">Esaretin Bedeli</a></li>
                <li><a href="https://www.imdb.com/title/tt0468569">Kara Şövalye</a></li>
                <li><a href="https://www.imdb.com/title/tt0068646">Baba</a></li>
            </ul>
        </li>
        <li>En iyi 3 dizi (Beyazperde):
            <ul> 
                <li><a href="https://www.beyazperde.com/diziler/dizi-4528/">Sherlock</a></li>
                <li><a href="https://www.beyazperde.com/diziler/dizi-3517/">Breakin Bad</a></li>
                <li><a href="https://www.beyazperde.com/diziler/dizi-7157/">Game of Thrones</a></li>
            </ul>
        </li>
        <li>En iyi 3 kitap (1000kitap):
            <ul> 
                <li><a href="https://1000kitap.com/kitap/suc-ve-ceza--121">Suç ve Ceza</a></li>
                <li><a href="https://1000kitap.com/kitap/sefiller-2-cilt-takim--172">Sefiller</a></li>
                <li><a href="https://1000kitap.com/kitap/seker-portakali--239">Şeker Portakalı</a></li>
            </ul>
        </li>
    
    </ol>
    
</body>
</html>
```
