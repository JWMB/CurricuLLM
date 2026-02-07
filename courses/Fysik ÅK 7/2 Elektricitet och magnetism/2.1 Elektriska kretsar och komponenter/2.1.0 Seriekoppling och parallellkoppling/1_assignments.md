Nivå 1 (Lätt)

**Question** Vad är skillnaden mellan seriekoppling och parallellkoppling?
**InputType** text
**Hint** Tänk på om strömmen delar upp sig eller inte.
**Hint** Tänk på om spänningen är samma över varje komponent.
**Answer** Seriekoppling: samma ström genom alla komponenter; spänningen fördelas över komponenterna. Parallellkoppling: samma spänning över varje gren; strömmen delas mellan grenarna.
**MaxPoints** 3
**AnalyzeSubmission** Kontrollera om svaret nämner minst: "samma ström" och "spänningen fördelas" för seriekoppling samt "samma spänning" och "strömmen delas" för parallellkoppling. Om alla fyra begrepp finns: korrekt. Om bara två av fyra finns: delvis.
**WrongAnswer** I seriekoppling är spänningen alltid densamma **Why** Förväxling av begreppen ström och spänning.

**Question** Om två lampor sitter i serie och en av lamporna går sönder (glödtråden bruten), vad händer med lamporna?
**InputType** single-choice
**Hint** Hur går strömmen genom en serie av komponenter?
**Hint** Tänk: som länkar i en kedja.
**Answer** Alla lampor slocknar
**MaxPoints** 1
**WrongAnswer** Bara den trasiga lampan slocknar **Why** Förväxling med parallellkoppling där andra grenar kan fortsätta få ström.
**WrongAnswer** Lamporna blir starkare **Why** Misstag i förståelse av ström och resistans i seriekoppling.

**Question** Vilka av följande påståenden är sanna för en parallellkoppling? (välj alla som gäller)
**InputType** multiple-choice
**Hint** Tänk på spänningen över varje gren.
**Hint** Tänk på vad som händer om en komponent i en gren slutar fungera.
**Answer** Samma spänning över varje komponent/gren
**Answer** Om en gren slutar fungera påverkas inte alltid de andra grenarna
**MaxPoints** 2
**WrongAnswer** Samma ström genom varje komponent **Why** Förväxlar ström med spänning; i parallell kan strömmen vara olika i varje gren.
**WrongAnswer** Total resistans blir större när man lägger till fler grenar **Why** I parallell minskar den totala resistansen när flera grenar läggs till.

**Question** Om du byter plats på batteriets plus- och minuspol i en enkel krets med en lampa, vad händer?
**InputType** single-choice
**Hint** Tänk på strömriktningens betydelse för en vanlig glödlampa.
**Hint** Lampan påverkas i de flesta fall inte av riktningen eftersom glödtråden är icke-riktad.
**Answer** Strömriktningen ändras men lampan lyser fortfarande
**MaxPoints** 1
**WrongAnswer** Inget händer alls **Why** Eleverna förstår inte att strömriktningen ändras även om lampan fortfarande lyser.
**WrongAnswer** Lampan slocknar alltid **Why** Felaktig idé att lampor är riktade som dioder.

**Question** Vilket av följande är sant för en seriekoppling när du lägger till ytterligare en resistor?
**InputType** single-choice
**Hint** Fundera på vad som händer med den totala resistansen.
**Hint** Strömmen i en seriekoppling beror på totalresistansen.
**Answer** Totala resistansen ökar
**MaxPoints** 1
**WrongAnswer** Totala resistansen minskar **Why** Förväxling med parallellkoppling.
**WrongAnswer** Totala resistansen förblir oförändrad **Why** Missförstånd om hur resistorer påverkar kretsen i serie.

**Question** Vad är en kortslutning (kort sagt)?
**InputType** text
**Hint** Tänk på en väg med väldigt låg resistans som kringgår komponenter.
**Hint** Vad händer med strömmen om den tar en väg utan motstånd?
**Answer** En förbindelse med mycket låg resistans som gör att strömmen tar en snabb väg förbi komponenter, ofta mycket hög ström.
**MaxPoints** 2
**AnalyzeSubmission** Kontrollera om svaret nämner "väg med låg resistans" eller "mycket hög ström" och att den kringgår komponenter. Om båda finns: korrekt.
**WrongAnswer** När en lampa lyser starkt **Why** Missförståelse av termen; förväxlar ljusstyrka med kortslutning.
**WrongAnswer** Ett säkerhetssystem som slår av strömmen **Why** Förväxling med säkring eller jordfelsbrytare.

---

Nivå 2 (Mellan)

**Question** Beräkna totalresistansen när två resistorer 10 Ω och 5 Ω är seriekopplade.
**InputType** text
**Hint** I serie adderas resistorerna.
**Hint** R_total = R1 + R2
**Answer** 15 Ω
**MaxPoints** 2
**AnalyzeSubmission** Kontrollera om eleven svarar "15" eller "15 Ω". Acceptera numeriskt svar inom ±0.1 Ω.
**WrongAnswer** 5 Ω **Why** Eleven räknade fel och kanske tänkte parallellkoppling istället.
**WrongAnswer** 50 Ω **Why** Räknefel eller missförstånd av addition.

**Question** Två resistorer, 10 Ω och 10 Ω, är parallellkopplade. Vad blir den totala resistansen?
**InputType** single-choice
**Hint** Två lika resistorer i parallell halverar resistansen.
**Hint** Formeln 1/R_total = 1/R1 + 1/R2.
**Answer** 5 Ω
**MaxPoints** 1
**WrongAnswer** 20 Ω **Why** Eleven adderade istället för att använda parallellformeln.
**WrongAnswer** 10 Ω **Why** Tro att parallell inte påverkar totalresistansen.
**WrongAnswer** 2 Ω **Why** Felaktig användning av formel eller decimalmiss.

