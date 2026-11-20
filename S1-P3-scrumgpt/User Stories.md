# User Stories

## Wachtwoord reset

Door: Bart

Als gebruiker wil ik mijn wachtwoord kunnen terugzetten, zodat ik weer kan inloggen als ik het wachtwoord vergeten ben.

Prioriteit: **must** / should / could / won’t have

Acceptatiecriteria:

- Gebruikers kunnen hun emailadres invullen om een wachtwoord reset mailtje te ontvangen.
- In het mailtje kunnen ze op een link klikken om naar de wachtwoord reset pagina te gaan.
- Op de wachtwoord reset pagina kan de gebruiker een nieuw wachtwoord kiezen.
- De gebruiker kan hierna met het nieuwe wachtwoord inloggen.

## Ontmoeten: Random chat

Door: Bart

Als gebruiker wil ik andere gebruikers in een random chat ontmoeten, zodat ik nieuwe vrienden kan maken.

Prioriteit: must / **should** / could / won’t have

Acceptatiecriteria:

- Een andere gebruiker wordt willekeurig gekozen.
- Er wordt geen gebruiker gekozen met wie iemand al vrienden is.
- De chat kan ieder moment verlaten worden.
- Als ik de pagina herlaad, blijft de chat open.

## Ontmoeten: Open brief

Door: Bart

Als gebruiker wil ik een open brief kunnen schrijven, zodat ik ook contact kan maken als er niemand online is voor de random chat.

Prioriteit: must / **should** / could / won’t have

Acceptatiecriteria:

- Gebruikers moeten brieven kunnen schrijven.
- De brieven moeten zichtbaar zijn voor andere gebruikers.
- Andere gebruikers kunnen de brief beantwoorden door een chat te starten.

## Ontmoeten: Lobby

Door: Bart

Als gebruiker wil ik met andere gebruikers in de lobby gaan, zodat we samen een extern spelletje kunnen spelen.

Prioriteit: must / **should** / could / won’t have

Acceptatiecriteria:

- Gebruikers kunnen de lobby betreden.
- De gebruikers kunnen elkaar zien.
- Gebruikers kunnen een spel voorstellen om te spelen.
- Gebruikers kunnen een chat openen om elkaar te leren kennen.

## Ontmoeten: Poster

Door: Bart

Als gebruiker wil ik een poster met QR-code maken, zodat ik een fysieke manier heb om mensen naar mijn profiel te verwijzen.

Prioriteit: must / **should** / could / won’t have

Acceptatiecriteria:

- Gebruikers kunnen een kort bericht schrijven voor op hun poster.
- Gebruikers kunnen de poster als PDF downloaden op de kunnen printen.
- Anderen kunnen de QR-code scannen om op het profiel te komen en de gebruiker een bericht sturen.

## Feed Pagina

Door: Marvin

Als gebruiker  
wil ik een feed pagina kunnen bekijken met berichten van andere tribe leden,  
zodat ik op de hoogte ben van hun activiteiten.

Prioriteit: **must** / should / could / won’t have

Acceptatiecriteria:

- Gebruikers moeten geregistreerd zijn
- Gebruikers hebben elkaar als vriend toegevoegd
- De gebruiker kan berichten zien van andere tribe leden die berichten hebben toegevoegd.

## Security

Als gebruiker vind ik het eng dat mijn gegevens zichtbaar zijn.

ik wil dat mijn berichten en gegevens niet leesbaar zijn voor andere

zodat ik mijn privacy behoud en veilig voel

Prioriteit: **must** / should / could / won’t have

Acceptatiecriteria:

- end to end encription
- alleen inloggen via school mailadres
- encripted wachtwoorden
- 

## Beter leren kennen

Door: Bart

Als gebruiker wil ik mijn profiel deels kunnen afschermen, zodat ik anderen stapsgewijs beter kan leren kennen.

Prioriteit: must / should / **could** / won’t have

Acceptatiecriteria:

- Gebruikers kunnen kiezen welke delen van hun profiel zichtbaar zijn per vriend.
- Na een ontmoeting kunnen gebruikers kiezen om meer van hun profiel zichtbaar te maken.

## Volledig profiel zien

Door: Bart

Als gebruiker wil ik mijn contactgegevens delen met echte vrienden, zodat anderen buiten het platform contact met me kunnen opnemen.

Prioriteit: must / should / could / won’t have

Acceptatiecriteria:

- Als iemand zijn volledige profiel met een ander heeft gedeeld, krijgt de ander ook contactgegevens te zien.

## titel

beschrijving

Prioriteit: must / should / could / won’t have

Acceptatiecriteria:

- criterium

## titel

beschrijving

Prioriteit: must / should / could / won’t have

Acceptatiecriteria:

- criterium

## titel

beschrijving

Prioriteit: must / should / could / won’t have

Acceptatiecriteria:

- criterium

**__Harsha__**

**NAAM User Story: Anoniem Inloggen & Profiel**

