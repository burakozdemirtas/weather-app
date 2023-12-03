<div align="center">
<img src="https://github.com/burakozdemirtas/weather-app/assets/33163650/a2e9740f-e3e4-49d6-aa23-d6efd0a287c5" width="160" height="160">
</div>



<h1 align="center"> Weather App </h1>
<p align="justify">
Bu proje, OpenWeatherMap API ve temel HTML ve JavaScript kodları kullanılarak gerçek zamanlı hava durumu bilgilerini gösteren bir web uygulaması örneğini içermektedir. Kullanıcı şehir adını girdiğinde, uygulama bu şehre ait hava durumu verilerini API üzerinden çeker ve kullanıcıya sıcaklık, nem, rüzgar hızı gibi bilgileri sunar. Ayrıca, hava durumu durumuna göre arka plan fotoğrafını ve hava durumu ikonunu dinamik olarak değiştirerek kullanıcıya görsel bir deneyim sunar.
</p>
<p align="justify">
This project includes a web application example that displays real-time weather information using the OpenWeatherMap API and basic HTML and JavaScript codes. When the user enters the city name, the application pulls the weather data for this city through the API and provides the user with information such as temperature, humidity and wind speed. Additionally, it provides a visual experience to the user by dynamically changing the background photo and weather icon according to the weather condition.
</p>

*  [:fire: Geliştirici / Developer](#fire-geliştirici-developer)
*  [:hash: Kod Nasıl Çalışır?/How does the code work?](#hash-kod-nasıl-çalışır-how-does-the-code-work)
*  [:hash: Projeden Görseller/ Images from the Project](#hash-projeden-görseller-images-from-the-project)

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

- API Key and API URL:
   * There are apiKey variables used to access the OpenWeatherMap API and apiUrl variables used to retrieve weather data.

- Selection of DOM Elements: document.querySelector:
   The * function provides access to certain elements in HTML (for example, city input box, weather icon, etc.).

- Weather Control Function:
   * Makes a request to the API to retrieve weather information for the city name entered by the user. Using data from the API, the elements on the page are updated and the background photo and weather icon are dynamically changed according to the weather condition.

- Background and Weather Image Change:
   * According to the weather condition coming from the API, the background photo (bgphoto) and weather icon (weatherIcon) on the page are changed dynamically.

- Error Management:
   * Responses from the API are checked and an error message is shown if the city is not found.
# :hash: Projeden Görseller/ Images from the Project
![Ekran görüntüsü 2023-12-03 203421](https://github.com/burakozdemirtas/weather-app/assets/33163650/3a65f61e-9c5e-4ea0-913f-7d6146401645)

![Ekran görüntüsü 2023-12-03 203408](https://github.com/burakozdemirtas/weather-app/assets/33163650/410d6e21-c757-478b-bf50-2888ada2b913)
![Ekran görüntüsü 2023-12-03 203312](https://github.com/burakozdemirtas/weather-app/assets/33163650/050e6d63-163f-4d35-9219-ed7f7183c362)
![Ekran görüntüsü 2023-12-03 202620](https://github.com/burakozdemirtas/weather-app/assets/33163650/be89bf3c-f6e8-4bfb-b94d-88590f87bda7)
![Ekran görüntüsü 2023-12-03 202550](https://github.com/burakozdemirtas/weather-app/assets/33163650/3ba3d9e9-b046-4eff-a253-e5e6017c0dcb)
