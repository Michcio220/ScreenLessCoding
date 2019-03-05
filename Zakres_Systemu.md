# Zakres Systemu - Screenless Coding 2

Wersja 0.1

### Ogólny opis:
System umożliwiającego naukę programowania dla dzieci bez użycia ekranów.Cały system jest podzielony na trzy głowne cześci plansza,serwer i moduł wykonawczy.Plansza jest podłoczona do serwera który przekazuje  instrukcje do modułu wykonawczego bedącego albo prostą gra lub robotem(np. robot Lego).Po ustawnieniu klocków na planszy dana instrukcja zostaje przekazana przez serwer do modułu wykonawczego , ktory nastepnie wykonuje te instrukcje.Klocki są bezpieczne w użyciu przez małe dzieci, nie wymaga sie wpasowywania klocków  w jakis sposób(sposób użycia nie może być za bardzo skomplikowany).Kilka przykładowych instrukcji to "przejdż 10 kroków do przodu", "podnieś rece", robienie jakieś czynności w petli.

### Aktorzy systemu:

| Aktor             | Opis |
|-------------------|------|
| Użytkownik        |   osoba w wieku od 2 do 5+ lat  |
| Administrator     | osoba odpowidzialna za prawidłowe działania serwera     |
| Osoba Nadzorująca | osoba odpowiedzialna za pomoc/nadzór w obsłudze systemu     |

### Aktor-Cel:
| Aktor             | Cel |
|-------------------|-----|
| Użytkownik        | nauczenie sie podstaw programowania    |
| Administrator     | nadzorowanie systemu, naprawa zawiszeń w systemie    |
| Osoba Nadzorująca | pomoc w obsłudze planszy i modułu wykonawczego    |


### Słownik projektowy:
|                   | Znaczenie |
|-------------------|-----------|
| Użytkownik        |  osoba korzystajaca z systemu         |
| Administrator     |  osoba nadzorująca serwer         |
| Osoba Nadzorująca |  osoba dorosła,opiekun         |
| Plansza           |   narzędzie do pisania programów, oparte na prostych drewnianych klockach        |
| Moduł Wykonawczy  |  dowolne urządzenie zdolne odczytać zestaw instrukcji pochodzący z serwera.         |
| Serwer            | komunikujący się z Planszą, pozwalający na przekształcenie układu klocków na zestaw instrukcji. Wystawia bezprzewodowo REST API dla modułów        wykonawczych          |
|  Klocki               | drewniane klocki służace do przekazywania instuckji serwer-moduł          | 

### Wymagania niefunkcjonalne:

* Plansza bedzie mogła rozpoznać typ klocka to rezystorze 
* Moduł wykonawczy bedzie mogł wykonywać bardzo skop 
