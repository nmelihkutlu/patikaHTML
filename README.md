# SQL - patika.dev - Soru ve Cevapları
>**[patika.dev](https://app.patika.dev/courses/html) platformu HTML öğrenme amaçlı soruların cevaplanması projesidir.** \
> **Profil için tıklayınız: [app.patika.dev/nmelihkutlu](https://app.patika.dev/nmelihkutlu)**


![](https://raw.githubusercontent.com/nmelihkutlu/patikaHTML/main/patikaHTML.png)



[Ödev1](#ödev-1) - [Ödev2](#ödev-2) -  [Bölüm Sonu Ödevi](#bölüm-sonu-ödevi) - [Ödev3](#ödev-3)

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

## Bölüm Sonu Ödevi

### Soru
Bölüm sonu çalışmasını yapınız.
### Cevap
Çalışma aşağıdaki gibidir.
```html

<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kodluyoruz</title>
</head>
<body>
    <!--Navbar- Start -->
    <header>
        <nav>
            <ul>
                <li>
                    <a href="index.html">Ana Sayfa</a>
                </li>
                <li>
                    <a href="about-us.html">Hakkımızda</a>
                </li>
                <li>
                    <a href="contact.html">İletişim</a>
                </li>
            </ul>
        </nav>
    </header>
    <!--Navbar- End -->

    <!--Content - Start -->
    <section>
        <!--Article - Start -->
        <article>
            <h2>Birinci Yazı</h2>
            <img height="300" src="img/image.jpg" alt="yazı 1'in resmi">
            <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Molestias, odio!</p>
            <p>Lorem ipsum dolor sit amet.</p>
            <p>Tempora tempore maxime quisquam quod.</p>
            <p>Eligendi aspernatur explicabo molestiae adipisci!</p>
            <ol>
                <li>Lorem, ipsum dolor.</li>
                <li>Debitis, amet neque.</li>
                <li>Ex, dicta temporibus!</li>
            </ol>
            <hr>
        </article>
        <article>
            <h2>İkinci Yazı</h2>
            <img src="https://picsum.photos/id/27/600/300" alt="yazı 2'in resmi">
            <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Molestias, odio!</p>
            <p>Lorem ipsum dolor sit amet.</p>
            <p>Tempora tempore maxime quisquam quod.</p>
            <p>Eligendi aspernatur explicabo molestiae adipisci!</p>
            <ul>
                <li>Lorem, ipsum dolor.</li>
                <li>Dolorum, voluptate porro!</li>
                <li>Doloribus, sequi. Temporibus!</li>
            </ul>
            <hr>
        </article>
        <article>
            <h2>Üçüncü Yazı</h2>
            <img src="https://picsum.photos/id/217/600/300" alt="yazı 3'in resmi">
            <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Molestias, odio!</p>
            <p>Lorem ipsum dolor sit amet.</p>
            <p>Tempora tempore maxime quisquam quod.</p>
            <p>Eligendi aspernatur explicabo molestiae adipisci!</p>
            <hr>
        </article>
    <!--Article - End -->
    </section>
    <!--Content - End -->
    
    <!--Footer - Start -->
    <nav>
        <ul>
            <li>
                <a href="index.html">Ana Sayfa</a>
            </li>
            <li>
                <a href="about.html">Hakkımızda</a>
            </li>
            <li>
                <a href="contact-us.html">İletişim</a>
            </li>
        </ul>
    </nav>
    <!--Footer - End -->
</body>
</html>
```


## Ödev 3

### Soru
Çikolatalı Küp Tarifi
Bu ödevimizde sevdiğimiz bir yemek ya da tatlının tarifini öğrendiğimiz bir web sitesini, HTML etiketlerini kullanarak yazmaya çalışacağız. Aşağıdaki resim size yol gösterebilir.
Bir önceki ödevimizde ilk web sayfamızı yapıp bunu kişisel sayfamız olarak tasarlamıştık. Yeni öğrendiğimiz bilgiler dahilinde bu sayfayı geliştirmeye devam edelim. Hazır mısınız? E hadi buyurun o zaman.
![](https://raw.githubusercontent.com/Kodluyoruz/taskforce/main/html/html-odev3/figures/%C3%A7ikolatak%C3%BCpleri.PNG)


### Cevap
**Dosya için tıklayınız: [odev3.html](https://github.com/nmelihkutlu/patikaHTML/blob/main/odev3.html)**

```html
<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kuru İncir Tatlısı</title>
</head>
<body>
    <!--head-->
    <section>
        <img height="200" src="https://i.nefisyemektarifleri.com/2020/12/01/kuru-incir-tatlisi-1.jpg" alt="Kuru İncir Tatlısı">
        <h1>KURU İNCİR TATLISI</h1>
        <a href="https://www.nefisyemektarifleri.com/kuru-incir-tatlisi-8453403/"><em>Nefis Yemek Tarifleri</em></a>
    </section>
    
    <!--ingredients-->
    <section>
        <h2>Kuru İncir Tatlısı Tarifi Nasıl Yapılır?</h2>
        <ol>
            <li>Önce kuru incirleri bir kaba alarak üzerlerine sıcak su dökün ve on beş dakika yumuşamalararını sağlayın.</li>
            <li>Suyu süzün ve incirlerin sap kısımlarını kesin.</li>
            <li>Kesik olan kısımları içe doğru kıvırınca oluşan çukura yarım cevizleri yerleştirin.</li>
            <li>Yayvan bir tencereye hepsini alarak üzerine 1büyük çay bardağı şekeri dökün.</li>
            <li>2su bardağı su ilave edin.</li>
            <li>Kaynayana kadar orta, kaynadıktan sonra kısık ateşte kapağı kapalı olarak pişirin. Bu arada sık sık kontrol edin. İncirler iyice pişip şerbeti koyulaşmaya başlayınca kapatın.</li>
            <li>Servis etmeden on dakika kadar önce tereyağını eritip incirlerin üzerine gezdirin.</li>
            <li>Soğuduktan sonra, kaymak veya dondurma ile servis edin.</li>
        </ol>
    </section>

    <!--photos-->
    <section>
        <img height="100" src="https://i.nefisyemektarifleri.com/2020/12/01/kuru-incir-tatlisi-2.jpg" alt="Tarif Resimleri">
        <img height="100" src="https://i.nefisyemektarifleri.com/2020/12/01/kuru-incir-tatlisi-3.jpg" alt="">
        <img height="100" src="https://i.nefisyemektarifleri.com/2020/12/01/kuru-incir-tatlisi-4.jpg" alt="">
        <img height="100" src="https://i.nefisyemektarifleri.com/2020/12/01/kuru-incir-tatlisi-5.jpg" alt="">
        <img height="100" src="https://i.nefisyemektarifleri.com/2020/12/01/kuru-incir-tatlisi-6.jpg" alt="">
        <img height="100" src="https://i.nefisyemektarifleri.com/2020/12/01/kuru-incir-tatlisi-7.jpg" alt="">
        <img height="100" src="https://i.nefisyemektarifleri.com/2020/12/01/kuru-incir-tatlisi-8.jpg" alt="">
        <img height="100" src="https://i.nefisyemektarifleri.com/2020/12/01/kuru-incir-tatlisi-9.jpg" alt="">
        <img height="100" src="https://i.nefisyemektarifleri.com/2020/12/01/kuru-incir-tatlisi-10.jpg" alt="">
        <img height="100" src="https://i.nefisyemektarifleri.com/2020/12/01/kuru-incir-tatlisi-11.jpg" alt="">
        <img height="100" src="https://i.nefisyemektarifleri.com/2020/12/01/kuru-incir-tatlisi-12.jpg" alt="">
        <img height="100" src="https://i.nefisyemektarifleri.com/2020/12/01/kuru-incir-tatlisi-13.jpg" alt="">
    </section>

    <!--footer-->
    <section>
        <p><b>Afiyet Olsun</b></p>
    </section>
    
</body>
</html>
```
