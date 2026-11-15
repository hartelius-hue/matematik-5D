# Matematikværkstedet · 5.D

Et interaktivt træningssite til 5. klasse, udgivet som et selvstændigt materiale. De første **13 emner følger kapitelrækkefølgen i MULTI 5**. Det **14. emne er et ekstra værksted i regneregler og regnemetoder**. Matematikværkstedet er ikke en officiel Gyldendal-udgivelse.

## Det indeholder sitet

- **56 forskellige spil:** fire spil til hvert af 14 emner, heraf et ekstra metodeværksted.
- **Tre niveauer i alle spil:** Kom i gang, Øv videre og Udfordring.
- **Syv opgaver pr. runde.** To forsøg pr. opgave, forklarende feedback og opsamling efter spillet.
- **Matematikhjælper:** Et tip, et separat regneeksempel og fagbegreber. Hjælpen viser ikke svaret på den aktuelle opgave.
- **Højtlæsning:** Manuel knap ved opgaver, fagtekster, introduktioner og forklaringer. Automatisk oplæsning kan slås til eller fra i topbjælken. Oplæsning bruger den tilgængelige tale-funktion i browseren; kvalitet og danske stemmer afhænger af enhed og browser.
- **Hjælp til at vælge træning:** Forsiden viser alle emner og ni elevudsagn som »Jeg vil forstå regneregler« og »Jeg vil forstå en tekstopgave«. Et udsagn fører til et anbefalet spil.
- Nye **3D-bannere** til hovedområderne, tilpasset mobil og computer.
- **Lokal øvehistorik** i browseren uden elevkonto, navn, sporing eller egen server.

## Det ekstra metodeværksted

1. **Regnerækkefølge:** Parenteser, gange/division før plus/minus og udtryk med flere regnearter.
2. **Plus og minus på flere måder:** Opdeling efter pladsværdi og kompensation.
3. **Smarte gangemetoder:** Opdeling, den distributive lov og regning via runde tal.
4. **Division trin for trin:** Sammenhængen mellem division og multiplikation, opdeling og kontrol.

## Udgiv på GitHub Pages

1. Upload indholdet af mappen til roden af repositoryet `hartelius-hue/matematik-5D`: `index.html`, `style.css`, `gamebank.js`, `app.js`, `assets/`, `.nojekyll` og denne `README.md`.
2. Gå til **Settings → Pages** i GitHub.
3. Vælg **Deploy from a branch**, `main`, `/(root)` og gem.
4. Adressen bliver normalt `https://hartelius-hue.github.io/matematik-5D/`, når GitHub Pages er aktiveret og udgivelsen gennemført.

Filerne er almindelig HTML, CSS og JavaScript. Der kræves ingen installation, database eller byggetrin. Åbn `index.html` lokalt for at prøve indholdet.

## Faglig og teknisk kvalitet

- Opgaverne bruger dansk matematisk fagsprog med korte instruktioner, opgaveforklaringer og tydelige læringsmål før, under og efter en runde.
- Faglig læsning arbejder med at forstå matematiske opgaver, fagord, oplysninger og spørgsmålet i en tekst.
- Øvehistorikken registrerer korrekt svar **i første forsøg** særskilt fra opgaver, der blev løst med et ekstra forsøg. Det er træningsdata, ikke en standardiseret elevtest.
- De matematiske opgaver er nyproducerede til dette site og ikke kopier fra MULTI-bogen.
- Web Speech API er en browserfunktion. Hvis den ikke er tilgængelig, kan sitet stadig bruges med tekst og matematikhjælperen.

## Vedligeholdelse

Opgaveindhold og generatorer ligger i `gamebank.js`, brugerflade og oplæsning i `app.js`, layout i `style.css` og strukturen i `index.html`. `tests/` indeholder scripts til opgave- og browsertest, men er ikke nødvendige for offentliggørelse.
