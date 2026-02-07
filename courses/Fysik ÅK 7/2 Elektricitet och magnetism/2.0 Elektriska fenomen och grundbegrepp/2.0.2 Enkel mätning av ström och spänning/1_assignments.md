Nedan följer uppgifter för avsnittet "Enkel mätning av ström och spänning". Uppgifterna är uppdelade i tre svårighetsnivåer (1–3). För varje uppgift finns fråga, typ av inmatning, ledtrådar, korrekta svar, poäng, analys (för fritextfrågor) och vanliga fel svar med förklaring.

Nivå 1 — Lätt
1)
**Question** Vad mäter en voltmeter?
**InputType** single-choice
**Hint** Tänk på bokstaven V.
**Hint** Den kopplas parallellt över en komponent.
**Answer** Spänning (volt)
**MaxPoints** 1
**WrongAnswer** Strömstyrka **Why** Det mäter istället en ammeter och enheten för ström är A.
**WrongAnswer** Resistans **Why** Resistans mäts med ohm-meter eller multimeter i ohm-läge, inte med voltmeter.

2)
**Question** Hur många volt är det om du har två batterier på 1,5 V i serie?
**InputType** text
**Hint** Lägg ihop spänningarna i serie.
**Hint** 1,5 + 1,5 = ?
**Answer** 3
**MaxPoints** 1
**AnalyzeSubmission** Kontrollera om svaret är talet 3 eller "3 V". Om så är fallet, returnera "correct", annars "incorrect".
**WrongAnswer** 1,5 **Why** Eleven tänkte bara på ett av batterierna, inte båda i serie.
**WrongAnswer** 2 **Why** Felaktig addition eller förväxling med parallellkoppling där spänningen blir densamma.

3)
**Question** Var ska du koppla en amperemeter när du vill mäta ström genom en lampa i en enkel krets?
**InputType** text
**Hint** Tänk på att ström måste flyta genom mätaren.
**Hint** Du måste bryta kretsen och sätta mätaren där du öppnat den.
**Answer** I serie med lampan
**MaxPoints** 2
**AnalyzeSubmission** Leta efter formuleringar som "i serie", "seriekopplad", eller "sätta mätaren i ledningen så att strömmen passerar genom den". Om svaret innehåller detta, ge "correct", annars "incorrect".
**WrongAnswer** Parallellt över lampan **Why** Det visar att eleven förväxlat voltmeter och amperemeter; en amperemeter får då en kortslutning och fel värde.

4)
**Question** Vilken enhet används för strömstyrka?
**InputType** single-choice
**Hint** Enheten börjar med bokstaven A.
**Hint** Samma enhet som en amperemeter visar.
**Answer** A (ampere)
**MaxPoints** 1
**WrongAnswer** V (volt) **Why** Volt är enheten för spänning, inte för ström.
**WrongAnswer** Ω (ohm) **Why** Ohm är enheten för resistans.

5)
**Question** Ange två säkerhetsregler när du använder en multimeter för att mäta ström eller spänning.
**InputType** text
**Hint** Tänk på att känna till korrekt mätområde och hur du kopplar mätaren.
**Hint** Använd aldrig mätaren i fel läge (t.ex. amperemeter i voltläge) eller kortslut batterier.
**Answer** Kontrollera och välj rätt mätområde / Se till att mätsladdarna är korrekt satta / Koppla amperemetern i serie och voltmetern i parallell / Undvik kortslutning och använd skydd (inget blött underlag). 
**MaxPoints** 3
**AnalyzeSubmission** Kontrollera att minst två av följande säkerheter nämns: "välj rätt mätområde", "koppla amperemeter i serie", "koppla voltmeter parallellt", "undvik kortslutning", "koppla bort ström innan du ändrar koppling", "använd isolerade händer/släck ström vid okända fel". Ge poäng per nämnd korrekt regel (max 3).
**WrongAnswer** Det är alltid säkert att använda högsta spänningsläget **Why** Felaktig tro; högsta läge kan skydda men felkoppling eller kortslutning kan fortfarande skada mätaren.

6)
**Question** Vilket påstående stämmer om en voltmeter i en krets?
**InputType** multiple-choice
**Hint** Den ska inte förändra kretsens ström i betydande grad.
**Hint** Den kopplas över komponenter och har hög inre resistans.
**Answer** Den kopplas parallellt över en komponent
**Answer** Den har hög inre resistans
**MaxPoints** 2
**WrongAnswer** Den kopplas i serie **Why** Förväxling med amperemeter; att koppla en voltmeter i serie ger felaktig mätning.
**WrongAnswer** Den har låg inre resistans **Why** Det skulle dra mycket ström och påverka kretsen; fel uppfattning om instrumentets konstruktion.

