Czytanie książek nie pomoże, jeśli nic nie będziecie robić. Kod sam do głowy nie wejdzie. 
To wiem z doświadczenia.

Zaczynamy!

###Zakres projektu:
Poruszamy się tylko po tym, co już znacie. Jedyna różnica to narzędzia. Będziemy używać do 
projektu GITHUBa, może Trello, gdyż warto, abyście już dziś zaczęli budować publiczne portfolio.

Przygotowanie strony dla wymyślonej firmy według grafiki wstępnie przygotowanej z tą różnicą, 
że interesuje nas wersja mobilna i tradycyjna, a mamy tylko grafiki dla dużych ekranów. Poza tym 
mamy do przygotowania obsługę logowania w JS i panel do obsługi i komunikacji z biurem firmy.

Dodelowo pewnie zrobimy koszyk zakupowy, a w dashoardzie jakiś czat, obsługę histori zamówień 
i może coś jeszcze wymyślimy.

Backendu nie będziemy poruszać. Chyba, że będzie konieczność to dodam kod php, jakąś bazę danych, 
może cron ale nie przewiduję tego na ten moment. Postaram się to ogarnąć używając JSONa.
###Technologia
Cały projekt ma się opierać na **HTML, CSS(SASS), JS+JQUERY, Bootstrap, szablonach mustache**. 
Dane będą dostarczone w formie **JSON**. Komunikacja w panelu i na stronach powinna odbywać się 
poprzez **AJAX**, aby uniknąć przeładowaywania stron. 

Do układu GRIDowego stosujemy bootstrapa 3 i bibliotekę jquery. O użyciu kolejnych bibliotek będę 
informował na bieżąco lub będą integrowane z Gruntem.

Jeśli będzie czas to ogarniemy angulara na dalszym etapie projektu.

**Projekt wymaga działającego GIT, NPM, GRUNTa. Opis konfiguracji na windowsie jest na grupie na slacku 
w materiałach, które wrzucałem.**

###Najważniejsze zasady w tym projekcie:
0. Na slacku wyślijcie mi swoje loginy z githuba, abym was dodał do projektu. Wtedy będziecie mogli 
klonować projekt i mergować zmiany. W przeciwnym razie będziecie musieli użyć forka i prosić o zatwierdzenie projektu.

1. sklonuj ten projekt i staraj się odświeżać ten projekt, aby mieć aktualną wersję. 
Przycisk clone or download. Jak będzie gotowy projekt trzeba będzie go zainstalować i zbudować.
```
git init
git clone...
npm install
grunt build
```
2. ZAŁÓŻ NOWE GAŁĘZIE I PRZEŁĄCZ SIĘ NA FEAUTURE. 

Powinieneś mieć gałęzie:
master (gałąź gotowa do umieszczenia na serwerze)
develop (gałąź deweloperska zaraz przed wydaniem) 
feature-(dowolna nazwa na której pracujesz-to dla twoich zadań)

Do wdrożenia pełnego GIT Flow brakuje gałęzi release i hotfix, ale do tego dojdziemy. Przy omawianiu SCRUMa 
trochę zmodyfikujemy gałęzie i zadania. Podobnie, jak do boardów

```
git branch...
```
**W skrócie:**
Najważniejsza jest gałąź develop. Ona musi być aktualna (aktualizacja GIT PULL w miarę często).
-Z tej gałęzi tworzysz gałąź faeture-(może być twoja nazwa związana z zadaniem). 
-Jak skończysz pracę nad jakimś etapem zadania(lub coś robisz) wysyłasz swoją wersję na GITHUB i prosisz(albo nie) o ocenę osoby z projektu wysyłając PULL REQUESTA. Swoją pracę oznaczasz etykietami.
UWAGA! Nie mergujemy zapytania (Nie dotykasz mergre pull request). 
(rzeczy umowne) 
Dodałem etykiety(LABELS):
```
FEATURE-oznacza zadanie do zrobienia
Proposal - jeśli macie jakąś propozycję modyfikacji tego, nad czym pracujecie
Need:code review - gdy skończycie i chcecie zatwierdzenia zmian
HELP WANTED-gdy potrzebna pomoc i dodajcie od razu w czym: CSS,HTML,JS
```
-Po wysłaniu ostatniej wersji kodu dodajecie prośbę o code review. Gdy dostaniecie 1-2 opinie pozytywne możecie kliknąć merge pull request z gałęzią develop i można zamknąć zadanie i pull requesta
UWAGA! Powinno być tak, że pracujecie nad 1-2 zadaniami, więc nikt z was nie powinien mieć więcje jak 1-2 Pull requesty

