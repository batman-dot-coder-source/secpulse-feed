# secpulse-feed

Automaattisesti kerätty data henkilökohtaiseen Euroopan turvallisuustilannekuvaan.
Raspberry Pi -keräin lukee julkisia viranomaissyötteitä (mm. Supo, PST, ABW, VDD, Rajavartiolaitos,
Puolustusministeriö, Försvarsmakten, Viron puolustusvoimat, Kyberturvallisuuskeskus, CERT-SE, CERT Polska)
neljä kertaa päivässä ilman kielimallia.

- status.json: lähteiden tila (HTTP-tila, kohdemäärät, uusin kohde)
- inbox/VVVV-KK-PP.json: kohteet, jotka nähtiin ensi kertaa kyseisenä päivänä

Sisältö on julkisten tiedotteiden otsikoita, linkkejä ja lyhyitä kuvauksia. Älä muokkaa käsin; keräin kirjoittaa tiedostot.
