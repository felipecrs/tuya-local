## Acknowledgements

None of this would have been possible without some foundational discovery work to get me started:

- [nicole-ashley](https://github.com/nicole-ashley)'s [homeassistant-goldair-climate](https://github.com/nicole-ashley/homeassistant-goldair-climate) was the starting point for expanding to non-Goldair devices as well.
- [TarxBoy](https://github.com/TarxBoy)'s [investigation using codetheweb/tuyapi](https://github.com/codetheweb/tuyapi/issues/31) to figure out the correlation of the cryptic DPS states .
- [sean6541](https://github.com/sean6541)'s [tuya-homeassistant](https://github.com/sean6541/tuya-homeassistant) library giving an example of integrating Tuya devices with Home Assistant.
- [clach04](https://github.com/clach04)'s [python-tuya](https://github.com/clach04/python-tuya) library.
- [jasonacox](https://github.com/jasonacox)'s [tinytuya](https://github.com/jasonacox/tinytuya) library which improves on the original.

Further device support has been made with the assistance of users.  Please consider contributing if you find a device that is not supported by gathering some information about the device's DPS ids and their values.

- [etamtlosz](https://github.com/etamtlosz) and [KiLLeRRaT](https://github.com/KiLLeRRaT) for their support and dev work towards GECO and GPCV heaters.
- [botts7](https://github.com/botts7) for support towards widening Kogan SmartPlug support.
- [awaismun](https://github.com/awaismun) for assistance in supporting Andersson heaters.
- [FeikoJoosten](https://github.com/FeikoJoosten) for development of support for Eurom Mon Soleil 600 heaters.
- [Xeovar](https://github.com/Xeovar) for assistance in supporting Purline M100 heaters, Garden PAC pool heatpumps and Qoto sprinklers.
- [paulmfclark](https://github.com/paulmfclark) for assistance in supporting Remora Inverter pool heatpumps
- [cartman10](https://github.com/cartman10) for assistance with BWT FI 45 pool heater.
 - [superman110](https://github.com/superman110) for assistance in supporting Eanons/purenjoy humidifier and SD123 human presence radar.
 - [woolmonkey](https://github.com/woolmonkey) for assistance in supporting Inkbird ITC306A Thermostat.
 - [hazell20](https://github.com/hazell20) for assistance in supporting Anko fans.
 - [meremortals70](https://github.com/meremortals70) for assistance in supporting Deta fan controllers.
 - [mvnixon](https://github.com/mvnixon) for assistance in supporting Madimack pool heaters.
 - [Lapy](https://github.com/Lapy) for contributing support for Electriq CD25PRO dehumidifiers.
 - [thomas-fr](https://github.com/thomas-fr) for contributing support for Poolex Silverline heatpumps.
 - [lperez31](https://github.com/lperez31) for contributing support for Poolex Vertigo heatpumps.
 - [b3nnyk22](https://github.com/b3nnyk22) for assistance in supporting Kogan Dehumidifiers.
 - [rodrigoGA](https://github.com/rodrigoGA) for assistance in supporting Greenwind dehumidifiers.
 - [jorgenDK](https://github.com/jorgenDK) for assistance in supporting TroniTechnik Air Conditioner, and thanks for the coffee!
 - [Fannangir](https://github.com/Fannangir) for assistance in supporting Tadiran Wind Air Conditioner, Zemismart curtain rail and Somgam 1, 2, 3 and 4 gang switches.
 - [marrold](https://github.com/marrold) for contributing support for ElectriQ CD20PRO dehumidifiers.
 - [Uaeguy](https://github.com/Uaeguy) for assistance in supporting Beca BHP-6000, Saswell T29UTK and Owon PCT513 thermostats, and thanks for the coffee!
 - [Johnnybyzhang](https://github.com/Johnnybyzhang) for assistance in supporting Lexy F501 fans.
 - [domgrimm](https://github.com/domgrimm) for assistance in supporting newer models of Kogan heater.
 - [EKCJ](https://github.com/EKCJ) for contributing support for ElectriQ DESD9LW dehumidifiers.
 - [ed-holland](https://github.com/ed-holland) for contributing support for Awow TH213 thermostats
 - [Vikedlol](https://github.com/Vikedlol) for assistance in supporting Wetair WCH-750 heaters.
 - [wwalczyszyn](https://github.com/wwalczyszyn) for contributing support for Fersk Vind 2 heatpumps.
 - [xbmcnut](https://github.com/xbmcnut) for assistance in supporting Kogan Smart Kettles and the new type of Kogan heater.
 - [ThomasADavis](https://github.com/ThomasADavis) for contributing support for Renpho RP-AP001S air purifiers.
 - [darek-margas](https://github.com/darek-margas) for contributing support for Arlec fans, Carson portable air conditioners, Grid Connect double outlets with and without USB and power monitoring, Mirabella Genio smartplugs.
 - [SamJongenelen](https://github.com/SamJongenelen) for assistance in supporting Saswell C16 Thermostats
 - [antoweb](https://github.com/antoweb) for assistance in supporting Beca BHT-6000 thermostats.
 - [klausahrenberg](https://github.com/klausahrenberg) for figuring out the BHT-6000 and other thermostats' internal MCU protocol for his alternate MQQT firmware, which helped with finding some of the details.
 - [Swiftnesses](https://github.com/Swiftnesses) for contributing support for Electriq CD12PW dehumidifiers
 - [MrDeon](https://github.com/MrDeon) for assistance in supporting Kogan KAWFPAC09YA air conditioners.
 - [SatarisGIT](https://github.com/SatarisGIT) for assistance in supporting Eberg Qubo Q40HD portable heatpump.
 - [lucaxxaa](https://github.com/lucaxxaa) for assistance in supporting Beca BHT-002 thermostat.
 - [nickdos](https://github.com/nickdos) for assistance in supporting Stirling FS1-40DC fan.
 - [Skro11-ru](https://github.com/Skro11-ru) for assistance in supporting Moes BHT-002 variant without external temperature sensor.
 - [novisys](https://github.com/novisys) for clarifications about BHT-6000 thermostat functionality.
 - [nzcodarnoc](https://github.com/nzcodarnoc) for contributing support for Kogan KASHMFP heaters.
 - [pascaltippelt](https://github.com/pascaltippelt) for assistance in supporting Minco MH-1823 thermostat.
 - [voed](https://github.com/voed) for assistance in supporting Advanced Energy monitoring smart switch, based on CBE smart switch but seeming to follow a Tuya Standard Template, so probably applicable to others.
 - [myevit](https://github.com/myevit) for assistance in supporting simple garage doors.
 - [maartendamen](https://github.com/maartendamen) for assistance in supporting Eurom Mon Soleil 601 heaters.
 - [TeddyLafrite](https://github.com/TeddyLafrite) for assistance in supporting Nedis HTPL20F heaters.
 - [mvroosmalen1970](https://github.com/mvroosmalen1970) for assistance in supporting Eurom SaniWall 2000 heaters.
 - [petrkotek](https://github.com/petrkotek) for contributing support for Madimack Elite V3 pool heatpumps.
 - [irakhlin](https://github.com/irakhlin) for contributing support for Aspen ASP200 fans.
 - [vampywiz17](https://github.com/vampywiz17) for contributing support for TMWF02 fan controllers, Digoo, Woox and MoesHouse smartplugs and powerstrips and simple switches with timers. Also sasistance with figuring out the formats used by Tuya for RGBW lighting.
 - [awaldram](https://github.com/awaldram) for confirming BHT-3000 support.
 - [bob-tm](https://github.com/bob-tm) for contributing support from Wetair WAW-H1210LW humidifiers.
 - [shakin89](https://github.com/shakin89) for assistance in supporting Beca BAC-002 thermostats.
 - [PaulJoosten](https://github.com/PaulJoosten) for assistance in figuring out the similarities and capabilities of different Eurom heaters.
 - [jdavidr17](https://github.com/jdavidr17) for assistance with discovering timer parameters for switches.
 - [miannelli516](https://github.com/miannelli516) for assistance with TR9B thermostats.
 - [edwinyoo44](https://github.com/edwinyoo44) for contributing support for JJPro JPD01 and JPD02 dehumidifiers and assistance with Poiema One purifiers.
 - [mpetcuRO](https://github.com/mpetcuRO) for assistance with Hysen HT08WE-2 thermometers.
 - [Paul-C-S](https://github.com/Paul-C-S) for assistance with Ecostrad Accent iQ heaters and contributing support for iQ Ceramic radiators.
 - [WildeRNS](https://github.com/WildeRNS) for assistance with Nashone MTS-700-WB thermostat smartplugs, SmartMCB Energy meter.
 - [ishioni](https://github.com/ishioni) for contributing support for Eberg Cooly C32HD air conditioner.
 - [Gekko47](https://github.com/Gekko47) for contributing support for ElectriQ CD12v2 dehumidifiers.
 - [andreq](https://github.com/andreq) for assistance with Inkbird ITC-308 thermostats.
 - [dlosito](https://github.com/dlosito) for assistance with a second variant of Awow TH213 thermostat.
 - [UrZdcw9](https://github.com/UrZdcw9) for assistance with Arlec ceiling fan with light.
 - [dlosito](https://github.com/dlosito) for assistance with Lefant M213 vacuum cleaners.
- [kramttocs](https://github.com/kramttocs) for assistance with Kyvol E30 vacuum cleaners.
- [dieantu](https://github.com/dieantu) for contributing support for Himox H06 purifiers.
- [pgistrand](https://github.com/pgistrand) for contributing support for Vork VK6067AW purifiers, and assistance with Parkside smart charger.
- [markbvdh](https://github.com/markbvdh) for assistance with Kogan garage openers and confirmation of Summerwave Si pool heatpumps.
- [tavicu](https://github.com/tavicu) for contributing support for Starlight Heatpumps, Simple Blinds and for the idea to support inverted values.
- [Chris061290](https://github.com/Chris061290) for contributing support for IPS Pro pool heatpumps, complete with unit tests.
- [MartinCarbol](https://github.com/MartinCarbol) for contributing support for two models of Tesla Air Purifier.
- [gschmidl](https://github.com/gschmidl) for assistance with Himox H05 purifier.
- [daitj](https://github.com/daitj) for contributing support for Wilfa Haze humidifier.
- [Utopia69](https://github.com/Utopia69) for providing additional info on his Fairland IPH45 heatpump (matching Madimack)
- [Seopgroenten](https://github.com/Soepgronten) for assistance with W'eau pool heatpumps.
- [choppedpork](https://github.com/choppedpork) for contributing support for QS Wifi curtain modules.
- [Swiftnesses](https://github.com/Swiftnesses) for assistance with Devola patio heaters and Atomi string lights.
- [odeBuXTeR](https://github.com/odeBuXTeR) for contributing support for Poolex Q-line pool heatpumps.
- [peterforeman](https:github.com/peterforeman) for assistance with improving Fairland/Madimack support.
- [Krispkiwi](https://github.com/Krispkiwi) for assistance with M027 curtain modules and debugging Kogan Kettle.
- [craibo](https://github.com/craibo) for contributing support for Jiahong ET-72W thermostats.
- [x-keita](https://github.com/x-keita) for contributing support for Betterlife BL1500 IR heaters and Nexxt smart switches.
- [Der-Nax](https:github.com/Der-Nax) for assistance with a second variant of energy monitoring smart switch and for contributing support for PY321-TY power clamps, Compteur smart meters and sensors on a Universal Remote Control.
- [17hoehbr](https://github.com/17hoehbr) for assistance supporting APOSEN A550
- [yurgh](https://github.com/yurgh) for assistant supporting Eesee Adam dehumidifier
- [KaportsevIA](https://github.com/KaportsevIA) for assistance supporting Hyundai Sahara dehumidifier, Yandax color bulb and ES01 powerstrip.
- [poolMiniDomo](https://github.com/poolMiniDomo) for assistance supporting Moes Temperature and Humidity switches.
- [pretoriano80](https://github.com/pretoriano80) for assistance supporting AlecoAir dehumidifiers.
- [JanekSMC](https://github.com/JanekSMC) for assistance supporting Orion Smart Locks.
- [RichardMawdsley](https://github.com/RichardMawdsley) for assistance supporting ElectriQ Airflex 15W heatpumps.
- [fwelvering](https://github.com/fwelvering) for assistance supporting a second variant of W'eau pool heatpumps.
- [illuzn](https://github.com/illuzn) for contributing support for Kogan Tower Heaters and Arlec PB88UHA power strips.
- [vnkorol](https://github.com/vnkorol) for assistance supporting 4-way power monitoring strip and Avatto roller blinds.
- [OmegaKill](https://github.com/OmegaKill) for assistance supporting Be Cool heatpumps.
- [djusHa](https://github.com/djusHa) for contributing support for essentials portable air purifier.
- [alexmaras](https://github.com/alexmaras) for contributing support for Catit Pixi smart fountain.
- [jamiergrs](https://github.com/jamiergrs) for assistance supporting Orion Grid Connect outdoor sirens.
- [myhomeiot](https://github.com/myhomeiot) for contributing support for Bresser 7-in-1 Weather Station and Dongguan Garage Door.
- [Condorello](https://github.com/Condorello) for assistance supporting Inkbird sous vide cookers.
- [sebastiangebosz](https://github.com/sebastiangebosz) for contributing improvements to Eberg Qubo heatpumps.
- [VoyteckPL](https://github.com/VoyteckPL) for contributing support for Fairland IPHCR15 pool heatpumps.
- [mihsu81](https://github.com/mihsu81) for assiting with support for Wistar roller blind controllers.
- [AlfredBroda](https://github.com/AlfredBroda) for contributing support for Beok TGR81 thermostats.
- [bedtiming](https://github.com/bedtiming) for assisting with support for Ledkia fan and light controllers.
- [timlaing](https://github.com/timlaing) for contributing support for ElectriQ EcoSilent 14HPW air conditioners.
- [Svellem](https://github.com/Svellem) for assisting with support for T5E-WF thermostats.
- [Aptul9](https://github.com/Aptul9) for assisting with support for Sendo air conditioners.
- [dilorenzo1987](https://github.com/dilorenzo1987) for contributing support for Stadler Form Roger purifiers.
- [fsevilla3](https://github.com/fsevilla3) for contributing support for water_heater entities and Hydrotherm Dynamix/X8 water heaters.
- [allistermaguire](https://github.com/allistermaguire) for contributing improvements to Saswell C16 thermostats.
- [karnas99](https://github.com/karnas99) for assistance in improving Hysen thermostat support.
- [cooperaj](https://github.com/cooperaj) for contributing support for ElectriQ CD12PRO-LE dehumidifiers.
- [geroulas](https://github.com/geroulas) for assisting with support for Inventor Atmosphere XL dehumidifiers.
- [and7ey](https://github.com/and7ey) for assisting with support for Screen sync smart lights.
- [dragosmd](https://github.com/dragosmd) and [RomchikL](https://github.com/RomchikL) for assisting with support for more dual switches.
- [patrik-malina](https://github.com/patrik-malina) for contributing improvements to Kyvol vacuums.
- [cr4shydlo](https://github.com/cr4shydlo) for assistance supporting Rotenso Roni heat pumps.
- [mojiro](https://github.com/mojiro) for contributing support for ETOP-HT thermostats.
