# W1
### Parametry charakteryzujące materiały
Współczynniki materiałowe - liczby charakteryzujące materiał niezależnie od wielkości i kształtu próbki.

Właściwość materiału - wielkość fizyczna, chemiczna lub umowna, która:

* daję się wyznaczyć bezpośrednio lub pośrednio przez pomiar innych wielkości
* wyrażona w określonych jednostkach lub bezwymiarowa 
* związana zależnościami znanymi lub wyznaczanymi eksperymentalnie z innymi właściwościami materiału

Wyróżniamy na przykład właściwości:
* **fizyczne**
* **chemiczne**
* specjalne
* technologiczne

Wśród właściwości fizycznych/chemiczny można dalej wyróżniać właściwości takie jak właściwości: termiczne, strukturalne - związane z wytrzymałością mechaniczną, **elektryczne (dielektryczne)** - wiążące się ze zjawiskiem przewodnictwa elektrycznego

Wśród elektrycznych właściwości możemy wymienić różne współczynniki materiałowe:
* rezystywność materiałów
* przenikalność elektryczna
* współczynnik strat dielektrycznych
* wytrzymałość elektryczna

### Energetyczny model pasmowy

`rysunek przedstawiający szerokość pasm dla przewodnika, półprzzewodnika i izolatora. Dla przewodnika pasmo podstawowe i przewodnictwa (walencyjne) szerokie, pasmo zabronione wąskie. Dla półprzewodnika wszystkie pasma podobnie szerokie. Dla izolatora pasmo zabronione szersze od pozostałych.`


![[Pasted image 20230211230856.png]]

Szerokości pasma przewodnictwa dla różnych typów materiałów

|Typ|Szerokoś pasma [eV]|
|-|-|
|Przewodniki| < 0.1 |
|Półprzewodniki|(0.1, 2.5) |
|Dielektryki|>2.5 |

Pasmo podstawowe: zakres energii elektronów walencyjnych związanych z jądrem atomowym.
Pasmo przewodnictwa: zakres energii elektronów walencyjnych, uwolnionych od jąder i będące swobodnymi nośnikami ładunku elektrycznego w ciele stałym

Dziki wzór na energię elektronu w temperaturze pokojowej W=kT, gdzie k to stała Boltzmanna a T to temperatura - wniosek w temperaturze pokojowej nie może występować przewodnictwo elektronowe w półprzewodnikach i dielektrykach

Do materiałów izolacyjnych (dielektryków) zaliczamy materiały o dużej przerwie energetycznej i w całości zajętym paśmie podstawowym.

Przewodnictwo rzeczywistych izolatorów wiąże się z przewodnictwem typu jonowego, zawartością zanieczyszczeń oraz z nieregularnościami struktury krystalicznej.

W materiałach nośniki ładunku są w stałym losowym ruchu. Po wprowadzeniu materiału w pole elektryczne, ruch staję się uporządkowany i rozpoczyna się przepływ prądu - prądu przewodnictwa (prądu upływu \[skrośny lub powierzchniowy\]).

W dielektryku w zasadzie nie ma swobodnych elektronów. Przewodzenie jest więc zawsze związane z ruchem jonów - charakter jonowy przewodnictwa. Jest ono zależne od:

* liczby jonów w jednostce objętości
* ich ruchliwości
* struktury materiału

wielkości te z kolei są zależne od warunków zewnętrznych:

* natężenie pola elektrycznego
* czynników dysocjujących
* czasu działania pola elektrycznego
* liczby i rodzaju zanieczyszczeń

**Przewodnictwo elektryczne** - ruch ładunków elektrycznych w materiale pod wpływem pola elektrycznego
(Jednostka pola elektrycznego $\frac{V}{m}$)

Obok prądu przewodnictwa pojawia się też prąd polaryzacyjny, zwany prądem przesunięcia dielektrycznego, związany z przemieszczeniem nośników w paśmie podstawowym i trwa tak długa aż ładunki te ustawią się w kierunku pola elektrycznego

Gęstość prądu w dielektryku

$$ j= j_u + j_p \quad v_{ui} \sim E$$
$$ j_u = \sum_{i=1}^{m} n_i q_i v_{ui} \quad v_{ui}=u_iE $$
$$ j_u = E \sum_{i=1}^{m} n_i q_i u_i \rightarrow j_u = \gamma E $$

$$ m\ -\ liczba\ rodzajów\ ładunków$$ $$ n_i\ -\ koncentracja\ nośników\ ładunków\ o\ wartości\ q_i $$$$v_{ui}\ -\ prędkość\ unoszenia$$

$$u_i\ - \ ruchliwość\  nośników$$ $$\gamma\ -\ konduktywność$$

$$E -\ natężenie\ pola\ elektrycznego\ [\frac{V}{m}]$$

W stałym polu elektrycznym prąd polaryzacyjny można zaniedbać ponieważ płynie tylko w momencie pierwotnego przyłożenia i usunięcia napięcia

$$\gamma=\frac{1}{\rho}$$ $$\rho \ - \ rezystywność$$

### Rezystywność skrośna i powierzchniowa
 
Pod wpływem przyłożonego z zewnątrz napięcia ładunki tworzą bardzo niewielki prąd upływu. Przepływ tego prądu w dielektrykach stałych odbywa się dwiema  drogami: na wskroś dielektryka tworząc prąd skrośny oraz po powierzchni tworząc prąd powierzchniowy.

# W2

### Z poprzedniego wykładu

Gęstość prądu w materiale dielektrycznym jest sumą prądu upływu i prądu polaryzacyjnego (prądu przesunięcia dielektrycznego)

Ruch nośników swobodnych w polu elektrycznym (prąd upływu/przewodzenia/przewodnictwa) będzie zależał od:
 * struktury dielektryka
 * koncentracji nośników 
 * natężenia pola elektrycznego.

rezystywność/konduktywność - stała materiałowa

### Rezystywność materiałów

Rozróżnia się dwa pojęcia: rezystywność skrośną i rezystywność powierzchniową.

Definicje:

* Rezystancja skrośna - $R_{\nu}$ - stosunek napięcia stałego doprowadzonego do próbki za pomocą elektrod do ustalonej wartości natężenia prądu płynącego między elektrodami na wskroś próbki bez uwzględnienia prądów powierzchniowych. Wyrażana jest w Omach $[\Omega]$
* Rezystancja powierzchniowa - $R_{s}$ -stosunek napięcia stałego doprowadzonego do próbki za pomocą elektrod do natężenia prądu płynącego między elektrodami na powierzchni próbki bez uwzględnienia prądów skrośnych. 
* Rezystywność skrośna - $\rho_{\nu}$ - \[brzydka definicja\] rezystancja skrośna odniesiona do wymiarów jednostkowych; \[ładna definicja\] stosunek natężenia stałego pola elektrycznego do gęstości ustalonego prądu płynącego między elektrodami na wskroś próbki bez uwzględnienia gęstości prądów powierzchniowych. Wyrażana jest w omach razy metr $\frac{V/m}{A/m^2} = \Omega m$
* Rezystywność powierzchniowa - $\rho_{s}=\frac{\rho_{\nu}}{d}, \rho_s=R_s \cdot \frac{b}{l}$, gdzie l - długość, b - szerokość przewodnika, d - grubość warstwy powierzchniowej

Rezystancję się mierzy, a rezystywności wyznacza - są stałymi materiałowymi

`Szereg rezystywnośći materiałów` - w $[\Omega m]$
![[Pasted image 20230211232517.png]]

