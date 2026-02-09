# Project Vektor 2.0 / LibreLearn / FreeFormation

*Formation wants to be free*

A generic system for training cognitive skills, performing spaced repetition of facts, work on curriculum exercises and more.
The primary target group consists of individuals or groups (such as school students), with administrators such as parents or teachers configuring trainings and reviewing results.
The subsystems are open source, and the project aims to encourage teachers or researchers to implement their own tests, games and training paradigms.

While the first application might be limited in scope (similar to the Vektor app), the system supports a wide range of data and can be used as the basis for a generic training and testing system, allowing schools and researchers to gain knowledge on the effects of different interventions.

Future additions that would help
* Integrated Jupyter Notebooks for collaborative analysis and visualization of datasets
* A test suite spanning over many cognitive domains

## Author

The project is being developed by Jonas Beckeman, co-founder of Cogmed Working Memory Training and lead developer of the training app Vektor from Cognition Matters foundation, in cooperation with professor Torkel Klingberg.

### CV

Jonas has produced learning and training software since 1992, when he co-authored one of Sweden's first e-learning CD-ROMs, "Multimedia Stål", which aimed to create a larger interest in metallurgy engineering degrees.
Later, he worked as tech lead on Levande Böcker titles such as Mulle Meck, and co-founded the game studio Monsterland which created the learning games Rymdjakten and Djuphavsjakten.

In 2000, he teamed up with researchers Torkel Klingberg and Helena Westerberg to create the working memory training product "RoboMemo", and subsequently co-founded the company Cogmed. After moving to the US to increase Cogmed's presence in the American markets, the company was sold to Pearson Education in 2010, where he worked until 2014. Hundreds of independent studies were made with the applications, including at Karolinska Institutet, Duke University, New York University and Jonas worked with many of the teams to suggest and make modifications to better serve their needs.

After leaving Cogmed/Pearson, part of the original Cogmed team joined forces again to start Cognition Matters foundation, a non-profit with the goal of creating the free math training app Vektor for young students. The app became very popular, primarily in Sweden and South America, but lost funding around 2020 and disappeared from the app stores.

From 2018, he worked as a consultant for Telia on their helpdesk products, primarily on a knowledgebase / chatbot solution. After the release of GPT 3.5, he pioneered Telia's work on GenAI chatbots, creating their first publicly available system (https://techtidningen.se/kontaktcenter-generativ-ai-till-telia-ace-plattformen/).

Jonas has also worked on multiple shorter projects as a freelance developer, including creating a math E-Learning proof-of-concept system for Natur och Kultur in 2009, and again as an AI/LLM implementation expert in 2024.

### Other
Over the years, Jonas has become disillusioned with profit-making companies in general, and especially with the EdTech sector, which routinely skips the important validation/research steps in order to push their products. He firmly believes that there are many talented people willing to communally improve eductional technology, some with development/programmer skills, some with pedagogical or subject expertise, or both.

Jonas is generally critical of technology implementations in schools, as most interventions have little to no solid research showing that they have better-than-negative effects. He also thinks that the frivolous use of US-based services is violating citizens' privacy, creates dangerous dependencies on foreign entities, and ultimately threatens the sovereignty of Sweden.

## Related work and research
Both Cogmed and Vektor have efficacy proven through multiple studies, with published articles in Nature Neuroscience, Nature Human Behaviour, JAMA Pediatrics, Developmental Science and others.

### Cogmed
When the link between working memory and ADHD symptoms was demonstrated in the late 1990's, Torkel Klingberg decided to evaluate whether training working memory could affect the ability to concentrate. In 2000, he contacted the game studio Monsterland AB, which had produced games he and his family had enjoyed, to create a proof-of-concept application for use in a small research study.

The study showed promising results, and after a second successful study, the company Cogmed AB was founded in 2003 with seeding from Karolinska Development AB, and the initial RoboMemo product was launched.
The company originally employed a large staff of CBT psychologists who guided children through the training process. However, while establishing an office in Chicago, IL in 2007, the strategy pivoted to selling trainings through licensed psychologist clinics.
Around the same time, a new product line was launched, based on new technology. Cogmed RM replaced RoboMemo, with the new Cogmed JM and QM targeting younger children and adults respectively.

In 2009, Cogmed had established a global network of clinics providing its products, spanning all contintents. Seed investors were keen on an exit, and in 2010 the company was sold to Pearson Education. A new web-based version was put into production around that time.

[...]

Working memory training products.
Original product: RoboMemo
Research overview: https://download.cogmed.com/research_summary

#### Journal of Political Economy - The Impact of Working Memory Training on Children's Cognitive and Noncognitive Skills (Cogmed)
* Link: https://www.ifo.de/en/publications/2025/contribution-refereed-journal/impact-working-memory-training-childrens-cognitive

