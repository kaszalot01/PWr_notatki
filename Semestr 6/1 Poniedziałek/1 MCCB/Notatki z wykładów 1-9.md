# Luźne notatki

## Stała podziału składnika "a"

$K_a=C_{sA}/C_{rA}$

stosunek stężenia składnika A w fazie stacjonarnej do stężenia w fazie ruchomej

Rozdział chromatograficzny jest możliwy tylko, gdy stałe podziału składników różnią się.

## Zastosowanie chromatografii

![[Pasted image 20230615180611.png]]

## Zredukowany czas retencji

![[Pasted image 20230615181038.png]]

$t_r'=t_r-t_m$
$V_R=t_r \cdot F$

$V_R$ - objętość retencji
$F$ - przepływ

## Współczynnik retencji k'

$k'=\frac{t_R'}{t_M}=\frac{C_sV_s}{C_rV_r}$

$k \sim -B[\%]$  
współczynnik retencji zależy od składu fazy ruchomej - zawartości bardziej polarnego rozpuszczalnika. **Im więcej składnika polarnego w fazie ruchomej tym mniejszy współczynnik retencji**

## Współczynnik rozdzielenia $\alpha$

$\alpha=\frac{t_{R2}'}{t_{R1}'}=\frac{k_2'}{k_1'}$

## Szerokości piku gaussowskiego

W zależności od tego co mamy na osi OX chromatogramu taki jest wymiar szerokości piku (objętość albo czas).

szerokość u podstawy $w_b=4 \sigma$
szerokość połówkowa $w_{1/2}=2.35 \sigma$

## Rozdzielczość

stosunek różnicy czasów retencji dwóch substancji do średniej szerokości pików tych substancji na chromatogramie

$R_s=\frac{2(t_{R2}-t_{R1})}{w_{b1}+w_{b2}}$

Jako, że szerokość piku gaussowskiego wnosi $4\sigma$, rozdzielczość chromatogramu o dwóch podobnych pikach oddzielonych od siebie w czasie o $n \sigma$ wynosi $n/4$.

## Dyfuzja

Pierwsze prawo Ficka

$J=-D\frac{\partial c}{\partial x}$

Dyfuzja powoduje rozmycie piku w zależności od czasu

$\sigma = \sqrt{2Dt}$ 

![[Pasted image 20230615184220.png]]

## Półki teoretyczne

$L=N \cdot H$

L - długość kolumny
N - liczba półek
H - wysokość półki

$N=16(\frac{V_R}{w_{b, obj}})^2=16(\frac{t_R}{w_{b, czas}})^2$

Efektywna liczba półek

$N=16(\frac{V_R'}{w_{b, obj}})^2=16(\frac{t_R'}{w_{b, czas}})^2$

Jak sobie pożonglujemy to nam wyjdzie, że dla danej długości kolumny, szerokość piku zależy od pierwiastka z wysokości półki teoretycznej. Zaraz się to nam przyda.

## Równanie Van Deemtera

$H=A+B/u_x+Cu_x$

H - wysokość półki teoretycznej
$A=2 \lambda d_p$ - dyfuzja wirowa ($\lambda$ - stała charakteryzująca upakowanie $d_p$ - wielkość ziarna)
$B/u_x$ - dyfuzja podłużna
$Cu_x$ - opór przenikania masy
$u_x$ - prędkość przepływu

Dyfuzja podłużna w fazie ruchomej spowodowana jest przypadkowym ruchem cząsteczek rozdzielanej substancji w fazie ruchomej. Im krócej substancja jest na kolumnie tym rozmycie jest mniejsze. Ponieważ dyfuzja w gazie jest znacznie szybsza niż w cieczy, w chromatografii gazowej przepływy powinny być większe niż w chromatografii cieczowej.

**ALE**

Parametr $Cu_x$ zależny jest od oporów powstających przy przemieszczaniu się rozdzielanych substancji do i od fazy stacjonarnej. Czynnik ten wynika z czasu potrzebnego do równoważenia pomiędzy fazą ruchomą i stacjonarną. Niższy przepływ daje  szansę na lepsze zrównoważenie, a to powoduje węższy pik.

**Generalnie jest minimum w $\sqrt{\frac{B}{C}}$  (zadanie z matury z matematyki)**

![[Pasted image 20230616143727.png]]

## Równanie Purnella

$R_s=\frac{1}{4}\sqrt{N}(\frac{\alpha-1}{\alpha})(\frac{k'}{k'+1})$

