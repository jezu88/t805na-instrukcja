# Tramwaj Konstal 805Na – uproszczona instrukcja i postępowanie przy usterkach

> **Wersja robocza 0.3** – opracowana na podstawie maszynopisu MPK Łódź „opis aparatury elektrycznej wagonu 805Na”, **część I kompletna: rozdz. 1–24 (s. 1–151)**.
> Do uzupełnienia pozostaje jedynie **część II opracowania** (współpraca obwodów, schematy, programy łączeń) – jeśli jest dostępna osobno.
> Dokument jest pomocą szkoleniową. **Obowiązujące są przepisy i instrukcje przewoźnika oraz polecenia dyspozytora.**

---

## 1. Jak działa wagon – w pigułce

| Element | Co robi | Gdzie jest |
|---|---|---|
| **Pantograf OTK-1** | Zbiera prąd z sieci 600 V (w praktyce 400–720 V) | Dach |
| **Odgromnik** | Chroni przed piorunami i przepięciami | Dach, przy pantografie |
| **Odłącznik liniowy OLT-198** | Ręcznie odcina obwód główny od sieci (widoczna przerwa) | Drewniana skrzynka z uchylną pokrywą |
| **Stycznik liniowy SUT-300** | Włącza i wyłącza obwód główny; **sam wybija przy przeciążeniu lub zwarciu (600 A)** | Podwozie |
| **4 silniki LTa-220** | Napęd i hamowanie elektrodynamiczne (2 grupy po 2 silniki) | Wózki |
| **Rozrusznik GBT-373** | Bęben z 99 pozycjami; płynnie zmienia rezystancję przy rozruchu i hamowaniu | Skrzynia rozrusznika |
| **Silnik rozrusznika PZSOb12a** | Obraca bęben rozrusznika (32 V) | Skrzynia aparatowa |
| **Przekaźnik samoczynnego rozruchu PST-257a (PSR)** | Pilnuje prądu rozruchu i hamowania zależnie od wciśnięcia pedału | Pomost przedni |
| **Rezystory wstępne AZT-151 (RR1–RR3)** | Ograniczają prąd przy ruszaniu | Skrzynia rozrusznika |
| **Bocznik indukcyjny** | Osłabia wzbudzenie silników przy wyższych prędkościach (2 stopnie) | – |

### Sterowanie (rozrząd pośredni, automatyczny)
- **Pedał jazdy**: im głębiej, tym większy prąd silników → szybszy rozruch (rozruch ok. 110–230 A na silnik).
- **Pedał hamowania**: hamowanie elektrodynamiczne (silniki pracują jak prądnice), prąd ok. 65–180 A.
- **Drążek kierunku na nastawniku**: zmienia kierunek jazdy.
- **Czuwak (pedał)**: **puszczenie czuwaka = hamowanie nagłe**: hamulce szynowe + II stopień hamulców szczękowych + hamowanie elektrodynamiczne.
- Rozruch: silniki najpierw **szeregowo**, a przy ok. 200 V na rozruszniku przekaźnik PUR przełącza grupy na **równoległe** (styczniki SG). To oszczędza ok. 6% energii.
- Ruch bębna rozrusznika: pozycje 1→99 trwają ok. 3 s, a 99→30 i 30→1 po ok. 2 s.

### Hamulce – cztery rodzaje
1. **Elektrodynamiczny**: hamulec podstawowy, działa przez silniki.
2. **Szczękowy, I stopień** (słabszy): 4 hamulce (po jednym na oś), bęben na wale silnika. Luzownik (solenoid typu HT-3) trzyma szczęki **odhamowane dopóki jest zasilany**. I stopień = zasilanie solenoidów **obniżonym napięciem przez rezystor** → częściowy docisk; rozrusznik dołącza go sam przy małych prędkościach, gdy hamowanie ED słabnie.
3. **Szczękowy, II stopień (pełna siła)**: **zanik napięcia na solenoidach luzowników** → sprężyna główna dociska szczęki pełną siłą. Działa **samoczynnie przy zaniku napięcia sterowania** albo po puszczeniu czuwaka (razem z szynowymi). *Dlatego awaria zasilania NN = wagon sam hamuje i stoi.*
4. **Szynowe HS-3 (elektromagnetyczne)**: 4 szt. (po 2 na wózek), elektromagnes przyciągany do szyny, **siła 42 kN niezależna od obciążenia i przyczepności**. Hamowanie nagłe i czuwak. Odhamowanie ręczne luzowników (gdy brak prądu) – dźwigienki w położenie poziome (np. przy holowaniu).

