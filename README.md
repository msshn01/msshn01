<h1 align="center">Musa Şahan</h1>

<p align="center">
  <b>Computer Engineering Student · Android Developer · Embedded Systems</b><br/>
  Building native Android apps with Clean Architecture, and low-level firmware for off-grid radio networks.
</p>

<p align="center">
  <a href="https://github.com/msshn01"><img src="https://img.shields.io/badge/GitHub-msshn01-181717?style=flat-square&logo=github&logoColor=white" /></a>
  <img src="https://img.shields.io/badge/İnönü%20University-Computer%20Engineering-0A66C2?style=flat-square" />
  <img src="https://img.shields.io/badge/Location-Malatya%2C%20Türkiye-E30A17?style=flat-square" />
</p>

---

## About Me

- 🎓 4th-year Computer Engineering student at **İnönü University** (expected graduation: 2027)
- 📱 Focused on **native Android development** with Kotlin & Jetpack Compose
- 📡 Currently building a **decentralized LoRa mesh network** on ESP32 as my graduation project
- 🤖 Exploring **LLM integration, RAG** and data processing with Python
- 🌱 Interested in the space where mobile meets hardware: embedded firmware, radio protocols and the apps that talk to them

---

## Featured Projects

### 📡 [LoRa Mesh — Off-Grid Messaging Network](https://github.com/msshn01/lora-mesh)

A decentralized communication network that carries messages between devices **without internet or cellular infrastructure**, designed with disaster and rubble scenarios in mind. Each node can relay packets for others, so messages hop across the network to reach nodes beyond direct radio range.

- **Hardware:** LILYGO T3 LoRa32 (ESP32-PICO-D4, SX1278 radio, SSD1306 OLED), 433 MHz
- **Firmware:** C on **ESP-IDF**, with a **register-level SX1278 driver** written from scratch over SPI
- **Custom mesh protocol:** in-packet route tracking, duplicate suppression via seen-packet lists, destination checks and **ACK-based delivery confirmation**
- **Field-tested:** RSSI/SNR measurement and sequence-number-based packet loss tracking in urban range tests
- **Next up:** an Android companion app in **Kotlin & Jetpack Compose** for sending and reading messages over the mesh

`C` `ESP-IDF` `ESP32` `LoRa` `SPI` `Embedded Systems` `Networking`

### 🚗 [CarLog — Vehicle Maintenance & Expense Assistant](https://github.com/msshn01/CarLog)

An Android app that keeps track of a driver's vehicles, maintenance history and upcoming deadlines, and reminds them before inspection or insurance dates slip by.

- **Architecture:** MVVM with a Clean Architecture package structure (`data` / `domain` / `ui` / `di`) and the Repository Pattern
- **UI:** fully built with **Jetpack Compose** and Jetpack Navigation, including an animated splash screen
- **Authentication:** **Firebase Auth** with email/password sign-up, input validation, password reset flow and auto-login
- **Garage:** multi-vehicle support with a vehicle carousel, active vehicle switching, and add/edit/delete flows
- **Maintenance tracking:** service logs (oil, brakes, timing belt, etc.) with **mileage- and time-based remaining-life indicators**
- **Smart reminders:** scheduled local notifications via **WorkManager** for inspection and insurance renewal dates
- **Roadmap:** offline-first sync with Room + Firestore, expense analytics with charts, and a **Gemini-powered AI assistant** that answers questions using the active vehicle's data as context

`Kotlin` `Jetpack Compose` `MVVM` `Firebase` `WorkManager` `Navigation`

---

## Tech Stack

**Android Development**

![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)
![Jetpack Compose](https://img.shields.io/badge/Jetpack%20Compose-4285F4?style=for-the-badge&logo=jetpackcompose&logoColor=white)
![Android](https://img.shields.io/badge/Android%20SDK-3DDC84?style=for-the-badge&logo=android&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)

**Embedded Systems**

![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black)
![ESP-IDF](https://img.shields.io/badge/ESP--IDF-E7352C?style=for-the-badge&logo=espressif&logoColor=white)
![ESP32](https://img.shields.io/badge/ESP32-000000?style=for-the-badge&logo=espressif&logoColor=white)
![LoRa](https://img.shields.io/badge/LoRa-1E88E5?style=for-the-badge&logoColor=white)

**AI & Data**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)

**Backend, Databases & Tools**

![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)

<details>
<summary><b>Detailed skills</b></summary>
<br/>

| Area | Technologies |
|---|---|
| **Architecture & Patterns** | Clean Architecture, MVVM, MVI, Repository Pattern, Dependency Injection (Hilt / Koin) |
| **Async & State** | Kotlin Coroutines, Flow, State Management, Jetpack Libraries |
| **Networking** | RESTful APIs, Retrofit, Ktor, JSON |
| **Persistence** | Room, SQLite, PostgreSQL, Firebase Firestore & Realtime Database |
| **Firebase** | Authentication, Cloud Messaging, Firestore, Realtime Database |
| **Embedded** | ESP-IDF, SPI, register-level radio drivers, LoRa (SX1278), OLED displays |
| **AI / ML** | LLM integration, RAG, computer vision basics, Pandas, NumPy |
| **Tools** | Android Studio, VS Code, Git / Git Flow, GitHub, Figma, Postman |

</details>

---

## GitHub Stats

<p align="center">
  <img src="https://github-readme-stats-fast.vercel.app/api?username=msshn01&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" height="165" />
  <img src="https://github-readme-stats-fast.vercel.app/api/top-langs/?username=msshn01&layout=compact&theme=tokyonight&hide_border=true&hide=html,css&langs_count=6" height="165" />
</p>

---

<p align="center">
  <i>Open to internship opportunities in Android development and embedded systems.</i>
</p>