## Układy chromatograficzne

Układ faz normalnych - faza stacjonarna jest **bardziej polarna** niż faza ruchoma. 
Przykłady:

- kolumnowa grawitacyjna
- typu flash

Faza stacjonarna:

- sole nieorganiczne
- tlenki nieorganiczne
	- tlenek krzemu 
		- **żel krzemionkowy**
		- krzemionka
	- tlenek glinu - alumina

Faza ruchoma:

**Im bardziej polarny związek, tym wolniej będzie eluował** 
Szereg polarności (od najmniej polarnych)

1. Alkany
2. Zw. aromatyczne
3. etery
4. estry, aldehydy
5. alkohole
6. kwasy karboksylowe
7. woda

Układ faz odwróconych - faza stacjonarna jest **mniej polarna** niż faza ruchoma. 
Przykład: RP-HPLC

Faza stacjonarna:

- modyfikowany żel krzemionkowy **C18**

### Elucja

![[Pasted image 20230617214922.png]]

![[Pasted image 20230617233814.png]]

# Zagadnienia
1. Chromatografia gazowa
	1. Typy kolumn
		1. Pakowane analityczne
		2. Mikropakowane
		3. Pakowane preparatywne
		4. Kapilarne
			1. WCOT (en. wall coated open tube): faza stacjonarna jest ciekła
			2. PLOT (en. porous layer open tube): fazą stacjonarną jest polarna warstwa ziaren adsorbenta.
			3. SCOT (en. support coated open tube): fazą stacjonarną są ziarna adsorbenta z osadzoną na nich fazą ciekłą
		5. mikrokapilarne
	3. Rodzaje GC:
		1. GSC, chromatografia adsorpcyjna gaz-ciało stałe.
			1. Adsorbenty węglowe, nieorganiczne (żele krzemionkowe, sita molekularne - naturalne lub syntetyczne zeolity), polimerowe (polimery porowate)
			2. Stosuje się do analiz związków o niskich masach cząsteczkowych
		2. GLC, chromatografia podziałowa gaz-ciecz
			1. Złoża różnej polarności
				1. niepolarne: alkany; do rozdziału substancji niepolarnych; rozdział zależy od temperatury wrzenia analitu
				2. średniopolarne: siloksany; do rozdziału mieszanin związków różnej polarności
				3. polarne: glikole polietylenowe i estry; do polarnych; rozdział zależy od polarności złoża
		3. Ciekła faza stacjonarna
			1. 90% wszystkich analiz
			2. Rozdzielenie następuje na skutek różnic w rozpuszczalności składników mieszaniny
	4. Typy detektorów
		1. FID - en.flame ionisation detector, **destrukcyjny**
		2. TCD - en.thermal conductivity detector, katarometr, **nieinwazyjny**
		3. ECD - en.electron-capture detector
		4. Inne detektory jonizacyjne
	5. Parametry procesu:
		1. rodzaj gazu nośnego
			1. nie ma wpływu w kolumnach pakowych
			2. w kapilarnych może być tylko wodór lub hel
		2. prędkość liniowa gazu nośnego
			1. $\mu = L/t_m$
			2. $\mu \sim$ lepkość, temperatura kolumny, ciśnienie
		3. temperatura kolumny - musi być optymalna
			1. wzrost = gorszy rozdział
			2. spadek = poszerzenie i niesymetryczność pików
2. Metoda normalizacji pola
	$X[\%]=\frac{A_x f_x}{\sum_i(A_i f_i)}$, gdzie A to procentowy udział sygnału chromatogramu a f to współczynnik odpowiedzi
3. Rozdzielczość i selektywność
	1. Selektywność (współczynnik rozdzielenia)
		Stosunek zredukowanych czasów retencji lub współczynników retencji ($k'=\frac{t_R'}{t_M}$)
		$\alpha=\frac{t_{R2}'}{t_{R1}'}=\frac{k_2'}{k_1'}$
	2. Rozdzielczość
		stosunek różnicy czasów retencji dwóch substancji do średniej szerokości pików tych substancji na chromatogramie.
		$R_s=\frac{2(t_{R2}-t_{R1})}{w_{b1}+w_{b2}}$
		Jako, że szerokość piku gaussowskiego wnosi $4\sigma$, rozdzielczość chromatogramu o dwóch podobnych pikach oddzielonych od siebie w czasie o $n \sigma$ wynosi $n/4$.
	3. Związane są równaniem Purnella: $R_s=\frac{1}{4}\sqrt{N}(\frac{\alpha-1}{\alpha})(\frac{k'}{k'+1})$
