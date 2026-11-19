# Notatki źródłowe – Konstal 805Na (maszynopis MPK Łódź, opis aparatury elektrycznej)
Źródło: zdjęcia ../805na/ (34 szt., numeracja 01–34 wg kolejności nazw plików)

## Spis treści (zdj.01–02)
1 Wiadomości ogólne 1 | 2 Odbierak prądu 8 | 3 Odgromnik 12 | 4 Odłącznik liniowy 14 | 5 Silniki trakcyjne 16
6 Bocznik indukcyjny 20 | 7 Styczniki 23 (7.1 SNF 27, 7.2 STT 30, 7.3 SU 320 Tr 32, 7.4 SUT-300 34)
8 Przekaźniki 38 (8.1 PJT-654 41, 8.2 zwłoczny PZW 44, 8.3 samoczynnego rozruchu PST-257a 46, 8.4 R-1510 51, 8.5 PSF-534 53)
9 Rozrusznik i rezystory wstępne rozruchu 55 (9.1 rozrusznik 55, 9.2 silnik rozrusznika 60, 9.3 rezystory wstępne 62)
10 Hamulec szczękowy i luzownik 64 (10.1 regulacja hamulca 69) | 11 Hamulce szynowe 70
12 Stanowisko motorniczego 74 (12.1 pulpit 75, 12.2 nastawnik jazdy 82, 12.3 wycieraczka 86)
13 Bezpieczniki i wyłączniki nadmiarowe 90
14 Tablice aparatowe 91: szafka aparatowa: TBN (bezp. niskiego napięcia) 92, TBW (bezp. wysokiego napięcia) 91, TŁS (przełączniki sterownicze) 94, TRPSR1 95, TAP5b 96, TP2b 98, TP-21b 99, TDg (urządzenia kontrolne) 99, TSR7 100, TŁO (łączniki ogrzewania) 100
  skrzynia aparatowa: TSK4 101, TSK5b 102, TSR8 102, TSK-3b 104, TAP4 105, TDM (diody silników) 106, TRMRr 107, TZA1/TZA2 108
  pozostałe: TSR7 108, TDPm (przekaźniki drzwi) 109, TRGu 111
15 Przetwornica 112 | 16 Regulator napięcia 117 | 17 Bateria akumulatorów 119 | 18 Przekształtnik 40/24V 124
19 Maszyna drzwiowa 126 | 20 Oświetlenie (wewn. 130, statecznik 131, zewn. 134) | 21 Dzwonki sygnałowe 139
22 Grzejniki elektryczne 141 | 23 Złącza sterowania ukrotnionego 145 | 24 Uszynienie wagonu 150

## 1. Wiadomości ogólne (s.1–7)
- Rozrząd pośredni sterowany automatycznie: nastawnik z pedałami jazdy i hamowania -> cewki styczników + napęd rozrusznika (silnik rozrusznika). Prędkość obrotu rozrusznika kontroluje przekaźnik samoczynnego rozruchu, zależnie od stopnia wciśnięcia pedału.
- Napięcie sieci nominalnie 600 V, w praktyce 400–720 V.
- Dwie grupy silników (po 2 silniki), przełączanie szereg -> równoległe stycznikami SG, sterowane przekaźnikiem napięcia rozruchu PUR (gdy spadek na rezystancji rozrusznika = 200 V); dioda D zapobiega przepływowi z ominięciem silników. Oszczędność ~6% energii.
- Hamowanie: elektrodynamiczne; przy niskich prędkościach rozrusznik włącza I stopień hamulców szczękowych.
- II (silniejszy) stopień hamulców szczękowych: samoczynnie przy zaniku napięcia zasilającego napędy aparatów rozrządu (brak hamowania ED) LUB razem z hamulcami szynowymi i hamowaniem ED po puszczeniu pedału czuwaka.
- Zmiana kierunku: drążek kierunku nastawnika (zmienia kierunek prądu w uzwojeniach wzbudzenia).
- Sterowanie ukrotnione: kilka wagonów z kabiny pierwszego; blokady zależne od stanu aparatów i urządzeń pomocniczych.
- Urządzenia pomocnicze: zasilanie obwodów rozrządu, chłodzenie silników i rezystorów, oświetlenie, sygnalizacja akustyczna/świetlna, ogrzewanie, zdalne sterowanie drzwiami.
- Opisano wagony wcześniejszych dostaw ze zmianami MPK Łódź + różnice ostatnich dostaw.

## 2. Odbierak prądu (s.8–11)
- Pantograf OTK-1 (nożycowy), ślizgacz z 2 ślizgami z wkładkami węglowymi (grafitowymi), mocowany na 4 łapach na izolatorach porcelanowych, zaciski M10.
- Opuszczanie: linka doprowadzona do kabiny motorniczego, blokowana zamkiem linki pantografu. Rama w dolnym położeniu opiera się na odbijakach.
- Dane: izolacja 800 V, robocze 600 V, prąd ciągły 400 A, chwilowy 600 A; położenie ślizgów: dolne robocze 1200 mm, dolne konstrukcyjne 275 mm, górne robocze 2300 mm, górne konstrukcyjne 2675 mm; docisk 69±7 N; masa 100 kg.

