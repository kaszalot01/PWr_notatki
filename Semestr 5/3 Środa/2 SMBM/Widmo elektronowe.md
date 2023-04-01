## Liczby kwantowe elektronu

Główna liczba kwantowa $n$:

- $n=1,2,3,4,...$

Orbitalna liczba kwantowa $l$:

- $l=0,1,2...n-1$
- $s\ p\ d\ f\ g$
- moment pędu $|L|=\sqrt{l(l+1)}\hbar$ 

Magnetyczna liczba kwantowa $m_l$:

- $m_l=l,(l-1),...,0,...(-l+1),-l$
- w polu elektrycznym lub magnetycznym odpowiada za kąt precesji wektora momentu pędu
- przy braku pola powoduje (2l+1)-krotne zdegenerowanie orbitalu

Spinowa liczba kwantowa $s$:
- $s=\frac{1}{2}$
- spinowy moment pędu (spin) $|S|=\sqrt{s(s+1)}\hbar=\hbar\frac{\sqrt3}{2}$

Magnetyczna spinowa liczba kwantowa $m_s$:

- $m_s=-\frac{1}{2},\frac{1}{2}$

## Elektrony w atomie

Zakaz Pauliego - w danym atomie elektrony nie mogą mieć jednakowych wszystkich liczb kwantowych

Konfiguracja elektronowa - $n\ l\ ^{|m_l| \cdot |m_s|}...$, $1s^22s^22p^63s^23p^63d^{10}$ 

Kwantowa liczba orbitalna wszystkich elektronów w atomie $L$

- $L=(l_1+l_2),(l_1+l_2-1),...,|l_1-l_2|$
- wypadkowy orbitalny moment pędu $|L|=\sqrt{L(L+1)}\hbar$

Kwantowa liczba spinowa wszystkich elektronów w atomie $S$

- $S=(s_1+s_2),(s_1+s_2-1),...,|s_1-s_2|$
- wypadkowy spinowy moment pędu $|S|=\sqrt{S(S+1)}\hbar$

Kwantowa liczba całkowitego wypadkowego momentu pędu wszystkich elektronów $J$

- $J=(L+S),(L+S-1),...,|L-S|$
- wypadkowy całkowity moment pędu $|J|=\sqrt{J(J+1)}\hbar$

Termy atomowe 
Nie rozpatrujemy powłok całkowicie zapełnionych.
$^{2S+1}L_J$, dla wszystkich możliwych S i L

Stany elektronowy opisany liczbami $n,l,m_l,m_s$) charakteryzuje funkcją falową, nazywaną spinorbitalem.
Kształt chmury elektronu opisany jest jedynie liczbami $n,l,m_l$,charakteryzuje go część konfiguracyjna funkcji falowej zwana orbitalem.

W polu magnetycznym stan dla każdej wartości $m_l$ ma inną energię. W polu elektrycznym stany dla przeciwnych wartości $m_l$ mają taką samą energię $(E(m_l)=E(-m_l))$ 

## Elektrony w cząsteczce

Termy

- $\Lambda=0,1,..L$
- $M_s=S,S-1,...-S$
- $\Omega$ jak J
- Termy analogicznie

Orbitale

- $\lambda=|m_l|$
- $\lambda = 0 (\sigma), 1 (\pi), 2 (\delta)$

## Energia stanów elektronowych

Trwałe stany elektronowe są opisane przez minima energii potencjalnej.![[Pasted image 20221215000908.png]]

Zasada Francka-Condona - przejścia elektronowe w molekule odbywają się tak szybko w porównaniu z oscylacyjnym ruchem jąder, że wszystkie odległości międzyjądrowe można uznać za stałe w czasie przejścia elektronowego. 

Diagramy korelacyjne - po jednej stronie energie dla "zdeformowanego zjednoczonego atomu" (odległość między atomami prawie 0), po drugiej dla "atomów nieznacznie na siebie odziaływujących" (odległość prawie nieskończona). Jak atomy "przyjeżdżają" z nieskończoności i energia maleje to orbital jest wiążący a jak rośnie to antywiążący.
![[Pasted image 20221215002018.png]]
Reguła Hunda dla orbitali w cząsteczkach - najniższej energii odpowiada term o najwyższej multipletowości.

## Oddziaływanie promieniowania z elektronami

Warunki absorpcji fotonu

- dopasowanie energetyczne $\Delta E=h \nu$
- niezerowe prawdopodobieństwo absorpcji $R_lm=\int_{-\infty}^\infty \Psi ^*_l \mu \Psi_m d \tau \neq 0$
	- reguła wyboru - przez jakąś potężną matmagię wynika z tego, że termy, między którymi zachodzi przejście muszą mieć tę samą multipletowość (singlet-singlet, dublet-dublet itd.)

Teoretyczna i doświadczalna intensywność integralna pasma, moc oscylatora $f$
$$\bar{A}_{teor}=B_{01}\frac{h \nu_{01}}{c^2}N_A=\frac{\pi e^2 N_A}{m_ec^2}$$
$$\bar{A}_{dośw}=2.303 \int _{po\ konturze} \varepsilon' d \bar{\nu}$$
gdzie $\varepsilon'=\frac{1}{\bar{\nu}l}\log{\frac{T_{tło}}{T}}$,l - grubość warstwy (?)

$$f=\frac{\bar{A}_{dośw}}{\bar{A}_{teor}}$$

Jeżeli moc oscylatora jest bliska jedności, oznacza to, że przejście elektronowe jest dozwolone

## Aparatura

Kuwety - kwarc, czasem szkło - przepuszczają promieniowanie w VIS (kwarc w UV)

![[Pasted image 20221215005854.png]]

Źródła promieniowania - lampa wolframowa (350-700nm), lampa wodorowa lub deuterowa (180-400nm)

Monochromator - obracana siatka dyfrakcyjna

Rozdzielenie wiązki - sektor wirujący - półkoliste zwierciadło - przez pół okresu obrotu przepuszcza jedną wiązkę a przez drugie pół drugą. Trochę nie wiem jak.

Mierzymy transmitancje - stosunek natężenia promieniowania przechodzącego przez próbkę to natężenia przechodzącego przez wzorzec.

## Zastosowania

- proste (dwuatomowe) molekuły w stanie gazowym
	- astrofizyka
		- skład ogonów komet
		- zorza polarna
		- skład atmosfer planet
	- chemia
		- reakcje zachodzące w płomieniach, łuku elektrycznym, plazmie
			- rodniki
			- jony
	- pomiary bardzo wysokich temperatur
- chromofory - układy sprzężonych wiązań wielokrotnych, związki zawierające orbitale $\sigma, \pi, n$. Np. grupa karbonylowa ($C=O$) , azowa ($N=N$) ,nitrozowa ($N=O$). Dla sprzężonych wiązań wielokrotnych następuje zbliżenie do siebie poziomów $\pi$ i $\pi^*$. 
	![[Pasted image 20221215124126.png]]
	\[$E(n \rightarrow \sigma^*) > E(\pi \rightarrow \pi^*)$\]
- przejścia z przeniesieniem ładunku (CT)
- 