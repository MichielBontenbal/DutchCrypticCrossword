# DutchCrypticCrossword
Code to solve Dutch Cryptic Crossword using reasoning models.

### First run: OpenAI o1 3 januari 2024
Result: 19% correct (16 out of 86 questions)

| #  | Omschrijving                                                                               | Antwoord 1            | Antwoord 2            | Juist? |
|----|-------------------------------------------------------------------------------------------|-----------------------|-----------------------|--------|
| 1  | Ach, dan komen er misschien wat minder skaters (4+4)                                      | Geen ramp            | Dooi weer            | nee    |
| 2  | 8. Vaak in de weg liggende familie van de wijsvinger (13)                                 | Verstandskies        | wegversperring       | nee    |
| 3  | 10. Kleurrijke zitjes langs de waterkant (15)                                             | Rietveldstoelen      | Strandstoeltjes      | nee    |
| 4  | 11. Hoge toon waar kinderen niet bij kunnen (8+2)                                         | Bovenste la          | Toonbank op          | nee    |
| 5  | 12. Het werkt toch minder als een regionale zender zich klassiek gaat presenteren (3)     | ATV                  | OFF                  | nee    |
| 6  | 13. Op het scherm is te zien waarin de klusjesman zijn accessoires bewaart (6)           | Bitmap               | schort               | nee    |
| 7  | 16. Waarschuwing om televisie te kunnen kijken (7)                                        | Signaal              | Signaal              | nee    |
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

