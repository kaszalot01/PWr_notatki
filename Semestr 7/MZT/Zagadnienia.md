1. Nie wchodzi
2. Podstawowe informacje o świetle. Współczynnik załamania dla różnych materiałów. Co można policzyć, znając współczynnik załamania światła (zadanie obliczeniowe, przynieść kalkulator). Prawo lamberta-beera. Co to są tensory. Moment dipolowy.
3. Mikroskopy, sondy, rozdzielczości, zastosowania (dlaczego taki a nie inny mikroskop). **ważne**
4. Spin elektronu, prąd spinowy, wytwarzanie prądu spinowego, ferromagentyzm i antyferromagnetyzm w ujęciu spintroniki.
5. Warstwowe materiały ograniczone kwantowo , wykresy gęstości stanów, wzrost epitaksjalny, kropki kwantowe (wytwarzania, zastosowania, prekursory) (pytanie opsiowe)
6. MEMS - skrót, metody wytwarzania, zastosowania (pytanie opisowe); wielkości, sensory akutatory  - przykłady. Maszyny molekularne (przykłady), 'o co chodzi w skalowaniu', optofluidyka
7. Materiały węglowe, ruchliwość elektronów w grafenie, powstawanie nanorurek i innych nanostruktur węglowych. 
8. Podział diód w zależności od sposobu wzbudzania, elektroluminescencja, 'przejście tych spinów przez te dziury', budowa oledów, wydajność, perowskity w fotowoltaice, metoda wytwarzania paneli fotowoltaicznych
9. Metody wytwarzania kryształów fotonicznych, wpływ metody na wartość przerwy wzbronionej

## Wykład 2

### Moment dipolowy

Moment dipolowy układu ładunków punktowych:

$\mu= \sum_i q_ir_i$, pod warunkiem, że $\sum_i q_i=0$ (warunek obojętności elektrycznej)

Wzór uogólniony dla "rozmytej" gęstości elektronowej:

$\mu = e \sum_A Z_A R_A - e \int_V \rho(r)rd\tau$

Moment dipolowy wykazują w szczególności cząsteczki dwuatomowe posiadające spolaryzowane wiązanie - najprostsze związki polarne.

### Indukowany moment dipolowy i tensor polaryzowalności

Jeżeli umieścimy swobodną cząsteczkę w zewnętrznym polu elektrycznym $E$ to na skutek zmiany rozkładu gęstości elektronowej pojawi się indukowany moment dipolowy $\mu_{ind}$

$\mu_{ind}=\tilde{\alpha}E$

współczynnik $\tilde{\alpha}$ nazywamy polaryzowalnością

Uogólnienie momentu indukowanego na przestrzeń trójwymiarową:

![[Pasted image 20231214170826.png]]

Tensor – uogólnienie pojęcia wektora; wielkość, której własności pozostają identyczne niezależnie od wybranego układu współrzędnych. Ale co to właściwie znaczy?

Dlaczego ten tensor ma aż 9 pozycji? Bo indukowany moment magnetyczny w danym kierunku (x, y albo z), zależy w różnym stopniu od wartości pola elektrycznego w każdym z trzech kierunków przestrzeni. To, jak zależy, opisuje  odpowiedni element danego **wiersza** tensora polaryzowalności. **Ten zapis macierzowy to nic innego jak układ 3 równań.** Całkowity moment indukowany w kierunku x jest sumą momentów indukowanych w tym kierunku przez składową pola elektrycznego w kierunku x, w kierunku y i w kierunku z. $\mu_{x, ind}=\alpha_{xx}E_x + \alpha_{xy}E_y+\alpha_{xz}E_z$

Jako, że przestrzeń opisujemy 3 wymiarami, to gdyby tensor miał mniej elementów to polaryzowalność nie byłaby w pełni opisana - moglibyśmy tak obrócić obiekt w polu, że nie wiedzielibyśmy jaki indukujemy moment. Tensor nie musi mieć zaś więcej elementów, bo kolejne kolumny tensora musiałyby być matematycznie związane z tymi poprzednimi - dałoby się je z nich wywnioskować.

