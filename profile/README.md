# Gemeenten werken samen aan een generiek publicatieplatform!

**De overheid wil voor burgers transparant en open zijn. Daarom heeft zij de Wet open overheid (Woo) vastgesteld. Die vraagt dat overheidsorganisaties hun documenten openbaar en digitaal beschikbaar maken. Zo laten wij als overheidsorganisatie zien wát wij doen en waaróm wij dat doen. Een groeiende groep burgers wil dat graag weten!**

**Alle overheidsorganisaties maken al documenten openbaar. Dat doen zij echter vaak op online platforms die alleen geschikt zijn voor een beperkte set aan documenten. Via een gezamenlijke aanpak met een groeiend aantal gemeenten hebben wij een platform ontwikkeld dat geschikt is voor alle typen documenten. Hiermee kunnen overheidsorganisaties eenvoudiger en grootschaliger documenten publiceren. Inwoners en andere belangstellenden worden dan beter geïnformeerd over ontwikkelingen in hun leefomgeving en kunnen zo beter meedenken en meedoen.**


## Wat hebben we al gerealiseerd en waarom?

Voor het publiceren van (aanzienlijke hoeveelheden) documenten is technologie nodig. De wet schrijft voor dat overheidsorganisaties hiervoor aansluiten op de [Generieke Woo-voorziening (GWV)](https://open.overheid.nl/). Deze landelijke voorziening vergt dat decentrale overheidsorganen documenten publiceren op een eigen online platform. 

Met het project ‘Generiek Publicatieplatform Woo (GGP-Woo)’ hebben de samenwerkende gemeenten een **generiek publicatieplatform** ontwikkeld en gerealiseerd voor de **actieve openbaarmaking** van documenten en metadata. Deze oplossing bestaat uit een viertal componenten:
- De **[GPP-publicatiebank](https://github.com/GPP-Woo/GPP-publicatiebank)**, een opslagvoorziening inclusief API's voor openbare documenten en metadata,
- Het **[GPP-zoeken](https://github.com/GPP-Woo/GPP-zoeken)**,  zoektechnologie voor het doorzoekbaar en vindbaar maken van openbare documenten,
- De **[GPP-app](https://github.com/GPP-Woo/GPP-app)**, gebruikersinterfaces voor medewerkers en beheerders voor het publiceren en beheren van openbare documenten
- Het **[GPP-burgerportaal](https://github.com/GPP-Woo/GPP-burgerportaal)**, gebruikersinterfaces voor burgers  voor het zoeken en raadplegen van openbare documenten

Met de huidige oplossing kunnen medewerkers **handmatig** documenten publiceren. Voor meer **geautomatiseerde oplossingen** kan er gekoppeld worden met een [API](https://github.com/GPP-Woo/GPP-publicatiebank?tab=readme-ov-file#api-specificatie). De gepubliceerde documenten kunnen door burgers gevonden en geraadpleegd worden op het **burgerportaal** van de gemeente. Deze kan geheel in huisstijl worden gebracht door gebruik te maken van het [NL Design System](https://nldesignsystem.nl/). Ook voorziet het burgerportaal in de **sitemaps** die nodig zijn voor aansluiting op de landelijke [Generieke Woo-Voorziening (GWV)](https://open.overheid.nl/).

We volgen daarbij de principes van **[Common Ground](https://commonground.nl/)** en **open source**. Uiteraard besteden we daarbij ook volop aandacht aan het voldoen aan **wet- en regelgeving**, **informatieveiligheid**, **digitale toegankelijkheid** en **open standaarden**.

Van alle vier bovengenoemde componenten zijn **productie-rijpe releases** beschikbaar. Eind april 2026 hebben we de meest recente releases uitgebracht met daarin nieuwe functionaliteiten zoals het strippen van embedded metadata, het kunnen zien en bewerken van publicaties van collega's en een geheel nieuw beheerscherm voor het burgerportaal (bewerken van de welkomsttekst, embedded video, afbeeldingen en externe URL's). 

Alle releases zijn hier op GitHub te **downloaden** en te **installeren**. Voor de technische implementatie adviseren wij om gebruik te maken van de [helm charts](https://github.com/GPP-Woo/charts). Dimpact heeft voor haar leden al een **hosting- en support-aanbod** opgesteld. Neem voor meer informatie contact op met je field manager!

Zie voor meer informatie **[de opname van ons webinar](https://www.youtube.com/watch?v=dRy1ODuVKHk)** eerder dit jaar en/of kijk op onze website **[www.gpp-woo.nl](https://www.gpp-woo.nl/)**!


## Waar werken we nu aan?

Op dit moment lopen de eerste **implementaties** van het GPP-Woo. Koploper daarin is gemeente Groningen met haar website [open.groningen.nl](https://open.groningen.nl/). Ook bij een aantal andere gemeenten staan al werkende productie-omgevingen klaar, maar moeten de medewerkers hier de eerste documenten nog in publiceren. Daarnaast werken enkele gemeenten nog aan de voorbereiding of uitvoering van de technsiche implementatie. Wanneer we hierin wat verder zijn, zullen we daar zeker breed over communiceren!

Ondertussen maken we de plannen voor de verdere **door-ontwikkeling**! Samen met de deelnemende gemeenten hebben we op hoofdlijnen (epics) de prioriteiten bepaald. Zie hiervoor [de lijst met epics](https://github.com/orgs/GPP-Woo/projects/2/views/5). Gelet op deze prioriteiten en de beperkingen die voortvloeien uit de landleijke ontwikkelingen, werkt de product owner momenteel onder meer aan het uitwerken van de epics rondom een documentviewer en de ondersteuning van bekendmakingen (incl. digitale terinzagelegging). Ook de epics rondom NLdoc en open data krijgen aandacht. Wanneer deze ideeën verder zijn uitgewerkt, zullen we daar uiteraard over communiceren. Het voornemen is sowieso om na de zomervakantie weer aan de slag te gaan met de door-ontwikkeling!

Daarnaast is ons voornemen om na de zomervakantie te starten met de **integratie** van het GPP-Woo binnen **[PodiumD](https://www.dimpact.nl/podiumd/)** van Dimpact. Als eerste zullen dan de impact bepaald moeten worden en een plan worden opgesteld. De uitvoering zal op z'n vroegst ergens in 2027 plaats vinden. En uiteraard zullen we er ook voor zorgen dat het GPP-Woo ook buiten de context van PodiumD beschikbaar en bruikbaar blijft!


## Wie zijn "we" en hoe doe ik mee?

Het project GPP-Woo wordt uitgevoerd onder de vlag van en ondersteund door [Dimpact](https://www.dimpact.nl/). Op dit moment zijn de volgende gemeenten **actief betrokken** bij het project:
- Gemeente Assen
- Gemeente Borger-Odoorn
- Gemeente Culemborg
- Gemeente Emmen
- Gemeente Enschede
- Gemeente Groningen
- Gemeente Haarlemmermeer
- Gemeente Kampen
- Gemeente Losser
- Gemeente Maashorst
- Gemeente Maastricht [^1]
- Gemeente Oldenzaal
- Gemeente Oost Gelre
- Gemeente Rotterdam
- Gemeente 's-Hertogenbosch
- Gemeente Sittard-Geleen [^1]
- Gemeente Tiel
- Gemeente Waterland
- Gemeente West Betuwe
- Gemeente Zaanstad

Het platform wordt momenteel in opdracht van Dimpact ontwikkeld door [ICATT](https://www.icatt.nl/) en [Maykin](https://www.maykinmedia.nl/nl/).

Wij vragen alle organisaties die GPP-Woo willen implementeren om zich aan te sluiten bij de **community**, zodat we samen kunnen optrekken in het onderhouden en door-ontwikkelen van de software. **Wil je met ons meedoen? Top!** Neem dan even contact met ons op (zie hieronder) en dan spreken we elkaar gauw!

[^1]: Niet lid van Dimpact.

## Contact

Meer weten over onze aanpak en ambities? Neem dan gerust contact op met een van de onderstaande **contactpersonen**:
- [Marco Klerks](mailto:mm.klerks@rotterdam.nl) - Product owner GPP-Woo  (Gemeente Rotterdam)
- [Jaap van Vliet](jaap.vanvliet@dimpact.nl) - Regisseur Samenwerking (Dimpact)
- [Martin de Bijl](mailto:martin.debijl@dimpact.nl) - Adviseur Innovatie (Dimpact)


