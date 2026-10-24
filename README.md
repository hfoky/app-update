# HFOKY APP

<p align="center">
  <img src="https://img.shields.io/badge/Android-8.0%2B-green.svg?style=for-the-badge&logo=android" alt="Android" />
  <img src="https://img.shields.io/badge/Kotlin-2.2-blue.svg?style=for-the-badge&logo=kotlin" alt="Kotlin" />
  <img src="https://img.shields.io/badge/Jetpack%20Compose-Material%203-purple.svg?style=for-the-badge&logo=jetpackcompose" alt="Compose" />
  <img src="https://img.shields.io/badge/Architecture-MVVM-orange.svg?style=for-the-badge" alt="MVVM" />

---

## O APLIKACJI

Phone Flip Manager to nowoczesna, wysoce zaawansowana i intuicyjna aplikacja mobilna stworzona dla handlarzy i pasjonatów flipowania telefonów. Pozwala śledzić zakupy, koszty naprawy, wysyłki, zyski netto oraz generować interaktywne listy usterek i testy sprawności urządzeń.

---

## GŁÓWNE FUNKCJE

### 1. Śledzenie Finansów i Flipów
* **Baza danych SQLite (Room)**: Pamięć urządzeń, stan baterii, koszty zakupu, wysyłki i napraw.
* **Kalkulator Zysku Netto**: Wyliczanie faktycznego zarobku i zamrożonego kapitału w czasie rzeczywistym.
* **Statusy Flipów**: W trakcie handlu, Sprzedany, Odwołany przez sprzedającego / kupującego.

### 2. Interaktywny Test Sprawności (Checklist)
* Dedykowane okno dialogowe z checklistą podzespołów (Ekran, Dotyk, Bateria, Aparat, Ładowanie, FaceID / Fingerprint, Wi-Fi, Zasięg, Głośniki, Mikrofon, Obudowa, Przyciski).
* Błyskawiczny podgląd uszkodzeń w postaci chipów ostrzegawczych na karcie telefonu.

### 3. Personalizacja i Styl Liquid Glass
* **Własny HEX Picker + Suwaki RGB**: Ręczny dobór koloru z podglądem na żywo.
* **Tryby Wyglądu**: Jasny, Ciemny, Systemowy oraz głęboki AMOLED Black.
* **Pływający pasek z płynnym podświetleniem**: Płynny slajd stron 120Hz i efekt półprzezroczystego szkła (Liquid Glass).

### 4. Wielojęzyczność (Multi-language)
* Pełna obsługa języka Polskiego oraz Angielskiego z natychmiastowym przełączaniem w czasie rzeczywistym.

### 5. Kopia Zapasowa i Automatyczne Aktualizacje OTA
* **Eksport i Import Bazy**: Wysyłanie pełnej bazy danych SQLite jednym kliknięciem przez WhatsApp, Messenger lub Dysk Google.
* **Wbudowane Aktualizacje z GitHuba**: Aplikacja automatycznie sprawdza nowe wydania `.apk` w repozytorium GitHub (`bodek5/app-update`), umożliwiając pobranie i instalację 1-kliknięciem.

---

## TECHNOLOGIA

* **Language**: [Kotlin](https://kotlinlang.org/)
* **UI Framework**: [Jetpack Compose (Material 3)](https://developer.android.com/jetpack/compose)
* **Database**: [Room SQLite Database](https://developer.android.com/training/data-storage/room)
* **Architecture**: MVVM (Model-View-ViewModel) + StateFlow & Coroutines
* **Storage & File Sharing**: Android `FileProvider` & `SharedPreferences`
* **Min SDK**: API 26 (Android 8.0+) | **Target SDK**: API 35/37 (Android 15+)

---

## INSTALACJA

1. Pobierz najnowszy plik **app-release.apk** z zakładki [Releases](https://github.com/bodek5/app-update/releases/latest).
2. Otwórz pobrany plik na swoim telefonie Android.
3. Zezwól na instalację z nieznanych źródeł i zainstaluj aplikację.

---

## AUTOR

Stworzone przez **hfoky**  
Developed with assistance from **Google Gemini AI Agent**  
*hfoky app &copy; 2026. All rights reserved.*