**Question** Vad händer med en lampa i seriekoppling om man lägger till ännu en likadan lampa i serien?
**InputType** multiple-choice
**Hint** Tänk på totalresistans och ström.
**Hint** Mer resistans → mindre ström → svagare ljus.
**Answer** Lampan blir svagare (mindre ljusstyrka)
**Answer** Totalströmmen i kretsen minskar
**MaxPoints** 2
**WrongAnswer** Lampan blir starkare **Why** Missuppfattning att fler lampor ger mer effekt.
**WrongAnswer** Inget händer med ljusstyrkan **Why** Förstår inte hur totalresistans påverkar ström.

**Question** Var i en krets placeras normalt en säkring (fuse) för att skydda kretsen?
**InputType** single-choice
**Hint** Tänk: säkringen ska skydda allt efter sig.
**Hint** Säkringen sitter i matningen från strömkällan.
**Answer** I serie med strömkällan (på matningen)
**MaxPoints** 1
**WrongAnswer** Parallellt med komponenterna **Why** Felaktig idé att säkringen skulle dela strömmen; då skyddar den inte.
**WrongAnswer** I mitten av en komponent **Why** Bristande förståelse av säkringens funktion.

**Question** Förklara varför en lampa i en parallellkoppling fortsätter lysa även om en annan lampa i samma krets slocknar.
**InputType** text
**Hint** Tänk på att varje lampa har sin egen gren.
**Hint** Strömmen kan ta andra vägar i parallellkoppling.
**Answer** Varje lampa sitter i en egen gren med samma spänning, så om en gren bryts påverkas inte de andra grenarna och deras lampor får fortfarande ström.
**MaxPoints** 3
**AnalyzeSubmission** Kontrollera om svaret nämner "egen gren", "samma spänning" eller "andra vägar för ström". Om minst två av dessa finns: delvis korrekt; om alla tre finns: korrekt.
**WrongAnswer** Eftersom batteriet är tillräckligt starkt **Why** Generaliserar felaktigt utan att förklara kretsens topologi.
**WrongAnswer** För att lamporna är kopplade i serie **Why** Förväxling av seriekoppling och parallellkoppling.

---

Nivå 3 (Svår)

**Question** En batterikälla på 12 V kopplar till två resistorer i serie, 6 Ω och 3 Ω. Beräkna strömmen i kretsen.
**InputType** text
**Hint** R_total = 6 + 3.
**Hint** Använd Ohms lag: I = V / R_total.
**Answer** 1.33 A
**MaxPoints** 3
**AnalyzeSubmission** Acceptera svar nära 1.33 A (t.ex. 4/3 A, 1.333 A) inom ±0.02 A. Om eleven uppger fel R_total, notera det som grundorsak till fel.
**WrongAnswer** 2 A **Why** Eleven kanske delade spänningen felaktigt eller räknade fel på totalresistansen.
**WrongAnswer** 0.5 A **Why** Felaktig division eller misstag i Ohms lag.

**Question** Två resistorer, 10 Ω och 20 Ω, är parallellkopplade. Vilken är den närmaste värdet på den ekvivalenta resistansen?
**InputType** multiple-choice
**Hint** Använd formeln 1/R = 1/R1 + 1/R2.
**Hint** R_eq = (R1*R2)/(R1+R2).
**Answer** 6.7 Ω
**MaxPoints** 2
**WrongAnswer** 30 Ω **Why** Eleven adderade resistorerna (serie-fel).
**WrongAnswer** 15 Ω **Why** Eleven tog medelvärdet istället för parallellformeln.
**WrongAnswer** 3.3 Ω **Why** Dubblat fel vid beräkning eller decimalförväxling.

**Question** En resistor på 3 Ω har 9 V över sig. Hur stor effekt (power) avger resistorn?
**InputType** single-choice
**Hint** Effekt P = V^2 / R eller P = V * I.
**Hint** Räkna först om du vill: I = V / R = 3 A, sedan P = V * I.
**Answer** 27 W
**MaxPoints** 2
**WrongAnswer** 3 W **Why** Felaktig användning av formel (kanske P = V/R misstolkat).
**WrongAnswer** 81 W **Why** Kan ha räknat V^2 men glömt dividera med R.

**Question** Ett batteri på 9 V ansluts till två identiska resistorer 6 Ω i parallell. Beräkna totala strömmen från batteriet.
**InputType** text
**Hint** Två 6 Ω i parallell blir 3 Ω totalt.
**Hint** Använd I_total = V / R_total.
**Answer** 3 A
**MaxPoints** 3
**AnalyzeSubmission** Acceptera svar nära 3 A (±0.05 A). Kontrollera att eleven antingen beräknat R_eq = 3 Ω och sedan I = 9 / 3 = 3 eller motsvarande resonemang.
**WrongAnswer** 1.5 A **Why** Eleven räknade ström i EN gren och glömde dubbla för två grenar.
**WrongAnswer** 0.5 A **Why** Felaktig beräkning av R_eq eller missförstånd av parallellkoppling.

**Question** När slår en säkring vanligtvis ifrån? (välj alla som gäller)
**InputType** multiple-choice
**Hint** Tänkt på säkringens märkström.
**Hint** Kortslutningar ger ofta mycket hög ström.
**Answer** När strömmen överstiger säkringens märkström
**Answer** Vid kortslutning där strömmen blir mycket hög
**MaxPoints** 2
**WrongAnswer** När spänningen är för hög **Why** Säkringar reagerar på ström, inte direkt på spänning.
**WrongAnswer** När temperaturen i rummet är hög **Why** Felaktig förståelse; dock kan hög temperatur påverka men det är inte huvudorsaken i normala scenarier.