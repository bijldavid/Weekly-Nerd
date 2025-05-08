# **Weekly Nerd** <br> <sub><sup>David Bijl</sup></sub>


## Week 1
**<sub><sup>3 t/m 7 feb</sup></sub>**

---

## <mark><samp>--- The rule of least power ~ **<sub><sup>Kilian Valkhof</sup></sub>** ---</samp></mark>
<br>

Idee: gebruik de **minst krachtige taal/structuur** die nog steeds doet wat je wil

<br>

**Waarom dit belangrijk is:**
Minder krachtige talen zijn:
- makkelijker te lezen
- beter voor toegankelijkheid
- eenvoudiger te hergebruiken / doorzoeken<br>

→ Hoe krachtiger de taal, hoe groter de kans dat je dingen moeilijker maakt dan nodig

<br>

**Voorbeeld:**
`<p>This is a paragraph</p>` → simpel, duidelijk
vs. een `div` met JS → complex, slechter voor screenreaders en onderhoud

<br>

**Toepassing op het web:**
Veel websites gebruiken JS waar dat niet nodig is  
→ Bijvoorbeeld: `<button onClick="window.location = 'url'">Link</button>`  
→ Beter: `<a href="url">Link</a>`

<br>

**Vuistregel:**
**HTML > CSS > JS**
  - Probeer altijd eerst met HTML
  - Alleen als het niet anders kan: CSS
  - JS pas als laatste redmiddel

<br>

**Valkuilen:**
Veel devs gebruiken meteen JS of frameworks, terwijl een simpele HTML-oplossing vaak beter is

<br>

**Toegankelijkheid:**
Minder krachtige oplossingen zijn meestal beter leesbaar voor screenreaders  
→ Ook beter voor SEO, prestaties, en onderhoud

<br>

> "Use the least powerful language suitable for a given purpose"


<br>
<br>
<br>


## Week 2
**<sub><sup>10 t/m 14 feb</sup></sub>**

---

❌ Geen spreker

<br>
<br>
<br>


## ~~Week 3~~ - <sub><sup>Voorjaarsvakantie</sub></sup>
**<sub><sup>17 t/m 21 feb</sup></sub>**

---

❌ Vakantie

<br>
<br>
<br>


## Week 4
**<sub><sup>24 t/m 28 feb</sup></sub>**

---

## <mark><samp>--- Betalen voor het web ~ **<sub><sup>Peter-Paul Koch</sup></sub>** ---</samp></mark>

**Probleem**  
Sites zijn ‘gratis’ omdat advertenties betalen  
→ Gevolg: tracking, datalekken, ads, slechte UX  
→ Iedereen klaagt over privacy, niemand over geld geven aan sites

<br>

**Zijn idee**  
Geef zelf geld aan sites die je goed vindt  
→ Denk aan 5-20 cent per dag per site  
→ Kleine betalingen = digitale dankbaarheid  
→ Betere content, gezondere webcultuur

<br>

**Waarom ads slecht zijn**  
→ Aandacht = geld → makers gaan voor kliks, niet voor kwaliteit  
→ Design & UX worden ondergeschikt aan winst

<br>

**Web Monetization = alternatief**  
- Browser ziet een `monetization` tag  
- Betaling start automatisch via wallet  
- Zolang je actief bent, krijgt de site geld

<br>

**Samenvatting**  
→ Nu bepaalt site hoeveel iets kost  
→ Alternatief: jij bepaalt wat content waard is  

>"Betaal voor wat je leest, anders lees je alleen wat de rijken willen dat je leest."

<br>
<br>
<br>


## Week 5
**<sub><sup>3 t/m 7 mar</sup></sub>**

---

## <mark><samp>--- Typography ~ **<sub><sup>Roel Nieskens</sup></sub>** ---</samp></mark>
<br>

**Wat zijn fonts eigenlijk?**  
Een font is een bestand dat beschrijft hoe letters eruitzien.  
→ Het verschil tussen een **typeface** en een **font**:  
  - Typeface = het ontwerp  
  - Font = de technische uitvoering van dat ontwerp (de file dus)

<br>

**Glyphs:**  
Een glyph is een visuele representatie van een karakter.  
Bijv. de hoofdletter *A* in cursief is een andere glyph dan een gewone A  
→ één karakter kan dus meerdere glyphs hebben (handig voor opmaak)

<br>

**Ligatures:**  
Samengevoegde tekens, zoals `ﬁ`, `ﬂ`, `æ`  
→ om visueel lelijke combinaties te fixen  
→ sommige fonts hebben ook "discretionary ligatures" (meer voor stijl dan noodzaak)