4. Elektroforeza kapilarna
	1. Elektroforeza – migracja jonów pod wpływem
		przyłożonego napięcia
	2. Techniki
		1. Kapilarna elektroforeza strefowa
		2. Żelowa elektroforeza kapilarna
		3. Kapilarne ogniskowanie izoelektryczne
		4. Izotachoforeza kapilarna
	3. Kapilary się nagrzewają co powoduje poszerzenie pików
	4. Detektory
		1. UV-Vis
		2. Fluorescencji
		3. Przewodnictwa
		4. Elektrochemiczny
	5. Prędkość i ruchliwość elektroforetyczna
		$\mu_{ep}=\frac{v_{ep}}{E}=\frac{q}{6\pi \eta r}$ , q - ładunek, r - średnica cząsteczki, eta - lepkość
	6. Prędkość i ruchliwość elektroosmotyczna
		$\mu_{EOF}=\frac{v_{EOF}}{E}=\frac{\varepsilon \zeta}{4\pi \eta}$, gdzie epsilon to stałą dielektryczna buforu a zeta to potencjał elektrokinetyczny
5. TLC
	1. Typy płytek
		1. Szklane, aluminiowe, z tworzywa sztucznego (tereftalan polietylowy)
			1. TLC - rozdział analityczny; 0.1-0.25mm sorbentu
			2. PLC - rozdział preparatywny; 0.5-2mm sorbentu
			3. HPTLC - 0.2mm sorbentu, adsorbenty o mniejszych rozmiarach, rozrzut tych rozmiarów też mniejszy
	2. Zalety
		1. równoczesny rozdział kilku różnych próbek
		2. proces rozdzielania można zatrzymać
		3. próbki nie muszą być oczyszczone
		4. różne, selektywne sposoby realizacji
		5. tania i mało pracochłonna
	3. Wady
		1. wyniki nie są powtarzalne
		2. im dalej w las tym szersze pasma
	4. Adsorbenty
		1. żel krzemionkowy (90% analiz)
		2. tlenki glinu
		3. **celuloza i jej pochodne**
		4. poliamidy
	5. Rozwijanie chromatogramu
		1. liniowe
		2. liniowe z dwóch stron
		3. kołowe
		4. dośrodkowe kołowe
		5. **dwukierunkowe prostopadłe** - najpierw normalnie linowo, potem obracamy płytkę o 90 stopni i rozwijamy innym eluentem. Może się okazać, że pozornie pojedyncze plamki się jeszcze rozdzielą.
	6. Wizualizacja chromatogramu
		1. UV
		2. wskaźniki fluoryzujące ($F_{254}, F_{366}$)
		3. komora jodowa
		4. zasadowy, wodny roztwór $KMnO_4$ 
		5. różne inne na podstawie reakcji chemicznych
	7. $R_f=z/l$, stosunek odległości środka danej plamki do odległości linii mety (czoła rozpuszczalnika)
6. Żel krzemionkowy
	**polarny adsorbent**. Może być modyfikowany grupami alkilowymi, ew. innymi. Dla grup alkilowych korzystamy ze skrótów według wzoru: $Cn$ gdzie $n$ to liczba atomów węgla w grupie. Np. $-CH_2(CH_2)_2CH_3$ to $C4$.
7. Zależności
	1. $d_p \uparrow H \uparrow w_b \uparrow N\downarrow t_R' \downarrow p_{req}\downarrow$
	2. $u_x \uparrow H \uparrow wb \uparrow N \downarrow  p_{req}\downarrow$
		(gdy $u_x$ jest większe niż $\sqrt{\frac{B}{C}}$)
8. Przepływ elektroosmotyczny
	1. Elektroosmoza – zjawisko związane z przepływem
		buforu w kapilarze pod wpływem przyłożonego napięcia.
	2. Przepływ elektroosmotyczny (EOF) to migracja buforu w kierunku katody. Jest spowodowany tworzeniem się dwuwarstwy na ścianie kapilary (warstwa wodorów grupy OH i druga warstwa wodorów z wiązań wodorowych). **Obniżenie pH powoduje zmniejszenie przepływu elektroosmotycznego.**	
