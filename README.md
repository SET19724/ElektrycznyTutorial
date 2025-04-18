# 🔧 Odblokowanie hulajnogi Ninebot – wersja BETA
**Aktualizacja:** 18.04.2025

> ⚠️ **Zastrzeżenie prawne**  
>  
> Niniejszy materiał został stworzony wyłącznie w celach edukacyjnych.  
> Autor nie ponosi odpowiedzialności za jakiekolwiek uszkodzenia sprzętu, błędne użycie instrukcji czy skutki wynikające z modyfikacji opisanych w tym dokumencie.  
>  
> Wszystkie czynności wykonujesz na **! WŁASNE RYZYKO I ODPOWIEDZIALNOŚĆ !**.  
>  
> Jest to jedynie tłumaczenie i opracowanie ogólnodostępnych informacji w języku polskim.


---

## 📌 Obsługiwane modele
- G30
- G2
- F2

---

## ❓ Czy potrzebuję programatora ST-LINK?
**Nie!** Jest to najnowsza metoda, która nie wymaga użycia ST-LINKa.

---

## 🔓 Obsługiwane wersje firmware

Obecnie **nie ma ograniczeń** dotyczących wersji firmware.  
Nawet jeśli masz wersję **1.8.1**, metoda powinna zadziałać bez problemu.

---