<br>

**Kerning:**  
Letterspatiëring tussen specifieke paren  
→ zorgt dat letters niet raar ver uit elkaar of te dicht op elkaar staan  
→ bijv. AV of WA ziet er zonder kerning best lelijk uit

<br>

**Layout features (OpenType magic):**  
Veel fonts ondersteunen verborgen typografische functies:
- **Fractions** → bijv. ½ i.p.v. 1/2  
- **Stylistic Sets** → alternatieve glyphs met een andere stijl  
- **Access All Alternates** → zelf glyphs kiezen  
- **Tabular Figures** → cijfers met gelijke breedte (handig bij kolommen)  
- **Oldstyle Figures** → cijfers met wisselende hoogte, vloeien beter mee in tekst  
- **Small Caps, Superscript, Subscript** → vaak gewoon ingebouwd

<br>

**Swoopy stuff:**  
Decoratieve elementen zoals sierlijke swashes bij hoofdletters  
→ meestal onderdeel van stylistic sets  
→ niet functioneel, maar wel mooi als je ‘t subtiel gebruikt

<br>

**OpenType:**  
Font-formaat dat al die extra features ondersteunt  
→ wordt breed ondersteund in moderne browsers  
→ maakt typografie op het web veel krachtiger (als je weet waar je het kunt aanzetten)

<br>

**Variable Fonts:**  
Eén enkel fontbestand met meerdere stijlen (bijv. gewicht, breedte, schuinheid)  
→ maakt aparte bold/italic/etc. bestanden overbodig  
→ lichter voor de browser én meer controle voor de ontwerper

<br>

Handige tool: https://wakamaifondue.com/<br>
**<sub><sup>Gemaakt door: Roel Nieskens</sup></sub>**

<br>
<br>
<br>

<hr>

## <mark><samp>--- Beyond Tweening ~ **<sub><sup>Cassie Evans</sup></sub>** ---</samp></mark>
<br>

**Wat is tweening?**  
Tweening (inbetweening) is het automatisch genereren van tussenliggende frames tussen twee keyframes.  
→ In code: je definieert een begin- en eindstaat, en de computer vult de rest in.

<br>

**quickSetter()**  
Soort snelweg om direct een CSS-eigenschap aan te passen  
→ goed voor dingen die vaak veranderen, zoals muis of scroll

<br>

**utils**  
Verzameling handige tools in gsap (om dingen korter/simpeler te schrijven)

- **utils.random()**  
Geeft elke keer een willekeurig getal (bijv. tussen 0 en 100)

- **utils.wrap()**  
Zorgt dat een waarde “rondloopt” (bijv. 370° wordt weer 10°)  
→ handig bij rotaties of carrousels

- **utils.pipe()**  
Plakt meerdere functies achter elkaar → output van de ene is input voor de volgende  
→ handig als je dingen wil combineren (bijv. afronden + beperken tot max)

<br>

**matchMedia()**  
Laat je verschillende animaties maken voor mobiel vs. desktop  
→ beetje zoals media queries maar dan in JS

<br>

**Control methods (zoals `.pause()`, `.resume()`, `.reverse()`, `.restart()` etc.)**  
Hiermee kun je een animatie stoppen, verder laten gaan, omkeren of opnieuw afspelen  
→ je kunt dus zelf bepalen *wanneer* iets beweegt, niet alleen *hoe*

<br>

**Helper functions (zoals `.to()`, `.from()`, `.fromTo()`)**  
Standaard GSAP functies om dingen te animeren  
→ `.to()` = ga naar bepaalde waarde  
→ `.from()` = begin vanaf die waarde  
→ `.fromTo()` = begin op X en ga naar Y


<br>
<br>
<br>


## Week 6
**<sub><sup>10 t/m 14 mar</sup></sub>**

---

## <mark><samp>--- Design for Flexibility ~ **<sub><sup>Nils Binder</sup></sub>** ---</samp></mark>
<br>

**Flexibel ontwerpen = ontwerpen voor verandering**  
In plaats van alles pixel-perfect vastzetten, ruimte laten voor groei, aanpassing en responsiviteit

<br>

**CSS-evolutie: van vaste breedtes naar dynamische wrappers**  
→ Oude aanpak: vaste `max-width`, vaste `margin`, vaste `padding`  
→ Nieuwe aanpak: gebruik van `min()`, `max()`, `clamp()` en `margin-inline` voor flexibele layouts

