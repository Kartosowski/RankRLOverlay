# RankRLOverlay

<img width="372" height="221" alt="image" src="https://github.com/user-attachments/assets/b2b69b9d-bbf6-4798-89e5-6a4bc8a132a3" />

![License](https://img.shields.io/badge/License-MIT-blueviolet?style=for-the-badge)
![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)

> Lekki overlay do Rocket League na stream. Pokazuje Twoją rangę i MMR w OBSie.

### Funkcje
* **Auto-update** – Staty odświeżają się same co 5 minut.
* **Wspierane Tryby** - 1s, 2s i 3s (Tymczasowo).
* **Lekkość** – Napisane w Go, nie obciąża procesora.
* **Design** – Czysty wygląd, przezroczystość i efekt blur.

### Szybki start (Dla użytkowników)
1. Wejdź w zakładkę **[Releases](https://github.com/Kartosowski/RankRLOverlay/releases)**.
2. Pobierz najnowszą wersję (plik `.zip`).
3. Rozpakuj i odpal `RankRLOverlay.exe`.

### 📺 Konfiguracja w OBS
Dodaj **Źródło przeglądarki (Browser Source)** i wpisz URL (zmień `NICK` na swój z Epic):
* **1v1:** `http://localhost:8080/1s/NICK`
* **2v2:** `http://localhost:8080/2s/NICK`
* **3v3:** `http://localhost:8080/3s/NICK`

> Support: https://discord.gg/xRJvJCzhWp
