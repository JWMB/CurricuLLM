## Sannolikhet

Sannolikhet är ett centralt begrepp inom matematik och statistik och handlar om att kvantifiera osäkerhet. När vi talar om sannolikhet avser vi chansen eller risken att en viss händelse inträffar. Ibland beskriver sannolikhet vår förväntan baserat på tidigare data eller modeller, och ibland hur säker vi kan vara på framtida händelser. Målet med detta kapitel är att ge dig en grundläggande förståelse för sannolikhet och hur du kan tillämpa denna kunskap för att lösa problem.

![coin-toss](coin-toss.png)

Sannolikhet uttrycks som ett tal mellan 0 och 1. Ett värde på 0 betyder att händelsen inte kan inträffa, och ett värde på 1 betyder att händelsen säkert kommer att inträffa. När vi talar om sannolikhet i praktiken, brukar vi ofta använda procenttal från 0% till 100% för att göra det mer intuitivt.

### Enkla händelser

En enkel händelse är en händelse som endast kan ha en viss utgång i sitt grundläggande urval. Ett klassiskt exempel på en enkel händelse är att kasta en singel 6-sidig tärning. Utfallsmöjligheterna är begränsade till siffrorna 1, 2, 3, 4, 5 och 6. Om du vill beräkna sannolikheten att tärningen visar en 3, är det en enkel händelse.

Formeln för sannolikhet (P) av en enkel händelse är:
\[ P(\text{händelse}) = \frac{\text{Antal gynnsamma utfall}}{\text{Antal möjliga utfall}} \]

**Exempel:**

Beräkna sannolikheten att en tärning kastas och visar en 3.

Gynnsamma utfall: 1 (endast talet 3)
Möjliga utfall: 6 (talen 1, 2, 3, 4, 5, 6)

\[ P(\text{3}) = \frac{1}{6} \]

Så sannolikheten att få en 3 på en enda kastning av tärningen är \(\frac{1}{6}\), eller cirka 16.67%.

### Kombinationer

Med sannolikhet är ofta frågan inte alltid om en enkel händelse, utan flera händelser som kan interagera med varandra. Kombinationer i sannolikhet handlar om att räkna möjliga arrangemang och permutationer av händelser, vilket ofta används vid mer komplexa analyser som involverar flera element.

![combination-diagram](combination-diagram.png)

Vid beräkning av sannolikhet för kombinationer använder vi metoder för att avgöra hur händelser kan inträffa tillsammans, vilket kan kräva förståelse av principerna såsom addition och multiplikation av sannolikheter, beroende på situationen om händelserna är oberoende eller beroende av varandra.

**Exempel:**

Anta att du har en grupp av 4 personer och du vill skapa ett lag som består av 2 personer. Hur många olika lag kan du skapa?

Använd kombinationsformeln för att beräkna detta:

\[ C(n, k) = \frac{n!}{k!(n-k)!} \]

Där \(n\) är det totala antalet objekt och \(k\) är antalet objekt att välja. I detta fall är \(n = 4\) och \(k = 2\):

\[ C(4, 2) = \frac{4!}{2!(4-2)!} = \frac{4 \times 3}{2 \times 1} = 6 \]

Så det finns 6 möjliga sätt att kombinera dessa 4 personer till lag bestående av 2 personer.

Genom att förstå dessa grundläggande begrepp kan du börja att tillämpa sannolikhet på praktiska problem och exempel i verkliga livet. I de följande avsnitten kommer du att lära dig mer om hur man kan använda sannolikhet i samband med statistik för att göra meningsfulla analyser och beslut.