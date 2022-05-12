# Internet & Wireless

## Onderzoeksvraag

Wat is de toepassing van Ultra-Wideband (UWB) in toekomstige technologieën?

## Taakverdeling

| Vraag                                                                                        | Wie?   |
|----------------------------------------------------------------------------------------------|--------|
| D1. Van welke frequentie/bandbreedte maakt Ultra-Wideband gebruik?                           | Bob    |
| D2. Waarom heet het eigenlijk Ultra-Wideband? Welke verschillen heeft het?                   | Camiel |
| D3. Welke toepassingen gebruiken al Ultra-Wideband?                                          | Camiel |
| D4. Hoe kan Ultra-Wideband betreft techniek zich in de toekomst ontwikkelen?                 | Bob    |
| D5. Wat is het verschil tussen Ultra-Wideband en bijvoorbeeld 4G en 5G betreft zend theorie. | Samen  |
| H1. Wat is de toepassing van Ultra-Wideband in toekomstige technologieën?                    | Samen  |

## Deelvragen

### 1. Van welke frequentie/bandbreedte maakt Ultra-Wideband gebruik?

Met behulp van Ultra-Wideband kan een grote hoeveelheid gegevens worden verzonden. Dit is mogelijk door kleine gegevenspakketjes te zenden over een brede frequentieband. Doordat er sprake is van brede frequentiebanden kunnen de gegevenspakketten parallel worden verzonden. Er dan zelfs een maximale data overdracht mogelijk van één gigabyte over tien meter.

UWB werkt met kortdurende pulsen (dit kan een miljardste van een seconde bedragen). Daardoor kan er al gebruik worden gemaakt van bestaande frequenties die al voor andere toepassingen worden gebruikt. De tijdsduur van een puls is vaak zelfs zo kort dat er hierbij geen interferentie op kan treden. Toch zijn er vanwege bezorgdheden over interferenties regels gekoppeld aan UWB door de 'Federal Communications Commission' (FCC). Deze commissie laat UWB alleen toe als het met een zeer laag vermogen wordt gebruikt binnen toepassingen. Dit zorgt ervoor dat het bereik van UWB vaak alleen tientallen meters kan bedragen. Indien het bereik vergroot moet worden zal het vermogen van UWB respectievelijk vergroot moeten worden. 

