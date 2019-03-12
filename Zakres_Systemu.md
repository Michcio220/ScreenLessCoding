# Zakres Systemu - Screenless Coding 2

Wersja 1.1

### Ogólny opis:
System umożliwiającego naukę programowania dla dzieci bez użycia ekranów.Cały system jest podzielony na trzy głowne cześci plansza,serwer i moduł wykonawczy.Plansza jest podłączona do serwera który przekazuje  instrukcje do modułu wykonawczego bedącego albo prostą gra lub robotem(np. robot Lego).Po ustawnieniu klocków na planszy dana instrukcja zostaje przekazana przez serwer do modułu wykonawczego , ktory nastepnie wykonuje dane instrukcje.Klocki są bezpieczne w użyciu przez małe dzieci, nie wymaga sie wpasowywania klocków  w jakis sposób przez dziecko.Kilka przykładowych instrukcji to "przejdż 10 kroków do przodu", "obróć sie", robienie jakieś czynności w petli.

### Aktorzy systemu:
## Aktorzy głowni
| Aktor             | Opis |
|-------------------|------|
| Dziecko           | dziecko w wieku od 2-5 lat  |
| Osoba Nadzorująca | osoba odpowiedzialna za pomoc/nadzór w obsłudze systemu     |
|                   |                                                             |

## Aktorzy wspomogajacy
| Aktor             | Opis |
|-------------------|------|
|                   |      |
|                   |      |     
 
### Tabela Aktor-Cel:
| Aktor             | Cel |
|-------------------|-----|
| Dziecko           | Nauka obchodzenia się z mechanizmami działania połączeń podczas układania klocków |
|                   | Nauka obchodzenia się z mechanizmami działania samochodu/robota                   |
|                   | Nauka programowania prostych instukcji, które imituja linijki kodu                                               |
| Osoba Nadzorująca | Pomoc w obsłudze planszy i modułu wykonawczego    |
|                   | Nadzór by dzieci nie zepsuły planszy etc.         |
|                   | Spędzenie miłych chwil z dzieckiem/podopiecznymi  |

### Lista IN-OUT

| Kategoria   | IN  | OUT |
|-------------|-----|-----|
| Przejście labiryntu            | Przejście labiryntu fizycznego          | Przejście labiryntu narysowanego na kartce |
| Robot       |            | |

### Słownik projektowy:
|                   | Znaczenie |
|-------------------|-----------|
| Dziecko           |  dziecko w wieku 2-5 lat korzystajaca z systemu         |
| Osoba Nadzorująca |  osoba dorosła,opiekun,rodzic        |
| Plansza           |  narzędzie do pisania programów, oparte na prostych drewnianych klockach        |
| Moduł Wykonawczy  |  dowolne urządzenie zdolne odczytać zestaw instrukcji pochodzący z serwera.         |
| Serwer            |  komunikujący się z planszą, pozwalający na przekształcenie układu klocków na zestaw instrukcji.       |
| Klocki            |  klocki służace do przekazywania instuckji serwer-moduł          | 

### User-stories:
1. Jako dziecko chcę zaprogramować swojego robota by przeszedł stworzony przez ze mnie labirynt ponieważ znudził mnie już podany.(Średni)
2. Jako dziecko chcę by klocki były różnych kolorów ponieważ będą bardziej interesujące(Średni)
3. Jako dziecko chcę móc kontrolować mojego robota ponieważ nie lubie wyglądu podstawowego robota(Niski)
4. Jako osoba nadzorujaca chcę by system był bezpieczny w obsłudze przez dziecko ponieważ bezpieczęństwo dziecka jest najważniejsze(Wysoki)
5. Jako osoba nadzorująca chcę by dziecko uważało nauke za pomocą urządzenia za przyjemne ponieważ uważam że dzieci uczą się
lepiej jeśli sprawia to im przyjemność(Wysoki)

### Wymagania niefunkcjonalne:

* Plansza bedzie mogła rozpoznać typ klocka po rezystorze 
* Moduł wykonawczy bedzie mogł wykonywać bardzo skomplikowane instrukcje
* Możliwości zaprogramowania przez dziecko petli
* Przejście labiryntu zaprojektowanego przez dziecko
* Interaktywne klocki
