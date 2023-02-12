# W1

## Wykład

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
	- wartości temperatury, od której zależna jest intensywność ruchu cieplnego cząsteczek, przeciwstawiającego się elektrycznych siłom porządkujących. Im wyższa temperatura, tym bardziej chaotyczna orientacja dipoli w wyniku bardzie intensywnych zderzeń i drgań cząsteczek,. Dla określonej temperatury ustala się określony stopnień uporządkowania dipoli, uwarunkowany tymi dwiema przeciwstawnymi tendencjami

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

