Svolværvannet Fiskekalkulator – PWA v5 med Open-Meteo

NYTT
- Appen henter automatisk værdata for Svolvær fra Open-Meteo.
- Du trenger bare å legge inn vind ved fiskestart selv.
- Følgende hentes/beregnes automatisk:
  * nedbør siste 48 timer
  * gårsdagens døgnmiddelvind
  * temperatur omkring kl. 20
  * lufttrykk nå og lufttrykk ca. fire døgn tidligere
  * trykkendring siste fire døgn
  * dagens månefase
  * hvor i sesongen vi er
- Ved nettfeil bruker appen sist lagrede værdata hvis den har det.
- Selve poengvektingen vises ikke i brukergrensesnittet.

VIKTIG
Open-Meteo-dataene er griddede/modellbaserte værdata for Svolvær og er ikke identiske
med observasjonene fra MET-stasjonene SN85470 og SN85450.

OPPDATER GITHUB PAGES
1. Pakk ut ZIP-filen.
2. Erstatt index.html og service-worker.js i GitHub-repositoryet.
3. manifest.json og ikonfilene kan beholdes, eller du kan laste opp alle filene fra pakken.
4. Commit changes.
5. Åpne GitHub Pages-siden i Chrome og last den på nytt én gang.
6. Lukk deretter den installerte PWA-en helt og åpne den igjen.

Appen må ha nett for å hente ferske værdata. Den statiske kalkulatoren fungerer fortsatt
som PWA, og sist hentede værdata lagres lokalt som reserve.