materiały przewodzące - rezystywność rzędu $10^{-8}$ (srebro ma najniższą), węgiel = $10^{-5}$, 

materiały półprzewodzące - german=0,46 ,krzem=640

materiały dielektryczne - $10^{10}-10^{19}$ 

Jony są większe (masa, objętość) od elektronów dlatego przewodność dielektryków jest dużo mniejsza od przewodników

### Elektrody

Metody wytwarzania:

* z powłok przewodzących - wykonywane przez naniesienie na próbkę lakierów i past schnących w temperaturze pokojowej lub podwyższonej, zawierających sproszkowany pigment przewodzący (Au,Ag,Al)
* napylane w próżni lub rozpylane katodowo - inaczej metale rozpylane katodowo, metale parowane w próżni, stosuje się Au, Ag, Al, Cu - Al ma najniższa temperaturę topnienia więc taniej, samo aluminium też jest tanie. W katodowym stosuje się też Pt ($t_{top}=1800^oC$)
* naniesione przez metalizację natryskową - stosuje się tylko do pomiarów rezystancji skrośnej (Ag,Al,Cu,Zn)
* z ciekłego metalu - Hg, tylko w wyjątkowych przypadkach, na pewno nie w podwyższonej temperaturze
* z grafitu koloidalnego - proste w użyciu, nie nadają się do materiałów higroskopijnych 
* z folii metalowej - najczęściej folia aluminiowa 5-20 $\mu m$, przytwierdzana cienką warstwą oleju transformatorowego (ew. parafinowego)

Warunki, które muszą spełniać elektrody:

1. Elektroda nie może być toksyczna
2. Musi doskonale przylegać do badanej próbki
3. Musi wykazywać stałe właściwości w czasie badania (w warunkach oddziaływania różnych czynników zewnętrznych - podwyższona temperatura itd.) 
4. Materiał elektrody nie może być aktywny chemicznie w stosunku do badanej próbki

Do pomiaru rezystancji skrośnej albo powierzchniowej należy stosować układ trójelektrodowy - system elektrod z pierścieniem ochronnym. Zadaniem pierścienia jest wyeliminowanie prądu powierzchniowego przy pomiarze rezystancji skrośnej i vice versa. 

