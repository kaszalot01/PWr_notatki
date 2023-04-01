SEM - scanning electron microscope
Konstrukcja - 1963 - Cambridge

Trzy rodzaje:

- wysokoenergetyczne (15-40 kV)
- niskoenergetyczne (100-500 V)
- zwierciadlane (~0V)

Schemat przejścia wiązki elektronów przez próbkę w SEM
![[Pasted image 20221220220259.png]]


Schemat mikroskopu SEM
![[Pasted image 20221220220456.png]]

Budowa mikroskopu:

- źródło elektronów
- układ formowania wiązki
- komora próżniowa i układ montowania próbki

Wiązka skanuje obszar 10 um x 10 um

Standardowy ekran SEM ma powierzchnie 10 cm x 10 cm

**<ważne>**

"Sygnały" pracy, mierzone w warstwie do 50nm od powierzchni (czyli chyba o tym co mierzymy):

- Elektrony wstecznie rozproszone 
- Elektrony wtórne

$\eta=\frac{I_{EWR}}{I_0}$ - współczynnik wstecznego rozpraszania, zazwyczaj $<0.6$

I - natężenia: wiązki pierwotnej i wiązki elektronów wstecznie rozproszonych

**</ważne>**

energie i liczności różnych elektronów
![[Pasted image 20221220220737.png]]

Elektrony, których nie mierzymy odfiltrowujemy siatkami, naelektryzowanymi tak aby odpychały elektrony o mniejszych energiach. Jak mierzymy sygnał EWR to odfiltrowujemy EW, których E<50eV.

Badana próbka musi spełniać następujące warunki:

- musi mieć odpowiednią konduktywność elektryczną - dielektryki dają dupy
- powinna mieć wysoki współczynnik emisji wtórnej - nie powinny rozpraszać wiązki
- musi dać się dobrze zamocować na stoliku - proszki, preparaty biologiczne (próżnia przeszkadza)

Gdy próbka jest nieprzewodząca, należy ją pokryć cienką warstwą (do 90nm) metalu - Au, Pt lub warstwą węgla, historycznie również Cu.

charakterystyka sygnału EWR - zależność od liczby atomowej
![[Pasted image 20221220220845.png]]

Do liczby atomowej 40, współczynnik $\eta$ zależy liniowo od liczby atomowej. Można tym rozróżniać atomy (?).

zależność eta od grubości warstwy
![[Pasted image 20221220221026.png]]

Dla bardzo cienkich warstw większa część elektronów przejdzie przez próbkę. Od pewnej grubości nie przechodzi już nic. Chcemy, żeby próbka była grubsza, żeby mieć pełny zakres sygnału.

Współczynnik $\eta$ nie zależy od energii elektronów

zależność eta od kąta padania wiązki
![[Pasted image 20221220221132.png]]

Coś o tym, że ruszamy próbką, nie mikroskopem. (?)

**<ważne>**

Efekty dzięki którym powstaje kontrast topograficzny w SEM

Sytuacja wyjściowa:
![[Pasted image 20221220222130.png]]

- efekt brzegowy - przy krawędzi, jeden detektor dostaje więcej bo wiązka nagle nie musi przechodzić z powrotem przez materiał 
![[Pasted image 20221220222220.png]]
- efekt pochłaniania - za uskokiem, jeden detektor nie dostaje sygnału bo cały jest rozpraszany na wzniesieniu
![[Pasted image 20221220222302.png]]
- efekt zacieniania - za uskokiem ale dalej, jeden detektor dostaje mniej sygnału bo część jest rozpraszana na krawędzi wzniesienia
![[Pasted image 20221220222324.png]]
**</ważne>**

Rodzaje detektorów

Rodzaj układu detekcyjnego określony jest przez:

- typ detektora
- liczba detektorów
- rozmieszczenie względem badanej próbki

Najczęściej stosowane w SEM typy detektorów:

- scyntylacyjne
- półprzewodnikowe
- konwertery EWR/EW

Detektor scyntylacyjny - zamiana elektronów na impulsy świetlne 
schemat - niezbyt omówiony został
![[Pasted image 20221220221226.png]]

Zalety detektorów półprzewodnikowych:

- małe rozmiary
- łatwość rozmieszczenia i montażu
- niski koszt
- przebieg charakterystyki wzmocnienia jest linowy
- możliwość budowania układów wielodetektorowych (np. pod różnymi kątami)
- możliwość realizacji zadanych algorytmów mieszania sygnałów (mod TOPO, mod COMPO)

**Mody TOPO i COMPO ważne**

TOPO - topografia
COMPO - kompozycja (skład materiału)

Zwykle albo jedno albo drugie

Przygotowanie próbki:

1. krzemowe podłoże
2. nałożona żywica, utwardzana tylko w niektórych miejscach
3. nieutwardzona żywica wymyta
4. trawienie (chyba tych niezabezpieczonych miejsc)

Wielkości mierzone:

- $TOPO=D_a-D_b$
- $COMPO=D_x+D_y$

Generacja obrazu w TOPO dla dwóch detektorów:
Dla pewnej wartości $TOPO=D_a-D_b$ malujemy średnią szarość. Dla większych TOPO malujemy na jaśniej a dla mniejszych ciemniej. 

