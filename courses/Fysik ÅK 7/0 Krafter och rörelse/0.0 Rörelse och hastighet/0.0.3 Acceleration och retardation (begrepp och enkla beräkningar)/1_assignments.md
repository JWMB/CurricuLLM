Svårighetsnivå 1 (Lätt)

**Question** Vad betyder acceleration?
**InputType** text
**Hint** Tänk på vad som händer med hastigheten när ett fordon ökar fart.
**Hint** Det handlar om förändring av hastighet per tidsenhet.
**Answer** Förändring av hastighet per tidsenhet
**MaxPoints** 2
**AnalyzeSubmission** Kontrollera om svaret nämner "förändring av hastighet" och "tid" (t.ex. "ändring av hastighet per sekund", "hastighetsökning per tidsenhet"). Om så är fallet, svara "correct", annars "incorrect".
**WrongAnswer** Hastighet **Why** Hastighet är hur snabbt något rör sig, men acceleration beskriver hur hastigheten ändras.
**WrongAnswer** Avstånd **Why** Avstånd är inte förändring av hastighet.

**Question** En bil ökar från 0 m/s till 10 m/s på 5 s. Beräkna accelerationen.
**InputType** text
**Hint** Använd a = (Δv) / Δt.
**Hint** Δv = 10 − 0 = 10 m/s, Δt = 5 s.
**Answer** 2 m/s^2
**MaxPoints** 2
**AnalyzeSubmission** Acceptera numeriska svar som "2", "2,0", eller "2 m/s^2". Om användaren anger 2 (med eller utan enhet m/s^2) ge "correct", annars "incorrect".
**WrongAnswer** 0,5 m/s^2 **Why** Blandning av division med felaktiga tal, troligen 5/10 i stället för 10/5.
**WrongAnswer** 20 m/s^2 **Why** Multiplicerade i stället för dividerade.

**Question** Vilken enhet används oftast för acceleration i fysik på grundskolan?
**InputType** single choice
**Hint** Tänk på att hastighet ofta mäts i m/s.
**Hint** Acceleration visar förändring i hastighet per sekund.
**Answer** m/s^2
**MaxPoints** 1
**WrongAnswer** m/s **Why** m/s är enhet för hastighet, inte för acceleration.
**WrongAnswer** km/h **Why** km/h är enhet för hastighet, inte för acceleration.
**WrongAnswer** m **Why** m är enhet för längd, inte för acceleration.

**Question** Om en cyklist bromsar så att hastigheten minskar, vad kallas det?
**InputType** single choice
**Hint** Det är motsatsen till acceleration.
**Hint** Ett annat ord som ofta används är inbromsning.
**Answer** Retardation (inbromsning)
**MaxPoints** 1
**WrongAnswer** Hastighet **Why** Hastighet är inte själva förändringen.
**WrongAnswer** Avstånd **Why** Avstånd handlar om hur långt, inte om minskning av hastighet.

**Question** En fotbollsspelare springer med hastigheten 6 m/s i 4 s. Under dessa 4 s ökar hastigheten jämnt till 10 m/s. Hur långt färdas spelaren under de 4 sekunderna?
**InputType** text
**Hint** För konstant acceleration kan medelhastigheten användas: (v0 + v)/2.
**Hint** v0 = 6 m/s, v = 10 m/s, tid = 4 s.
**Answer** 32 m
**MaxPoints** 3
**AnalyzeSubmission** Acceptera numeriska svar som "32", "32 m" eller "32 m." För kontroll: räkna ut v_med = (6+10)/2 = 8 m/s, s = 8*4 = 32 m. Om detta stämmer, "correct", annars "incorrect".
**WrongAnswer** 16 m **Why** Endera glömt multiplicera med tid eller tagit medelvärdet felaktigt (t.ex. (10-6)/2).
**WrongAnswer** 40 m **Why** Kan ha multiplicerat slutlig hastighet med tid utan att använda medelhastigheten.

**Question** Vilket ritas i ett hastighet–tid-diagram som en lutande linje uppåt?
**InputType** single choice
**Hint** Tänk på vad lutning visar i ett v–t-diagram.
**Hint** Uppåt betyder hastigheten blir större med tiden.
**Answer** Positiv acceleration
**MaxPoints** 1
**WrongAnswer** Negativ acceleration **Why** Negativ acceleration skulle ge en nedåtgående lutning.
**WrongAnswer** Konstant hastighet **Why** Konstant hastighet visas som en horisontell linje.
**WrongAnswer** Ingen rörelse **Why** Ingen rörelse visas som en horisontell linje vid v = 0.

