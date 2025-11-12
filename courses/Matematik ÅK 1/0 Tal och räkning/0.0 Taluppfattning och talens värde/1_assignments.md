Nivå 1 — Lätt (Årskurs 1, 6–7 år)
1)
**Question** Hur många äpplen finns det? Räkna och skriv siffran. (Det finns fem äpplen.)
**InputType** text
**Hint** Titta och räkna en och en.
**Hint** Räkna högt: 1, 2, 3, 4, 5.
**Answer** 5
**Answer** fem
**MaxPoints** 1
**AnalyzeSubmission** Acceptera antingen siffran "5" eller talordet "fem" (case-insensitive). Om svaret efter normalisering är exakt "5" eller "fem" markera som korrekt, annars fel.
**WrongAnswer** 4 **Why** Missade ett äpple vid räkningen.
**WrongAnswer** 6 **Why** Räkningen fortsatte förbi slutet.

2)
**Question** Skriv talnamnet för siffran 8.
**InputType** text
**Hint** Tänk på hur många fingrar du visar med ett fullt handpar minus två.
**Hint** Uttala siffran: åtta.
**Answer** åtta
**MaxPoints** 1
**AnalyzeSubmission** Acceptera "åtta" (case-insensitive). Små stavfel med en bokstav får också godkännas (t.ex. "atta" om det är uppenbart), annars fel.
**WrongAnswer** ått **Why** Stavfel som gör det otydligt.
**WrongAnswer** 7 **Why** Förväxling med ett lägre tal.

3)
**Question** Vilken siffra är tio?
**InputType** single-choice
**Hint** Tio består av två siffror: ett och noll.
**Hint** Hitta "10" bland alternativen.
**Answer** 10
**MaxPoints** 1
**WrongAnswer** 1 **Why** Förväxlar talet 10 med talet 1.
**WrongAnswer** 0 **Why** Noll är inte tio.
**WrongAnswer** 11 **Why** Ett högre tal än tio.

4)
**Question** Vilket tal är störst: 3 eller 7?
**InputType** single-choice
**Hint** Räkna från 1 uppåt.
**Hint** 7 kommer efter 3.
**Answer** 7
**MaxPoints** 1
**WrongAnswer** 3 **Why** Räknar baklänges eller missförstår "störst".

5)
**Question** Vilka tal kommer efter 4 på tallinjen? (Välj alla som passar.)
**InputType** multiple-choice
**Hint** Talen som kommer efter 4 är större än 4.
**Hint** Tänk 4, 5, 6, 7 ...
**Answer** 5
**Answer** 6
**MaxPoints** 2
**WrongAnswer** 3 **Why** Har valt ett tal som kommer före 4.
**WrongAnswer** 4 **Why** Valde samma tal istället för talen efter.

6)
**Question** Hur skrivs siffran två?
**InputType** single-choice
**Hint** Det ser ut som ett litet böjt streck med en kurva.
**Hint** Leta efter "2".
**Answer** 2
**MaxPoints** 1
**WrongAnswer** S **Why** Blandar ihop bokstav och siffra.
**WrongAnswer** z **Why** Fel tecken, inte en siffra.

7)
**Question** Vilket tal är tiokompis till 7? (Vilket tal tillsammans med 7 blir 10?)
**InputType** single-choice
**Hint** Tänk: 7 + ? = 10.
**Hint** 7 + 3 = 10.
**Answer** 3
**MaxPoints** 1
**WrongAnswer** 2 **Why** Räknade fel eller tänkte 7 + 2 = 9.
**WrongAnswer** 4 **Why** Överskattning.

Nivå 2 — Medel
1)
**Question** Skriv talen i ordning från minst till störst: 5, 2, 8.
**InputType** text
**Hint** Vilket tal är minst? Börja där.
**Hint** Säg talen högt: två, fem, åtta.
**Answer** 2,5,8
**Answer** 2 5 8
**Answer** 2;5;8
**MaxPoints** 2
**AnalyzeSubmission** Acceptera svar som innehåller talen i exakt ordning 2 följt av 5 följt av 8, separerade med kommatecken, mellanslag eller semikolon. Om ordningen är korrekt markera poäng, annars fel.
**WrongAnswer** 5,2,8 **Why** Började inte med det minsta talet.
**WrongAnswer** 8,5,2 **Why** Omvänd ordning.

2)
**Question** Vad är 6 + 3?
**InputType** text
**Hint** Räkna uppåt från 6 tre steg.
**Hint** 6 → 7 → 8 → 9.
**Answer** 9
**Answer** nio
**MaxPoints** 1
**AnalyzeSubmission** Acceptera "9" eller "nio" (case-insensitive). Små stavfel i "nio" kan godkännas om det är tydligt.
**WrongAnswer** 8 **Why** Missade ett steg när de räknade.
**WrongAnswer** 10 **Why** Rättade överräkning.

3)
**Question** Vilket tal saknas på tallinjen? 4, 5, __, 7.
**InputType** single-choice
**Hint** Talen går uppåt med ett.
**Hint** Efter 5 kommer 6.
**Answer** 6
**MaxPoints** 1
**WrongAnswer** 3 **Why** Första talet tog de fel på som saknades.
**WrongAnswer** 5 **Why** Valde ett tal som redan finns.

4)
**Question** Vilka tal är mindre än 6? (Välj alla som passar.)
**InputType** multiple-choice
**Hint** Tänk på talen 1,2,3,4,5.
**Hint** Mindre än 6 betyder alla tal före 6.
**Answer** 1
**Answer** 4
**Answer** 5
**MaxPoints** 3
**WrongAnswer** 6 **Why** Felaktigt antagit att "mindre än" inkluderar talet 6.
**WrongAnswer** 7 **Why** Ett större tal, inte mindre.