### Polaryzacja

Podział:

- polaryzacja indukowana
	- elektronowa - przemieszczenie ujemnie naładowanych chmur elektronowych
	- atomowa - przemieszczeni dodatnio naładowanych jąder atomowych (jeżeli występują wiązania jonowe to nazywana też jonową)
- polaryzacja orientacyjna (dipolowa)

Każdej z tych polaryzacji odpowiada polaryzowalność ($\alpha$) i związana z nią polaryzowalność molowa ($\Pi$) 

Zmienne pole elektryczne (np. pochodzące od fali elektromagnetycznej), powoduje, zależne od częstotliwości, straty energii związane z polaryzacją dipoli, elektronów i atomów. Z tymi stratami związane są zjawiska załamania fali EM, dlatego współczynnik załamania $n$ jest związany z przenikalnością elektryczną $\varepsilon$.

### Co można obliczyć znając współczynnik załamania światła?

Coś co w przestrzeni 3-wymiarowej porusza się w jakimś kierunku, można opisać 2 liczbami. Dlatego na przykład pole elektryczne fali elektromagnetycznej można opisać wektorem na płaszczyźnie prostopadłej do kierunku rozchodzenia się fali.

Dlatego też zjawiska związane z polaryzacją fali EM opisują wartości o dwóch współrzędnych np. w relacji Fresnela reflektancje: $r_p$ i $r_s$, lub współczynniki załamania przy dwójłomności kołowej.

#### Wzory

![[Pasted image 20231214192810.png]]

![[Pasted image 20231214192836.png]]


### Wartości współczynnika załamania światła

|Ośrodek| n|
|-|-|
|powietrze| 1|
|woda|1.33|
|etanol| 1.36|
|szkło|1.52|
|NaCl|1.54|
|diament|2.42|

## Wykład 3

### TEM

- modus operandi: przejście wiązki elektronów przez próbkę (próbka musi być cienka, dostajemy projekcję 2D), obraz na "fosforyzującym" (sic! lepiej: "elektroluminescencyjnym") ekranie za próbką.
- rozdzielczość ~1nm

### SEM

- mo: próbkę skanuje wysokoenergetyczna wiązka elektronów. Detektory zliczają elektrony wstecznie rozproszone (BSE) przez próbkę. Dostajemy mapę 3d powierzchni.
- r: ~5nm

### STM

![[Pasted image 20231214200542.png]]

Można badać tylko materiały przewodzące (można ewentualnie karbonizować próbkę, lub naparować na nią metal)

- sonda: platyna-iryd / wolfram
- rozdzielczość: 0.01 nm (10pm)

### SPM (scannig probe microscopes)

nadają się do badania żywych komórek
#### AFM

![[Pasted image 20231214201253.png]]

sodny: SiN, SiC
mody: tapping (przerywanego kontaktu) , contanc, non-contact

![[Pasted image 20231214201653.png]]

- rozdzielczość 1nm
- przykłady preparatów:
	- drożdże
	- powierzchnie płyt CD, DVD
	- powierzchnia grafitu
	- cienkie warstwy polimerów
- szczególne podtypy
	- LFM (mikroskop sił bocznych, może wykrywać zmiany w składzie)
	-  MFM (mikroskop sił magnetycznych, można mierzyć np. dyski HDD)
	- EFM (j.w. tylko polem elektrycznym)
	- FMI (obrazowanie z modulacją siły - właściwości mechaniczne \[sprężystość/sztywność]) 
#### SNOM (scanning near-field optical microscope)

- mo: tunelowanie fotonów przez 80 nm aperturę
- sonda: zaostrzony światłowód pokryty warstwą aluminium 
- mody: SFM (shear force), reflection, MAC (magnetic cantilever, ruch o małej amplitudzie)
- preparaty
	- DNA
	- kropki kwantowe