```css
  .wrapper {
    width: min(100% - 3rem, 75rem);
    margin-inline: auto;
  }
```

<br>

**Figma en CSS: dezelfde taal spreken**  
- Figma gebruikt units als px, %, rem
- CSS heeft extra units: em, ch, ex, vw, vh, vmin, vmax<br>

→ Consistent gebruik van units zorgt voor betere samenwerking tussen design en development

<br>

**Whitespace is geen verspilde ruimte**  
Strategisch gebruik van witruimte verbetert leesbaarheid en esthetiek  

<br>

**Responsieve eenheden in CSS**
- `vw`, `vh`, `vmin`, `vmax`: gebaseerd op viewport-afmetingen
- `qh`, `qw`, `qi`, `qb`, `qmin`, `qmax`: gebaseerd op container-afmetingen<br>

→ deze units maken het mogelijk om layouts te ontwerpen die zich aanpassen aan verschillende schermgroottes en resoluties

<br>
<br>
<br>

<hr>

## <mark><samp>--- Imperative vs. Declarative Design ~ **<sub><sup>Jeremy Keith</sup></sub>** ---</samp></mark>
<br>

**Imperative programming**  
Je beschrijft stap voor stap wat de computer moet doen  
→ bijv. in JS: arrays maken, loops schrijven, if/else gebruiken  
→ veel controle, maar ook meer kans op fouten

<br>

**Declarative programming**  
Je beschrijft wat je wilt bereiken, niet hoe  
→ bijv. in HTML/CSS: je zegt wat iets is of hoe het eruit moet zien  
→ browser regelt de details

<br>

**Voorbeelden op het web:**  
- HTML = declaratief → je zegt: “dit is een knop”  
- CSS = declaratief → je zegt: “maak dit rood”  
- JS = imperatief → je zegt: “voeg deze class toe als er geklikt wordt”

<br>

**Mindset:**  
Declaratief = browser vertrouwen, minder controle maar meer veerkracht  
Imperatief = alles zelf regelen, meer controle maar ook meer verantwoordelijkheid

<br>

**Design systemen:**  
- Imperatief: focus op exacte uitkomsten (precies deze knop, precies deze kleur)  
- Declaratief: focus op regels en systemen (bijv. “hoverkleur is altijd 5% donkerder”)<br>

→ makkelijker schaalbaar en aanpasbaar

<br>
<br>
<br>

## Week 7
**<sub><sup>17 t/m 21 mar</sup></sub>**

---

## <mark><samp>--- CSS Character Animations ~ **<sub><sup>Julia Miocene</sup></sub>** ---</samp></mark>
<br>

**CSS = niet alleen styling, maar ook tekenen en animeren**  
Julia maakt complete tekeningen en animaties met alleen CSS   
→ Geen JS, geen SVG, alleen `div`s, `::before`, `::after`, `transform`, `position`, etc.

<br>

**Alles is een `div`:**  
bijv. een hoofd is een `div`, met daarin twee ogen (`div`s), met daarin pupillen (`div`s)  
→ alles wordt gepositioneerd met `position: absolute` binnen een relatief gepositioneerde ouder

<br>

**`transform-origin` = scharnierpunt:**  
Bepaalt waar een element draait of schaalt  
→ bijv. transform-origin: bottom center; laat iets draaien vanaf de onderkant  
→ handig voor armen, benen, wijzers, enz.

<br>

CSS features die ze gebruikt:  
- `::before` en `::after` pseudo-elementen
- `transform`, `rotate`, `scale`, enz.
- `position: absolute` en `relative` voor layout
- `transform-origin` voor animatie-assen
- `clip-path`, `border-radius`, `gradients` voor vormen

<br>
<br>
<br>


## Week 8
**<sub><sup>24 t/m 28 mar</sup></sub>**

---

❌ Hackathon

<br>
<br>
<br>


## Week 9
**<sub><sup>31 t/m 4 apr</sup></sub>**

---

## <mark><samp>--- Circuit Bending ~ **<sub><sup>Rosa</sup></sub>** ---</mark></samp>
<br>

**Over Rosa**  
→ Technische maker & hacker, ex-CMD  
→ Doet veel met e-waste, livesets, workshops en hacklabs  
→ Alles wat ze bedenkt, wilt ze zelf maken

<br>

**Hacker-mindset**  
→ Zelf CMS bouwen, eigen servers draaien, los van grote platforms  
→ Platform-agnostisch = geen voorkeur voor merken of systemen

<br>

