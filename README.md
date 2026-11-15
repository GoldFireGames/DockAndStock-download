# Dock & Stock

![Dock & Stock - menu główne](img/menu.png)

Gra tycoon o prowadzeniu hurtowni i centrum dystrybucji. Wynajmujesz halę, stawiasz rampy i regały, zatrudniasz magazynierów, zamawiasz towar od producentów i realizujesz zlecenia klientów na czas. Z czasem rozbudowujesz halę, kupujesz własną flotę tirów i odblokowujesz kolejne poziomy. Możesz też przejść się po swojej hurtowni z kawą w ręce.

## Pobieranie

1. Wejdź w zakładkę **[Releases](../../releases/latest)**.
2. Pobierz `DockAndStock-Windows-vX.Y.Z.zip` (w nazwie jest numer wersji).
3. Rozpakuj i uruchom `DockAndStock.exe`.

Wymagania: Windows 10/11, 64-bit.

Windows może pokazać ostrzeżenie SmartScreen, bo gra nie ma jeszcze podpisu cyfrowego: kliknij **Więcej informacji → Uruchom mimo to**.

Do pobrania jest zawsze tylko najnowsza wersja. Zapisy gry z poprzednich wersji wczytują się w nowej.

## Modyfikowanie danych gry

Ceny, produkty, producenci, hale i balans są w zwykłych plikach JSON w folderze `DockAndStock_Data/StreamingAssets`. Możesz je edytować w dowolnym edytorze tekstu (zapisuj w UTF-8, przed zmianami zrób kopię). Nowe produkty dopisuj na końcu listy.

## Sterowanie (skrót)

- Kamera: WASD / strzałki – ruch, Q / E – obrót, kółko myszy – przybliżenie
- Spacer: przycisk **Spacer** albo przybliżenie do końca; G – widok z pierwszej osoby, Esc – powrót
- B – tryb budowy, X – buldożer, N – widok ścian, I – tabela towaru
- Spacja – pauza, 1/2/3 – prędkość gry
- F5 / F9 – szybki zapis / wczytanie
- Esc → **Informator** – zasady i mechaniki gry

Gra jest we wczesnej wersji – błędy i pomysły mile widziane w zakładce **Issues**.

## Historia zmian

### 0.4.1
- Kółko myszy przybliża dużo mocniej (ok. 28% na ząbek przy czułości 100%, suwak do 400%); listy i panele przewijają się 3x szybciej.
- Ustawienia: zmiany zapisują się dopiero po „Zastosuj zmiany”; nowy przycisk „Przywróć domyślne”; „Wróć bez zmian” cofa niezastosowane zmiany.

### 0.4.0
- Zakupy: kafelki produktów ze zdjęciami; każdy produkt u kilku producentów, którzy różnią się ceną i czasem dostawy; cenniki zmieniają się co 3 dni; wybór czasu dostawy (48 h taniej, 24 h, 8 h drożej albo własny tir).
- Zlecenia: lista w sekcjach (nowe, w realizacji, kontrakty, zakończone) i szczegóły z rozliczeniem po prawej.
- Oś czasu na górnym pasku: przyjazdy dostaw oraz odbiory i dostawy do klientów w najbliższych 24 h.
- Tryb spaceru: chodzisz postacią po hali i placu, widok z pierwszej osoby (G) z kawą w ręce.
- Informator w menu Esc: zasady i mechaniki gry.
- Regał przepływowy na 3 palety: pełna paleta sama zjeżdża w dół.
- Oświetlenie nocą w hali i na placu.
- Ludzie i wózki poruszają się 2,5 raza szybciej.
- Strefy obklejone taśmą w ukośne pasy, czerwone krzyżyki na kafelkach bez dojazdu.
- Większe okno nowego zlecenia, Postęp nie nakłada się na inne panele, matowe plandeki tirów.

### 0.3.0
- Nowe zlecenie wyskakuje w oknie (Przyjmij / Odrzuć / Później); nieprzyjęte oferty znikają przed terminem odbioru.
- Klik na pracownika, paletę albo tira pokazuje, co robi, do jakiego zlecenia jest paleta i dokąd jedzie tir.
- Ręczne przenoszenie palet myszką.
- Wybór produktów, które oferujesz klientom.
- Wykup wynajmowanej hali za gotówkę albo na kredyt.
- Poziom firmy nie spada, gdy reputacja chwilowo spadnie.
- Ludzie: lista według zmian, czytelne okno szczegółów.
- Kolizje tylko między wózkami widłowymi.
- Kamera przybliża bliżej, suwaki czułości.
- Podgląd doku przy budowie, darmowe stałe punkty kompletacji, osobne kategorie regałów, czytelne statusy zleceń.

### 0.2.0
- Rozładunek: palety trafiają tylko tam, gdzie da się dojechać; strefa przyjęć zapełnia się od najdalszych miejsc.
- Wybór monitora w ustawieniach.
- Numery ramp na placu i na tablicy nad bramą.

### 0.1.0
- Pierwsze wydanie na Windows.
- Flota: zestawy w trasie zostają w trasie po wczytaniu zapisu.
- Tryby widoku ścian (przekrój / niskie / z dachem) dla wszystkich budynków.
- Pierwszeństwo na rampie przy kolejce tirów.
