---
layout: single
title: &title "Renters rente - beregn effekten i vores onlineberegner"
seo_title: "Renters rente beregner (2026) • Formel & onlineberegner »"
permalink: /renters-rente/
description: "Beregn effekten af renters rente med vores gratis onlineberegner. Se formlen med løbende indbetalinger, konkrete regneeksempler og 72-reglen."
excerpt: "Beregn renters rente effekt med vores gratis onlineberegner. Se renters rente formel med og uden løbende indbetalinger samt 72-reglen."
header:
  overlay_image: https://images.unsplash.com/photo-1559526324-593bc073d938?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=2000&q=5
  caption: *title
  alt: "Renters rente beregner og formel"
toc: true
author_profile: true
feature_row:
  - title: "Google Sheet"
    excerpt: "Kopier mit Google Sheet for både at lave enkle renters rente-beregninger og mere avancerede beregninger med løbende månedlige indskud."
    url: https://docs.google.com/spreadsheets/d/1fA9aYAgvjNHZC_FLccb4yOMVz7FTxrDFw0JOa-CG_ew/copy?usp=sharing
    btn_label: Hent Google Sheet
    btn_class: btn--success
last_modified_at: 2026-07-18T13:45:01Z
mathjax: true
faq:
  - question: "Hvad er renters rente?"
    answer: "Renters rente (kapitalfremskrivning) opstår, når du ikke hæver dit afkast eller dine renter, men lader dem blive stående, så du året efter både får afkast af dit oprindelige indskud og af de tidligere års afkast. Det skaber eksponentiel vækst over tid."
  - question: "Hvordan beregner man renters rente?"
    answer: "Du beregner renters rente med formlen V = P · (1 + r)^t, hvor P er din startkapital, r er den årlige rente som decimaltal (f.eks. 0,07 for 7 %), og t er antal år. Du kan også indtaste dine tal direkte i vores onlineberegner ovenfor eller bruge vores Google Sheet."
  - question: "Hvad er formlen for renters rente med løbende indbetalinger?"
    answer: "Med faste løbende indbetalinger bruges formlen V = P · (1 + r)^n + i · (((1 + r)^n - 1) / r), hvor P er startbeløb, i er indbetalingen pr. termin, r er renten pr. termin som decimaltal, og n er antal terminer."
  - question: "Hvad er 72-reglen?"
    answer: "72-reglen er en hurtig tommelfingerregel til at udregne, hvor mange år det tager at fordoble dine penge ved renters rente. Du dividerer blot 72 med dit årlige afkast i procent – ved 7 % i afkast tager det cirka 10,3 år at fordoble din formue (72 / 7 = 10,3)."
---

**Renters rente** betyder, at du ikke kun får afkast af de penge, du selv har sat ind – du får også afkast af tidligere års renter og kursgevinster. Over tid skaber det en sneboldeffekt med eksponentiel vækst, hvor afkastet til sidst vokser hurtigere end dine egne indbetalinger.

Jo længere tid dine penge får lov at arbejde, desto vildere bliver effekten. Brug vores gratis **renters rente beregner** herunder til at teste dine egne tal – eller hop videre til formlen med løbende indskud og 72-reglen.

## Udregn renters rente

Vi har lavet en onlineberegner til at visualisere **effekten af renters rente**. Indtast dit startbeløb, dine månedlige indbetalinger, din forventede rente og din tidshorisont herunder:

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
Forestil dig, at du investerer **10.000 kr.** til et årligt afkast på **7 %** uden at sætte flere penge ind:

* **År 1:** Du tjener 7 % af 10.000 kr. = **700 kr.** Du har nu **10.700 kr.**
* **År 2:** Nu får du 7 % i afkast af de *10.700 kr.* = **749 kr.** Du har nu **11.449 kr.**
* **År 10:** Efter 10 år er dine 10.000 kr. vokset til **19.672 kr.** – uden du har tilføjet en eneste ekstra krone. Næsten halvdelen af beløbet er nu rene rente- og afkastindtægter.
* **År 30:** Efter 30 år er de samme 10.000 kr. vokset til **76.123 kr.**

Det er netop denne effekt, Albert Einstein ofte (omend fejlagtigt) citeres for at kalde *"verdens ottende vidunder"*.

## Regneark med renters rente beregner

Foretrækker du at regne videre i et regneark, hvor du selv kan tilpasse rækkerne?

{% include feature_row type="left" %}

## Formel for renters rente

Den klassiske **formel for renters rente** (for et engangsbeløb uden løbende indskud) ser sådan ud:

$$
V = P \left(1 + \frac{r}{n}\right)^{n \cdot t}
$$

