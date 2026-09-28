# Vos Pro

Toetsvolgsysteem voor docenten: scores per vraag invoeren (ook met meerdere versies en N voor
"niet gemaakt"), cijfers met een normering naar keuze, RTTI, en statistiek per vraag (p-waarde, RIT, RIR).
Toetsen en resultaten deel je met collega's via een `.vospro.json`-bestand.

Alles draait op je eigen laptop, in je browser. Er gaan **geen leerlinggegevens het internet op**:
de database staat alleen op dit apparaat (`%LOCALAPPDATA%\VosPro`). Het programma kijkt alleen
of er een nieuwe versie is (één klein bestand van deze pagina).

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
