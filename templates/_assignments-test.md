Givet strukturen för en lärobok nedan, generera ett antal uppgifter för eleven att lösa.
Uppgifterna måste inte ha ekvationer eller numeriska tal som svar, det kan också röra sig om fritextsvar, t.ex. resonerande svar på logiska problem.

Skapa sektioner, en för varje svårighetsgrad 1-3, där 1 är lätt och 3 är svårt för målgruppen.
Övningarna ska bestå av
* Question: Fråga / problemformulering
* Type: Frågetyp, antingen "text" (användaren svarar med fritext), eller "alternatives" (användaren svarar genom att välja bland alternativ - för dessa ska du skapa fler felaktiga alternativ än antalet korrekta alternativ)
* Hint: ett eller flera tips på hur problemet kan lösas. Om du kommer på mer än ett tips, ska de ordnas efter hur hjälpsamma de är, men de minst hjälpsamma tipsen först
* Answer: ett eller flera korrekta möjliga svar. Håll svaret så kort som möjligt och undvik onödiga ord, t.ex. om frågan är "A har 2 äpplen och ger bort 1, hur många har han kvar?" så ska svaret inte vara "två äpplen" utan bara "2".
* MaxPoints: max antal poäng man kan få på frågan
* AnalyzeSubmission: Skapa en prompt med vilken användarens svar kan analyseras för att bedöma riktigheten. Behövs ej när Type = alternatives
* WrongAnswer: fundera på vilka felaktiga svar som kan vara vanliga, och förklara vilka fel som kan ha lett till det felaktiga svaret.

Skapa 5 till 10 uppgifter för varje svårighetsgrad. Ungefär en tredjedel kan vara frågor med fritextsvar.

Exempel på Type="text" (fritextfråga):
**Question** Vilken är Illinois huvudstad?
**Type** text
**Hint** Tänk på TV-serien Simpsons
**Hint** Namnet är vårlikt
**Answer** Springfield
**MaxPoints** 1
**AnalyzeSubmission** Om användarens svar är det rätta svaret fast felstavat, svara "korrekt", annars "inkorrekt"
**WrongAnswer** Chicago **Why** Det är den största staden, men inte huvudstaden

**Question** Varför inleddes Korstågen?
**Type** text
**Hint** Religiösa, politiska och ekonomiska motiv
**Hint** Heliga städer, Seljuk, handelsrutter
**Answer** Religiöst: återta heliga platser, syndernas förlåtelse, skydda pilgrimmer. Politiskt: minska interna Europeiska konflikter, öka kungars herravälde, öka påvens herravälde, hjälpa Byzantiska riket mot Seljuk-turkar. Ekonomiskt: ta land och resurser, behärska handelsrutter, skapa nya hertigdömen 
**MaxPoints** 10
**AnalyzeSubmission** Lista de teman som ingår härefter som användaren fått med i sitt svar: "Religiöst: återta heliga platser, syndernas förlåtelse, skydda pilgrimmer. Politiskt: minska interna Europeiska konflikter, öka kungars herravälde, öka påvens herravälde, hjälpa Byzantiska riket mot Seljuk-turkar. Ekonomiskt: ta land och resurser, behärska handelsrutter, skapa nya hertigdömen". Lista separat felaktiga orsaker så de kan räknas som minuspoäng
**WrongAnswer** Gud uppmanade månniskorna att göra det **Why** Gud finns inte

Exempel på Type="alternatives" (single eller multiple choice):
**Question** Vilken är statsmaktens grenar i USA?
**Type** alternatives
**Hint** De är tre
**Hint** lagstiftande, utförande och lagförande
**Answer** Legislativa
**Answer** Exekutiva
**Answer** Judiciella
**MaxPoints** 3
**WrongAnswer** Spekulära **Why** Ett hittepå-begrepp
**WrongAnswer** Polisiära **Why** Det skulle kunna ses som en del av den judiciella grenen
**WrongAnswer** Populära **Why** Någon sådan gren finns inte


Avsnittet du ska skriva frågor för är "{{heading}}", och ligger här i strukturen:
{{toc}}
