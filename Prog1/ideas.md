# Separata helper-files?

Ha funktionsskript som varje labb importerar?
Istället för att ha dem i varje labb.
Bra sätt att förenkla koden, enda nackdelen är att eleverna behöver ladda ner hjälpskripten.

Kan hjälpskripten vara online?
Inte helt fan av det, delvis pga cross-site scripting, delvis pga då krävs internet.

Nackdelen är att helperfilerna döljer då koden vilket gör att eleverna inte kan lära sig koden från kopiering/imitering.

Helperfilerna behöver också arbeta utifrån generiska saker och kan inte vara anpassade för den specifika laborationen.

CSS kan vara en separat fil.

# Bibliotek

## GSAP

https://greensock.com/gsap/

<script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/3.9.1/gsap.min.js"></script>

## D3 vs Charts

https://d3js.org/

<script src="https://d3js.org/d3.v7.min.js"></script>

https://www.chartjs.org/

https://www.createwithdata.com/d3js-or-chartjs/

## Agolia Places

https://community.algolia.com/places/

Adress auto-completion

## Moment.js

https://momentjs.com/

Datum och tid

## Three.js

https://threejs.org/

3D animation

## Axios

https://axios-http.com/

HTTP-requests

## VideoJS

https://videojs.com/getting-started/

Video embedding

## Phaser

https://phaser.io/

HTML5 game framework



# Generella

Input är en viktig del för att lära sig programmering, att testa hur ett program reagerar beroende på input från användaren.
Därför är console-log i node problematisk då node saknar prompts.

Att använda js i sin naturliga miljö, i webbläsaren, där output kan visas både i console och på sidan, men input kan ske från input-element så väl som webbsidans REPL.

Borde egentligen bara ha instruktioner i labb-filerna, samt länkar till resurser (så som Tektal och MDN).

## Wes bos style

Skapa hela mappar med övningar där instruktionerna är skrivna i kommentarer

Använda bara html-filer och köra inline style och script för enkelhets skull?
Behöver då ha med Separation of Concerns som en stor del av lärandet.

Genom att skapa färdiga exempel får eleverna både se kod, och möjlighet att lyckats i en relativt säker miljö med verkliga exempel.
Problemet: Mycket tid går åt att skapa exemplena och testa dem.

# Space Miner

# Basic Premise övningar

Först förklara vad det är. Be dem ta fram några premisser från existerande (app, musik, film, spel, osv). Sedan ska de få ändra den premissen (pivot). Slutligen ska de skapa en ny premiss och presentera den.

# Lektionsidéer

**På den här uppgiften kommer \_\_\_ vara extra viktigt.**

- Användarvänlighet (tex. visa felmeddelande, lätt att hitta och tydligt vad som händer i applikationen)
- Performance (minst antal operationer)
- Utseende
- Dokumentation
- Planering
- Kodstruktur

**Lektionsupplägg**

1. Presentera uppdraget och vad som är viktigt
2. Genomgång/repetition av koncept eller tekniker
3. Uppdelning i grupper
4. Iterationsarbete med lärarhjälp

Grupp-programmering i helklass (de ger förslag, jag skriver) ibland. Gör liknande i arbetsgrupper.

Gör ett poängsystem för inlämning? Behöver dela upp det i kategorier likt stats för att få fram att de lär sig enligt kursplanens krav (ala kursmatrisen).

Bonuspoäng är möjliga, men har då med högre betyg, inte inlämningspoäng.

# Skapa ett spel som...

Hanterar temat "Kärlek".

Utforskar mekaniken Jump utifrån Marios värld.

Har tre olika karaktärer.

Tillåter spelaren att teleportera som sin främsta mekanik.

Är gjort för två spelare på samma maskin.

Låter spelaren använda en enkel mekanik på många olika sätt.
