# Screenless Coding 2- Wizja Projektu

Autorzy:
Patryk Dąbrowski, Michał Malinowski, Dominik Czerwiński, Mikołaj Herwart, Bartosz Kordylewski 

## 1 Wstęp
Niniejszy dokument przedstawia wizję projektu pod tytułem Screenless Coding, który jest narzędziem oferującą łatwą i szybką naukę podstaw programowania bez uzycia ekranów dla najmłodszych użytkowników.

## 2. Cel
System pozwoli młodym dzieciom nauke podstaw programowania.Bedzie to wykonywane za pomocą łatwej do obsługi przez dziecko planszy z klockami służącymi za sposób interakcji z planszą przez dziecko.Plansze bedzie można bezprzewodowo podłaczyć do robota, który bedzię w stanie wykonywać czynności zaprogramowane przez dziecko.Będzie także możliwośc zaprogramowania instrukcji "goto" i "if".Robot bedzię też w stanie przejść labirynt 


## 3. Rynek 

### 3.1 Przedstawienie problemu
Myślenie analityczne i algorytmiczne to bardzo ważna umiejętność, którą
należy rozwijać od najmłodszego. Niestety w przypadku większości
dostępnych narzędzi, programowanie odbywa się na tablecie/komputerze,
a to oznacza wiele godzin spędzonych przed ekranem. Może to być
przeszkodą dla najmłodszych dzieci (2-5 lat). Stąd pomysł na stworzenie
narzędzia nie wymagającego ekranu. 


### 3.2 Alternatywy i konkurencja

| Nazwa | Zalety | Link |
|-------|--------|------|
| LOMO - The tangible coding game      |  Bezekranowy sposób nauki dzieci programowania wykorzystujacy zaplające się klocki do pokazania przejścia programu, łatwy w obsłudze,     | https://www.indiegogo.com/projects/lomo-the-tangible-coding-game/coming_soon     |
| Robot DOC by Clementoni | Łatwe w użyciu przez dzieci,robot rozpoznaje gdzie jest na planszy, gdzie są przeszkody etc.| https://www.clementoni.com/pl/60972-doc-mowiacy-robot-edukacyjny/ |
| Matatalab Coding Set      | Nauka bezekranowa, używa klocków do przesyłania instrukcji,duża ilość klocków, robot potrafi podnosić różne przedmioty | https://www.matatalab.com/      |
| Code-a-pillar by Fisher Price | Programowanie za pomocą klockó,które łaczą się z głowa zdolną do odbierania instrukcji od klocków z nią połączoną | https://fisher-price.mattel.com/shop/en-us/fp/think-learn-code-a-pillar-dkt39 |

## 4. Użytkownicy

### 4.1 Środowisko użytkownika

System ma umożliwić nauke programowania dla młodego dziecka.System będzie się składał z 
planszy interaktywnej, na której za pomocą klocków dziecko bedzię mogło zaprogramować
wykonanie jakiegoś ciągu intrukcji przez robota.Nie bedzie wymagane przez dziecko żadne wpasowywanie klocków.
Dziecko nie musi posiadać żadnej wstępnej wiedzy o programowaniu. 

### 4.2 Tabela użytkowników

| Użytkownik        | Krótki opis   |
|---------|--------------------------|
| Opiekun | osoba zaznajomiona z instrukcją załączoną do urządzenia (w kontekście używania)    |
|         | osoba spełniająca wymogi bycia opiekunem dziecka                                   |
| Dziecko | dziecko w wieku 2-5 lat  |


### 4.3 Cele użytkowników

| Użytkownik        | Cel   |
|---------|---|
| Opiekun | Pomoc w obsłudze planszy i modułu wykonawczego    |
|         | Nadzór by dzieci nie zepsuły planszy etc.         |
|         | Spędzenie miłych chwil z dzieckiem/podopiecznymi  |
| Dziecko | Nauka obchodzenia się z mechanizmami działania połączeń podczas układania klocków |
|         | Nauka obchodzenia się z mechanizmami działania samochodu/robota |
|         | Nauka programowania linijek kodu za pomoca ustawiania klocków na planszy |

### 4.4 Charakterystyka użykowników
* dziecko

| Opis                 | dziecko w wieku 2-5+ lat  |
|----------------------|---|
| Typ                  | dziecko korzystające z systemu  |
| Odpowiedzialnośc     | - |
| Kryteria Zadowolenia | Bezpieczne, ciekawe klocki i plansza, łatwe do obsługi, wytrzymały robot   |

* opiekun

| Opis                 | osoba nandzorująca dziecko   |
|----------------------|---|
| Typ                  | osoba dorosła, rodzic, opiekun   |
| Odpowiedzialnośc     | - |
| Kryteria Zadowolenia | dziecko czerpie przyjemność z korzystania z systemu, dziecko nauczy się nowych rzeczy    |

## 5 Opis Produktu
### 5.1 Funkcjonalności produktu:
* tworzenie wieku linijek kodu na plaszy za pomocą z szerokiego wyboru klocków()
* możliwość stworzenia za pomocą klocków instrukcji warunkowej "if"(Mało systemów na rynku posiada tę funkcjonalność)
* możliwość zaprogramowania robota do wykonywania czynności w pętli(instrukcja "goto")()
* możliwość przejścia robota przez labirynt
* możliwość rozpoznania przez robota przeszkód

### 5.2 
| Wymaganie                                         | Priorytet | Problem | 
|---------------------------------------------------|----------|---------
| Rozpoznywanie klocków                             | Średni | Rozpoznywanie róznych typów klockow |
| Przechodzenie labiryntu stworzonego przez dziecko | Niski | Rozpoznywanie przeszkód przez robota | 
| Implementacja instrukcji "if"                     | Wysoki | Zaprojektowanie klocka zdolnego do przesłanie sygnału "jeśli coś jest prawdą to zrób" | 
| Implementacja instrukcji "goto"                   | Wysoki | Zaprojektowanie klocka zdolnego na przesłanie sygnału "przejdż do linijki X" | 
| Kompatybilność systemu z innymi robotami na rynku | Niski  | Możliwość podłączenia planszy do innych robotów i obsługa ich za jej pomocą |
| Implementacja petli "for"                         | Niski  | Zaprojektowanie klocków zdolnych do przekazania instrukcji "rób jak"  

## 6 Zakres i ograniczenia
### 6.1 Zakres
W pierwszej wersji systemu możliwe będzie zaprogramowanie kilku linijek kodu na planszy za pomocą paru klocków.Robot będzie w stanie przejść prostą trasę wyznaczoną przez dziecko(np. przejście przez pewne pomieszczenie).Możliwe bedzie też zaprogramowanie  pętli "goto" lub instrukcji warunkowej "if".

### 6.2 Ograniczenia
* W pierwszej wersji systemu robot może nie być w stanie rozpoznywać przeszkód(będzie się zatrzymywać jeśli zablokuje mu sie drogę)
* Z powodu braku rozpoznywania przeszkód robot nie bedzie w stanie móc przechodzić labiryntu