## Wykład 4


Momenty magnetyczne powstają w wyniku ruchu elektronów **i spinu elektronów**. Całkowity moment magnetyczny atomu jest sumą momentów pochodzących od wszystkich elektronów i jądra. Moment magnetyczny wynikający z obecności jednego niesparowanego elektronu → magneton Bohra = $\mu_B=9.273 \cdot 10^{-24} A/m2$

### Prąd spinowy

Przepływ spinu przy braku przepływu ładunku. Jak można wpływać na kierunek spinu, a co za tym idzie generować prąd spinowy? Polem magnetycznym, efektem Kondo (odwrócenie spinu przy rozproszeniu elektronu w ujęciu falowym na domieszce magnetycznej), optycznie (to chyba znaczy też polem magnetyczny ale z fali EM)
### Ferromagnetyzm i antyferromagnetyzm

Zjawisko, w kórym materia wykazuje własne, spontaniczne namagnesowanie. Mają wysoką, dodatnią wartość podatności magnetycznej.

![[Pasted image 20231214212525.png]]

W antyferromagnetykach, momenty magnetyczne ustawione są antyrównolegle, dając zerowe namagnesowanie.

![[Pasted image 20231214213243.png]]

![[Pasted image 20231214213354.png]]

![[Pasted image 20231214213444.png]]

![[Pasted image 20231214213530.png]]

## Wykład 5

![[Pasted image 20231214223704.png]]


![[Pasted image 20231214214247.png]]

![[Pasted image 20231214220933.png]]
![[Pasted image 20231214221003.png]]

### Kropki kwantowe

- wytwarzanie
	- litografia wiązką elektronową
	- epitaksjalny wzrost z naprężeniem (samoorganizujące się kropki kwantowe)
	- **mokra synteza w kolbie trójszyjnej (Schlenka) z udziałem czynnika stabilizująceg kropki  - en.cap, najczęściej TOPO**
- zastosowanie
	- lasery
	- materiały widmami absorpcji/emisjii, zależnymi od wielkości kropek
- skład
	- CdSe + ZnSe
	- **CdSe**
	- InAs
	- InP +ZnS (korszel)
	- CdS+Hgs (korszel)

|Skład| Metoda| Zastosowanie|
|-|-|-|
|CdSe + ZnSe| litografia wiązką elektronową||
|InAs| epitaksjalny wzrost z naprężeniem| laser|

## Wykład 6

MEMS - micro electro-mechanical systems, mikrosystemy. Co najmniej jeden wymiar w skali mikro (0.1-100 um)

- wytwarzanie: 
	- mikroobróbka krzemu lub szkła
		- anizotropowe trawienie (np. w KOH) z maską
	- dla układów polimerowych (PDMS, PU, PMMA)
		- wytłaczanie na gorąco
		- odlewanie w formie
		- wtryskiwanie
	- litografia
		- Vis
		- UV, X-ray, e-beam
		- FIB

- zastosowania
	- sensory (czujniki)
		- akcelerometr
		- mikrofon
	- procesory
	- aktuatory (siłowniki)
		- mikropompy
		- wtryskarki atramentu
		- elementy komunikacji optycznej
		- lustra skanujące
	- przekładnie
	- zawiasy

- wytwarzanie 2:
	- odciskanie (replica molding)- matryca
	- mikrodrukowanie kontaktowe ($\mu CP$) - jak pieczątką
	- mikro kontaktowe wytłaczanie
	- nanodrukowanie - tipem jak do AFMu (zamoczonym w 'atramecie' albo z rezerwuarem atramentu)
	- dwufotonowa polimeryzacja

- zastosowania 2

![[Pasted image 20231214230834.png]]

- wielkości

![[Pasted image 20231214231033.png]]

### Optofluidyka