### Pulpit motorniczego
- **Pedały (od prawej, typowo):** jazdy, hamowania, czuwak. **Drążek nastawnika kierunku**: przód / 0 / tył. Blokada: kierunek przestawisz tylko przy pedałach w „0”; pedał wciśniesz tylko przy kierunku dokładnie „przód”/„tył”.
- **Łącznik jazdy ŻR = stacyjka** (uruchomienie kluczykiem). Pozostałe łączniki: ogrzewanie tramwaju ŻOT, ogrzewanie stanowiska ŻOM i szyb ŻOS, oświetlenie wewnętrzne ŁLW / tablic ŁLJ / stanowiska ŁLM, oświetlenie zewnętrzne ŁLZ (0/pozycyjne/+reflektor+stopnie), reflektor ŁRDK (mijania/drogowe), wycieraczka ŻWS (0/I/II), kierunkowskazy, światła awaryjne, łącznik drzwi, łącznik przetwornicy.
- **Dwie wersje pulpitu:** starszy 805Ng/p1 i nowszy **805Na/P3** (inne rozmieszczenie, dwie lampki kierunkowskazów, lampka LSJ1).

### Lampki sygnalizacyjne – co znaczą
| Lampka | Stan normalny | Zaświecenie / zgaśnięcie oznacza |
|---|---|---|
| **ŻSM1** (przetwornica) | **nie świeci** | świeci = brak pracy lub awaria silnika przetwornicy |
| **LSP1** (napięcie 40 V / poślizg) | nie świeci | miga = poślizg kół; świeci ciągle = zanik napięcia prądnicy, przepalenie bezp. B8/B15/B16 lub awaria przetwornicy (ładowanie akumulatorów) |
| **LSS1** (rezerwa hamulców szynowych) | świeci (przód/tył) | zgaśnięcie = niesprawny rezerwowy obwód hamulców szynowych (bezp. B19 / PLSS / ŁLSS) |
| **LS21** (luzowniki szczękowe) | nie świeci | świeci = którykolwiek hamulec szczękowy zahamowany; gaśnie gdy wszystkie odhamowane |
| **LSD1** (drzwi) | świeci | gaśnie gdy choć jedne drzwi otwarte |
| **LSJ** (jazda) | świeci | gaśnie przy zakłóceniu rozruchu/hamowania w którymś wagonie (np. zanik prądu w obwodzie głównym) |
| **LSJ1** (tylko 805Na/P3) | nie świeci | świeci = niesprawny wagon (odwrotnie do LSJ) |
| **LSK** (kierunkowskazy) | pulsuje przy włączeniu | – |

---

## 2. Najważniejsze zasady bezpieczeństwa

1. **Odłącznik liniowy OLT-198 przełączaj tylko bez prądu.** Najpierw zdejmij nogę z pedałów i odczekaj, aż wyłączy się stycznik liniowy. Odłącznik nie jest wyłącznikiem pod obciążeniem.
2. Otwarty odłącznik daje **widoczną przerwę izolacyjną**. Zanim ktoś zacznie pracę przy obwodzie głównym, potrzebny jest **odłącznik otwarty i opuszczony pantograf**.
3. **Pantograf opuszcza się linką z kabiny.** Linkę blokuje zamek linki pantografu.
4. Napięcia w wagonie:
   - obwód główny: **600 V DC** (do 720 V), izolacja 800 V;
   - sterowanie: **24–40 V DC**;
   - silnik rozrusznika: 32 V;
   - przekaźniki drzwi: 36 V.
5. Odgromnik na dachu po uderzeniu pioruna może być uszkodzony. Zgłoś każde wyładowanie w pobliżu wagonu.

---

## 3. Postępowanie przy usterkach

> Kolejność ogólna: **1) zatrzymaj bezpiecznie → 2) zabezpiecz wagon (hamulec, światła awaryjne) → 3) powiadom dyspozytora → 4) proste czynności sprawdzające → 5) zjazd / wezwanie pogotowia technicznego.**
> Procedury poniżej wynikają z opisu działania aparatów. **Porównaj je z instrukcją dla motorniczego obowiązującą u przewoźnika.**

