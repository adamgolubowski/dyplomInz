# Projekt i wykonanie stacji monitorującej wybrane parametry środowiska naturalnego na platformie Arduino.
### Autor: Adam Gołubowski, nr albumu 6311
### Promotor: mgr inż. Zbigniew Rosiek
### Warsawska Wyższa Szkoła Informatyki, 2016
---
##### Cel pracy
Celem pracy był projekt oraz wykonanie stacji służącej do pomiaru wybranych parametrów środowiska naturalnego wraz z oprogramowaniem służącym do obsługi urządzeń pomiarowych. Stacje pomiarowe i oprogramowanie składają się na system realizujący założenia monitorowania środowiska. 
##### Założenia
Przyjęto kilka istotnych założeń, które wpłynęły na kształt pracy. Po pierwsze praca miała zostać wykonana z wykorzystaniem komputera z rodziny Arduino. Ponadto założono, że urządzenie powinno umożliwiać pomiar parametrów mających wpływ na jakość powietrza. Uznano, że w ramach pracy zostanie przygotowany projekt systemu, ale również zostanie przygotowane działając urządzenie oraz oprogramowanie umożliwiające pracę systemu. Z kolei wymagania dotyczące dokładności pomiarów, kalibracji czujników i analizy uzyskanych danych uznano za wykraczające poza zakres pracy.
##### Monitorowanie jakości powietrza
Ogólna koncepcja
Wymagania
Funkcjonalne
Możliwość użycia czujników jakości powietrza
Odczytywanie danych z czujników
Rejestrowanie odczytów
Udostępnianie danych z odczytów

Poza funkcjonalne
Wykorzystanie platformy Arduino do budowy stacji
Dokładność pomiarów i kalibracja czujników – poza zakresem pracy
Praca automatyczna 
Niezawodność 
Udostępnianie informacji w standardowym formacie wymiany danych 
Projekt systemu
Stacja pomiarowa
Stacja pomiarowa – cykl pracy
Usługa sieciowa z bazą danych
Usługa sieciowa – przykładowe zapytanie GET
Aplikacja internetowa
Testy
Stacja pracowała w trybie ciągłym przez 7 dni
Automatyczne odczyty co 15 minut
Pomiar 5 parametrów  (stężenie CO, O3, obecność pyłów, temperatura, wilgotność)
Przesyłanie danych do usługi sieciowej na platformie Azure
W bazie zarejestrowano 3257 odczytów – 96% wszystkich oczekiwanych
Dane dostępne przez usługę sieciową
Aplikacja internetowa prezentująca wyniki odczytów

Plany rozwojowe
Podsumowanie
Produkty:
działający prototyp stacji pomiarowej wraz z oprogramowaniem.
usługa sieciowa (web service) wraz z bazą danych
aplikacja kliencka 