**BESCHRIJVING:**  
*Als* eerstejaars student (zoals Kees)  
*wil ik* inloggen met mijn HU-schoolmail en een schuilnaam of roepnaam kiezen,  
*zodat* ik me veilig voel en anoniem gebruik kan maken van het platform zonder direct mijn volledige privé-identiteit prijs te geven.  
*Korte toelichting:* Biedt een lage drempel en borgt de 'safe space' en privacy-eisen.

**PRIORITEIT:** Must Have

**ACCEPTATIECRITERIA (wanneer is het af):**  
De gebruiker kan alleen inloggen met een geldig @student.hu.nl e-mailadres.

De gebruiker heeft het verplichte veld 'Roepnaam / Schuilnaam' ingevuld.

Na inloggen worden de gekozen schuilnaam en profiel-avatar op de header van het dashboard getoond.

De inlogstatus blijft behouden in de browser (via localStorage) na een pagina-refresh.

**KWALITEITSCRITERIA (wanneer is het goed volgens een professional):**  
Privacy & Dataminimalisatie: Voldoet aan de AVG-richtlijnen voor onderwijsinstellingen (*Open-ICT Privacy Protocol, 2025*).  
Toegankelijkheid: Formulier-velden zijn gelabeld conform WCAG 2.1 AA standaarden (*W3C, 2025*).

**NAAM User Story: Interesses Opslaan (Laag 1/2)**

**BESCHRIJVING:**  
*Als* tribe-lid  
*wil ik* minimaal 3 hobby- en interesse-tags (bijv. Gaming, Python, Bowlen) selecteren op mijn profiel,  
*zodat* de applicatie mij kan matchen met gelijkgestemde studenten op de 'tweede laag van de gespreks-ui'.  
*Korte toelichting:* Vormt de basis-dataset die nodig is om de matcher en filters te laten werken.

**PRIORITEIT:** Must Have

**ACCEPTATIECRITERIA (wanneer is het af):**

Er is een overzicht van minimaal 10 vooraf gedefinieerde interesse-tags waar de gebruiker uit kan klikken.

Geselecteerde tags veranderen visueel van kleur (active state).

De gekozen tags worden opgeslagen in de profiel-state.

Als de gebruiker minder dan 3 tags kiest, verschijnt er een duidelijke melding: *"Kies minimaal 3 interesses"*.

**KWALITEITSCRITERIA (wanneer is het goed volgens een professional):**

UI Feedback: Visuele statusveranderingen vinden plaats binnen 100ms na interactie (*Nielsen Norman Group, 2025*).

**NAAM User Story: Ijsbreker Kaart Trekken**

**BESCHRIJVING:**  
*Als* introverte student (Kees)  
*wil ik* met één druk op de knop een willekeurige vragenkaart trekken uit een categorie,  
*zodat* ik direct een betekenisvol gesprek/onderwerp heb om de ijsberg te breken met een medestudent.  
*Korte toelichting:* De kern-functionaliteit van de "Tribe Onion Matcher" om sociale angst en 'gespreks-drempels' weg te nemen.

**PRIORITEIT:** Must Have

**ACCEPTATIECRITERIA (wanneer is het af):**