Svårighetsnivå 2 (Mellan)

**Question** Förklara skillnaden mellan acceleration och hastighetsändring.
**InputType** text
**Hint** Tänk på begreppet "per tidsenhet".
**Hint** Acceleration beskriver hastighetsändring per sekund; hastighetsändring kan vara ett enda tal (Δv).
**Answer** Acceleration = hastighetsändring per tidsenhet; hastighetsändring (Δv) är skillnaden mellan slut- och starthastighet.
**MaxPoints** 3
**AnalyzeSubmission** Kontrollera om svaret säger att acceleration är "per tidsenhet" och att hastighetsändring är skillnaden mellan två hastigheter. Om båda delar nämns, "correct", annars "incorrect".
**WrongAnswer** De är samma sak **Why** Förvirring mellan själva förändringen och förändringens hastighet (tidselementet glömt).
**WrongAnswer** Acceleration är avstånd **Why** Blandar ihop begrepp avstånd/hastighet.

**Question** En bil saktar ner från 20 m/s till 5 m/s på 3 sekunder. Beräkna accelerationen (anta rak retardation).
**InputType** text
**Hint** a = (Δv)/Δt, Δv = v_final − v_start.
**Hint** Tänk på tecken: minskning av hastighet ger negativ acceleration om du använder samma riktning som positiv.
**Answer** -5 m/s^2
**Answer**  -5
**MaxPoints** 3
**AnalyzeSubmission** Acceptera "-5 m/s^2", "-5", eller "−5 m/s^2". Kontrollera beräkningen: Δv = 5 − 20 = −15, a = −15/3 = −5. Om detta stämmer, "correct", annars "incorrect".
**WrongAnswer** 5 m/s^2 **Why** Har ignorerat att hastigheten minskar (glömt negativt tecken).
**WrongAnswer** -0,75 m/s^2 **Why** Felaktig division, troligen 5/ (3*?) eller fel Δv.

**Question** I ett hastighet–tid-diagram visar en kurva en snabb, brant nedgång från 15 m/s till 0 m/s på 3 s, följt av en lång horisontell linje vid 0 m/s. Vilken tolkning är bäst?
**InputType** multiple choice
**Hint** Tänk vad lutningen betyder och vad en horisontell linje vid 0 visar.
**Hint** Tänk på vad som hände först och sedan.
**Answer** Första delen: kraftig retardation (stark inbromsning)
**Answer** Andra delen: vila/ingen rörelse
**MaxPoints** 2
**WrongAnswer** Konstant acceleration hela tiden **Why** Då skulle linjen vara rät och lutande hela tiden, inte horisontell vid 0.
**WrongAnswer** Konstant hastighet på 15 m/s **Why** Hastigheten sjunker till 0 i diagrammet.

**Question** Om en bils hastighet mäts i km/h! Hur konverterar du 72 km/h till m/s (avrunda till heltal)?
**InputType** text
**Hint** 1 km/h ≈ 0,2778 m/s. Alternativt dela med 3,6.
**Hint** 72 / 3,6 = ?
**Answer** 20 m/s
**MaxPoints** 2
**AnalyzeSubmission** Acceptera "20", "20 m/s" eller "≈20". Kontrollera division 72/3,6 = 20. Om korrekt, "correct", annars "incorrect".
**WrongAnswer** 200 m/s **Why** Felaktig multiplikation (gissningsvis multiplicerat istället för dividerat).
**WrongAnswer** 12 m/s **Why** Delat med fel tal eller använt fel omräkning.

**Question** En cykel accelererar från 3 m/s till 9 m/s under 2 s, sedan bromsar den till 6 m/s under 1 s. Vilken total förändring i hastighet skedde och vad är medelaccelerationen under hela tiden (3 s)?
**InputType** text
**Hint** Total Δv = slutv − startv. Medelacceleration = total Δv / total tid.
**Hint** Start = 3 m/s, slut efter allt = 6 m/s.
**Answer** Δv = 3 m/s; a_medel = 1 m/s^2
**MaxPoints** 3
**AnalyzeSubmission** Acceptera svar i formen "Δv = 3 m/s, a = 1 m/s^2" eller liknande. Kontrollera beräkning: slutv 6 − start 3 = 3; a_medel = 3/3 = 1. Om detta stämmer, "correct".
**WrongAnswer** Δv = 6 m/s **Why** Räknat som summan av steg i stället för slut minus start.
**WrongAnswer** a_medel = 0,5 m/s^2 **Why** Felaktig division (troligen använt fel total tid).

