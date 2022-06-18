# Mailclient
Bij veel activiteiten is het handig om leden individueel te kunnen berijken.
Dit kan met appjes, Bcc's of handmatig veel mailen.
Wij als 12e LustrumCie der C.S.R. liepen er tegen aan dat mailtjes vaak in de spam kwam als je te veel bcc's deed.
Vooral bij oudleden was dit een probleem, maar het werkt ook goed voor het mailen van leden met specifieke info als kamer/tafel/bus indeling. 

Na wat [literatuur onderzoek](https://realpython.com/python-send-email/) bleek het makkelijk te kunnen in python met wat kennis van html. 
Ik gebruik zelf graag jupyter notebook te vinden op [anaconda](https://www.anaconda.com/), maar 'gewoon'[python](https://www.python.org/downloads/) kan natuurlijk ook.
Zorg wel dat je [pandas](https://pandas.pydata.org/) en [numpy](https://pandas.pydata.org/) installeert in je omgeving (pip install ...)

Het notebook bestand is ook in git te openen, hier beschrijf ik wat ik doe en hoe het werkt.
Op de Wiki staat een extra bestand alleen voor C.S.R. leden waar specifieke mail informatie op staat(hoeft niet per se publiek zegmaar)

Er zijn 2 typen scripjes
1. Mail leden op basis van een ketzer, hierbij hoef je zelf niks te doen, alleen de html tekst aan te passen, kan bijvoorbeeld op basis van niks ingevoerd. Maar ook iedereen in de ketzer. 
2. Mail leden met info uit een excel, hierbij lever je een excel aan en kan je kollomen uit de excel per persoon aanroepen in je html tekst.
