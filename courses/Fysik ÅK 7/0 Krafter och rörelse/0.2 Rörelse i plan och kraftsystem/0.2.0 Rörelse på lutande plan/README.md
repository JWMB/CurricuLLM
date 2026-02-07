Rörelse på lutande plan

När ett föremål rör sig på ett lutande plan (till exempel en låda på en ramp eller en pulka i en backe) spelar flera krafter roll. Här förklarar vi vilka krafter det är, hur man kan räkna ut vad som händer, och visar några exempel.

![Block på lutande plan med krafter: tyngdkraft, normalkraft och friktion](block_pa_lutande_plan_krafter.png)

Vad händer med tyngdkraften?
- Tyngdkraften (mg) drar alltid rakt nedåt mot jordens centrum.
- När ett föremål står på ett lutande plan kan man dela upp tyngdkraften i två delar:
  - En komponent rakt in i planet (perpendicular): mg cosθ. Denna balanseras av normalkraften N.
  - En komponent längs planet (parallel): mg sinθ. Denna vill få föremålet att glida nedför planet.
- θ (theta) är lutningsvinkeln mellan planet och horisontalplanet.

Krafter som påverkar rörelsen längs planet
- Normalkraft N: trycket från planet, riktad vinkelrätt ut från ytan. N = mg cosθ (om inget annat trycker på).
- Friktionskraft f: motverkar rörelse längs planet. Riktningsberoende — om föremålet försöker glida nedåt så pekar friktionen uppåt längs planet.
  - Statisk friktion (hindrar att det börjar röra sig) kan vara upp till f_s,max = μ_s N.
  - Kinetisk (glid) friktion när det rör sig: f_k = μ_k N.
- Resultantkraften längs planet bestämmer om och hur snabbt föremålet accelererar: F_net = mg sinθ - f.

Enkel formel för acceleration (utan komplicerad växling)
- Om det inte finns friktion (eller om friktionen är mycket liten) blir accelerationen nedför planet:
  a = g sinθ
  där g ≈ 9,82 m/s^2.
- Om det finns glidfriktion med koefficient μ_k:
  a = g (sinθ - μ_k cosθ)
  (Här har massan m tagits bort eftersom den finns i både tyngdkraften och friktionen.)

När stannar föremålet eller börjar glida?
- Föremålet rör sig bara om den nedåtgående komponenten mg sinθ är större än vad statisk friktion kan motstå: mg sinθ > μ_s N = μ_s mg cosθ.
- Det betyder att det börjar glida om tanθ > μ_s, eller om vinkeln θ > arctan(μ_s).
- Exempel: Om μ_s = 0,4 så börjar föremålet glida när θ ≈ arctan(0,4) ≈ 21,8°.

Exempel 1 — inget friktionsmotstånd
- Problem: En låda med massan 2,0 kg står på en ramp lutande 30°. Antag att friktionen är försumbar. Bestäm accelerationen.
- Lösning:
  1. a = g sinθ.
  2. sin30° = 0,5 så a = 9,82 × 0,5 ≈ 4,91 m/s^2.
- Svar: Accelerationen nedför rampen är ungefär 4,9 m/s^2.

![Exempel: låda på 30-graders ramp beräkning](rakneexempel_block_30grader.png)

Exempel 2 — med friktion
- Problem: Samma låda (2,0 kg) på samma ramp (30°), men nu är friktionskoefficienten μ_k = 0,20. Bestäm accelerationen.
- Lösning:
  1. Normalkraft: N = mg cosθ, men vi behöver i praktiken bara cos30° ≈ 0,866.
  2. Friktionskraft: f = μ_k N = μ_k mg cosθ.
  3. Nettokraft nedåt längs planet: F = mg sinθ - f = mg(sinθ - μ_k cosθ).
  4. Acceleration: a = F / m = g (sinθ - μ_k cosθ).
  5. Sätt in värden: a = 9,82 × (0,5 - 0,20 × 0,866) ≈ 9,82 × (0,5 - 0,1732) ≈ 9,82 × 0,3268 ≈ 3,21 m/s^2.
- Svar: Accelerationen är ungefär 3,2 m/s^2.

Exempel 3 — när ligger jämvikt?
- Problem: En tung kartong står stilla på en ramp. Friktionen är sådan att μ_s = 0,35. Vilken minsta lutning krävs för att kartongen ska börja glida?
- Lösning:
  1. Jämför tanθ med μ_s. Start av glid när tanθ > μ_s.
  2. θ_min = arctan(μ_s) = arctan(0,35) ≈ 19,3°.
- Svar: Om rampen lutar mer än cirka 19° börjar kartongen glida.

Praktiska tips (om du vill undersöka själv)
- Du kan testa med en leksaksbil eller bok på en ramp. Mät rampens lutning och tiden bilen tar att åka en viss sträcka. Om bilen startar från vila kan du använda s = 0,5 a t^2 för att räkna fram a och jämföra med formeln a = g sinθ (när friktionen är liten).
- Var försiktig med tunga föremål så att inga skador sker, och lämna experimentiella instruktioner till läraren om det behövs.

Varför är det viktigt?
- Lutande plan hjälper oss förstå hur krafter fungerar i vardagliga situationer — från cykling nedför en backe till transporter på ramper. Att kunna dela upp krafter i komponenter (längs och vinkelrätt mot planet) gör många beräkningar enklare och visar hur tyngdkraft, normalkraft och friktion samverkar.

Ytterligare illustration (valfritt att titta på)
![Mätning av tid och sträcka för att bestämma acceleration på en ramp](experiment_ramp_tid_stracka.png)