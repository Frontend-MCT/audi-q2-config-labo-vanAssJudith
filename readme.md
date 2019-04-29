# Audi Q2 Explorer
We maken een kleine website voor een nieuw model. We maken dit enkel op mobile.

Het _draait vooral om herhaling van wat we deze module al gezien hebben_. Er zijn een paar kleine nieuwe dingen, maar dat gaat vooral om de performante afbeeldingen. Je kan de oefening dus ook maken zonder geoptimaliseerde afbeeldingen en achteraf kijken wat beter kan.


## Doelstellingen
- **Nette en gestructureerde code** schrijven.
- **Afbeeldingen op een performante** manier gebruiken.
- Semantische HTML schrijven.
- SCSS herbruikbaar en netjes schrijven volgens een ITCSS pattern.
- JS schrijven op een gestructureerde manier en met een logische opsplitsing.
- Gulp opzetten.


## Over deze oefening
- Begin met nadenken over hoe je de oefening wil aanpakken. Wat heb je nodig, welke bestandsstructuur wil je, etc.

- Je kan deze oefening maken met verschillende pagina's, zoals de vorige oefening of het proberen te doen als een single page application.
	- Kijk eens naar de optie voor het gebruik van https://visionmedia.github.io/page.js/.
	- ⚠️ Een SPA maken in vanilla JS in niet simpel. Als je de vorige labos nog erg moeilijk vindt, gebruik dan aparte pagina's.

- Je krijgt een adobe XD bestand voor deze oefening. Probeer alles zo goed mogelijk na te maken.

- Op het splash-scherm na, houd je altijd de laatst geselecteerde kleur (blauw, rood, grijs, etc.). Ps.: gebruik hiervoor CSS variabelen.
Wat doe je met wit?


## HTML
Probeer semantische tags te gebruiken.


## SCSS
Gebruik een duidelijke structuur. Volgens mij is het het gemakkelijkste om de bestanden van vorige keer te kopiëren en vandaaruit opnieuw te vertrekken.


## Javascript
Dit is waarschijnlijk het moeilijkste deel van deze oefening. Probeer te denken hoe jij het wil aanpakken.

Een voorstel om te werken is:
- een UI module,
- een localStorage module,
- een soort van controller (of doe je dit met app.js?).


## Afbeeldingen
Je zult merken dat de afbeeldingen niet op de goede grootte gemaakt zijn. Denk na over de goede extensies, een correcte grootte, overbodige delen in de afbeelding, etc.


- Kijk de snelheid na via de audit-tool in Chrome.
- Alle afbeeldingen komen van [de site van Audi](https://www.nl.audi.be/be/web/nl/modellen/q2/q2/packs.html). Daar kan je ook de originele gebruiken indien je dat handig vindt.


## Gulp
Vertrek van een gelijkaardige manier als de vorige keer.
Zorg dat je zeker ook via je smartphone kan kijken: we werken voor mobiel.

Het enige wat je nu kan doen, is het maken van een taak voor het automatisch optimaliseren van de afbeeldingen. Doe dit alleen als je tijd over hebt. Anders kan je dit handmatig doen via Photoshop en online tools.
