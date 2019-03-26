# Screenless Coding 2- Wizja Projektu

Autorzy:
Patryk Dąbrowski, Michał Malinowski, Dominik Czerwiński, Mikołaj Herwart, Bartosz Kordylewski 

## 1 Wstęp
Niniejszy dokument przedstawia wizję projektu pod tytułem Screenless Coding, który jest narzędziem oferującą łatwą i szybką naukę podstaw programowania bez uzycia ekranów dla najmłodszych użytkowników.

## 2 Miejsce na rynku 

### 2.1 Przedstawienie problemu
Myślenie analityczne i algorytmiczne to bardzo ważna umiejętność, którą
należy rozwijać od najmłodszego. Niestety w przypadku większości
dostępnych narzędzi, programowanie odbywa się na tablecie/komputerze,
a to oznacza wiele godzin spędzonych przed ekranem. Może to być
przeszkodą dla najmłodszych dzieci (2-5 lat). Stąd pomysł na stworzenie
narzędzia nie wymagającego ekranu. 

### 2.2 Przedstawienie produktu
System pozwoli młodym dzieciom nauke podstaw programowania.Bedzie to wykonywane za pomocą łatwej do obsługi przez dziecko planszy z klockami służącymi za sposób interakcji z planszą przez dziecko.Plansze bedzie można bezprzewodowo podłaczyć do robota, który bedzię w stanie wykonywać czynności zaprogramowane przez dziecko.Będzie możliwośc zaprogramowania instrukcji "goto" i "if".Robot bedzię też w stanie przejść labirynt 

### 2.3 Alternatywy i konkurencja

| Nazwa | Zalety | Wady |
|-------|--------|------|
| LOMO - The tangible coding game      |  Bezekranowy sposób nauki dzieci programowania wykorzystujacy zaplające się klocki do pokazania przejścia programu, łatwy w obsłudze,     | Klocki są bardzo małe, nie przystosowane do obsługi przez małe dzieci     |
| Robot DOC by Clementoni | Łatwe w użyciu przez dzieci,robot rozpoznaje gdzie jest na planszy, gdzie są przeszkody etc.| Robot nie jest zbyt wytrzymały, robot nie rozpoznaje przeszkód poza planszą |
| Matatalab Coding Set      | Nauka bezekranowa, używa klocków do przesyłania instrukcji,duża ilość klocków, robot potrafi podnosić różne przedmioty | Brak implmentacji instrukcji "if" i "goto"     |
| Sphero Star Wars Enabled-droids | Robot kontrolowany przez smartfona,bezpieczny do użycia przez małe dzieci  | Zbyt wyskoa cena,nie pozwala na nauke ,tylko bardziej na obsługe robota za pomocą smartphona |

## 3 Opis interesariuszy

### 3.1 Środowisko użytkownika

System ma umożliwić nauke programowania dla młodego dziecka.System będzie się składał z 
planszy interaktywnej, na której za pomocą klocków dziecko bedzię mogło zamprogramować
wykonanie jakiegoś ciągu intrukcji przez robota.Nie bedzie wymagane przez dziecko żadne wpasowywanie klockow.
Dziecko nie musi posiadać żadnej wstępnej wiedzy o programowaniu. 

### 3.2 Użytkownicy

| Użytkownik        | Krótki opis   |
|---------|--------------------------|
| Opiekun | osoba zaznajomiona z instrukcją załączoną do urządzenia (w kontekście używania)    |
|         | osoba spełniająca wymogi bycia opiekunem dziecka                                   |
| Dziecko | dziecko w wieku 2-5 lat  |
|         |                          |

### 3.3 Cele użytkowników

| Użytkownik        | Cel   |
|---------|---|
| Opiekun | Pomoc w obsłudze planszy i modułu wykonawczego    |
|         | Nadzór by dzieci nie zepsuły planszy etc.         |
|         | Spędzenie miłych chwil z dzieckiem/podopiecznymi  |
| Dziecko | Nauka obchodzenia się z mechanizmami działania połączeń podczas układania klocków |
|         | Nauka obchodzenia się z mechanizmami działania samochodu/robota |
|         | Nauka programowania linijek kodu za pomoca ustawiania klocków na planszy |
                                           |
### 3.5 Charakterystyka użykowników
* dziecko

| Opis                 | dziecko w wieku 2-5+ lat  |
|----------------------|---|
| Typ                  | dziecko korzystające z systemu  |
| Odpowiedzialnośc     | - |
| Kryteria Zadowolenia | Bezpieczne, ciekawe klocki i plansza, łatwe do obsługi   |

* opiekun

| Opis                 | osoba nandzorująca dziecko   |
|----------------------|---|
| Typ                  | osoba dorosła, rodzic, opiekun   |
| Odpowiedzialnośc     | - |
| Kryteria Zadowolenia | dziecko czerpie przyjemność z korzystania z systemu    |

### 3.6 Kluczowe wymagania

| Wymaganie                                         | Priorytet | Problem | 
|---------------------------------------------------|----------|---------
| Rozpoznywanie klocków                             | Średni | Rozpoznywanie róznych typów klockow |
| Przechodzenie labiryntu stworzonego przez dziecko | Średni | Rozpoznywanie przeszkód przez robota | 
| Implementacja instrukcji "if"                     | Wysoki | Zaprojektowanie klocka zdolnego do przesłanie sygnału "jeśli coś jest prawdą to zrób" | 
| Implementacja instrukcji "goto"                   | Wysoki | Zaprojektowanie klocka zdolnego na przesłanie sygnału "przejdż do lini 5" | 
| Kompatybilność systemu z innymi robotami na rynku | Niski  | Możliwość podłączenia plaszny do innych robotów i obsługa ich za jej pomocą |

## 4 Opis Produktu
Funkcjonalności produktu:
* tworzenie swoich własnych instrukcji z szerokiej gamy klocków()
* możliwość stworzenia za pomocą klocków instrukcji warunkowej "if"(Mało systemów na rynku posiada tę funkcjonalność)
* możliwość zaprogramowania robota do wykonywania czynności w pętli(instrukcja "goto")()
* możliwość przejścia robota przez labirynt
* możliwość rozpoznania przez robota przeszkód przed sobą
* możliwość
* możliwość
* możliwość

## 5 Zakres i ograniczenia
W pierwszej wersji systemu możliwe będzie zaprogramowanie kilku linijek kodu za pomocą conajmniej 4-6 klocków.Robot będzie w stanie przejść prostą trasę wyznaczoną przez dziecko(np. przejście przez pewne pomieszczenie) lub labirynt(zaprojektowany przez dziecko).Każdy z klocków będzie posiadał namespace który pozwoli na jego rozpoznanie przez plansze.Możliwe bedzie też zaprogramowanie jednej z bardziej rozwinietej instrukcji(petla lub warunek).

