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

Zgodnie z matematycznym ujęciem  prawa Paschena napięcie przebicia dla danego gazu, dla danego materiału elektord, w danej temepratrze jest funkcją $p\cdot d$ gdzie p to jest ciśnienie a d to odległość międzyelektrodowa. Graficznym ujęciem są krzywe (charakterystyki) Paschena. Dla różnych gazów kształt tych charakterystyk jest zbliżony.  

## Elektrety

Elektretem nazywamy dielektryk, który wytwarza w swoim otoczeniu trwałe, zewnętrzne pole elektryczne. Źródłem w elektrecie są nagromadzone w nim ładunki elektryczne lub wytworzony w dielektryku i "zamrożony" stan polaryzacji. 
Zjawisko gromadzenia trwałego ładunku elektrycznego w dielektrykach daje duże możliwości ich praktycznych zastosowań. Możliwości zastosowania elektrtów związane są z czasem życia ładunku elektrycznego (ostatnie niepewne, zmieniła slajd)

Metody wytwarzania elektretów

- metoda termoelektryczna - wytwarzanie elektretu z polimeru dipolowego (pozostałem metody - ładunek z zewnętrznego źródła)
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