Systemy wykorzystujące interakcji cieczy i światła. Sensoryka, analiza chemiczna. "Lab-on-a-chip". Pomiary: fotoluminescencji, chemiluminescencji, zmian współczynnika załamania światła, inne spektroskopie. Połączone z mikropompami, mikromieszalnikami, itp. Małe, dokładne, tanie, mobilne, zautomatyzowane. Biosensor, refraktometr, interferometr.

### Maszyny molekularne

- rotaksany (pierścień na sztandze)
- katenany (obrączki)
- pochodzenia biologicznego
	- kinezyny
	- maszyny na ATP (pompy ?)

### Skalowanie

Mikrostruktury mają znacznie większy stosunek powierzchni do objętości niż struktury milimetrowe

![[Pasted image 20231214233041.png]]



## Wykład 7

diament - sp3
grafit - sp2
karbin - sp

grafen
fulereny
nanorurki

Ruchliwość elektronów w temp. pokojowej $2.5 \cdot 10^5 cm2 /V s$

Osiągane są wysokie ruchliwości elektronów właściwie niezależne od temperatury!!! Ruchliwość dziur i elektronów: $~ 10^5 cm2 /V s$ Elektronika oparta na grafenie może zastąpić technologię krzemową

Zarówno dziury jak i elektrony mogą być nośnikami ładunku.

Prędkość elektronów na poziomie Fermiego  jest odwrotnie proporcjonalna do masy efektywnej - grafen ma tę masę b. małą.

![[Pasted image 20231215000911.png]]

niby półprzewodnik, ale nie ma przerwy energetycznej

![[Pasted image 20231215000956.png]]

Metody otrzymywania fulerenów:

- laserowa
- płominiowa
- elektrołukowa
- pieca słonecznego

potem rozdzielanie

Metody otrzymywania nanorurek:

- elektrołukowa
- elektrołukowa katalityczna (Gd2O3, Gd)
- katalityczna piroliza węglowodorów
- laserowe rozpylanie grafitu
- wysokotemperaturowa synteza elektrolityczna 

Nanorurki

- single wall
- multiwall

![[Pasted image 20231215002259.png]]

zig-zag

![[Pasted image 20231215002325.png]]

armchair

![[Pasted image 20231215002349.png]]



## Wykład 8

Przykłady luminescencji:

- fotoluminescencja
- elektroluminescencja
- chemoluminescencja
- bioluminescencja
- sonoluminescencja
- katodoluminescencja

Elektroluminescencja to luminescencja wzbudzona przez energię pola elektrycznego.

Gdy złącze p-n zostanie spolaryzowane w kierunku przewodzenia, czyli półprzewodnik p połączony jest z dodatnim biegunem zasilania , wtedy w warstwie typu n, o grubości 1µm, więcej elektronów znajduje się w pasmie przewodnictwa niż na górnych poziomach pasma walencyjnego. Jest to stan odwrócenia obsadzeń (inwersja obsadzeń). Oznacza to, że elektrony mogą przejść na puste poziomy pasma podstawowego i rekombinować z dziurami znajdującymi się po stronie p złącza p-n. Temu przejściu towarzyszy emisja światła widzialnego lub bliskiej podczerwieni.


![[Pasted image 20231215003347.png]]

![[Pasted image 20231215003621.png]]

![[Pasted image 20231215003601.png]]

![[Pasted image 20231215003828.png]]

Organiczno-nieorganiczne perowskity dla fotowoltaiki

![[Pasted image 20231215004239.png]]

## Wykład 9

Mikromanipulacja (układanie kulek krzemu i lateksu) - 11% gap

Litografia warstwowa (rentgenowska?)- 27% gap

Sterta drewna (łączenie wytrawionych w krzemie belek) - 17% gap

Litografia UV - 5% gap

GLAD (GLancing angle deposition) - 15% gap

Auto-klonowanie - 14% gap

Metody masowej produkcji:

Litografia dwufotonowa (bez masek)

Sedymentacja z koloidu

Kopolimery blokowe