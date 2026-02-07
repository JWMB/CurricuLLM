Enkel mätning av ström och spänning

Introduktion
- När vi bygger enkla elektriska kretsar vill vi ofta veta hur mycket ström som går genom kretsen och hur stor spänningen är över en komponent. Att kunna mäta ström och spänning hjälper oss förstå hur kretsen fungerar och om något är fel.
- De vanligaste instrumenten är en multimeter (som kan mäta både spänning och ström) eller separata mätare: voltmeter (för spänning) och amperemeter/ammeter (för ström).

![multimeter som visar mätningar av spänning och ström](multimeter_visar_matning_av_spanning_och_strom.png)

Vad betyder ström och spänning?
- Spänning (V, volt) är det som "trycker" på elektriska laddningar och får dem att röra sig i en krets. Tänk på spänning som trycket i ett vattenrör.
- Ström (I, ampere eller A) är hur många elektriska laddningar som passerar en punkt per sekund. Tänk på ström som hur mycket vatten som flyter genom röret.
- Vanliga enheter: 1 A = 1 ampere. Mindre strömmar anges ofta i milliampere (mA), där 1 A = 1000 mA.

Vilken instrumentkoppling används?
- Voltmeter: alltid parallellt med den del du vill mäta spänningen över. Den ska inte bryta kretsen, utan mäta över samma två punkter.
- Ammeter: alltid i serie med kretsen, så all ström som går i kretsen också går genom mätaren.

Illustration: ammeter i serie och voltmeter i parallell
![schema_ammeter_serie_voltmeter_parallell_batteri_resistor.png](inkoppling_av_ammeter_i_serie_och_voltmetern_i_parallell.png)

Praktiskt med en multimeter
- Välj rätt mätartyp: ställ vredet på DC-spänning (V DC) för batterier (lika ström). För ström, välj DC-ström (A eller mA) om det är en likströmkrets.
- Börja med högre mätområde om du är osäker. Om skärmen visar "1" eller "OL" kan det betyda att du är utanför området.
- För spänningsmätning: koppla multimeterns röda kabel till den punkt som är mest positiv och svarta till den andra punkten. Om du byter leder kan avläsningen bli negativ (ingen fara — bara byta plats på siffrans tecken).
- För strömmätning: du måste öppna kretsen och koppla in multimetern i serie. Många multimeterkontakter har en särskild jack för hög ström (10A) och en för mA/µA — använd rätt kontakt.

Viktiga säkerhetsråd
- Mät aldrig vägguttag (230 V) eller apparater som är kopplade till nätspänning med enkla skolkretsar. Dessa kan vara farliga.
- Undvik kortslutning (att koppla plus och minus direkt utan motstånd) — det kan ge stor ström och skada batterier eller mätare.
- Om multimetern är säkrad (fuse) så kolla att säkringen är hel om mätaren inte visar ström.

Exempel 1 — Mäta spänningen på ett batteri
- Material: 1 batteri 9 V, multimeter.
- Steg:
  1. Ställ multimetern på V DC (t.ex. 20 V-område om det finns val).
  2. Koppla den röda mätsonden till batteriets pluspol och den svarta till minuspol.
  3. Läs av värdet. Ett nytt batteri kan visa något över 9, t.ex. 9,2 V. Ett svagt batteri kan visa under 9 V.
- Tolkning: Spänningen utan belastning visar batteriets nominella spänning, men under belastning (när något är kopplat) kan spänningen sjunka något.

Exempel 2 — Mäta ström i en enkel krets (batteri och resistans)
- Material: 1 batteri 9 V, resistor 100 Ω (eller en liten glödlampa), multimeter.
- Teori (Ohms lag): I = V / R.
  - Om R = 100 Ω och V = 9 V, då I = 9 / 100 = 0,09 A = 90 mA.
- Hur mäta (enkel steg-för-steg):
  1. Koppla först kretsen utan multimeter: batteri → resistor → tillbaka till batteriet (kretsen är sluten).
  2. Stäng av eller bryt strömmen (ta bort en ledning).
  3. Ställ multimetern på lämpligt strömläge (0,2 A eller 200 mA om sådana val finns). Sätt sondkablarna i rätt jack (röd i mA-jacket om du förväntar dig mA).
  4. Anslut multimetern i den öppna delen av kretsen så att strömmen måste passera genom multimetern: batteriets plus → multimeter → resistor → tillbaka till batteri.
  5. Läs av strömmen. Den bör vara nära 90 mA (0,09 A) om resistorn är precis 100 Ω.
- Om mätvärdet är mycket mindre eller noll: kontrollera kopplingar, batteriet, eller att multimetern är rätt inställd.

Bild som visar mätning av ström med multimeter i serie
![multimeter_inkopplad_i_serie_for_strommatning_batteri_resistor.png](multimeter_inkopplad_i_serie_for_strommatning_batteri_resistor.png)

Exempel 3 — Mäta spänning över en komponent i samma krets
- Med samma krets (9 V batteri och 100 Ω resistor):
  1. Ställ multimetern på V DC.
  2. För att mäta spänningen över resistorn sätter du multimeterns prober i parallell över resistorn (en probe i vardera ände).
  3. Avläsningen visar hur stor del av batteriets spänning som ligger över resistorn. I detta fall bör det vara nära 9 V eftersom hela spänningen går över motståndet när vi bara har ett motstånd i kretsen.

Tips och vanliga fel
- Om du försöker mäta ström utan att öppna kretsen riskerar du kortslutning — mät alltid ström i serie.
- Om voltmätaren ger negativt värde har du vänt sonderna åt fel håll. Byt plats på dem eller notera att värdet bara är negativt.
- Mätområde: om displayen visar "OL" eller blankt vid mätning, välj högre mätområde.
- En voltmeter har hög inre resistans för att inte påverka kretsen. En ammeter har låg inre resistans för att inte begränsa strömmen.

Övningar att prova
1) En krets har ett 4,5 V-batteri och en lampa som drar 45 mA. Vilken resistans motsvarar detta? (Svar: R = V/I = 4,5 V / 0,045 A = 100 Ω)
2) Du mäter en spänning över ett batteri och får 1,2 V. Är batteriet troligtvis ett zink-kol 1,5 V-batteri eller ett annat? Vad kan det betyda? (Svar: Troligtvis urladdat eller svagt, eftersom normalt 1,5 V är nominellt.)
3) Om multimetern visar 0,12 A när den är inkopplad i serie med en resistor och batteri 9 V, vilken är resistansen? (Svar: R = 9 V / 0,12 A = 75 Ω)

Sammanfattning
- Spänning mäts med voltmeter/parallellt; ström mäts med ammeter/serie.
- Använd multimeter rätt: välj DC, rätt mätområde och rätt jack för ström.
- Var försiktig: kortslut inte batterier och mät inte nätström. Kontrollera alltid kopplingar om värdet verkar fel.

Mer att utforska
- Mät hur spänningen över en lampa förändras när du byter motstånd eller batteri.
- Jämför spänningen över flera komponenter i serie och parallell för att se hur den fördelas.