Svårighetsnivå 3 (Svår)

**Question** Förklara med egna ord varför acceleration kan vara negativ även om ett föremål rör sig framåt.
**InputType** text
**Hint** Tänk på riktning och förändring i hastighet.
**Hint** Negativ acceleration betyder att hastigheten minskar i den valda positiva riktningen.
**Answer** Negativ acceleration betyder att hastigheten minskar i den valda positiva riktningen; föremålet kan fortfarande röra sig framåt men sakta ner.
**MaxPoints** 3
**AnalyzeSubmission** Leta efter att eleven nämner: "minskning av hastighet", "vald positiv riktning" och att "föremålet fortfarande kan röra sig framåt". Om minst två av tre punkter finns, ge "correct", annars "incorrect".
**WrongAnswer** Negativ acceleration betyder att objektet rör sig bakåt **Why** Förväxlar riktningen på rörelsen med tecknet för accelerationen.

**Question** Ett objekt har hastighet v0 = 5 m/s och accelererar konstant med a = 2 m/s^2 i 4 s. Beräkna slutlig hastighet och sträcka som färdats under dessa 4 s.
**InputType** text
**Hint** v = v0 + a t. För sträcka använd s = v0 t + 0.5 a t^2.
**Hint** v0 = 5, a = 2, t = 4.
**Answer** v = 13 m/s
**Answer** s = 5*4 + 0,5*2*4^2 = 20 + 16 = 36 m
**MaxPoints** 4
**AnalyzeSubmission** Kontrollera två delar: slutlig hastighet = 13 m/s och sträcka = 36 m. Acceptera format som "v=13 m/s, s=36 m" eller separata rader. Om båda är korrekta, "correct", annars markera vilka som är felaktiga.
**WrongAnswer** v = 21 m/s **Why** Felaktig addition eller multiplicerat a*t som 2*8 etc.
**WrongAnswer** s = 52 m **Why** Använt fel formel (kanske v*t med slutlig hastighet) eller fel på halva a*t^2.

**Question** I ett hastighet–tid-diagram är det arean under kurvan som ger sträcka. Sant eller falskt?
**InputType** single choice
**Hint** Tänk på vad arean under hastighet–tid-kurvan representerar.
**Hint** Enhet: (m/s) * s = m.
**Answer** Sant
**MaxPoints** 1
**WrongAnswer** Falskt **Why** Missförståelse; arean under v–t-diagram visar faktiskt förflyttad sträcka.

**Question** Ett tåg går från stillastående till 20 m/s med konstant acceleration på 1 m/s^2. Hur lång tid tar uppaccelerationen och hur långt rullar tåget under denna tid?
**InputType** text
**Hint** Tid: t = (v − v0)/a. Sträcka: s = v0 t + 0.5 a t^2 eller med medelhastighet.
**Hint** v0 = 0, v = 20 m/s, a = 1 m/s^2.
**Answer** t = 20 s
**Answer** s = 0,5 * 1 * 20^2 = 200 m
**MaxPoints** 4
**AnalyzeSubmission** Acceptera "t=20 s, s=200 m" eller liknande. Kontrollera tidsberäkning 20 s och sträcka 200 m (medelhastighet 10 m/s * 20 s = 200 m). Om båda korrekta, "correct".
**WrongAnswer** t = 40 s **Why** Felaktig dubblering; troligen räknat fel på a.
**WrongAnswer** s = 400 m **Why** Använt slutlig hastighet * tid (20*20) utan att använda medelhastigheten eller korrekt formel.

**Question** Vilka av följande påverkar storleken på acceleration? (välj alla som gäller)
**InputType** multiple choice
**Hint** Fundera på formeln a = Δv/Δt.
**Hint** Tänk vad som ändrar Δv och Δt.
**Answer** Hur mycket hastigheten ändras (Δv)
**Answer** Hur lång tid förändringen tar (Δt)
**MaxPoints** 2
**WrongAnswer** Föremålets massa **Why** Massan påverkar kraften som krävs (F = ma) men inte själva accelerationen i formeln a = Δv/Δt.
**WrongAnswer** Färg på objektet **Why** Orelaterat egenskap.

--- End of assignments ---