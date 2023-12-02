<div align="center">
<img src="https://github.com/burakozdemirtas/weather-app/assets/33163650/a2e9740f-e3e4-49d6-aa23-d6efd0a287c5" width="160" height="160">
</div>



<h1 align="center"> Weather App </h1>
<p align="justify">
Bu proje, OpenWeatherMap API ve temel HTML ve JavaScript kodları kullanılarak gerçek zamanlı hava durumu bilgilerini gösteren bir web uygulaması örneğini içermektedir. Kullanıcı şehir adını girdiğinde, uygulama bu şehre ait hava durumu verilerini API üzerinden çeker ve kullanıcıya sıcaklık, nem, rüzgar hızı gibi bilgileri sunar. Ayrıca, hava durumu durumuna göre arka plan fotoğrafını ve hava durumu ikonunu dinamik olarak değiştirerek kullanıcıya görsel bir deneyim sunar.
</p>

*  [:fire: Geliştirici / Developer](#fire-geliştirici-developer)
*  [:hash: Kod Nasıl Çalışır?/How does the code work?](#hash-kod-nasıl-çalışır-how-does-the-code-work)


# :fire: Geliştirici/ Developer
| Adı Soyadı / Name Surname| 
| :--- | 
| [Burak ÖZDEMİRTAŞ](https://github.com/burakozdemirtas) |


# :hash: Kod Nasıl Çalışır? How does the code work?

- API Anahtarı ve API URL'si:
  * OpenWeatherMap API'ye erişim sağlamak için kullanılan apiKey ve hava durumu verilerini çekmek için kullanılan apiUrl değişkenleri bulunmaktadır.

- DOM Elemanlarının Seçimi: document.querySelector :
  * fonksiyonu ile HTML içerisindeki belirli elementlere (örneğin, şehir giriş kutusu, hava durumu ikonu, vs.) erişim sağlanmaktadır.

- Hava Durumu Kontrol Fonksiyonu:
  * Kullanıcının girdiği şehir adına ait hava durumu bilgilerini çekmek için API'ye istek yapar. API'den gelen veriler kullanılarak, sayfa üzerindeki elementler güncellenir ve hava durumu durumuna göre arka plan fotoğrafı ve hava durumu ikonu dinamik olarak değiştirilir.

- Arkaplan ve Hava Durumu Görseli Değişimi:
  * API'den gelen hava durumu durumuna göre, sayfadaki arka plan fotoğrafı (bgphoto) ve hava durumu ikonu (weatherIcon) dinamik olarak değiştirilir.

- Hata Yönetimi:
  * API'den gelen yanıtlar kontrol edilir ve şehir bulunamadığında bir hata mesajı gösterilir.

---
