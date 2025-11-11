Given the structure of a textbook for the demographic "Mellanstadiet i Svenska grundskolan" (see below), generate a number of assignments/questions/problems for the student to solve.
An assignments can be of 3 different types:
* text: the student answers in free text
* single choice: the student chooses one of several alternatives
* multiple choice: the student chooses one or more of several alternatives

The assignments should consist of

* Question: Question/problem formulation
* InputType: User input type (text, single-choice or multiple-choice)
* Hint: one or more tips on how to solve the problem. If you come up with more than one hint, they should be arranged according to how helpful they are, with the least helpful hints first. One entry per hint.
* Answer: one or more correct possible answers. Keep the answer as short as possible and avoid unnecessary words, e.g. if the question is “A has 2 apples and gives away 1, how many does he have left?”, the answer should not be “two apples” but just “2”. One entry per answer.
* MaxPoints: maximum number of points that can be earned on the question
* AnalyzeSubmission: Create a prompt with which the user's answer can be analyzed to assess its accuracy. Not needed when Type = alternatives
* WrongAnswer: think about what incorrect answers might be common, and explain what mistakes might have led to the incorrect answer. One entry per incorrect answer.

Adhere to the structure given in the below examples.

Examples of Type=text (free text question):
**Question** What is the capital of Illinois?
**InputType** text
**Hint** Think of the TV series The Simpsons.
**Hint** The name is spring-like.
**Answer** Springfield
**MaxPoints** 1
**AnalyzeSubmission** If the user's answer is the correct answer but misspelled, respond “correct,” otherwise “incorrect.”
**WrongAnswer** Chicago **Why** It is the largest city, but not the capital.

**Question** Why were the Crusades launched?
**InputType** text
**Hint** Religious, political, and economic motives
**Hint** Holy cities, Seljuk, trade routes
**Answer** Religious: recapture holy sites, forgiveness of sins, protect pilgrims. Political: reduce internal European conflicts, increase the power of kings, increase the power of the Pope, help the Byzantine Empire against the Seljuk Turks. Economic: seize land and resources, control trade routes, create new duchies. 
**MaxPoints** 10
**AnalyzeSubmission** List of themes included in the user's answer: "Religious: recapture holy sites, forgiveness of sins, protect pilgrims. Politically: reduce internal European conflicts, increase the power of kings, increase the power of the Pope, help the Byzantine Empire against the Seljuk Turks. Economically: take land and resources, control trade routes, create new duchies." List incorrect reasons separately so they can be counted as minus points
**WrongAnswer** God urged people to do it **Why** God does not exist

Example of Type=multiple choice:
**Question** What are the branches of government in the United States?
**InputType** multiple choice
**Hint** There are three
**Hint** legislative, executive, and judicial
**Answer** Legislative
**Answer** Executive
**Answer** Judicial
**MaxPoints** 3
**WrongAnswer** Speculative **Why** A made-up concept
**WrongAnswer** Police **Why** It could be seen as part of the judicial branch
**WrongAnswer** Popular **Why** There is no such branch


The section you are to write questions for is “Grundläggande principer för kritiskt tänkande”, and is located here in the structure:
# Kritiskt tänkande
## ----> Grundläggande principer för kritiskt tänkande
### Analysera argument
### Fråga och undersök
# Logiska felslut
# Källkritik
# Vetenskaplig förståelse

Create sections, one for each difficulty level 1-3, where 1 is easy and 3 is difficult for the target group "Mellanstadiet i Svenska grundskolan". Create 5 to 10 questions for each difficulty level. About one-third can be questions with InputType=text, the rest should be single-choice or multiple-choice.
Remember to provide alternatives (correct / incorrect answers) on separate lines just like the examples above.
Do not forget to include the **InputType** row for each assignment. 

Once you have created the assignments, translate your output into Swedish.