📽️ **Poradnik wideo**  
Ten poradnik oparty jest w dużej mierze na materiale z YouTube od użytkownika [Mc Kuc](https://www.youtube.com/@McKuc), który pokazuje krok po kroku nową metodę odblokowania:

[![Zobacz poradnik na YouTube](https://img.youtube.com/vi/WXCJJVfrrk0/hqdefault.jpg)](https://www.youtube.com/watch?v=WXCJJVfrrk0)

---

## ⚙️ Proces odblokowania


### 1. Pobierz aplikację ScooterHacking Utility
👉 PLATFORMA ANDROID [https://utility.cfw.sh](https://utility.cfw.sh)

⚠️ **Co jeśli nie mam androida tylko Iphone ?**  
>Możesz użyć projektu Luna który znajduje sie na https://luna.cfw.sh obecnie poradnik pokazuje tylko jak zrobić to na android ale zasada działania jest taka sama.
Różni się tylko interfejs






- Po uruchomieniu aplikacji wybierz swoją hulajnogę.
  *(Włącz hulajnogę oraz Bluetooth w telefonie)*

  ![](screeny/14.png)

- Kliknij trzy kropki w prawym górnym rogu.

  ![](screeny/1.png)

- Wybierz opcję **"Hardware details"**.

  ![](screeny/2.png)

- Skopiuj swój unikalny **UID**.

  ![](screeny/3.png)

---

### 2. Odepnij hulajnogę od konta w oficjalnej aplikacji

- Przejdź do **Settings**.

  ![](screeny/4.png)

- Na dole wybierz **"Unbind vehicle"**.

  ![](screeny/5.png)

- Kliknij **"Unbind"** – aplikacja poprosi o e-mail przypisany do konta.

  ![](screeny/6.png)

---

### 3. Uzyskanie plików od bota na Telegramie

- Otwórz Telegram i znajdź bota **@downgrade_ninebot**
  👉 [https://t.me/downgrade_ninebot](https://t.me/downgrade_ninebot)

#### Krok po kroku:
W skrócie:
1. Wpisz `/start`
2. Zaznacz **"I understand"**
3. Wybierz model hulajnogi
4. Wklej skopiowany UID
   > **Uwaga:** dokładność UID jest kluczowa — jedna pomyłka = nie odblokujesz
5. Poczekaj na wygenerowanie plików
6. Pobierz pliki

Tutaj ze screenami:

Piszemy /start
Zaznacz "I understand" po przeczytaniu informacji
Następnie wybieramy model

![](screeny/15.png)

![](screeny/16.png)

Bot zapyta o UID wklejamy ze schowka swój unikalny numer

![](screeny/17.png)

Bot potrzebuje trochę czasu teraz czekamy może potrwać od 1 minuty do kilku dni zależnie od kolejki którą musi bot przetworzyć

![](screeny/18.png)

Pobieramy przygotowany plik pod naszą hulajnogę naciskając na 3kropki

![](screeny/9.png)


Po otrzymaniu plików kliknij trzy kropki i wybierz **"Download"**

![](screeny/9.png)

---

### 4. Wgranie plików przez ScooterHacking Utility

1. W aplikacji wybierz zakładkę **FLASH**
2. Kliknij **"LOAD FROM FILE"**
3. Znajdź pobrany plik w pamięci telefonu i wybierz go

   ![](screeny/10.png)

4. Kliknij **"START FLASH"**

   ![](screeny/11.png)

> ⚠️ Nie oddalaj się od hulajnogi i jej nie wyłączaj – możesz ją uceglić! W takim wypadku pomoże tylko programator ST-LINK.

![](screeny/12.png)

Po zakończeniu pojawi się komunikat: **"FLASH COMPLETE!"**
Hulajnoga wyda sygnał dźwiękowy „bi-bip”.

![](screeny/19.png)

✅ **Gotowe! Hulajnoga odblokowana!**

---

## 🎯 Co teraz?

Masz dwie opcje:

- 🔧 [Wgraj SHFW – custom firmware](#-jak-wgrać-shfw-custom-firmware)

  - Dużo opcji jest to alternatywne oprogramowanie od https://scooterhacking.org
  - W skrócie możecie ustawić każdy tryb mocy pod siebie i osiągnąć wyższe prędkości


- 🌍 [Zmień numer seryjny by:](#zmiana-regionu--poprzez-numer-seryjny)

  - Zmienić ograniczenia prędkości
  - Odblokować tempomat

Jak zmienicie oprogramowanie na alternatywne warto korzystać z aplikacji NineDash
 https://play.google.com/store/apps/details?id=adriandp.ninedash

Nie wiadomo czy aplikacja nie wymusi automatycznej aktualizacji która ponownie zablokuje możliwości zmian dla zaawansowanych użytkowników


  > ⚠️ **Uwaga prawna**  
> Zmiana ograniczeń prędkości może naruszać lokalne przepisy dotyczące poruszania się hulajnogą elektryczną po drogach publicznych.  
>  
> Tak zmodyfikowany pojazd może być użytkowany **wyłącznie na terenie prywatnym i na własną odpowiedzialność**.  
>  
> Autor nie ponosi odpowiedzialności za skutki wynikające z nieprzestrzegania przepisów prawa ani za szkody wyrządzone osobom trzecim.

---

## 🌍 Zmiana regionu – poprzez numer seryjny

### Przykład numeru seryjnego (G30):
N4GSD1939C0123

| Pozycja  | Fragment | Znaczenie                                      |
|----------|----------|------------------------------------------------|
| 1–3      | N4G      | Identyfikator produktu                         |
| 4        | S        | Wersja produktu / region                       |
| 5        | D        | Linia produkcyjna                              |
| 6–7      | 19       | Rok produkcji (np. `19` = 2019)                |
| 8–9      | 39       | Tydzień produkcji                              |
| 10       | C        | Rewizja produktu                               |
| 11–14    | 0123     | Unikalny numer seryjny                         |

**Najważniejsze są 4 pierwsze znaki!**

---

### 📌 Przykłady zmian numerów seryjnych

#### G30:
- `N4GE` → DE (20 km/h)  
- `N4GS` → International (30 km/h) ← zalecana zmiana

#### G2:
- `01GZ` → DE, 20 km/h, bez tempomatu  
- `01GU` → US, 32 km/h, z tempomatem ← zalecana zmiana  

---

## 🛴 Lista prefixów numerów seryjnych

### G2:
| Prefix   | Region | Ograniczenie       |
|----------|--------|--------------------|
| 01GZ     | DE     | 20 km/h, brak CC   |
| 01GT/01GY| EU     | 25 km/h, brak CC   |
| 01GU/01GX| US     | 32–35 km/h, z CC   |
| 02GV     | EU     | 25 km/h, z CC      |
| 02GW     | EU     | 25 km/h, brak CC   |

### G30:
| Prefix   | Model                        | Prędkość  |
|----------|------------------------------|-----------|
| N4GS     | Max (WW)                     | 30 km/h   |
| N4GC     | Max (EU)                     | 25 km/h   |
| N4GE     | Max (DE, niebieski)          | 20 km/h   |
| N4GP     | Max (EU)                     | 25 km/h   |
| N4GN     | Max Lite (WW)                | 30 km/h   |
| N4GA/N4GO| Max Lite (EU)                | 25 km/h   |
| N4GM     | Max Lite (DE)                | 20 km/h   |
| N4GT     | Maserati MC                  | 25 km/h   |
| N4YC     | Seat Mó                      | 20 km/h   |
| NTG1     | Audi EKS                     | 20 km/h   |

---

## ✨ Złoty numer seryjny

Jeśli zmienisz **pozycje 6–9** w numerze seryjnym na `1111`, np.:N4GSD1111C0123


...i zrestartujesz hulajnogę, odblokujesz **pełny potencjał fabrycznego oprogramowania**.

> To był numer testowy używany przez deweloperów – bez limitów prędkości i z aktywnym tempomatem.

---


## 📊 F2 / F2 Plus / F2 Pro (sortowane wg SPORT prędkości)

Tabele jaką znalazłem z oryginalnymi wartościami według numeru

| Prefix SN | ECO prędkość | ECO prąd | DRIVE prędkość | DRIVE prąd | SPORT prędkość | SPORT prąd | Model    | Czujnik temp. silnika (E41) |
|-----------|---------------|-----------|----------------|------------|----------------|------------|----------|-----------------------------|
| NAGK      | 15 km/h       | 9 A       | 20 km/h        | 18 A       | 22 km/h        | 26 A       | F2 Plus  | Nie                         |
| NAGE      | 15 km/h       | 9 A       | 20 km/h        | 18 A       | 22 km/h        | 24 A       | F2       | Nie                         |
| NAGU      | 15 km/h       | 9 A       | 20 km/h        | 18 A       | 25 km/h        | 28 A       | F2 Pro   | Tak                         |
| NAGT      | 12 km/h       | 9 A       | 20 km/h        | 18 A       | 25 km/h        | 28 A       | F2 Pro   | Tak                         |
| NAGD      | 15 km/h       | 9 A       | 20 km/h        | 18 A       | 25 km/h        | 24 A       | F2       | Nie                         |
| NAGC      | 12 km/h       | 9 A       | 20 km/h        | 18 A       | 25 km/h        | 24 A       | F2       | Nie                         |
| NAGJ      | 15 km/h       | 9 A       | 20 km/h        | 18 A       | 25 km/h        | 26 A       | F2 Plus  | Nie                         |
| NAGB      | 15 km/h       | 9 A       | 25 km/h        | 18 A       | 30 km/h        | 24 A       | F2       | Nie                         |
| NAGF      | 15 km/h       | 9 A       | 25 km/h        | 18 A       | 30 km/h        | 26 A       | F2 Plus  | Nie                         |
| NAGG      | 15 km/h       | 9 A       | 25 km/h        | 18 A       | 30 km/h        | 26 A       | F2 Plus  | Nie                         |
| NAGA      | 15 km/h       | 9 A       | 25 km/h        | 18 A       | 30 km/h        | 24 A       | F2       | Nie                         |
| NAGH      | 12 km/h       | 9 A       | 20 km/h        | 18 A       | 26 km/h        | 26 A       | F2 Plus  | Nie                         |
| NAGS      | 15 km/h       | 9 A       | 25 km/h        | 18 A       | 32 km/h        | 28 A       | F2 Pro   | Tak                         |
| NAGR      | 15 km/h       | 9 A       | 25 km/h        | 20 A       | 32 km/h        | 28 A       | F2 Pro   | Tak                         |



---

## ℹ️ Dodatkowe info

**Oznaczenia:**
- *with CC* – z tempomatem  
- *no CC* – bez tempomatu  
- **DE** – Niemcy  
- **EU** – Europa  
- **US** – USA  
- **WW** – Międzynarodowy  

---

## 🔁 Jak zmienić region?

1. Otwórz aplikację **ScooterHacking Utility**  
2. Przejdź do zakładki:  
   `TOOLS > CHANGE REGION`  

   ![](screeny/20.png)

3. Wybierz gotowy region lub użyj opcji „CUSTOM”  

   ![](screeny/21.png)

4. Wpisz pełny, poprawny numer seryjny (zgodnie z tabelą wyżej)  
5. Zatwierdź – hulajnoga uruchomi się ponownie

> ⚠️ Nie wpisuj przypadkowych numerów – użyj poprawnych kodów dla swojego modelu!

---

## 🚀 Jak wgrać SHFW (Custom Firmware)

![](screeny/22.png)  
![](screeny/23.png)  
![](screeny/24.png)

Często pojawia się błąd **"Flashing failed"** — **nie panikuj!**  
SHFW najprawdopodobniej zostało poprawnie wgrane. Najlepiej w takim przypadku **wyłącz i włącz hulajnogę**.

Jeśli na ekranie pojawiają się cyfry, to oznacza poziom naładowania baterii.  
Przy 100% powinno wyświetlać się `A0`.

Po poprawnym wgraniu pojawi się wersja SHFW — jak na screenie poniżej.  
Dla pewności warto jeszcze raz powtórzyć proces flashowania.

![](screeny/25.png)  
![](screeny/26.png)

---

## ⚙️ Ustawianie SHFW

> Jeśli tego nie zrobisz, hulajnoga **nie będzie jeździć**, ponieważ nie ma domyślnych ustawień!

Przejdź do zakładki **"CONFIG"**:

![](screeny/27.png)

Rozwiń sekcję **Throttle** — tu ustawisz prędkość i ilość amperów dla poszczególnych trybów:

![](screeny/28.png)

🔸 **Uwaga**: Screen pokazuje tylko wygląd menu — nie kopiuj tych ustawień.

### 📋 Parametry do ustawienia:

- **Speed limit** – maksymalna prędkość hulajnogi  
- **Select mode** – wybór trybu (ECO / DRIVE / SPORT)  
- **Throttle mode** – najlepiej ustawić na `DPC`  
- **Power limit** – zależnie od modelu hulajnogi  

ℹ️ Po kliknięciu ikonki `i` przy każdej opcji wyświetli się szczegółowy opis w języku angielskim.


## 🧠 WAŻNE Silnik nowej generacji model G30 WAŻNE !

Jeśli posiadasz **nowszy silnik trzeciej generacji (Gen 3)** w hulajnodze G30, koniecznie zaznacz opcję **"New motor"** w zakładce `Motor config/Motor settings`.

🔍 **Nie jesteś pewien, którą wersję silnika masz?**  
Porównaj numer seryjny silnika który znajduje się na silniku przy kodzie QR (Motor Serial Number – SN) z poniższą tabelą:

| Numer seryjny silnika (SN)   | Generacja          | Modele                            |
|------------------------------|--------------------|-----------------------------------|
| Zaczyna się od `6`           | Pierwsza generacja | Większość starszych modeli        |
| Zaczyna się od `9`           | Druga generacja    | G30P, niektóre G30Lx              |
| Zawiera `PCAH`               | Trzecia generacja  | G30P                              |
| Zawiera `PAAH`               | Trzecia generacja  | G30E                              |
| Zawiera `PADH` lub `PADJ`    | Trzecia generacja  | G30D                              |

> ✅ **Wniosek:** Jeśli twój numer silnika zawiera `PCAH`, `PAAH`, `PADH` lub `PADJ`, **masz silnik Gen 3** i musisz zaznaczyć odpowiednią opcję w konfiguracji!
Inaczej będą dziwne dźwięki + koło nie będzie jeździć

---


---

## ✅ Zalecane ustawienia wg poradnika od lekrsu
  https://github.com/lekrsu/shfw-walkthrough

Dla modeli: **G30, G2, F2**  
Aby osiągnąć maksymalną wydajność:

### 🧠 Ustawienia ogólne:
Ustawiacie sobie po kolei 3 tryby czyli ECO,DRIVE,SPORT
- Włącz **Expert View** (w prawym górnym rogu)
-W zakładce Throttle
-Naciśnij BUILD CURVE

![](screeny/30.png)

- Tryb SPORT:
  - DPC: **25A**
  - Krzywa: pełna kwadratowa (Quadratic na max w prawo = 1.0)
- Pozostałe tryby: niższe ustawienia (Ja zalecam 10A ECO,16 DRIVE,25A SPORT)
- Ograniczenie prędkości: **wyłączone (0 km/h)**(Przy innych trybach niż sport warto ustawić preferowaną wartość)
- Acceleration boost: **100%**
- Brake boost: **50%**
- Włącz **Overmodulation** dla SPORT/DRIVE



---

### 🧲 Field Weakening (Osłabienie pola magnetycznego)

**Do normalnego użytku:**
- Prędkość: 20 km/h
- Initial: 0A
- Variable: 1200

**Dla wyższej efektywności (niższe zużycie baterii):**
- Prędkość: 20 km/h
- Initial: 0A
- Variable: 600

**Dla szczytowej prędkości (może powodować problemy):**
- Prędkość: 20 km/h
- Initial: 0A
- Variable: 2000

### Brake Hamulce

Warto w tej zakładce ustawić autobraking na 6A

Da nam to automatyczne hamowanie podobne do oryginału

---

### 🛞 Kalibracja kół - Realne prędkości na liczniku
Znajdziecie to ustawienie w "Motor settings"
Domyślny rozmiar kół w modelach g30 Max to **10"**, ale ustaw:

- **G30** → `9.3"`
- **G2 i F2** → `9.7"`

![](screeny/29.png)

> Dzięki temu prędkość na wyświetlaczu będzie bardziej zgodna z rzeczywistą (GPS).

---

### ⚙️ Silnik

- Ustaw **Motor frequency**: `20 kHz` lub `24 kHz`  
  (dla G2 i F2 nie ma tej opcji)

---

### 🔋 Ograniczenia nowszych modeli

Niektóre nowe G30 z nowszym BMS mają ograniczenie prądu baterii do **28A**  
→ przez co będą miały gorsze osiągi niż starsze modele (z limitem **40A**)


## 📚 Źródła:

- https://www.youtube.com/watch?v=WXCJJVfrrk0  
- https://github.com/lekrsu/shfw-walkthrough  
- https://wiki.scooterhacking.org/doku.php?id=nbmax  
-https://rollerplausch.com/threads/f2-series-informationen-firmware-hardware-tuning.11004/