## 3. Odgromnik (s.12–13)
- Na dachu przy podstawie pantografu. Iskiernik + stos zmiennooporowy + obudowa porcelanowa. Chroni przed wyładowaniami atmosferycznymi i przepięciami, prąd odprowadzany do uszynienia wagonu.

## 4. Odłącznik liniowy OLT-198 (s.14–15)
- Otwiera/zamyka obwód główny W STANIE BEZPRĄDOWYM (nie pod obciążeniem!). W stanie otwarcia widoczna przerwa izolacyjna – bezpieczeństwo przy konserwacji/naprawie.
- Drewniana obudowa z uchylną pokrywą, jednobiegunowy odłącznik nożowy. Wyłączanie: obrót rączki w pokrywie i odchylenie pokrywy; załączanie: zamknięcie pokrywy.
- Dane: izolacja 800 V, probiercze 3800 V, prąd 400 A, praca ciągła, 10^4 cykli, 7 kg.

## 5. Silniki trakcyjne LTa-220 (s.16–18)
- Szeregowe prądu stałego; samoczynnie dopasowują prędkość do obciążenia, duży moment przy małych prędkościach, odporne na przeciążenia i zmiany napięcia.
- Uzwojenia: wirnika, komutacyjne (końcówki A–H), biegunów głównych/wzbudzenia (E–F). Zmiana kierunku = zmiana kierunku prądu w wzbudzeniu.
- Górny kwadratowy otwór – doprowadzenie powietrza chłodzącego. Charakterystyki n=f(I), M=f(I) do 300 A.
- Dane LTa-220: praca godzinna 41,5 kW / 157 A / 1845 obr/min / 88%; ciągła 40 kW / 150 A / 1890 obr/min / 88%; max 4200 obr/min, max napięcie 720 V, najmniejszy stopień wzbudzenia 63%, max prąd chwilowy (30 s) 314 A. Chłodzenie wymuszone 7,5–0,4 m³/min.

## 6. Bocznik indukcyjny (s.20–22; zdj.13 = zdjęcie bocznika z zaciskami T29,T27,T12,T13,T15)
- Osłabianie wzbudzenia: I stopień – 78% prądu przez wzbudzenie, 22% przez bocznik (E1/E2 do T15/T12, E3/E4 do T29/T26); II stopień – 63% / 37% (E1/E2 do T13/T12, E3/E4 do T27/T26).
- Indukcyjność bocznika chroni przed złą komutacją i ogniem okrężnym na komutatorze w stanach przejściowych.

## 7. Styczniki (s.23–25)
- Elektromagnetyczne zwierne, sprężyna zwrotna, komora łukowa z cewką wydmuchową; zestyki pomocnicze zwierne/rozwierne.
- Tabl. 7.1 – wykaz styczników 805Na (starszy typ) i miejsce zainstalowania:
  SBW1 SNF151 TSR8 | SBW2 SNF101 TSR8 | SBW3 SNF151 TSR8 | SBW4 SNF151 TSR8 | SPH SNF151 TSR7 | SPHR SNF151 TSR7
  SG1 STT150-1 TSK3b | SG2 STT150-2 TSK3b | SG3 STT150-1 TSK5b | SG4 SU320Tr skrz.aparat.
  SH1, SH2 STT150-1 TSK4 | SH3 STT TSK3b | SJ1–SJ3 STT150-1 TSK3b | SL1, SL2 SNF105 TSR8 | SM SUT300-4 podwozie
  SKW1 SNF151 TSR8 | SKW2 SNF456? TSR8 | SO1, SO2 SNF106 TSR8 | SOW SNF143 TSR7 | SOW1 SNF153 TSR7
  SR1, SR2 STT TSK3b | SR3–SR5 STT TSK5b | SR6, SR7 STT TSK4 | SW SNF139 TAP4 | SZH1/SZH2 SNF456 TAP4
  (odczyt przybliżony – kopia słabej jakości)
- Zdj.16: fragment drugiej tablicy styczników (prawdopodobnie nowszy typ): SJ3 TSK3b | SL TSR7 | SM podwozie | SMW1, SMW2 TSR7 | SO1, SO2 TSR7 | SOW, SOW1 TSR8 | SR1,SR2 TSK3b | SR3–SR5 TSK5b | SR6,SR7 TSK4 | SW TAP4 | SZH1, SZH2 TAP4
  => w nowszych wagonach jeden stycznik liniowy SL (TSR7) zamiast SL1/SL2 (TSR8).
- Oznaczenie SNF-xyz: x=1 z cewką wydmuchową / 2 z magnesami trwałymi; y = zestyki pomocnicze (0 brak,1 1r,2 1z,3 2z,4 2r,5 1r+1z); z = prąd ciągły (0=2A,9=4A,7=6A,6=10A,5=16A,3=30A,2=40A,1=52A). SNF-151 = wydmuch, 1r+1z, 52 A.
- 7.3 SU 320 Tr (s.32–33): stycznik z forsowanym napędem, 2 tory prądowe, w skrzyni aparatowej (pionowo, zwora do góry). 160 A ciągły, izolacja 800 V (pomoc. 500 V), łączeniowe 600 V, cewka 40 V, sterowanie 24–50 V (0,6–1,25 Un), 2 zestyki główne zwierne, moc 165 W rozruch / 25 W zamknięty, czas zamykania 30 ms / otwierania 25 ms, 9 kg. Praca −30…+35 °C.
- Łączniki pomocnicze SU320: 10 A, 110 V, 2z+2r.

