---
title: "Passive danske fonde: Liste over danske investeringsforeninger (2026)"
redirect_from:
  - /danske-inveseringsforeninger-med-passive-indeksfonde/
permalink: /danske-investeringsforeninger-med-passive-indeksfonde/
seo_title: "Passive investeringsforeninger • Danske indeksfonde i 2026"
description: "Se den opdaterede liste med de bedste passive, danske investeringsforeninger. Sammenligning af omkostninger (ÅOP), benchmark og skat på danske indeksfonde."
excerpt: "Leder du efter de bedste danske passive investeringsforeninger? Her er det komplette overblik over passive globale indeksfonde i Danmark opdelt på skat og omkostninger."
category:
  - Investering
tags:
  - investeringsforeninger
  - passiv investering
  - værdipapirer
  - indeksfonde
header:
  overlay_image: https://images.unsplash.com/photo-1511376868136-742c0de8c9a8?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&h=600&w=1200&q=10
  teaser: https://images.unsplash.com/photo-1511376868136-742c0de8c9a8?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&h=300&w=400&q=10
  caption: "Passive danske fonde: Liste over danske investeringsforeninger"
last_modified_at: 2026-07-04T12:45:00+02:00
---

Jeg er meget interesseret i at finde de bedste danske passive investeringsforeninger. Fordi det kan være lidt af en jungle at få det fulde overblik over markedet i Danmark, har jeg sat mig for at lave den ultimative, strukturerede liste over de mest populære passive indeksfonde.

Når du vælger danske investeringsforeninger frem for udenlandske ETF'er, skyldes det i 9 ud af 10 tilfælde de særlige danske skatteregler for frie midler. Men hvilke fonde findes der, hvad koster de i ÅOP, og hvilke passer til netop din strategi? Det kigger vi på her.

---

## Sådan finder du passive fonde på Nordnet

Hvis du er kunde hos Nordnet, kan du med fordel bruge deres indbyggede screeningsværktøj til fonde. Ved at filtrere efter "Investeringsforeninger" og vælge forvaltningstypen "Indeks", kan du hurtigt skære de dyre, aktive fonde fra.

{% include figure image_path="/assets/images/nordnet-passiv-indeksfond.png" caption="Søger du specifikt efter investeringsforeninger med indeksforvaltning på Nordnet, dukker der i dag et bredt udvalg op fra udbydere som Sparindex, Danske Invest og Nordea Invest." alt="passiv investeringsforeninger med indeksfonde" %}

Da jeg foretrækker en helt enkel, passiv investeringsstrategi, der følger hele verden, har jeg skåret listen yderligere til, så den udelukkende viser de **globale passive indeksfonde**.

{% include figure image_path="/assets/images/nordnet-passiv-global-indeksfond.png" caption="Filtrerer du udelukkende efter globale aktier, indsnævres feltet til de mest relevante kernefonde for den langsigtede investor." alt="passiv investeringsforeninger med indeksfonde" %}

---

## Det store valg: Udbyttebetalende eller akkumulerende?

Før du vælger din specifikke fond, skal du træffe en vigtig beslutning baseret på dit depot og din skattestrategi:

* **Udbyttebetalende fonde (Distribuerende):** Disse fonde udbetaler automatisk et årligt udbytte til dig. Fordelen er, at de i et almindeligt aktiedepot (for frie midler) er **realisationsbeskattede som aktieindkomst**. Det betyder, at du kun betaler 27 % (op til **63.400 kr.** i 2026) eller 42 % (over grænsen) i skat af dine realiserede gevinster og udbytter. Dine kursgevinster på "papiret" beskattes ikke, før du sælger.
* **Akkumulerende fonde:** Disse fonde udbetaler ikke udbytte, men geninvesterer i stedet overskuddet internt i fonden. Disse er altid **lagerbeskattede** (du betaler skat af årets fiktive gevinst d. 31. december). Hvis fonden er dansk og akkumulerende, beskattes den som kapitalindkomst, medmindre den står på Skattestyrelsens positivliste, hvor den i stedet lagerbeskattes som aktieindkomst. Norske fonde (som Storebrand) beskattes dog som aktieindkomst, hvis de er på positivlisten.

Hvis du vil forstå skatternes dybere betydning for din formue, kan du læse min store moderside: **[Indeksfonde - Komplet guide til index investering](/indeksfonde/)**.

---

## Komplet overblik over de passive danske indeksfonde

Herunder har jeg samlet de mest gængse globale indeksfonde fra de danske udbydere. For at en fond kan kvalificere sig til denne liste, skal den opfylde to krav:
1. Den skal kunne købes nemt via de gængse handelsplatforme som egen bank, [Nordnet](/go/nordnet/) eller Saxo Bank.
2. Den skal have et globalt fokus, da en bred verdensfond bør udgøre fundamentet i enhver passiv portefølje.

Her er det samlede, rå overblik over fondene på tværs af kategorier:

{% assign fonde = site.data.funds | where: "type", "Investeringsforening" | where: "strategy", "Passiv" %}

{% include fund-table.html funds=fonde %}

*Bemærk: Jeg har inkluderet information om, hvorvidt fondene kan købes via **Nordnets Månedsopsparing**. Det er en kæmpe fordel, da du derved slipper for at betale købskurtage, når du køber op måned efter måned.*

