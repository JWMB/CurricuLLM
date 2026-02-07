Svårighetsgrad 1 (lätt)
1)
Question: Vad är ett lutande plan?
InputType: text
Hint: Tänk på en ramp eller en rutschkana.
Hint: Beskriv hur ytan står i förhållande till horisontalplanet.
Answer: En yta som lutar i förhållande till horisontalplanet
MaxPoints: 2
AnalyzeSubmission: Kontrollera om svaret nämner att det är en yta/plan som är lutat jämfört med horisont (sök efter ord som "yta", "lut", "ramp", "sned", "i förhållande till horisont"). Om minst ett av dessa ord finns: "correct", annars "incorrect".
WrongAnswer: Ett horisontellt golv **Why** Ett horisontellt golv lutar inte.

2)
Question: I vilken riktning pekar tyngdkraften (tyngd) på ett föremål nära jordens yta?
InputType: single-choice
Hint: Tänk på vad som händer om du släpper något.
Hint: Mot jordens mitten.
Answer: Rakt nedåt mot jordens centrum
MaxPoints: 1
WrongAnswer: Rakt uppåt **Why** Förväxling med motkraft eller lufttryck.
WrongAnswer: I sidled **Why** Tyngdkraften verkar inte sidledes utan vertikalt nedåt.

3)
Question: Vilka krafter verkar på en låda som ligger stilla på ett lutande plan (lådan glider inte)?
InputType: multiple-choice
Hint: Tänk på tyngdkraft, tryck mot yta och friktion.
Hint: Tre vanliga krafter brukar nämnas.
Answer: Tyngdkraft (mg)
Answer: Normalkraft
Answer: Friktionskraft
MaxPoints: 3
WrongAnswer: Luftmotstånd **Why** Kan finnas men räknas normalt inte i grundläggande beskrivning av en stillastående låda.
WrongAnswer: Motorisk kraft **Why** Finns bara om något aktivt drar/lutar föremålet.

4)
Question: Förklara med egna ord vad centripetalkraft är.
InputType: text
Hint: Koppla till rörelse i cirkel.
Hint: Beskriv riktningen på kraften.
Answer: Kraft som håller ett föremål i cirkulär rörelse, riktad mot cirkelns centrum
MaxPoints: 2
AnalyzeSubmission: Kontrollera att svaret nämner både "cirkel/cirkulär rörelse" och att kraften är "mot centrum" eller liknande. Om båda nämns: "correct", om bara en av delarna nämns: "partial", annars "incorrect".
WrongAnswer: Kraft som skjuter utåt **Why** Förväxling med den upplevda centrifugalkänslan; verklig centripetalkraft är mot centrum.

5)
Question: Vad känns som om du trycks utåt i en karusell — hur kallas den känslan i vardagligt tal?
InputType: single-choice
Hint: Inte en verklig kraft i Newtons mening, utan en upplevelse i kroppen.
Hint: Samma ord används ofta i vardagsspråk.
Answer: Centrifugalkänsla
MaxPoints: 1
WrongAnswer: Centripetalkraft **Why** Centripetalkraften är riktad mot centrum; "centrifugalkänsla" beskriver den upplevda utåtverkande känslan.
WrongAnswer: Gravitation **Why** Gravitation är alltid nedåt, inte den utåtverkande känslan i cirkelrörelse.

6)
Question: Vad är rörelsemängd (impuls) och hur beräknas den i enklaste form?
InputType: text
Hint: Tänk på samband mellan massa och hastighet.
Hint: Använd symbolen p.
Answer: Rörelsemängd är massa gånger hastighet, p = m·v
MaxPoints: 2
AnalyzeSubmission: Kontrollera om svaret innehåller uttrycket "massa gånger hastighet" eller "p = m·v". Om ja: "correct", annars "incorrect".
WrongAnswer: Kraft gånger tid **Why** Detta blandas ihop med impulsändring, men grundläggande definition i mekanik är p = m·v.

