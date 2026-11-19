# Szablon wyglądu – wzorowany na instrukcji obsługi Fiat Stilo (tylko układ graficzny)

Źródło wzoru: `../Instrukcja STILO.pdf`. Z pliku wzięto **wyłącznie wygląd**, bez żadnych treści.

## Format strony
- **A5 poziomo** (210 × 148 mm; w PDF 595 × 419 pt).
- Druk czarno-biały z odcieniami szarości. Kolor występuje tylko na okładce.
- Duże marginesy i dużo białej przestrzeni.

## Okładka
- Pełnoformatowe zdjęcie pojazdu lub detalu, np. zbliżenie logo.
- W prawym górnym rogu **pełny prostokąt w kolorze firmowym** (granat), przylegający do górnej krawędzi:
  - nazwa pojazdu: duże wersaliki, pogrubione, białe;
  - niżej mniejszy podtytuł „INSTRUKCJA OBSŁUGI”: wersaliki, kolor akcentu (pomarańczowy).

## Zakładki rozdziałów (najbardziej charakterystyczny element)
- Pionowy pasek zakładek wzdłuż **zewnętrznej krawędzi strony**: na stronach parzystych po lewej, na nieparzystych po prawej.
- 8 zakładek jedna pod drugą: zaokrąglone prostokąty z szarą obwódką i tekstem obróconym o 90°. Tekst ma 2–3 linie, małe pogrubione wersaliki.
- **Zakładka bieżącego rozdziału jest czarna z białym tekstem.** Pozostałe są białe z szarym tekstem.
- Numer strony: duży, pogrubiony, pod paskiem zakładek, w zewnętrznym dolnym rogu.

## Strona tytułowa rozdziału
- Tytuł rozdziału wyśrodkowany u góry: **litery konturowe (puste w środku, z cieniem), wersaliki, szeroki rozstaw liter**.
- Pod nim spis podrozdziałów z kropkowanymi wypełniaczami do numeru strony:
  - w 1 lub 2 kolumnach, wersaliki, zwykła grubość;
  - w krótkim rozdziale spis zajmuje prawą połowę strony.

## Strony treści
- **Układ 3-kolumnowy.** Ilustracje mogą zajmować 2 kolumny.
- Font: **bezszeryfowy, wąski (condensed)**, np. Frutiger Condensed, Myriad Condensed lub Roboto Condensed. Tekst wyrównany do lewej albo justowany, ok. 9–10 pt.
- Hierarchia nagłówków:
  - H1 (temat strony): duże pogrubione wersaliki, czarne, np. „KLUCZYKI”;
  - H2: małe pogrubione wersaliki, np. „CODE CARD”;
  - H3: pogrubiony tekst zdaniowy, np. „Zaświecenie się lampki … podczas jazdy:”.
- Wyróżnienia w tekście: **pogrubienie** dla nazw położeń i przycisków, np. **STOP**, **MAR**, **rys. 6**.
- Listy: zamiast kropek **puste kwadraciki ❒**. Podpunkty zaczynają się od myślnika „–”.

## Ramki ostrzeżeń (2 rodzaje)
1. **Ramka „UWAGA”** (zagrożenie): szare tło, po lewej duża ikona trójkąta z wykrzyknikiem, u góry **ciemny pasek z napisem UWAGA** (biała kursywa, wersaliki). Treść pogrubiona kursywą.
2. **Ramka „Wskazówka/Informacja”**: szare tło, po lewej trójkąt z piktogramem tematu (np. samochód, ręka), bez paska. Treść pogrubiona kursywą.
- Ramki stoją w kolumnach. Tekst opływa ikonę.

## Ilustracje
- Rysunek kreskowy albo zdjęcie w **cienkiej czarnej ramce**.
- Pod ramką: po lewej podpis „rys. 12”, po prawej mały kod rysunku, np. „F0C0510m”.
- Elementy na rysunku oznaczone **literami w czarnych kółkach** (A, B, C) z cienkimi liniami odnośnymi. W tekście pojawiają się jako „**A-rys. 58**”.
- Ikony lampek i symboli: piktogram w okręgu po lewej, obok pogrubiony nagłówek w wersalikach i opis.

## Tabele
- Proste tabele z poziomymi liniami i pogrubionym wierszem nagłówka, np. tabela bezpieczników: Odbiornik | Bezpiecznik | Amper | Rys.

## Struktura rozdziałów wzoru (8 zakładek)
Deska rozdzielcza i sterowanie · Bezpieczeństwo · Uruchamianie silnika i jazda · Lampki sygnalizacyjne i komunikaty · W razie awarii · Obsługa samochodu · Dane techniczne · Spis alfabetyczny

---

## Propozycja zakładek dla instrukcji uproszczonej 805Na
1. **STANOWISKO MOTORNICZEGO** (pulpit, nastawnik, pedały, czuwak)
2. **BEZPIECZEŃSTWO** (napięcia, odłącznik, pantograf, pożar)
3. **PRZYGOTOWANIE I JAZDA** (uruchomienie wagonu, rozruch, hamowanie, ukrotnienie)
4. **SYGNALIZACJA I KONTROLKI**
5. **W RAZIE AWARII** (procedury usterek)
6. **APARATURA – GDZIE CO JEST** (tablice, skrzynie, bezpieczniki)
7. **DANE TECHNICZNE**
8. **SKOROWIDZ**

## Realizacja techniczna (propozycja)
- Skład w HTML + CSS (`@page` A5 landscape, CSS grid na 3 kolumny), eksport do PDF przez Chromium lub WeasyPrint.
- Treść w Markdown/JSON, wspólnym z przyszłą aplikacją Android: jedno źródło danych, dwa sposoby wyświetlania.
- Font: Roboto Condensed lub Barlow Condensed (licencja otwarta).
- Kolorystyka okładki: zamiast granat/pomarańcz Fiata na przykład barwy MPK Łódź. Do ustalenia.
