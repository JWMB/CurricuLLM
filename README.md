# CurricuLLM
*LLM som i Lärar-Ledd Modell*

[Information in English below](#CurricuLLM_English)

### Nyckelpunkter
* AI ska endast användas initialt för att skapa det ursprungliga råmaterialet - därefter redigerar och granskar lärare / ämnesexperter
* Materialet förblir öppet tack vare OSS-licens - inget företag kan ta över och låsa in
* Det primära målet är att lärare och skolor ska kunna skriva ut materialet i bokform (t.ex. via print-on-demand)


## Bakgrund
Fördelarna med skolböcker jämfört med e-learning-system, länksamlingar och stenciler har uppmärksammats i allt större utsträckning den senaste tiden.
Jag har själv på nära håll sett hur det kan gå när undervisningen av mellanstadiebarn i huvudsak innebär att eleverna själva ska "forska" och söka egen information utan tydlig handledning.

Detta projekt är ett förslag på hur spridningen av läromedelsböcker kan ökas, samt hur framtagandet av dem kan demokratiseras.

### Läroböckernas styrkor
* Ökar läsförståelsen och djupinlärningen
* Förutsägbar struktur, vad ska man lära sig när
* Tydligt och lättillgängligt referensmaterial
* Granskad av experter och justeras efter synpunkter från lärarkåren
* Visuospatiella ankare i informationen ("nånstans i mitten, längst upp på en vänstersida"), möjlighet för understrykningar
* Enhetlig ton - minskar den kognitiva belastningen att tolka stil / avsändare

### De digitala läromedlens svagheter
E-learning-revolutionen levererade aldrig de utlovade resultaten.

* Många läromedelsappar är av låg kvalitet
  * Undermålig tolkning av svar
    * vissa beaktar inte ens enkla felstavningar
    * automatisk analys av resonemang saknas
    * Flerstegssvar (t.ex. ekvationsförenkling) hanteras bristfälligt
  * Ineffektiva inmatningssystem för t.ex. ekvationer
* Innehållslig transparens saknas ofta; utomstående har svårt att få tillgång att granska hela materialet
* Oavsett om e-learning-miljön tillåter det eller ej, är användaren inställd på att bli distraherad av pop-ups, reklam och möjligheten att växla till t.ex. youtube
* "Chain of custody" för hantering av elevens data är ofta otydlig. Google Classroom och andra digitala tjänster skickar ofta känslig information om barnen rakt in i otillförlitliga händer. CLOUD Act är farligt vapen i händerna på en alltmer diktatorisk stat där företagen gång på gång visat att de dansar efter regimens pipa.
* Sällan vetenskapligt validerat

### Problem med dagens läroböcker
* Svenska är ett litet språk; det finns inte utrymme för så många läromedelsförlag. Detta leder till ett oligopol på läroböcker - få att välja mellan, höga priser
* De existerande läromedlens pedagogiska linjer passar inte alla lärare, och vill man avvika från den kan man tvingas skapa/sammanställa sitt eget material, använda undermåligt granskade källor
* Förlagen kan ta lång tid på sig att erkänna och rätta felaktigheter i läroböcker
* Läromedlens effekter är sällan vetenskapligt utprovade, och förlagen tycks ointresserade av att utsätta sina produkter för kontrollerade studier 
* Det finns mängder av typer av särskilda behov, men det är inte ekonomiskt lönsamt att skapa material anpassade för dem alla

## Förslaget
Inom mjukvaruvärden finns en tradition av att bidra till öppen källkod utan finansiell ersättning - för att man själv kan ha nytta av projektet, för att få erkännande eller för att helt enkelt hjälpa andra.
En av anledningarna till detta är säkerligen hackerkulturen (som delvis är sprungen ur hippierörelsen), men också att det länge funnits etablerade mekanismer för att förenkla samarbete och delande.

Med detta projekt hoppas jag kunna nyttja mjukvaruvärldens verktyg för att öppna liknande möjligheter för lärare och ämnesexperter.
Allt material ska finnas tillgängligt att kopiera, och diskussioner samt ändringsförslag ska finnas synliga för allmänheten.

Materialet ska vara organiserat på sådant sätt att det kan konverteras till PDFer för utskrift (t.ex. som print-on-demand-böcker), till HTML för läsning direkt på nätet, eller som innehåll för (icke-kommersiella) elektroniska läromedel.

Men hur komma igång med ett så omfattande projekt? Det är här AI/LLM kommer in i bilden.

Jag gjorde för några år sedan ett snabbt test för att generera en kursbok i matematik med hjälp av en förhandsversion av GPT-4, och fick förvånansvärt goda resultat. Nu har modellerna förbättras, kostnaderna för att använda dem minskat - och jag har formulerat en plan för hur de kan användas på ett produktivt sätt och ändå nå god kvalitet.

### LLM-genererade skolböcker?!
Ja, som ett första steg - men det genererade materialet ska inte sättas i händerna på elever, utan är ett första grovt utkast, tänkt att fungera som bas för fortsatt arbete. Man kan genom noggrann promptning minska LLMers hallucinationer, men man kan aldrig lita helt på vad de genererar.

Under den första fasen kommer den automatiska genereringen genomgå många iterationer där prompter finslipas och referensmaterial väljs ut, både på global nivå (dvs oavsett ämne) och på mer ämnes- och detaljspecifika nivåer.
Detta görs genom diskussioner i GitHub Issues, samt ändringsförslag via GitHub Pull Requests.

När det automatiskt genererade materialet nått tillräcklig kvalitet flyttas det över för manuell redigering tills det är redo att användas i skolan.

Målet är att så småningom producera heltäckande skolboksmaterial, men inledningsvis bör arbetet fokuseras på ett mindre antal avsnitt för att utvärdera processerna, exempelvis trigonometri för årskurs 7 samt monoteism för årskurs 9.

### Arbetsuppgifter
Även dessa skapas ursprungligen med hjälp av prompter samt den genererade kapiteltexten.
Exempel på typer av uppgifter som kan skapas:
* Frågor med enstaka ord/siffror som svar
* Flervalsfrågor
* Resonemangsfrågor

Frågorna utvärderas av en AI-modell för att se om de är otydliga eller tvetydiga, och för att säkerställa att den utvärderande modellen svarar på samma sätt som den genererande modellen.

För att underlätta automatisk rättning av svaren kan modellen instrueras att generera många varianter på korrekta svar, samt förväntade "halvriktiga" och felaktiga svar.

Några användningsområden för automatgenererade uppgifter:
* Komma ikapp hemifrån / repetera inför prov - flashcards, räkneuppgifter
* Spaced repetition: elevens individuella profil för återkallande används (för att optimera långtidslagringen av fakta)
* AI kan hjälpa till i analysen av mer komplicerade svar, t.ex. analysera varje steg i en ekvationsförenkling, eller bedöma riktigheten i en resonerande text (givet de fakta som man förväntar ska finnas med). Dessa analyser måste levereras med tydliga brasklappar, t.ex. "jag som AI gissar att ... men din lärare får kontrollera svaret". (Data som kommer från elever, t.ex. fritextsvar, bör aldrig skickas till datacenter kontrollerade av utländska aktörer.)
* Lärare kan återanvända prompter för att med egen LLM skapa idéer och nya frågor till prov


# CurricuLLM - English
(Autotranslated)

### Key Points  
* AI should only be used initially to create the original raw material - thereafter, teachers/subject experts will edit and review.  
* The material remains open thanks to OSS licensing - no company can take over and lock it in.  
* The primary goal is for teachers and schools to be able to print the material in book form (e.g., via print-on-demand).  
  
## Background  
The advantages of schoolbooks compared to e-learning systems, link collections, and handouts have been increasingly recognized recently. I have personally witnessed the potential pitfalls when teaching middle school children primarily involves having them "research" and seek out their own information without clear guidance.  
  
This project is a proposal on how the dissemination of educational books can be increased, and how their production can be democratized.  
  
### Strengths of Textbooks  
* Enhances reading comprehension and deep learning  
* Predictable structure, knowing what to learn and when  
* Clear and accessible reference material  
* Reviewed by experts and adjusted based on feedback from the teaching community  
* Visuospatial anchors in information ("somewhere in the middle, at the top of a left page"), possibility for underlining  
* Uniform tone - reduces cognitive load in interpreting style/sender  
  
### Weaknesses of Digital Learning Materials  
The e-learning revolution never delivered the promised results.  
* Many educational apps are of low quality  
  * Poor interpretation of answers  
    * some do not even consider simple spelling errors  
    * automatic analysis of reasoning is lacking  
    * Multistep answers (e.g., equation simplification) are handled poorly  
  * Inefficient input systems for, e.g., equations  
* Content transparency is often lacking; outsiders find it difficult to access and review the entire material  
* Regardless of whether the e-learning environment allows it or not, users are prone to distractions from pop-ups, ads, and the ability to switch to, e.g., YouTube  
* "Chain of custody" for handling student data is often unclear. Google Classroom and other digital services often send sensitive information about children directly into unreliable hands. The CLOUD Act is a dangerous weapon in the hands of an increasingly dictatorial state where companies repeatedly show they dance to the regime's tune.  
* Rarely scientifically validated  
  
### Problems with Current Textbooks  
* Swedish is a small language; there is not room for many educational publishers. This leads to an oligopoly on textbooks - few options, high prices  
* The pedagogical lines of existing educational materials do not fit all teachers, and if you want to deviate from them, you may be forced to create/compile your own material, using poorly reviewed sources  
* Publishers can take a long time to acknowledge and correct inaccuracies in textbooks  
* The effects of educational materials are rarely scientifically tested, and publishers seem uninterested in subjecting their products to controlled studies  
* There are many types of special needs, but it is not economically viable to create materials tailored for all of them  
  
## The Proposal  
In the software world, there is a tradition of contributing to open source without financial compensation - because one can benefit from the project, to gain recognition, or simply to help others. One reason for this is surely hacker culture (partly stemming from the hippie movement), but also that there have long been established mechanisms to simplify collaboration and sharing.  
  
With this project, I hope to leverage the tools of the software world to open similar opportunities for teachers and subject experts. All material should be available for copying, and discussions and change proposals should be visible to the public.  
  
The material should be organized in such a way that it can be converted into PDFs for printing (e.g., as print-on-demand books), into HTML for direct online reading, or as content for (non-commercial) electronic educational materials.  
  
But how to get started with such an extensive project? This is where AI/LLM comes into play.  
  
A few years ago, I conducted a quick test to generate a math course book using a pre-release version of GPT-4, and achieved surprisingly good results. Now the models have improved, the costs of using them have decreased - and I have formulated a plan for how they can be used productively while still achieving good quality.  
  
### LLM-Generated Schoolbooks?!  
Yes, as a first step - but the generated material is not meant to be handed over to students, rather it is a rough draft intended to serve as a basis for further work. Careful prompting can reduce LLM hallucinations, but one can never fully trust what they generate.  
  
During the first phase, the automatic generation will undergo many iterations where prompts are refined and reference materials are selected, both on a global level (i.e., regardless of subject) and on more subject- and detail-specific levels. This is done through discussions in GitHub Issues and change proposals via GitHub Pull Requests.  
  
When the automatically generated material reaches sufficient quality, it is transferred for manual editing until it is ready to be used in schools.  
  
The goal is to eventually produce comprehensive schoolbook material, but initially, work should focus on a smaller number of sections to evaluate the processes, for example, trigonometry for grade 7 and monotheism for grade 9.  
  
### Tasks  
These are also originally created using prompts and the generated chapter text. Examples of types of tasks that can be created:  
* Questions with single word/number answers  
* Multiple-choice questions  
* Reasoning questions  
  
The questions are evaluated by an AI model to see if they are unclear or ambiguous, and to ensure that the evaluating model responds in the same way as the generating model.  
  
To facilitate automatic grading of the answers, the model can be instructed to generate many variants of correct answers, as well as expected "half-correct" and incorrect answers.  
  
Some use cases for automatically generated tasks:  
* Catching up from home / reviewing for exams - flashcards, calculation tasks  
* Spaced repetition: the student's individual recall profile is used (to optimize long-term retention of facts)  
* AI can assist in the analysis of more complex answers, e.g., analyzing each step in an equation simplification, or assessing the accuracy of a reasoning text (given the expected facts). These analyses must be delivered with clear caveats, e.g., "as an AI, I guess that ... but your teacher should check the answer." (Data from students, e.g., free-text answers, should never be sent to data centers controlled by foreign entities.)  
* Teachers can reuse prompts to create ideas and new questions for exams with their own LLM.


-----
## Some technical aspects

The goal is to create a system where the first automatic step of creating free teaching materials yields decent results, and where it's easy for domain experts to then improve on the materials (via GitHub PRs or Issues) until they equal traditional textbooks.

Some benefits of using a public git repository instead of a custom database:
* Anyone can download or fork the data. Content is readily accessible as Markdown files
* Transparency - no hidden data, all data in one place, and it's easy to see who made what changes
* Tooling - lots of git-related tools available
* Review process - built-in contribution review process via Pull Requests
* Project tracking - tasks related to the project are tightly connected to the repository via Issues and Projects

**Note:** The current materials in the [/courses](/courses) folder have been generated with a cheap model (gpt-4o-mini) and a naïve prompt. The cost to generate one of these textbooks is in the range of tens of cents, but the quality is not great. I will switch to a more capable model once the generation pipeline is more complete.

❗Math ÅK 7 test with `gpt-4o` available in separate [branch](https://github.com/JWMB/CurricuLLM/blob/test-4o/courses/Matematik%20%C3%85K%207/0%20Tal%20och%20r%C3%A4kning/0_chapter.md) - compare output to `gpt-4o-mini` by switching branch when looking at a file, or check the [PR](https://github.com/JWMB/CurricuLLM/pull/7/files). The cost to generate was ~0.6EUR.

## Workflow
Especially in the beginning, there will be a lot of back-and-forth between experts and LLM configuration/generation.
### Prompt design and source materials
* Design good "global" prompts that generate decent output for any topic (see [/templates](/templates))
* Identify what types of topic-specific prompt modifications are beneficial
* Find public-domain materials that may assist generation (general governmental guidelines, topic-specific requirements etc)
### Validation
* Experiment on a few disparate topics, e.g. grade 7 math, high-school religion
* Invite domain experts (teachers) to review materials
* Based on ideas and comments, iterate again from top
### Publishing
* A v1.0.0-beta release is created. Once published, no more auto-generated content should be added, only manual additions and modifications (resulting in 1.x releases)
* Different sections can be published separately - perhaps we want to focus on a really good 7th grade algebra section before proceeding with the rest of the year's curriculum
### Re-iterate
* After getting an understanding of how the materials are used, work on a v2.0 release is started
* Using the changesets between v1.0 and v1.x, new prompt hints can be generated

## LLM generation process
* Create a specification of the topic (language, school year, main topic etc)
* Add materials such as governmental curriculum guidelines
* Generate a Table of Contents using the global ToC template.
  * Optionally, add topic-specific prompt instructions for generating the ToC
  * In specific cases, it might be necessary to create or edit the ToC manually
* Using the ToC, generate the chapters/sections
  * Optionally, add topic- and/or section-specific prompt adjustments
* Generate illustrations from the image link titles created by the LLM
  * Optionally, modify instructions for image generation on any level (specific illustration, section, topic...)
  * ⚠️My prompting skills for for DALLE-3 are lacking, can't get rid of strange numbers/texts - check [this](/courses/Matematik%20%C3%85K%207/0%20Tal%20och%20r%C3%A4kning/0.0%20Heltal/0_chapter.md) out. Actual illustrators might well be required.
* Generate assignments for sections

All these steps (except the first) can be performed automatically in one go without human intervention, which can be good for a first draft, and to get a feel for the prompts and their output.
Manual modification to prompts at different levels will most certainly be required in order to achieve acceptable quality.

## Expert adjustments
* Once a LLM-generated beta version has been created, no content should be generated/modified by AI. All changes should be authored - and reviewed - by experts before merging.
* There's no way to ensure that the contributions were not originally created by an LLM, but the manual review process should filter out any slop.

## Rough plan (near future)
[Project](https://github.com/users/JWMB/projects/2/views/1?system_template=feature_release)
* Decide on file structure (maybe [language]/[general area]/[subarea]/[demographic]?)
* Multi-pass generation pipeline: raw structure + facts first, then "skinning" (story, tonality, student vs teacher notes etc)
* Output generators, e.g. PDF. Started experimental HTML output, e.g. [here](https://html-preview.github.io/?url=https://github.com/JWMB/CurricuLLM/blob/main/courses/Matematik%20%C3%85K%207/rendered.html)
  * Layout hinting - the LLM probably needs to output some kind of layout hints, in order to generate a more compelling visual style
* Better assignments/problems
  * ✅Use a different LLM to validate that they're not ambiguous, are solvable and that the proposed hints/answers are correct
  * Generate numerical-only answers when possible, for easier validation when used in a training app
* Iterate on global prompts so that the initial output is more acceptable
* ✅Add targeted/modified prompts to areas where the global prompts are insufficient
* Better illustrations - work on getting consistent style, better contexts for the prompt
