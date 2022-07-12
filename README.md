# JavaScript project: herexamen 2021-2022

In dit practicum implementeren we het spel [Vier op een rij](https://nl.wikipedia.org/wiki/Vier_op_%27n_rij) in Javascript.
Zoals de projecten in het eerste semester, wordt dit project ingediend via GitHub Classroom.
Tijdens de verdediging kijken we naar de recentst gepushte commit versie vóór het verstrijken van de deadline.


## Afspraken

Overloop eerst de afspraken vooraleer je begint aan de opgave.


### Gedragscode

De practica worden gequoteerd, en het examenreglement is dan ook van toepassing.
Soms is er echter wat onduidelijkheid over wat toegestaan is en niet inzake samenwerking bij opdrachten zoals deze.

De oplossing en/of programmacode die ingediend wordt, moet volledig het resultaat zijn van werk dat je zelf gepresteerd hebt.
Je mag je werk uiteraard bespreken met andere studenten, in de zin dat je praat over algemene oplossingsmethoden of algoritmen, maar de bespreking mag niet gaan over specifieke code die je aan het schrijven bent of die je wenst in te dienen.
Als je het met anderen over je practicum hebt, mag dit er dus *nooit* toe leiden, dat je op om het even welk moment in het bezit bent van een geheel of gedeeltelijke kopie van het opgeloste practicum van anderen, onafhankelijk van of die code op papier staat of in elektronische vorm beschikbaar is, en onafhankelijk van wie de code geschreven heeft (mede-studenten, eventueel uit andere studiejaren, volledige buitenstaanders, internet-bronnen, e.d.).
Dit houdt tevens ook in dat er geen enkele geldige reden is om je code door te geven aan mede-studenten, noch om ze beschikbaar te stellen via publiek bereikbare directories of websites. De git-repository die we jullie ter beschikking stellen is standaard op privaat ingesteld.

Elke student is verantwoordelijk voor de code en het werk dat hij of zij indient.
Als er tijdens de beoordeling van het practicum twijfels zijn over het feit of het practicum zelf gemaakt is (bvb. gelijkaardige code, of oplossingen met andere practica), zal de student gevraagd worden hiervoor een verklaring te geven.
Indien dit de twijfels niet wegwerkt, zal er worden overgegaan tot het melden van een onregelmatigheid, zoals voorzien in het onderwijs- en examenreglement (zie http://www.kuleuven.be/onderwijs/oer/).

**Alle inzendingen worden automatisch met elkaar vergeleken met behulp van plagiaatsoftware voor code.
Deze software geeft een score van gelijkaardigheid aan projecten.
De projecten die het meest op elkaar lijken worden nadien manueel nagekeken.**


### Toelichting

Het is toegestaan om gebruik te maken van informatie en code (bijvoorbeeld hulpfuncties) op het internet om je practicum op te lossen, **indien je de bron vermeldt**.
Het is niet de bedoeling om een volledig opgelost spel te downloaden en dit in te dienen, zelfs met bronvermelding.

Indien je twijfelt over wat al dan niet toegestaan is, stel dan een vraag op het discussieforum!


### Forum

Alle vragen over het practicum, *inclusief vragen aan medestudenten*, moeten gesteld worden via het **discussieforum** op [Toledo](https://toledo.kuleuven.be).

Alle antwoorden van assistenten op het discussieforum worden beschouwd als **deel van de opgave** en kunnen bijgevolg aanvullingen of correcties bevatten.
Zorg ervoor dat je deze posts leest!

Tip: open het forum en klik bovenaan op *subscribe* om een e-mail te krijgen wanneer nieuwe threads worden toegevoegd aan het forum.


### Indienen

De *deadline* voor dit practicum is **vrijdag 12 augustus 2022** om **23u59**.
Het practicum wordt ingediend met behulp van _Git_, door simpelweg je oplossing te pushen naar deze online repository.

Wijzigingen aan jullie repository na deze datum zullen niet aanvaard worden.

``` bash

$ git add index.html
$ git add code.js
... <alle bestanden toevoegen met git add> ...
$ git commit -m "Oplossing practicum"
$ git push origin master
```

**Kijk goed na of je alle bestanden correct hebt ingediend. Een foute inzending wordt gelijkgesteld aan laattijdige inzending!**
Controleer je inzending door je eigen repository opnieuw te clonen in een tijdelijke folder.

``` bash
$ cd /tmp
$ git clone https://www.github.com/informaticawerktuigen2021-2022/herexamen-javascript-connect4-[github_accountnaam]
$ cd herexamen-javascript-connect4-[github_accountnaam]
$ firefox index.html
```

Indien alles correct is gepusht zouden bovenstaande commando's je oplossing moeten downloaden van GitHub en vervolgens openen in Firefox.

Je kan de inhoud van de repository ook nakijken op de website van GitHub zelf.

**Tip:** Het is ook een goed idee om regelmatig gedurende het maken van je project je bestanden te committen en pushen met git.
Zo heb je altijd een back-up van je code.


### Verdediging

Op de verdediging is het uiterst belangrijk dat je goed kan uitleggen wat je code doet, en waarom je bepaalde keuzes hebt gemaakt.
Vergeet zeker niet om als voorbereiding voor de verdediging je eigen code opnieuw te bekijken, zeker de ingewikkelde delen.
Met code waarvan je niet kan uitleggen hoe ze werkt, kan je uiteraard weinig punten verdienen.

Er kan je tijdens de verdediging ook gevraagd worden beperkte aanpassingen te doen aan de code die je hebt geschreven.
Op deze manier controleren we enerzijds of je de code zelf hebt geschreven, en anderzijds of je de taal voldoende begrijpt.

De praktische informatie omtrent de verdediging en de planning volgen later via Toledo.

De verdediging is een examenmoment, behandel dit ook zo.
**Zorg ervoor dat je op tijd aanwezig bent.**
Indien je om eender welke reden niet op tijd op de verdediging kan geraken, neem dan zo snel mogelijk contact op met het assistententeam zodat er gezocht kan worden naar een oplossing.
*Niet komen opdagen op je verdediging, zonder enige verwittiging, zal resulteren in een 0 op dit practicum*.
Indien je door ziekte je verdediging niet kan halen, bezorg je je ombudspersoon een doktersattest.
Via de ombudspersoon kan dan een inhaalverdediging vastgelegd worden.


## Evaluatiecriteria

In deze sectie beschrijven we kort enkele criteria die we gebruiken om een score toe te kennen aan het practicum.


### Functionaliteit

In de eerste plaats wordt er gekeken naar een correcte, foutloze werking van je programma.
Zorg ervoor dat alle functionaliteit die in de opgave gevraagd wordt, ook aanwezig is in je programma.
Je zal enkel kunnen slagen voor dit practicum als je een werkend spel oplevert!


### Leesbaarheid code

Zorg ervoor dat je code leesbaar is!

Enkele tips:

* Gebruik duidelijke, verklarende namen voor alle variabelen en functies.
* Maak gebruik van functies om je code op te delen. Deel lange functies op in kleinere subfuncties die je probleem stap voor stap oplossen. Als je je code voldoende opsplitst in functies met heldere namen zal de code snel leesbaar worden.
* *Indenteer* je code! Vele editors hebben auto-formatting functionaliteit. Maak daar gebruik van! Er is niets vervelender dan code te lezen met foute of geen indentatie.
* Maak gebruik van commentaar, maar enkel voor de stukken code die slecht leesbaar zijn. Voeg deze commentaar dus pas toe nadat je alle bovenstaande stappen hebt uitgevoerd en nog steeds merkt dat het stuk code lastig te lezen is.
* Wees consequent met alle stijlkeuzes die je maakt. Indien je bijvoorbeeld beslist om een accolade telkens op een nieuwe regel te laten beginnen, doe dit dan voor het volledige document.


### Correcte inzending

Zorg ervoor dat je code correct en tijdig is ingediend via GitHub.


### Niet gequoteerd

We geven geen punten op

* Mooiheid van de user interface. Het kan leuk zijn om je spel mooier te maken, maar hier kan je geen punten mee winnen. (Concreet mogen munten dus bvb. vierkant zijn.)
* Extra (ongevraagde) functionaliteit. Je mag eigen functies toevoegen, maar hier kan je geen punten mee winnen.


# Opgave

De opdracht van in practicum bestaat eruit het spel [Vier op een rij](https://nl.wikipedia.org/wiki/Vier_op_%27n_rij) te implementeren met behulp van HTML, CSS en Javascript.
In deze sectie beschrijven we eerst de algemene regels en werking van het spel.
Vervolgens beschrijven we de specifieke functionaliteit die we verwachten in jullie oplossing.


## Vier op een rij

Om de regels van Vier op een rij op te frissen kan je het spel [online](https://basisonderwijs.online/digibordtools/vieropeenrij.html) spelen.
We beschrijven de regels ook in deze sectie.

### Spelregels

#### Doel van het spel

Vier of meer van je munten op een aaneensluitende rij krijgen (horizontaal, verticaal of diagonaal!), en vermijden dat je tegenstander hetzelfde doet.

#### Het spelbord

Het bord is (in dit geval) een rechthoek, verdeeld in 6 × 8 vakken.

#### De munten

Elke speler heeft zijn eigen kleur munten (meestal geel en rood).

#### Het spel

Het aantal spelers is beperkt tot exact twee spelers. De spelers laten om de beurt een munt in het spelbord vallen. De eerste munt kan enkel in de onderste rij terecht komen. Nadat er een munt is geplaatst, kan de volgende speler kiezen om boven dat stuk te spelen of ernaast op de onderste rij. Elke volgende munt valt dus als het ware op een van de reeds gespeelde munten of (indien nog mogelijk) in de onderste rij. Met andere woorden: je bouwt verder op de stukken die reeds geplaatst werden.


## Functionaliteit

In deze sectie beschrijven we de functionaliteit die we verwachten voor dit practicum.

* Voorzie een spelbord dat bestaat uit 6 rijen en 8 kolommen.
* Het spel moet gespeeld kunnen worden door twee menselijke spelers - je hoeft dus geen computerspeler te voorzien.
* Zorg ervoor dat er een visueel verschil is tussen een leeg vakje en munten van beide spelers.
* De kleur van de speler die aan zet is moet weergegeven worden.
* De speler moet een munt in een kolom laten vallen (dit komt neer op het inkleuren van een vak). Dit bv. kan door op een knop boven de kolom te klikken, door op de kolom zelf te klikken, ... De munt moet zich gedragen zoals in de spelregels beschreven. De kleur van de munt is uiteraard deze van de huidige speler.
* Van zodra een speler een munt heeft geplaatst, dient de beurt automatisch over te gaan naar de andere speler.
* Je moet ook detecteren of een speler gewonnen heeft. Het spel geeft een melding zodra een speler wint. Ook als het bord vol is en er geen winnaar is, breng je de spelers hiervan op de hoogte. De spelers moeten dan de optie hebben om een nieuw spel te kunnen aanvangen.
* Toon een timer die aangeeft hoe lang het huidige spel al loopt.
* Voorzie ook een knop om onmiddellijk een nieuw spel te starten.


## Oplossingsstrategie

Om dit practicum op te lossen kan je het werk opsplitsen in een aantal stappen:

1. Maak eerst met behulp van HTML en CSS de volledige interface voor een willekeurig spelbord.
Zorg ervoor dat je hierin alle grafische elementen al verwerkt.
2. Bedenk een representatie in JavaScript die de volledige staat van het spel kan beschrijven. Denk bijvoorbeeld aan de oefenzitting, waarin we een tweedimensionale lijst gebruikten om een Sliding Puzzle voor te stellen.
3. Schrijf een functie die de interne Javascript-representatie kan omzetten naar jouw HTML-representatie. Kijk bijvoorbeeld naar de functies *draw_puzzle* en *generate_puzzle_html* uit de oefenzitting.
4. Vervolgens kan je functies schrijven die gebruik maken van de interne voorstelling van je spel om het spel te spelen. Bij iedere aanpassing van de interne representatie kan je deze opnieuw omzetten naar HTML met behulp van je omzetfunctie. Je kan de functies telkens testen door deze uit te voeren vanuit de JavaScript console.
5. Maak gebruik van de onclick-attributen van HTML om ervoor te zorgen dat wanneer men op het spelbord klikt, de correcte JavaScript functies (geschreven in de vorige stap) uitgevoerd worden.


## Opgave downloaden

Via GitHub Classroom hebben jullie een eigen private kopie gekregen van deze repository.

Deze repository kan je clonen met het commando:

``` bash
$ git clone https://www.github.com/informaticawerktuigen2021-2022/herexamen-javascript-connect4-[github_accountnaam]
```

De repository bevat reeds een basis-HTML bestand gekoppeld aan een leeg Javascript-bestand en een leeg CSS-bestand.
Vanuit deze bestanden kan je starten.
Het is echter ook toegestaan je eigen bestanden toe te voegen of de meegeleverde bestanden te verwijderen.
