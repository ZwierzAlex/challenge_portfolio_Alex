# Task 1
## Subtask 2
9 punktów
## Subtask 3
*Cześć :smiley: Biorę udział w tym challenge'u, ponieważ po ponad dekadzie w marketingu uznałam, że czas coś zmienić. Firma w kórej pracowałam, zaczęła się bardzo mocno rozwijać, a tym samym poważnie zmieniać swoją stronę, swój sklep on-line. Dzięki czemu zostały na mnie przeniesione obowiązki współpracy z developerami zajmujacymi się tym, z devami, zajmującymi się migracją naszej strony i odkryłam, że to jest właśnie to co chcę robić "jak będę duża" :upside_down_face:! Całe życie wszyscy mi powtarzają, że czepiam się szczegółów, a ja im na to odpowiadam, że życie składa się ze szczegółów. Tak właśnie jest, jeden mały błąd może nieść za sobą olbrzymie konsekwencje :( Udało mi się znaleźć jeszcze 2 firmy, kóre akurat od podstaw budowały swoje strony, dzięki temu mogłam aktywnie uczestniczyć w testowaniu wszystkiego co tylko zostawało wprowadzane na serwery testowe. To spowodowało, że postanowiłam oddać się temu w 100%, a żeby to zrobić i móc pracować jak QA, wiedziałam, że jeszcze daleka droga przede mną. Postanowiłam więc zwolnić się z pracy i poświęcić swój czas i energię na uczenie się i rozwijanie w tym, co realnie mnie interesuje i w skórcie mówiąc- jara :satisfied:*
**Ola**
## Subtask 4 
Aplikacja służy do tworzenia i zarządzania zestawieniami graczy, meczów i rankingów. Dzięki niej można śledzić statystyki danego gracza oraz poznać podstawowe dane na jego temat, takie jak wiek, waga czy wzrost.
### Funkcjonalności aplikacji
Dodawanie gracza -działa zgodnie z założeniem.
Edytowanie danych istniejącego gracza-działa zgodnie z założeniem.
Dodawanie meczu-działa zgodnie z założeniem.
Edytowanie istniejącego meczu-działa zgodnie z założeniem.
Dodawanie raportu-działa zgodnie z założeniem.
Edytowanie istniejącego raportu-działa zgodnie z założeniem.
Zmiana języka aplikacji na angielski-działa zgodnie z założeniem.
Wszystkie powyższe funkcjonalności działają zgodnie z planem- wszytkie wielkości daje się dodawać lub edytować.
### Interfejs
Prosty, mało intuicyjny. Górne boxy z ilością meczów, graczy, raportów i akcji są nieklikalne- utrudnia to nawigację po tych wielkościach. Żeby realnie dostać się do meczów, graczy czy raportów należy kliknąć przycisk [gracze] po lewej stronie, co nie jest jasne i oczywiste. Jeśli użytkownik chce dostać się w zakładkę [ilość meczy] chce klinkąć właśnie w taką zakładkę, nie chce przechodzić przez graczy, bo nie to go interesuje, jednak nie ma innej możliwości. Jedyna szansa, żeby dostać się do meczu czy też rankingu to droga przez "Aktywność"- jeśli był to akurat ostatnio dodany mecz/gracz/ranking. Jednak kliknięcie w ostatnio dodany mecz/ranking kieruje użytkownika od razu do edycji danych. Zagospodarowanie przestrzeni strony można by było zaplanować lepiej, z mojej perspektywy jest tu dużo martontrastwa miejsca, które można by było wykorzystać do rozbudowny strony, żeby była bardziej przejrzysta, intuicyjna i przyjazna dla użytkownika.
### Błędy
1. Formularze edycji przyjmują wartości mniejsze od zera (wpisane ręcznie) w oknach dialogowych, gracz może mieć ujemną wagę, wzrost i czas.
2. Formularze edycji gracza przyjmują dowolne daty urodzenia wprowadzone ręcznie: można ustawić datę urodzenia na 01.01.0001 a można również podać datę w przyszłości np. 01.01.2050 lub datę dnia teraźniejszego np. 25.04.2023.
3. Formularze edycji w swoich polach przyjmują wszystkie istniejące znaki w tym specjalne oraz cyfry. Tak jak w przypadku imion/nazwisk/nazwy klubu czy maila można to dopuścić, tak:
- okno "numer telefonu" nie powinno dopuszczać liter ani znaków specjalnych z wyjątkiem "+" ;
- okna: "pozimo rozygrywek" , "główna pozycja gracza" , "pozycja alternatywna" , "osiągnięcia" oraz "język" nie powinny przyjmować innych wartości niż literowe;
- okno "profil facebook" powinien wymagać podania linku z facebooka, nie dowolnego ciągu znaków;
- okno "link do youtube" powinien wymagać podania linku z youtube'a, nie dowolnego ciągu znaków;
1+2+3 -> Załączony screen_1
4. Korzystając z polskiej wersji językowej przyciski odrzucające lub potwierdzające zmiany mają angielskie napisy (screen_2).
5. Korzystając z polskiej wersji językowej ikony pobierania, drukowania, wyboru kolumn i sortowania mają angielskie podpisy (film_1). 
6. Na główniej stronie znajduje się błąd w słowie "Aktywność" (screen_3).
