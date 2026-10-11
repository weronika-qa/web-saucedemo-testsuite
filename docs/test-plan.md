\# Plan Testów – Wyszukiwarka Booking.com



\## 1. Wstęp

Głównym celem działań testowych jest dostarczenie interesariuszom informacji o jakości dostarczanego produktu. Celem planu testów jest zapewnienie jakości i prawidłowego działania wyszukiwarki dostępnej na stronie \*\*booking.com\*\*. Testy mają na celu sprawdzenie funkcjonalności, wydajności oraz użyteczności wyszukiwarki, aby zapewnić użytkownikom bezproblemowe korzystanie z serwisu. W przygotowanym dokumencie zostały zebrane kluczowe informacje na temat działań testowych, wyszczególnione wszystkie komponenty oprogramowania poddawane weryfikacji oraz typy testów, jakie zostaną przeprowadzone.



\---



\## 2. Zakres Testów



\### Realizowane typy testów:

\* Jednostkowe

\* Funkcjonalne

\* Wydajnościowe



\### Typy testów, które NIE będą przeprowadzane:

\* \*\*Automatyczne\*\* – brak wystarczającego budżetu na etapie związanym z testowaniem oprogramowania.



\---



\## 3. Przedmiot Testów

Komponentem poddawanym testom jest \*\*wyszukiwarka booking.com\*\* z uwzględnieniem całej logiki filtrowania w odpowiednich polach.



\---



\## 4. Kryteria Zaliczenia / Nieuzyskania Zaliczenia



\* \*\*Zaliczenie:\*\* Wszystkie przypadki testowe zakończone sukcesem; brak krytycznych błędów.

\* \*\*Niezaliczenie:\*\* Wykrycie krytycznych błędów (np. brak możliwości wyszukiwania, nieprawidłowe wyniki, niedziałające filtry) lub wystąpienie więcej niż 5 błędów o wysokim priorytecie.



\---



\## 5. Kryteria Wejścia i Wyjścia



\### 5.1. Kryteria Wejścia

\* Zdefiniowane wymagania biznesowe i techniczne (dokumentacja).

\* Gotowy moduł wyszukiwarki dostępny na środowisku testowym.

\* Przygotowane przypadki testowe.



\### 5.2. Kryteria Wyjścia

\* Przeprowadzenie wszystkich zaplanowanych testów.

\* Naprawienie wszystkich błędów krytycznych i o wysokim priorytecie.

\* Spełnienie przez komponenty wszystkich ustalonych założeń zgodnie z dokumentacją.

\* Wygenerowanie raportu końcowego z przeprowadzonych testów.



\---



\## 6. Lista Wymagań Funkcjonalnych do Przetestowania

1\. Wprowadzanie kryteriów wyszukiwania (miejsce, data, liczba osób).

2\. Wyświetlanie wyników zgodnie z oczekiwanymi kryteriami.

3\. Działanie filtrów (cena, liczba gwiazdek, typ obiektu).

4\. Działanie sortowania (wg oceny, odległości, opinii).

5\. Wyświetlanie szczegółowych informacji o obiektach (zdjęcia, opis, oceny, dostępność).

6\. Obsługa błędów lub niepełnych danych wejściowych.

7\. Kompatybilność z różnymi przeglądarkami i urządzeniami mobilnymi.

8\. Szybkość działania wyszukiwarki i ładowania wyników.



\---



\## 7. Środowisko Testowe

\* \*\*Systemy operacyjne:\*\* Windows, macOS, Linux, Android, iOS

\* \*\*Przeglądarki:\*\* Chrome, Edge, Mozilla Firefox, Opera, Brave, Safari

\* \*\*Urządzenia:\*\* Komputer, laptop, tablet, smartfon

\* \*\*Baza testowa:\*\* Środowisko testowe z przygotowaną bazą danych symulującą rzeczywiste warunki działania.



\---



\## 8. Harmonogram Testów

\* \*\*Etap 0:\*\* Weryfikacja funkcjonalności w oparciu o User Story (dokumentacja) – \*1 dzień\*

\* \*\*Etap 1:\*\* Przygotowanie przypadków testowych i środowiska testowego – \*1 tydzień\*

\* \*\*Etap 2:\*\* Testy funkcjonalne – \*2 tygodnie\*

\* \*\*Etap 3:\*\* Testy wydajnościowe i użyteczności – \*2 tygodnie\*

\* \*\*Etap 4:\*\* Raportowanie i weryfikacja błędów – \*1 tydzień\*

\* \*\*Etap 5:\*\* Testy regresyjne – \*2 dni\*



\---



\## 9. Raport z Testów

Raport końcowy będzie zawierał:

\* Plan testów

\* Listę przypadków testowych i ich wyniki (zaliczone / niezaliczone)

\* Listę wykrytych błędów wraz z ich priorytetami

\* Wnioski i rekomendacje



\---



\## 10. Lista Narzędzi

\* \*\*Zarządzanie testami:\*\* Jira, TestLink

\* \*\*Automatyzacja:\*\* Selenium, Appium

\* \*\*Testy wydajnościowe:\*\* Postman, JMeter, LoadRunner

\* \*\*Raportowanie błędów:\*\* Jira, TestLink, Bugzilla



\---



\## 11. Zarządzanie Incydentami / Błędami

Wszystkie wykryte błędy będą zgłaszane i śledzone w programie \*\*JIRA\*\*.



\### Proces zarządzania błędami:

1\. \*\*Zgłoszenie błędu\*\* – dokładny opis oraz załączniki (zrzuty ekranu, logi, wideo).

2\. \*\*Nadanie priorytetu\*\* – Krytyczny, Wysoki, Średni, Niski.

3\. \*\*Naprawa błędu\*\* – realizowana przez zespół deweloperski.

4\. \*\*Weryfikacja\*\* – re-test naprawionego błędu przeprowadzony przez zespół testerski.



\---



\## 12. Role i Odpowiedzialności

\* \*\*Kierownik testów:\*\* Planowanie i nadzorowanie procesu testowego.

\* \*\*Testerzy:\*\* Przygotowanie przypadków testowych, przeprowadzanie testów, raportowanie błędów.

\* \*\*Deweloperzy:\*\* Naprawa zgłoszonych błędów.

\* \*\*Analityk biznesowy:\*\* Weryfikacja zgodności wyników z wymaganiami biznesowymi.

