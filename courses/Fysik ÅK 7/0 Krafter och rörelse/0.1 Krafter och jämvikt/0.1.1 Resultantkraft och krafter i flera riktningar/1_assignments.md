Level 1 — Lätt (Årskurs 7)

**Question** Vad är en resultantkraft?
**InputType** text
**Hint** Tänk på vad som händer om flera krafter verkar på samma punkt.
**Hint** Resultanten visar den samlade effekten av alla krafter.
**Answer** Den sammanlagda kraften som bestämmer rörelsens förändring.
**MaxPoints** 2
**AnalyzeSubmission** Kontrollera om elevens svar nämner att resultantkraften är "summan" eller "sammanlagda krafter", att den bestämmer rörelsens förändring eller acceleration, eller att det är en "nettokraft". Om minst ett av dessa begrepp finns: "korrekt", annars "fel".
**WrongAnswer** En kraft som alltid drar åt höger **Why** Missförstånd: tror att resultant har en bestämd riktning oberoende av krafter.

---

**Question** Två jämbördiga krafter drar i motsatt riktning, till exempel 5 N åt höger och 5 N åt vänster. Vilken är resultantens storlek?
**InputType** single-choice
**Hint** Tänk på vad som händer om två lika stora krafter drar åt motsatta håll.
**Hint** Resultanten blir summan i riktning (kan bli noll).
**Answer** 0 N
**MaxPoints** 1
**WrongAnswer** 10 N **Why** Felaktigt adderat absolutvärden istället för att ta hänsyn till riktning.
**WrongAnswer** 5 N **Why** Blandar ihop och tror att en av krafterna "vinner".

---

**Question** Vilken metod använder man för att rita resultant av två krafter grafiskt?
**InputType** single-choice
**Hint** Tänk på att man ska rita vektorer från samma punkt och sedan en diagonal.
**Hint** Parallellogrammet eller triangeln visar resultantens riktning och storlek.
**Answer** Rita båda krafter från samma punkt och dra diagonalen i parallellogrammet
**MaxPoints** 1
**WrongAnswer** Rita dem i serie utan att flytta startpunkt **Why** Missförstår att krafter måste starta i samma punkt vid addition.

---

**Question** En kraft på 3 N verkar åt öster och en annan på 4 N verkar åt norr. Hur stor är resultantens storlek?
**InputType** single-choice
**Hint** Dessa krafter är vinkelräta mot varandra — använd Pythagoras.
**Hint** 3-4-5-triangeln är vanligt förekommande.
**Answer** 5 N
**MaxPoints** 1
**WrongAnswer** 1 N **Why** Felaktig subtraktion istället för att använda Pythagoras.
**WrongAnswer** 7 N **Why** Felaktig addition av storlekar utan hänsyn till riktning.

---

**Question** I föregående uppgift (3 N öster, 4 N norr): Vilken riktning (ungefär) har resultantkraften mätt från österlig riktning uppåt (counterclockwise)?
**InputType** text
**Hint** Använd arctan(y/x) där y=4 och x=3.
**Hint** Beräkna arctan(4/3) och avrunda till närmaste grad.
**Answer** 53° (ungefär)
**MaxPoints** 2
**AnalyzeSubmission** Acceptera svar mellan 52° och 54° som korrekta. Om eleven skriver i radianer, konvertera och jämför om det motsvarar ~0.93 rad.
**WrongAnswer** 37° **Why** Blandar ihop vilken komponent som ska stå i täljare och nämnare (använder arctan(3/4) istället för arctan(4/3)).

---

**Question** Vilket påstående stämmer om ett föremål där resultantkraften inte är noll?
**InputType** single-choice
**Hint** Tänk på Newtons andra lag (F = ma).
**Hint** Om nettokraft finns så ändras föremålets rörelse.
**Answer** Föremålet får en acceleration / förändrar sin rörelse
**MaxPoints** 1
**WrongAnswer** Föremålet är alltid i vila **Why** Förväxlar obalans i krafter med jämvikt.
**WrongAnswer** Inget händer om det finns friktion **Why** Fokuserar bara på friktion och glömmer nettoresultatet av krafter.