Svårighetsgrad 2 (medel)
1)
Question: En låda med massa 2,0 kg glider på ett friktionsfritt lutande plan som lutar 30° mot horisontalen. Beräkna accelerationens storlek (använd g = 9,8 m/s²).
InputType: text
Hint: Komponent av tyngden parallellt med planet är mg·sin(θ).
Hint: Använd Newtons andra lag (F = m·a).
Answer: 4,9
MaxPoints: 3
AnalyzeSubmission: Kontrollera om svaret är numeriskt och nära 4,9 (tolerans ±0,1). Om inom tolerans: "correct", annars "incorrect".
WrongAnswer: 9,8 **Why** Har tagit hela tyngden istället för parallellkomponenten eller glömt sin(30°).
WrongAnswer: 2,45 **Why** Har delat felaktigt med 2 eller använt fel trigonometriskt värde.

2)
Question: Vilket uttryck beskriver komponenten av tyngdkraften som drar en låda nedför ett lutande plan med vinkel θ?
InputType: single-choice
Hint: Välj mellan sin och cos.
Hint: Kom ihåg att parallellkomponenten använder sin(θ).
Answer: mg·sin(θ)
MaxPoints: 1
WrongAnswer: mg·cos(θ) **Why** Cos ger normalkomponenten, inte den som drar nedför planet.
WrongAnswer: m·g·tan(θ) **Why** Tan används inte för komponent av kraft direkt.

3)
Question: Vilka faktorer påverkar storleken på centripetalkraften för ett föremål i cirkulär rörelse?
InputType: multiple-choice
Hint: Formeln är F = m·v²/r.
Hint: Alla tre storheter i formeln påverkar.
Answer: Massa
Answer: Hastighet
Answer: Radie
MaxPoints: 3
WrongAnswer: Tid (period) **Why** Perioden påverkar indirekt men är inte direkt med i F = m·v²/r (perioden kan användas för att hämta v).
WrongAnswer: Vinkelhastighet **Why** Vinkelhastighet kan användas i andra uttryck men var inte med i de givna alternativen (om det inte erbjuds som alternativ).

4)
Question: Två föremål kolliderar och fastnar ihop. Föremål 1 har massa 1,0 kg och hastighet 3,0 m/s åt höger. Föremål 2 har massa 2,0 kg och står stilla. Vilken hastighet får det hopklistrade föremålet efter kollisionen?
InputType: text
Hint: Använd rörelsemängdens bevarande (p_total före = p_total efter).
Hint: Totala massan efter är 3,0 kg.
Answer: 1,0
MaxPoints: 3
AnalyzeSubmission: Kontrollera om användaren beräknat p_total före = 1·3 + 2·0 = 3 kg·m/s och delat med totalmassa 3 kg för att få 1,0 m/s. Om numeriskt ~1,0 (±0,05): "correct", annars "incorrect".
WrongAnswer: 0,5 **Why** Har troligen räknat fel på delning eller använt felmassa.
WrongAnswer: 3,0 **Why** Har glömt att massan ökar när föremålen fastnar ihop.

5)
Question: I cirkelrörelse är accelerationen riktad ... ?
InputType: single-choice
Hint: Koppla till centripetalkraften.
Hint: Tänk på accelerationens riktning relativt cirkelns centrum.
Answer: Mot centrum
MaxPoints: 1
WrongAnswer: Utåt från centrum **Why** Förväxling med centrifugalkänslan.
WrongAnswer: Tangentiellt **Why** Tangentiell acceleration ändrar hastighetens storlek, men för konstant hastighet i cirkelrörelse är riktningen radial mot centrum.

Svårighetsgrad 3 (svår)
1)
Question: En vagn med massa 5,0 kg befinner sig på ett lutande plan med vinkel 25°. Friktionskoefficienten mellan vagn och plan är μ = 0,15. Beräkna vagnen acceleration nedför planet (använd g = 9,8 m/s²). Antag att vagnen faktiskt rör sig nedåt.
InputType: text
Hint: Summa krafter parallellt med planet är mg·sinθ − friktion. Friktionen = μ·N och N = mg·cosθ.
Hint: Skriv a = g(sinθ − μ·cosθ).
Answer: 2,81
MaxPoints: 4
AnalyzeSubmission: Förväntat värde ≈ 2,81 m/s². Acceptera svar inom ±0,05. Kontrollera även om eleven angett formel a = g(sinθ − μ·cosθ) eller numeriskt beräknat med sin25° ≈0,4226 och cos25° ≈0,9063. Om inom tolerans: "correct", annars "incorrect".
WrongAnswer: 0,00 **Why** Har glömt friktionen eller räknat så friktionen är lika med paralellkomponenten.
WrongAnswer: 9,8 **Why** Tagit hela tyngdaccelerationen istället för komponent eller gjort enhetsfel.

