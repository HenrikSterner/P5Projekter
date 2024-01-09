# Et lidt større projekt i programmering
### Af Henrik Sterner (hst@nextkbh.dk)

## Indledning
Nærværende dokument udgør en beskrivelse af et større projekt, hvor I skal vælge et af nedenstående temaer og udvikle et koncept/en ide, som I skal implementere. Som udgangspunkt vælger I selv sproget I vil lave det i. 

I er velkomne til at arbejde i grupper af 2 til 4 personer eller individuelt. Til eksamensprojektet må I dog kun være 2 til 3 personer. 

Ved afslutningen af projektet skal I 

- aflevere en rapport og koden for programmet
- lave en lille fremlæggelse på 10 min pr grupper om projektet og hvad I har lavet. 

## Krav til programmet
Programmet bør inddrage nogle af de strukturer, som vi har arbejdet med i undervisningen. Herunder

1. Variabler:
2. Betingelser
3. Løkker
4. Funktioner
5. Arrays/lister



## Struktur for rapporten
Udover programmet skal I også skrive en rapport på 3-5 sider pr gruppe (max 3, hvis I er alene, max 4 hvis I er to og max 5 hvis I er mere end 2), kaldet en synopsis, der dokumenterer jeres arbejde og brug af de forskellige strukturerer. 

Rapporten kan fokusere på følgende: 
- en beskrivelse af jeres program, 
- en beskrivelse af jeres arbejde med programmet. 

Brug gerne pseudokode og flowcharts til at beskrive jeres program. Husk at tænke formidlingsaspektet ind. Den bedste måde at formidle kode på, er ikke nødvendigvis at formidle på kodeniveau.

Herunder et forslag til en struktur for rapporten. I kan vælge at følge den eller lave jeres egen:

1. Forside
2. Kort abstract (censor kan herved orientere sig om opgavens indhold)
3. Problemformulering
4. Funktionsbeskrivelse (skærmlayout, indtastningsmuligheder, funktionalitet – alt efter hvad det er for et program)
5. Dokumentation af selve programmet (overordnet beskrivelse af programmet, detaljeret dokumentation af dele af programmet (flowchart, pseudokode), variabler, objekter, events, igen meget afhængigt af hvad det er for et program)
6. Test af programmet
7. Konklusion
8. Bilag (det er godt at få koden placeret i bilag, da den muligvis ikke ville kunne indeholdes indenfor de angivne sider).

## Valg af temaer
I kan vælge et af nedenstående temaer. 

### Tema 1: Spil
Lav en prototype på et spil. Det kan være et brætspil, som I digitaliserer. I må gerne lave et spil, som I selv har fundet på. Det kan også være et spil, som eksisterer allerede, men som I så videreudvikler på.

Spillet bør rumme muligheden for enten at spille mod en anden spiller eller mod computeren.

### Tema 2: Formidling af en faglig problemstilling i et andet fag

Lav et program, som har til formål at formidle en faglig problemstilling eller aspekt fra et andet fag. 

Det kan eksempelvis være:

* Simulering og visualisering af et eksperiment i fysik/kemi eller biologi hvor man kan justere på forskellige parametre. 
* Modellering og beregning af noget i matematik. F.eks. regression eller finde nulpunkter for funktioner. 
* En samfundsfaglig problemstilling 
* Et bog eller et digt i dansk

Krav: Der skal gerne være en grafisk brugergrænseflade. 

### Tema 3: Simpel Chatbot
I det følgende tema skal I prøve at implementere en simpel chatbot. 

Et eksempel på en sådan er Eliza Chatbot. 
Herunder en kort introduktion til Eliza Chatbot (hentet fra wikipedia):
ELIZA er et tidligt computerprogram til behandling af naturligt sprog udviklet mellem 1964 og 1966 på MIT Artificial Intelligence Laboratory af Joseph Weizenbaum.[1] Programmet blev skabt til at demostrere det overfladiske i kommunikationen mellem menneske og maskine, idet ELIZA simulerede en samtale ved brug af mønstergenkendelse og metodisk substitution, som gav brugeren en oplevelse af at blive forstået af maskinen, til trods for at programmet ikke havde nogen forståelsesramme for miljø og hændelser.[2] ELISA var en af de første chatbots, men blev også anset for at være et af de første programmer med mulighed for at bestå Turing-testen.
I sin enkleste form virker ELIZA på følgende måde:[3]
1.	En prioriteret liste med nøgleord anvendes overfor brugerens indtastede sætning. Nøgleordet med højest prioritet, som findes i brugerens sætning, anvendes. Eksempler på nøgleord kunne være:
2.	"can you" (kan du) → svar 1-3 anvendes
3.	"can I" (kan jeg) → svar 4-5 anvendes
4.	"you are" (du er) → svar 6-9 anvendes
5.	...
6.	(ikke fundet) → svar 106-112 anvendes
7.	Nøgleordet har ledt til et sæt af svar; et af disse vælges tilfældigt. Fx kan svarene til "can you" (kan du) være:
8.	"Don't you believe that I can<*" (Tror du ikke jeg kan ...?)
9.	"Perhaps you would like to be able to<*" (Du vil måske gerne være i stand til at ...?)
10.	"You want me to be able to<*" (Du vil gerne, om jeg kan ...?)
11.	Svaret gøres komplet, ved at den del af brugerens sætning, som kommer efter nøgleordet, indsættes i svaret. I eksemplerne ovenfor erstattes "<*" af den del af brugerens sætning, som kommer efter nøgleordet.
12.	Svaret vendes, således at 1. person (jeg, mig) erstattes af 2. person (du, dig) og modsat. (På engelsk kan denne udskiftning også omfatte verbet, som bøjes efter stedordet; I am, you are.)

Udover selve chatbotten må I også meget gerne lave en simpel brugergrænseflade.



### Tema 4: Et selvvalgt projekt
Hvis I har en god ide, som I gerne vil forsøge at implementere, så kom og snak, så finder vi ud af det :-).