---

Level 2 — Medel (Årskurs 7)

**Question** Beskriv stegvis hur du hittar resultantkraften när två krafter verkar i två olika riktningar (inte nödvändigtvis vinkelräta).
**InputType** text
**Hint** Rita vektorerna från samma startpunkt.
**Hint** Avsluta genom att rita parallellogram eller addera x- och y-komponenter.
**Answer** Rita krafterna från samma punkt, bilda parallellogram eller dela upp krafterna i x- och y-komponenter, summera komponenterna och bestäm resultantens storlek och riktning.
**MaxPoints** 3
**AnalyzeSubmission** Kontrollera att elevens beskrivning innehåller minst två av följande: rita krafter från samma punkt, använda parallellogram/diagonal, dekomponera i x- och y-komponenter, summera komponenter, beräkna storlek (Pythagoras) och riktning (arctan). Om minst två finns: "korrekt", annars "fel".
**WrongAnswer** Bara addera storlekarna **Why** Missar vektornatur och riktning.

---

**Question** Två krafter på 10 N vardera verkar i exakt motsatta riktningar. Vad blir resultantens storlek?
**InputType** single-choice
**Hint** De tar ut varandra om de är lika stora och motsatta.
**Answer** 0 N
**MaxPoints** 1
**WrongAnswer** 20 N **Why** Felaktig addition utan att ta hänsyn till riktning.
**WrongAnswer** 10 N **Why** Tror att en kraft alltid är "starkare" även fast de är lika stora.

---

**Question** En låda dras med 2 N mot öster och 2 N mot norr. Välj alla rätta påståenden.
**InputType** multiple-choice
**Hint** De är vinkelräta krafter.
**Hint** Komponenterna i x- respektive y-led är 2 N vardera.
**Answer** Komponent i x-led är 2 N
**Answer** Komponent i y-led är 2 N
**Answer** Resultantens storlek är cirka 2.8 N
**Answer** Resultantens riktning är 45° nordost
**MaxPoints** 4
**WrongAnswer** Resultantens storlek är 4 N **Why** Felaktig addition av magnituder utan riktning.
**WrongAnswer** Resultantens riktning är 90° **Why** Missförstår hur riktning bestäms från komponenter.

---

**Question** Räkna ut komponenterna i x- och y-led för en kraft på 10 N som verkar i 30° över horisontalen (x-axeln).
**InputType** text
**Hint** Använd cos för x-komponenten och sin för y-komponenten.
**Hint** cos30 ≈ 0.866, sin30 = 0.5.
**Answer** Fx ≈ 8.66 N, Fy = 5 N
**MaxPoints** 3
**AnalyzeSubmission** Acceptera svar där Fx ligger mellan 8.6 och 8.7 N och Fy mellan 4.9 och 5.1 N. Om enbart omvända funktioner (sin/cos bytta) används, markera som fel men ge feedback.
**WrongAnswer** Fx = 5 N, Fy = 8.66 N **Why** Bytt plats på sin och cos för komponentsberäkning.

---

**Question** Om resultantkraften på ett föremål är noll, vad kan sägas om föremålets rörelse just nu?
**InputType** single-choice
**Hint** Jämvikt betyder ingen nettokraft.
**Hint** Objektet kan vara i vila eller röra sig med konstant hastighet.
**Answer** Föremålet är i jämvikt: antingen i vila eller rör sig med konstant hastighet
**MaxPoints** 1
**WrongAnswer** Föremålet måste accelerera **Why** Förväxlar kraftens effekt med annan kraftlag.

---

Level 3 — Svår (Årskurs 7)