### 3.1 Wagon nagle traci napęd, a stycznik liniowy „wybił”
**Prawdopodobna przyczyna:** zadziałał przekaźnik nadmiarowo-prądowy PGA-115 w styczniku SUT-300. Prąd przekroczył ok. 600 A (przeciążenie lub zwarcie w obwodzie głównym).
**Co wiadomo z dokumentacji:** stycznik po zadziałaniu **trzyma się w pozycji wyłączonej** (cewka trzymająca). **Ponowne załączenie jest możliwe dopiero po przerwaniu zasilania cewki trzymającej i ponownym zasileniu cewki napędowej.** W praktyce oznacza to reset przez zdjęcie i ponowne podanie sterowania.
**Postępowanie:**
1. Zdejmij nogę z pedału jazdy. Drążek kierunku ustaw w położeniu zerowym.
2. **Reset stycznika liniowego = przerwanie i ponowne podanie napięcia sterowania.** W praktyce: wyłącz i ponownie załącz **łącznik jazdy ŻR (kluczyk/stacyjka)**, co odcina cewkę trzymającą. Dopiero wtedy stycznik da się ponownie załączyć. (Dokładną procedurę resetu potwierdź z instrukcją przewoźnika.)
3. Ruszaj łagodnie. **Jeśli stycznik wybija ponownie, nie próbuj dalej.** Może to być zwarcie w obwodzie głównym. Zgłoś usterkę i wezwij pogotowie techniczne.
4. Swąd spalenizny, dym lub iskrzenie: postępuj jak w 3.6.

### 3.2 Wagon rusza szarpiąc, za wolno lub nie przyspiesza mimo wciśniętego pedału
**Możliwe przyczyny:** rozregulowany przekaźnik samoczynnego rozruchu PSR (PST-257a), usterka silnika rozrusznika lub jego sprzęgła ciernego, usterka styczników grup SG lub przekaźnika PUR (przełączanie szereg→równoległe), niskie napięcie w sieci (poniżej ok. 400 V).
**Postępowanie:** sprawdź, czy inne tramwaje jadą normalnie (napięcie sieci). Jeśli objaw się powtarza, zgłoś usterkę rozruchu. Regulacja PSR to praca warsztatowa (zasilacze 0–300 A).

### 3.3 Słabe hamowanie elektrodynamiczne
**Możliwe przyczyny:** usterka rozrusznika lub PSR, przerwa w obwodzie silników.
**Co wiadomo:** przy małych prędkościach wagon i tak dołącza **I stopień hamulców szczękowych**. Przy zaniku napięcia sterowania zadziała **II stopień** samoczynnie.
**Postępowanie:** zachowaj większy odstęp i jedź z mniejszą prędkością. W razie potrzeby użyj hamulca szynowego lub czuwaka. Zgłoś usterkę i kontynuuj jazdę tylko za zgodą dyspozytora.

### 3.4 Wagon samoczynnie hamuje mocno (II stopień) i nie da się ruszyć
**Prawdopodobna przyczyna:** **zanik napięcia sterowania 40/24 V** aparatów rozrządu → luzowniki tracą zasilanie i sprężyna dociska szczęki pełną siłą (II stopień). Źródła NN: bateria akumulatorów (5×5 6G100H, 25 ogniw, 100 Ah), przetwornica PTA-44 (40 V), przekształtnik 40/24 V, bezpieczniki/wyłączniki.
**Co sprawdzić:**
1. **Lampka ŻSM1** (przetwornica) świeci? → przetwornica nie pracuje. **Lampka LSP1** świeci ciągle? → zanik napięcia 40 V / brak ładowania.
2. Odłącznik akumulatorów **ODAk (ON-2)** na tablicy **TBN** – czy załączony.
3. Bezpieczniki niskiego napięcia na **TBN** (szafa aparatowa): 12 bezpieczników topikowych; w nowszych wagonach wyłączniki instalacyjne S-161 – sprawdź, czy któryś nie wypadł. Bezp. B8/B15/B16 dotyczą obwodu 40 V/ładowania.
4. Przekształtnik 40/24 V po zwarciu **blokuje się** – wymaga **wyłączenia i ponownego załączenia zasilania** (reset jak w 3.1).
5. Jeśli napięcie NN nie wraca – zgłoś usterkę, wagon do zjazdu / holowania (drzwi i hamulce odhamuj ręcznie – patrz 3.5 i rozdz. hamulce).