ISSUES - to zadania do zrobienia oraz miejsce na komentarze i uwagi dotyczące zadań aktualnych i przyszłych, aby zadanie było jasne dla każdego.

-----część na później START---
Na stronie **Projects** w menu GITHUB jest projekt o nazwie **frontend**. To są aktualne zadania do wykonania, 
czyli  boardy, na których nie będziemy teraz pracować. (osobiście wolałbym narzędzie Trello.com, ale wtedy musielibyście 
zakładać kolejne konta i połączyć je z GITHUBem). Temat boardów powróci przy omawianiu scruma
Wybierasz jedno, nad którym będziesz pracować. Przesuwasz na in progress, a potem na kolejne etapy.
**Biorąc zadanie musisz wejść w nie i zaznaczyć, że ty je będziesz robić. WAŻNE!**

```
BOARDY:
to do - zadania do zrobienia
blocked- zadania na później
in progress - zadania w trakcie robienia przez wybrane osoby
code review/bug reports- wysłanie kodu do sprawdzenia
done- zadanie skończone
```
-----część na później END---

UWAGA!Zadanie może się składać z kilku etapów, więc czasem warto sobie stworzyć lokalnie gałąź o nazwie 
zadania(lub story). Potem od tego zrobić mniejszy feauture i po skończeniu scalić z gałęzią zadania. 
Na końcu wysłać scalone zadanie na serwer.

###Zadania
Jednym z pierwszych zadań będzie skonfigurowanie środowiska do pracy. Przygotowałem te dane i rozpisałem 
zadania. GIT logiem lub w GITHUBie może sprawdzić postęp. To już jest zrobione.
Katalog data zawiera pociętą grafikę i screeny. 

Kolejnymi zadaniami musimy się podzielić. Na początek, kto pierwszy ten lepszy:)

###Uwagi końcowe
W normalnej pracy musicie określać czas pracy nad poszczególnymi zadaniami i ustalać priorytety zadań. Warto 
już teraz nad tym pomyśleć i mierzyć czas wykonywanych zadań. SCRUM

Teraz jedno jest istotne. Commitujcie jak najczęściej projekt i zakładajcie pull requesty. Jak macie pytania 
to dodawajcie etykiety i opisy problemów przy nich. Każdy problem w kodzie można zespołowo łatwiej rozwiązać.

Ja proponuję taki układ pull requesta, jeśli są problemy:
```
W tytule podawajcie numer zadania np. #9
PYTANIE
 opis zagadnienia
NASTĘPNE KROKI
 co chcę robić
OPINIA
 dlaczego tak?
```
Ważne!
```
Stosujemy zasadę. Jak nie wiecie co zrobić przez 15 minut to szukamy pomocy. Albo Slack, albo komentarz 
do pull requesta z etykietą zieloną "HELP WANTED"
```
Specjalnie nie robię listy rzeczy do zrobienia na zasadzie kliknij tutaj, zrób to. Zadania mają być na 
tyle dobrze zdefiniowane, abyście sami byli w zakresie określić zakres prac do wykonia. Odpowiedzi na 
większość pytań znajdziecie w materiałach, które już były lub możecie dopytać przy zadaniu lub w pull request z numerem zadania np #3.

Tylko przez praktykę można zrozumieć pewne zagadnienia.

Małe WIKI jest dodane

##Małe ale jako uwaga na marginesie

**Wgrałem 2 branche stworzone lokalnie na kompie CUT-GRAPHICS i FILES-STRUCTURE. Powinienem najpierw u siebie połączyć te gałęzie i wgrać DEVELOPA do repo na githubie. Mniej gałęzi byłoby w repo. Poza tym już pewnie sam bym rozwiązał kilka problemów, jakbym miał konflikty z developem. Branche lokalne wgrywa się często jak ma się problem do wglądu dla innych, ale to też zależy od firmy i zasad ustalonych w projekcie. Później dobrze jest czyścić zawartość**

**UWAGA! Czcionka ma się uniwersalnie dopasowywać. Stosujemy standardowe rozmiary dla bootstrapa. Rozmiary podajemy w jednostkach dynamicznych em,rem lub procent. Nie narzucam rozmiarów. (1em=16px) Jak będą gotowe podstrony to wybierzemy sposób prezentacji headera i footera(będzie okazja do dyskusji). Oczywiście czyjaś praca wyleci częściowo z projektu, ale tu chodzi o naukę m.in znaczników HTML5.**