Nivå 2 — Medel
7)
**Question** Du ska mäta spänningen över en resistor i en krets med batteri. Beskriv steg för steg hur du kopplar multimetern (volt-läge) och gör mätningen.
**InputType** text
**Hint** Tänk på att välja rätt mätområde först.
**Hint** Koppla mätarens sladdar till rätt jack och sätt den över resistorn utan att bryta kretsen.
**Answer** Välj voltläge och rätt mätområde / Sätt röd sladd i V-ingång, svart i COM / Koppla mätprobarnas spetsar över resistorn (parallellt) / Avläs värdet
**MaxPoints** 4
**AnalyzeSubmission** Kontrollera att svaret innehåller minst fyra steg i rätt ordning: (1) välj volt-läge och mätområde, (2) anslut röd till V och svart till COM, (3) placera proberna parallellt över komponenten, (4) läs av värdet. Ge poäng per korrekt steg (max 4).
**WrongAnswer** Sätt multimetern i ampere-läge och sätt den över resistorn **Why** Eleven förväxlar volt- och ampermätning vilket kan kortsluta eller ge fel mätning.

8)
**Question** En krets med ett batteri 9 V och en lampa ger ström 0,3 A. Hur stor effekt (W) förbrukar lampan? (P = U × I)
**InputType** text
**Hint** Använd formeln P = U × I.
**Hint** 9 × 0,3 = ?
**Answer** 2,7
**MaxPoints** 2
**AnalyzeSubmission** Kontrollera om eleven skriver "2,7" eller "2,7 W". Om ja, returnera "correct". Om eleven använder fel multiplikation eller fel enhet, returnera "incorrect".
**WrongAnswer** 27 **Why** Felaktig decimalflytt eller missförstånd av enheterna (9×3 istället för 9×0,3).
**WrongAnswer** 0,03 **Why** Dividerat istället för multiplicerat eller felaktig placering av decimalpunkt.

9)
**Question** Vilken av följande åtgärder är korrekt när du ska mäta ström med en multimeter? (Markera alla som är korrekta.)
**InputType** multiple-choice
**Hint** Tänk på hur amperemetern måste ingå i kretsen.
**Hint** Det handlar om inställning av mätinstrumentet och koppling.
**Answer** Bryt kretsen och koppla mätaren i serie
**Answer** Välj ett lämpligt strömområde på mätaren innan mätning
**MaxPoints** 2
**WrongAnswer** Koppla mätaren parallellt över strömkällan **Why** Parallellkoppling ger kortslutning och fel mätning.
**WrongAnswer** Använd alltid mätarens högsta spänningsläge för ström **Why** Felaktig kombination av lägen; man måste välja strömläge och inte spänningsläge.

10)
**Question** Vad händer om du försöker mäta ström genom att koppla en multimeter i volt-läget i serie i en krets?
**InputType** single-choice
**Hint** Tänk på att voltläge har hög inre resistans.
**Hint** Vad händer med strömmen om du sätter in en hög resistans i kretsen?
**Answer** Strömmen blir mycket liten eller mätaren skyddar kretsen (mätningen blir felaktig)
**MaxPoints** 1
**WrongAnswer** Du får rätt strömvärde **Why** Felaktig förståelse; voltläget ger inte korrekt ström eftersom mätarens höga resistans blockerar strömmen.
**WrongAnswer** Mätaren exploderar alltid **Why** Överdrift; det kan skada mätaren i vissa felkopplingar men vanligtvis leder voltläge till fel mätning snarare än explosion.

11)
**Question** En voltmeter visar 4,5 V över en komponent. Vilken av följande slutsatser är riktig? (Välj en.)
**InputType** single-choice
**Hint** Spänning är skillnaden i elektrisk potential mellan två punkter.
**Hint** Voltmeter visar skillnad mellan sina två prober.
**Answer** Det är 4,5 V mellan de två punkterna där proberna sitter
**MaxPoints** 1
**WrongAnswer** Det betyder att komponenten har 4,5 A genom sig **Why** Förväxling mellan spänning (V) och ström (A).
**WrongAnswer** Batteriet är på 4,5 A **Why** Förväxling mellan enheter och begrepp.

