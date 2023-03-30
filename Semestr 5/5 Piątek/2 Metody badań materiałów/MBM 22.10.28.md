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