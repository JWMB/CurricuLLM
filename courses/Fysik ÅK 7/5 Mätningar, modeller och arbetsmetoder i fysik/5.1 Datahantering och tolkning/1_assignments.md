Sektion: Datahantering och tolkning — svårighetsgrad 1 (Lätt)

**Question** Läs av värdet på mätpunkten i tabellen: Temperatur vid klockan 10:00 är 18,5 °C. Vilket värde skrivs i tabellen om värdet avrundas till en decimal?
**InputType** text
**Hint** Titta på siffran efter första decimalen.
**Hint** Om den andra decimalen är 5 eller mer, avrunda uppåt.
**Answer** 18,5
**MaxPoints** 1
**AnalyzeSubmission** Kontrollera om svaret exakt är "18,5" (inklusive kommatecken eller punkt accepteras). Om ja, returnera "correct", annars "incorrect".
**WrongAnswer** 18,0 **Why** Kunde bero på att man skrev av fel decimal eller tänkte att man skulle avrunda ner.

**Question** Vad betyder "mätnoggrannhet"?
**InputType** text
**Hint** Tänk på hur nära mätvärden ligger varandra.
**Hint** Inte samma som "riktighet" (accuracy) som handlar om hur nära ett värde är det sanna värdet.
**Answer** Hur lika upprepade mätningar är varandra / hur spridda mätvärden är
**MaxPoints** 2
**AnalyzeSubmission** Kontrollera om svaret nämner upprepade mätningar eller spridning mellan mätvärden; om ja, ge poäng i förhållande till fullständighet (2 poäng om båda idéerna nämns, 1 poäng om en nämns), annars 0.
**WrongAnswer** Hur nära mätningen är det verkliga värdet **Why** Det beskriver "riktighet", inte "noggrannhet".

**Question** Vilken enhet används vanligtvis för att ange osäkerhet i en längdmätning?
**InputType** single-choice
**Hint** Enheten är samma som för själva längden.
**Hint** Vanliga längdenheter: mm, cm, m
**Answer** cm
**Answer** m
**MaxPoints** 1
**WrongAnswer** liter **Why** Volymenhet, inte lämplig för längd.
**WrongAnswer** grader **Why** Temperatur/vinkel, inte längd.

**Question** På ett stapeldiagram visas antal elever som tycker om olika frukter. Stapeln för äpple är längst. Vad kan man dra för slutsats?
**InputType** multiple-choice
**Hint** Tänk på vad stapellängd visar.
**Hint** Välj alla meningar som är rimliga utifrån diagrammet.
**Answer** Fler elever valde äpple än de andra frukterna
**Answer** Äpple är mest populärt i denna undersökning
**MaxPoints** 2
**WrongAnswer** Alla elever gillar äpple **Why** Diagrammet visar "fler" eller "mest", inte att "alla" valde det.
**WrongAnswer** Stapeln visar vikten av äpple **Why** Stapeldiagrammet visar antal/antal personer, inte vikt.

**Question** Vilken av följande är en vanlig felkälla när man mäter temperatur med en termometer?
**InputType** single-choice
**Hint** Tänk på yttre påverkan på termometern.
**Hint** Felkälla: placering, kalibrering eller hantering.
**Answer** Termometern stod i direkt solljus
**MaxPoints** 1
**WrongAnswer** Termometern var för lång **Why** Beskrivningen är otydlig och inte en typisk felkälla.
**WrongAnswer** Vi mätte för många gånger **Why** Flera mätningar är oftast bra för noggrannhet, inte en felkälla i sig.

**Question** Vilka av följande hjälper till att minska mätosäkerhet?
**InputType** multiple-choice
**Hint** Välj alla som minskar spridningen i mätresultat.
**Hint** Tänk på upprepade mätningar och bättre utrustning.
**Answer** Göra flera upprepade mätningar
**Answer** Använda bättre kalibrerad utrustning
**MaxPoints** 2
**WrongAnswer** Göra mätningen snabbare **Why** Hastighet minskar inte nödvändigtvis osäkerhet och kan ge fler fel.
**WrongAnswer** Ta bort alla mätningar som avviker utan kontroll **Why** Att slentrianmässigt ta bort avvikare kan felaktigt påverka resultatet och dölja verklig spridning.

---

Sektion: Datahantering och tolkning — svårighetsgrad 2 (Medel)

