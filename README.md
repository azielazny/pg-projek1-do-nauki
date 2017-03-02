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
0. Na slacku wyślijcie mi swoje loginy z githuba, abym was dodał do rojektu. Wtedy będziecie mogli 
klonować projekt. W przeciwnym razie będziecie musieli użyć forka.

1. sklonuj ten projekt i staraj się odświeżać ten projekt, aby mieć aktualną wersję. 
Przycisk clone or download
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
feauture-(dowolna nazwa na której pracujesz-to dla twoich zadań)

Do wdrożenia pełnego GIT Flow brakuje gałęzi release i hotfix, ale do tego dojdziemy. Przy omawianiu SCRUMa 
trochę zmodyfikujemy gałęzie i zadania.

```
git branch...
```
**W skrócie:**
Najważniejsza jest gałąź develop. Ona musi być aktualna (aktualizacja GIT PULL w miarę często).
Z tej gałęzi tworzysz gałąź faeuture-(może być twoja nazwa związana z zadaniem). 
Jak skończysz pracę nad zadaniem mergujesz swoją gałąź z developem i wysyłasz swoją gałąź na github 
Na stronie github klikasz Pull Requests zgłaszając konieczność scalenia Twojej gałęzi z developem.

ISSUES - to zadania do zrobienia oraz miejsce na komentarze i uwagi dotyczące zadań aktualnych i przyszłych.

Na stronie **Projects** w menu GITHUB jest projekt o nazwie **frontend**. To są aktualne zadania do wykonania, 
czyli  boardy, na których będziemy pracować. (osobiście wolałbym narzędzie Trello.com, ale wtedy musielibyście 
zakładać kolejne konta i połączyć je z GITHUBem) Według mnie boardy w GITHUBie są trochę upośledzone.
Wybierasz jedno, nad którym będziesz pracować. Przesuwasz na in progress.
**Biorąc zadanie musisz wejść w nie i zaznaczyć, że ty je będziesz robić. WAŻNE!**

```
BOARDY:
to do - zadania do zrobienia
blocked- zadania na później
in progress - zadania w trakcie robienia przez wybrane osoby
code review/bug reports- wysłanie kodu do sprawdzenia
done- zadanie skończone
```


UWAGA!Zadanie może się składać z kilku etapów, więc czasem warto sobie stworzyć lokalnie gałąź o nazwie 
zadania(lub story). Potem od tego zrobić mniejszy feauture i po skończeniu scalić z gałęzią zadania. 
Na końcu wysłać scalone zadanie na serwer.

###Zadania
Jednym z pierwszych zadań będzie skonfigurowanie środowiska do pracy. Przygotowałem te dane i rozpisałem 
zadania. GIT logiem lub w GITHUBie może sprawdzić postęp. To już jest zrobione.
Katalog data zawiera pociętą grafikę i screeny. 

Kolejnymi zadaniami musimy się podzielić. Na początek, ko pierwszy ten lepszy:)

###Uwagi końcowe
W normalnej pracy musicie określać czas pracy nad poszczególnymi zadaniami i ustalać priorytety zadań. 
Do tego jeszcze dojdziemy.

Teraz jedno jest istotne. Commitujcie jak najczęściej projekt. Jak macie pytania to dodawajcie etykiety 
i opisy problemów przy zadaniach. Każdy problem w kodzie można zespołowo łatwiej rozwiązać.

Na koniec uwaga. Mierzcie czas pracy nad poszczególnymi zadaniami.
```
Stosujemy zasadę. Jak nie wiecie co zrobić przez 15 minut to szukamy pomocy. Albo Slack, albo komentarz 
do zadania z etykietą zieloną "HELP WANTED"
```
Specjalnie nie robię listy rzeczy do zrobienia na zasadzie kliknij tutaj, zrób to. Zadania mają być na 
tyle dobrze zdefiniowane, abyście sami byli w zakresie określić zakres prac do wykonia. Odpowiedzi na 
większość pytań znajdziecie w materiałach, które już były.

Tylko przez praktykę można zrozumieć pewne zagadnienia.


