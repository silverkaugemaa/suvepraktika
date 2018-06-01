## Projekti funktsionaalsusnõue:

**Klient:**
 * Saab sisselogida
 * Esitada uue taotluse
 * Saab olemas taotlusi vaadata
 * Klient saab taotluse tagasivõtta (taotlus jääb alles)
 * Andmebaasis on taotluse last modified väli.
 * Olemasoleva taotluse kohta genereerida PDF'i
 * Klient saab valida taotluse ning selle põhjal genereerida aruandluse

**Admin:**
 * Saab näha kõiki taotlusi ning soovitud taotluse kohta genereerida PDF'i
 * Märkuste lahter kuhu admin saab taotluse kohta informatsiooni kirjutada.
 * Filtreerida taotlusi.
 * Saab iga taotluse kohta genereerida kas positiivse või negatiivse otsuse korral.
 * Genereerida taotleja nime, projekti nime ja taoteldavat summat sisaldava väljavõtte.
 * Näeb kõiki aruandeid ning saab neid vaadata.

## Kliendi funktsionaalsuse Use Case'id:

**Klient saab sisselogida**
1) Klient on sisselogimis lehel.
2) Klient sisestab oma TLÜ e-maili aadressi ja parooli.
3) Klient vajutab "Login" nuppu.
4) Kui kliendi e-mail ja parool on õiged, suunatakse ta pealehele.

**Klient saab esitada uue taotluse:**
1) Klient logib sisse või on sisse logitud.
2) Klient valib pealehelt "esita uus taotlus".
3) Klient valib taotluse liigi.
4) Klient täidab valitud taotluse vormi.
5) Klient vajutab "kinnita".

**Klient saab olemas taotlusi vaadata:**
1) Klient logib sisse või on sisse logitud.
2) Klient valib pealehelt tema poolt varasemalt esitatud taotluse.
3) Vajutades nuppu "vaata taotlust" viiakse ta valitud taotluse lehele, kuhu kuvatakse andmebaasist laetud taotluse sisu.

**Klient saab taotluse tagasivõtta (taotlus jääb alles):**
1) Klient logib sisse või on sisse logitud.
2) Klient valib esitatud taotluste nimekirjast ühe taotluse.
3) Klient vajutab "vaata taotlust" nupu kõrval olevat nuppu: "võta tagasi".
4) Taotlus kaob esitatud taotluste nimekirjast.

**Klient saab olemasoleva taotluse kohta genereerida PDF'i:**
1) Klient logib sisse või on sisse logitud.
2) Klient valib esitatud taotluste nimekirjast ühe taotluse.
3) Klient vajutab nuppu "genereeri PDF".
4) Kliendile laetakse alla PDF fail, mis sisaldab taotluse sisu.