### 7.4 Stycznik liniowy SUT-300 (s.34–37) – WAŻNE dla awarii
- Stycznik liniowy (SL) do załączania/wyłączania prądów roboczych ORAZ wyłączania prądów przeciążeniowych i zwarciowych w obwodzie głównym. Montowany na podwoziu (SM w tabeli = SUT300-4 "podwozie").
- = stycznik STT-300 + mechanicznie sprzężony przekaźnik nadmiarowo-prądowy PGA-115 (cewka prądowa Lp nadmiarowa + cewka napięciowa trzymająca Lt).
- Gdy prąd trakcyjny > prąd nastawczy -> PGA-115 przyciąga zworę, rozwiera styki główne, przełącznik Pp przerywa zasilanie cewki napędowej Ln i załącza cewkę trzymającą Lt (zwora trzymana po przerwaniu prądu).
- PONOWNE ZAŁĄCZENIE możliwe dopiero po PRZERWANIU zasilania cewki trzymającej Lt i ponownym zasileniu cewki napędowej Ln (czyli "reset" – odłączenie i ponowne podanie napięcia sterowania).
- Prąd zadziałania w 805Na: 600 A (zakres nastawy 550–750 A), regulowany śrubą naciągu sprężyny. Jeśli zadziała przy mniejszym prądzie -> zwiększyć naciąg; jeśli nie rozłącza przy nastawionym -> zmniejszyć (czynność warsztatowa).
- Dane: izolacja 800 V, łączeniowe 600 V, ciągły 300 A, łączeniowy zwykły 300 A / dorywczy 1200 A, sterowanie 40 V (24–42 V), moc 57 W, czas własny włączania 400 ms / otwierania 60 ms, styki pomocnicze 2z+1r 10 A, masa 43,5 kg.

## 8. Przekaźniki (s.38–41)
- Typy: PJT 654, PSF 534, PST 257a, PZW 541/544/546/547, R-1510.
- Tabl. 8.1 (starszy typ) / 8.2 (nowszy) – oznaczenia i miejsce:
  PB TAP4 | PD1–PD4 TDPm (drzwi) | PH TAP4 | PHP TP2b/TP21b | PK1, PK2 TP2b/TP21b | PKR TP2b/TP21b | PKW TAP4 | PLSS TP2b/TP21b | PLZ TP2b/TP21b
  PMRr TAP4 | PMW TAP4 | POW TAP4 | PP TP2b/TP21b | PR TAP4 | PRS TSR7/TSR8 | PSR (PST-257a, samoczynnego rozruchu) pomost przedni
  PUN TAP5b | PUP TAP5b | PUR (PJT654) TSR7/TSR8 | PUS TAP5b | PZJ TP2b/TAP5b | PZR TP2b/TP21b
- PJT-654: obwody sterowania i pomocnicze; magnetowód, cewka, styki, płyta izolacyjna, pokrywa, sprężyna regulowana.
- PJT-654 (s.42–43): 4 zestyki (2z+2r w.1 / 4z w.2); zadziała przy ≥24 V DC; izolacja styków 600 V, uzwojenia 250 V, styki 10 A, napięcie napędu 40 V, rozruchowe 24 V, moc 5 W, czas 60 ms, 1000 cykli/h, 1,85 kg. Regulacja: śruba naciągu sprężyny tak, by zwora przyciągała przy 24 V (warsztat).

## 8.2 Przekaźniki zwłoczne PZW (s.44–45)
- Pierścienie opóźniające (zwłoka przy odpadaniu), blaszka miedziana przeciw klejeniu zwory.
- PZW-541 0,45 s cewka napięciowa 20 V | PZW-544 0,65 s 20 V | PZW-545 0,75–0,8 s 40 V | PZW-546 0,8 s 40 V | PZW-547 0,8 s prądowa 12 A.
- Izolacja 500 V, styki 10 A, praca ciągła, 250 ł/h, trwałość 5·10^4, 5,4 kg.

## 8.3 Przekaźnik samoczynnego rozruchu PST-257a (PSR, pomost przedni) (s.46–49)
- 2 przekaźniki sprzężone: kontrolny (4 cewki, zwora z węglowym stykiem oscyluje między 2 srebrnymi stykami) i regulacyjny (1 cewka, bez styków, działa na zworę kontrolnego cięgnem).
- Sprzężenie zwrotne obwód główny <-> sterowanie: prąd silników ustawiany wciśnięciem pedału, wpływa na położenie rozrusznika.
- Prawidłowa regulacja ma "istotne znaczenie dla poprawnego działania" – regulacja warsztatowa (zasilacze 0–300 A, 0–2 A, 0–45 V, lampka; zaciski T21/T23/T31/T36/T39, B7, 7, 31, 50z; rezystor RPSR2):
  1) min. prąd rozruchu Jr_min = 110–120 A (sprężyna)
  2) min. prąd hamowania Jh_min = 65–75 A (sprężyna)
  3) max prąd rozruchu Jr_max = 220–230 A przy 24,2 V na cewce regulacyjnej (rezystor RPSR2)
  4) max prąd hamowania 170–180 A przy 32 V (RPSR2)
  5) działanie przy prądzie wybiegowym (cewka wybiegowa 0–2 A, T39+/T36−)