### 3.5 Usterka drzwi
**Co wiadomo:** 4 pary drzwi, każda ma własną **maszynę drzwiową** (silnik DC 32 V typ PASOřc12, przekładnia ślimakowa, krzywki CUM). Zasilanie **z przetwornicy (40 V)**. Przekaźniki drzwi PD1–PD4 na tablicach **TDPm nad drzwiami** (PSF-534, 36 V).
**Postępowanie:**
1. **Drzwi nie działają elektrycznie przy zaniku napięcia sieci / wyłączonej przetwornicy** – to normalne, bo maszyna drzwiowa jest zasilana z przetwornicy. **Drzwi otwiera się wtedy ręcznie** (mechanizm ręcznego otwierania przy drzwiach).
2. Pojedyncze drzwi nie zamykają się → **lampka LSD1 nie zaświeci** (sygnalizuje „wszystkie zamknięte”); rozruch bywa zablokowany przy otwartych drzwiach (blokada rozruchu).
3. Zgłoś usterkę; sprawdzenie przekaźnika PD/PSF-534 i tablicy TDPm to czynność warsztatowa.

### 3.6 Dym, swąd, iskrzenie, pożar
1. Zatrzymaj wagon, **opuść pantograf** (linka w kabinie).
2. Ewakuuj pasażerów, powiadom dyspozytora i straż pożarną.
3. Gaś tylko gaśnicą przeznaczoną do urządzeń elektrycznych i tylko po opuszczeniu pantografu.

### 3.7 Pantograf nie dociska, iskrzy lub stracił kontakt z siecią
**Dane:** docisk statyczny 69 ± 7 N. Robocza wysokość ślizgacza 1200–2300 mm nad podstawą. Ślizgi mają wkładki węglowe (grafitowe).
**Postępowanie:** jedź ostrożnie bez gwałtownego poboru prądu. Zgłoś usterkę, bo zużyte wkładki lub złamany ślizgacz grożą zerwaniem sieci. Przy uszkodzeniu mechanicznym opuść pantograf i zatrzymaj się.

### 3.8 Silniki: zapach przegrzania, zadziałanie zabezpieczeń po długim podjeździe
**Dane:** praca ciągła 150 A na silnik, praca godzinna 157 A, maks. chwilowo 314 A przez 30 s. Chłodzenie wymuszone (wentylator).
**Postępowanie:** zgłoś usterkę. Sprawdź, czy słychać wentylatory chłodzenia. ⚠️ Szczegóły w rozdz. 2 części II.

### 3.9 Dzwonek zewnętrzny dzwoni sam / brak oświetlenia lub ogrzewania
**Dzwonek zewnętrzny (HD3500-06):** poza sygnałem ostrzegawczym służy też do **sygnalizacji zaniku napięcia zasilania awaryjnego hamulców szynowych**. Jeśli dzwoni samoczynnie – sprawdź zasilanie NN (jak w 3.4) i zgłoś usterkę układu awaryjnego hamulców.
**Oświetlenie:** wewnętrzne = świetlówki 40 V przez stateczniki PT-3 (starsze w oprawach OK-20p) + żarówki; stopni drzwi – żarówki sterowane krzywką drzwi. Zewnętrzne: reflektory typ 136 (BA20d 45/40 W), lampy 620/621. Pojedyncza niesprawna oprawa/statecznik → wymiana warsztatowa; sprawdź bezpieczniki oświetlenia.
**Ogrzewanie:** nawiewne (ciepło z rezystorów rozrusznika, sterowane klapą) + grzejniki z sieci 600 V (pasażerów 10GKa 700 W, kabiny OT-100 600 W, szyb OS-00100 250 W). Brak ogrzewania → sprawdź łączniki ŻOT/ŻOM/ŻOS i bezpieczniki WN; grzejniki na 600 V – usterka to zgłoszenie warsztatowe.

---

## 4. Ściąga – gdzie co jest (wg rozdz. 14 – tablice aparatowe)

