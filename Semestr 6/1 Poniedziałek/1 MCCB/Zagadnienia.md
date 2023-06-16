1. Chromatografia GC
2. Metoda normalizacji pola, współczynniki odpowiedzi
3. Rozdzielczość i selektywność układu
4. Elektroforeza kapilarna
5. Pojemność jonowa
6. Definicje: anionit, kationit
7. Żywica jonowymienna
8. Żel krzemionkowy
9. Chromatografia typu SEC (filtracja żelowa)
10. Chromatografia TLC
11. Współczynnik rozdzielenia 
12. Współczynnik retencji k
13. Rozdzielczość Rs
14. Współczynnik podziału (nomen omen retardacji) Rf
15. Wzajemne zależności: 
	1. wielkości cząstek żelu
	2. strumienia przepływu
	3. liczby półek teoretycznych
	4. zredukowanego czasu retencji
	5. ciśnienia
16. Chromatografia cieczowa
17. Przepływ elektroosmotyczny
18. Chromatografia typu IMAC
19. HPLC
20. Wpływ stałej dielektrycznej/rozpuszczalnika na retencję w układzie faz odwróconych
21. Siła elucji
22. Elucja izokratyczna i gradientowa
23. Cyklodekstryny
24. Chromatografia nadkrytyczna

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
współczynnik retencji zależy od składu fazy ruchomej - zawartości bardziej polarnego rozpuszczalnika. **Im więcej składnika polarnego  w fazie ruchomej tym mniejszy współczynnik retencji**

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
- 

# Omówienie
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
			1. 
		3. Ciekła faza stacjonarna 
	4. Typy detektorów
		1. FID - en.flame ionisation detector, **destrukcyjny**
		2. TCD - en.thermal conductivity detector, katarometr, **nieinwazyjny**
		3. ECD - en.electron-capture detector
2. Żel krzemionkowy - **polarny adsorbent**. Może być modyfikowany grupami alkilowymi, ew. innymi. Dla grup alkilowych korzystamy ze skrótów według wzoru: $Cn$ gdzie $n$ to liczba atomów węgla w grupie. Np. $-CH_2(CH_2)_2CH_3$ to $C4$.

3. 
	1. $d_p \uparrow H \uparrow w_b \uparrow N\downarrow t_R' \downarrow p_{req}\downarrow$
	2. $u_x \uparrow H \uparrow wb \uparrow N \downarrow t_r' \downarrow p_{req}\downarrow$
		(gdy $u_x$ jest większe niż $\sqrt{\frac{B}{C}}$)
21. Siła elucji:
	- charakteryzuje energię oddziaływania rozpuszczalnika z fazą stacjonarną
	- jest proporcjonalna do polarności rozpuszczalnika
	- zależy od adsorbentu
	- dla oddziaływania pentanu z adsorbentem przyjęto parametr siły elucji $\varepsilon^0=0$ 
	- szereg eluotropowy: pentan < etery < octan etylu < acetylonitryl < metanol < kwas octowy < woda
- 

   