- PST-257a dane: izolacja obw. trakcyjnych 800 V, pomocniczych 250 V, napięcie styków 35 V, 8 kg. Prąd wybiegowy Jw = 1,1–1,2 A (lampka zapala się), przerwa stykowa 1,6 mm, docisk ≥15 G.

## 8.4 R-1510 (s.51–52)
- Przekaźniki pośredniczące z rodziny R15, wtykowe (z gniazdem/bez). Wykonania: R-1510-1322-1024 (24 V), R-1510-1322-1040 (40 V), R-1510-5423-1040 (40 V).
- 10 A przy 250 V, obciążalność trwała 3 A, 0,8–1,1 Un, 1,5 W, zadziałanie 20 ms / powrót 15 ms, ok. 80 g, 3r+3z lub 4r+4z.
- Praktycznie: przekaźnik wtykowy -> możliwa szybka wymiana na sprawny (warsztat/serwis).

## 8.5 PSF-534 – przekaźnik drzwi (s.53–54)
- Napęd elektromagnetyczny + 2 łączniki pomocnicze ZDP-403; bez obudowy i podstawy, mocowane bezpośrednio do tablic TDPm w pomieszczeniach maszyn drzwiowych NAD DRZWIAMI. Pozycja pionowa, styki u dołu.
- Cewka 36 V DC, 2z+2r, 5 A, praca ciągła.

## 9. Rozrusznik GBT-373 i rezystory wstępne (s.55–57)
- Przełącza rezystancję w szereg z silnikami przy rozruchu i hamowaniu; przygotowuje rezystancję do ponownego rozruchu/hamowania na wybiegu.
- Rezystancja główna: 93 elementy (taśma chromonikielina) 50×0,029 Ω + 43×0,043 Ω = 3,299±0,26 Ω; palce miedziane dociskane rolkami krzyżaka do pierścienia zbiorczego (zawsze 3 palce – zabezpiecza przed przerwaniem obwodu).
- 99 pozycji rozrusznika. Rozruch: max rezystancja w poz. 1, maleje ze wzrostem nr. Hamowanie: max w poz. 99, maleje ze spadkiem nr.
- Rezystancja wybiegowa: 22 oporniki (6×4 Ω, 8×4,8 Ω, 8×5,5 Ω) = 106,4 Ω, na bębnie z komutatorem i 2 szczotkami zbiorczymi. Zespół łączników CVM (styki pomocnicze rozrusznika).
- Bęben rozrządczy obraca się z krzyżakiem, szczotki nieruchome; rezystancja wybiegowa rośnie od 0 do 106,4 Ω (poz. 1 -> 99). 12 przerywników CUM 323 na 2 listwach izolacyjnych, uruchamiane segmentami stalowymi wg programu (część II, rys. 46).
- Dane GBT-373: izolacja główna 800 V, pomocnicza 250 V, łączniki pomocnicze 35 V, 99 pozycji, rezystancja 3,299 ±8%, czas ruchu: poz. 1→99 3±0,3 s; 99→30 2±0,2 s; 30→1 2±0,2 s; masa 170 kg.

## 9.2 Silnik rozrusznika PZSOb12a (s.60–61)
- W skrzyni aparatowej, napęd przez wał, przekładnię ślimakową i sprzęgło cierne. Dwubiegunowy, 2 uzwojenia (praca nawrotna – obroty w obie strony).
- 32 V, 2,85 A, 0,03 kW, sprawność 0,33, 300 obr/min (max 375), moment 0,0975 kGm, 19,5 kg.

## 9.3 Rezystory wstępne rozruchu AZT-151 (s.62–63)
- 3 rezystory (RR1, RR2, RR3) w skrzyni rozrusznika; ograniczają prąd w początkowej fazie rozruchu.
- Każdy: 2 skrętki po 1 Ω z zaczepem 0,8+0,2 Ω; RR1, RR2 ustawione na 1,6 Ω; RR3 (jedna skrętka) 1 Ω. Izolacja 600 V, probiercze 3800 V, 25 A, praca ciągła, 5 kg.

---

# UZUPEŁNIENIE: rozdz. 10–19 (strony 64–129)
Źródło: zdjęcia ../805na_cz2/ (33 szt., seria IMG_..._15xxxx, numeracja p01–p33). Rozkładówki 2 stron.

## 10. Hamulec szczękowy i luzownik (s.64–69)
- Hamulec szczękowy ma **dwa stopnie działania**: I – w końcowej fazie hamowania elektrodynamicznego; II – do hamowania awaryjnego.
- Wagon ma **4 hamulce szczękowe (po jednym na oś)**. Zespół (rys.10.1): bęben hamulcowy na wale silnika trakcyjnego, szczęki z nakładkami ciernymi dociskane sprężyną, luzownik **typu HT-3** działający przez cięgno i mechanizm krzywkowy.
- Luzownik (rys.10.2): obudowa, **cewka z rdzeniem (solenoid)**, sprężyna główna, układ dźwigni/cięgieł, dźwigienka luzowania ręcznego, dwuprzerwowy łącznik pomocniczy (zamknięty przy zahamowaniu).
- Zasada: w stanie **bezprądowym sprężyna główna** dociska szczęki do bębna = wagon zahamowany. Zasilenie solenoidu pełnym napięciem → rdzeń wciągnięty → **odhamowanie**. Daje to **samoczynne hamowanie awaryjne (II stopień)** przy zaniku napięcia rozrządu.
- **I stopień** (słabszy, przy umiejscawianiu wagonu): solenoidy zasilane **obniżonym napięciem przez rezystor** → mniejszy docisk.
- Odhamowanie ręczne (gdy brak zasilania el.): przestawić dźwigienki luzowników w położenie poziome (np. przy holowaniu).
- Rys.10.1 legenda: 1-śruby regulacyjne, 2-krzywka regulująca docisk szczęk, 3-bęben hamulcowy, 4-szczęki hamulcowe, 5-nakładki cierne, 6-sprężyna, 7-cięgło, 8-luzownik (a-stan zahamowania, b-stan odhamowania).

