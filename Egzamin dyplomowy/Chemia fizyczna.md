## Termodynamika

**Energia wewnętrzna** to energia jaką przypisujemy układowi. Może się zmieniać poprzez wykonywanie pracy i wymianę ciepła.

$$\Delta U=Q+W$$

**Pierwsza zasada termodynamiki** - energia wewnętrzna układu izolowanego jest stała.

Praca objętościowa:

![[Pasted image 20240203122528.png]]

$$W=\int -F dz=\int-\frac{F}{A}Adz=\int -p_{ex}dV$$

$$dU=dQ-pdV$$

W stałej objętości ($dV=0$) zmiana energii wewnętrznej jest równa ciepłu. Izolowanym układem, który nie pozwala na zmianę objętości jest bomba kalorymetryczna. Powołując się na pierwszą zasadę termodynamiki, można w niej zmierzyć zmianę energii wewnętrznej jakiegoś procesu (np. reakcja chemiczna podgrzeje wodę w kalorymetrze, wyznaczymy ciepło które zyskała woda, na mocy 1ZTD jest to takie samo ciepło, jakie wygenerowała reakcja)

**Entalpia** - taka miara energii, która jest równa ciepłu kiedy nie zmienia się ciśnienie.

$$H=U+pV$$
$$dH=dU+d(pV)$$
$$dH=dU+pdV+Vdp$$
$$(dU=dQ-pdV)$$
$$dH=dQ+Vdp$$

Pojemność cieplna

$$C=\frac{dQ}{dT}$$
Łatwo można zauważyć, że

$$C_{dv=0}=\frac{dU}{dT}$$
$$C_{dp=0}=\frac{dH}{dT}$$

**Prawo Hessa**

$$\Delta H^{\circleddash}=\Sigma_{produktów}  n \Delta_{tw}H^{\circleddash}-\Sigma_{substratów} n \Delta_{tw}H^{\circleddash}$$

**Entropia** - taka miara, której zmiana określa kierunek samorzutnych procesów. Procesy następują samorzutnie, kiedy ich skutkiem jest wzrost entropii. Zmianę entropii określono następująco. Proces jest odwracalny (myślmy: samorzutny w obie strony) gdy wartość zmiany entropii jest zerowa.

$$dS=\frac{dQ}{T}$$

Zmiana entropii w wybranych procesach

Rozprężanie gazu 
$$ \Delta S = nRln\frac{V_k}{V_p}$$
$$V_k>V_p$$
$$\Delta S >0$$

Zwiększanie temperatury

$$\Delta S = Cln\frac{T_k}{T_p}$$
Przemiana fazowa

$$d S = \frac{dH}{T}$$

**Druga zasada termodynamiki** - entropia wszechświata ma tendencję do zwiększania się.

Inne sformułowania:

- Zmiana entropii $dS$ dla dowolnego procesu rzeczywistego w układzie odosobnionym spełnia nierówność $dS\geq0$ Równość zachodzi tylko dla procesów odwracalnych.
- Nie istnieje proces termodynamiczny, którego jedynym wynikiem byłoby pobranie ciepła ze zbiornika o temperaturze niższej i przekazanie go do zbiornika o temperaturze wyższej.
- Nie jest możliwy proces, którego jedynym skutkiem byłoby pobranie pewnej ilości ciepła ze zbiornika i zamiana go w równoważną ilość pracy.
- Nie istnieje demon termodynamiczny Maxwella.

Standardowe zmiany entropi procesów można sumować jak standardowe zmiany entalpi, ale standardowa entropia tworzenia pierwiastków nie jest równa 0.

![[Pasted image 20240203133323.png]]

**Entalpia swobodna** - w stałej temperaturze i pod stałym ciśnieniem $$\Delta G=-T \Delta S_{całkowita}$$

Dzięki temu łatwo może służyć do określania samorzutności procesów.

Dodatkowo

$$\Delta_r G=\Delta_r G^\circleddash + RTlnQ$$
$$Q=\Pi_i (x_i^{\nu_i})$$
### Potencjał chemiczny

$$\mu_i=\frac{dG}{dn_i}$$

$$\mu_i=\mu_i^\circleddash+RTln(x_i)$$

Dla reakcji:

$N_2+3H_2=2NH_3$

$$dG=-\mu_{N_2}dn-3\mu_{H_2}dn+2\mu_{NH_3}dn$$
dn - postęp reakcji

W stanie równowagi:

$$\frac{dG}{dn}=0$$
Szuruburu:

$$ln\frac{x_{NH_3}^2}{x_{N_2}x_{H_2}^3}=jakieś\ stałe$$
a to już jest prawo działania mas!


### Kinetyka reakcji: wyznaczanie rzędu reakcji.



![[Pasted image 20240202122046.png]]

Reakcja: $a+b(+...) \rightarrow c$
$r=k[a]^{\alpha}[b]^{\beta}...$

Bierzemy nadmiar wszystkich substratów poza jednym - równanie upraszcza się i możemy wyznaczyć rząd dla reagenta w niedomiarze. Potem można zrobić tak samo dla innych reagentów i otrzymamy równanie kinetyczne.

![[Pasted image 20240202121953.png]]

Jak wyznaczyć rząd reakcji? Mierzyć stężenia w czasie i dopasować krzywą według scałkowanego równania kinetycznego.

Albo najlepiej wyznaczyć zależność log(dc/dt) od log(kc) i wtedy nachylenie będzie równe rzeędowi.

## Światło a materia

![[Pasted image 20240202123528.png]]

![[Pasted image 20240202123535.png]]

### Prawo Lamberta-Beera

![[Pasted image 20240202123828.png]]

![[Pasted image 20240202123835.png]]

### Współczynnik załamania światła materiałów optycznych.

	![[Pasted image 20240202125404.png]]