![](https://i.imgur.com/VvboZfK.png)

Budowa elektrod z pierścienie ochronnym dla pomiarów rezystancji skrośnej:

* Elektroda na spodzie - napięciowa
* Okrąg wewnętrzny - elektroda chroniona
* Pierścień - elektroda ochronna

Dla pomiarów rezystancji powierzchniowej - pierścień jest elektrodą napięciową a ta na spodzie jest ochronna

`Rysunek obu układów`

![[Pasted image 20230212154434.png]]

Trzeba przykładać takie napięcie żeby natężenie pola było w zakresie $0.1-1kV/mm$

# W3

### Z ostatniego wykładu

Do pomiaru rezystancji skrośnej i powierzchniowej stosuje się układ trójelektrodowy.

Zadaniem pierścienia ochronnego jest:
- ujednorodnienie pola elektrycznego
- wyeliminowanie prądów powierzchniowych gdy mierzymy rezystancję skrośną
- vice versa jw.

Natężenie pola elektrycznego przy pomiarach - $0.1-1\frac{kV}{mm}$

### Pomiar rezystancji dielektryków - w której chwili mierzymy?

W chwili przyłożenia napięcia prąd ma dwie składowe - prąd upływu i polaryzacji. 

`Wykres zależnośći prądu płynącego przez dielektryk od czasu`
![[Pasted image 20230211232827.png]]

Zasada kciuka dla pomiaru rezystancji powierzchniowej dielektryków stałych- odczekać 60\[s\] przed pomiarem (dla materiałów tradycyjnych, powszechnie stosowanych)

Zasada kciuka dla pomiaru rezystancji skrośnej d.s. - odczekać 60\[s\], jeśli nie będzie stabilny wykonujemy dynamiczną charakterystykę (pomiary po 1, 2, 3, 5, 10, 25, 50, 100 minutach)

Dla dielektryków ciekłych - odczekiwać 5 \[min\] (skrośna, powierzchniowej się nie mierzy)

W nowoczesnych materiałach prąd przejściowy może płynąc przez dziesiątki lat

`Porównanie pomairów w układach dwu- i trój-elektrodowych`

![[Pasted image 20230212004536.png]]

### Metody pomiaru rezystancji

Niezbędny pomiar rezystancji w zakresie $10^6$ do $10^{18} [\Omega]$.
Metody:
1. techniczne
2. mostkowe
3. porównawcze
4. ładowania kondensatora
5. elektrometryczne

|metody| pomiar rezystacnji|
|-|-|
|1,2,3| $<10^{13}$|
|4,5|$>10^{13}$|

Metoda techniczna - metoda woltomierz-amperomierz, porównanie napięcia doprowadzonego do elektrod i prądu płynącego między nimi ($R_x=\frac{U_x}{I_x}=\frac{U_x}{\alpha\cdot p  \cdot C_i}$ ), gdzie $\alpha [dz]$ - wychylenie galwanometru, $C_i [\frac{A}{dz}]$ - stała prądowa,  $p$ - przekładnia bocznika.

![[Pasted image 20230212154756.png]]

Metoda ładowania kondensatora - pomiar napięcia $U_c$ na kondensatorze wzorcowym $C_N$, ładowanym prądem płynącym przez badaną rezystancję, oraz czasu $t$, po upływie którego na pojemności $C_N$ pojawi się napięcie $U_c$, rezystancja dana jest wzorem $R_x=\frac{U\cdot t }{C_n \cdot U_c}$ , gdzie U to napięcie doprowadzone do próbki.

![[Pasted image 20230212154829.png]]

# W4

Najczulsze galwanometry mierzą z dokładnością do $10^{-11}A/dz$
Pospolite galwanometry do $10^{-9} A/dz$

Z tego powodu do pomiaru małych prądów stosuje się **elektrometry**.

Elektrometr - miliwoltomierz mierzący spadek napięcia na zamontowanym na wejściu rezystorze wzorcowym $R_N$ 

![[Pasted image 20230212154854.png]]

Warunki doboru $R_N$:

- wzorcowy (o dokładnie znanej rezystancji)
- opór stabilny w czasie
- liniowa charakterystyka prądowo-napięciowa 
- wysoka wartość oporu  $10^8-10^{12}\ [\Omega]$ 

Elektrometry przeznaczone do pomiaru bardzo wysokich rezystancji nazywa się *teraomometrem*. Ma on wbudowane źródło napięcia pomiarowego.

![[Pasted image 20230212154913.png]]

$$R_x=\frac{U_0 \cdot R_N}{U_{wyj}}$$ 
Czynniki zewnętrzne:

- napięcie pomiarowe
- temperatura
- czas 
- wilgotność

Prawo Ohma jest dobrze spełnione przez metale, gorzej dla półprzewodników i dielektryków. Powyżej pewnego krytycznego/granicznego napięcia charakterystyka odbiega od liniowości. 

![[Pasted image 20230212154929.png]]

W przypadku dielektryków o nieliniowości **nie świadczy napięcie** tylko natężenie pola elektrycznego. Charakterystyka jest linowa kiedy pole jest jednorodne. Pole jest jednorodne jeżeli dla różnych napięć pomiarowych rezystancja jest taka sama. 

Zależność rezystywności skrośne kwarcu od temperatur:

![[Pasted image 20230212154943.png]]

A - kwarc bezpostaciowy
B - krystaliczny prostopadle do głównej osi kryst.
C - krystaliczny równolegle do głównej osi kryst.

Zmiany w czasie 

![[Pasted image 20230212154953.png]]

Dla czasów długich: stała, po długim czasie spada (starzenie)
Dla czasów krótkich: rośnie w pierwszych 60s (prąd polaryzacyjny), potem stała

Wpływ wilgotności zależy od rodzaju dielektryka i szczególnie uwidacznia się na powierzchniach materiałów hydrofilowych, tworzących błonę wodną.

|rodzaj materiału| rezystancja skrośna| rezystancja powierzchniowa|
|-|-|-|
|higroskopijne | spada wraz ze wzrostem wilgotności| spada wraz ze wzrostem wilgotności|
|jonowe i dipolowe| jest stała| spada wraz ze wzrostem wilgotności|
|neutralne | jest stałą| jest stała| 

Spadki nie sią liniowe

Rezystywność skrośna - podsumowanie

- Rezystywność skrośna dielektryków maleje ze wzrostem temperatury w wyniku zwiększenia jonizacji. Szczególnie silny wpływ obserwuje się w cząstkach z wiązaniami jonowymi. np. szkło sodowe
- rezystywność skrośna dielektryków ciekłych i stałych zależy silnie od stopnia zanieczyszczenia i zawilgocenia. Zanieczyszczenia tworzą dodatkowe źródło swobodnych jonów.
- najwyższe wartości rezystywności skrośnej osiągają dielektryki niepolarne
- ... (przełączyła slajd)

Rezystywność powierzchniowa - podsumowanie


- odnosi się tylko do dielektryków stałych
- zależy bardzo silnie od ich budowy, stopnia zanieczyszczenia, od stopnia zawilgocenia ich powierzchni
- największe wartości dla dielektryków, których powierzchnie nie ulegają zwilżeniu: parafina 10e16 Om, najmniejsze...
- ... (przełączyła slajd)

## Konduktywność półprzewodników

- konduktywność metali, dielektryków i półprzewodników jest proporcjonalna do iloczynu ruchliwości i koncentracji
- wzrost temperatury i związane z tym zwiększenie drgań sieci krystalicznej zmniejszają ruchliwość elektronów i dziur w półprzewodniku
- w przeciwieństwie do metalu, gdzie koncentracja elektronów jest stałą, w półprzewodnikach zależy ona bardzo silnie od temperatury
- przy wzroście temperatury zachodzą w półprzewodniku dwa procesy oddziałujące na wartość konduktywności: zmniejszanie się ruchliwości i bardzo silny wzrost koncentracji nośników

`Zależnośc rezystywności czystego germanu od teperatury  - spada`

![[Pasted image 20230212155112.png]]

Konduktywność półprzewodnika samoistnego w temperaturze pokojowej jest mała.
Trzeba domieszkować.

Konduktywność półprzewodnika

$$\gamma = \gamma_s + \gamma_d $$

gdzie $\gamma_s$ to konduktywność samoistna a $\gamma_d$ to konduktywność niesamoistna (pochodząca od domieszek)

Konduktywność półprzewodników domieszkowych od temperatury - obszar I - rośnie, II- maleje, III - rośnie.

![[Pasted image 20230212155127.png]]

|Obszar| konduktywność| dlaczego| główny udział|
|-|-|-|-|
| 1| rośnie| $\gamma_d >> \gamma_s$| konduktywność niesamoistna|
|2| maleje| wszystkie atomy domieszek zostały zjonizowane - wzrost koncentracji nośników zostaje zahamowany, znaczenie zaczyna mieć ruchliwość która spada ze wzrostem temperatury| ruchliwość nośników|
|3| rośnie| zaczyna mieć znaczenie konduktywność samoistna - nośniki przechodzą z pasma walencyjnego w pasmo przewodnictwa| konduktywność niesamoistna|

## Przenikalność elektryczna

Zachowanie dielektryków pod wpływem zewnętrznego pola elektrycznego zależy od ich:

- właściwości związanych z transportem nośników ładunku
- właściwości związanych ze zjawiskami polaryzacji

Właściwości te są wzajemnie zależne i zależą od wielu czynników zewnętrznych takich jak:

- natężenie pola elektrycznego
- zależność pola elektrycznego do czasu (stałe, zmienne, impulsowe)
- temperatura
- działanie promieniowania elektromagnetycznego

Dielektryki - przerwa energetyczna jest na tyle duża, że w normalnych warunkach liczba elektronów zdolnych znaleźć się w paśmie przewodnictwa jest bardzo mała.

Dielektryk - zbiór dipoli i ładunków swobodnych

Polaryzacja elektryczna $P$ - makroskopowy moment dipolowy
Indukcja elektryczna $D=\varepsilon E$ 

Polaryzacja dielektryka - zjawisko polegające na utworzeniu dipoli elektrycznych lub orientacji już istniejących dipoli jako reakcja na przyłożone pole elektryczne.

Zdolność do polaryzacji jest główną właściwością dielektryków.

# W5

Dielektryk można traktować jako neutralny elektrycznie zbiór dipoli i ładunków swobodnych. Jeśli dipole trwałe lub indukowane są przynajmniej częściowo uporządkowane w jakimś określonym kierunku, określona objętość dielektryka będzie miała wypadkowy, makroskopowy moment dipolowy P zwany wektorem polaryzacji elektrycznej lub polaryzacją elektryczną

Pole elektryczne E w jakimś punkcie obszaru związane jest z indukcją elektryczną zależnością:
$$ D= \varepsilon E = \varepsilon_0 \varepsilon_w E\ [\frac{A\cdot s}{m^2} (?)] $$

$\varepsilon$ - bezwzględna przenikalność elektryczna ośrodka, $\varepsilon_w$ - względna polaryzacja elektryczna, $\varepsilon_0$ - przenikalność elektryczna próżni

Polaryzacja dielektryków jest rezultatem **5 podstawowych zjawisk**: polaryzacji elektronowej, atomowej, jonowej, orientacyjnej (dipolowej), makroskopowej (związanej z ładunkiem przestrzennym)

Mechanizmy polaryzacji:

- polaryzacja elektronowa - pole elektryczne wywołuje względne przesuniecie dodatniego i ujemnego ładunku atomu. Atom uzyskuje w ten sposób indukowany elektryczny moment dipolowy
- polaryzacja atomowa (molekularna, cząsteczkowa) - jest rezultatem przesunięcia się względem siebie atomów cząsteczki posiadających różne ładunki. Atomy mają znacznie większe masy niż elektrony, dlatego reakcja na zmianę pola elektrycznego jest wolniejsza. Jej udział w całkowitej polaryzacji jest znacznie mniejszy niż polaryzacji elektronowej, toteż niekiedy byłą ona pomijana
- polaryzacja jonowa - pole wywołuje względne przesunięcie dodatnich i ujemnych jonów w cząsteczce. Indukowany jest wówczas dodatkowy moment dipolowy
- polaryzacja dipolowa (polaryzacja orientacji) - jeśli w nieobecności pola istnieją w ośrodku stałe momenty dipolowe ustawione w różnych przypadkowych kierunkach. Pole elektryczne powoduje ich obrót i uprządkowanie w kierunku pola.
- polaryzacja makroskopowa - związana z ładunkiem przestrzennym. Ładunki swobodne w dielektryku przemieszczają się pod wpływem pola. Zatrzymują się na granicach ziaren lub nieprawidłowościach struktury.

`rysunek różnych polaryzacji`

![[Pasted image 20230212153949.png]]

Polaryzacja elektronowa

- występuję we wszystkich dielektrykach. Polega na przesunięciu zewnętrznych powłok elektronowych względem dodatnich jąder
- polaryzacja elektronowa jest praktycznie bezinercyjna, przebiega w czasie $10^{-15}s$
- towarzyszące jej odkształcenie jest całkowicie sprężyste
- praca włożona w jej powstanie nie zamienia się w ciepło, lecz zostaje zmagazynowana w polu elektrycznym - polaryzacja jest bezstratna
- powstałe dipole elektryczne mają charakter dipoli indukowanych - po usunięciu zewnętrznego pola elektrycznego polaryzacja elektronowa natychmiast ustępuje

Polaryzacja jonowa

- występuje tylko w takich materiałach, których cząsteczki zbudowane są z jonów
- polega na wzajemnym, sprężystym rozsunięciu różnoimiennych jonów
- zjawisko to ze względu na bezwładność stosunkowo ciężkich jonów, zachodzi w czasie $10^{-13} s$, a więc wolniej od polaryzacji elektronowej
- nie powoduje strat energii na ciepło
- ustępuje po uśnięciu zewnętrznego pola elektrycznego

Polaryzacja dipolowa

- występuje w dielektrykach stałych, ciekłych i gazowych z cząsteczkami o charakterze trwałych dipoli elektrycznych
- pod nieobecność pola elektrycznego cząsteczki dielektryka znajdują się w chaotycznym ruchu cieplnym, wskutek czego momenty ich dipoli elektrycznych wzajemnie się znoszą i wypadkowy moment dipolowych jest równy zeru
- w zewnętrznym polu elektrycznym na cząsteczki - dipole elektryczne - wywierane są siły porządkujące, starające się ustawić je równolegle do pola elektrycznego
- stopień uporządkowania dipoli wzdłuż linii sił pola elektrycznego jest zależny od dwóch przeciwstawnie działających czynników:
	- wartości zewnętrznego pola elektrycznego
	- wartości temperatury, od której zależna jest intensywność ruchu cieplnego cząsteczek, przeciwstawiającego się elektrycznych siłom porządkujących. Im wyższa temperatura, tym bardziej chaotyczna orientacja dipoli w wyniku bardzie intensywnych zderzeń i drgań cząsteczek. Dla określonej temperatury ustala się określony stopnień uporządkowania dipoli, uwarunkowany tymi dwiema przeciwstawnymi tendencjami

Polaryzacja dielektryka zawierającego cząstki polarne jest sumą pięciu efektów:
$$P=P_{el}+P_{at}+P_j+P_d+P_m$$
Do czterech mikroskopowych mechanizmów polaryzacji (zachodzą w pojedynczych atomach lub cząsteczkach) dodano makroskopowy mechanizm polaryzacji, gdy w dielektryku znajduje się pewna, z reguły bardzo niewielka liczba ładunków swobodnych (ładunek przestrzenny). Wędrują one w dielektryku pod wpływem pola elektrycznego zbierając się na niedoskonałościach siatki krystalicznej (zanieczyszczenia, granice ziaren, mikropęknięć). Ten typ polaryzacji wymaga najdłuższych czasów do osiągnięcia stanu równowagi.

Makroskopowo, polaryzacja objawia się tym, że zwiększa się pojemność elektryczna kondensatora wypełnionego dielektrykiem. 

Kondensator - element elektryczny (elektroniczny), zbudowany z dwóch przewodników (okładek) rozdzielonych dielektrykiem. Doprowadzenie napięcia do okładek kondensatora powoduje zgromadzenie się na nich ładunku elektrycznego. Zdolność kondensatora do gromadzenia ładunku określa **pojemność - C \[F]**.

Dla kondensatora próżniowego:

$$ Pole\ elektryczne - E_0=\frac{U=napięcie}{l=odległość\ między\ okładkami}$$

Dla kondensatora z dielektrykiem - w polu $E_0$ (panującym przed włożeniem dielektryka) dielektryk ulega polaryzacji. Na powierzchni dielektryka powstaje ładunek, który zrównoważyć musi dodatkowy ładunek na okładkach kondensatora.

Większy ładunek elektryczny zebrany na okładkach kondensatora przy tym samym napięciu oznacza, że pojemność kondensatora uległa zwiększeniu dzięki wypełnieniu kondensatora dielektrykiem.

Pojemność kondensatora:

$$ C=\varepsilon_0 \varepsilon_w \cdot \frac{S = powierzchnia\ okładki\ kondensatora}{l = odległość\ między\ okładkami}=\frac{Q=ładunek}{U=napięcie}$$

Przenikalność elektryczna względna dielektryka liczbowo jest równa stosunkowi pojemności elektrycznej kondensatora z danym dielektrykiem do pojemności tego samego kondensatora po usunięciu dielektryka. Przenikalność elektryczna charakteryzuje właściwość gromadzenia energii w polu elektrycznym.

Względna przenikalność elektryczna jest tym większa nim silniejsze jest zjawisko polaryzacji w dielektryku (im więcej rodzajów polaryzacji zachodzi w materiale)

Przenikalność jest funkcją stanu skupienia, temperatury, częstotliwości *czegoś tam*

Małymi wartościami przenikalności względnej charakteryzują się:

- dielektryki lotne
- dielektryki bez polaryzacji jonowej, dipolowej lub każdej innej

Zależność przenikalności od temperatury dla ciekłych dielektryków jest znacząca (zmiana o 60 dla wody w przedziale 300 stopni)

Zależność nie musi być liniowa ani nawet monotoniczna

Dla dielektryków stałych o cząstkach charakteryzujących się wiązaniami jonowymi wzrasta przy wzroście temperatury - osłabia się więź jonów co ułatwia polaryzację jonową. 

Dla dielektryków dipolowych natomiast maleje - zwiększa się chaotyczny ruch dipoli

Przenikalność elektryczna względna zawsze maleje w zależności od częstotliwości

`wykres zależność składowych względniej przenikalności elektrycznej od częstotliwości

![[Pasted image 20230212154031.png]]

# W6

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

`Ważne wykresy wskazowe dla skłądowych prądu w dielektrykach`

![[Pasted image 20230212211353.png]]

Współczynnik strat dielektrycznych $tg \delta$ - cecha materiałów, nie zależy od prądów i napięć w kondensatorze, ani od jego kształtów i wymiarów. Jest to miara zdolności zamiany energii pola EM na ciepło. Charakteryzuje zdolność dielektryka do rozpraszania energii pola EM.

Kondensator rzeczywisty można modelować za pomocą kondensatora i opornika połączonych równolegle albo szeregowo. Większość rzeczywistych kondensatorów lepiej modelować układem równoległym.

`Ważne wyprowadzenie wzoru na tg(delta) w układzie równoległym`

![[Pasted image 20230212211704.png]]

W dielektryku niepolarnym modelowanym równoległym układem zastępczym wartość oporu określa tylko rezystywność skrośną. ($R_{v}=\rho_{v} \cdot \frac{l}{S}$)

Ze wzrostem temperatury maleje rezystywność - więc (dla układu równoległego i dielektryków niepolarnych) - $tg\delta$ maleje wraz ze wzrostem częstotliwości i rośnie ze wzrostem temperatury.

![[Pasted image 20221118100740.png]]

Dla dielektryków polarnych - tangens w funkcji częstotliwości na początku rośnie bo rośnie energia tracona na obrót dipoli, potem maleje bo obrót dipoli nie nadąża za zmianami pola elektrycznego - zanika składowa dipolowa polaryzacji.

W funkcji temperatury - przy niskiej temperaturze duża lepkość więc ruch dipoli niewielki i obserwujemy małe straty (nie ma ruchu nie ma na czym tracić). Potem lepkość maleje na tyle aby ruch był możliwy ale generuje on stary energii, więc tangens rośnie. Przy najwyższej temperaturze dipole mogą poruszać się bez strat energii - tangens maleje.

![[Pasted image 20221118101614.png]]

W dielektrykach występują straty:

- przewodnościowe (w dielektrykach niepolarnych)
- polaryzacyjne (nomen-omen)
- jonizacyjne - występują w dielektrykach niejednorodnych zawierających wtrącenia gazowe, np. ceramice. Występują w przemiennym polu elektrycznym. `Wykres zależnosći`

![[Pasted image 20230212211842.png]]

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


# W7

Spóźniłem się.

Wpływ sposobu nakładania elektrod:
największy uchyb jest spowodowany przez cienką warstwę powietrza między elektrodą a powierzchnią próbki, Jest on szczególnie duży, gdy badany materiał ma małą grubość lub gdy jego przenikalność elektryczna jest bardzo duża.

- im większa szczelina, tym większy błąd pomiaru
- istnienie szczeliny powietrznej jest w tym bardziej krytyczne, im większa przenikalność elektryczna materiału
- dla materiałów o dużej przenikalności elektrycznej przyleganie musi być bardzo dobre

Rzeczywisty dielektryk w układzie można zamodelować dwoma pojemnościami - $C_d$ i $C_p$ - pojemnością kondensatora powietrznego. Pojemność zmierzona $C_w$ jest sumą szeregowo połączonych pojemność dielektryka i kondensatora powietrznego $C_w=\frac{C_pC_d}{C_p+C_d}$

Wpływ doprowadzeń:
- Niskie częstotliwości (nie przepisałem)
- Częstotliwości $10MHz-100MHz$
	- wpływ $r_d$ (rezystancji przewodów próbka-miernik, rezystancja elektrod, rezystancje kontaktowe) $tg\delta_w=(r_x+r_d)C_x\omega=tg\delta_x+r_d\omega C_x$ (szeregowy układ zastępczy). $r_d$ wyznacza się badając dla badanej aparatury kondensatory bezstratne.
	- naskórkowość - en.skin efect (dla f>1MHz) $R \sim \sqrt{f}$
Wpływ indukcyjności:
- $C_m=\frac{C_x}{1-LC_x\omega^2}$
- obserwujemy: $C_m \neq C_x, \varepsilon_m>\varepsilon_x$

Układy pomiarowe (pomiar - charakterystyki $\varepsilon = f(\omega, T), tg\delta = f(\omega, T)$, powód - wpływ doprowadzeń):

- poniżej 20Hz - pomiar charakterystyk prądu ładowania i rozładowywania kondensatora w funkcji czasu
- 20Hz-100kHz - metody mostkowe
- 100kHz-300MHz - metody rezonansowe
- 300MHz - 50GHz - metody mikrofalowe
	- przy najwyższych częstotliwościach - metody pośrednie (pomiar współczynnika załamania światła $n^2=\varepsilon$)

Pomiary mostkowe - porównanie parametrów kondensatora z elementami wzorcowymi tego samego rodzaju w momencie równowagi mostka (prąd w przekątnej równy zero).

## Wytrzymałość elektryczna

Podwyższając napięcie przyłożone do okładzin kondensatora z dielektrykiem osiąga się napięcie krytyczne zwane napięcie przebicia $U_p$, przy którym następuje przebicie elektryczne dielektryka.

Natężenie pola elektryczne $E_p$, odpowiadające napięciu przebicia, nazywa się **wytrzymałością elektryczną dielektryka**.

Określa się je dla kondensatora płaskiego jako:
$$E_p=\frac{U_p}{l}$$
Wytrzymałość elektryczna zależy od:

- kształtu elektrod - wpływa on silnie na wartość natężenia lokalnego pola elektrycznego. Dla elektrod płaskich pole jest równomierne. Dla elektrod ostrzowych pole jest silnie nierównomierne (lokalne wyładowania, niszczenie izolacji w pobliżu elektrody) Wytrzymałość elektryczna ostrzowego układu jest znacznie niższa niż układu płaskiego. 
- stanu zawilgocenia izolacji - silnie obniża wytrzymałość elektryczną. (spada ponad dwukrotnie dla wilgotności 0.02%)
- temperatury - wzrost prowadzi do zmniejszenia wytrzymałości
- grubości warstwy izolacji - nieliniowa, zależy od rodzaju dielektryka
- rodzaju napięcia - stałe, przemienne, udarowe. Wartości wytrzymałości największe dla udarowych a najniższa dla stałego (kwestia czasu).

> uwaga trudne słowo - prawo Paschena

Zgodnie z matematycznym ujęciem  prawa Paschena napięcie przebicia dla danego gazu, dla danego materiału elektrod, w danej temperaturze jest funkcją $p\cdot d$ gdzie p to jest ciśnienie a d to odległość międzyelektrodowa. Graficznym ujęciem są krzywe (charakterystyki) Paschena. Dla różnych gazów kształt tych charakterystyk jest zbliżony.  

## Elektrety

Elektretem nazywamy dielektryk, który wytwarza w swoim otoczeniu trwałe, zewnętrzne pole elektryczne. Źródłem w elektrecie są nagromadzone w nim ładunki elektryczne lub wytworzony w dielektryku i "zamrożony" stan polaryzacji. 
Zjawisko gromadzenia trwałego ładunku elektrycznego w dielektrykach daje duże możliwości ich praktycznych zastosowań. Możliwości zastosowania elektretów związane są z czasem życia ładunku elektrycznego (ostatnie niepewne, zmieniła slajd)

Metody wytwarzania elektretów

- metoda termoelektryczna - wytwarzanie elektretu z polimeru dipolowego (pozostałe metody - ładunek z zewnętrznego źródła)
- metoda ulotowa, ze względu na prosty proces technologiczny umożliwia stosowanie jej do wytwarzania elektretów na skalę przemysłową
- metoda cieczowa, pozwala na otrzymanie stabilnych elektretów o dużej gęstości powierzchniowej ładunku
- metoda elektronowiązkowa 

Metoda termoelektryczna `podkrędocny schemat, którego nie przepisałem` 

Temperatura polaryzacji to temperatura, w której możliwe jest ustawienie dipoli w kierunku pola elektrycznego. Dla wosków i żywic - temperatura mięknienia. Dla polimerów dipolowych, trochę większa niż temperatura zeszklenia.

Warunki procesu:

1. podnosimy temperaturę do temperatury polaryzacji
2. przykładamy pole elektryczne
3. ochładzamy utrzymując pole -"zamrażanie stanu polaryzacji"

Metody implantacji ładunków z zewnętrznego źródła:

1. Metoda ulotowa - próbka położna na elektrodzie płaskiej, a nad nią zawieszona jest elektroda ostrzowa, przykładamy wysokie napięcie. Prosta, nagminnie stosowana.  
2. Metoda cieczowa - wprowadzanie ładunku pod wpływem napięcia z niezwilżającej cieczy przewodzącej. Następnie proces starzenia i migracja ładunków w głąb materiału.
3. Metoda ładowania wiązką niskoenergetycznych elektronów - zalety metody - można zgromadzić kontrolowane gęstości ładunku jednego znaku na głębokości ściśle określonej zasięgiem elektronów. Dla takich, dobrze zdefiniowanych, elektretó można badać procesy zmiany przestrzennego rozkłądu ładunku oraz jego kontrolowany zanik. 

# W8

## Z ostatniego wykładu

Elektret - dielektryk, który wytwarza stałe pole elektryczne.

`Próbowałem przepisać "podkręcony schemat" z ostatniego wykładu, zmieniła slajd zanim przepisałem`

![[Pasted image 20230212224833.png]]

## Dalej o elektretach

Zalety metody ładowania monoenergetycznymi elektronami, z badawczego punktu widzenia, polegająca na tym, że w dielektryku można zgromadzić kontrolowane gęstości ładunku jednego znaku na głębokości ściśle określonej zasięgiem elektronów. Dla takich dobrze zdefiniowanych elektretów można badać procesy zmiany przestrzennego rozkładu ładunku oraz jego kontrolowany zanik. `

Stanowisko elektrowiązkowe - strumień elektronów -> soczewki -> próbka

Charakterystyki średniego położenia ładunku elektrycznego w materiale

`dwa wykresy nieliniowo monotonicznie rosnące, położenie w mikrometrach w funkcji energii wiązki elektronów`

![[Pasted image 20230212214131.png]]

Rozkład ładunku elektrycznego w folii PE

![[Pasted image 20230212213936.png]]


Pomiar gęstości powierzchniowej ładunku
Metoda kompensacyjna (metoda głowicy wibracyjnej) układ działa na zasadzie kompensacji własnego pola elektretu przez sztucznie wprowadzone pole zewnętrzne.

Elektroda pomiarowa (wibracyjna) wibruje w polu elektretu, który wytwarza stałe pole elektretu, oraz w polu wprowadzanym przez elektrodę kompensacyjną. Sygnał jest wzmacniany i prowadzany do oscyloskopu.

![[Pasted image 20230212214041.png]]

Gęstość prądu:

$$ q_s = \varepsilon_w \varepsilon_0 \frac{U_K}{d}$$

gdzie d to grubość próbki
Metoda indukcji elektrostatycznej 

![[Pasted image 20230212214023.png]]

Jeżeli płytkę elektretową umieścić między dwiema metalowymi elektrodami to na zasadzie indukcji elektrostatycznej, w elektrodach zostanie wyindukowany ładunek różnoimienny. 

![[Pasted image 20230212214303.png]]

1. Zamykamy wyłącznik żeby odprowadzić ładunek z górnej części górnej elektrody (na rysunku dodatni) do ziemi
2. Odsuwamy elektrodę od próbki i otwieramy włącznik. Pozostałego (ujemnego na rysunku) ładunku już nic nie "trzyma" i płynie do kondensatora. Mierzymy napięcie i gęstość wyznaczamy ze wzoru: $q_s=\frac{C_N \cdot U}{S}$ gdzie S to pole powierzchni elektrody

W nowoczesnych elektretach polimerowych, o wartości wykonanego elementu decyduje zwykle homoładunek i jego stabilność w czasie. Pojęcie czasu życia elektretu można więc utożsamić z czasem relaksacji homoładuknu w temperaturze pokojowej.

Matematyczny model oceny wypadkowego czasu życia elektretu oparty jest na równaniu Arrheniusa:

$$q(T,t) = q_s (0,T)exp(\frac{-t}{\tau(T)})$$

Badanie zaniku ładunku:

- w warunkach izotermicznej depolaryzacji
- w procesie nieizotermicznym (TSQ) lub szacowania czasu życia ładunku na podstawi badań termicznie stymulowanych prądów (TSD)

Zastosowania elektretów:

- przetworniki elektroakustyczne:
	- mikrofony elektretowe
	- słuchawki i głośniki elektretowe
- przetworniki elektromechaniczne
- elektrografia
- aerozolowe filtry elektretowe
- zastosowania biomedyczne

Elektretowe filtry przeciwpyłowe - głównym elementem filtru jest polimerowa włóknina elektretowa. Jest ona doskonałym materiałem do wychwytywania cząstek aerozoli lub pyłu, w tym również submikronowych. Uzyskano już wysoką efektywność usuwania cząstek o średnicach większych niż 1 mikrometr, wciąż jednak oczekuje się na rozwiązanie pozwalające na usuwanie cząstek submikronowych.

Cząstki submikronowe - głęboka penetracja układu oddechowego, zjawiska atmosferyczne, metale ciężkie

Zalety filtrów z ładunkiem elektrycznym:

- duża skuteczność filtracji
- wychwytywanie cząstek submikronowych
- mały opór stawiany przepływającemu medium
- równomierne osadzenie zanieczyszczeń w strukturze włókniny, co opóźnia "zapychanie się" wkładu i wydłuża czas użytkowania filtrów
- brak konieczności stosowania zewnętrznego źródła zasilania (ładunku elektryczne są wbudowane w strukturę materiału)
- łatwa eksploatacja
- niski koszt produkcji


Materiały do bezpośredniego kontaktu z krwią

Powierzchnię śródbłonka pokrywa tzw. glikokaliks - warstwa glikoprotein i glikozoaminoglikanów, których 80% stanowi siarczan heparyny. Są to nośniki ujemnych ładunków, które nadają wewnętrznej powierzchni naczyń ujemny potencjał elektryczny.

Cząsteczki białka i elementy upostaciowione krwi są również nosicielami ujemnego ładunku elektrostatycznego.

Uznając znaczenie ładunku elektrycznego w procesie tworzenia zakrzepów przyjęto, że powierzchnia materiału, przeznaczonego do kontaktu z krwią, powinna być nosicielem ujemnego ładunku elektrostatycznego. Implantacja ładunku elektrycznego -> efekt elektretowy.

Dziana poliestrowa proteza naczyń krwionośnych "Dallon"

Sposoby zapobiegania elektryzacji:

- zwiększenie wilgotności powietrza
- antystatyki - substancje, które eliminują lub zmniejszają elektryzowanie się ciał stałych.
- wprowadzanie włókien metalicznych, stosowanie napełniaczy przewodzących (np. sadzy)

Antystatyki może być prowadzany:
- zewnętrznie poprzez nanoszenie na powierzchnie wodnych lub alkoholowych roztworów
- wewnętrznie - dodatek domieszek (związki azotu, fosforu i siarki)


## Materiały magnetyczne

Wszystkie znane pierwiastki, związki chemiczne i materiały mogą zostać sklasyfikowane na podstawie ich własności magnetycznych. Każde ciało umieszczone w polu magnetycznym magnesuje się

Miarą stopnia namagnesowania jest magnetyzacja (albo namagnesowanie)

Magnetyzacja jest to moment magnetyczny przypadający na jednostkę objętości

Właściwości magnetyczne materiału charakteryzują podatność magnetyczna, która określa związek między namagnesowaniem i natężeniem pola magnetycznego

$$\vec{M}=\chi \vec{H}$$ 
Zależnie od podatności magnetycznej, wszystkie materiały można podzielić na trzy rodzaje:

- diamagnetyki - mała, ujemne wartość podatności magnetycznej $\chi \in (0.1, 10)\cdot 10^{-6}$ 
- paramagnetyki $\chi \in (0,1)$
- ferromagnetyki $\chi >1$ 

W teorii pola elektromagnetycznego indukcję magnetyczną B definiuje sie jako:

$B= \mu _0 H + \mu_0 M$
$B= \mu_0 H + \mu_0 \chi H = \mu_0 (1+ \chi)H$

$\mu_w=1+\chi$

$B=\mu_0 \mu_w H$

Diamagnetyki - gazy szlachetne, niektóre metale (cynk, złoto, rtęć), niektóre niemetale (krzem, fosfor, siarka), związki organiczne (alkohol)

Paramagnetyki: niektóre pierwiastki (glin, platyna, palla, chrom) oraz ich sole, powietrze, gazowy tlenek azotu, ciekły i stały tlen

Ferromagnetyki - żelazo, nikiel, kobalt, gadolin i ich stopy, stopy chromu

> ważne - $\mu _w$ może być <1

Diamagnetyki - wszystkie elektrony sparowane, atom nie ma zewnętrznego momentu magnetycznego. Po umieszczeniu d-a w zewnętrznym polu magnetycznym ładunki dążą do częściowego ekranowania wnętrza ciała przez przyłożonym polem

Diamagnetyki magnetyzują się w bardzo słabym stopniu i w kierunku przeciwnym do kierunku działania zewnętrznego pola magnetycznego

Ten rodzaj magnetyzacji jest proporcjonalny do zewnętrznego pola magnetycznego i jest niezależny od temperatury

Paramagnetyki - posiadają co najmniej jeden niesparowany elektron, co skutkuje zewnętrznym momentem magnetycznym dla danego atomu. Przy braku uporządkowania wypadkowy moment magnetyczny jest zerowy.

Gdy umieścimy paramagnetyk w zewnętrznym polu magnetycznym, materiał magnetyzuje się w nieznacznym stopniu w kierunku zgodnym z kierunkiem działania zewnętrznego pola magnetycznego.

Magnetyzacja proporcjonalna do zewnętrznego pola i odwrotnie proporcjonalna do temperatury

Ferromagnetyki - jedynie w postaci ciał stałych (pozostałe mogły mieć inne stany skupienia) W stanie ciekłym i gazowym ferromagnetyki zachowują się jak paramagnetyki.

Ferromagnetyki - silne właściwości magnetyczne. Każdy atom wytwarza własne pole magnetyczne. Atomy ustawiają się tak aby pole magnetyczne cząstek było zgodne z p.m. sąsiadów. Obszary tego samego kierunku nazywamy domenami. Pole magnetyczne domen mogą być ustawione w dowolnym kierunku. Przy przyłożeniu zewnętrznego pola domeny ustawiają się w jego kierunku. Domeny nie wracają do ustawienia chaotycznego po ustaniu zewnętrznego p.m. - pozostałość magnetyczna. Ten magnetyzm nie jest proporcjonalny do zewnętrznego pola i jest odwrotnie proporcjonalny do różnicy temperatury bezwzględnej i temperatury krytycznej (punku Curie) $T-\theta$ 

Pętla histerezy magnetycznej

![[Pasted image 20230212214403.png]]

Materiały miękkie i twarde 

![[Pasted image 20230212214500.png]]

Materiały miękkie - natężenie koercji $H_c< 1000A/m$
Materiały twarde - $H_c >10 kA/m$

# W9

Tematy wykładów

1. SEM (cz. 1 i 2)
2. EDS, TEM
3. STM, AFM
4. Transmisja światła, OBIC
5. XRD

Klasyfikacja metod badania materiałów

- wiązki elektronowej (?)
	- SEM
	- TEM (?)
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

# W10

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

# W11

Zastosowanie:

- badanie cienkich warstw, powłok
	- twardość ($TiO_2$)
	- właściwości gazochromowe ($WO_3$)
	- właściwości antybakteryjne ($Ti-Ag, Nb-Ag$) - publiczne ekrany dotykowe
	- no i oczywiście struktury

EDS - energy dispersive spectroscpoy, metoda pomiarowa oparta na oddziaływaniu elektronów z atomami w materiale, często jako przystawka do SEM, minimalny poziom wykrywalności pierwiastków jest mniejszy niż 0.1% wag., ale dokładność tego pomiaru jest mała ($\pm 1\%$). Metoda nieniszcząca. Mała rozdzielczość (~50nm)

Działanie:

- elektron z padającej wiązki wybija elektron z orbity
- wakansję po wybitym elektronie zajmuje elektron z wyższej orbity
- w wyniku przeskoku elektronu emitowana jest energia, którą mierzymy

Wyniki przedstawiamy jako: widmo, mapy pierwiastków lub zestawienie ilościowe.

Każdemu pierwiastkowi odpowiada charakterystyczny pik w widmie, obserwujemy też piki nie pochodzące bezpośrednio od atomów, np. będące sumą innych pików.

WDS - wavelength-dispersive X-ray spectroscopy - do pierwiastków lekkich, długi czas pomiaru (15-600 min)

> Jak kupujesz hafn to przyjeżdżają smutni panowie

> Pytanie na kolokwium: na czym polega EDS, naszkicuj widmo (jakieśtam piki, powiedzieć, że odpowiadją atomom)

TEM  - operuje na wiązce elektronów, większa rozdzielczość (teoretycznie ~1pm)

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

Cienkie próbki często nanosimy na siatki miedziane (rzadziej Mo, Au, Pt) pokryte jakąś tam żywicą. Nie można nanosić na nie plazmą. 


# W12

Dalej o przygotowaniu próbek TEM

Proces FIB (focused ion beam):

- wycięcie klina
- wbicie "gwoździa", żeby mieć za co trzymać
- pocienienie klina do próbki

Mody/tryby obrazowanie w TEM:

- jasnego pola (BF, bright field) - ciemny na obrazku oznacza, że coś jest a jasny, że nie ma. Najpopularniejszy tryb. Grubsze obszary próbki wyjdą ciemne. 
- ciemnego pola (DF)
- wysokorozdzielczy (HR) - widać atomy (jako kulki), dokładność 0.05nm, można wyznaczać płaszczyzny krystalograficzne

Wzór dyfrakcyjny
SAED - selected area electron diffraction
Pozwalają na wyznaczenie składu. Krystaliczny vs amorficzny

STEM - skaningowa transmisyjna mikroskopia elektronowa

- wiązka jest zogniskowana (do 0.05-0.2 nm)
- skanujemy wiązką próbkę
- próbka jest oświetlona w każdym punkcie wiązką równoległą do osi optycznej

CryoTEM - obrazowanie próbek biologicznych, chłodzenie ciekłym azotem

Zalety TEM:

- oferuje bardzo potężne powiększenie i rozdzielczość
- ma szeroki zakres zastosowań i może być wykorzystywany w wielu różnych dziedzinach nauki, edukacji i przemysłu
- dostarcza informacji o strukturze, składzie materiałowym
- obrazy są wysokiej jakości i szczegółowe

Wady TEM:

- są duże i bardzo drogie (od 300 000$)
- pracochłonne przygotowanie próbek
- obsługa i analiza wymagają specjalnego przeszkolenia
- próbki są ograniczone do małych rozmiarów ($\mu$m) i muszą być przezroczyste dla elektronów
- wymagają specjalnej obudowy i konserwacji
- obrazy są czarno-białe

Jeszcze raz o tym, że w SEM: próbka na dole, detektor z boku, TEM: próbka w środku, detektor na dole.

# W13

## Badanie materiałów a pomocą STM i AFM

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

# W14

## Metoda OBIC

OBIC - optical beam induced current - prąd generowany wiązką optyczną
LBIC - light beam induced current - prąd generowany wiązką świetlną

Metoda OBIC opiera się na absorpcji promieniowania 
`schemat co się dzieje jak promień pada na materię - każdy go zna (abs, trans, odb, emisja)`

Metody fotokonduktancyjne - szeroki zakres promieniowania (w tym całe widzialne)

W metodzie OBIC zogniskowana i zmodulowana wiązka światła o długości fali $\lambda$ skanuje od punktu do punktu powierzchnię próbki, powodując generację par elektron-dziura.

Generacja ma charakter lokalny, gdyż związana jest ze średnicą padającej wiązki światła.

`Model rozpraszania wiązki świetlnej w ciele stałym - wiązka pada na powierzchnię, pod powierzchnią zaznaoczono "obszar generacji" w kształcie kropli`

`Schemat powstawania prądu OBIC`

![[Pasted image 20230212234516.png]]

Indukowanie prądu zachodzi w wyniku separacji swobodnych nośników ładunku generowanych pod wpływem bombardowania próbki fotonami

Separacja nośników zachodzi na granicy ośrodków aktywnych

Obszarami elektrycznie aktywnymi są np.:

- obce wtrącenia
- naprężenia
- uszkodzenia sieci
- dyslokacje
- błędy ułożenia
- granice ziaren

Do podstawowych zalet metody OBIC można zaliczyć:

- wysoką rozdzielczość, ze względu na mały obszar oddziaływania wiązki na próbkę
- możliwość badania zarówno materiałów wyjściowych stosowanych do produkcji przyrządów półprzewodnikowych jak i gotowych przyrządów.
- metoda jest nieniszcząca
- możliwość prowadzenia badań ilościowych i jakościowych
- fakt że propagacja wiązki światła i pomiary odbywają się w powietrzu (co jest zaletą w stosunku do szeroko stosowanych metod elektronowiązkowych wymagających wysokiej próżni)
- subtelniejszy charakter oddziaływania "lekkich fotonów" na badaną powierzchnię - chyba chodzi o to że taka wiązka np. elektronów to może lokalnie coś zniszczyć w próbce 

Schemat metody:

Jedna strona schematu:

- źródło światła
- modulator (wiatraczek)
- monochromator
- mikroskop
- próbka

Druga strona schematu:

- jakieś mierniki prądu, zmienił slajd

Informacje:

- jakościowe
	- rozkład prądu (kolorowa mapa)
	- rozkład defektów
	- sprawność kwantowa
- ilościowe
	- długość drogi dyfuzji (jak głęboko są nośniki)
	- czas życia nośników
	- prędkość rekombinacji nośników

Rodzaje badanych materiałów:

- generalnie (dramatyczna pauza) półprzewodniki
- wszystko inne co reaguje na światło

Trzy sposoby pomiaru rozkładu prądu $I_{OBIC}$ w linii wzdłuż kierunku skanowania wiązką świetlną próbki ze złączem p-n (lub m-s):

- rozkład prądu indukowanego w złączu mierzony między kontaktami A, B 

![[Pasted image 20230212234609.png]]

Gdy wiązka światłą W zbliża się do granicy złącza p-n, cześć nośników generowanych w jej pobliżu dyfunduje w obszar złącza, gdzie zostaje rozpreparowana.

Indukowany prąd będzie wzrastał eksponencjalnie w miarę zbliżania się do samego złącza, a następnie aż do kolejnej granicy złącza.

- 2 rozkład został skipnięty "żeby się nie mieszało"

- rozkład prądu na granicy ziaren, mierzony między kontaktami A,B (lub A,C)

## Nanoindentacja - nie będzie na egzaminie

Twardość - zdolność przeciwstawiania się odkształceniom. Skala Mohsa (od 1 do 10). Mierzymy metodami wciskania wgłębników w materiał - metodami indentacji.

Wgłębniki mają różne kształty i są z różnych materiałów.

Metoda Vickersa jest lepsza od metody Brillena

> Najpierw jest delikatnie a potem jeszcze raz i jeszcze raz i jeszcze...

Metoda Rockwella - robimy rysę, przyciskając coraz mocniej - igła ryje próbkę jak tupolew ziemię

Metoda Bayera - bierzesz próbkę i zasypujesz specjalnym piaskiem (nie takim z nad Bałtyku) i wytrząsasz. Trzeba zabezpieczyć krawędzie próbki bo tam by popękała bardzo szybko. Rysy będą tak małe, że będzie je widać jako zmatowienie przedmiotu.

# W15

## Pomiary optyczne

`rysunek co się dzieje ze światłem przy przejściu z przez cienką warstwę na podłożu`

![[Pasted image 20230212234920.png]]

`charakterystyka transmisji światła cienkiej warstwy TiO2`

![[Pasted image 20230212234948.png]]

Współczynnik kierunkowej transmisji światła 

![[Pasted image 20230212235025.png]]

![[Pasted image 20230212235041.png]]

Sfera integracyjna

Współczynnik transmisji, odbicia

Odbicie od powłok zależy od mikro- i makroskopowych właściwości ich powierzchni (np. chropowatości i falistości)

Jeżeli na powierzchni powłoki występują nierówności, których rozmiary są znacznie mniejsze od długości fali światła padającego, to następuje tzw. kierunkowe (zwierciadlane) odbicie światła.

Gdy nierówności są porównywalne z długością fali, odbicie może mieć charakter dyfuzyjny. Wówczas nie można wyróżnić określonego kierunku światła odbitego.

Parametry wyznaczane na podstawie charakterystyk transmisji i odbicia światła:
- Wyznaczanie średniego poziomu transmisji metodą obwiedni
- Wyznaczanie położenie krawędzi optycznej absorpcji ($\lambda_{cutoff}$)
- Współczynnik załamania światła - można sobie wyznaczyć charakterystykę z widma transmisji (dla cienkiej warstwy - jak są interferencje) 
- Współczynnik absorpcji
- Grubość fizyczna (dla cienkiej warstwy - jak są interferencje)
- Szerokość optycznej przerwy energetycznej ($E_g^{opt}$)

## Zwilżalność

Zwilżalność określona jest przez stosunek sił kohezji i adhezji działających na styku ciała stałego oraz cieczy.

Napięcie powierzchniowe cieczy - charakterystyczne dla cieczy

Swobodna energia powierzchniowa - można zmieniać

Kat zwilżania

$$\cos{\theta_c}=\frac{\gamma_{SG}-\gamma_{SL}}{\gamma_{LG}}$$

superhydrofilowe - $\theta<30^o$
hydrofilowe - $\theta<90^o$
hydrofobowe - $\theta>90^o$
superhydrofobowe - $\theta>150^o$


Liść lotosu - bardzo rozwinięta powierzchnia - włoski o średnicy 1nm
Struktura powierzchni samoczyszczącej

Przykłady zastosowań powierzchni hydro- i superhydrofobowe:

- szyby samochodowe
- soczewki okularowe
- farby

Układ do pomiarów zwilżania

![[Pasted image 20230212235524.png]]

Podstawowe elementy układu:

- system zrzucania kropli
- źródło światła
- powierzchnia na stoliku
- aparat fotograficzny

Dynamiczny kąt zwilżania z tensjometrem optycznym - majstrujemy sobie igłą przy kropelce

Pomiar kąta dla kropli w ruchu (powierzchnia po kątem)

Metoda pęcherzyka powietrza - płytka zanurzona w cieczy i z wpompowanym pod nią pęcherzykiem gazu

Metoda płytki Wilhelmy'ego - zanurzanie i wyciąganie próbki w cieczy pomiarowej

Model Cassie-Baxtera - chropowaty = hydrofobowy

Model Wenzela - chropowaty = hydrofilowy

Metody określania swobodnej energii powierzchniowej (SEP)

- Zismana (wyznaczanie krytycznego napięcia powierzchniowego - przy jakim n.p. $\cos \theta =1$ )