## 11. Hamulce szynowe (s.70–73)
- Awaryjne hamowanie tramwaju. Zawieszone sprężyście na podwoziu **elektromagnesy**, które po wzbudzeniu przyciągają się do szyn, wywołując siłę tarcia. **Zaleta: siła hamowania niezależna od masy wagonu i przyczepności kół.**
- Wagon 805Na: **4 hamulce szynowe typu HS-3**, po 2 na wózek. Magnetowód: rdzeń, 2 nabiegunniki, 2 wymienne płozy. Cewka miedziana w izolacji bawełnianej/asfaltowej, obudowa (dawniej mosiężna; w MPK Łódź ostatnio tylko osłona izolacyjna cewki).
- **Dane HS-3:** izolacja znamionowa 250 V, probiercze 2000 V 50 Hz, napięcie uzwojenia 35 V, rezystancja 3,7 Ω, **siła znamionowa 42 kN** (leżąc na szynie), wysokość zawieszenia nad główką szyny 12 mm, praca dorywcza, masa 130 kg.

## 12. Stanowisko motorniczego (s.74–89)
### 12.1 Pulpit (rys.12.1 / 12.4 / 12.4a)
- Rys.12.1 legenda stanowiska: 1-pulpit, 2-dźwignia nastawnika kierunku, 3-pedał czuwaka, 4-pedał hamowania, 5-pedał jazdy, 6-grzejnik szyb, 7-grzejnik kabiny motorniczego, 8-wycieraczka.
- **Dwie wersje pulpitu:** rys.12.4 = wagon **805Ng/p1** (legenda 1–32), rys.12.4a = wagon **805Na/p3** (legenda 1–28). Układ podobny; różnice w liczbie i rozmieszczeniu łączników/lampek.
- Elementy pulpitu (z legend): łącznik przetwornicy, łącznik ogrzewania tramwaju, łącznik ogrzewania motorniczego i szyb, łącznik przełączania świateł reflektora (krótkie/długie), przełącznik kierunkowskazów, łącznik pozostałych drzwi, łącznik uszczelkowania drzwi I wagonu (zamykanie), łącznik świateł awaryjnych, oświetlenie tablic informacyjnych, oświetlenie stanowiska, lusterka zewnętrznego, tachometr, woltomierz, mikrofon (nie stosowany w części wagonów).
### 12.1a Łączniki pulpitu (s.78) – oznaczenia schematowe
- **ŁRDK** – przełącznik świateł reflektorów (2 poz.: mijania / drogowe)
- **ŁLW** – oświetlenie wewnętrzne; **ŁLJ** – oświetlenie tablic informacyjnych; **ŁLM** – oświetlenie stanowiska motorniczego; **ŁOL** – ogrzewacz lusterek zewnętrznych
- **ŻWS** – wycieraczka szyby (3 poz.: 0 / I / II – różne prędkości)
- **ŁLZ** – oświetlenie zewnętrzne (3 poz.: wył. / światła pozycyjne / + reflektor zewn. i oświetlenie stopni)
- **ŻOT** – ogrzewanie tramwaju; **ŻR** – łącznik jazdy pełniący **rolę stacyjki** (uruchomienie kluczykiem)
- **ŻOM** – ogrzewanie stanowiska motorniczego; **ŻOS** – ogrzewanie szyb (w 805Na/P3 nabudowane za stanowiskiem)
- Woltomierz napięcia 40 V, techograf.
### 12.1b Lampki sygnalizacyjne (s.78–80) – oznaczenia
- **ŻSM1** – praca silnika przetwornicy (świeci = brak pracy / awaria; w stanie OK nie świeci)
- **LSP1** – napięcie 40 V i poślizg (świeci chwilowo = poślizg kół; ciągle = zanik napięcia prądnicy, przepalenie B8/B15/B16 lub awaria przetwornicy)
- **LSS1** – sprawność rezerwowego obwodu zasilania hamulców szynowych (świeci przy "p/t" nawrotnika; gaśnie m.in. przy przepaleniu bezp. rezerwowego, uszkodzeniu PLSS bezp. B19, po wył. ŁLSS)
- **LS21** – luzowniki hamulców szczękowych (świeci = którykolwiek luzownik zahamowany; gaśnie gdy wszystkie odhamowane)
- **LSD1** – stan drzwi (świeci gdy wszystkie zamknięte; gaśnie gdy choć jedne otwarte)
- **LSJ** – jazda (świeci = poprawne działanie wszystkich wagonów w rozruchu/wybiegu/hamowaniu; gaśnie przy zakłóceniach – np. zanik prądu w obwodzie głównym; w wagonie uszkodzonym wtedy zał. kierunkowskazy + dzwonek wewn.)
- **LSJ1** (805Na/P3) – zakłócenia jazdy (działa odwrotnie do LSJ: świeci = niesprawny wagon)
- **LSK** – kierunkowskazy (pulsuje; w 805Na/P3 dwie lampki: lewe i prawe)
- Lampki mają przesłony do regulacji jasności (pokrętłem).
### 12.2 Nastawnik jazdy DAT-681 (s.80–85)
- Schemat blokowy (rys.12.6): zespół dźwigni napędowych i blokady → nastawnik wyborczy jazdy / rozłącznik działania napędu / nastawnik wyborczy hamowania → zespół nawrotnika. Nastawnik **DAT-681** (rys.12.7, 12.8 widok od strony rezystora **GRS-325**).
- Rozłączniki typu **CUM-323** na płycie izolacyjnej; krzywki na wałach otwierają/zamykają zestyki.
- **Blokada mechaniczna:** przestawienie dźwigni nastawnika kierunkowego możliwe tylko gdy dźwignie jazdy i hamowania są w poz. "0" (pedały niewciśnięte); wciśnięcie pedału jazdy/hamowania możliwe tylko gdy nastawnik kierunkowy dokładnie w poz. "przód" lub "tył".
- Na nastawniku nabudowany **bocznik pomiarowy 400 A** dla II grupy silników (w ostatnich dostawach dwa boczniki – dla obu grup).
- **Dane DAT-681:** izolacja obw. głównego 800 V, obw. sterowania rozłączników mech. 250 V, napięcie sterowania 35 V DC, robocze nawrotnika 800 V, prąd cieplny styków nawrotnika 200 A, styków rozłączników 20 A, praca ciągła, gęstość łączeń 50 ł/min, siła napędowa walca nawrotnika 170 N / jazdy 110 N / hamowania 70 N, trwałość łączenia nawrotnika 10⁴ cykli przełączeniowych, trwałość mechaniczna 10⁵ cykli, masa 50 kg.
### 12.3 Wycieraczka szyby (s.86–89)
- Silnik **MWS 24 V**, dwa uzwojenia (2 prędkości). Łącznik ŁWS 3-pozycyjny (0/I/II). Łącznik pomocniczy MWS zapewnia dojazd pióra do położenia spoczynkowego po wyłączeniu. Przewody 680 / 900 / 970–973. Rys.12.9 schemat, rys.12.10 widok.

