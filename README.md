# Erivajadustega lastele rakenduste disainimine

See repositoorium koondab valiku teadusartilite kokkuvõtteid ja viiteid tööriistadele ja rakendustele, mis aitavad luua rakendusi ja veebilehti lastele, kellel on erinevad erivajadused. Materjalid on varustatud eestikeelsete kokkuvõtete ja soovitustega, et toetada arendajaid, disainereid ja haridustöötajaid Eestis.

Repositoorium on loodud diplomitöö raames, mille eesmärk on tõsta teadlikkust, ligipääsetavusest, toetada kaasavat disaini ning teha rahvusvahelised ressursid kättesaadavaks eesti keeles.

## Disainipõhimõtted

Erivajadustega lastele disainides tuleks arvestada üldiste disainipõhimõtetega:

- **Selge, struktureeritud ja ennustatav liides**
Üks ülesanne korraga: igal ekraanivaatesel olgu konkreetne eesmärk.
Paigutus peab olema loogiline ja korduv – elemendid samades kohtades igas vaates.
Väldi visuaalset ülekoormust: animatsioonid, taustad, mustrid jms olgu miinimumini viidud.
Tekst olgu lühike, arusaadav ja toetatud visuaalidega.
Kõik tegevused peavad olema lihtsalt algatavad ja lõpuni viidavad.
- **Kohandatavus ja kasutajaprofiili tugi**
Võimalda isikupärastamist vastavalt lapse eale, oskustele ja meeleolule.
Profiilipõhine kohandamine: helitugevus, raskusaste, tempo, kontrastsus, tugiinfo.
Arendaja peab vältima valikuid, mis võivad viia kinnisideeni või lõputu kordamiseni.
Rakendused peavad toetama dünaamilist kohandumist – kasutaja ei pea sobituma süsteemiga.
- **Kognitiivse koormuse juhtimine**
Jagada tegevused väikesteks, juhendatud sammudeks.
Piirata ühe vaate infohulka, vältida valikute kuhjumist.
Aeglane ja rahulik visuaalne dünaamika toetab keskendumist.
- **Tagasiside: selge, juhendav, korduv**
Tagasiside olgu viivitamatu, nähtav ja arusaadav.
Kasuta helisid, visuaalseid muutusi (nt toon, animatsioon) ja sõnalist kinnitust.
Iga ebaõnnestumine peab avama uue katse, mitte karistust.
Korratavus tugevdab turvatunnet: sarnase tulemuse korral sarnane tagasiside.
- **Emotsionaalse turvatunde loomine**
Kujundus peab looma usaldusväärsust: tuttavad sümbolid, pehmed toonid, aeglane liikumine.
Heli peab olema kontrollitav ja algama vaikselt või kasutaja käsul.
Väldi visuaalseid üllatusi või äkilisi efekte.
Juhendamine ja toetavad vihjed loovad psühholoogilist mugavust.
- **Mängustamine, motivatsioon ja tähenduslik kordus**
Mänguelemendid suurendavad huvi: preemiad, tasemed, avatari kohandused.
Esimene edukas tegevus peaks tooma kohese eduelamuse.
Rakendus peab pakkuma varieeruvat raskust, võimaldades lapse arenguga kaasa minna.
Kordused olgu tähenduslikud ja loovad, mitte mehaanilised.
- **Universaalne disain ja WCAG lastesõbralik tõlgendus**
WCAG standardid on aluseks, kuid neid tuleb lapse arengu järgi kohandada.
Tekstiga peab alati kaasnema pilt või heli.
Navigeerimine peab toimima ka siis, kui laps ei oska lugeda või kirjutada.
Toetada tuleb kõiki sisestusviise (puuteekraan, pilguga juhtimine, hääl jne).
- **Kasutajakeskne disain ja terapeudi roll**
Arendus peab tuginema kasutajauuringutele ja spetsialistide koostööle.
Terapeudi roll ei tohi piirduda testimisega, vaid hõlmama ka arendusetappi.
Rakendused peavad olema tähenduslikud ka lapsevanema ja õpetaja jaoks.
- **Sisu mitmekesisus ja arenguline pidevus**
Visuaalsed ja interaktiivsed elemendid vajavad uuendamist, et vältida igavust.
Kujundus peab arenema koos lapsega – tasemepõhine sisu, uuenev välimus.
Avataride, värvide ja tegevuste varieerimine toetab motivatsiooni.
- **Kokkuvõte**
Disain, mis toetub lapse isiklikule kogemusele, tema arengule ja emotsionaalsele seisundile, loob keskkonna, kus tehnoloogia muutub partneriks, mitte barjääriks. Iga visuaal, iga heli ja iga liigutus peab toetama last, mitte väsitama teda. Hea rakendus ei ole mitte lihtsalt arusaadav, vaid kaasav, juhendav ja muutuv koos lapsega.