Rekonstrukcja obrazu powierzchni próbki jest możliwa, gdy stosunek sygnału do szumu jest większy od 5.
$$\frac{S}{N}>5$$
W modzie TOPO detektory ustawiane nisko nad próbką, pod kątem $<30^o$ do podłoża. 
W modzie COMPO ustawiane wysoko, pod kątem $>60^o$
![[Pasted image 20221220221344.png]]

W rzeczywistości algorytmy są dużo bardziej skomplikowane.

Czynniki wpływające na sygnał EWR:

- układ detekcji
- algorytm mieszania sygnałów
- eliminacja artefaktów

Strategia detekcji:

- separacja modów
	- COMPO
		- metoda linearyzacji
		- metoda symulacji kolorów
	- TOPO
		- trójwymiarowa rekonstrukcja

Artefakty - powstają na drodze tworzenie obrazu w SEM, ale nie mają nic wspólnego z rzeczywistymi właściwościami próbki. Rozróżniamy artefakty związane z:

- układem detekcyjnym
- energią wiązki elektronowej (większa energia, głębszy obszar oddziaływania)
- niedoskonałą separacją informacji o topografii i kompozycji

Zestaw pytań na temat SEM:

- klasyfikacja metod badania materiałów
- budowa i zasada działania mikroskopu SEM
- charakterystyka sygnału EWR w SEM
- rodzaje detektorów w SEM
- jak powstaje kontrast topograficzny w SEM (pokazać na rysunku)
- porównać mody TOPO i COMPO w SEM
- krótka charakterystyka artefaktów w SEM

Zastosowanie SEM:

- nauka
- przemysł
- medycyna

Porównanie mikroskopii - slajd z rozdzielczościami, którego nie zdążyłem przepisać

Podsumowanie SEM:

- zarys historii
	- 1931, Max Knoll i Ernst Ruska, pierwszy TEM
	- 1935, Max Knoll, pierwszy SEM
	- 1965, Cambridge instrument company, pierwszy komercyjny SEM
- budowa
	- działo elektronowe - generowanie wiązki elektronów
		- d.e. z emisją polową (FEG) - tworzy silne pole elektryczne, aby odciągnąć elektrony od atomu
			- ostra igła wolframowa, średnica wiązki wychodzącej z działa - 5nm
		- d.e. z emisją polową Schottky'ego - podobne jak wyżej; ostrze pokryte $ZrO_2$ 
		- termiczne d.e. - termoemisja
			- wolfram
			- $LaB_6$ 
	- układ soczewek - formowanie wiązki
	- detektory
		- ETD
			- siatka kolektora
			- scyntylator
			- fotopowielacz
		- TLD
			- umieszczony nad soczewką
			- ultra wysoka rozdzielczość (UHR)
	- sygnał 
		- elektrony wtórne - niskoenergetyczny kontrast kompozycyjny
		- elektrony wstecznie rozproszone (BES - back-scattered electrons) - wysokoenergetyczny kontrast kompozycyjny
		- charakterystyczne promieniowanie rentgenowskie (EDS) - do składu materiałowego
	- wszystko w wysokiej próżni
- działanie
	- skanowanie linia po linii
	- napięcie przyspieszające wpływa na penetracje wiązki i głębie ostrości - im większe napięcie tym głębiej zaglądamy
	- en.working distance - odległość między obiektywem a próbką - też coś tam wpływa na głębie ostrości ale mało
- przygotowanie próbek
	- aluminiowe, ruchome uchwyty/stoliki 
	- przytwierdzenie próbki musi przewodzić prąd (taśma węglowa, farba/taśma przewodząca), albo zaciski/imadełka
	- próbki muszą być przewodzące lub pokryte czymś przewodzącym
	- próbki biologiczne (mokre) zamraża się albo zalewa żywicą
	- przekroje - cięcie, zarysowanie i złamanie, szlifowanie
	- morfologia - proszki, powłoki 
- Zastosowanie:
	- badanie cienkich warstw, powłok
		- twardość ($TiO_2$)
		- właściwości gazochromowe ($WO_3$)
		- właściwości antybakteryjne ($Ti-Ag, Nb-Ag$) - publiczne ekrany dotykowe
		- no i oczywiście struktury

Porównanie SEM/TEM

| |SEM|TEM|
|-|-|-|
|typ elektronów| rozproszone, odbite, "skanujące"| przechodzące|
|napięcie przyspieszające| 1-30kV| 60-300kV|
|grubość próbki| obojętnie| <150nm|
|informacja| obraz 3D powierzchni| obraz projekcyjny 2D mikrostruktury|
|max. powiększenie| 1-2 miliony| >50 miliony|
|pole widzenia| duże| ograniczone|
|rozdzielczość przestrzenna| 0.5nm| <50pm|
|formowanie obrazu| elektrony zliczanie przez detektory, komputer wyświetla obraz| bezpośrednie obrazowanie na ekranie fluorescencyjnym lub ekranie komputera z CCD|
|działanie/obsługa| łatwy w użyciu, względnie mało skomplikowane przygotowanie próbki| pracochłonne przygotowanie próbki, używanie wymaga przeszkolenia|
|układ optyczny| formowanie wiązki przed próbką, detektory przed próbką (zbierają odbite)| układ optyczny przez i za próbką, ekran fluorescencyjny za próbką|