---

{% assign distribuerende = site.data.funds | where: "type", "Investeringsforening" | where: "dividend", "Distribuerende" %}

## Liste over {{ distribuerende.size }} udbyttebetalende (realisationsbeskattede) fonde

Disse fonde er oplagte til dig, der investerer for **frie midler** og ønsker at udskyde skatten på dine kursgevinster i overensstemmelse med realisationsprincippet. 

Følgende fonde er passive, udbyttebetalende og globale:

{% for f in distribuerende %}
- [{{ f.name }}]({{ f.morningstar_url }}) (Ticker: `{{ f.ticker }}`)
{%- endfor %}

*Tip: Navnene kan variere en smule på tværs af bankernes handelsplatforme. Brug derfor altid fondens `ticker` (forkortelse) i parentesen, når du søger efter den, så du er sikker på at ramme den rigtige.*
{: .notice--info }

---

{% assign akkumulerende = site.data.funds | where: "type", "Investeringsforening" | where: "dividend", "Akkumulerende" %}

## Liste over {{ akkumulerende.size }} akkumulerende (lagerbeskattede) fonde

Disse fonde egner sig særligt godt til pensionsdepoter (f.eks. ratepension eller aldersopsparing) eller til virksomhedsskatteordningen (VSO), hvor der i forvejen er tvungen lagerbeskatning.

Følgende fonde er passive, akkumulerende og globale:

{% for f in akkumulerende %}
- [{{ f.name }}]({{ f.morningstar_url }}) (Ticker: `{{ f.ticker }}`)
{%- endfor %}

*Bemærk vedrørende Storebrand:* Selvom Storebrand er en norsk udbyder, er deres fonde ekstremt populære i Danmark, fordi de er godkendt som aktieindkomst på Skats positivliste. De akkumulerende fonde sikrer, at du slipper for at geninvestere små udbytter manuelt.

---

## Hvad skal du holde øje med? (ÅOP og Benchmark)

Når du sammenligner passive fonde, er der to nøgletal, der reelt betyder noget:

### 1. Årlige Omkostninger i Procent (ÅOP)
Da passive fonde blot følger et indeks mekanisk, betaler du ikke for "geniale genveje", men for ren administration. Derfor skal ÅOP være så lav som overhovedet muligt. En god dansk passiv fond bør ligge et godt stykke under 1,0 %.

Her er de årlige omkostninger for de **udbyttebetalende** globale fonde:

{% for f in distribuerende %}
- [{{ f.name }}]({{ f.morningstar_url }}) — **{{ f.aaop }} ÅOP**
{%- endfor %}

Her er de årlige omkostninger for de **akkumulerende** globale fonde:

{% for f in akkumulerende %}
- [{{ f.name }}]({{ f.morningstar_url }}) — **{{ f.aaop }} ÅOP**
{%- endfor %}

*Sammenligning med udlandet:* Til sammenligning kan du købe udenlandske, børshandlede fonde (ETF'er) med en ÅOP helt ned til 0,07 % - 0,12 %. Grunden til, at de danske fonde koster en smule mere i administration (typisk 0,40 % - 0,50 %), er de administrative omkostninger forbundet med at overholde de danske udbytte- og skatteregler. For mange investorer opvejer fordelen ved realisationsbeskatning dog denne prisforskel.

### 2. Benchmark (Hvilket indeks følger fonden?)
Selvom alle fondene kalder sig "globale", er der nuancer i, hvad de definerer som *verden*. Det indeks, fonden spejler, kaldes dens benchmark:

{% for f in distribuerende %}
- [{{ f.name }}]({{ f.morningstar_url }}) — Benchmark: `{{ f.index }}`
{%- endfor %}

Kort fortalt opdeles verdensindekserne typisk fra MSCI således:
* **MSCI World:** Dækker udelukkende virksomheder i den *udviklede* del af verden (f.eks. USA, Europa, Japan).
* **MSCI Emerging Markets:** Dækker udelukkende *udviklingslande* (f.eks. Kina, Indien, Brasilien).
* **MSCI ACWI (All Country World Index):** Indeholder *både* udviklede lande og udviklingslande. Det er det absolut bredeste fundament, du kan vælge.

Hvis du vælger en fond, der følger MSCI World, fravælger du bevidst udviklingslandene. Vælger du en fond som *Sparindex INDEX Globale Aktier*, følger den MSCI ACWI-princippet og dækker dermed hele den globale økonomi bredest muligt.

---

## Konklusion og min anbefaling

Valget af den bedste passive investeringsforening afhænger fuldstændig af dit depot:

1. **Investerer du for frie midler?** Så vil de fleste have størst fordel af en **dansk, udbyttebetalende fond** (som Sparindex eller Danske Invest) for at opnå realisationsbeskatning og derved lade den udskudte skat arbejde for sig.
2. **Investerer du via Aktiesparekonto eller pension?** Så er der tvungen lagerbeskatning. Her bør du kigge mod de markant billigere udenlandske ETF'er (eller akkumulerende fonde som Storebrand) for at presse ÅOP i bund.

---

*Hvilken fond er din personlige favorit i din portefølje, og prioriterer du lavest mulige omkostninger (ÅOP) eller bredest muligt benchmark? Lad os høre din mening i kommentarerne herunder!*

{% include disclaimer.md %}