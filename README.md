# Aplikacja Klubu Nocnego - README

## Opis projektu
Aplikacja mobilna klubu nocnego została zaprojektowana z myślą o społecznościowym doświadczeniu użytkowników. Główne funkcje aplikacji to:
- Informacje o wydarzeniach organizowanych w klubie.
- Możliwość dołączenia do społeczności klubowiczów.
- Multijęzyczne wsparcie dla użytkowników.
- Panel administracyjny umożliwiający zarządzanie wydarzeniami.
- Dodatkowe opcje, takie jak mapa i kontakt z klubem.

## Funkcjonalności
- **Strona główna**: Przycisk "Informacje", "Mapa" oraz "Kontakt".
- **Strona z informacjami**: Szczegóły dotyczące wydarzeń, takie jak data, godzina i opis.
- **Panel administracyjny**: Zarządzanie wydarzeniami poprzez aplikację.

## Technologia
Aplikacja została napisana w Flutterze (język Dart), co umożliwia jej uruchomienie zarówno na Androidzie, jak i iOS.

### Wersje użytych technologii
- **Flutter**: 3.10.0
- **Dart**: 3.0.5

## Struktura katalogów
Proponowana struktura katalogów w repozytorium:
```
project-root/
├── lib/                # Kod źródłowy aplikacji
│   ├── main.dart       # Główny plik aplikacji
│   ├── pages/          # Ekrany aplikacji
│   │   ├── home.dart   # Strona główna
│   │   ├── info.dart   # Strona z informacjami
│   │   ├── contact.dart # Strona kontaktowa
│   ├── widgets/        # Komponenty wielokrotnego użytku
├── assets/             # Zasoby (np. obrazy, ikony)
├── documentation/      # Dokumentacja projektu
│   ├── report.pdf      # Raport projektu w formacie PDF
├── test/               # Testy jednostkowe aplikacji
├── pubspec.yaml        # Plik konfiguracji projektu Flutter
└── README.md           # Dokumentacja repozytorium
```
## Dokumentacja
- [Raport PDF](raport_z_projektu.pdf)
- [Prezentacja PDF](prezentacja_tfr.pdf)


## Instrukcja uruchomienia
1. Sklonuj repozytorium na swój komputer:
   ```bash
   git clone <URL_REPOZYTORIUM>
   ```
2. Przejdź do katalogu projektu:
   ```bash
   cd project-root
   ```
3. Zainstaluj zależności:
   ```bash
   flutter pub get
   ```
4. Uruchom aplikację w trybie debugowania:
   ```bash
   flutter run
   ```

## Autor
Imię i nazwisko: Jakub Grzyb 
Numer indeksu: 49482  

## Licencja
Projekt udostępniany na licencji MIT. Szczegóły znajdują się w pliku LICENSE.