![[Pasted image 20240202125436.png]]

## Spektroskopia

![[Pasted image 20240202202602.png]]

![[Pasted image 20240202202458.png]]

#### UV-Vis

![[Pasted image 20240202221726.png]]

![[Pasted image 20240202221741.png]]

*dzięki uprzejmości Marka Czyszczonia*

### Spektrofluorymetria

![[Pasted image 20240202222123.png]]

*dzięki uprzejmości Marka Czyszczonia*

![[Pasted image 20240202222352.png]]

![[Pasted image 20240202222423.png]]

### IR

![[Pasted image 20240202223334.png]]

![[Pasted image 20240202223510.png]]

![[Pasted image 20240202223647.png]]

![[Pasted image 20240202224021.png]]

### Raman

![[Pasted image 20240202224209.png]]

![[Pasted image 20240202224238.png]]

> poprawnie mówimy "stołksowskie", nie "sztokesowskie", Stokes był Irlandczykiem

![[Pasted image 20240202224808.png]]

![[Pasted image 20240202224820.png]]

![[Pasted image 20240202224927.png]]

![[Pasted image 20240202225021.png]]

![[Pasted image 20240202225119.png]]

> En.based odpowiedź na pytanie o różnice między IR a ramanem - cena

### UPS, XPS

![[Pasted image 20240202233022.png]]

![[Pasted image 20240202233137.png]]

*dzięki uprzejmości Marka Czyszczonia*

![[Pasted image 20240202233248.png]]

![[Pasted image 20240202233315.png]]

### NMR

Wirujące, dodatnio naładowane jądro atomowe generuje moment magnetyczny.

(Tylko jądra atomowe o nieparzystej liczbie nukleonów ($^1H,\  ^{13}C$) można obserwować w spektroskopii NMR.)

Spin jądrowy kwantuje jądrowy moment magnetyczny (tzn. moment zależy od spinu, a spin przyjmuje dyskretne wartości)

![[Pasted image 20240202235426.png]]

W zewnętrznym polu magnetycznym, obecność momentu magnetycznego jądra powoduje ruch precesyjny wektora momentu pędu jądra (nie ważne co to za wektor, ważne że się kręci). Ruch odbywa się po skwantowanych orbitach, z którymi związane są skwantowane poziomy energii.

Dla wodoru sprawa jest prosta - dwie orbity, dwa poziomy.

![[Pasted image 20240202235815.png]]

![[Pasted image 20240202235936.png]]



No i rzucamy w próbkę fale EM radiowej częstotliwości która jest spolaryzowana kołowo i dzięki temu częstotliwość się zmienia w czasie (jakoś, don't ask my how), i jak częstotliwości pasują, to energia pasuje do różnicy poziomów i jest rezonans. 

Ale zaraz, zaraz, skoro to zawsze jest wodór, to różnica poziomów powinna być zawsze taka sama - do dupy taka metoda. Otóż nie, bo atomy wodoru są otoczone elektronami w różny sposób, stąd trochę różne energie, a stąd przesunięcie chemiczne. Sąsiednie jądra też wpływają, jak są takie same, to jednak trochę się różnią i stąd multiplety.

![[Pasted image 20240203002406.png]]

![[Pasted image 20240203002720.png]]


## Materiały magnetyczne

Diamagnetyki - mają wszystkie elektrony sparowane, atom **nie ma trwałego momentu magnetycznego**. Po umieszczeniu d-a w zewnętrznym polu magnetycznym ładunki dążą do częściowego ekranowania wnętrza ciała przez przyłożonym polem. (Teoria Langevin - magnetyzm robi prąd -> prąd robi magnetyzm przeciwny; jakieś NMRowe zaklęcia typu precesja)
Diamagnetyki magnetyzują się w bardzo słabym stopniu i w kierunku przeciwnym do kierunku działania zewnętrznego pola magnetycznego
Ten rodzaj magnetyzacji jest niezależny od temperatury

Paramagnetyki - posiadają co najmniej jeden niesparowany elektron, co skutkuje **trwałym momentem magnetycznym dla danego atomu**. Przy braku uporządkowania **wypadkowy moment magnetyczny jest zerowy**.
Gdy umieścimy paramagnetyk w zewnętrznym polu magnetycznym, materiał magnetyzuje się w nieznacznym stopniu w kierunku zgodnym z kierunkiem działania zewnętrznego pola magnetycznego.
Magnetyzacja odwrotnie proporcjonalna do temperatury 

Ferromagnetyki - silne właściwości magnetyczne. Każdy atom wytwarza własne pole magnetyczne. Atomy ustawiają się tak aby pole magnetyczne cząstek było zgodne z p.m. sąsiadów. Obszary tego samego kierunku nazywamy domenami. Pole magnetyczne domen mogą być ustawione w dowolnym kierunku.**Przy przyłożeniu zewnętrznego pola domeny ustawiają się w jego kierunku. Domeny nie wracają do ustawienia chaotycznego po ustaniu zewnętrznego p.m. - pozostałość magnetyczna.** Ten magnetyzm nie jest proporcjonalny do zewnętrznego pola i jest odwrotnie proporcjonalny do różnicy temperatury bezwzględnej i temperatury krytycznej (punku Curie) $T-\theta$. Ferromagnetyki występują jedynie w postaci ciał stałych (pozostałe mogły mieć inne stany skupienia) W stanie ciekłym i gazowym ferromagnetyki zachowują się jak paramagnetyki.

![[Pasted image 20240203004052.png]]

![[Pasted image 20240203005551.png]]

## Napięcie powierzchniowe i międzyfazowe.

![[Pasted image 20240203010554.png]]


## Transport ciepła w materiałach.

![[Pasted image 20240203135542.png]]
