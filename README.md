# Vos Pro

Toetsvolgsysteem voor docenten: scores per vraag invoeren (ook met meerdere versies en N voor
"niet gemaakt"), cijfers met een normering naar keuze, RTTI, en statistiek per vraag (p-waarde, RIT, RIR).
Toetsen en resultaten deel je met collega's via een `.vospro.json`-bestand.

Alles draait op je eigen laptop, in je browser. Er gaan **geen leerlinggegevens het internet op**:
de database staat alleen op dit apparaat (`%LOCALAPPDATA%\VosPro`). Het programma kijkt alleen
of er een nieuwe versie is (één klein bestand van deze pagina).

# Features
Vos Pro biedt een overzichtelijke omgeving voor het beheren van toetsen, invoeren van behaalde punten, berekenen van cijfers, toetsanalyses en vergelijkingen met andere klassen/schooljaren. Vos Pro draait in de browser vanaf een programma dat op de computer draait en slaat data lokaal op, met de mogelijkheid om data op te slaan in de door de school aangeboden cloud dienst.

## Welkomscherm en overzicht
<img width="1338" height="1260" alt="Dashboard" src="https://github.com/user-attachments/assets/50878fca-0ed0-4ec0-b98c-8133979ece2e" />
Het welkomsscherm laat zien hoeveel toetsen nog in afwachting zijn van een beoordeling, hoe ver recente afnames nagekeken zijn en stelt de docent in staat om direct een nieuwe afname te plannen, een toets aan te maken of naar het klassenoverzicht te gaan. Via recente afnames is het mogelijk om van een recente afname de scores in te voeren.

Via de menu balk is snel te navigeren naar andere onderdelen van Vos Pro, het geselecteerde schooljaar te veranderen, de tekst groter/kleiner te maken, de instellingen aan te passen en Vos Pro af te sluiten.

## Klassenoverzicht en leerlingbeheer
<img width="1338" height="1260" alt="Klassenoverzicht" src="https://github.com/user-attachments/assets/4b8d3356-4566-41d0-bd38-9ae0bb30a21e" />
Vos Pro ondersteunt het importeren van een .xlsx bestand vanuit magister om zodoende onderbouw klassen te importeren met hun klasnaam. Clusters werken ook maar dienen onder een aparte naam geimporteerd te worden en kunnen slechts per cluster geimporteerd worden. Gedurende het jaar is het mogelijk om leerlingen uit klassen te verwijderen of klassen zelf te verwijderen. Handmatige invoer werkt uiteraard ook.

## Toetsen
<img width="1338" height="1260" alt="Overzicht van alle toetsen - nieuwe aanmaken - importeren van collega" src="https://github.com/user-attachments/assets/c9f00e1b-66b3-44fa-91cb-279135300f31" />
Het brood en boter van Vos Pro. In het hoofdmenu staat een overzicht van alle toetsen en krijgt de docent de gelegenheid om een nieuwe toets aan te maken. In het overzicht is te zien voor welk leerjaar en niveau een toets is, welk type toets, weging, het aantal versies en het aantal afnames dat huidig aan deze toets hangt.

### RTTI en Normering
<img width="1286" height="946" alt="RTTI - selecteren - versiebeheer" src="https://github.com/user-attachments/assets/672b4792-f165-4bad-b590-d7e5a00d2f2f" />
Vos Pro ondersteund verschillende versies van een bepaalde toets zodat resultaten van eenzelfde klas bij eenzelfde toets blijven. RTTI-niveau's van vragen, het maximaal aantal punten en of een vraag als bonus telt of helemaal niet zijn gemakkelijk te selecteren. Rechts is te zien hoe de RTTI-verdeling van een toets tot stand is gekomen om te waarborgen dit aansluit bij het beoogde niveau.

<img width="433" height="749" alt="Kies normering - toegestane punten - overzicht van afnames" src="https://github.com/user-attachments/assets/4adb2a9f-eea4-4922-a045-f96ff72b8cfd" />
Vos Pro is standaard ingesteld op het uitsluitend toestaan van gehele punten voor vragen. Mocht een docent hiervan willen afwijken dient dit expliciet geselecteerd te worden. Daarnaast kan er voor de normering gekozen worden. Vos Pro ondersteund verscheidene normeringen waarbij het mogelijk is om te bepalen welk percentage punten behaald dient te worden voor een 5,5. Onderaan de normering staat een voorbeeld om te controleren.

### Samenwerken en samen interpreteren
Vos Pro is opgebouwd om samen te werken met collega's. Hoewel er geen leerlingdata Vos Pro verlaat van jouw laptop is het wel mogelijk om een toets die ingesteld is, of resultaten van een toets te exporteren. Dit bestand <naam>.vospro.json kan een collega importeren. Dit werkt voor zowel een toets als toetsresultaten. Hierdoor wordt het mogelijk om direct van een hele jaarlaag in kaart te brengen hoe er gepresteerd wordt en wat de kwaliteit van een toets is. Bij een export kan de naam van de docent of afkorting meegegeven worden welke zichtbaar wordt in de bestandsnaam en bij de import.

