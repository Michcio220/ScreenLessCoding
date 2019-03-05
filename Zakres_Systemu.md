# Zakres Systemu - Screenless Coding 2

Wersja 0.5

### Ogólny opis:
System umożliwiającego naukę programowania dla dzieci bez użycia ekranów.Cały system jest podzielony na trzy głowne cześci plansza,serwer i moduł wykonawczy.Plansza jest podłoczona do serwera który przekazuje  instrukcje do modułu wykonawczego bedącego albo prostą gra lub robotem(np. robot Lego).Po ustawnieniu klocków na planszy dana instrukcja zostaje przekazana przez serwer do modułu wykonawczego , ktory nastepnie wykonuje te instrukcje.Klocki są bezpieczne w użyciu przez małe dzieci, nie wymaga sie wpasowywania klocków  w jakis sposób(sposób użycia nie może być za bardzo skomplikowany).Kilka przykładowych instrukcji to "przejdż 10 kroków do przodu", "obróć sie", robienie jakieś czynności w petli.

### Aktorzy systemu:

## Aktorzy głowni
| Aktor             | Opis |
|-------------------|------|
| Dziecko        |   osoba w wieku od 2-5 lat  |
| Osoba Nadzorująca | osoba odpowiedzialna za pomoc/nadzór w obsłudze systemu     |

## Aktorzy 

### Aktor-Cel:
| Aktor             | Cel |
|-------------------|-----|
| Dziecko        | zaprogramowania robota do wykonywania pewnej czynności ciagle   |
|                | nauka podstaw pogramowania                                      |
|                | zaprogramani przjescia przez robota jakiegoś pomieszczenia      |
| Osoba Nadzorująca | pomoc w obsłudze planszy i modułu wykonawczego    |
|                   | nadzór by dzieci nie zepsuły planszy etc. |


### Słownik projektowy:
|                   | Znaczenie |
|-------------------|-----------|
| Użytkownik        |  osoba korzystajaca z systemu         |
| Osoba Nadzorująca |  osoba dorosła,opiekun,osoba obeznana z obsługą         |
| Plansza           |   narzędzie do pisania programów, oparte na prostych drewnianych klockach        |
| Moduł Wykonawczy  |  dowolne urządzenie zdolne odczytać zestaw instrukcji pochodzący z serwera.         |
| Serwer            | komunikujący się z Planszą, pozwalający na przekształcenie układu klocków na zestaw instrukcji. Wystawia bezprzewodowo REST API dla modułów        wykonawczych          |
|  Klocki               | drewniane klocki służace do przekazywania instuckji serwer-moduł          | 

### User-stories:
1. Jako dziecko chce zaprogramować swojego robota by przeszedł stworzony przez ze mnie labirynt ponieważ znudził mnie już podany z robotem
(Średni)
2. Jako osoba nadzorujaca chce
4. Jako dziecko chce by robot mogł byc zaprogramowany do przejścia mojego pokoju aby
5.


### Wymagania niefunkcjonalne:

* Plansza bedzie mogła rozpoznać typ klocka to rezystorze 
* Moduł wykonawczy bedzie mogł wykonywać bardzo skomplikowane instruckje
* Możliwości zaprogramowania przez dziecko petli
