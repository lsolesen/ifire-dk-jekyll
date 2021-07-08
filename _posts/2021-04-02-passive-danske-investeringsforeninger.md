---
title: &title "Passive danske fonde: Liste over danske investeringsforeninger"
redirect_from:
  - /danske-inveseringsforeninger-med-passive-indeksfonde/
permalink: /danske-investeringsforeninger-med-passive-indeksfonde/
seo_title: "Passive investeringsforeninger • 8 danske indeksfonde 2021 »"
description: "Se en liste med de bedste passive, danske investeringsforeninger. Jeg har lavet en liste over passive investeringsfonde i Danmark. Se listen her!"
excerpt: "Jeg er meget interesseret i at finde de bedste danske passive investeringsforeninger. Derfor har jeg lavet en liste over passive indeksfonde i Danmark."
category:
  - Investering
tags:
  - investeringsforeninger
  - passiv investering
  - værdipapirer
header:
  overlay_image: https://images.unsplash.com/photo-1511376868136-742c0de8c9a8?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=1950&q=80
  teaser: https://images.unsplash.com/photo-1511376868136-742c0de8c9a8?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=400&q=80
  caption: *title
last_modified_at: 2021-04-03T20:22:02+02:00
---

Jeg er meget interesseret i at finde de bedste danske passive investeringsforeninger. Derfor har jeg lavet en liste over passive indeksfonde i Danmark.

Det kan faktisk være lidt svært at få overblik over de danske passive fonde.

## Liste over passive danske indeksfonde

