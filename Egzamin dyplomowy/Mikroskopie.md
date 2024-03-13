- wiązki elektronowej 
	- SEM
	- TEM 
- siły atomowe oraz zjawiska tunelowania
	- AFM
	- STM

## SEM

Schemat przejścia wiązki elektronów przez próbkę w SEM

![[Pasted image 20221220220259.png]]

![[Pasted image 20240203233002.png]]
Schemat mikroskopu SEM

![[Pasted image 20221220220456.png]]

![[Pasted image 20240203233037.png]]


Możemy mierzyć:

- elektrony wtórne (secondary electrons, SE)
- elektrony wtórnie rozproszone (back scattered electrons, BSE)
- promienie x, charakterystyczne dla przeskoku elektronów z powłoki walencyjne na niższą, z której wybito elektron


![[Pasted image 20240203233127.png]]

Badana próbka musi spełniać następujące warunki:

- musi mieć odpowiednią konduktywność elektryczną - dielektryki dają dupy
- powinna mieć wysoki współczynnik emisji wtórnej - nie rozpraszać wiązki
- musi dać się dobrze zamocować na stoliku - proszki, preparaty biologiczne (próżnia przeszkadza)

Gdy próbka jest nieprzewodząca, należy ją pokryć cienką warstwą (do 90nm) metalu - Au, Pt lub warstwą węgla, historycznie również Cu.

SEMem można mierzyć topografię oraz skład próbki (TOPO/COMPO)

Rozdzielczość - do 3nm

## TEM vs SEM

TEM  - operuje na wiązce elektronów, większa rozdzielczość

Porównanie SEM/TEM

| |SEM|TEM|
|-|-|-|
|typ elektronów| rozproszone, odbite, "skanujące"| przechodzące|
|napięcie przyspieszające| 1-30kV| 60-300kV|
|grubość próbki| obojętnie| **<150nm** |
|informacja| obraz 3D powierzchni| obraz projekcyjny 2D mikrostruktury|
|max. powiększenie| 1-2 miliony| >50 miliony|
|pole widzenia| duże| ograniczone|
|rozdzielczość  | **3nm** | **0.1nm** |
|formowanie obrazu| elektrony zliczanie przez detektory, komputer wyświetla obraz| bezpośrednie obrazowanie na ekranie fluorescencyjnym lub ekranie komputera z CCD|
|działanie/obsługa| łatwy w użyciu, względnie mało skomplikowane przygotowanie próbki| pracochłonne przygotowanie próbki, używanie wymaga przeszkolenia|
|układ optyczny| formowanie wiązki przed próbką, detektory przed próbką (zbierają "odbite") | układ optyczny przez i za próbką, ekran fluorescencyjny za próbką|

Budowa TEM:

- Działo elektronowe - na szczycie kolumny, z wolframu 
- soczewki elektromagnetyczne
- próbka - cienka
- dalszy układ optyczny - dostrajamy wiązkę 
- ekran fluorescencyjny

Przygotowanie próbek TEM:

- mechaniczne
	- ultramikrotomia - cięcie diamentowym ostrzem
	- łamanie, kruszenie, polerowanie mechaniczne
- mechaniczno-chemiczne
	- skoncentrowana wiązka jonów (FIB)
	- trawienie chemiczne
	- polerowanie elektrochemiczne

Badanie materiałów a pomocą STM i AFM

STM - skaningowy mikroskop tunelowy. Służy do badania materiałów przewodzących w nanoskali. Wykorzystuje zjawisko tunelowania elektronów między igłą pomiarową a próbką, po przyłożeniu napięcia rzędu kilku woltów. Igła pomiarowa powinna mieć koniec średnicy rzędu nanometrów (idealnie by było jeden atom ale tak nigdy nie jest). Gdy odległość miedzy igłą a próbką jest od 0.4 do 0.7 nm, to elektron przeskakuje przez barierę potencjału w wyniku tunelowania (emisji polowej).

W STM stosowane są dwa mody pomiarowe:

- mod stałej odległości - stała odległość sondy podczas ruchu w płaszczyźnie XY - rejestruje się zmiany prądu tunelowego między sondą a próbką, który pozwala odwzorować kształt powierzchni. Stosowany jest do płaskiej powierzchni. Daje wysoką rozdzielczość obrazu. Pozwala na dużą szybkość skanowania. 
- mod stałego prądu - stały prąd między sondą a próbką - odległość między igłą próbką regulowane jest tak, aby zachować stałą wartość prądu - obraz powierzchni próbki powstaje na podstawie zarejestrowanych wychyleń igły skanującej. Pozwala na dobre odwzorowanie topografii powierzchni. Daje małą rozdzielczość poziomą obrazu.

`rysunek STM w zeszycie (ważne: napięcie polaryzacyjne)`

![[Pasted image 20230212234212.png]]

Wady metody STM:

- możliwość wykonywania pomiarów tylko dla materiałów przewodzących
- wpływ kształtu sondy (igły) skanującej na otrzymywane wyniki
- duża czułość na wstrząsy mechaniczne i akustyczne (silna zależność wartości prądu tunelowego od odległości między igłą a próbką)

Ostrza są wolframowe. Robi się je  metodą wytrawiania.

AFM - mikroskop sił atomowych - pozwala badać powierzchnie materiałów dielektrycznych. Ostrze o wyglądzie piramidy z kwadratem w podstawie. 

`rysunek AFM (ważne: element piezoelektryczny)`

![[Pasted image 20230212234228.png]]

`wykresy siła-odległość`

![[Pasted image 20230212234237.png]]

![[Pasted image 20230212234245.png]]

mod kontaktowy, przerywanego kontaktu, bezkontaktowy

`inny schamte AFM (laser)`

![[Pasted image 20230212234301.png]]

Pomiary o wysokiej rozdzielczości wykonywane są najczęściej w ultra wysokiej próżni (UHV)

Zalety AFM:

- atomowa zdolność rozdzielcza
- można badać przewodniki, półprzewodniki i izolatory

Mody pracy:

- stałoprądowy - belka nie jest wprowadzona w wibracje
	- mod kontaktowy - stosowany jest do powierzchni atomowo gładkich oraz chropowatych a jego wadą jest możliwość uszkodzenia powierzchni próbki.
- zmiennoprądowe - belka wibruje z określoną częstotliwością
	- mod przerywanego kontaktu (chwilowokontaktowy) - małe jest ryzyko uszkodzenia powierzchni próbki i może być stosowany do tak delikatnych próbek, jak np. białka
	- mod bezkontaktowy - korzystamy kiedy próbka jest silnie reaktywna i może reagować z krzemem w igle

Zastosowania AFM:

- do badania żywych preparatów biologicznych w środowisku zbliżonym do naturalnego ( np. w wodzie)
- do pomiarów topograficznych
- do badania właściwości mechanicznych próbki takich jak : elastyczność, siła adhezji, tarcie

Artefakty w AFM:

- zmiany geometrii ostrza 
	- urwanie ostrza
	- pochwycenie - przyklejenie materiału do ostrza
	- stępione ostrze
-  odwzorowanie kształtu ostrza
	- Zbyt duże ostrze - np. jak jest wąski pik to się robi szeroka piramida
- jakiś tam dryf. Nie powiedział o nim za wiele
- kierunek skanowania - jak zmieniamy kierunek skanowania to możemy zobaczyć czy mamy np. artefakt związany ze zbyt dużym ostrzem
- zakrzywienie ruchu ostrza
- adsorpcja wody na powierzchni próbki