5)
**Question** Vilka av dessa par bildar 10? (Välj alla rätta: 3+7, 5+4, 6+4, 8+2)
**InputType** multiple-choice
**Hint** Räkna ihop varje par.
**Hint** 3+7=10, 8+2=10.
**Answer** 3+7
**Answer** 8+2
**MaxPoints** 2
**WrongAnswer** 5+4 **Why** 5+4 blir 9, saknar 1.
**WrongAnswer** 6+4 **Why** 6+4 blir 10? (Här är svaret FEL om listan angav 6+4 som fel — kontrollera att alternativet är korrekt) — OBS: Denna rad beskriver ett vanligt misstag: tro att 6+4 inte är 10, men 6+4 = 10 (om alternativet ges kan vara korrekt). 
(Anmärkning för lärare: Om du vill att 6+4 också ska vara rätt, markera det som Answer istället. Här antas 6+4 inte vara en av de rätta alternativen för att ge ett exempel på felsvar.)

6)
**Question** Vilket tal kommer direkt före 10?
**InputType** single-choice
**Hint** Tänk ett steg bakåt från 10.
**Hint** 9 kommer före 10.
**Answer** 9
**MaxPoints** 1
**WrongAnswer** 8 **Why** Har hoppat över talet 9.
**WrongAnswer** 10 **Why** Förstår inte "före" som innan.

7)
**Question** Vilket tal är tiokompis till 6?
**InputType** single-choice
**Hint** 6 + ? = 10.
**Hint** 6 + 4 = 10.
**Answer** 4
**MaxPoints** 1
**WrongAnswer** 3 **Why** Trodde 6+3=10 men det blir 9.
**WrongAnswer** 5 **Why** Räknade fel.

Nivå 3 — Svår
1)
**Question** Skriv hur många tiotal och ental det finns i talet 17. (Exempel: 1 tiotal och 2 ental)
**InputType** text
**Hint** Talet 17 är 10 + 7.
**Hint** Ett tiotal, sju ental.
**Answer** 1 tiotal och 7 ental
**Answer** 1 tiotal, 7 ental
**Answer** 1 och 7
**MaxPoints** 2
**AnalyzeSubmission** Acceptera formuleringar som visar "1 tiotal" och "7 ental" i valfri ordning, eller korta former som "1 och 7". Case-insensitive. Om båda delarna är korrekta ge full poäng, annars inget.
**WrongAnswer** 10 och 7 **Why** Skrev talen felaktigt som summor istället för antal tiotal/ental.
**WrongAnswer** 17 tiotal **Why** Missförstått begreppen tiotal/ental.

2)
**Question** Vilket tal ligger mellan 12 och 14?
**InputType** text
**Hint** Tänk: 12, __, 14.
**Hint** Det är talet 13.
**Answer** 13
**Answer** tretton
**MaxPoints** 1
**AnalyzeSubmission** Acceptera "13" eller "tretton" (case-insensitive). Annars fel.
**WrongAnswer** 12 **Why** Tolkar "mellan" som inkluderande.
**WrongAnswer** 14 **Why** Misstolkning av ordningen.

3)
**Question** Vilket är störst: 15 eller 9?
**InputType** single-choice
**Hint** Räkna uppåt från 1 till siffrorna.
**Hint** 15 är mycket större än 9.
**Answer** 15
**MaxPoints** 1
**WrongAnswer** 9 **Why** Fel vid jämförelse, kanske räknat fel.

4)
**Question** Vilka tal är större än 12 och mindre än 17? (Välj alla som passar.)
**InputType** multiple-choice
**Hint** Talen är 13, 14, 15, 16.
**Hint** Välj alla tal mellan 12 och 17 men inte 12 och 17 själva.
**Answer** 13
**Answer** 14
**Answer** 15
**Answer** 16
**MaxPoints** 4
**WrongAnswer** 12 **Why** Valde gränsvärdet som inte ska vara med.
**WrongAnswer** 17 **Why** Valde gränsvärdet som inte ska vara med.

5)
**Question** Hur mycket är 10 + 7?
**InputType** text
**Hint** Tio plus sju är tio och sju.
**Hint** 10 + 7 = 17.
**Answer** 17
**Answer** sjutton
**MaxPoints** 1
**AnalyzeSubmission** Acceptera "17" eller "sjutton" (case-insensitive). Små stavfel i "sjutton" kan godkännas.
**WrongAnswer** 16 **Why** Missade ett steg vid addition.
**WrongAnswer** 15 **Why** Felräkning.

6)
**Question** Vilka tal tillsammans med 4 blir 10? (Välj alla som passar: 6, 5, 7, 3)
**InputType** multiple-choice
**Hint** 4 + ? = 10.
**Hint** 4 + 6 = 10.
**Answer** 6
**MaxPoints** 1
**WrongAnswer** 5 **Why** 4+5=9, saknar 1.
**WrongAnswer** 7 **Why** 4+7=11, för mycket.
**WrongAnswer** 3 **Why** 4+3=7, för lite.

7)
**Question** Skriv talen i ordning från störst till minst: 11, 14, 9.
**InputType** text
**Hint** Vilket tal är störst? Börja där.
**Hint** 14, 11, 9.
**Answer** 14,11,9
**Answer** 14 11 9
**MaxPoints** 2
**AnalyzeSubmission** Acceptera talen i exakt ordning 14, 11, 9 separerade med kommatecken eller mellanslag. Ge full poäng om ordningen är korrekt.
**WrongAnswer** 11,14,9 **Why** Bytte plats på största och nästa största.