## 13. Bezpieczniki i wyłączniki nadmiarowe (s.90)
- **Bezpiecznik topikowy** (rys.13.1): korpus porcelanowy, element topikowy, przestrzeń wypełniona piaskiem kwarcowym (gasi łuk). Chroni obwody WN i NN przed przeciążeniem/zwarciem.
- **Wyłącznik nadmiarowy** (rys.13.2): zabezpieczenie termiczne (termobimetalowe) oraz elektromagnetyczne; element bimetalowy, elektromagnes, zapadka, pozycje 0-wyłączenie / I-włączenie. Przy przeciążeniu rozłącza termicznie, przy zwarciu – elektromagnetycznie.

## 14. Tablice aparatowe (s.91–111) — GDZIE CO JEST
Większość aparatów w **szafie aparatowej** i **skrzyni aparatowej**. Różnice wagony starsze/nowsze (805Na vs 805Na/P3 – nowe od wagonu N-101 na S-161, zmiany typów bezpieczników/wyłączników, tablica TŁO przeniesiona do szafy z pulpitu).
### 14.1 Tablice w szafie aparatowej
- **TBW** (bezpieczniki wysokiego napięcia): starsze B1(6A) B2(6A) B3(10A) B4(25A) B6(10A) B7(25A) B26(25A), B11(10A) B12(10A) B14(10A) B15(6A) B17(25A) B20(25A) B21(25A) B25(10A) B27(6A) B28(20A) B29(10A); wyłączniki nadmiarowe N101: WN1, WN2. W nowszych zamiast bezpieczników – samoczynne wyłączniki instalacyjne S161: S161-8A (B11,B12,B13,B14,B27), S161-6A (B24,B25,B29), S161-10A (B20,B21,B28,WN3), S161-16A (B17,WN1), S161-25A (WN2,B4). + oprawa na bezpiecznik zapasowy.
- **TBN** (bezpieczniki niskiego napięcia): odłącznik akumulatorów ON-2 (ozn. ODAk) + 12 bezpieczników topikowych.
- **TŁS** (przełączniki sterownicze): ŁK15-2429 (ŁGM), ŁK15-1843 (ŁS), łącznik (ŁRA), bezp. rurkowy WTA-0,315A (B19). Nowsze dodatkowo: ŁK15-2812 (ŁDG), 6 lampek LSM2 LSP2 LSS2 LSZ2 LSD2 LSJ2, bezp. WTA-4A (B15).
- **TRPSR1** (rezystory): RDX219D 12W/15 (RPSR1), RDX219D 25W/82 (RPSR2), dioda DO1-10-03 (DPSR).
- **TAP5b** (przekaźniki): 3× PJT-654 wyk.1 (PUN, PUP, PUS), kondensatory CPUN (opóźniające PUN), kondensator 32 µF (CUP), rezystor DER-20W 500Ω (RUP), diody DO1-10-12 (DUS), DO1-10-03 (DUN); w starszych też AWN75 (RL), DER150W 6000Ω (RUS), DO1-10R-03 (DL); w nowszych zespół DE/DER150W 3000Ω (RUS), DESW 50W 2000Ω (RUS1).
- **TP2b** (przekaźniki, starsze): R15-1510-1322-1024 (PK1,PK2,PLZ), R15-1510-1322-1040 (PZJ,PLSS,PHP,PZR,PP), PZW-545 (PKR), 2× przerywacz kierunkowskazów DLB-5 (PrK1,PrK2), DER50 15Ω (RK), OWZ 3W 15Ω (RPZJ).
- **TP-21b** (tylko nowsze): PZW-545 (PKR), R15-1510-5423-1040 (PP), 4× R15-1510-1322-1040 (PHP,PLSS,PZR,PZJ), R15-1510-1322-1024 (PLZ), 2× przekaźnik elektroniczny kierunkowskazów PEK (PK1,PK2), kondensator 61L-I 220µF (CPZJ), DE7,5 15Ω (RPZJ), diody DO1-10-14 (D6,D7), DO1-10-03 (DLZ,DPKR).
- **TDg** (urządzenia kontrolne, tylko starsze): 6 lampek LSM2 LSP2 LSS2 LSZ2 LSJ2, ŁK15-2812 (ŁDg), łączniki ŁLSS/ŁLSJ, 2× WDT454.
- **TSR7** (tylko nowsze, w szafie): SNF155 (SL), SNF151 (SMW1), 3× SNF156 (SO1,SO2,SMW2), dioda DO1-10-03 (DSMW), DER150 12500 (RMW1), AWN75 6Ω (RMW2).
- **TŁO** (łączniki ogrzewania, nowsze): 3× WDT-454 (ŁOM, ŁOS1, ŁOS2).
### 14.2 Tablice w skrzyni aparatowej
- **TSK4**: 4× STT-150-1 (SH1,SH2,SR6,SR7).
- **TSK5b** (rys.14.10).
- **TSR8** (starsze): 4× SNF-151 (SMW1,SBW1,SBW3,SBW4), SNF-101 (SBW2), 2× SNF-105 (SL1,SL2), 2× SNF-106 (SO1,SO2). Nowsze (805Na/P3, rys.14.12) – inne wyposażenie.
- **TSK-3b**: 7× STT-150-1 (SG1,SH3,SJ1,SJ2,SJ3,SR1,SR2), STT-150-2 (SG2).
- **TAP4**: 2× SNF155 (SZH1,SZH2), SNF139 (SW), 2× PJT654 wyk.1 (PH,PR), PZW544 (PKW), PZW545 (PB), PZW541 (PMRr), PZW546 (POW), PZW547 (PMW), AWN-75 5,4Ω (RZH), diody D3/D8, D4/D5/D9, DW/DSZH, DPR, BYP401-200.
- **TDM** (diody silników): D10-200-12 z radiatorem RM160 (DM), RDL (RD), kondensator MKHP2-0,5µF-1000V (CD).
- **TRMRr** (rezystory): 3× AWN75 0,7Ω (RMRr1,ROW), 3× AWN75 4Ω (RMRr2,RMRr3,RMRr4).
- **TZA1, TZA2** – tablice zaciskowe (zaciski przewodów).
### 14.3 Pozostałe
- **TSR7** (starsze, w podwoziu przy skrzyni aparatowej): 2× SNF151 (SEH,SEHR), SNF-143 (SOW), SNF-153 (SOW1), PJT654 (PUR), PJT654 wyk.1 (PRS), DER-150W 6000Ω (RPUR), diody DO1-10-12 (D1,D2)... [dalsza lista ucięta na dole kadru]