#### Developmental Science - Adaptive training leads to sustained enhancement of poor working memory in children
* Link: https://onlinelibrary.wiley.com/doi/10.1111/j.1467-7687.2009.00848.x

#### Neurotherapeutics - Will working memory training generalize to improve off-task behavior in children with attention-deficit/hyperactivity disorder? 
* Link: https://www.neurotherapeuticsjournal.org/article/S1878-7479(23)01737-3/fulltext

### Vektor
After witnessing the impact of Cogmed working memory training on one of their children, the parents wanted to see if basic math and numeracy could be trained in a similar fashion.
Together with founders of Cogmed, they started a non-profit foundation, Cognition Matters.

#### Journal of Educational Psychology - Short and long-term effects of a mathematics tablet intervention for low performing second graders
* Link: https://psycnet.apa.org/doiLanding?doi=10.1037%2Fedu0000264
*[...] adaptive math training on tablet can help low performing 8-year-olds catch up about half a year of schooling in critical math skills. Students with lower IQ benefitted in particular and made long-term gains 12 months after training finished*

#### PsyArXiv - Digital, Mathematical and Cognitive Training: Evidence from a Randomized Trial (Preprint)
* Link: PsyArXiv - https://osf.io/preprints/psyarxiv/24ej7_v1
*The results suggest that this intervention is a feasible and effective way of enhancing the mathematical and cognitive abilities of children in rural areas*

#### Cognitive Development - Working memory capacity, variability, and response to intervention at age 6 and its association to inattention and mathematics age 9
* Link: https://www.sciencedirect.com/science/article/pii/S0885201421000083
*results showed improved prediction for mathematics from WM training improvement and variability*

#### Nature Human Behaviour - Training spatial cognition enhances mathematical learning in a randomized study of 17,000 children
* Link: https://www.nature.com/articles/s41562-021-01118-4
*This large, community-based study shows that spatial cognitive training can result in transfer to academic abilities, and that reasoning ability and maintenance of spatial information is relevant for mathematics learning in young children.*

#### Nature Human Behaviour - Training spatial cognition enhances mathematical learning in a randomized study of 17,000 children
* Link: https://www.nature.com/articles/s41562-021-01118-4
* Abstract: Spatial and mathematical abilities are strongly associated. Here, we analysed data from 17,648 children, aged 6–8 years, who performed 7 weeks of mathematical training together with randomly assigned spatial cognitive training with tasks demanding more spatial manipulation (mental rotation or tangram), maintenance of spatial information (a visuospatial working memory task) or spatial, non-verbal reasoning. We found that the type of cognitive training children performed had a significant impact on mathematical learning, with training of visuospatial working memory and reasoning being the most effective. This large, community-based study shows that spatial cognitive training can result in transfer to academic abilities, and that reasoning ability and maintenance of spatial information is relevant for mathematics learning in young children.

#### Frontiers in Human Neuroscience - Resting State EEG Related to Mathematical Improvement After Spatial Training in Children
* Link: https://www.frontiersin.org/journals/human-neuroscience/articles/10.3389/fnhum.2021.698367/full

#### Cognitive Development - Working memory capacity, variability, and response to intervention at age 6 and its association to inattention and mathematics age 9
* Link: https://www.sciencedirect.com/science/article/pii/S0885201421000083

## Terminology
* Trainee - an end user who uses the system to train
* Training - an account with configuration that the trainee logs into when using the system
* Game - a combination of assignment/task generators, level management and other configurations that are used to produce stimuli and analyze responses
* Training plan - part of the configuration that includes game definitions, system instructions for deciding when they should be available, conditions for unlocking rewards etc
* Administrator - a parent or teacher who configures the training and reviews the results

## Subsystems
The system is comprised of three main subsystems: Admin server, Training Logic server, and client apps

### Admin server
This system is up and running since 2023, used in a research version of the previous Vektor app.

* Front-end
    * Administrators set up training accounts (individual accounts or groups) and change training configurations
    * Administrators or trainees can inspect their training results
* Back-end
    * User authentication (future: integrate with e.g. school IdPs)
    * Collection of training results and data aggregation
    * AI-assisted training result analysis for presentation to administrators, including automatic adjustments of training configurations

### Training Logic Server
Work on this system started in 2025. The system can be used in its current state, but not all components are fully implemented.

* Based on the training configuration and training plan, the service decides which games to make available
* Fetches training settings and previous results from the Admin server, and sends back data generated by the trainee.
* The game configuration specifies which components to instantiate. Components can include
    * Stimuli generator
    * Response analyzer
    * Level (difficulty) manager