**Question** Förklara skillnaden mellan "systematiskt fel" och "slumpmässigt fel" i mätningar.
**InputType** text
**Hint** Tänk på om felet påverkar alla mätningar likadant eller varierar.
**Hint** Ge ett exempel på varje typ.
**Answer** Systematiskt fel påverkar mätningar på samma sätt (t.ex. felkalibrerad våg); slumpmässigt fel varierar mellan mätningar (t.ex. små variationer i avläsning).
**MaxPoints** 3
**AnalyzeSubmission** Kontrollera om svaret nämner att systematiskt fel ger en konstant eller förskjutning åt samma håll och att slumpmässigt fel ger spridning/variation mellan mätningar. Ge 3 poäng för båda förklaringarna med exempel, 1–2 poäng om bara en del är korrekt, 0 om fel.
**WrongAnswer** Båda är samma sak **Why** Missförståelse att feltyper inte skiljer sig åt.

**Question** Ett linjediagram visar temperatur under en vecka. Temperaturen ökar stadigt från måndag till fredag och sjunker på lördagen. Vad visar diagrammet?
**InputType** single-choice
**Hint** Tänk på "stadigt ökande" och "sjunker".
**Hint** Välj det som bäst beskriver förändring över tid.
**Answer** Temperaturen steg under veckan och föll under helgen
**MaxPoints** 1
**WrongAnswer** Temperaturen var densamma varje dag **Why** Ignorerar beskrivningen om ökning och minskning.
**WrongAnswer** Diagrammet visar lufttrycket **Why** Det handlar om temperatur, inte lufttryck.

**Question** Du har gjort tre längdmätningar av samma föremål: 12,3 cm; 12,5 cm; 12,4 cm. Ange medelvärde och skriv också en enkel uppskattning av spridning (avvikelse från medelvärdet).
**InputType** text
**Hint** Räkna ihop och dela med antal mätningar för medelvärde.
**Hint** Avvikelse: räkna differensen från medelvärdet för varje mätning.
**Answer** Medelvärde 12,4; avvikelser: -0,1; +0,1; 0,0 (eller spridning 0,2)
**MaxPoints** 3
**AnalyzeSubmission** Kontrollera att medelvärdet är 12,4 (till en decimal). Kontrollera att avvikelserna anges som -0,1; 0; +0,1 eller att spridningen anges som 0,2 cm. Ge full poäng om detta stämmer, annars partiell.
**WrongAnswer** Medelvärde 12,3 **Why** Fel i uträkning eller att man bara tog första värdet.
**WrongAnswer** Spridning 1,0 **Why** Förväxlar kanske med standardavvikelse eller räknar felaktigt.

**Question** Vilka påståenden om en modell är sanna?
**InputType** multiple-choice
**Hint** En modell förenklar verkligheten och beskriver mönster.
**Hint** Tänk på modellens användbarhet och begränsningar.
**Answer** En modell förenklar verkligheten
**Answer** En modell kan vara användbar även om den inte är helt korrekt
**MaxPoints** 2
**WrongAnswer** En modell visar alltid exakt hur verkligheten är **Why** Missuppfattning; modeller är förenklingar.
**WrongAnswer** En modell är onyttig om den inte är sann i alla detaljer **Why** Felaktig syn; många modeller är ändå användbara.

**Question** I en undersökning frågade man 100 elever om de cyklar till skolan. Resultatet visades i ett cirkeldiagram: 40 % ja, 60 % nej. Om undersökningen istället bara hade 10 elever med samma proportioner, vad händer med osäkerheten?
**InputType** single-choice
**Hint** Tänk på provstorlekens effekt på tillförlitlighet.
**Hint** Mindre urval ger större osäkerhet i procentandelar.
**Answer** Osäkerheten blir större vid 10 elever än vid 100 elever
**MaxPoints** 1
**WrongAnswer** Osäkerheten blir mindre vid 10 elever **Why** Missuppfattning kring provstorlek.
**WrongAnswer** Osäkerheten påverkas inte av antal deltagare **Why** Fel, provstorlek påverkar statistisk osäkerhet.

---

Sektion: Datahantering och tolkning — svårighetsgrad 3 (Svårt)