## Afnames en scores
<img width="1338" height="1260" alt="Afnames - overizcht" src="https://github.com/user-attachments/assets/677f752f-5615-4e65-9221-a410d9d19c66" />
Het afnames tabblad is een uitgebreider overzicht dan op het startscherm. Hier is zichtbaar hoe ver het nakijkwerk is, kan er een nieuwe afname geplannde worden en zijn er knoppen per afname om scores in te voeren en de resultaten te bekijken.

### Scores invoeren
<img width="1338" height="1260" alt="toetsinvoer met zicht op cijfers" src="https://github.com/user-attachments/assets/0969839f-6045-4590-8b23-d0e7ea7eb6bb" />
Scores invoeren is intuitief en snel te bewerkstelligen met een toetsenbord met een numpad. In de bovenste balk kan de normering aangepast worden of de afnamedatum. Leerlingen die een vrijstelling nodig hebben kunnen deze verkrijgen via het vrijstelling menu. 

Bij het invoeren van de punten per vraag is per vraag te zien wat het RTTI-niveau is en het maximaal aantal punten. Navigatie-cues staan bovenaan met de optie om een "N" in te vullen voor Niet gemaakt. Het totaal aantal punten wordt live meegeteld en met de gekozen berekening omgezet naar een cijfer.

## Resultaten 
<img width="1338" height="1260" alt="Resultaten van een toets - RTTI scores per leerling" src="https://github.com/user-attachments/assets/55fbec2e-481c-4da0-9d33-7e9c4a88dcef" />
Bij de resultaten is in één oogopslag de belangrijkste data te zien. Gemiddelde, histogram van de afgeronde eindcijfers, de totale prestatie op RTTI en de individuele prestatie op RTTI. Hier heeft een docent ook de optie om de resultaten te exporteren voor analyse bij een andere collega. Ook hier is de optie beschikbaar om de normering aan te passen of aan de N-term te sleutelen.

## Statistiek
De statistiek gaat dieper in op een toets, RIR- en RIT-waarden worden berekend aan de hand van toetsdata en kunnen vergeleken worden met andere klassen en toetsen:

<img width="1338" height="1260" alt="Statistiek van een toets" src="https://github.com/user-attachments/assets/39fb129e-19a0-4e38-8b2c-8f6ee0885bf2" />

Een toegelicht scatterplot laat zien waar vragen zich bevinden aan de hand van RIT- of RIR-waarden. Een overzicht van belangrijke data van alle versies, klassen etc. is hier ook zichtbaar evenals een histogram van alle groepen die een toets hebben gemaakt. Hier is het ook mogelijk om de export van een collega te importen en klassen direct met elkaar te vergelijken.

<img width="1338" height="1260" alt="RIT en RIR plus instructies" src="https://github.com/user-attachments/assets/2e23557d-f63c-4500-bd41-3577625560f0" />

Een uitgebreid overzicht van de scatter-plot erboven is zichtbaar, kleurgecodeerd en wordt toegelicht in "hoe lees ik RIT en RIR". Indien beschikbaar is het ook mogelijk om (mits dezelfde toets herhaaldelijk wordt afgenomen) schooljaren met elkaar te vergelijken.

## Instellingen
<img width="1338" height="1178" alt="Instellingen" src="https://github.com/user-attachments/assets/66d0e9eb-2688-4574-b628-396c2ed0b41f" />
Vos Pro vraagt de gebruiker bij het eerste gebruik om een cloud-opslaglocatie te kiezen. Daarnaast houdt Vos Pro (afhankelijk van de instelling) backups bij op de lokale machine, de gebruiker kan kiezen hoeveel backups er behouden moeten worden. De database-grootte is niet hinderlijk voor de opslag van een laptop. Het is hier dus ook mogelijk om een database van een collega te importeren indien het noodzakelijk is dat dit gebeurt.

## Installeren (Windows)
1. Klik op **Start**, typ `PowerShell` en open **Windows PowerShell**.
2. Kopieer deze regel, plak hem in het blauwe venster (rechtermuisknop of Ctrl+V) en druk op Enter:
   ```
   irm https://raw.githubusercontent.com/HPDesignJetZ9/vos-pro-releases/main/installeer.ps1 | iex
   ```
3. Volg het installatievenster dat verschijnt (Volgende → Installeren → Voltooien).
4. Klaar: Vos Pro staat in het Startmenu (en op het bureaublad) en opent in je browser.

Mag je bestanden gewoon downloaden? Dan kan het ook met
**[VosPro-Setup.exe](https://github.com/HPDesignJetZ9/vos-pro-releases/releases/latest/download/VosPro-Setup.exe)**
(waarschuwt Windows: **Meer info** → **Toch uitvoeren**).

Beheerdersrechten zijn niet nodig. Nieuwe versies installeer je later met één klik op de
knop **Update** bovenin het programma; vooraf wordt automatisch een back-up van je database gemaakt.

Afsluiten: de knop ⏻ rechtsboven. Verwijderen: Instellingen → Apps → Vos Pro (je database blijft staan).

Alle versies: [Releases](https://github.com/HPDesignJetZ9/vos-pro-releases/releases)