* Training plan types are also components, which provides extensibility to the logic that governs the training flow
* Component implementations can be added to the service as code, or be configured as relays to external REST APIs for easier prototyping
* Examples of implementations:
    * Working memory exercises
    * Non-verbal reasoning exercises
    * Arithmetic exercises on a number line
    * Fractions and factorization exercise
    * Generic Q'n'A exercise that fetches questions (including images/sounds) and answers from external sources (that the administrator can specify) - supports multiple response types such as free text, single-choice, multiple-choice, sorting, item matching

### Client app
Currently two client app implementations exist: A re-implementation of Vektor, the beloved training app provided free by the Cognition Matters foundation, and an experimental chat-style client (not well-suited for games with more complex UI, e.g. number line, but excellent for Q'n'A-style games).

* The client app is presentation layer that communicates with the Training Logic Server for most logic
* A TypeScript library exists for easier implementation of games
* While some might want to create a new client from scratch, we will provide a reference implementation that is easy to modify.

## Licensing
The source code will have a copy-left license. Commerical use is not allowed by default.
Possibly, parts of the system will have a dual license, allowing commercial use for a fee.

## Authentication
By default, the system should handle as little PII as possible.

If a school uses an identity system where users have roles (student, teacher, parent, headmaster) and users can be associated as classes etc, we can use a SCIM-like system to provision accounts and permissions using anomymous IDs rather than email addresses, names, class names etc. Authentication can be solved with a SSO setup (where only the anonymous ID is provided as a claim). Note that the teacher view will then not be able to show student or class names. This can be partly solved by randomizing names and using symbols to represent these. Alternative solutions is integrating with a school's generic reporting system, where class views with names can be resolved - or that names are stored in the teacher's browser rather than on the servers.

If no such systems exist, local email-based server accounts or 3rd-party IdPs can be used.
Since trainees are often young, a simpler authentication system may be used, using a mnemo-like code that represents username and password together with an URL component representing the class/teacher.

## Deployment
The subsystems will be available for self-hosting on request for entities that are highly concerned about data sovereignty, and where full anonymization is not possible.
For the furthering of the project, it is better if users connect to the same servers:
* Updates are made centrally and are not dependend on local IT personnel
* Developers can better identify bug root causes using server logs
* Generated training data is valuable for evaluating new training paradigms or subgroup performance

For self-hosted deployments, there should be a clause requiring some type of data transfer to the project so researchers can include those data points in studies. The type of data might be subject to negotiation depending on the entity.

## Modifications and research
The availability of granular data is important for researchers in order to create robust statistical models for evaluating the effect sizes of different applications, configurations, training paradigms or reliability of tests.
If data is completely anonymized, there should be few obstacles to share data with researchers. However, in some study designs, PII may be critical - e.g. when comparing performance by gender or birth month.

This can be handled by parental consent forms, granting access to a combination of accessing entities and data types. This PII can then either be stored in a central system - or, if all PII resides with e.g. a school, the school grants access to the party to fetch the requested data for joining with the available training data.

Modifications to different parts of the system will be encouraged, such as custom or modified client apps, new game types, training plan or level adjustment algorithms, IRT / ML item selection, repetition spacing algorithms etc.
Training data this needs to be clearly marked with which components (and versions of components) are used.


## External resources
### Vektor images
![Vektor, Numberline](https://www.specialnest.se/sites/default/files/styles/articles_breakpoints_theme_specialnest_wide_1x/public/article/images/vektor_skarmdump.jpg?itok=DhS-taco&timestamp=1559641663)  
![Vektor, Story](https://s5.pappasappar.se/wp-content/uploads/vektor-bakgrundshistoria-768x576.jpg)  
![Vektor, Character menu](https://s9.pappasappar.se/wp-content/uploads/vektor-karaktar-768x576.jpg)  
![Vektor, N-Pals](https://s5.pappasappar.se/wp-content/uploads/vektor-taluppfattning-768x576.jpg)  
![Vektor, Numberline decimals](https://s9.pappasappar.se/wp-content/uploads/vektor-subtraktion-decimaltal-768x576.jpg)  

### Cogmed images
![Cogmed JM, Main menu](https://images.squarespace-cdn.com/content/v1/57fec909be65948159717a21/1476821828964-W12BKHDDRJM836Y1O64K/Screenshot+%28223%29.png?format=1500w)  
![Cogmed RM, Main menu](https://images.squarespace-cdn.com/content/v1/57fec909be65948159717a21/1476822042659-YN95LOCK9AJL05FHCMWJ/Screenshot+%28225%29.png?format=1500w)  
![Cogmed RM, Asteroids](https://images.squarespace-cdn.com/content/v1/57fec909be65948159717a21/1476821775524-U7JFD7B7Z163TXBGYZOE/Screenshot+%28226%29.png?format=1500w)  
![Cogmed JM, Rollecoaster](https://images.squarespace-cdn.com/content/v1/57fec909be65948159717a21/1476822014386-FET0RRLF2PD5XQRSQCI2/Screenshot+%28224%29.png?format=2500w)  
