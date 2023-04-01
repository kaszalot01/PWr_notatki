## SEM c.d.

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