**DIY mentaliteit**  
→ Zelf doen, zelf slopen, zelf leren  
→ Onafhankelijk kunnen bouwen, denken & maken

<br>

**Tools die ze gebruikt**  
- **ImageMagick** → photoshop via de terminal  
- **Bash** → automatiseren & bewerken via command-line  
- **Audio hacking** → met kabels/mixers gek geluid maken (bewust rauw)

<br>
<br>
<br>

<hr>

## <mark><samp>--- Anchor Positioning ~ **<sub><sup>Sanne t' Hooft</sup></sub>** ---</mark></samp>
<br>

**Wat is het?**  
Nieuwe CSS manier om iets te positioneren **tov een ander element** (niet meer alleen tov parent)  
→ handig voor dingen als tooltips, dropdowns, floating buttons

<br>

**Waarom handig?**  
Voorheen moest je JS gebruiken om bv. een tooltip goed onder een knop te zetten  
→ nu kan dat gewoon met CSS

<br>

**Hoe werkt het?**

1. geef een element een `anchor-name`:

```css
.button {
  anchor-name: --btn;
}
```

2. gebruik dat anchor bij een ander element om positie op te baseren:

```css
.tooltip {
  position: absolute;
  top: anchor(--btn bottom);
  left: anchor(--btn left);
}
```

→ tooltip wordt dan gepositioneerd aan onderkant van de knop

<br>

Andere dingen die je kunt doen:
- block-start, inline-end, enz. werken ook
- handig bij vertical vs horizontal schrijven
- kan ook met inset, right, bottom enz.

<br>

**Fallbacks als er geen ruimte is (@position-fallback)**
→ voorbeeld: dropdown past niet boven knop, dan maar onder:
```css
@position-fallback {
  @try {
    top: anchor(--btn bottom);
  }
  @try {
    bottom: anchor(--btn top);
  }
}
```

<br>

**Browser support:**  
→ alleen in Chrome (met flag aan) en in de toekmost ook in andere browsers

<br>
<br>
<br>


## Week 10
**<sub><sup>7 t/m 11 apr</sup></sub>**

---

## <mark><samp>--- Receipt Printers 101 ~ **<sub><sup>Niels Leenheer</sup></sub>** ---</samp></mark>
<br>

**Wat zijn receipt printers?**  
Printers die kassabonnen printen, vaak via USB, serieel, netwerk of Bluetooth.  
→ Gebruiken meestal ESC/POS-taal (van Epson) of StarPRNT (van Star).  
→ ESC/POS = oude printertaal met escape-codes voor opmaak (zoals bold, underline).

<br>

**Printertalen:**  
- **ESC/POS**: standaardtaal voor veel printers, gebruikt ASCII + escape-codes.  
- **StarPRNT**: eigen taal van Star-printers, niet compatibel met ESC/POS, tenzij handmatig ingesteld.

<br>

**Libraries van Niels:**  
**ReceiptPrinterEncoder**: maakt ESC/POS- of StarPRNT-commando's aan.  
- Kan tekst, stijlen, tabellen, barcodes, QR-codes en afbeeldingen toevoegen.  
- Combineert eerdere libraries (EscPosEncoder en StarPrntEncoder) in één.

<br>

**Data versturen naar de printer:**  
Printers kunnen verbonden zijn via USB, serieel, netwerk of Bluetooth.  
Browser-gebaseerd printen vereist specifieke API's:
- **WebUSB**: voor USB-printers (werkt niet op Windows zonder workaround).
- **WebSerial**: voor seriële verbindingen of virtuele seriële poorten.
- **WebBluetooth**: alleen voor Bluetooth Low Energy-apparaten.

<br>

**Printen vanuit de browser:**  
Vereist een Chromium-gebaseerde browser.  
→ Beperkingen: Netwerkprinters kunnen niet direct benaderd worden vanuit de browser vanwege beveiligingsredenen.

<br>

**Printen vanaf de server (Node.js):**  
- **NetworkReceiptPrinter**: voor netwerkprinters.  
- **SystemReceiptPrinter**: gebruikt het systeemprinterstuurprogramma, ongeacht de verbindingsmethode.

<br>
<br>
<br>


## Week 11
**<sub><sup>14 t/m 18 apr</sup></sub>**

---

## <mark><samp>--- Accessibility & Semantiek ~ **<sub><sup>Erik Kroes</sup></sub>** ---</samp></mark>
<br>

**Wat is accessibility**  
Het gaat erom dat iedereen je site kan gebruiken, ook mensen met een beperking  
→ Het is niet "wel of niet toegankelijk", je kunt altijd iets verbeteren  
→ Kleine dingen maken al verschil

