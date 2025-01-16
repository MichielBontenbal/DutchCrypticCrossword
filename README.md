# DutchCrypticCrossword
Code to solve Dutch Cryptic Crossword using reasoning models.

### First run: OpenAI o1 3 januari 2024
Result: 19% correct (16 out of 86 questions)

| #  | Omschrijving                                                                               | Goede Antwoord           | Antwoord o1            | Juist? |
|----|-------------------------------------------------------------------------------------------|-----------------------|-----------------------|--------|
| 1  | Ach, dan komen er misschien wat minder skaters (4+4)                                      | Geen ramp            | Dooi weer            | nee    |
| 2  | 8. Vaak in de weg liggende familie van de wijsvinger (13)                                 | Verstandskies        | wegversperring       | nee    |
| 3  | 10. Kleurrijke zitjes langs de waterkant (15)                                             | Rietveldstoelen      | Strandstoeltjes      | nee    |
| 4  | 11. Hoge toon waar kinderen niet bij kunnen (8+2)                                         | Bovenste la          | Toonbank op          | nee    |
| 5  | 12. Het werkt toch minder als een regionale zender zich klassiek gaat presenteren (3)     | ATV                  | OFF                  | nee    |
| 6  | 13. Op het scherm is te zien waarin de klusjesman zijn accessoires bewaart (6)           | Bitmap               | schort               | nee    |
| 7  | 16. Waarschuwing om televisie te kunnen kijken (7)                                        | Signaal              | Signaal              | ja    |
| 8  | 17. Voorgedragen Nederlandse pianist (8)                                                 | Borstlap             | Gevraagd             | nee    |
| 9  | 18. Stabiele types na carnaval (6)                                                       | Vasten               | Vasten               | ja     |
| 10 | 19. Zo gesimplificeerd dat je naar bed kan (10)                                          | Uitgekleed           | Uitgekleed           | ja     |
| 11 | 21. Utrechtse pendant van een Delfts blauwe vaas (9)                                     | Groenekan            | Roodblauw            | nee    |
| 12 | Verscheen recentelijk in de bundel van Jantje zag eens pruimen hangen (8)                | Kersvers             | premiere             | nee    |
| 13 | Delftplaats arbeid (2+8+7)                                                               | In raadsels spreken  | Op goudmijn werken   | nee    |
| 14 | Met een nieuwe coupe zit je ineens op een lager niveau (3+2+4+8)                         | Van de trap gevallen | Met de trap gevallen | nee    |
| 15 | Uitdagende vluchtaankondiging (3+2+3+3+2+3)                                              | Pak me dan als je kan| Hijack               | nee    |
| 16 | Daar is een collectie goed te zien (13)                                                  | Textielmuseum        | Diacollectie         | nee    |
| 17 | Dominosteentje (dat blijft staan) (11)                                                   | Tegenvaller          | dominosteen          | nee    |
| 18 | Betaalsysteem met een eigen koers (4)                                                    | Giro                 | Euro                 | nee    |
| 19 | Door Engelstaligen bevestigde werkelijkheid (3)                                          | Ido                  | Yes                  | nee    |
| 20 | Boek in stripvorm (3)                                                                    | Pil                  | pdf                  | nee    |
| 21 | Draaglichaam (4)                                                                         | Tors                 | Romp                 | nee    |
| 22 | Goederen fabriceren om te laten zien dat het mogelijk is (9)                             | Waarmaken            | Prototype            | nee    |
| 23 | Rebellerende stammen (11)                                                                | Houtopstand          | Terugpraten          | nee    |
| 24 | Zo'n kleedje zal iets afgeven (14)                                                       | Estafettestok        | Kameelharenjas       | nee    |
| 25 | Handhaver die je in een wurggreep neemt (3 +11)                                          | Boa constrictor      | Boa constrictor      | ja     |
| 26 | Minderwaardig bedonderdeel (15)                                                          | Inflatiespiraal      | Slechte bedbodem     | nee    |
| 27 | (Zoals men voor de NAVO dans)t (5)'                                                      | Tango                | tango                | ja     |
| 28 | Gevaarlijke stof waar je U tegen zegt (7)                                                | Uranium              | Uranium              | ja     |
| 29 | Behoort tot de loofbomen (7)                                                             | Ereplaats            | Esdoorn              | nee    |
| 30 | Niet meer in New York aanwezig in Rotterdam nog wel (6)'                                 | Towers               | Molens               | nee    |
| 31 | Zij hebben een uitgang voor zichzelf (9)"                                               | Eigenaars            | Vluchtweg            | nee    |
| 32 | Ceremoniemeester (17)                                                                    | Partifunctionaris    | Meester ceremonie    | nee    |
| 33 | Wie lang van huis is, is erg wisselend in zijn emoties (6)                               | Jantje               | Labiel               | nee    |
| 34 | Idioot dwingt een vloerkleed zijn ontstaanswijze af (8)                                  | Geknoopt             | Vlechten             | nee    |
| 35 | Proefwerklokaal (15)                                                                     | Repetitieruimte      | Practicumlokaal      | nee    |
| 36 | Harde of zachte hulpmiddelen om te kunnen starten (13)                                   | Contactlenzen        | Slaginstrument       | nee    |
| 37 | Normaal gehuisvest zijn (6)                                                              | Gewoon               | Gewoon               | ja     |
| 38 | Hij kent nog niet alle openingen, er zitten de nodige gaten in (10)                      | Leerdammer           | houtblazer           | nee    |
| 39 | Ingelijst stuk (10)                                                                      | Implantaat           | schilderij           | nee    |
| 40 | Amsterdamse stationsmuziek (3)                                                           | Rai                  | RAI                  | ja     |
| 41 | Alarmerend gezicht (4)                                                                   | Toet                 | Toet                 | ja     |
| 42 | Diertjes op de mat (4)                                                                   | Worp                 | made                 | nee    |
| 43 | Ster die snel zal verdwijnen (8)                                                         | Avondzon             | Vallende             | nee    |
| 44 | Verhardt het OM (9)                                                                      | parketlak            | thermoset            | nee    |
| 45 | Voorzien van een ruim toilet, alsof het niks is (3+5+5)                                  | met groot gemak      | Met groot gemak      | ja     |
| 46 | Bewijsbaar (5)                                                                           | staaf                | Juist                | nee    |
| 47 | De tijd vinden om je rechtmatige deel te krijgen (8)                                     | toekomen            | Verdient             | nee    |
| 48 | Reactie helemaal in het midden (6)                                                       | hartje               | Reflex               | nee    |
| 49 | Stop op het hoogtepunt (3)                                                               | nok                  | top                  | nee    |
| 50 | Is onzijdig, behalve als het jong is (4)                                                 | ding                 | KIND                 | nee    |
| 51 | Bourgondische versie van een Nederlandse soap (4+1+2)                       | Cote d'or            | Eet 't op             | nee    |
| 52 | Apple, maar ook Action (5)                                                  | A-merk               | KETEN                 | nee    |
| 53 | Die gozer is niet thuis (4)                                                 | gast                 | niet                  | nee    |
| 54 | Bevervacht (8)                                                              | trilhaar             | Verwacht              | nee    |
| 55 | Mystiek familielid van het urinemonster (10)                                | watergeest           | hermetisme            | nee    |
| 56 | Superschot (13+4)                                                           | overtreffende trap   | Een Schot in de Roos  | nee    |
| 57 | Flauw commentaar (10+7)                                                     | ongezouten kritiek   | Broodjeaapverhaal     | nee    |
| 58 | Die breuk impliceert psychische schade (4)                                  | knak                 | Deuk                  | nee    |
| 59 | Het was heerlijk,' zei de paus (15)                                         | zaligverklaring      | Het was goddelijk     | nee    |
| 60 | Doen werklozen en geparkeerde auto's (2+6+5)                                | op straat staan      | Op straat staan       | ja     |
| 61 | Niet-passend treffen onder diensttijd (8)                                   | mismatch             | ongepast              | nee    |
| 62 | Zuid-Hollander die zware zaken te beoordelen krijgt (12)                    | Moordrechter         | Sliedrechter          | nee    |
| 63 | Met maar een paar gerechten kom je als reiziger niet ver (6+5)              | kleine kaart         | Kleine kaart          | ja     |
| 64 | Steen (goede kaart) (6)                                                     | topaas               | Ruiten                | nee    |
| 65 | En dan is het ook nog een stukje familievermogen (11)                       | neveneffect          | Handtekening          | nee    |
| 66 | Met harde hand zacht gemaakt (6)                                            | geweld               | Kneden                | nee    |
| 67 | Men zegt dat hij blijft (8)                                                 | schrijver            | monument              | nee    |
| 68 | Is samengebald op de set (4)                                                | prop                 | edit                  | nee    |
| 69 | Zo in de nacht komt men zich laten zien (4+2+3)                             | voor de dag          | Voor de dag           | ja     |
| 70 | Zo kapot dat je het moede hoofd te ruste wil leggen (3+4+2+5)               | rijp voor de sloop   | Met lood in benen     | nee    |
| 71 | Fijn om te horen, een verkiezing zonder ongeregeldheden (7+8)               | zuivere stemming     | Zuivere stemming      | ja     |
| 72 | Slap keukenartikel (6)                                                      | vadoek               | Spatel                | nee    |
| 73 | Voorkomend dat men bij de les is (6)                                        | attent               | Attent                | ja     |
| 74 | Niet werken bij gebrek aan inhoud (9)                                       | ledigheid            | Leegstand           | nee    |
| 75 | Wanneer gasten zich als dweil gedragen (4+2+5+5)                            | over de vloer komen  | Over de vloer komen | ja     |
| 76 | Utrechtse familie van de Weesper mop (12+3)                                 | Amersfoortse kei     | Utrechtse moppen    | nee    |
| 77 | Stom genoeg ben je er niet bij (3)                                          | suf                  | dom                 | nee    |
| 78 | Zielloze clubmuziek (8)                                                     | ledenpop             | synthpop            | nee    |
| 79 | Ze blijkt het toch niet met iedereen te doen in Brabant (8)                 | Schijndel            | monogame            | nee    |
| 80 | Binnenland (9)                                                              | terrarium            | Nederland           | nee    |
| 81 | Maatschappelijke ontwikkeling die tegen de studentencultuur ingaat (8)      | vergroening          | Orthodox            | nee    |
| 82 | Hersens gebruikt? Vergeet het maar (3+2+7)                                  | had je gedacht       | Het is waanzin      | nee    |
| 83 | Juist onaangedaan (4)                                                       | vlak                 | koel                | nee    |
| 84 | Schema van zoon Alex (6)                                                    | matrix               | schema              | nee    |
| 85 | Hun tanden zijn wit geschilderd (6)                                         | haalen               | haaien              | ja     |
| 86 | Stroming binnen de fanzone (10)                                             | ventilatie           | Afzonderen          | nee    |