**Question** Tre krafter är i jämvikt. Två av dem är F1 = 5 N i 0° (öst) och F2 = 7 N i 120° (mätt från östlig riktning mot moturs). Bestäm storlek och riktning för den tredje kraften F3 som behövs för jämvikt.
**InputType** text
**Hint** Bestäm först summan av komponenterna för F1 och F2, sedan ta motsatt riktning för F3.
**Hint** Räkna x- och y-komponenter: cos120 = -0.5, sin120 ≈ 0.866.
**Answer** F3 ≈ 6.24 N, riktning ≈ 256° (mätt från östlig riktning moturs)
**MaxPoints** 4
**AnalyzeSubmission** Kontrollera beräkning av komponenter för F1 och F2: (5,0) och (-3.5, ≈6.06). Summan ≈ (1.5, 6.06). F3 är motsatsen ≈ (-1.5, -6.06). Magnitud ≈ 6.24 N (acceptera 6.2–6.3) och riktning ≈ 256° (acceptera 254–258°). Om eleven presenterar riktning som “104° nedåt från öst” eller som negativ vinkel, acceptera om ekvivalent.
**WrongAnswer** F3 = 2 N åt sydväst **Why** Tar bara skillnad i någon komponent eller avrundar felaktigt utan vektoradd.

---

**Question** Vilken formel är korrekt för x-komponenten (Fx) av en kraft F som bildar vinkel θ mot x-axeln?
**InputType** single-choice
**Hint** Tänk på vilka trigonometriska funktioner ger närliggande katet.
**Hint** Fx = F cos θ eller Fx = F sin θ — välj rätt.
**Answer** Fx = F · cos θ
**MaxPoints** 1
**WrongAnswer** Fx = F · sin θ **Why** Vanligt misstag att byta sin och cos beroende på vilken komponent som är närliggande.

---

**Question** Två krafter verkar: 12 N i 60° och 5 N i 240°. Välj alla korrekta påståenden.
**InputType** multiple-choice
**Hint** Beräkna komponenter för båda krafter och summera.
**Hint** cos60=0.5, sin60≈0.866; cos240=-0.5, sin240≈-0.866.
**Answer** Resultantens x-komponent är 3.5 N
**Answer** Resultantens y-komponent är ≈ 6.06 N
**Answer** Resultantens storlek är 7 N
**Answer** Resultantens riktning är ≈ 60°
**MaxPoints** 4
**WrongAnswer** Resultantens storlek är 5 N **Why** Felaktig vektoraddition eller avrundningsfel.
**WrongAnswer** Resultantens riktning är 240° **Why** Förväxlar en av kraftriktningarna med resultantens riktning.

---

**Question** En kropp är i jämvikt under tre krafter: F1 = 8 N i 0° (öst) och F2 = 6 N i 90° (norr). Bestäm F3:s storlek och riktning.
**InputType** text
**Hint** Summan av x-komponenter måste vara noll och summan av y-komponenter måste vara noll.
**Hint** Fx3 = -8 N, Fy3 = -6 N → magnitud = sqrt(8^2+6^2).
**Answer** F3 = 10 N, riktning ≈ 217° (mätt från östlig riktning moturs)
**MaxPoints** 4
**AnalyzeSubmission** Acceptera magnitud 10 N (exakt) och riktning mellan 215°–219°. Alternativt accepterar beskrivning "10 N riktning sydväst" eller vinkel som 180°+36.87° ≈ 216.87°.
**WrongAnswer** F3 = 2 N åt sydväst **Why** Tar ej hänsyn till båda komponenterna eller subtraherar felaktigt.

---

**Question** Om två lika stora krafter F bildar en vinkel på 60° mellan sig, vilken är resultantens storlek uttryckt i F?
**InputType** single-choice
**Hint** Resultantformeln för lika krafter: R = 2F cos(θ/2).
**Hint** Här θ/2 = 30°, cos30 ≈ 0.866.
**Answer** R = 2F · cos30 ≈ 1.732·F
**MaxPoints** 2
**WrongAnswer** R = 2F **Why** Felaktigt antagande att man bara adderar storlekar utan vinkel.
**WrongAnswer** R = F **Why** Tror att krafter som inte är exakt motsatta inte påverkar varandra.

---

Slutsats: Sektionerna ovan innehåller totalt 18 uppgifter i tre svårighetsnivåer (lätt, medel, svår). Varje uppgift följer den begärda strukturen med Hint, Answer, MaxPoints, AnalyzeSubmission (för textfrågor) och misstag (WrongAnswer) samt förklaringar varför fel svar kan uppstå.