2)
Question: Två objekt rör sig mot varandra längs samma linje. Objekt A: massa 2,0 kg, hastighet 5,0 m/s åt höger. Objekt B: massa 3,0 kg, hastighet 2,0 m/s åt vänster. De stöter ihop och fastnar ihop. Bestäm slutlig hastighet och ange riktning.
InputType: text
Hint: Välj en riktning som positiv (t.ex. höger) och räkna p = m·v med tecken.
Hint: p_total = 2·5 + 3·(−2) = ?
Answer: 0,8 höger
MaxPoints: 4
AnalyzeSubmission: Förväntat p_total = 10 − 6 = 4 kg·m/s; totalmassa 5 kg; v = 4/5 = 0,8 m/s åt höger. Kontrollera om svaret anger numeriskt 0,8 m/s och riktning "höger" eller ekvivalent. Om korrekt: "correct", annars "incorrect".
WrongAnswer: 0,8 vänster **Why** Feltecken vid uppställning av hastigheter.
WrongAnswer: −0,8 **Why** Angivit negativ riktning men tolkningen kan vara omvänd; kontrollera teckenhantering.

3)
Question: Vilket uttryck beskriver normalkraften från ett horisontellt plan på ett föremål med massa m?
InputType: single-choice
Hint: Ingen lutning, ingen acceleration i vertikal led (om föremålet vilar).
Hint: Tänk på att normalkraft balanserar tyngden.
Answer: N = m·g
MaxPoints: 1
WrongAnswer: N = m·g·cos(θ) **Why** Det fungerar för lutande plan; här är θ = 0 så det blir m·g, men alternativet kan vara förvirrande.
WrongAnswer: N = 0 **Why** Felaktigt om föremålet vilar på planet.

4)
Question: Om hastigheten i en cirkelbana dubblas (v → 2v) men radien är oförändrad, vad händer med centripetalkraften och perioden?
InputType: multiple-choice
Hint: F = m·v²/r och T = 2πr/v.
Hint: Tänk hur v² och v påverkar storheter.
Answer: Centripetalkraften blir fyra gånger större
Answer: Perioden halveras
MaxPoints: 2
WrongAnswer: Centripetalkraften blir dubbelt så stor **Why** Många antar linjär ökning istället för kvadratisk.
WrongAnswer: Perioden blir kvar lika stor **Why** Missförstånd om samband mellan hastighet och period.

5)
Question: Ange tre skillnader mellan centripetalkraft (fysikalisk kraft) och centrifugalkänsla (upplevd kraft) i egna ord.
InputType: text
Hint: En är "verklig" och en är "inbillad/fiktiv" i ett roterande referenssystem.
Hint: Tänk på riktning, orsak och i vilket referenssystem de beskrivs.
Answer: Centripetalkraft är en verklig kraft riktad mot centrum; centrifugalkänsla är en fiktiv upplevelse utåt i ett roterande referenssystem; centrifugalkänslan uppstår när man betraktar rörelsen från ett roterande perspektiv
MaxPoints: 4
AnalyzeSubmission: Kontrollera att svaret innehåller minst två av följande punkter: (1) centripetalkraft är riktad mot centrum / fysisk kraft, (2) centrifugalkänsla är utåt / fiktiv i roterande referenssystem, (3) orsak respektive upplevelse/perspektiv. Om tre nämns: "correct", om två: "partial", annars "incorrect".
WrongAnswer: De är samma sak **Why** Förväxling mellan verklig krafter och upplevda krafter i roterande referenssystem.