Nivå 3 — Svår
12)
**Question** En enkel krets: batteri 12 V, resistor R = 60 Ω. Beräkna strömmen i kretsen med Ohms lag.
**InputType** text
**Hint** I = U / R.
**Hint** 12 / 60 = ?
**Answer** 0,2
**MaxPoints** 2
**AnalyzeSubmission** Kontrollera om svaret är "0,2" eller "0,2 A". Ge "correct" om detta, annars "incorrect".
**WrongAnswer** 3 **Why** Eleven kan ha bytt plats på R och I eller multiplicerat istället för dividerat.
**WrongAnswer** 0,02 **Why** Felaktig decimalplacering (12/600?) eller skrivfel.

13)
**Question** Du mäter ström men får oväntat högt värde. Vilka fel kan ha skett? (Välj alla rimliga orsaker.)
**InputType** multiple-choice
**Hint** Tänk på koppling, mätinstrumentets läge och kortslutning.
**Hint** Tänk på om mätaren kan ha kopplats parallellt av misstag.
**Answer** Ammeter kopplad parallellt av misstag
**Answer** Fel mätområde valt så mätaren visar ohämmat värde eller är överbelastad
**Answer** Kortslutning i kretsen
**MaxPoints** 3
**WrongAnswer** Voltmeter istället för resistansmätare **Why** Mindre relevant för högt strömvärde; ger inte direkt orsaken.
**WrongAnswer** Batteriet bytt ut till 1,5 V **Why** Ger inte högre ström normalt; ovanligt fel för att få högtt värde.

14)
**Question** En voltmeter har hög inre resistans och en amperemeter har låg inre resistans. Förklara varför dessa egenskaper är önskvärda (kort).
**InputType** text
**Hint** Tänk på hur en mätare påverkar kretsen.
**Hint** Hur påverkar motstånd i mätaren den totala strömmen och spänningsfallet?
**Answer** Voltmeterns höga inre resistans gör att den inte tar ström så den påverkar inte spänningen i kretsen. Ammetermeterns låga inre resistans gör att den inte lägger stort spänningsfall i kretsen och ändrar inte strömmen mycket.
**MaxPoints** 3
**AnalyzeSubmission** Leta efter två förklaringar: (1) voltmetern ska ha hög resistans för att inte påverka kretsen; (2) amperemetern ska ha låg resistans för att inte lägga till spänningsfall. Ge poäng för varje korrekt del (max 3).
**WrongAnswer** Voltmetern behöver hög resistans för att mäta ström korrekt **Why** Förväxling; voltmeterens höga resistans är för att inte påverka spänningen, inte för att mäta ström.

15)
**Question** Du ska mäta ström i en del av ett enkelt nätverk som är parallellkopplat. Vilken metod är korrekt?
**InputType** single-choice
**Hint** Du måste mäta just strömmen genom en gren.
**Hint** Kom ihåg att ammeter ska ingå i den specifika grenen.
**Answer** Bryt den valda grenen och koppla in amperemetern i serie i den grenen
**MaxPoints** 2
**WrongAnswer** Koppla amperemetern i huvudledningen utan att bryta grenen **Why** Då mäter du eventuell annan summaström, inte strömmen i den specifika grenen.
**WrongAnswer** Koppla amperemetern parallellt över hela nätverket **Why** Kortslutning och felaktig metod.

16)
**Question** En multimeter har ett internt motstånd i ampereläget som är 0,05 Ω. Du mäter ström i en krets med total resistans 10 Ω och spänning 5 V. Hur mycket påverkar amperemeterns inre resistans strömmen i procent (ungefär)? (Beräkna ström med och utan meters inre resistans och jämför.)
**InputType** text
**Hint** Beräkna först ström utan meter: I = U/R.
**Hint** Beräkna sedan med meterens extra 0,05 Ω i serie: R_total = 10 + 0,05.
**Answer** Ca 0,5 %
**MaxPoints** 4
**AnalyzeSubmission** Kontrollera följande beräkning: I0 = 5 / 10 = 0,5 A; I1 = 5 / 10,05 ≈ 0,4975 A; procentändring = (0,5 - 0,4975)/0,5 ≈ 0,005 = 0,5 %. Om eleven visar liknande uträkning och cirka 0,5 %, ge "correct".
**WrongAnswer** 5 % **Why** Eleven missade decimaler eller använde fel resistansaddition.
**WrongAnswer** 50 % **Why** Stora räknefel eller missförstånd av hur liten 0,05 Ω är jämfört med 10 Ω.

Slut.