9. Siła elucji:
	- charakteryzuje energię oddziaływania rozpuszczalnika z fazą stacjonarną
	- jest proporcjonalna do polarności rozpuszczalnika
	- zależy od adsorbentu
	- dla oddziaływania pentanu z adsorbentem przyjęto **parametr** siły elucji $\varepsilon^0=0$. Parametr siły elucji to nie to samo co siła elucji.
	- szereg eluotropowy: pentan < etery < octan etylu < acetylonitryl < metanol < kwas octowy < woda
10. Elucja izokratyczna i gradientowa:
	1. Izokratyczna - stały skład eluentu
	2. Gradientowa - ciągła zmiana składu eluentu, zwiększenie siły elucji ![[Pasted image 20230617222856.png]]
11. Rozdział enancjomerów
	1. Metody chromatograficzne
		1. metoda pośrednia - przeprowadzenie enancjomerów w pochodne diastereoizomeryczne przed analizą
		2. metoda bezpośrednia - niekowalencyjne oddziaływania z chiralnym selektorem
			1. chiralna faza stacjonarna (**HPLC, GC, TLC**)
			2. chiralna faza ruchoma
	2. Nadmiar enancjomeryczny $ee\%$ 
		$ee\%=\frac{[E_{major}]-[E_{minor}]}{[E_{major}]+[E_{minor}]} [\%]$ 
	3. Stosunek enancjomeryczny $er$
		$er=\frac{[E_{minor}]}{[E_{major}]}$
	4. Typy faz i główne oddziaływania 
		1. Pochodne cyklodekstryn (polimerów D-glukozy) - inkluzja 
		2. Pochodne aminokwasów - wiązania wodorowe
		3. Chiralne kompleksy metali - wiązania kowalencyjne 
12. Jonity
	1. Anionit to zasada na trwałe związana z powierzchnią ziarna stałej substancji 
	2. Kationit to kwas na trwałe związany z powierzchnią ziarna stałej substancji
	3. Pojemność jonowa - liczba moli jonów, które jonit jest zdolny zatrzymać w jednostce swojej masy. Powinna być raczej niewielka - bardziej symetryczne, wąskie piki. ![[Pasted image 20230618153123.png]]
	4. Podział
		1. jonity syntetyczne
			1. żywice jonowymienne - wielkocząsteczkowe związki nierozpuszczalne w wodzie i rozpuszczalnikach organicznych, zawierające grupy funkcyjne zdolne do wymiany jonów
				1. żywice kationowymienne (od najmocniejszych)
					1. sulfonowe
					2. fosfonowe
					3. karboksylowe
					4. aminodioctanowe
					5. fosfinowe
					6. fenolowe
				2. żywice anionowymienne (od najmocniejszych)
					1. aminy czwartorzędowe
					2. inne aminy
					3. grupy dialkilosulfoniowe 
				3. żywice amfoteryczne
			2. żele krzemionkowe
		2. jonity półsyntetyczne - np. węgle sulfonowane
		3. jonity naturalne - kationity glinokrzemianowe (zeiolity)
13. Chromatografia jonowymienna i jonowa
	1. Czynniki wpływające na retencje
		1. typ jonitu
		2. pH eluentu
		3. siła jonowa eluentu
		4. rodzaj przeciwjonu w eluencie
		5. 
14. HPLC
	1. Detektory
		1. UV-Vis
		2. matryca fotodiodowa
		3. FT-IR
		4. MS
		5. refraktometryczny
		6. fluorescencyjny
		7. elektrochemiczny
		8. przewodnictwa

# Galeria

![[Pasted image 20230618001922.png]]
![[Pasted image 20230618001936.png]]
![[Pasted image 20230618001943.png]]
![[Pasted image 20230618001956.png]]
![[Pasted image 20230618002031.png]]
![[Pasted image 20230618002114.png]]
![[Pasted image 20230618002131.png]]
![[Pasted image 20230618002537.png]]
![[Pasted image 20230618002614.png]]
![[Pasted image 20230618002626.png]]
![[Pasted image 20230618002720.png]]
![[Pasted image 20230618002816.png]]
![[Pasted image 20230618002824.png]]
![[Pasted image 20230618002912.png]]
![[Pasted image 20230618002938.png]]
(Normalizacja pola)
![[Pasted image 20230618002957.png]]
![[Pasted image 20230618003117.png]]
![[Pasted image 20230618003147.png]]
![[Pasted image 20230618003226.png]]
![[Pasted image 20230618152813.png]]