Hvis du er kunde hos Nordnet, så kan du bruge deres [screeningsværktøj til Investeringsforeninger](https://www.nordnet.dk/markedet/investeringsforeninger-liste?sortField=yield_1y&sortOrder=desc&selectedTab=overview&fundType=INDEX).

{% include figure image_path="/assets/images/nordnet-passiv-indeksfond.png" caption="Hvis du søger på investeringsforeninger på Nordnet efter Indeks, så kommer der dd. 36 indeksfonde frem fra forskellige danske investeringsforeninger" alt="passiv investeringsforeninger med indeksfonde" %}

Jeg er imidlertid ikke interesseret i alle indeksfondene på listen, da jeg gerne vil have en enkel investering, der følger verdensmarkedet. Jeg kan i Nordnet reducere listen yderligere til kun at have globale passive indeksfonde på listen.

{% include figure image_path="/assets/images/nordnet-passiv-global-indeksfond.png" caption="Hvis du kun vil have de globale fonde, så kommer der 11 indeksfonde frem" alt="passiv investeringsforeninger med indeksfonde" %}

Der er altså på Nordnet i alt 11 forskellige passive fonde, der følger et globalt indeks at vælge imellem.

Nu skal du så tage en beslutning om du er interesseret i en udbyttebetalende eller en akkumulerende indeksfond.

Hvis du vælger en udbyttebetalende fond, så er den realisationsbeskattet, som aktieindkomst. Hvis du vælger en akkumulerende indeksfond, så er den lagerbeskattet. Hvis den er dansk, så er den også beskattet som kapitalindkomst, mens det for fx norske Storebrand er lagerbeskattet som aktieindkomst.

Hvilken type skat du ønsker på dine passive indeksfonde kommer helt an på din egen strategi og øvrige økonomiske forhold.

Mange foretrækker en udbyttebetalende dansk fond, når de investerer for frie mider. Men lad os kigge lidt på det.

En investeringsforening er typisk ikke passiv, men de kan have afdelinger, hvor investeringerne forvaltes passivt. Derfor bliver det de enkelte indeksfonde, der er passive.

## Liste over danske passive indeksfonde

Jeg havde selv brug for et overblik over indeksfonde fra danske investeringsforeninger. Der er forskel på beskatningen på udenlandske ETF'er og danske fonde. Derfor synes jeg det kan være godt med et overblik over passive danske fonde.

Listen er lavet på baggrund af følgende overvejelser:

- Det skal være muligt at købe fondene hos de almindelige mæglere, fx egen bank, Nordnet eller Saxo
- Jeg har fokuseret på globale fonde i listen, da det er det jeg selv investerer i. Jeg opfatter globale passive indeksfonde som fonde, der investerer i en del af verdensindekset.

Lad os først få et hurtigt overblik over alle fondene:

{% assign fonde = site.data.funds | where: "type", "Investeringsforening" | where: "strategy", "Passiv" %}

{% include fund-table.html funds=fonde %}

Jeg har inkluderet i oversigten, om du kan købe fonden via Nordnets månedsopsparing. Det er nemlig vigtigt for mig, da jeg månedligt køber op i de passive danske investeringsfonde.

{% assign fonde = site.data.funds | where: "type", "Investeringsforening" | where: "dividend", "Distribuerende" %}

## Liste over {{ fonde.size }} udbyttebetalende danske passive fonde

Listen indeholder fonde der i et depot, hvor du investerer for frie midler bliver realisationsbeskattet. Fondene er nemlig udbyttebetalende, som du skal betale skat af. Fondene på denne liste består kun af distribuerende passive danske fonde.

Listen indeholder altså passive investeringsfonde, der er:

- Passive
- Udbyttebetalende
- Globale

Her kan du se listen over {{ fonde.size }} udbyttebetalende passive indeksfonde.

{% for f in fonde %}
- [{{ f.name }}]({{ f.morningstar_url }}) ({{ f.ticker }})
{%- endfor %}

Når du kigger på listen, så kan navnene godt være lidt anderledes på den platform du anvender. Derfor har jeg skrevet `tickeren` i parentes, så du ikke er i tvivl om, hvilken fond, der snakkes om.
{: .notice--info }

{% assign akkumulerende = site.data.funds | where: "type", "Investeringsforening" | where: "dividend", "Akkumulerende" %}

## Liste over {{ akkumulerende.size }} akkumulerende danske passive fonde

Listen indeholder passive investeringsfonde, der er:

- Passive
- Akkumulerende
- Globale

Her kan du se listen over {{ akkumulerende.size }} akkumulerende passive indeksfonde.

{% for f in akkumulerende %}
- [{{ f.name }}]({{ f.morningstar_url }}) ({{ f.ticker }})
{%- endfor %}

Storebrand er norsk. Den beskattes som aktieindkomst efter lagerprincippet. Du skal være opmærksom på, at de akkumulerende fonde beskattes anderledes end de udbyttebetalende danske fonde. De akkumulerende danske fonde beskattes som kapitalindkomst med mindre de er på Skats positivliste over fonde.

## Hvad skal jeg være opmærksom på med passive indeksfonde?

Når du kigger på passive fonde, så skal du have en forståelse for følgende punkter:

- **Omkostninger**. Du skal kende de samlede årlige omkostninger i fonden. Når du kender omkostningerne, så kan du vurdere om fonden er dyr eller billig?
- **Benchmark**. En passiv fond bør vurderes på, hvor god den er til at følge benchmark for fonden. Det er nemlig fondens formål at tracke et indeks.

## Omkostninger for den passive investeringsforening

Det kan være lidt kompliceret at afdække, hvad omkostningerne er i en fond. Derfor er der regler, der skal beskytte investorerne. Udbyderne af fondene skal opgøre de samlede årlige omkostninger i procent (ÅOP) i en fond.

Du kan altså ved at finde ÅOP (årlige omkostninger i procent) se hvor dyr den passive fond er. En passiv fond bør være noget mindre end 1%.

De **udbyttebetalende danske passive fonde** har følgende årlige omkostninger i procent.

{% for f in fonde %}
- [{{ f.name }}]({{ f.morningstar_url }}) ({{ f.aaop }})
{%- endfor %}

Danske Invests fond er altså den billigste fond i omkostninger. De øvrige fonde ligger på linje.

De **akkumulerende danske passive fonde** har følgende årlige omkostninger i procent.

{% for f in akkumulerende %}
- [{{ f.name }}]({{ f.morningstar_url }}) ({{ f.aaop }})
{%- endfor %}

Storebrand-fondene er altså rimelig attraktive, hvad angår årlige omkostninger.

Men omkostninger er ikke alt. Du skal også huske at tænke på, hvilket indeks de enkelte fonde forsøger at tracke.

Hvis du vælger at investere i ETF'er, som er UCITS-godkendte og derved godkendt til køb i EU, så kan du få globale ETF'er med passiv forvaltning helt ned til 0,12%. De amerikanske indeksinvestorer kan købe Vanguard Total Stock Market Index (VTI), som har en omkostning på kun 0,03%.
{: .notice--success }

Omkostningerne på de danske passive fonde er desværre stadig relativt høje. Heldigvis ser det ud til, at der kommer mere og mere konkurrence, så vi kan håbe på, at vi snart får mere attraktive danske passive investeringsforeninger, der sikrer lavere priser.

## Benchmark index for den passive fond

Benchmark er det indeks, som fonden skal følge. Formålet med de passive fonde er at spejle afkastet i indekset bedst muligt.

Benchmark for de **udbyttebetalende danske indeksfonde** er:

{% for f in fonde %}
- [{{ f.name }}]({{ f.morningstar_url }}) ({{ f.index }})
{%- endfor %}

Benchmark index for de **akkumulerende danske indeksfonde** er:

{% for f in akkumulerende %}
- [{{ f.name }}]({{ f.morningstar_url }}) ({{ f.index }})
{%- endfor %}

Det er lidt kompliceret, men alle fondene følger verdensindekset. Der er imidlertid lidt forskel på, hvad indekset betegner som verden.

Derfor har jeg også skrevet et andet indlæg om de forskellige indekser.

Hvis du vil dykke ned i de forskellige betegnelser i forhold til benchmark, så kan du kigge på [Morningstars oversigt](https://advisor.morningstar.com/principia/pdf/prn_indexabbreviations_1011.pdf).

Lynhurtigt er verdensindekset opdelt i:

- MSCI World - som kun indeholder de udviklede lande.
- MSCI Emerging - som indeholder udviklingslande.
- MSCI ACWI - som indeholder hele verden.

Det er mig stadig en gåde, hvorfor MSCI World ikke kunne være det globale indeks, og så de udviklede lande kunne hedde MSCI Developed. Men det skal åbenbart ikke være let at huske.

Ud over spejle verdensindekset, så kan fondene også have et særligt fokus, fx på lav volatilitet, bæredygtighed eller etik.

## Konklusion

Jeg håber at oversigten over passive danske investeringsforeninger og indeksfonde har været med til at skabe en større forståelse for, hvad du kan vælge imellem.

Når du investerer, så er det vigtigt, at du ved, hvad du investerer i.

Der er **{{ fonde.size }} passive, danske udbyttebetalende fonde, som har et globalt fokus**. Alle disse passive fonde betaler udbytte.

Hvis du vil nøjes med en passiv udbyttebetalende fond fra listen ovenfor, så er 'Sparinvest Index Globale Aktier' den fond, der investerer i det bredest mulige verdensindeks. 

Der er **{{ akkumulerende.size }} passive, danske akkumulerende fonde, som har et globalt fokus**. Alle disse passive fonde betaler udbytte.

Hvis jeg mangler nogle fonde på listen, så brug endelig kommentarerne.

{% include disclaimer.md %}

{% comment %}

passive investeringsforeninger liste
passive investeringsfonde
passive investeringsforeninger
passiv investeringsfond
bedste passive fonde
bedste passive indeksfonde
passiv investeringsforening
udbyttebetalende investeringsforeninger
danske invest global indeks


***

{% endcomment %}