Op een gegeven moment wilde de FCC de regels voor UWB versoepelen. Dit werkt echter tegengehouden door grote bedrijven die bepaalde frequentiebanden hadden opgekocht. In feite kan UWB opereren bijhorende een frequentie tussen de 3.1 en 10.6 GHz. Echter heeft het tegenwoordig haar toepassingen gevonden rond de 1 GHz (dezelfde frequentie als [GPS](https://nl.wikipedia.org/wiki/Global_positioning_system)), en de [GPR](https://nl.wikipedia.org/wiki/Ground-penetrating_radar). De frequentie varieert hierbij tussen de 3.1 en 10.6 GHz, zoals hierboven al eenmaal benoemd. Er is nog geen exacte frequentieband gegeven dat speciaal voor UWB wordt gebruikt, alhoewel worden hier recentelijk ontwikkelingen in gemaakt binnen IEEE 802.15.4Z.

UWB werkt met een spread-sprectrum technologie. Hierbij wordt een singaal met opzet verspreid over een bepaald frequentiedomein. Deze dergelijke signalen hebben een veel grotere bandbreedte dan de werkelijke informatie dat ze bevatten. Dit betekent dat er een ruisachtig signaal ontstaat, wat moeilijk te detecteren of te onderscheppen is. Verder wordt het ook moeilijk om een spread-spectrum signaal te storen met andere signalen. Vaak vraagt men zich af hoe een ontvanger een signaal kan decoderen dat veelal ruis zal bevatten. Om dit ruis eruit te filteren wordt er gebruik gemaakt van _spreading-codes_. Dit zijn codes die vrij willekeurig moeten zijn, maar toch moet de informatie bekend zijn bij zowel de zender als ontvanger van het UWB-signaal.Hieirn zijn twee factoren te definiëren, de eerste is FHSS. Het informatiesignaal springt van de ene frequentieband naar de andere. De volgorde hiervan wordt bepaald door de _spreading-codes_. De tweede is daarentegen DSSS. De informatie wordt in bits verzonden, en de _spreading-code_ werkt met een hogere frequentie. Het is mogelijk om deze twee toepassingen met elkaar te combineren.

In de onderstaande afbeelding wordt deze theorie mooi gevisualiseerd. Je kunt zien dat UWB een groot frequentiebereik heeft. Het varieert inderdaad van ongeveer 3.1 tot 10.6 GHz. Verder is ook zichtbaar dat de FCC een limiet heeft gesteld aan het vermogen dat UWB zoal uit mag zenden. Merk op dat dit voor 802.11a (een 5 GHz Wi-Fi verbinding) veel groter is. Doordat UWB zo'n groot frequentiespectrum kunnen veel gegevens worden verzonden, maar een verminderd zendvermogen van dit medium kan het echter maar enkele meters reiken.

<p align="center">
  <img src="doc/img/UWB_SPECTRUM.png" height="250" width="500"/>
  <p>Figuur 1: Overzicht spectra verschillende wireless protocollen</p>
</p>

Het is zichtbaar dat het bereik van UWB dicht bij het 'noise level' ligt. Soms vraagt men zich hierbij af of het 'noise level' niet kan storen met het vermogen dat UWB zoal gebruikt. Dit vormt geen probleem, aangezien UWB gebruik maakt van spread-spectrum technologie. Deze technologie is hierboven al uitgewerkt, en zorgt ervoor dat het signaal met opzet over een breed frequentiebereik wordt verstuurd. Op basis van de data dat binnen een signaal wordt verstuurd maakt het dus niet uit dat het vermogen van UWB dicht bij het 'noise level' ligt. 

### 2. Waarom heet het eigenlijk Ultra-Wideband? Welke verschillen heeft het?

In figuur 1 is het bereik en domein van de verschillende protocollen goed te vergelijken. Hieruit blijkt ook dat de bekendere protocollen die worden weergeven in dit figuur een (stuk) band gebruiken voor de communicatie. Bij het bekijken van het UWB spectrum wordt het al snel duidelijk dat er een paar verschillen zijn tussen "standaard" protocollen zoals GPS, Wi-Fi of Bluetooth en UWB. Uit het figuur is het voornaamste verschil duidelijk het verschil in breedte van de frequentie band. Bij GPS of Wi-Fi wordt er een vrij smal bereik gebruikt voor het versturen van data, terwijl bij UWB dit bereik een stuk groter is. Het verschil in bereik is zo groot dat het UWB spectrum de veelgebruikte Wi-Fi standaarden (802.11a/n/ac/ax) overlapt.

### 2. Waarom heet het eigenlijk Ultra-Wideband? Welke verschillen heeft het? 

### 3. Welke toepassingen gebruiken al Ultra-Wideband?



### 4. Hoe kan Ultra-Wideband betreft techniek zich in de toekomst ontwikkelen?

UWB heeft steeds meer toepassingen. Dit komt er onder andere mede door dat Apple in haar nieuwste producten met deze technologie voorziet. Het wordt voornamelijk gebruik om precies locaties te bepalen, en bijvoorbeeld objecten tot een exacte afstand te kunnen vinden. Maar tegenwoordig vindt het ook steeds meer haar toepassingen in bijvoorbeeld de zorg en autotechniek. Deze toepassingen zullen zich in de nabije toekomst daarom steeds verder gaan ontwikkelen, en UWB zal een groter aandeel hebben in de technologie dat wordt gebruikt in het dagelijks leven. Hieronder volgt een verdere opsomming:

- Social distancing. Ten tijde dat de corona-pandemie op zijn toppunt was werd UWB gebruikt om afstanden te bepalen, om zo eventuele besmettingen tussen personen op te kunnen sporen. Doordat afstanden tot tien centimeter nauwkeurig kunnen worden gemeten kan een verspreiding in sommige gevallen worden voorkomen, of worden opgespoord. De reden dat UWB hier onder andere ook voor wordt gebruikt is dat het een zeer laag stroomverbruik heeft, ideaal voor mobiele apparaten. In de toekomst zal UWB er dus voor kunnen worden gebruikt om verspreidingen van virussen op te sporen.
- Industrie. Gereedschappen (zoals bijvoorbeeld momentsleutels) in productieprocessen kunnen op afstand worden gekalibreerd met behulp van UWB. Eventuele fouten in gereedschappen kunnen direct en snel worden opgelost, en de productie kan efficiënter worden verricht. In de toekomst zal UWB verdere toepassingen krijgen in bijvoorbeeld de verf industrie. Er kan middels dit medium zeer nauwkeurig de afstand worden bepaald tussen een spuitkop en een oppervlak dat wordt gespoten. Zo worden oneffenheden in een verf proces volledig geëlimineerd. 
- Er worden zeer recentelijk stappen gezet in de ontwikkeling van UWB Secure Payment, om de volgende stap van beveiligd betalen te zetten. De opname van Scrambled Timestamp Sequence (STS) in IEEE 802.15.4Z helpt ervoor te zorgen dat kritieke informatie, zoals de validatieafstand tot de betaalterminal veilig wordt bewaard en niet kan worden onderschept of gemanipuleerd. Contactloos betalen kan met UWB dus veiliger worden gemaakt.
- Auto's, contactloos de auto binnentreden. Veelal nieuwe auto's worden voorzien van een technologie waar men de auto kan betreden, zonder hier bijvoorbeeld fysiek de sleutel voor te hoeven gebruiken. Echter, doordat je hier niet de sleutel fysiek voor hoeft te gebruiken bestaat er een kans voor dieven de auto gemakkelijker te kunnen stelen. Maar als autosleutels voorzien worden van UWB kan dit worden gebruikt om te kijken of de drager van de sleutel daadwerkelijk in de buurt is van de auto om deze te openen, en zich in de auto bevindt om deze te starten. Met behulp van IEEE 802.15.4Z met Scrambled Timestamp Sequence (STS) zal het zelfs mogelijk worden om communicatie tussen een sleutel en auto volledig te beveiligen, zonder dat hacken mogelijk is. 

### 5. Wat is het verschil tussen Ultra-Wideband en bijvoorbeeld 4G en 5G betreft zend theorie.

## Hoofdvraag: Wat is de toepassing van Ultra-Wideband in toekomstige technologieën?

### Afkortingen

Hieronder is een opsomming gegeven van enkele gebruikte afkortingen in dit vooronderzoek:

* FCC, Federal Communications Commission.
* UWB, Ultra-Wideband.
* FHSS, Frequency Hopping Spread Spectrum.
* DSSS, Direct Sequence Spread Spectrum.

### Referenties

Hieronder is een opsomming gegeven van de referenties gebruikt in dit vooronderzoek.

* Wikipedia. (2021, 21 april). Ultra-wideband. Geraadpleegd op 3 mei 2022, van https://nl.wikipedia.org/wiki/Ultra-wideband
* ScienceDirect. (2021, 23 februari). Ultra-Wideband. Geraadpleegd op 3 mei 2022, van https://www.sciencedirect.com/topics/engineering/ultra-wideband
* UWB Alliance. (2020, 26 januari). UWB Allicance. Geraadpleegd op 3 mei 2022, van https://uwballiance.org
* IEEE SA. (2020, 15 mei). IEEE SA - IEEE 802.15.4z-2020. IEEE. Geraadpleegd op 3 mei 2022, van https://standards.ieee.org/ieee/802.15.4z/10230/
* Qorvo US Inc. (2020, Mei). Getting Back to Basics with
Ultra-Wideband (UWB). Geraadpleegd op 12 Mei 2022, van https://www.qorvo.com/-/media/files/qorvopublic/white-papers/qorvo-getting-back-to-basics-with-ultra-wideband-uwb-white-paper.pdf

> Voor referenties, gebruik een APA-vermelding. Dit is eenvoudig te genereren via de volgende [link](https://www.scribbr.nl/bronnengenerator/apa/).
