W oparciu o pewien projekt sensorów, chciałbym wykorzystać już gotowe rozwiązanie dla stworzenia logów oraz logiki sterowania określonych urządzeń w domu.

## jak to można wykonać?

Istnieje wiele rozwiązań gotowych, które wymagają konfiguracji.

Czy jest to możłiwe bez konfiguracji?

Myślę, że opierając takie rozwiązania na WIFI, można bazując na interfejsie REST API

połączyć co potrzeba w jeden lub wiele aplikacji, które będą spełniały określone zadania.



System powinien składać się z prostych modułów, gdzie komunikacja odbywa się w sposób prosty, 
poprzez nadawnie informacji lub odbieranie.
Nadawanie może być realizowane poprzez nadajnik, który potrzebuje 
Nadajnik od odbiornika różni się tym, że inicjuje odbieranie danych od odbiornika, poprzez nadanie

Podczasz odbierania informacji z jakiegoś urządzenia

Każde urządzenie działa w jednym z 3 trybów:

+ tylko nadawanie
+ tylko odbiorenia
+ nadawnie i odbierane



+ [out] liczba informująca o temperaturze

+ [in] włącz/wyłącz przekaźnik

+ [out/in] logger

+ [out/in] baza danych

+ [out/in] logika sterująca w zależności od danych w bazie danych







https://openenergymonitor.org/emon/
+ wireseless
- sensors are not BLE