**Szafa aparatowa (tablice):** TBN (bezpieczniki NN + odłącznik akumulatorów ODAk), TBW (bezpieczniki WN / wyłączniki S-161), TŁS (przełączniki sterownicze + lampki), TSR7 (nowsze), TAP5b (przekaźniki PUN/PUP/PUS), TP2b lub TP-21b (przekaźniki jazdy/kierunkowskazów), TDg (lampki, starsze), TŁO (ogrzewanie, nowsze), TRPSR1 (rezystory PSR)
**Skrzynia aparatowa:** TSK4, TSK5b, TSK-3b, TSR8, TAP4, TDM (dioda silników DM), TRMRr (rezystory), TZA1/TZA2 (zaciski), stycznik SG4 (SU 320 Tr), silnik rozrusznika PZSOb12a
**Podwozie:** stycznik liniowy SUT-300 (SM); TSR7 (starsze – styczniki ogrzewania/wentylacji przy skrzyni)
**Pomost przedni:** przekaźnik samoczynnego rozruchu PSR (PST-257a)
**Nad drzwiami:** TDPm, przekaźniki drzwi PD1–PD4 (PSF-534)
**Przetwornica PTA-44, bateria akumulatorów, regulator RNT-731, przekształtnik 40/24 V:** pod pudłem wagonu

| Grupa styczników | Oznaczenia | Tablica |
|---|---|---|
| Jazdy | SJ1–SJ3 | TSK-3b |
| Hamowania | SH1, SH2 (TSK4), SH3 (TSK-3b) | |
| Rozruchowe | SR1, SR2 (TSK-3b), SR3–SR5 (TSK5b), SR6, SR7 (TSK4) | |
| Grup silników (szereg/równolegle) | SG1, SG2, SG3, SH3 (TSK-3b), SG4 (SU320Tr, skrzynia) | |
| Liniowe | SL1, SL2 (starsze, TSR8) / SL (nowsze, TSR7) + SM = SUT-300 (podwozie) | |
| Bocznikowania wzbudzenia | SBW1–SBW4 (TSR8) | |
| Ogrzewania | SO1, SO2 (TSR8/TSR7), SOW, SOW1 (TSR7 starsze) | |
| Wentylatorów | SW (TAP4), SMW1, SMW2 (TSR7 nowsze) | |
| Hamulców szynowych | SZH1, SZH2 (SNF155) | TAP4 |

> Pełny wykaz aparatów na każdej tablicy (bezpieczniki B1–B29, przekaźniki, diody, rezystory) jest w `notatki_zrodlowe.md`, rozdz. 14.

---

## 5. Dane techniczne (skrót)

- Sieć: 600 V DC (400–720 V)
- Silniki: 4 × LTa-220, 40 kW ciągłe (41,5 kW godzinowe), maks. 4200 obr/min
- Zabezpieczenie nadprądowe linii: 600 A (SUT-300)
- Pantograf OTK-1: 400 A ciągłe, 600 A chwilowe, masa 100 kg
- Rozrusznik GBT-373: 99 pozycji, 3,3 Ω główna, 106,4 Ω wybiegowa, 170 kg
- Bocznik: I stopień 78% wzbudzenia, II stopień 63%
- Sterowanie: 24–40 V DC
- Hamulce szynowe HS-3: 4 szt., 35 V, siła 42 kN, 130 kg
- Przetwornica PTA-44: silnik 3,8 kW/600 V, prądnica 1,8 kW/40 V/45 A, 280 kg
- Bateria akumulatorów: 5×5 6G100H, 25 ogniw Cd-Ni, 100 Ah, ładowanie 25 A/6 h
- Przekształtnik 40/24 V (PtR): wyjście 28 V, 25 A, 16 kg
- Nastawnik DAT-681: nawrotnik 800 V/200 A, masa 50 kg
- Silnik drzwi PASOřc12: 185 W, 32 V, przełożenie 187,2

---

## 6. Stan opracowania

**Część I maszynopisu – KOMPLETNA (rozdz. 1–24, s. 1–151):**
- [x] s. 1–63: wiadomości ogólne, pantograf, odgromnik, odłącznik, silniki, bocznik, styczniki, przekaźniki, rozrusznik
- [x] s. 64–73: hamulec szczękowy, luzownik, regulacja, hamulce szynowe
- [x] s. 74–89: stanowisko i pulpit motorniczego, nastawnik, wycieraczka
- [x] s. 90–111: bezpieczniki, wyłączniki nadmiarowe, tablice aparatowe
- [x] s. 112–129: przetwornica, regulator napięcia, akumulatory, przekształtnik 40/24 V, maszyna drzwiowa
- [x] s. 130–151: oświetlenie, dzwonki, grzejniki, sterowanie ukrotnione, uszynienie
- [x] brakujące wcześniej strony 20–21, 26–31, 37 – uzupełnione

**Do zdobycia:**
- [ ] **część II opracowania** (współpraca obwodów, schematy ideowe, programy łączeń), jeśli istnieje osobny tom
