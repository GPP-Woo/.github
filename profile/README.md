# Gemeenten werken samen aan een generiek publicatieplatform!

De overheid wil voor burgers transparant en open zijn. Daarom heeft zij de Wet open overheid (Woo) vastgesteld. Die vraagt dat gemeenten hun documenten openbaar en digitaal beschikbaar maken. Zo laten wij als gemeente zien wát wij doen en waaróm wij dat doen. Een groeiende groep inwoners wil dat graag weten! 

In de praktijk maken gemeenten al documenten openbaar. Dat doen zij op online platforms die vaak alleen geschikt zijn voor een beperkte set aan documenten. Via een gezamenlijk project met negen gemeenten gaan we dit jaar een platform ontwikkelen dat geschikt is voor alle typen documenten. Hiermee kunnen we eenvoudiger en grootschaliger documenten publiceren. Inwoners en andere belangstellenden worden dan beter geïnformeerd over ontwikkelingen in hun gemeente en kunnen zo beter meedenken en meedoen. 


## Wat gaan we realiseren, waarom en wanneer?

Voor het publiceren van (aanzienlijke hoeveelheden) documenten is technologie nodig. De wet schrijft voor dat overheidsorganisaties, waaronder gemeenten, hiervoor aansluiten op de landelijke voorziening [Woo-index](https://open.overheid.nl/). Deze landelijke voorziening vergt dat overheidsorganen, dus ook gemeenten, documenten publiceren op een eigen online platform. 

Met het project ‘Generiek Publicatieplatform Woo (GGP-Woo)’ ontwikkelen en realiseren de samenwerkende gemeenten een generiek publicatieplatform voor de publieke openbaarmaking van documenten en metadata. Deze bestaat uit een viertal componenten:
- De [GPP-publicatiebank](https://github.com/GPP-Woo/GPP-publicatiebank), een opslagvoorziening inclusief API's voor openbare documenten en metadata,
- Het [GPP-zoeken](https://github.com/GPP-Woo/GPP-zoeken),  zoektechnologie voor het doorzoekbaar en vindbaar maken van openbare documenten,
- De [GPP-app](https://github.com/GPP-Woo/GPP-app), gebruikersinterfaces voor medewerkers en beheerders voor het publiceren en beheren van openbare documenten
- Het [GPP-burgerportaal](https://github.com/GPP-Woo/GPP-burgerportaal), gebruikersinterfaces voor burgers  voor het zoeken en raadplegen van openbare documenten

We volgen daarbij de principes van [Common Ground](https://commonground.nl/) en open source. Uiteraard besteden we daarbij ook volop aandacht aan het voldoen aan wet- en regelgeving, informatieveiligheid, digitale toegankelijkheid en open standaarden.

Meer informatie over de boogde oplossing is te lezen in onze [Project Start Architectuur](https://github.com/GPP-Woo/.github/blob/main/docs/PSA%20Generiek%20Publicatieplatform%20Woo%20V1.1.pdf).


## Hoever zijn we?

Van alle vier bovengenoemde componenten zijn inmiddels releases uitgebracht! Deze zijn hier op GitHub te downloaden en te installeren. Voor de technische implementatie adviseren wij om gebruik te maken van de [helm charts](https://github.com/GPP-Woo/charts). Dimpact heeft voor haar leden al een hosting- en support-aanbod opgesteld. Neem voor meer informatie contact op met je field manager!

Met de huidige oplossing kunnen medewerkers handmatig documenten publiceren. Voor meer geautomatiseerde oplossingen kan er gekoppeld worden met een [API](https://github.com/GPP-Woo/GPP-publicatiebank?tab=readme-ov-file#api-specificatie). De gepubliceerde documenten kunnen door burgers gevonden en geraadpleegd worden op het _burgerportaal_ van de gemeente. Deze kan geheel in huisstijl worden gebracht door gebruik te maken van het [NL Design System](https://nldesignsystem.nl/). Ook voorziet het _burgerportaal_ in de sitemap die nodig is voor aansluiting op de landelijke [Woo-voorzieningen](https://open.overheid.nl/).

Ondertussen zitten we niet stil! Samen met de deelnemende gemeenten hebben we op hoofdlijnen (epics) de prioriteiten bepaald. Zie hiervoor [de lijst met epics](https://github.com/orgs/GPP-Woo/projects/2/views/5). In mei 2025 hebben we de "lokale thema's" en "Bewaartermijnen archiefbeheer" opgeleverd. In juni en juli 2025 hebben we de API's t.b.v. integraties met zaaksystemen en andere bronsystemen uitgebreid en verbeterd. Ook hebben we enkele verbeteringen doorgevoerd t.b.v. de gebruiksvriendelijkheid voor medewerkers en burgers. Deze nieuwe functionaliteiten zijn begin september opgeleverd als productie-release en zijn dus nu beschikbaar om te downloaden en te implementeren!

Wij vragen alle organisaties die GPP-Woo willen implementeren om zich aan te sluiten bij de community, zodat we samen kunnen optrekken in het onderhouden en door-ontwikkelen van de software. Neem hiervoor contact met ons op (zie hieronder). De community heeft overigens al besloten om in Q4 van dit jaar weer verder te gaan met de door-ontwikkeling. De scope en planning worden nu voorbereid en afgestemd. Wil je meer weten? Neem dan contact met ons op! (Zie hieronder)


## Wie zijn "we"?

Het project GPP-Woo wordt uitgevoerd onder de vlag van en ondersteund door [Dimpact](https://www.dimpact.nl/). Op dit moment zijn de volgende gemeenten actief betrokken bij het project:
- Gemeente Assen
- Gemeente Enschede
- Gemeente Groningen
- Gemeente Haarlemmermeer
- Gemeente Kampen
- Gemeente Losser
- Gemeente Maastricht [^1]
- Gemeente Rotterdam
- Gemeente 's-Hertogenbosch
- Gemeente Sittard-Geleen [^1]
- Gemeente Waterland
- Gemeente Zaanstad

Het platform wordt momenteel in opdracht van Dimpact ontwikkeld door [ICATT](https://www.icatt.nl/) en [Maykin](https://www.maykinmedia.nl/nl/).

[^1]: Niet lid van Dimpact.

## Contact

Meer weten over onze aanpak en ambities? Neem dan gerust contact op met een van de onderstaande contactpersonen:
- [Marco Klerks](mailto:mm.klerks@rotterdam.nl) - Product owner GPP-Woo  (Gemeente Rotterdam)
- [Martin de Bijl](mailto:martin.debijl@dimpact.nl) - Adviseur Innovatie (Dimpact)
- [Jaap van Vliet](jaap.vanvliet@dimpact.nl) - Regisseur Samenwerking (Dimpact)

