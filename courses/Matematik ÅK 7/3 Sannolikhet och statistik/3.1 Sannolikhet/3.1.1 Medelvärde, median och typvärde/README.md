# Medelvärde, median och typvärde

Inom statistik används medelvärde, median och typvärde för att beskriva och sammanfatta data på olika sätt. Dessa tre mått kallas centrala mått och ger oss olika perspektiv på en dataset. Här kommer vi att förklara var och en av dessa begrepp, ge exempel på hur de räknas ut samt när det kan vara lämpligt att använda dem.  

## Medelvärde

Medelvärde, ofta kallat "genomsnitt", beräknas genom att lägga samman alla värden i en dataset och dela sammanlagda värdet med antalet observationer. Det är ett av de mest använda måtten för att sammanfatta data eftersom det ger en allmän bild av värdena.

### Beräkning av medelvärde

För att beräkna medelvärdet följer du dessa steg:

1. **Summera alla värden**: Lägg ihop alla tal i datasetet.
2. **Dela med antalet värden**: Ta det totala summan och dela det med antalet värden i datasetet.

**Exempel**: Om vi har följande värden: 4, 8, 6, 5 och 3.

- Steg 1: 4 + 8 + 6 + 5 + 3 = 26
- Steg 2: 26 / 5 = 5,2

Så medelvärdet av dessa värden är 5,2.

![Medelvärde illustration](https://example.com/medelvarde-illustration)

## Median

Medianen är det mittersta värdet i en dataset när värdena är sorterade i ordning. Om det finns ett udda antal observationer är medianen det mittersta värdet. Om det finns ett jämnt antal observationer är medianen medelvärdet av de två mittersta värdena.

### Beräkning av median

1. **Sortera värdena**: Ordna värdena i stigande ordning.
2. **Identifiera medianen**:
   - Om antalet värden är udda: Ta det mittersta värdet.
   - Om antalet värden är jämnt: Beräkna medelvärdet av de två mittersta värdena.

**Exempel**: För datasetet 4, 8, 6, 5 och 3 börjar vi med att sortera:

Sorterade värden: 3, 4, 5, 6, 8

Eftersom det finns 5 värden (udda) är medianen 5.

För datasetet 4, 8, 6 och 5 (jämnt antal värden):

Sorterade värden: 4, 5, 6, 8

Medianen blir (5 + 6) / 2 = 5,5.

![Median illustration](https://example.com/median-illustration)

## Typvärde

Typvärdet är det värde som uppträder mest frekvent i en dataset. Det kan finnas mer än ett typvärde (multimodalt) om flera värden har samma, högsta frekvens.

### Beräkning av typvärde

1. **Räkna frekvenser**: Notera hur många gånger varje värde förekommer i datasetet.
2. **Identifiera typvärdet**: Det värde som förekommer flest gånger är typvärdet.

**Exempel**: För datasetet 4, 8, 6, 5, 3, 4, 8 och 4.

Värden a priori:
- 4: 3 gånger
- 8: 2 gånger
- 6: 1 gång
- 5: 1 gång
- 3: 1 gång

Här är typvärdet 4 eftersom det förekommer flest gånger.

![Typvärde illustration](https://example.com/typvarde-illustration)

## Sammanfattning

Medelvärde, median och typvärde är centrala mått inom statistik som ger olika insikter om datasetet. Medelvärde ger en genomsnittlig siffra, median hjälper oss att förstå det centrala värdet, och typvärde visar vilket värde som förekommer oftast. Valet av vilket mått som ska användas beror på datasetets karaktär och syftet med analysen.