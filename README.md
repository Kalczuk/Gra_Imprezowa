# 🎲 Gra Imprezowa – Towarzyska Gra Planszowa Online & Lokalnie

🚀 **Zagraj na żywo (Live Demo):** https://alkochinczyk-813fd.web.app/

---

## 📖 O projekcie

**Gra Imprezowa** (wewnętrzna nazwa kodowa: *alkochinczyk*) to webowa, interaktywna adaptacja klasycznej gry planszowej „Chińczyk”, wzbogacona o mechanikę kart wyzwań, zadań specjalnych oraz dynamicznych wydarzeń towarzyskich. Projekt został stworzony z myślą o integracji ze znajomymi – zarówno przy jednym urządzeniu, jak i na odległość przez internet.

Głównym celem technicznym projektu było zbudowanie wieloplatformowej aplikacji w technologii **Flutter Web**, zintegrowanej z bazą danych czasu rzeczywistego (**Cloud Firestore**) oraz zautomatyzowanym procesem wdrożeniowym (**CI/CD**).

---

## ✨ Główne funkcjonalności

* **📱 Tryb lokalny (Pass & Play):** Możliwość rozgrywki dla kilku graczy na jednym ekranie (telefonie lub komputerze).
* **🌐 Tryb wieloosobowy (Online Lobby):** Tworzenie prywatnych pokojów gry i dołączanie do nich za pomocą unikalnych kodów. Synchronizacja ruchów pionków, rzutów kostką i stanów gry odbywa się w czasie rzeczywistym dzięki Firebase.
* **🃏 System kart wyzwań:** Specjalne pola na planszy aktywujące losowe karty z wyzwaniami i zadaniami dla graczy, co urozmaica klasyczną mechanikę Ludo.
* **🎨 Custom UI & Animacje:** Autorski interfejs dopasowany do klimatu gier towarzyskich, płynne animacje ekranu ładowania oraz responsywne skalowanie widoków.

---

## 🛠️ Stack Technologiczny (Tech Stack)

Projekt został zrealizowany przy użyciu nowoczesnych narzędzi i bibliotek:

* **Framework:** [Flutter](https://flutter.dev/) (kompilacja do Web)
* **Język:** [Dart](https://dart.dev/)
* **Silnik gry / Komponenty:** `flame`
* **Backend & Synchronizacja (BaaS):** [Firebase](https://firebase.google.com/) (`firebase_core`, `cloud_firestore`)
* **Hosting:** Firebase Hosting
* **CI/CD:** GitHub Actions (automatyczne budowanie i publikacja po każdym `push` do gałęzi głównej)
* **Stylizacja i czcionki:** `google_fonts`, Material Design

---

## 🚧 Status projektu i znane ograniczenia (WIP / MVP)

Projekt znajduje się obecnie w fazie **MVP (Minimum Viable Product)** i służy jako poligon doświadczalny do nauki architektury Fluttera oraz integracji z usługami chmurowymi. 

**Co warto wiedzieć:**
* Gra jest w pełni grywalna od początku do końca, jednak w kodzie mogą występować drobne błędy (tzw. *edge-cases*) związane m.in. z synchronizacją stanów przy nagłym rozłączeniu gracza lub specyficznymi zachowaniami interfejsu na nietypowych rozdzielczościach.
* Projekt jest **otwarty na dalszy rozwój, optymalizację i refaktoryzację**. Jeśli przeglądasz ten kod i masz pomysł na usprawnienie logiki lub poprawę błędów – śmiało korzystaj z repozytorium, zgłaszaj *Issues* lub twórz *Pull Requesty*!

---