## Tööriistad ja rakendused

### 1. Ligipääsetavuse kontroll ja kohandamine

| **Tööriist** | **Kirjeldus** | **Link** |
|--------------|----------------|----------|
| **Pa11y** | Avatud lähtekoodiga tööriist, mis võimaldab automaatset WCAG testimist. Sobib pidevaks testimiseks CI/CD keskkonnas. | [pa11y.org](https://pa11y.org/) |
| **axe DevTools** | Laiendus, mis toob välja WCAG rikkumised koos konteksti ja parandussoovitustega. Toetab laste rakendustes ligipääsetavusvigade ennetamist. | [deque.com](https://www.deque.com/axe/devtools/) |
|**WAVE** | Visuaalne tagasiside ligipääsetavuse kohta (nt kontrastid, alternatiivtekstide puudumine). Lihtne kasutada ka ilma tehnilise taustata. | [wave.webaim.org](https://wave.webaim.org/) |
| **Accessibility Insights** | Microsofti tööriist, sobib kasutajavoo järkjärgulise testimiseks. | [accessibilityinsights.io](https://accessibilityinsights.io/) |
| **Color Contrast Analyzer** | Kontrollib teksti ja tausta kontrastsust vastavalt WCAG nõuetele. | [tpgi.com](https://www.tpgi.com/color-contrast-checker/) |
| **Google Lighthouse – Accessibility** | Chrome’i sisseehitatud tööriist ligipääsetavuse hindamiseks. Pakub automaatseid soovitusi ja skoori. Hea alus WCAG vastavuse esmaseks kontrolliks. | [developer.chrome.com](https://developer.chrome.com/docs/lighthouse/accessibility/scoring) |

---

### 2. Kommunikatsiooni ja sisu lihtsustamise tööriistad

| **Tööriist** | **Kirjeldus** | **Link** |
|--------------|----------------|----------|
| **ARASAAC** | Rahvusvaheliselt tuntud sümbolikogu alternatiivseks kommunikatsiooniks. Sisaldab üle 12 000 piktogrammi, mida saab kasutada suhtlusrakendustes ja visuaalse toe materjalides. Sobib suhtlustahvlite, tegevuskaartide ja juhendmaterjalide loomiseks. | [arasaac.org](https://arasaac.org/) |
| **Pictoselector** | Tasuta piktogrammide loomisvahend suhtlusrakenduste või ekraaniviidete tarbeks. | [pictoselector.eu](https://www.pictoselector.eu/) |
| **Boardmaker Online** | Standard haridusasutustes ja teraapiakeskustes visuaalsete õppematerjalide koostamiseks. | [goboardmaker.com](https://goboardmaker.com/) |
| **Widgit Online** | Lihttekstiga pildikaardid ja sümbolid. Sarnane Boardmakerile, fookus kergesti loetaval sõnal + pildil. | [widgitonline.com](https://widgitonline.com/) |
| **Sõnaklahv** | Eesti keele lihtsustamise tööriist, mis hindab keelekasutust ja aitab sisu kohandada. | [sonaklahv.ee](https://sonaklahv.ee/) |
| **Keeleabi** (EKI) | Õigekeelsuse ja lihtlausestuse kontroll eestikeelses sisus. | [keeleabi.eki.ee](https://keeleabi.eki.ee/) |

---

### 3. Sensoorse ja alternatiivse juhtimise testimiseks

| **Tööriist** | **Kirjeldus** | **Link** |
|--------------|----------------|----------|
| **Switch Access (Android Accessibility Suite)** | Võimaldab testida rakendust ilma puutetundliku ekraanita (lülitite ja klaviatuuriga). | [support.google.com](https://support.google.com/accessibility/android/answer/6122836) 
| **GazePointer** | Simuleerib pilguga juhtimist, et testida, kas UI on navigeeritav silmadega. | [sourceforge.net](https://sourceforge.net/projects/gazepointer/) |
| **Tobii Eye Tracker** | Professionaalne tööriist silmajälgimise analüüsiks laste testimisel. | [tobii.com](https://www.tobii.com/) |
| **VoiceOver (iOS)** | iOS-i sisseehitatud ekraanilugeja. Võimaldab testida kasutajaliidese navigeeritavust ja tekstide arusaadavust. | [apple.com](https://support.apple.com/guide/iphone/turn-on-and-practice-voiceover-iph3e2e415f/ios) |
| **TalkBack (Android)** | Androidi ekraanilugeja. Sobib rakenduse testimiseks olukorras, kus kasutaja ei saa visuaalset tuge kasutada. | [support.google.com](https://support.google.com/accessibility/android/answer/6283677) |

---

### 4. Visuaalid, ikoonid ja kujunduselementide allikad

| **Tööriist** | **Kirjeldus** | **Link** |
|--------------|----------------|----------|
| **OpenMoji** | Avatud emojide kogu, sobilik suure kontrastiga visuaalide loomiseks. | [openmoji.org](https://openmoji.org/) |
| **Noun Project – Accessibility & Kids** | Lai valik ikoone, sh ligipääsetavust ja lapsi puudutavad kategooriad. | [thenounproject.com](https://thenounproject.com/) |
| **CAST UDL Guidelines** | Universaalse õppe disaini printsiibid (sisuloome juhised visuaalse mitmekesisuse jaoks). | [udlguidelines.cast.org](https://udlguidelines.cast.org/) |

---

### 5. Multimeedia ja interaktiivne sisu

| **Tööriist** | **Kirjeldus** | **Link** |
|--------------|----------------|----------|
| **Book Creator** | Lastele suunatud visuaalsete lugude ja harjutuste loomiseks. | [bookcreator.com](https://bookcreator.com/) |
| **Voki** | Anima-avatari tööriist häälega sisu loomiseks. | [voki.com](https://www.voki.com/) |
| **Pictello** | Suhtluslugude ja sotsiaalsete juttude koostamine fotode ja häälega. | [assistiveware.com](https://www.assistiveware.com/products/pictello) |
| **CoughDrop** | Pilvepõhine AAC platvorm. Võimaldab luua, jagada ja kohandada suhtluslahendusi. | [coughdrop.com](https://www.coughdrop.com/) |
| **Proloquo2Go** | iOS-i põhine alternatiivne suhtlusrakendus – sobib viitamiseks disaini ja UX-lahenduste planeerimisel. | [assistiveware.com](https://www.assistiveware.com/products/proloquo2go) |

---
### 6. Liikumispõhiste rakenduste eeskujud

| **Tööriist** | **Kirjeldus** | **Link** |
|--------------|----------------|----------|
| **PhysiApp** | Harjutuste edastamiseks videopõhiselt. Sobib kasutajaliideste modelleerimiseks liikumispõhistes ja füsioteraapial põhinevates rakendustes. | [physiapp.com](https://www.physiapp.com/) |
| **MoveSpring** | Aktiivsuse jälgimise tööriist, millel on visuaalselt motiveeriv ja kaasav liides. Sobib eeskujuks liikumistegevuste ja sammupõhise UX-i disainimisel. | [movespring.com](https://movespring.com/) |

---

### 7. Üldised kasulikud tööriistad arenduse ja disaini toetuseks

| **Tööriist** | **Kirjeldus** | **Link** |
|--------------|----------------|----------|
| **Figma** | Prototüüpide ja liidestega testimiseks, võimaldab kergesti jagada lapsevanema või terapeudiga. | [figma.com](https://www.figma.com/) |
| **Balsamiq** | Madala detailsusega UI skeemide loomiseks varases faasis. | [balsamiq.com](https://balsamiq.com/) |
| **Miro** | Koostööplatvorm disainiprotsessi, persona loomise ja kasutajateekondade kaardistamiseks. | [miro.com](https://miro.com/) |
| **UserTesting / Hotjar** | Suunatud tagasiside ja interaktsioonide jälgimine (väldi isikuandmeid, kui kasutatakse lastega!). | [usertesting.com](https://www.usertesting.com/), [hotjar.com](https://www.hotjar.com/) |
| **Canva for Education** | Lihtsustatud visuaalne disainikeskkond. Sobib koostöös õpetajatega visuaalide loomiseks. | [canva.com/education](https://www.canva.com/education/) |
| **Boardmaker by Tobii Dynavox** | Sümbolil põhinevate suhtlusliideste (AAC) loomiseks. Sisaldab PCS-sümbolite kogu ja on laialt kasutatud eripedagoogikas. | [tobiidynavox.com](https://www.tobiidynavox.com/) |
| **Pictello** | Visuaalsete juhiste ja isikupärastatud õpetuslugude loomiseks. Toetab struktureeritud õpet ja alternatiivset kommunikatsiooni. | [assistiveware.com](https://www.assistiveware.com/products/pictello) |

---

### 8. Disainiraamistikud ja mõttekaardid

| **Tööriist** | **Kirjeldus** | **Link** |
|--------------|----------------|----------|
| **Microsoft Inclusive Design Toolkit** | Empaatiakaardid, kasutajaprofiilide ja barjääride kaardistamine. Aitab mõista, milliste funktsioonide või keskkonnatingimuste tõttu võib rakendus kasutajale raskesti ligipääsetav olla. Väga hea alus kaasava disaini planeerimiseks. | [inclusive.microsoft.design](https://inclusive.microsoft.design/) |

---

# Kasutajate ja spetsialistide kaasamine
Digirakenduste disainimisel erivajadustega laste jaoks ei piisa pelgalt ligipääsetavusest – tuleb aktiivselt kaasata lapsi ja vajadusel nende toetajaid kogu disainiprotsessi vältel. Erivajadustega lastele suunatud digilahenduste disainis on kasutajate ja valdkonna spetsialistide kaasamine kriitilise tähtsusega. Kaasamine aitab tagada, et loodav rakendus vastab sihtrühma tegelikele vajadustele ning toetab tõhusalt hariduslikke ja terapeutilisi eesmärke. Selline lähenemine toetub mitmete teadusartiklite ja teooriate soovitustele.

## Miks kaasamine on oluline?
- Lapsed ise ei pruugi osata või suuta oma vajadusi ja raskusi sõnastada – just seetõttu on oluline kaasata ka vanemad, õpetajad, terapeudid.
- Professionaalide kogemus aitab välja tuua nüansse, mida arendajad ei pruugi märgata (nt liigne stimulatsioon, raskesti tõlgendatav ikoon).
- Kaasav protsess suurendab kasutatavust ja usaldusväärsust, mis on eriti oluline sotsiaalsete või kognitiivsete raskustega kasutajate puhul.

### Valmistumine: looge alus usaldusel
- Suhelge hooldajate ja õpetajatega enne lapse kaasamist. Nad aitavad mõista lapse tugevusi, tundlikkust ja eelistusi.
- Vältige traditsioonilisi küsitlusi. Autistlikel lastel võib olla keeruline verbaalselt vastata. Kasutage selle asemel vaatlusi ja tegevuspõhiseid sissejuhatusi.
- Lapse eelvaatlus loomulikus keskkonnas (nt koolis või kodus) aitab disainimeeskonnal hinnata sobivaid töömeetodeid
- Kaasamise tööriistad ja võtted
- Valige tööriistad, mis võimaldavad lapse osalusel loomulikult tekkida:

### Visuaalsed skeemid – pildid, ikoonid, vooskeemid
- Madala tehnoloogiaga prototüübid – paberimängud, ehitusplokid, magnetid
- Digitaalsed visanditööriistad – joonistusäppid, kus laps saab kujundada tegelasi või stseene
- Rollimängud ja lugude jutustamine – toetavad empaatiat ja eneseväljendust
- Oluline: vältige tegevusi, mis nõuavad abstraktset mõtlemist või sotsiaalset survet. Toetage lapse enesetempot ja huvipakkuvaid valdkondi.

### Osalemise vormid
- Disainiprotsessis võib laps tegutseda:
  - Informandina – jagab oma eelistusi (nt valib ikoonid, animatsioonid)
  - Testijana – proovib erinevaid kujunduslahendusi (nt liides, helid)
  - Kaastöötajana – loob visuaalseid komponente või määrab stseeni järjekorra
  - Kui lapse vahetu osalus ei ole võimalik, kaasake proksid (lapsevanem, õpetaja), kes aitavad tõlgendada lapse huve.

### Järeltegevused
- Valideerige tulemused lapse või hooldaja kaudu. Näidake arendatud prototüüipe ja koguge visuaalse või tegevuspõhise tagasiside.
- Korrake vajadusel. Kaasamine ei ole ühekordne sündmus – kohandage kujundusi vastavalt saadud infole.

### Kaasamise kokkuvõte
Erivajadustega lastega seotud digilahenduste arenduses ei piisa ainult ligipääsetavuse kontrollist – oluline on mõista sihtrühma reaalseid vajadusi, mis ilmnevad koostöös laste ja nende ümber olevate täiskasvanutega. Kaasav arendusprotsess tagab suurema kasutatavuse, usalduse ning võimaldab arendada tõeliselt ligipääsetavaid ja mõjuvaid rakendusi.

## Testimine ja tagasiside erivajadustega kasutajatega
Testimine on oluline osa rakenduse arendustsüklist, kuid erivajadustega laste puhul peab see toimuma teadlikult ja tundlikult. Alljärgnevalt on toodud juhised ja soovitused, kuidas testida rakendust nii, et see arvestaks sihtrühma võimekuse ja piirangutega ning pakuks usaldusväärset tagasisidet.

### Miks on testimine erivajadustega lastega eriline?
- Paljud lapsed ei oska või ei saa anda verbaalset tagasisidet, seega on oluline koguda kaudset infot, näiteks jälgides nende käitumist rakenduse kasutamisel.
- Kasutajakogemus sõltub tihti tugevalt kontekstist, näiteks sellest, kas rakendust kasutatakse üksi, koos täiskasvanuga või rühmas.
- Tähelepanu- ja sensoorse koormuse taluvus on iga lapse puhul erinev, seetõttu tuleb jälgida ka selliseid reaktsioone nagu frustratsioon, segadus või ärevus.
- Funktsionaalsed probleemid ilmnevad sageli ainult reaalses kasutusolukorras, mitte formaalses testikeskkonnas.

### Testimise ettevalmistamine
- Selgitage lapse individuaalsed vajadused enne testimist, suheldes vanemate või õpetajatega.
- Valmistage ette turvaline ja stressivaba keskkond, kus laps saab testimises osaleda omas tempos.
- Vältige kõrge survega olukordi. Testimine peab toetama lapse loomuomast tegutsemist ilma liigsete juhisteta.
- Testimise võtted
- Efektiivne testimine peaks sisaldama mitmekesiseid ja paindlikke lähenemisi:

### Vaatlus – jälgige, kuidas laps loomulikult suhtleb rakendusega.
- Mängu kaudu testimine – laske lapsel uurida prototüüipe ja funktsioone mänguliselt, mitte struktureeritud ülesannetega.
- Hääletu vaatlus ja kaudne tagasiside – kui laps ei soovi verbaalselt suhelda, tuginege tema reaktsioonidele ja kehakeelele.

### Testimissessiooni struktuur
- Lühikesed ja paindlikud sessioonid. Pikk ja intensiivne testimine väsitab last kiiresti.
- Selged algus- ja lõpupunktid. Looge ülheselt mõistetavad signaalid, mis annavad lapsele teada, millal tegevus algab ja lõpeb.
- Valikuvabadus. Lase lapsel otsustada, milliseid funktsioone ta soovib proovida.

### Järelanalüüs ja parendused
- Dokumenteerige loomulikke reaktsioone, mitte ainult sõnalist tagasisidet.
- Kaasa hooldajad tulemuste tõlgendamisse, et vältida väärtõlgendusi.
- Korrake vajadusel testimist, et kinnitada muudatuste sobivust.

### Kokkuvõte
Testimine on oluline mitte ainult veatu rakenduse saavutamiseks, vaid eelkõige selleks, et mõista, kuidas laps tegelikult digikeskkonnas toimib. Vaatlus, lihtne tagasiside ja täiskasvanute tõlgendus moodustavad koos toimiva meetodi, mis aitab arendada rakendusi, mis on tõeliselt ligipääsetavad ja sobivad erinevate erivajadustega lastele.

## Artiklid
Siit leiad erivajadustega lastele disainimisele keskenduvate teadusartiklite põhjal koostatud praktilised kokkuvõtted, mis on suunatud arendajatele ja disaineritele, kes loovad digitaalseid rakendusi erivajadustega lastele.

- [Visuaalsete tööriistade ligipääsetav disain autismispektriga lastele - Zubair et al (2021)](https://tluhk.github.io/erivajadustega_lastele_suunatud_digirakenduste_arenduspohimotted/artikkel_zubair_2021.html)
- [UX-soovitused autismiga lastele - Abboud et al (2024)](https://tluhk.github.io/erivajadustega_lastele_suunatud_digirakenduste_arenduspohimotted/artikkel_abboud_2024.html)
- [Emotsionaalse kogemuse disain lasterakendustes - Chen (2022)](https://tluhk.github.io/erivajadustega_lastele_suunatud_digirakenduste_arenduspohimotted/artikkel_chen_2022.html)
- [Tehnoloogiapõhine pedagoogika ja motivatsioon - Bratu et al (2024)](https://tluhk.github.io/erivajadustega_lastele_suunatud_digirakenduste_arenduspohimotted/artikkel_bratu_2024.html)
- [Tarkvaradisaini kvaliteet ASD laste rakendustes - Chinchay et al (2024)](https://tluhk.github.io/erivajadustega_lastele_suunatud_digirakenduste_arenduspohimotted/artikkel_chinchay_2024.html)
- [UX-praktikad UDL raames intellektipuudega õpilastele – AlRawi ja AlKahtani (2022)](https://tluhk.github.io/erivajadustega_lastele_suunatud_digirakenduste_arenduspohimotted/artikkel_alrawi_2022.html)
- [Digitehnoloogia rakendamine erivajadustega laste õppes – Hongngam et al (2022)](https://tluhk.github.io/erivajadustega_lastele_suunatud_digirakenduste_arenduspohimotted/artikkel_hongngam_2022.html)
- [Autismisõbralik kasutajaliides – Kamaruzaman et al (2016)](https://tluhk.github.io/erivajadustega_lastele_suunatud_digirakenduste_arenduspohimotted/artikkel_kamaruzaman_2016.html)
- [Kasutajakeskne mHealth-rakendus Jooay – Shikako et al. (2021)](https://tluhk.github.io/erivajadustega_lastele_suunatud_digirakenduste_arenduspohimotted/artikkel_shikako_2021.html)
- [Mängustatud e-õppe rakenduste disain Downi sündroomiga lastele – Vieira et al. (2019)](https://tluhk.github.io/erivajadustega_lastele_suunatud_digirakenduste_arenduspohimotted/artikkel_vieira_2019.html)
- [Erivajaduste mõistmise raamistik arendusprotsessis – Florian et al. (2006)](https://tluhk.github.io/erivajadustega_lastele_suunatud_digirakenduste_arenduspohimotted/artikkel_florian_2006.html)
- [Digiplatvormid perede toetamiseks – Gruebner et al. (2022)](https://tluhk.github.io/erivajadustega_lastele_suunatud_digirakenduste_arenduspohimotted/artikkel_gruebner_2022.html)
- [Digitaalne lapsevanemlus erivajadustega laste peredes – Kumaş & Yildirim (2024)](https://tluhk.github.io/erivajadustega_lastele_suunatud_digirakenduste_arenduspohimotted/artikkel_kumas_2024.html)

---

## Panusta projekti

See GitHubi leht on loodud eesmärgiga koondada praktilisi soovitusi, tööriistu ja uurimuspõhiseid kokkuvõtteid, mis toetavad erivajadustega laste vajadusi arvestavate digilahenduste loomist. Kui soovid kaasa aidata, oled väga oodatud!

### Kuidas saad aidata hoida lehte ajakohasena ja kasulikuna?

### Lisa teadusartikli kokkuvõte
- Kui tead mõnda head teadusartiklit, mis toetab kaasavat disaini või ligipääsetavust erivajadustega laste digirakendustes, lisa sellest kokkuvõte `artiklid/` kausta.
- Kasuta sama formaati nagu olemasolevates failides.
- 
- Märgi kindlasti:
  - artikli autorid ja ilmumisaasta,
  - pealkiri kujul `# Teema – Autor (aasta)`,
  - sisuline kokkuvõte ainult artikli põhjal (ära lisa omi tõlgendusi!),
  - lisa allika viide lõppu.

### Soovita või uuenda tööriista infot
- Kui tead mõnda head tööriista, mis toetab ligipääsetavust, alternatiivset suhtlust, sensoorseid kohandusi või lihtsustatud sisu loomist – lisa see vastavasse sektsiooni `tooriistad.md`.
- Kasuta selget ja neutraalset kirjeldust, sobivaid linke ning vajadusel märgi, milleks see sobib.

### Esita parandus- või täiendusettepanekuid
- Kui märkad viga, soovid täpsustada mõistet või täiendada mõnd osa, saad teha seda GitHubis pull request'iga või luues issue.
- Kasuta võimalusel viiteid teadusartiklitele või usaldusväärsetele ligipääsetavuse allikatele.

## Soovituslik stiil ja eesmärk
- Kirjuta selgelt, neutraalselt ja praktiliselt – sihtgrupiks on arendajad ja disainerid, mitte teadlased.
- Eesmärk on luua rakendusi, mis on **põhjendatud, läbimõeldud ja sihtrühma tegelikke vajadusi arvestavad**.
- Iga panus, olgu väike või suur, aitab muuta digitaalmaailma kaasavamaks.

### Aitäh panustamast!
