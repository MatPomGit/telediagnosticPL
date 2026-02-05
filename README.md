# TelediagnosticPL - Interaktywny moduł szkoleniowy

Witamy w interaktywnym module szkoleniowym poświęconym algorytmom uczenia maszynowego stosowanym przy diagnostyce ADHD oraz ASD.

## O czym jest ten moduł?

Ten zasób to kompletny materiał edukacyjny w formie interaktywnej prezentacji. Skupia się na pokazaniu, jak współczesne metody ML mogą wspierać proces diagnostyczny w kontekście zaburzeń neuropsychiatrycznych, szczególnie ADHD (zespół nadpobudliwości psychoruchowej z deficytem uwagi) oraz ASD (zaburzenia ze spektrum autyzmu).

## Do kogo skierowany jest materiał?

Moduł został przygotowany z myślą o osobach, które chcą poznać praktyczne zastosowania algorytmów ML w kontekście medycznym - zarówno studentach, jak i praktykach szukających wprowadzenia do tematu telediagnostyki.

## Uruchomienie modułu

Pobierz całość repozytorium i otwórz `index.html` w dowolnej współczesnej przeglądarce (najlepiej Chrome lub Firefox). Możesz to zrobić poprzez:

- Bezpośrednie otwarcie pliku przez przeglądarkę
- Serwer lokalny (np. `python -m http.server` dla Pythona lub `npx http-server` dla Node.js)

Po uruchomieniu zobaczysz interaktywny interfejs Rise Player, który poprowadzi Cię przez całość materiału.

## Co znajdziesz w środku?

Zawartość modułu obejmuje prezentację złożoną z wielu slajdów i elementów interaktywnych, skompresowanych przy użyciu algorytmu LZW. Player automatycznie dekompresuje treść przy pierwszym uruchomieniu.

Główne komponenty aplikacji:
- `index.html` - punkt wejścia z całą prezentacją
- `goodbye.html` - ekran końcowy po zamknięciu
- `lib/` - zestaw bibliotek JavaScript obsługujących player i kompresję
- `assets/` - obrazy wykorzystane w prezentacji

## Wymagania techniczne

Wystarczy współczesna przeglądarka z włączonym JavaScript. Moduł automatycznie dostosowuje się do rozdzielczości ekranu.

## Informacje dodatkowe

Materiał opracowany przez MatPomGit jako narzędzie wspierające edukację w obszarze zastosowań AI w medycynie diagnostycznej.
