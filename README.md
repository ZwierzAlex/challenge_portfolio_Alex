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
Prosty, mało intuicyjny. Górne boxy z ilością meczy, graczy, raportów i akcji są nieklikalne- utrudnia to nawigację po tych wielkościach, a wręcz uniemożliwia dostanie się do ogólnych rankingów. Zagospodarowanie przestrzeni strony można by było zaplanować lepiej, z mojej perspektywy jest tu dużo martontrastwa miejsca, które można by było wykorzystać do rozbudowny strony, żeby była bardziej przejrzysta, intuicyjna i przyjazna dla użytkownika.
### Błędy
#### Gracze
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
6. Pokazuje się jeden błąd 403 oraz jeden błąd, kórego niestety nie potrafię opisać, ponieważ nie za bardzo umiem, dlatego też załączam screen_6. (screen_5 i screen_6).
7. Wybierając konktretnego gracza z listy graczy, użytkownik zostaje automatycznie przeniesiony do strony edycji danych wybranego przez niego gracza, uważam, że powinny się pojawić jego dane, które ewentulanie mogą być później zedytowane, jednak nie powinno się to dziać automatycznie.
8. Graczy można sortować po imieniu, nazwisku, wieku, pozycji, klubie i recencji, jednak nie ma tej możliwości w przypadku 2 ostatnich kolumn tj. mecze i raporty, co uważam, że jest również ważne.
9. Wyszukiwarka w headerze ma napis: search, pomimo wybranej wersji językowej polskiej.
#### Strona główna
10. Błąd w słowie "Aktywność" (screen_3).
11. Jeden błąd 404 (screen_4).
12. Klikając "Ostatnio stworzony lub zaktualizowany gracz/mecz/ranking" znajdujący się w "Aktywnościach" wyświetla się od razu strona edycji.
#### Mecze
13. Data meczu przyjmuje wszystkie dowolne wartości w przeszłości czy przyszłości
14. Czas gry może być wartością poniżej zera
15. Kolor koszulki przyjmuje wszystkie znaki w tym specjalne i cyfry
16. Drużyna zawodnika i drużyna przeciwnika przyjmują wszystkie znaki w tym specjalne i cyfry

13-16 -> screen_7

![screen_2](https://user-images.githubusercontent.com/131251044/234254749-4ea5b060-5018-467a-9229-0b247a1d5420.jpg)
![screen_3](https://user-images.githubusercontent.com/131251044/234254750-f9177f95-ca38-4516-852e-ec19f2c7b4e5.jpg)
![screen_5](https://user-images.githubusercontent.com/131251044/234254752-d318dfbb-212f-4ad2-9a7e-20526569c4fa.jpg)
![screen_6](https://user-images.githubusercontent.com/131251044/234254755-48c72092-159d-4ec6-84b7-077122331aa4.jpg)
![screen_4](https://user-images.githubusercontent.com/131251044/234254767-12d854ad-9d89-494d-8509-981cce92d4f5.jpg)
![screen_7](https://user-images.githubusercontent.com/131251044/234254768-10b4e397-7ce3-469a-993c-32bb6421150c.jpg)


https://user-images.githubusercontent.com/131251044/234254771-8b758f9e-fcdd-42ea-b0c5-9d2f949853d8.mp4

![screen_1](https://user-images.githubusercontent.com/131251044/234254773-db210675-5ecf-4f7e-b0f9-48b660de826a.jpg)
