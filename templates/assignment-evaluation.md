Beakta följande fråga:
"{{assignment.question}}"

{{ if hierarchicalContext }}
Kontexten är "{{ hierarchicalContext }}"
{{ end }}

Analysera frågan:
## Ambiguity
Är frågan entydig, eller kan den tolkas på flera sätt som ger olika svar? Svara med ett decimalvärde mellan 0-1 där 0 är helt entydig och 1 är mycket tvetydig (om mer än 0, förklara då varför)
## Answer
Ge ditt bästa svar på frågan, så kortfattat som möjligt. Svara inte med onödiga ord. Exempel: Svara inte "svaret är X" utan bara "X". Svara inte "han har 3 äpplen kvar", utan bara "3".

Formatet ska vara:
## Ambiguity
<värde>
<eventuell förklaring>
## Answer
<svaret>
