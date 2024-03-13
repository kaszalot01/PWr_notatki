Tematy wykładów

1. SEM (cz. 1 i 2)
2. EDS, TEM
3. STM, AFM
4. Transmisja światła, OBIC
5. XRD

Klasyfikacja metod badania materiałów

- wiązki elektronowej 
	- SEM
	- TEM 
- siły atomowe oraz zjawiska tunelowania
	- AFM
	- STM
- wiązka świetlna
	- OBIC
	- transmisja światła
- wiązki rentgenowskiej
	- XRD
	- EDS
	- XPS
- wiązki jonów
	- SIMS

Przykłady fizykochemicznych metod badań materiałów

- zwilżalność
	- kąt zwilżania, napięcie powierzchniowe
	- swobodna energia powierzchniowa
- fotokataliza
	- aktywność fotokatalityczna

SEM - scanning electron microscope
Konstrukcja - 1963 - Cambridge

Trzy rodzaje:

- wysokoenergetyczne (15-40 kV)
- niskoenergetyczne (100-500 V)
- zwierciadlane (~0V)

`Schemat przejścia wiązki elektronów przez próbkę w SEM`

![[Pasted image 20221220220259.png]]

Po rzuceniu wiązki elektronów na próbkę, generuje ona:

- promieniowanie r

`Schemat mikroskopu SEM`

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

`energie i liczności różnych elektronów`

![[Pasted image 20221220220737.png]]

Elektrony, których nie mierzymy odfiltrowujemy siatkami, naelektryzowanymi tak aby odpychały elektrony o mniejszych energiach. Jak mierzymy sygnał EWR to odfiltrowujemy EW, których E<50eV.

Badana próbka musi spełniać następujące warunki:

- musi mieć odpowiednią konduktywność elektryczną - dielektryki dają dupy
- powinna mieć wysoki współczynnik emisji wtórnej - nie rozpraszać wiązki
- musi dać się dobrze zamocować na stoliku - proszki, preparaty biologiczne (próżnia przeszkadza)

Gdy próbka jest nieprzewodząca, należy ją pokryć cienką warstwą (do 90nm) metalu - Au, Pt lub warstwą węgla, historycznie również Cu.

`charakterystyka sygnału EWR - zależność od liczby atomowej`

![[Pasted image 20221220220845.png]]

Do liczby atomowej 40, współczynnik $\eta$ zależy liniowo od liczby atomowej. Można tym rozróżniać atomy (?).

`zależność eta od grubości warstwy`

![[Pasted image 20221220221026.png]]

Dla bardzo cienkich warstw większa część elektronów przejdzie przez próbkę. Od pewnej grubości nie przechodzi już nic. Chcemy, żeby próbka była grubsza, żeby mieć pełny zakres sygnału.

Współczynnik $\eta$ nie zależy od energii elektronów

`zależność eta od kąta padania wiązki`

![[Pasted image 20221220221132.png]]

Coś o tym, że ruszymy próbką, nie mikroskopem. (?)

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

Detektor scyntylacyjny - zamiana elektronów na impulsy świetlne `schemat - niezbyt omówiony został`

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