## 15. Przetwornica PTA-44 (s.112–115)
- Źródło napięcia 40 V dla obwodów pomocniczych i ładowania akumulatorów. Silnik + prądnica na wspólnym wale; na obu końcach wentylatory odśrodkowe (chłodzenie przetwornicy, silników trakcyjnych i rozruszników). Silnik szeregowo-bocznikowy; prądnica wzbudzenie bocznikowe, napięcie regulowane regulatorem.
- **Dane (silnik / prądnica):** moc 3,8 kW / 1,8 kW; napięcie 600 V / 40 V; prąd 9,2 A / 45 A; wzbudzenie szer.-boczn. / bocznik.; prąd wzbudzenia max 0,34 A / 1,4 A; prędkość 2000 / 2000 obr/min; sprawność 81,5% / 78,5%; opór dodatkowy w obw. głównym 8,5 Ω; opór rozładowczy uzw. bocznikowego 1200 Ω; wahania napięcia zasilania 400–720 V; granice regulacji napięcia 27–40 V; masa z wentylatorami 280 kg. Rezystor szeregowy silnika ogranicza wzrost prądu przy szybkich zmianach napięcia sieci (przejazd przez izolator sekcyjny).

## 16. Regulator napięcia RNT-731 (s.116–117)
- Utrzymuje napięcie prądnicy przetwornicy w określonych granicach. Zestyki węglowo-grafitowe (2 nieruchome + wibracyjny na zworze elektromagnesu). Cewka wzbudzająca ma uzwojenie napięciowe i prądowe. Oddziałuje przez 4 rezystory RG1–RG4. Rys.16.1 (1-kolumna, 2-styk ruchomy, 3-cewka napięciowa, 4-cewka prądowa, 5-jarzmo, 6-sprężyna, 7-styk prawy, 8-styk lewy, 9-śruba regulacyjna). Ostatnio próby regulatorów elektronicznych.

