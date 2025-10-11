# Sannolikhet

Sannolikhet är ett centralt begrepp inom matematik som används för att beskriva hur troligt det är att en viss händelse inträffar. Det kan vara allt från att vrida ett mynt och få "klave" till att dra ett kort från en kortlek. Sannolikhet används inom många områden, inklusive statistik, ekonomi, naturvetenskap och spelteori. Grundläggande för att förstå sannolikhet är att man har en tydlig definition av de händelser som betraktas. 

### Enkla händelser

En enkel händelse är en händelse som inte kan delas upp i flera underhändelser. Den kan antingen inträffa eller inte inträffa. Sannolikheten för en enkel händelse kan kvantifieras och uttryckas som en siffra mellan 0 och 1, där 0 innebär att händelsen är omöjlig och 1 innebär att händelsen är säker.

#### Exempel:

Anta att vi kastar en vanlig sexsidig tärning. Händelsen att få en "fyra" är en enkel händelse. Det finns sex möjliga utfall (1, 2, 3, 4, 5, 6), och bara ett av dessa utfall är en "fyra". Sannolikheten för denna händelse kan beräknas enligt följande:

\[
P(\text{fyra}) = \frac{\text{antalet gynnsamma utfall}}{\text{antalet möjliga utfall}} = \frac{1}{6} \approx 0,1667
\]

En tydlig illustration som kan bidra till förståelsen av enkel händelse är en bild av en tärning, med fokus på sidorna. ![Tärning med sidor](https://example.com/tarning-med-sidor)

### Kombinationer

Kombinationer handlar om att räkna ut hur många olika sätt man kan välja ett visst antal element från en större uppsättning utan att ta hänsyn till ordningen hos dessa element. I många situationer är det viktigt att veta hur många sätt olika händelser kan inträffa eller olika objekt kan väljas, och detta ger oss möjligheten att beräkna sannolikheter för mer komplexa händelser.

#### Exempel:

Tänk dig att du har en kortlek med 52 kort och vill veta hur många olika sätt du kan dra 5 kort. Detta är ett klassiskt exempel på en kombination. Antalet sätt att välja \(k\) objekt från en mängd av \(n\) objekt kan beräknas med formeln:

\[
C(n, k) = \frac{n!}{k!(n-k)!}
\]

Där \(n!\) (n-fakultet) betyder att man multiplicerar alla heltal från 1 till \(n\).

Om vi vill dra 5 kort från en kortlek på 52 kort, sätter vi in värdena \(n = 52\) och \(k = 5\) i formeln:

\[
C(52, 5) = \frac{52!}{5!(52-5)!} = \frac{52!}{5! \cdot 47!} = \frac{52 \times 51 \times 50 \times 49 \times 48}{5 \times 4 \times 3 \times 2 \times 1} = 2 598 960
\]

Det finns alltså 2 598 960 olika sätt att välja 5 kort ur en kortlek med 52 kort.

För att illustrera detta kan en bild av en kortlek användas, med fokus på att lyfta fram antalet kort. ![Kortlek](https://example.com/kortlek)

Genom att förstå de grundläggande begreppen inom sannolikhet, såsom enkla händelser och kombinationer, bygger vi en solid grund för att kunna utforska mer komplexa sannolikhetsproblem och tillämpningar.