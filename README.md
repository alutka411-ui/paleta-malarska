# Paleta Malarza

Aplikacja internetowa do analizy kolorów i planowania palet malarskich. Przygotowana również jako PWA (można ją zainstalować z poziomu obsługiwanej przeglądarki).

## Publikacja na GitHub Pages

1. Rozpakuj paczkę ZIP.
2. Wgraj **wszystkie pliki** z tego folderu do głównego katalogu repozytorium GitHub (razem z `index.html`, ikonami, `manifest.webmanifest`, `sw.js` i `.nojekyll`).
3. Zatwierdź zmiany przyciskiem **Commit changes**.
4. Otwórz **Settings → Pages**.
5. Wybierz **Deploy from a branch**, gałąź `main` i katalog `/(root)`, po czym kliknij **Save**.
6. Otwórz opublikowany adres `https://...github.io/...` i poczekaj, aż strona się załaduje.

## Instalacja jako aplikacja

- **Android / Chrome:** otwórz opublikowaną stronę, wybierz menu ⋮ i opcję „Zainstaluj aplikację” albo „Dodaj do ekranu głównego”.
- **iPhone / iPad:** otwórz stronę w Safari, wybierz Udostępnij, a następnie „Dodaj do ekranu początkowego”.
- **Komputer / Chrome lub Edge:** otwórz stronę i poszukaj ikony instalacji przy pasku adresu albo wybierz menu przeglądarki → „Zainstaluj Paleta Malarza”.

Jeśli opcja instalacji nie pojawia się od razu, sprawdź, czy strona działa pod adresem HTTPS, wszystkie pliki zostały wgrane i odśwież stronę. Po aktualizacji service workera czasem pomaga zamknięcie i ponowne otwarcie strony.

## Ważne

- Nie jest to plik APK ani instalator Windows. Instalacja odbywa się przez przeglądarkę jako PWA.
- Aplikacja działa pod HTTPS (GitHub Pages zapewnia HTTPS).
- Service worker buforuje podstawowe pliki aplikacji do użycia offline.
- Nie usuwaj `manifest.webmanifest`, `sw.js` ani plików ikon — są potrzebne do instalacji i wyświetlania ikony.