## 17. Bateria akumulatorów 5×5 6G100H (s.118–123)
- Obok przetwornicy źródło NN; przy uruchamianiu wagonu jedyne źródło NN. Ładowana przez przetwornicę w czasie jazdy. **25 ogniw kadmowo-niklowych (zasadowych) połączonych szeregowo, w 5 skrzynkach po 5.** Masa czynna: płyta dodatnia wodorotlenek niklowy, ujemna tlenek kadmu, elektrolit – roztwór wodny wodorotlenku potasu.
- Eksploatacja: biały osad na pokrywie = węglan potasu (reakcja KOH z CO₂); elektrolit co 2 lata wymienić; dodatek wodorotlenku litu.
- **Dane:** 25 ogniw, pojemność 100 Ah, gęstość elektrolitu 1,19–1,21 g/cm³ (20°C), dodatek wodorotlenku litu 20 g/litr. Wyładowanie: napięcie średnie 30 V, prąd znamionowy 20 A, końcowe 25 V. Ładowanie: max 40 A, normalnie 25 A, czas 6 h.

## 18. Przekształtnik 40/24 V typ PtR (s.124–127)
- Impulsowy stabilizator z szeregowym kluczem tranzystorowym (4× **2N3055** równolegle, T1–T4) – przekształca 40 V → 24 V. Dławik Dł, kondensator C5, diody D5/D6, dioda D20 (zabezpieczenie przepięciowe), C1/C6/C7/D21. Zabezpieczenie nadprądowe na przekaźniku kontaktronowym PK2 → PK1 (samopodtrzymanie, blokada klucza T7). **Reset: po zwarciu/przeciążeniu ponowne zadziałanie możliwe dopiero po wyłączeniu i ponownym załączeniu napięcia zasilającego.** Rys.18.1 schemat, rys.18.2 widok.
- **Dane:** izolacja 60 V, wejściowe 40 V (zakres 33–42 V), wyjściowe 28 V, probiercze 1000 V 50 Hz, prąd obciążenia 25 A, bieg jałowy 30 A, przy 25 A i wej. znam.: 28 V −1,5 V, masa 16 kg.

## 19. Maszyna drzwiowa (s.126–129)
- Zdalne sterowanie 4 par drzwi; każde drzwi = osobna maszyna. Silnik napędowy + przekładnia ślimakowo-zębata + cięgła + sprzęgło (cierne, zabezpieczające) + 3 krzywki napędzające łączniki **CUM**. Rys.19.1 zespół, rys.19.2 schemat kinetyczny.
- 6 obwodów sterowanych krzywkami: zwierający rezystory ograniczające prąd silników drzwi, blokady rozruchu z otwartymi drzwiami, sygnalizacji otwarcia drzwi na pulpicie, oświetlenia stopni, sygnalizacji ostrzegawczej dzwonkowej i świetlnej.
- Silnik DC szeregowy, zasilany 40 V z przetwornicy przez łączniki krzywkowe ŁD (typu CUM). **Zasilanie z przetwornicy → brak możliwości elektrycznego otwarcia drzwi przy wyłączonej przetwornicy / zaniku napięcia sieci → drzwi otwiera się wtedy ręcznie.** Zmniejszony moment (przez opornik szeregowy) trzyma drzwi w pozycji skrajnej.
- **Dane silnika PASOřc12:** moc 185 W (praca 15 min), 32 V, 1750 obr/min, moc chwilowa 500 W, rezystancja wirnika 3,25 Ω, biegunów głównych 0,049 Ω. Przekładnia: ślimakowo-zębata i₁=47/14=3,6, sprzęgło i₂=52, całkowite i=187,2.

---

## BRAKI W ZDJĘCIACH (stan po 2. partii, 2026-11-19)
- **Uzupełnione:** rozdz. 10–19 (s.64–129) — hamulec szczękowy, hamulce szynowe, stanowisko/pulpit/nastawnik/wycieraczka, bezpieczniki, tablice aparatowe (komplet), przetwornica, regulator napięcia, akumulatory, przekształtnik 40/24 V, maszyna drzwiowa.
- **Nadal brak stron:** 20–21 (początek bocznika), 26–27, 29–31 (SNF, STT), 37 (?).
- **Nadal brak rozdz. 20–24 (s.130–150):** 20 oświetlenie (wewn./statecznik/zewn.), 21 dzwonki sygnałowe, 22 grzejniki elektryczne, 23 złącza sterowania ukrotnionego, 24 uszynienie wagonu.
- Niektóre ostatnie wiersze tablic 14.3 (TSR7 starszy – dalsza lista diod) ucięte na dole kadru p23.
- Część II opracowania (współpraca obwodów, schematy, programy łączeń) – nie sfotografowana.