* **V (Slutbeløb/Værdi):** Værdien af investeringen i slutningen af perioden.
* **P (Startkapital/Hovedstol):** Det oprindeligt investerede beløb (*Principal*).
* **r (Rentefod):** Den årlige rente i procent angivet som decimaltal (f.eks. `0,07` for 7 %).
* **n (Terminer pr. år):** Hvor mange gange renten tilskrives om året (`1` ved årlig tilskrivning, `12` ved månedlig tilskrivning).
* **t (Antal år):** Hvor mange år investeringen løber.

Lidt forenklet er der fire håndtag, der afgør, hvor kraftig renters rente-effekten bliver for dig:

* **Tid:** Renters rente batter først for alvor, når tidshorisonten er lang (gerne 10–30 år).
* **Afkast og omkostninger:** Selv 0,5–1,0 % forskel i årligt afkast eller løbende fondsgebyrer ([ÅOP](/investeringsomkostninger/)) gør en kæmpe forskel over 20–30 år.
* **Startbeløb:** De penge, du kommer i gang med tidligst, er dem, der når at trække renter i flest år.
* **Skat:** Skat er den største udgift på en dansk investering. Kan du udskyde skatten (realisationsbeskatning) eller nøjes med 17 % på en [Aktiesparekonto](/aktiesparekonto/), bliver der markant mere kapital tilbage til at trække renters rente.

## Renteformlen for renters rente med månedligt indskud

De fleste sparer ikke kun op med ét engangsbeløb, men indbetaler et fast beløb hver måned. Når du kombinerer en startkapital ($P$) med faste, løbende indbetalinger ($i$) ved slutningen af hver termin, ser **renteformlen for renters rente med månedligt indskud** sådan ud:

$$
V = P(1 + r)^n + i \cdot \frac{(1 + r)^n - 1}{r}
$$

* **V:** Slutbeløb efter alle terminer.
* **P:** Startkapital (hovedstol).
* **i:** Fast indbetaling pr. termin (f.eks. dit månedlige indskud).
* **r:** Renten pr. termin som decimaltal. Ved månedlige indbetalinger regnes der med månedlig terminsrente – f.eks. $r = \frac{0{,}07}{12} \approx 0{,}00583$ (nominel månedlig rente) eller $r = (1 + 0{,}07)^{1/12} - 1 \approx 0{,}00565$ (effektiv årlig rente på 7 %).
* **n:** Samlet antal terminer (ved månedlige indbetalinger over 20 år er $n = 20 \cdot 12 = 240$).

*(Indbetaler du beløbet i starten af hver måned frem for i slutningen, ganges det sidste led blot med $(1 + r)$).*

Jeg bliver selv motiveret hver gang, jeg taster nye tal ind i beregneren ovenfor og ser, hvordan de månedlige indskud fra en [Nordnet Månedsopsparing](/nordnet-maanedsopsparing/) langsomt overtages af afkastets egen sneboldeffekt.

Husk dog altid at vurdere din risikoprofil, før du jagter høje procenter – højere forventet afkast hænger sammen med større udsving undervejs. Vil du måle dit faktiske historiske afkast på en portefølje med løbende ind- og udbetalinger, bør du bruge den *interne rente* (XIRR).

## 72-reglen: Hvor hurtigt fordobles dine penge?

Hvis du vil lave en lynhurtig renters rente-beregning i hovedet, kan du bruge **72-reglen**. Reglen fortæller dig, cirka hvor mange år det tager at fordoble din formue ved en bestemt årlig rente.

Du dividerer blot tallet 72 med dit forventede årlige afkast i procent:

$$ \text{År for fordobling} = \frac{72}{\text{Årligt afkast i \%}} $$

* **Ved 7 % i afkast:** $\frac{72}{7} = \mathbf{10{,}3\text{ år}}$ til at fordoble dine penge.
* **Ved 10 % i afkast:** $\frac{72}{10} = \mathbf{7{,}2\text{ år}}$ til at fordoble dine penge.

## Ofte stillede spørgsmål

{% include faq.html %}

## Konklusion

Nu har du både en onlineberegner, et regneark og de præcise formler til at lave din egen **renters rente-beregning** – både med og uden løbende månedlige indskud.

Vil du regne videre på din økonomi, kan du også prøve vores [opsparingsberegner](/opsparingsberegner/), beregne din [udbetalte løn efter skat](/udbetalt-loen-efter-skat/) eller se, hvornår din formue rækker til frihed i vores [økonomisk uafhængighed beregner](/okonomisk-uafhaengighed-beregner/).

Har du spørgsmål eller forslag til forbedringer af beregneren, er du meget velkommen til at skrive en kommentar herunder.

{% include disclaimer.md %}