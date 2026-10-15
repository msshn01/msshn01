<h1 align="center">Musa Şahan</h1>

<p align="center">
  <b>Bilgisayar Mühendisliği Öğrencisi · Android Geliştirici · Gömülü Sistemler</b><br/>
  Clean Architecture ile native Android uygulamaları, internetsiz radyo ağları için düşük seviyeli gömülü yazılımlar geliştiriyorum.
</p>

<p align="center">
  <a href="https://github.com/msshn01"><img src="https://img.shields.io/badge/GitHub-msshn01-181717?style=flat-square&logo=github&logoColor=white" /></a>
  <img src="https://img.shields.io/badge/İnönü%20Üniversitesi-Bilgisayar%20Mühendisliği-0A66C2?style=flat-square" />
  <img src="https://img.shields.io/badge/Konum-Malatya%2C%20Türkiye-E30A17?style=flat-square" />
</p>

---

## Hakkımda

- 🎓 **İnönü Üniversitesi** Bilgisayar Mühendisliği 4. sınıf öğrencisiyim (beklenen mezuniyet: 2027)
- 📱 Kotlin ve Jetpack Compose ile **native Android geliştirme** üzerine odaklanıyorum
- 📡 Bitirme projesi olarak ESP32 üzerinde **merkezi olmayan bir LoRa mesh ağı** geliştiriyorum
- 🤖 Python ile **LLM entegrasyonu, RAG** ve veri işleme üzerine çalışıyorum
- 🌱 Mobil ile donanımın buluştuğu alanla ilgileniyorum: gömülü yazılım, radyo protokolleri ve bunlarla konuşan uygulamalar

---

## Öne Çıkan Projeler

### 📡 [LoRa Mesh — İnternetsiz Mesajlaşma Ağı](https://github.com/msshn01/lora_mesh)

Cihazlar arasında **internet veya baz istasyonu olmadan** mesaj taşıyan, afet ve enkaz senaryoları düşünülerek tasarlanmış merkezi olmayan bir haberleşme ağı. Her düğüm başkalarının paketlerini aktarabildiği için mesajlar ağ üzerinde atlayarak doğrudan menzil dışındaki düğümlere ulaşır.

- **Donanım:** LILYGO T3 LoRa32 (ESP32-PICO-D4, SX1278 radyo, SSD1306 OLED), 433 MHz
- **Gömülü yazılım:** **ESP-IDF** üzerinde C ile, SPI üzerinden sıfırdan yazılmış **register seviyesinde SX1278 sürücüsü**
- **Özgün mesh protokolü:** paket içinde rota takibi, "görülen paketler" listesiyle kopya engelleme, hedef kontrolü ve **ACK ile teslim onayı**
- **Saha testleri:** şehir içi menzil testlerinde RSSI/SNR ölçümü ve sıra numarasıyla paket kaybı takibi
- **Sıradaki adım:** mesh üzerinden mesaj gönderip okumak için **Kotlin ve Jetpack Compose** ile Android uygulaması

`C` `ESP-IDF` `ESP32` `LoRa` `SPI` `Gömülü Sistemler` `Ağ Protokolleri`

### 🚗 [CarLog — Araç Bakım ve Gider Asistanı](https://github.com/msshn01/CarLog)

Kullanıcının araçlarını, bakım geçmişini ve yaklaşan tarihlerini takip eden, muayene veya sigorta süresi dolmadan hatırlatma yapan bir Android uygulaması.

- **Mimari:** Clean Architecture paket yapısıyla (`data` / `domain` / `ui` / `di`) MVVM ve Repository Pattern
- **Arayüz:** tamamen **Jetpack Compose** ve Jetpack Navigation ile, animasyonlu açılış ekranı dahil
- **Kimlik doğrulama:** **Firebase Auth** ile e-posta/şifre kaydı, form doğrulama, şifre sıfırlama ve otomatik giriş
- **Garaj:** araç kartlarıyla çoklu araç desteği, aktif araç seçimi, ekleme/düzenleme/silme akışları
- **Bakım takibi:** yağ, fren, triger gibi bakım kayıtları ve **kilometre ile zamana göre kalan ömür göstergeleri**
- **Akıllı hatırlatıcılar:** muayene ve sigorta yenileme tarihleri için **WorkManager** ile zamanlanmış bildirimler
- **Yol haritası:** Room + Firestore ile offline-first senkronizasyon, grafiklerle gider analizi ve aktif aracın verilerini bağlam olarak kullanan **Gemini tabanlı yapay zekâ asistanı**

`Kotlin` `Jetpack Compose` `MVVM` `Firebase` `WorkManager` `Navigation`

---

## Teknolojiler

**Android Geliştirme**

![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)
![Jetpack Compose](https://img.shields.io/badge/Jetpack%20Compose-4285F4?style=for-the-badge&logo=jetpackcompose&logoColor=white)
![Android](https://img.shields.io/badge/Android%20SDK-3DDC84?style=for-the-badge&logo=android&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)

**Gömülü Sistemler**

![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black)
![ESP-IDF](https://img.shields.io/badge/ESP--IDF-E7352C?style=for-the-badge&logo=espressif&logoColor=white)
![ESP32](https://img.shields.io/badge/ESP32-000000?style=for-the-badge&logo=espressif&logoColor=white)
![LoRa](https://img.shields.io/badge/LoRa-1E88E5?style=for-the-badge&logoColor=white)

**Yapay Zekâ ve Veri**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)

**Backend, Veritabanları ve Araçlar**

![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)

<details>
<summary><b>Detaylı yetkinlikler</b></summary>
<br/>

| Alan | Teknolojiler |
|---|---|
| **Mimari ve Tasarım Desenleri** | Clean Architecture, MVVM, MVI, Repository Pattern, Dependency Injection (Hilt / Koin) |
| **Asenkron Programlama ve State** | Kotlin Coroutines, Flow, State Management, Jetpack kütüphaneleri |
| **Ağ** | RESTful API'ler, Retrofit, Ktor, JSON |
| **Veri Saklama** | Room, SQLite, PostgreSQL, Firebase Firestore ve Realtime Database |
| **Firebase** | Authentication, Cloud Messaging, Firestore, Realtime Database |
| **Gömülü Sistemler** | ESP-IDF, SPI, register seviyesinde radyo sürücüleri, LoRa (SX1278), OLED ekranlar |
| **Yapay Zekâ / ML** | LLM entegrasyonu, RAG, temel görüntü işleme, Pandas, NumPy |
| **Araçlar** | Android Studio, VS Code, Git / Git Flow, GitHub, Figma, Postman |

</details>

---

## GitHub İstatistikleri

<p align="center">
  <img src="https://github-readme-stats-fast.vercel.app/api?username=msshn01&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&locale=tr" height="165" />
  <img src="https://github-readme-stats-fast.vercel.app/api/top-langs/?username=msshn01&layout=compact&theme=tokyonight&hide_border=true&hide=html,css&langs_count=6&locale=tr" height="165" />
</p>

---

<p align="center">
  <i>Android geliştirme ve gömülü sistemler alanında staj fırsatlarına açığım.</i>
</p>
