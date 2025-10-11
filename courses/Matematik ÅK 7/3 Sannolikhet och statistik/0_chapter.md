# Sannolikhet och statistik

## Sannolikhet

Sannolikhet handlar om att kvantifiera osäkerhet. Det är en matematisk disciplin som undersöker hur troligt det är att en viss händelse inträffar. Sannolikheten för en händelse uttrycks som ett tal mellan 0 och 1, där 0 innebär att händelsen aldrig inträffar och 1 innebär att den alltid inträffar. 

### Grunderna i sannolikhet

Sannolikheten för en händelse A, betecknas som P(A), kan beräknas med följande formel:

\[ P(A) = \frac{\text{Antal gynnsamma utfall}}{\text{Totala antalet utfall}} \]

#### Exempel

Tänk dig att vi kastar en vanlig sexsidig tärning. Sannolikheten att få en fyra (händelsen A) är:

- Antal gynnsamma utfall: 1 (det finns bara en fyra på tärningen).
- Totala antalet utfall: 6 (tärningen har sidorna 1 till 6).

Då blir sannolikheten:

\[ P(\text{fyra}) = \frac{1}{6} \approx 0.167 \]

### Typer av sannolikhet

Det finns två huvudsakliga typer av sannolikhet: teoretisk sannolikhet och empirisk sannolikhet.

1. **Teoretisk sannolikhet**: Detta handlar om matematisk beräkning baserat på antaganden. Exempelvis, sannolikheten att få en sekvens av tre "kronor" i tre på varandra följande myntkast kan beräknas genom att tänka på varje myntkast som en oberoende händelse.

2. **Empirisk sannolikhet**: Denna typ av sannolikhet baseras på observationer och experiment. Om vi kastar en tärning 100 gånger och får en fyra 20 gånger, då kan den empiriska sannolikheten för att få en fyra beräknas som 20/100 = 0.2.

![Sannolikhetsdiagram](https://example.com/sannolikhetsdiagram)

## Statistik

Statistik är grenen av matematik som handlar om insamling, analys, tolkning och presentation av data. Det syftar till att förstå och beskriva fenomen genom att analysera och dra slutsatser från data.

### Typer av statistik

Statistik kan delas in i två huvudkategorier: deskriptiv statistik och inferentiell statistik.

1. **Deskriptiv statistik**: Denna typ handlar om att sammanfatta och beskriva egenskaper hos en datamängd. Vanliga metoder för deskriptiv statistik inkluderar medelvärde, median och standardavvikelse. Dessa mått hjälper till att förstå hur data är fördelat.

   - **Medelvärde**: Genomsnittsberäkning av en mängd data.
   - **Median**: Mittenvärdet i den ordnade datan.
   - **Standardavvikelse**: Ett mått på hur mycket variabla data ligger i närheten av medelvärdet.

   #### Exempel

   Om vi har följande datamängd som representerar antalet böcker lästa av 5 studenter under ett år: [5, 2, 3, 8, 4]
   
   - Medelvärdet beräknas som \( \frac{5+2+3+8+4}{5} = 4.4 \).
   - Medianen, när vi ordnar datan (2, 3, 4, 5, 8), är 4.
   - Standardavvikelsen visar hur spridd datan är i förhållande till medelvärdet.

   ![Deskriptiv statistik graf](https://example.com/deskriptiv_statistik_graf)

2. **Inferentiell statistik**: Denna typ av statistik används för att dra slutsatser om en större population baserat på ett urval av data. Det innebär att man använder sannolikhetsteori för att göra uppskattningar eller hypotestester.  

   - **Exempel**: Om en forskare vill veta genomsnittlig längd för alla gymnasieelever i en stad, kan de mäta längden på ett slumpmässigt urval av elever och sedan extrapolera resultaten för att göra en uppskattning för hela populationen.

Statistik är också centralt i många typer av forskning och analys och används inom områden som samhällsvetenskap, ekonomi, medicin och ingenjörsvetenskap. Genom grundlig statistisk analys kan man identifiera mönster, göra förutsägelser och informera beslut.