<br>

**Hoe zorg je dat iets toegankelijk is?**  
- Gebruik gewoon goede HTML (dus `<button>`, `<a>`, `<section>`, etc.)  
- Let op kleurcontrast  
- Gebruik niet teveel rare ARIA-rollen als het niet hoeft  
- Test ook met screenreader of mensen zelf, niet alleen met tools

<br>

**Waar heeft Erik gewerkt?**  
ING, IKEA, WeTransfer, etc.  
→ Werkt nu als freelancer bij grote bedrijven

<br>

**Tekstgrootte en headings**  
- Begin met `<h1>`, daarna `<h2>`, enz. → geen levels overslaan  
- Maakt het duidelijker voor screenreaders  
- Gebruik `rem` voor schaalbare tekst i.p.v. `px`

<br>

**Welke HTML-tags moet je gebruiken?**  
- Gebruik semantische tags: `<nav>`, `<main>`, `<article>`, `<footer>`, enz.  
- Geen `div` of `span` gebruiken als je iets beters hebt  
- Goed voor toegankelijkheid én SEO

<br>

**Kleurcontrast**  
- Tekst moet goed leesbaar zijn tegen de achtergrond  
- Check contrast met een tool (WCAG regels)

<br>

**Buttons vs. links**  
- `<button>` = voor acties (bijv. iets openen, iets versturen)  
- `<a>` = voor navigatie (naar andere pagina of plek op de pagina)  
- Niet door elkaar halen, dat is verwarrend

<br>
<br>
<br>

<hr>

## <mark><samp>--- Thinking Outside of the Accessibility Box ~ **<sub><sup>Nienke de Keijzer</sup></sub>** ---</samp></mark>
<br>

**Over het project:**  
Nienke onderzocht de toegankelijkheid van de GVB-app als afstudeerproject bij CMD.  
→ Ze ontdekte dat de app niet goed bruikbaar was voor mensen met een beperking.  
→ Ze ontwierp een nieuwe versie van de app met toegankelijkheid als uitgangspunt.  
→ GVB was zo onder de indruk dat ze haar aanbevelingen hebben overgenomen en haar hebben aangenomen.

<br>

**Belangrijkste inzichten:**  
- Toegankelijkheid gaat verder dan alleen voldoen aan regels; het draait om echte bruikbaarheid voor iedereen.  
- Door gebruikers met beperkingen te betrekken bij het ontwerp, krijg je waardevolle feedback.  
- Kleine aanpassingen kunnen een groot verschil maken in gebruiksvriendelijkheid.

<br>

**Aanbevelingen voor ontwerpers:**  
- Begin met toegankelijkheid in gedachten, niet als bijzaak.  
- Test je ontwerpen met diverse gebruikersgroepen.  
- Maak gebruik van semantische HTML en zorg voor voldoende kleurcontrast.  
- Zorg voor duidelijke navigatie en leesbare tekstgroottes.

<br>
<br>
<br>


## ~~Week 12~~ - <sub><sup>Meivakantie</sub></sup>
**<sub><sup>28 t/m 2 mei</sup></sub>**

---

❌ Vakantie

<br>
<br>
<br>








## Doelen

---
## <mark><samp>**<sup><sub>Doel 1</sup></sub>** | Complexere javascript schrijven</samp></mark>

Ik wil graag beter worden in JavaScript. Ik denk dat ik de basis redelijk goed begrijp, maar ik vind het nog lastig om wat complexere dingen zelf te bouwen. Het lijkt me een handige skill om onder de knie te krijgen.

## <mark><samp>**<sup><sub>Doel 2</sup></sub>** | Minder snel AI gebruiken tijdens projecten</samp></mark>

Dit doel hangt best goed samen met mijn eerste doel. Ik ben vaak te veel gefocust op het eindresultaat, en dan gebruik ik AI om dingen op te lossen die ik eigenlijk zelf zou moeten leren. Daardoor leer ik het uiteindelijk niet echt goed.

## <mark><samp>**<sup><sub>Doel 3</sup></sub>** | Niet automatisch akkoord gaan met ideeën van andere</samp></mark>

Ik vind mezelf niet super sterk in conceptueel denken. In een groep laat ik het daarom vaak aan anderen over. Ik ga soms te snel akkoord met ideeën, ook als ik eigenlijk denk dat ze niet zo goed zijn. Ik wil leren om vaker mijn mening te geven.
