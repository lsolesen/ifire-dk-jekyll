---
layout: single
title: &title "Renters rente - beregn effekten i vores onlineberegner"
permalink: /renters-rente/
description: "Brug vores renters rente beregner til at se effekten af renters rente. Vi bruger renteformlen med konstant rentefod og mulighed for løbende kapitalindskud."
excerpt: "Beregn renters rente effekt på renteudbetalinger med denne beregner. Se renters rente formel med konstant rentefod og mulighed for løbende kapitalindskud."
header:
  overlay_image: https://images.unsplash.com/photo-1559526324-593bc073d938?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=2000&q=5
  caption: *title
  alt: "Photo by Austin Distel on Unsplash - Renters Renter"
toc: true
author_profile: true
feature_row:
  - title: "Google Sheet"
    excerpt: "Download mit Google Sheets for både at lave enkle renters rente beregninger og mere avancerede renters rente beregninger med løbende indskud."
    url: https://docs.google.com/spreadsheets/d/1fA9aYAgvjNHZC_FLccb4yOMVz7FTxrDFw0JOa-CG_ew/copy?usp=sharing
    btn_label: Google Sheets
    btm_class: btn--success
last_modified_at: 2021-07-18T13:45:01Z
---

Renters rente er en af de mest motiverende årsager til at investere. Første år får du renter af din investering. De følgende år får du både renter af investeringen og af renterne fra de tidligere år. Det betyder, at du over tid får en eksponentiel stigning af dine penge. 

Desto længere tid, du kan investere pengene, desto større bliver effekten af renters rente. Ved første øjekast kan renters rente formel godt være lidt forvirrende, så derfor kan det være dejligt med en onlineberegner, der gør arbejdet for dig.

## Udregn renters rente

Vi har lavet en onlineberegner til at visualisere **effekten af renters rente**. Indtast dine tal herunder for at se, hvordan din opsparing kan vokse med og uden løbende indbetalinger.

***

{% include renters-rente.html 
  base="10000"
  deposit="50"
  rate="7"
  years="30" %}

***

## Hvad er renters rente?

> Rentes rente eller kapitalfremskrivning er det fænomen, at når en kapital forrentes adskillige gange til en konstant rentefod, stiger renteudbetalingerne fra den ene renteudbetaling til den næste. Årsagen er, at rentepengene lægges til den oprindelige kapital, så der ved næste renteudbetaling betales renter af et så meget desto større beløb.

<cite>--- [Wikipedia](https://da.wikipedia.org/wiki/Rentes_rente)</cite>

### Eksempel på renters rente i praksis
Forestil dig, at du investerer **10.000 kr.** til et årligt afkast på **7%**.
* **År 1:** Du tjener 7% af 10.000 kr. Det er 700 kr. Du har nu 10.700 kr.
* **År 2:** Nu får du 7% i rente af de *10.700 kr.* Det er 749 kr. Du har nu 11.449 kr.
* **År 10:** Efter 10 år er dine 10.000 kr. vokset til **19.671 kr.** – uden du har sat en ekstra krone ind. Næsten halvdelen af beløbet er nu rene renteindtægter.

Det er Albert Einstein ofte (omend fejlagtigt) citeret for at kalde *"verdens ottende vidunder"*.

## Regneark med renters rente beregner

{% include feature_row type="left" %}

## Formel for renters rente

[Formlen](http://www.helpfulcalculators.com/compound-interest-calculator) for renters rente ser sådan her ud:

{% include math formula="V=P*(1+\frac{r}{n})^{n*t}" %}

* **V (Slutbeløb/Værdi):** Værdien af investeringen i slutningen af perioden.
* **P (Startkapital/Hovedstol):** Det oprindelige investerede beløb (Principal).
* **r (Rentefod):** Den årlige rente i procent angivet som decimaltal (f.eks. 0,07 for 7%).
* **n (Terminer pr. år):** Hvor mange gange renten tilskrives om året (ofte 1 for årlig, eller 12 for månedlig tilskrivning).
* **t (Antal år):** Hvor lang tid investeringen løber.

Lidt forenklet så har følgende forhold særlig stor effekt på effekten af renters rente i renteberegningen.

- **Tid**. Renters rente giver først rigtig effekt, når der er en lang tidshorisont (gerne mere end 10 år).
- **Afkast**. En mindre, tilsyneladende ubetydelig renteændring - eller omkostninger i investeringsforeninger - har rigtig stor effekt over lang tid.
- **Oprindelige beløb**. Det er dette beløb, der står længst og giver afkast i flest år.
- **Skat**. Skat er den største udgift du får på din investering. Derfor betyder dine skatteforhold meget - og skatteforholdene er lidt indviklede i Danmark.

Derfor er det en god ide at forsøge at optimere ovenstående punkter, hvis du vil have den optimale effekt af renters renter.

## Renteformlen for renters rente med månedligt indskud

Måske kan du også tilføje et beløb til din investering hver måned. Du kan bruge denne formular til at udregne effekten af en fast månedlig investering.

Formlen for renters rente med løbende indbetalinger ser sådan her ud.

{% include math formula="V=P*(r+1)^n+i*\frac{(1+r)^n-1}{1+r}" %}

- **i:** månedligt tilbagevendende beløb

Jeg bliver i hvert fald rigtig motiveret, når jeg bruger renteberegneren ovenfor og kan se, hvor stor effekten af renters rente virkelig er, når investeringen har mange år til at passe sig selv.

Når du skal finde en investering, der giver dig dit ønskede afkast, så er der flere forhold, du skal være opmærksom på. Først og fremmest skal du tænke på, hvad din risikoprofil er. Højere renter hænger oftest sammen med højere risiko. Dernæst skal du holde øje med om den _interne rente_ (XIRR) af din investering er lige så høj, som du forventede.

## 72-reglen: Hvor hurtigt fordobles dine penge?

Hvis du vil lave en lynhurtig renters rente beregning i hovedet, kan du bruge den berømte **72-regel**. Reglen fortæller dig, hvor mange år det tager at fordoble din investering ved en bestemt rente.

Du tager blot tallet 72 og dividerer med dit forventede årlige afkast:

$$ \text{År for fordobling} = \frac{72}{\text{Årligt afkast i \%}} $$

**Eksempel:** Får du et årligt afkast på 7%, tager det cirka 10,2 år at fordoble dine penge ($72 / 7 = 10,2$). Får du derimod 10% i afkast, tager det kun 7,2 år.

## Ofte stillede spørgsmål

### Hvad er renters rente?

Renters rente (kaldes også kapitalfremskrivning) er, når renterne på en kapital opnår renter.

### Hvordan beregner man renters rente?

Du kan bruge beregneren ovenfor, som giver et godt visuelt overblik. Jeg har også lavet et [Google Sheet](https://docs.google.com/spreadsheets/d/1fA9aYAgvjNHZC_FLccb4yOMVz7FTxrDFw0JOa-CG_ew/copy), hvor du kan taste værdierne ind. Du kan også bruge renteformlen selv.

## Konklusion

Nu har du et godt udgangspunkt for at lave en **renters rente beregning**, fordi du ved hvordan renteformlen skal bruges.

Hvis du er interesseret i denne beregner, så kan du måske også være interesseret i vores beregner til, [hvad får jeg udbetalt efter Skat](/udbetalt-loen-efter-skat/) eller vores [opsparingsberegner](/opsparingsberegner/).

Hvis du har forbedringer til indlægget om renters rente så skriv endelig.

{% include disclaimer.md %}