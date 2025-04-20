---
title: "Tööriistad ja platvormid"
nav_order: 8
---

# Tööriistad ja platvormid erivajadustega lastele mõeldud rakenduste disainiks

Alljärgnev on kombineeritud ja ajakohastatud valik tööriistu, mis aitavad arendajatel ja disaineritel luua digirakendusi, mis on sobilikud erivajadustega lastele. Eelistatud on avatud lähtekoodiga, tasuta ja/või praktikas terapeutilises kontekstis kasutusel olevad lahendused.

---

## 1. Ligipääsetavuse kontroll ja kohandamine

### [Pa11y](https://pa11y.org/)
- Avatud lähtekoodiga tööriist, mis võimaldab automaatset WCAG testimist
- Sobib pidevaks testimiseks CI/CD keskkonnas

### [axe DevTools](https://www.deque.com/axe/devtools/)
- Laiendus, mis toob välja WCAG rikkumised koos konteksti ja parandussoovitustega
- Toetab laste rakendustes ligipääsetavusvigade ennetamist

### [WAVE](https://wave.webaim.org/)
- Visuaalne tagasiside ligipääsetavuse kohta (nt kontrastid, alternatiivtekstide puudumine)
- Lihtne kasutada ka ilma tehnilise taustata

### [Accessibility Insights](https://accessibilityinsights.io/)
- Microsofti tööriist, sobib kasutajavoo järkjärgulise testimiseks

### [Color Contrast Analyzer](https://www.tpgi.com/color-contrast-checker/)
- Abiks, kui kujunduses kasutatakse palju ikoonide ja taustade kombinatsioone

### [Google Lighthouse – Accessibility](https://developer.chrome.com/docs/lighthouse/accessibility/scoring)
- Chrome’i sisseehitatud tööriist ligipääsetavuse hindamiseks.
- Pakub automaatseid soovitusi ja ligipääsetavuse skoori.
- Hea alus WCAG vastavuse esmaseks kontrolliks.

---

## 1. Ligipääsetavuse kontroll ja kohandamine

