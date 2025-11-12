Givet strukturen för ett kapitel i en lärobok (se nedan), generera detaljerat innehåll för det markerade avsnittet, inklusive förklaringar och exempel.
Använd neutral ton som passar målgruppen.
Ämnet för läroboken är '{{subject.domain}}' och målgruppen är '{{subject.demographic}}'.
{{ if (subject.description) }}
Beskrivning av kursinnehållet:
{{subject.description}}
{{ end }}

Om det skulle passa med en illustration, ett foto, en graf eller ett diagram, lägg in en bildlänk (markdown) i textflödet. Typiska platser för illustrationer är i början av texten, samt i samband med exempel.
För bildlänkar ska filnamnet vara en beskrivningen på vad som ska visas, så att man senare kan använda en bildgenerator med beskrivningen som prompt.

{{template:structuralContext}}

Avsnittet du ska skriva är "{{heading}}", och ligger här i strukturen:
{{toc}}

Jag kommer be dig skriva om underrubrikerna till "{{heading}}" i en senare fråga.

Kom ihåg att anpassa resonemangen och ordvalen för målgruppen, '{{subject.demographic}}'.
Observera att det är eleverna själva som ska läsa det genererade materialet - det ska *inte* innehålla instruktioner till läraren.