# Balistyka, czyli dlaczego ziemniak nie leci prosto
Balistyka- (gr.ballein "rzut") jest nauką zajmującą się miotaniem oraz ruchem pocisków i rakiet. Pełne zrozumienie tematu wymaga znajomości matematyki, fizyki areodynamiki oraz innych dziedzin. Wątek ten ma na celu odpowiedzieć w przystępny sposób czemu nasz ziemniak nie leci prosto oraz co zrobić aby trafiał tam, gdzie chcemy.
## Spis treści
1. [Trochę teorii- czyli niezbędne podstawy aby jak kolwiek ogarnąć temat](#1.Teoria)
2. [Miary kątowe](#2.Miary-kątowe)
3. [Lunety i inne celowniki optyczne](#3.Lunety-i-inne-celowniki-optyczne)
4. [Obliczanie odległości do celu](#4.Określanie-odległości-do-celu)
5. [Obliczanie odległości do celu-zadania](#5.Określanie-odległości-do-celu-zadania)
6. [Przyjmowanie poprawek na strzał](#6.Przyjmowanie-poprawek-na-strzał)
7. [Przyjmowanie poprawek na strzał-zadania](#7.Przyjmowanie-poprawek-na-strzał-zadania)
8. [Rozwiązania zadań z zakresu oblicznia odległości i przyjmowania poprawek](#8.Rozwiązania-zadań-z-zakresu-oblicznia-odległości-i-przyjmowania-poprawek)

## 1.Teoria
Pomimo tego, że strona ta ma w jak najbardziej przystępny sposób wyjaśnić, jak to się dzieje że nasz ziemniak leci do celu a nie robi fikołka w locie, jest to nie możliwe bez znajomości podstaw fizyki oraz matematyki. Będzie to kluczowe w dalszych etapach podczas obliczania odległości do celu oraz poprawek na strzał. 
### Podstawy matematyczne 
Dawno temu Galileusz powiedział "Matematyka jest alfabetem, przy pomocy którego Bóg opisał wszechświat"... Są to naprawdę zacne słowa do momentu, w którym nie musimy liczyć równania długiego na 2km zawierającego 20 pochodnych i 40 całek. Na szczęście podstawy matematyki, które są wymagane aby celnie miotać ziemniakmi są sporo prostrze. Jeżeli ktoś w szkole siedząc na matematyce zastanawiał się na co mu te wszystkie sinusy cosinusy i inne rzeczy przydadzą się w życiu to odpowiadam, że właśnie tutaj. Można stwierdzić że właściwie całe określanie odległości oraz branie poprawek opiera się na trygonometrii tzn.sinusy, cosinusy, tangensy, trójkąty podobne i wiele innych. W tej części postaram się wyjaśnić cały wymagany aparat matematyczny.

#### Sinus
Definicja mówi że sinus jest to stosunek przyprostokątnej do przeciwprostoktnej trójkąta. Mówiąc jaśniej sinus danego kąta (tutaj roboczo nazwijmy go α) jest równy przyprostokątnej (jeden z boków leżący przy kącie prostym, w naszym przypadku bok B) leżącej na przeciwko kąta α podzielonej przez przeciwprostokątną (bok który nie ma styczności z kątem prostym, w naszym przypadku bok C). W praktyce łatwo to zapamiętać ponieważ w trójkącie szukamy dużej kosy lub cyfry 7 w trójkącie.

![trygonometria](https://github.com/user-attachments/assets/420d7190-0d6c-4c05-b77c-15bd7b77272b)

#### Cosinus 
Drugą funkcją podobną do sinusa jest Cosinus. Definicja mówi że cosinus jest to stosunek długości przyprostokątnej przyległej do kąta alfa do długości przeciwprostokątnej. Z polskiego na nasze oznacza to że w trójkącie szukamy wierzchołka z katem który nas interesuje. Następnie bierzemy odcinek który łączy nasz wierzchołek z kątem prostym (w naszym przypadku bok A)  i dzielimy go przez odcinek który nie dotyka kąta prostego (w naszym przypadku bok C). 

![trygonometria](https://github.com/user-attachments/assets/fade0c80-6c0a-4943-9078-04481f6eb3a5)

#### Tangens i Cotangens
Dwie ostatnie funkcje które będą nas z tego interesować są tangens i cotangens. Zostaną omówione one wspólnie ponieważ cotangens jest odwrotnością tangensa. Nie wgłębiając się w definicje Tangens danego kąta (ponownie roboczo nazwiemy go α) to długość przyprostokątnej która nie dodtyka interesującego nas kąta (w naszym przypadku bok B) podzielona przez przyprostokątną która już dotyka interesującego nas kąta (w naszym przypadku bok A). Dla cotangensa będzie na odwrót czyli dzielimy długość przyprostokątnej, która dotyka interesujący nas kąt, prze długość przyprostokątnej, która już go nie dotyka

![trygonometria](https://github.com/user-attachments/assets/fade0c80-6c0a-4943-9078-04481f6eb3a5)

#### Trójkąty podobne
O ile bez wcześniejszych funckji można sobie jako tako poradić tak bez znajomoći trójkątów podobnych obliczenia będą niezwykle ciężkie o ile nie niemożliwe. Ale do brzegu, o trójkątach podobnych mówimy wtedy jeżeli jeden jest większą kopią drugiego - tak możemy powiedzieć w bardzo dużym uproszczeniu. Definicja z wikipedii mówi **"Jeśli trójkąty są podobne, to: wszystkie szczególne odcinki jednego trójkąta (wysokości, środkowe, odcinki dwusiecznych, promienie kół: opisanego i wpisanego itp.) są proporcjonalne do odpowiednich odcinków drugiego trójkąta w tej samej skali. stosunek ich pól jest równy kwadratowi skali podobieństwa"** Oznacza to tyle że jeżeli mamy dwa trójkąty jeden o bokach A, B, C oraz drugi o bokach D, E, F Trójkąty są podobne jeżeli wszystkie boki drugiego trójkąta są x razy większe lub mniejsze od boków drugiego trójkąta. 

Oczywiście jest to bardzo duże uproszczenie i sporo matematyków lub osób które mają trochę większe pojęcie o matematyce dostaje zawału, gdy to widzi ale na ten moment tyle nam wystarczy. Jest tak, ponieważ w balistyce głównie będziemy korzystać z trójkątów podobnych, które jednocześnie są trójkątami prostokątnymi.

![trojkatypodobne](https://github.com/user-attachments/assets/8c880a7a-e08f-438f-9b08-9b2bd298ae49)

Spójrzmy na obrazek powyżej. Przedstawia on dwa trójkąty podobne jedne o bokach A, B, C, natomiast drugi o bokach A+X, Z, C+Y. W takim przypadku aby bardziej to uzmysłowić możemy przyjąć, że trójkąt A, B ,C ma boki równe 1. W takim wypadku jeżeli odcinek X miał by również długość 1 dla większego trójkąta odcinek A+X ma długość 2. W takim razie skoro podstawa większego trójkąta jest 2 razy dłuższa od podstawy mniejszego, reszta odcinków będzie również 2 razy dłuższa. Przykładowo, skoro odcinek B ma długość 1 to odcinek Z jeżeli będzie 2 razy dłuższy będzie miał długość 2.

Analogicznie jeżeli powiedzmy większy trójkąt będzie miał boki o długości A+X=2, Z=2, C+Y=2, natomiast bok A mniejszego trójkąta będzie miał długość 0,25 to inne boki również będą 8 razy mniejsze.

### Podstawy Fizyczne 
Jeżeli podstawy matematyczne mamy już za sobą można przejść do podstaw fizycznych. Tutaj sprawa zaczyna się delikatnie komplikować ponieważ zagadnienia takie jak areodynamika czy balistyka do najłatwiejszych nie należą jednak warto je chodź trochę liznąć aby wiedzieć właśnie czemu nasz przykładowy "ziemniak" nie robi fikołka w locie i nie próbuje trafić osoby która nim rzuciła.

#### Areodynamika
Na samym początku kiedy rzucimy naszym ziemniakiem powinniśmy sobie zadać pytanie czemu on w ogóle unosi do góry a następnie spada. Przecież jeżeli go delikatnie zepchniemy ze stołu zaczyna on od razu spadać. No włąśnie tutaj musimy sobie odpowiedzieć na pytanie jak to się dzieje że cokolwiek zaczyna latać. Powiedzmy że żeby nasz ziemniak zaczął latać mamy trzy główne sposoby.

Pierwszym sposobem możemy kojarzyć głównie z Elonem Muskiem i lotami kosmicznymi. Kiedy oglądamy takie starty możemy zobaczyć że rakieta ma bardzo duży silnik i startuje ona pionowo w górę. No właśnie czyli patrząc na to możemy stwierdzić że jeżeli naszemu ziemniakowi nadamy dość dużą siłę skierowaną pionowo w górę to zacznie się on unosić. Po części tak jest przykładowo wystarczy wziąć piłkę oraz ją podrzucić. Jeżeli siła którą damy piłce będzie duża zacznie się ona wznosić, jednak po pewnym czasie spadnie. Działa tutaj siła oporu powietrza oraz siła grawitacji, które po pewnym czasie niwelują włożoną w piłkę siłe. 

Drugi sposób polega na wykorzystaniu powierzchni nośnych i odpowiedniej siły ciągu. Bardziej jaśniej, jeżeli porównamy samolot i samochód możemy dojść do szokującego odkrycia mianowicie......samolot lata a auto jeździ. No właśnie tylko dlaczego, przecież obydwa urządzenia mają silnik i poruszają się ze sporą prędkością. Mimo to przy standardowj jeżdzie samochód nie wykazuje chęci do unoszenia się. Dzieje się to przez wykorzystanie w samolocie powierzchni nośnych jakimi są skrzydła. Przez połączenie ciągu (dużej prędkości) oraz odpowiedniego kształtu skrzydła otrzyujemy siłę ciągłą.  

## 2.Miary kątowe




## 3.Lunety i inne celowniki optyczne



## 4.Obliczanie odległości do celu



## 5.Obliczanie odległości do celu-zadania



## 6.Przyjmowanie poprawek na strzał



## 7.Przyjmowanie poprawek na strzał-zadania




## 8.Rozwiązania zadań z zakresu oblicznia odległości i przyjmowania poprawek