| **Tööriist** | **Kirjeldus** | **Link** |
|--------------|----------------|----------|
| Pa11y | Avatud lähtekoodiga tööriist, mis võimaldab automaatset WCAG testimist. Sobib pidevaks testimiseks CI/CD keskkonnas. | [pa11y.org](https://pa11y.org/) |
| axe DevTools | Laiendus, mis toob välja WCAG rikkumised koos konteksti ja parandussoovitustega. Toetab laste rakendustes ligipääsetavusvigade ennetamist. | [deque.com](https://www.deque.com/axe/devtools/) |
| WAVE | Visuaalne tagasiside ligipääsetavuse kohta (nt kontrastid, alternatiivtekstide puudumine). Lihtne kasutada ka ilma tehnilise taustata. | [wave.webaim.org](https://wave.webaim.org/) |
| Accessibility Insights | Microsofti tööriist, sobib kasutajavoo järkjärgulise testimiseks. | [accessibilityinsights.io](https://accessibilityinsights.io/) |
| Color Contrast Analyzer | Kontrollib teksti ja tausta kontrastsust vastavalt WCAG nõuetele. | [tpgi.com](https://www.tpgi.com/color-contrast-checker/) |
| Google Lighthouse – Accessibility | Chrome’i sisseehitatud tööriist ligipääsetavuse hindamiseks. Pakub automaatseid soovitusi ja skoori. Hea alus WCAG vastavuse esmaseks kontrolliks. | [developer.chrome.com](https://developer.chrome.com/docs/lighthouse/accessibility/scoring) |



## 2. Kommunikatsiooni ja sisu lihtsustamise tööriistad

### [ARASAAC](https://www.arasaac.org/)
- Avatud sümbolipank (visuaalsed viited, tegevused, olukorrad)
- Toetab visuaalset planeerimist ja suhtlust erivajadustega kasutajaga

### [Pictoselector](https://www.pictoselector.eu/)
- Tasuta piktogrammide loomisvahend suhtlusrakenduste või ekraaniviidete tarbeks

### [Boardmaker Online](https://goboardmaker.com/)
- Standard haridusasutustes ja teraapiakeskustes visuaalsete õppematerjalide koostamiseks

### [Widgit Online](https://widgitonline.com/)
- Sarnane Boardmakerile, fookus kergesti loetaval sõnal + pildil

### [Sõnaklahv](https://sonaklahv.ee/)
- Eesti keele lihtsustamise tööriist, mis hindab keelekasutust ja aitab sisu kohandada

### [Keeleabi (EKI)](https://keeleabi.eki.ee/)
- Õigekeelsuse ja lihtlausestuse kontroll eestikeelses sisus

### [ARASAAC](https://arasaac.org/)
- Rahvusvaheliselt tuntud sümbolikogu alternatiivseks kommunikatsiooniks.
- Sisaldab üle 12 000 piktogrammi, mida saab kasutada suhtlusrakendustes ja visuaalse toe materjalides.
- Sobib suhtlustahvlite, tegevuskaartide ja juhendmaterjalide loomiseks.


---

## 3. Sensoorse ja alternatiivse juhtimise testimiseks

### [Switch Access (Android Accessibility Suite)](https://support.google.com/accessibility/android/answer/6122836)
- Võimaldab testida rakendust ilma puutetundliku ekraanita (lülitite ja klaviatuuriga)

### [GazePointer](https://sourceforge.net/projects/gazepointer/)
- Simuleerib pilguga juhtimist, et testida, kas UI on navigeeritav silmadega

### [Tobii Eye Tracker (UX analüüsiks)](https://www.tobii.com/)
- Professionaalne tööriist silmajälgimise analüüsiks laste testimisel

### [VoiceOver (iOS)](https://support.apple.com/guide/iphone/turn-on-and-practice-voiceover-iph3e2e415f/ios)
- iOS-i sisseehitatud ekraanilugeja.
- Võimaldab testida kasutajaliidese navigeeritavust ja tekstide arusaadavust.

### [TalkBack (Android)](https://support.google.com/accessibility/android/answer/6283677)
- Androidi ekraanilugeja.
- Sobib rakenduse testimiseks olukorras, kus kasutaja ei saa visuaalset tuge kasutada.


---

## 4. Visuaalid, ikoonid ja kujunduselementide allikad

### [OpenMoji](https://openmoji.org/)
- Avatud emojide kogu, sobilik suure kontrastiga visuaalide loomiseks

### [Noun Project – Accessibility & Kids](https://thenounproject.com/)
- Lai valik ikoone, sh ligipääsetavust ja lapsi puudutavad kategooriad

### [CAST UDL Guidelines](https://udlguidelines.cast.org/)
- Universaalse õppe disaini printsiibid (sisuloome juhised visuaalse mitmekesisuse jaoks)

---

## 5. Multimeedia ja interaktiivne sisu

### [Book Creator](https://bookcreator.com/)
- Lastele suunatud visuaalsete lugude ja harjutuste loomiseks

### [Voki](https://www.voki.com/)
- Anima-avatari tööriist häälega sisu loomiseks

### [Pictello](https://www.assistiveware.com/products/pictello)
- Suhtluslugude ja sotsiaalsete juttude koostamine fotode ja häälega

### [CoughDrop](https://www.coughdrop.com/)
- Pilvepõhine AAC platvorm. Võimaldab luua, jagada ja kohandada suhtluslahendusi

### [Proloquo2Go](https://www.assistiveware.com/products/proloquo2go)
- 	iOS-i põhine alternatiivne suhtlusrakendus – sobib viitamiseks disaini ja UX-lahenduste planeerimisel
---

## 6. Üldised kasulikud tööriistad arenduse ja disaini toetuseks

### [Figma](https://www.figma.com/)
- Prototüüpide ja liidestega testimiseks, võimaldab kergesti jagada lapsevanema või terapeudiga

### [Balsamiq](https://balsamiq.com/)
- Madala detailsusega UI skeemide loomiseks varases faasis

### [Miro](https://miro.com/)
- Koostööplatvorm disainiprotsessi, persona loomise ja kasutajateekondade kaardistamiseks

### [UserTesting / Hotjar (ettevaatlikult)](https://www.usertesting.com/, https://www.hotjar.com/)
- Suunatud tagasiside ja interaktsioonide jälgimine (väldi isikuandmeid, kui kasutatakse lastega!)

### [Canva for Education](https://www.canva.com/education/)
- Lihtsustatud visuaalne disainikeskkond.
- Sobib koostöös õpetajatega visuaalide loomiseks.

### [Boardmaker by Tobii Dynavox](https://www.tobiidynavox.com/)
- Sümbolil põhinevate suhtlusliideste (AAC) loomiseks.
- Sisaldab PCS-sümbolite kogu ja on laialt kasutatud eripedagoogikas.

### [Pictello](https://www.assistiveware.com/products/pictello)
- Visuaalsete juhiste ja isikupärastatud õpetuslugude loomiseks.
- Toetab struktureeritud õpet ja alternatiivset kommunikatsiooni.

## 7. Liikumispõhiste rakenduste eeskujud

### [PhysiApp](https://www.physiapp.com/)
- Harjutuste edastamiseks videopõhiselt.
- Sobib kasutajaliideste modelleerimiseks liikumispõhistes ja füsioteraapial põhinevates rakendustes.

### [MoveSpring](https://movespring.com/)
- Aktiivsuse jälgimise tööriist, millel on visuaalselt motiveeriv ja kaasav liides.
- Sobib eeskujuks liikumistegevuste ja sammupõhise UX-i disainimisel.

## 8. Disainiraamistikud ja mõttekaardid

### [Microsoft Inclusive Design Toolkit](https://inclusive.microsoft.design/)
- Empaatiakaardid, kasutajaprofiilide ja barjääride kaardistamine.
- Aitab mõista, milliste funktsioonide või keskkonnatingimuste tõttu võib rakendus kasutajale raskesti ligipääsetav olla.
- Väga hea alus kaasava disaini planeerimiseks.

---

## Kokkuvõte

Erivajadustega lastele suunatud rakenduste loomisel tuleb toetuda spetsiifilistele tööriistadele, mis võimaldavad arvestada kognitiivsete, sensoorsete ja kommunikatiivsete vajadustega. Eelistada tuleks avatud, paindlikke ja praktikas järele proovitud vahendeid, mis sobivad kasutamiseks koos terapeudi, lapsevanema ja lapse endaga.