**Question** Du mätte elektrisk resistans flera gånger och fick dessa värden (i ohm): 98, 102, 95, 105, 100. Beräkna medelvärde, median och ge en kommentar om utrustningens noggrannhet och möjliga felkällor.
**InputType** text
**Hint** Medelvärde = summan / antal. Median = mellersta värdet efter sortering.
**Hint** Tänk på spridning och om resultaten ligger nära varandra.
**Answer** Medelvärde 100; median 100; kommentar: värden ligger nära varandra (±5), visar god noggrannhet men vissa systematiska fel eller kalibrering kan finnas.
**MaxPoints** 5
**AnalyzeSubmission** Kontrollera att medelvärdet beräknats till 100 ohm och median till 100 ohm. Kontrollera att kommentaren nämner spridning (t.ex. ±5) och möjligtvis systematiskt fel eller kalibrering. Ge poäng: 2 för korrekt medelvärde+median, 3 för en relevant kommentar (noggrannhet och åtminstone en möjlig felkälla).
**WrongAnswer** Medelvärde 1000 **Why** Räknefell eller felaktig placerad decimal.
**WrongAnswer** Median 98 **Why** Fel vid sortering eller val av mellersta värde.

**Question** Beskriv hur du skulle planera ett experiment för att undersöka hur noggrant en linjal mäter längd. Ta med vilka variabler du kontrollerar, hur många upprepningar, och hur du hanterar felkällor.
**InputType** text
**Hint** Ange kontroll av temperatur, samma person som läser av, flera upprepningar.
**Hint** Tänk på att jämföra mot en standard (t.ex. måttband eller kalibrerad linjal).
**Answer** Plan: mät samma föremål flera gånger (minst 5) med linjalen och en kalibrerad referens; kontrollera temperatur och avläsningspunkt; ha samma mätare; räkna medelvärde och spridning; undersök systematiskt fel genom jämförelse med referens.
**MaxPoints** 6
**AnalyzeSubmission** Kontrollera att svaret nämner: upprepade mätningar (minst 3–5), kontroll av variabler (temperatur, samma mätare eller metod), användning av referens eller kalibrering, och beräkning av medelvärde/spridning. Ge poäng beroende på hur många av dessa punkter som finns: full poäng om alla nämns, partiell annars.
**WrongAnswer** Bara mäta en gång för att spara tid **Why** Ger ingen information om noggrannhet eller spridning.

**Question** Vilket uttalande om modeller i naturvetenskap är mest korrekt?
**InputType** single-choice
**Hint** En modell hjälper förklaringar men har begränsningar.
**Hint** Tänk på att modeller kan ändras när ny data kommer.
**Answer** Modeller är förenklingar som kan ändras när ny information finns
**MaxPoints** 1
**WrongAnswer** Modeller är alltid absoluta sanningar **Why** Förstår inte att modeller är förenklingar.
**WrongAnswer** Modeller behövs inte i vetenskap **Why** Fel, modeller är centrala för förklaring och förutsägelse.

**Question** I en laboration visar ett linjärt samband i en modell att y = 2x + 1. Efter mätningar passerar inte alla punkter exakt genom linjen. Vilka förklaringar är rimliga? (Välj alla som gäller.)
**InputType** multiple-choice
**Hint** Tänk på både mätfel och modellbegränsningar.
**Hint** Välj flera alternativ som kan förklara avvikelser.
**Answer** Mätosäkerhet i mätningar
**Answer** Modellen är en förenkling och missar vissa effekter
**Answer** Fel i avläsning eller i utrustningen
**MaxPoints** 3
**WrongAnswer** Att linjen är felritad utan anledning **Why** Inte en rimlig förklaring utan undersökning.
**WrongAnswer** Att alla mätningar måste ligga exakt på linjen i verkligheten **Why** Missförstår naturen av mätosäkerhet och modellens approximativa karaktär.

**Question** Du får följande dataset: 2, 2, 3, 14, 3, 2. Ange median, medelvärde och diskutera om medelvärdet påverkas mycket av avvikare (outliers).
**InputType** text
**Hint** Sortera för median; medelvärde = summa/antal.
**Hint** Fundera på vilken roll värdet 14 spelar jämfört med andra värden.
**Answer** Median 2, medelvärde 4,5; medelvärdet påverkas starkt av avvikaren 14
**MaxPoints** 4
**AnalyzeSubmission** Kontrollera att median är 2 och medelvärde är 4,5 (ungefär). Kontrollera att kommentaren nämner att medelvärdet påverkas mycket av avvikaren och att median är mer robust. Ge poäng för korrekta beräkningar och för en korrekt tolkning.
**WrongAnswer** Median 3 **Why** Fel vid sortering eller val av mittvärde.
**WrongAnswer** Medelvärde 2,7 **Why** Fel i summering eller division.

---