De gebruiker kan een categorie kiezen (bijv. *Hobby's*, *Studie*, *Persoonlijke Lore*).

Het klikken op "Trek Ijsbreker" toont een nieuwe, willekeurige vraag uit een Array van vragen.

De vragenkaart heeft een werkende flip-animatie in de interface.

De getoonde vraag kan met één klik gekopieerd worden naar het klembord (*"Kopieer Vraag"*).

**KWALITEITSCRITERIA (wanneer is het goed volgens een professional):**

Randomisatie: De Math.random() logica zorgt ervoor dat dezelfde vraag niet twee keer achter elkaar verschijnt (*JavaScript Clean Code Rules, 2025*).

**NAAM User Story: Matcher Grid Filteren**

**BESCHRIJVING:**  
*Als* sociale verbinder (Nathalie)  
*wil ik* de lijst met tribe-leden kunnen filteren op specifieke interesse-tags en zoektermen,  
*zodat* ik snel studenten vind die dezelfde specifieke hobby of studie-behoefte delen.  
*Korte toelichting:* Biedt een overzichtelijke 'rich search' door de bio's en tags van medestudenten.

**PRIORITEIT:** Must Have

**ACCEPTATIECRITERIA (wanneer is het af):**  
Er is een werkend zoekveld en een reeks categorie-filterknoppen aanwezig.

Bij het typen in het zoekveld worden de profielkaarten in het grid real-time gefilterd.

Indien er geen matches zijn, verschijnt de tekst: *"Geen tribe-leden gevonden met deze interesse"*.

Het deactiveren van het filter toont direct weer alle profielen.

**KWALITEITSCRITERIA (wanneer is het goed volgens een professional):**  
Performance: De filtering van de DOM-elementen voert uit zonder merkbare vertraging (< 50ms) (*Google Lighthouse UX Metric, 2025*).

**NAAM User Story: Hangout Activiteit Aanmaken**

**BESCHRIJVING:**  
*Als* initiatiefrijke student  
*wil ik* een nieuwe informele hangout (bijv. koffie drinken, bowlen) op het prikbord kunnen plaatsen,  
*zodat* ik de hele tribe kan uitnodigen voor een offline ontmoeting.  
*Korte toelichting:* Waardevolle functionaliteit om de stap van online naar offline verbinding te maken.

**PRIORITEIT:** Must Have

**ACCEPTATIECRITERIA (wanneer is het af):**

Het formulier bevat verplichte velden: *Titel*, *Categorie*, *Locatie* en *Max. Deelnemers*.

Na verzenden wordt de nieuwe hangout als een nieuwe kaart bovenaan het prikbord geplaatst.

De organisator en de gekozen categorie-badge staan op de kaart afgebeeld.

**KWALITEITSCRITERIA (wanneer is het goed volgens een professional):**  
Input Validatie: Lege invoervelden worden rood gemarkeerd met een duidelijke foutmelding (*Usability.gov Form Guidelines, 2025*).

**NAAM User Story: Datumprikker Stemmen**

**BESCHRIJVING:**  
*Als* tribe-lid  
*wil ik* mijn beschikbaarheid kunnen aanvinken op voorgestelde datums van een hangout,  
*zodat* er snel een geschikte datum voor de groep gevonden wordt.  
*Korte toelichting:* Zorgt voor de interactieve datumprikker-functionaliteit binnen Concept 2.

**PRIORITEIT:** Must Have

**ACCEPTATIECRITERIA (wanneer is het af):**

De gebruiker kan per datumoptie de status 'Ja' of 'Nee' aanvinken.

De totale stemmenteller per datum past zich direct aan.

De datum met de meeste stemmen krijgt visueel het label *"Best Passend"*.

**KWALITEITSCRITERIA (wanneer is het goed volgens een professional):**  
State Consistency: De uitgebrachte stemmen blijven bewaard na het navigeren door de pagina's.

### **2.2 SHOULD HAVE User Stories**

**NAAM User Story: Mutual Consent Vrijgave**

**BESCHRIJVING:**  
*Als* privacy-bewuste student (Kees)  
*wil ik* dat mijn Discord/Teams contactgegevens pas zichtbaar worden als we *beide* een match-verzoek hebben geaccepteerd,  
*zodat* ik niet ongevraagd benaderd word en de controle houd over mijn netwerk.  
*Korte toelichting:* Borgt de gewenste 'mutual consent' privacy-laag.

**PRIORITEIT:** Should Have

**ACCEPTATIECRITERIA:** (Alleen verplicht voor Must Haves, optioneel bijgewerkt voor Should Haves)\[cite: 8\]

**KWALITEITSCRITERIA:** *Privacy by Design* standaarden\[cite: 8\].

**NAAM User Story: Coach Vibe-Check Input**

**BESCHRIJVING:**  
*Als* begeleidende coach (Sander)  
*wil ik* in één overzicht de geaggregeerde stemmingsuitslag van de tribe kunnen inzien\[cite: 8\],  
*zodat* ik tijdig zie hoe het met de groep gaat zonder individuele privacy te schenden.  
*Korte toelichting:* Biedt de coach een laagdrempelige 'temperatuurmeter'.

**PRIORITEIT:** Should Have\[cite: 8\]

**KWALITEITSCRITERIA:** Geaggregeerde dataweergave (geen individuele namen gekoppeld aan emoties)\[cite: 8\].

### **2.3 COULD HAVE & WON'T HAVE User Stories**

**NAAM User Story: Anonieme Q&A Vraag Stellen**

**BESCHRIJVING:**  
*Als* student met een inhoudelijke vraag  
*wil ik* anoniem een vraag op de tribe-muur kunnen posten\[cite: 8\],  
*zodat* ik hulp kan vragen bij vakken zonder bang te zijn om dom over te komen.

**PRIORITEIT:** Could Have\[cite: 8\]

**NAAM User Story: Discord Notification Link**

**BESCHRIJVING:**  
*Als* actieve Discord-gebruiker  
*wil ik* een automatische melding ontvangen in ons Discord-kanaal wanneer er een nieuwe hangout is gemaakt\[cite: 8\],  
*zodat* ik geen uitjes of koffiemomenten mis.

**PRIORITEIT:** Could Have\[cite: 8\]

**NAAM User Story: In-App Direct Chat**

**BESCHRIJVING:**  
*Als* student  
*wil ik* een volledige, ingebouwde chat-applicatie met spraakberichten in de webapp\[cite: 8\],  
*zodat* ik geen externe apps zoals Discord meer nodig heb.

**PRIORITEIT:** Won't Have (Out of scope voor de 2-weekse bouwsprint & Expo; we linken door naar Discord/Teams).

**NAAM User Story: AI Matching Algoritme**

**BESCHRIJVING:**  
*Als* student  
*wil ik* dat een kunstmatige intelligentie mijn gedrag analyseert en vrienden voorstelt\[cite: 8\],  
*zodat* ik zelf niet meer hoef te zoeken.

**PRIORITEIT:** Won't Have (Bewust afgekeurd: de doelgroep wil géén verslavend of complex algoritme).

#### 