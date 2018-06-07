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
---

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
---

## Admini funktsionaalsuse Use Case'id:

**Admin saab näha kõiki taotlusi ning soovitud taotluse kohta genereerida PDF'i:**
1) Admin logib sisse.
2) Admin edastatakse pealehele, kus on näha kõik taotlused.
3) Admin valib ühe taotluse ja vajutab selle kõrval olevat nuppu "genereeri PDF".

**Admin saab taotluste märkuste lahtrit täita:**
1) Admin valib ühe taotluse
2) Admin avab selle detail vaates ning täidab selle väärtuste lahtri.
3) Admin vajutab nuppu salvesta.

**Admin saab filtreerida taotlusi:**
1) Admin sisestab pealehel filtri välja väärtuse mille järgi taotluste nimekirja filtreeritakse.

**Admin saab iga taotluse kohta genereerida kas positiivse või negatiivse otsuse:**
1) Admin valib pealehelt ühe taotluse.
2) Admin avab selle detail vaates.
3) Admin vajutab kas positiivse või negatiivse otsuse nuppu.

**Admin saab genereerida taotleja nime, projekti nime ja taoteldavat summat sisaldava väljavõtte:**
1) Admin valib pealehelt ühe taotluse.
2) Admin avab selle detail vaates.
3) Admin vajutab väljavõtte genereerimise nuppu.