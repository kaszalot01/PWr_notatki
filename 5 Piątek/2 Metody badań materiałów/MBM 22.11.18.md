## Z poprzedniego wykładu
 - rodzaje polaryzacji
 - przenikalność elektryczna - współczynnik materiałowy, charakteryzuje właściwość gromadzenia energii w polu elektrycznym
 - względna przenikalność elektryczna jest zawsze większa od 1 i jest tym większa im więcej rodzajów polaryzacji występuje w dielektryku
 - małymi wartościami $\varepsilon_w$ charakteryzują się związki lotne
 - $\varepsilon_w$ jest funkcją temperatury, np. dla wody $\varepsilon_w$ maleje wraz ze wzrostem temperatury, ale dla oleju syntetycznego jest niemonotoniczna (ma maksimum dla ok. 10$^oC$), dla dielektryków jonowych $\varepsilon_w$ rośnie ze wzrostem temperatury, bo rozluźniają się wiązania jonowe i zwiększa się polaryzacja jonowa.
 - dla dielektryków, w których występuje tylko polaryzacja elektronowa i jonowa, $\varepsilon_w$ jest praktycznie niezależny od częstotliwości dla szerokiego zakresu wartości
 - $\varepsilon_w$ zawsze maleje w funkcji częstotliwości, ponieważ niektóre rodzaje polaryzacji nie nadążają za częstą zmianą prądu
 - przenikalność elektryczna jest wykładnikiem zjawisk polaryzacyjnych zachodzących w materiale dielektrycznym
 
 ## Stratność dielektryczna

Prąd strat występuje nie tylko w wyniku ruchu ładunków elektrycznych, lecz jest głównie związany ze zjawiskami polaryzacyjnymi, prowadzącymi do pochłaniania energii przez dielektryk.

Straty energii w dielektryku wywołane są polaryzacją i prądami upływu

$I = I_c + I_a + I_u$
$I_c+I_a=I_p$

$I_c$ - prąd ładowania związany z polaryzacją elektronową i jonową, nie wywołuje strat energii
$I_a$ - prąd absorpcyjny związany z polaryzacją dipolową. Jego energia zamieniana jest częściowo w energię potencjalną odkształceń sprężystych dipoli, a częściowo zużywana na pokonanie oporów stawianych przez ośrodek obrotom cząstek dipoli. Ta część energii zużywana jest nieodwracalnie na ciepło
$I_u$ - prąd upływu wywołany konduktywnością skrośna dielektryka. Przepływowi tego prądu towarzyszą straty energii elektrycznej na ciepło.
$I_p$ - prąd polaryzacyjny

W bilansie energetycznym w obwodach prądu stałego, starty energii związane ze zjawiskiem polaryzacji dielektryka są pomijalnie małe w porównaniu ze stratami upływu. $P_{strat}=UI_u$ 

Jeśli napięcie jest sinusoidalnie zmienne, wówczas proces ładowania i rozładowania będzie się powtarzać okresowo i starty związane z prądem polaryzacji nie mogą być pominięte.

`Ważne wykresy wskazowe dla skłądowych prądu w dielektrykach - w zeszycie od kompozytów`

Współczynnik strat dielektrycznych $tg \delta$ - cecha materiałów, nie zależy od prądów i napięć w kondensatorze, ani od jego kształtów i wymiarów. Jest to miara zdolności zamiany energii pola EM na ciepło. Charakteryzuje zdolność dielektryka do rozpraszania energii pola EM.

Kondensator rzeczywisty można modelować za pomocą kondensatora i opornika połączonych równolegle albo szeregowo. Większość rzeczywistych kondensatorów lepiej modelować układem równoległym.

`Ważne wyprowadzenie wzoru na tg(delta) w układzie równoległym - w zzeszycie. W domu wyprowadzić wzór dla ukłądu szeregowego.`

W dielektryku niepolarnym modelowanym równoległym układem zastępczym wartość oporu określa tylko rezystywność skrośną. ($R_{v}=\rho_{v} \cdot \frac{l}{S}$)

Ze wzrostem temperatury maleje rezystywność - więc (dla układu równoległego i dielektryków niepolarnych) - $tg\delta$ maleje wraz ze wzrostem częstotliwości i rośnie ze wzrostem temperatury.

![[Pasted image 20221118100740.png]]

Dla dielektryków polarnych - tangens w funkcji częstotliwości na początku rośnie bo rośnie energia tracona na obrót dipoli, potem maleje bo obrót dipoli nie nadąża za zmianami pola elektrycznego - zanika składowa dipolowa polaryzacji.

W funkcji temperatury - przy niskiej temperaturze duża lepkość więc ruch dipoli niewielki i obserwujemy małe straty (nie ma ruchu nie ma na czym tracić). Potem lepkość maleje na tyle aby ruch był możliwy ale generuje on stary energii, więc tangens rośnie. Przy najwyższej temperaturze dipole mogą poruszać się bez strat energii - tangens maleje.

![[Pasted image 20221118101614.png]]

W dielektrykach występują straty:

- przewodnościowe (w dielektrykach niepolarnych)
- polaryzacyjne (nomen-omen)
- jonizacyjne - występują w dielektrykach niejednorodnych zawierających wtrącenia gazowe, np. ceramice. Występują w przemiennym polu elektrycznym. `Wykres zależnosći od U w zeszycie`

W dielektrykach i układach rzeczywistych występuje zwykle jednocześnie straty kilku rodzajów. Stosunek wzajemny strat różnych rodzajów, **związany z budową i jakością dielektryku**, zmienia się wraz ze zmianą częstotliwości i temperatury.

Istotę znaczenie ma znajomość przebiegów dyspersyjne dla oceny jakości dielektryków $tg \delta = f(f,T)$ 

|Struktura dielektryka| dielektryk| $tg\delta$ @ f= 1MHz, T= 293K| Rodzaj start dominujących|
|-|-|-|-|
|Dielektryki o wiązaniu kowalencyjnym| | | |
| niepolarne| polistyren, PTFE, parafina| 0.0002| przewodnościowe|
|polarne| żywica fenolowo-formaldehydowa| 0.01| dipolowo-relaksacyjne|
|Dielektryki o wiązania jonowych| | | |
|o gęstej siatce krystalicznej| rutyl| 0.0001| przewodnościowe|
|...| | | | 

Pomiary C i $tg\delta$ 

1. Przygotowanie próbki do pomiarów
	1. Wybór kształtu próbki
		1. płasko-równoległe
		2. rurowe
	2. Wybór elektrod
		1. układ 2-elektrodowy
		2. układ 3-elektrodowy
2. Zależność
	1. $C=\varepsilon_0\varepsilon'f_{geom}=\varepsilon'C_0$  - obowiązuje tylko wtedy, gdy pole elektrycznie całkowicie przebiega w badanym ośrodku. Sytuacja komplikuje się, jeśli część jego linii sił przebiega w innym ośrodku
	2. Uogólniony przypadek pojemności kondensatora rzeczywistego - $C=C_g(=poj.\ geometryczna)+C_b(=poj.\ brzegowa)+C_r=(poj.\  rozproszona)$
		1. $C_g \sim \varepsilon l S$
		2. $C_b \sim \Psi \Pi_{i=1}^{i=n} \varepsilon_i \cdot l_{próbki}l_{elektrod}$   
			1. $\Psi$  - kształt układu
		3. $C_r \sim \Psi x$
			1. $\Psi$  - kształt układu
			2. $x$ - odległość od elementów uziemionych


