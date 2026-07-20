---
layout: single
title: "Biløkonomi: Sådan beregner du bilens sande kilometerpris og TCO"
permalink: /bilokonomi/
redirect_from:
  - /bilen-synes-2020/
  - /gomore/
category:
  - Privatøkonomi
tags:
  - biløkonomi
  - spar penge
  - budget
excerpt: "Hvad koster din bil dig egentlig pr. kilometer? Få formlen til at beregne din bils Total Cost of Ownership (TCO), se hvornår det kan betale sig at skifte bil, og forstå matematikken bag biludlejning."
last_modified_at: 2026-07-20T10:00:00+02:00
header:
  teaser: https://images.unsplash.com/photo-1466692476868-aef1dfb1e735?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&h=300&w=400&q=10
---

Bilen er for de fleste husholdninger den næststørste udgift i hverdagen – kun overgået af boligen. Alligevel kender de færreste deres reelle udgift pr. kørte kilometer. Mange kigger kun på benzinprisen ved standeren, men glemmer afskrivning, værkstedsregninger, dækslid og ejerafgifter.

Hvis du jagter økonomisk uafhængighed (FIRE), er optimering af biløkonomien et af de steder, hvor du kan hente de absolut største besparelser.

Her er guiden til at beregne din bils sande kilometerpris (Total Cost of Ownership), tjeklisten for hvornår bilen bør skiftes, og regnestykket bag biludlejning.

---

## 📊 Formlen: Hvad koster din bil reelt pr. kilometer?

For at kende din sande kilometerpris, skal du opdele dine udgifter i tre kategorier og holde dem op mod det faktiske antal kilometer, du kører om året.

### 1. Faste ejerskabsudgifter (Uafhængige af kilometer)
Dette er udgifter, du betaler blot for at have bilen stående i indkørslen:
* **Afskrivning / Værditab:** Bilens købspris minus forventet salgspris, fordelt på de måneder du ejer bilen.
* **Bilforsikring:** Ansvar og kasko.
* **Grøn ejerafgift / Vægtafgift.**

### 2. Variable driftsudgifter (Afhænger af kilometer)
Dette er udgifter, der stiger, jo mere du kører:
* **Brændstof / El:** Reelt forbrug (km/l eller kWh/km).
* **Værksted, service og reparationer.**
* **Dækslid:** Typisk ca. 0,15–0,20 kr. pr. km.
* **Parkering, vask og vejaftaler (Brobizz mv.).**

### 📐 Sådan udregner du din kilometerpris
Brug en udgifts-app (fx Spiir) eller dit netbank-arkiv over 12-36 måneder:

$$
\text{Kilometerpris} = \frac{\text{Samlede udgifter (Ejerskab + Drift + Afskrivning)}}{\text{Totalt antal kørte kilometer}}
$$

> **Tommelfingerregel:** En ældre, frikøbt benzin/dieselbil ligger ofte på en samlet kilometerpris omkring **2,50 – 3,50 kr./km** alt inklusiv. En nyere bil med højt værditab kan hurtigt koste **4,00 – 6,00 kr./km**.

---

## 🚘 Case Study: Citroën Berlingo som forudfyldt eksempel

For at gøre beregningen håndgribelig har jeg forudfyldt beregneren herunder med de **faktiske, historiske tal fra min Citroën Berlingo 1.6 (2006-model)**, som vi ejede i 87 måneder.

I løbet af ejertiden kørte vi i gennemsnit **15.720 km om året** (1.310 km/mdr), og udgifterne fordelt på et år så således ud:

* **Værditab / Afskrivning:** 10.068 kr./år (købspris på 73.000 kr. fordelt ud)
* **Forsikring & Ejerafgift:** 7.308 kr./år
* **Værksted, service & dæk:** 9.384 kr./år
* **Brændstof (Benzin):** 14.736 kr./år (ca. 10–11 km/l)
* **Parkering & Brobizz:** 3.876 kr./år

Tryk på knappen herunder for at se, hvordan det samlede regnestykke og kilometerprisen så ud for min Berlingo:

{% include tco-beregner.html 
   id="berlingo"
   title="🚗 Berlingo Case Study (Tryk og se resultat)"
   km_year=15720
   depreciation=10068
   fixed_costs=7308
   maintenance=9384
   fuel_cost=14736
   other_costs=3876 
%}

Som det fremgår af beregningen, landede min Berlingo på en samlet kilometerpris på **2,89 kr. pr. km** og en månedlig udgift på næsten **3.800 kr.** Du kan frit ændre i felterne i boksen ovenfor og indtaste dine egne tal for at se, hvordan din bil klarer sig i forhold til Berlingoen.

---

## 🛠️ Reparere eller skrotte: Hvornår skal bilen skiftes?

Det evige dilemma med en ældre bil er: *Kan det betale sig at kaste 10.000–20.000 kr. efter en reparation til syn, eller skal bilen skrottes?*

For at træffe en rationel beslutning bør du sammenligne **reparationsomkostningen pr. måned** med bilens restværdi:

1. **Indhent flere tilbud:** Brug platforme som fx Autobutler til at indhente tilbud fra flere mekanikere. Forskellen på værkstedspriser kan være enorm.
2. **Månedlig levetidsforlængelse:** Hvis en reparation koster 12.000 kr., og den holder bilen kørende og synet i 12 måneder, koster reparationen dig **1.000 kr./mdr.**
3. **Sammenlign med alternativet:** Kan du leje en bil via samkørselstjenester (fx GoMore) eller klare dig med offentlig transport i de måneder, for et mindre beløb end bilens samlede faste udgifter + reparation? If fald bør bilen skrottes.

### 🧮 Regnestykket: Kan det betale sig at syne en gammel bil?

Når din ældre bil står overfor et syn, bør du lave en hurtig kalkule baseret på tre faktorer:

1. **Beregn Netto-omkostningen:**  
   Holder du reparationsudgiften op mod bilens gensalgsværdi, ser formlen således ud:
  {% include math formula="$$\text{Nettoudgift} = \text{Reparation/Syn} + \text{Faste udgifter i perioden} - (\text{Forventet salgspris} - \text{Skrotindkomst})$$" %}

2. **Sammenlign med "Lejebils-ækvivalenten":**  
   Divider din samlede netto-omkostning ved synet med dagsprisen for en lejebil (fx GoMore til ca. 400 kr./dag).  
   * *Eksempel:* Hvis et syn og 8 måneders faste udgifter koster dig 13.300 kr., svarer det til **33 dages billeje**. Har du kun brug for bil 2-3 dage om måneden, er det en ren overskudsforretning at skrotte bilen med det samme og leje efter behov.

3. **Husk at "skrælle" bilen før skrotning:**  
   Skrothandleren giver kun den faste skrotpræmie uanset bilens stand. Afmonter derfor altid ekstraudstyr som tagbøjler (fx Thule), cykelholdere, tagboks og ekstra hjulsæt, og sælg dem særskilt på DBA. Det kan ofte give et par tusinde kroner ekstra i kassen.


### 🚘 Case Study: Berlingoens oprindelige syns-kalkule

Da min Citroën Berlingo stod overfor syn, overvejede vi at beholde den i **8 måneder mere** indtil årets udgang. Vores udgangspunkt var:

* **Forventet syns-klargøring:** 8.000 kr.
* **Faste udgifter (Forsikring 355 kr. + Ejerafgift 312 kr.):** 667 kr./mdr.
* **Forventet salgspris efter syn:** 10.000 kr.
* **Skrotværdi uden syn:** 2.200 kr.
* **Gennemsnitlig lejebilspris (GoMore):** 400 kr./dag.

Prøv at trykke på beregneren herunder for at se, hvor mange dages billeje vores Berlingo reelt svarede til:

{% include bilsyn-beregner.html 
   id="berlingo_syn"
   title="⚖️ Berlingo Case Study: Syn vs. Skrot & Lejebil"
   months=8
   repair_cost=8000
   fixed_monthly=667
   expected_sale=10000
   scrap_value=2200
   rental_daily=400 
%}

**Resultatet af beregningen:**
I den oprindelige kalkule landede netto-omkostningen på **5.536 kr.** over de 8 måneder. Det svarede til i alt **13,8 dages billeje** (eller knap **1,7 dagers billeje om måneden**). Da vi brugte bilen mere end 2 dage om måneden, kunne synet dengang godt betale sig.

### 💥 Da mekaniker-chokket ændrede regnestykket
Da vi sendte bilen til mekanikeren og indhentede tilbud via Autobutler, løb de reelle reparationsudgifter (bagbro, bremser mm.) op i **22.500 kr.** 

Prøv at ændre tallet for *"Reparation & syns-klargøring"* i beregneren ovenfor til **22500 kr.**

Nu stiger netto-omkostningen pludselig til over **20.000 kr.**, hvilket svarer til **50 dages billeje** (over **6 dages leje om måneden**). Da vores kørselsbehov var faldet og var mindre end 6 dage om måneden, tog vi den hurtige beslutning: Bilen blev skrottet med det samme for skrotpræmien på 2.200 kr., og vi gik 100 % over til lejebiler og cykler.

---

## 🚘 Udlejning via GoMore: Kan det reelt betale sig?

Når bilen alligevel står stille i indkørslen, virker det oplagt at udleje den via platforme som GoMore. Skattereglerne er endda skruet sådan sammen, at der findes et ret pænt skattefrit bundfradrag for privat biludlejning.

Men før du regner lejeindtægten ind som et fast tilskud til dit bilbudget, skal du kende forskel på *bruttoindtægt* og *nettoindtægt*. 

Når du sætter din udlejningspris, skal du nemlig modregne det usynlige slid på bilen. Her er et virkeligt regneeksempel baseret på FDMs tommelfingerregler og mine egne historiske tal fra en ældre Citroën Berlingo:

Det giver følgende regnskab, hvor jeg går ud fra en udlejningspris på 325 kroner (udregninger baseret på [artikel fra FDM](https://fdm.dk/node/8888)).

_(Læg mærke til at dine forudsætninger kan være anderledes, hvis du vil [udleje din bil via GoMore](/go/gomore/){: rel='sponsored nofollow noopener' })_

<iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vQcPiPHuya32XoyHcIXTxbiR_GpnSCwpHAl14gXreS31Zf5IBCxRhhirijORT9RvZRymniTJDJdG8Fo/pubhtml?gid=1711999018&amp;single=true&amp;widget=true&amp;headers=false" style="width:75%; height: 550px;"></iframe>


### 🧮 Det skjulte regnestykke (Prøv selv)

Lad os antage, du udlejer din bil for **325 kr. for en dag**, og lejeren kører en pæn tur. Hvad koster den tur *dig*?

* **Dækslid:** FDM anslår ca. 0,17 kr. pr. kørt kilometer.
* **Værditab:** FDM anslår ca. 0,44 kr. pr. kørt kilometer.
* **Mekanisk vedligehold:** Historiske tal på min egen bil viste en udgift på 0,59 kr. pr. kørt kilometer i sliddele og værksted.

Når platformen (GoMore) har taget deres gebyr for forsikring og formidling, og du har trukket dækslid, kilometer-afhængigt værditab og fremtidige værkstedsregninger fra, skrumper de 325 kr. markant. 

Beregneren herunder er forudfyldt med FDMs tommelfingerregler samt mine egne historiske værkstedstal fra en ældre Citroën Berlingo. Prøv at justere på antallet af kørte kilometer og se, hvad der sker med dit overskud!

{% include gomore-beregner.html 
   id="gomore_case" 
   price="325" 
   fee_percent="20" 
   km="150" 
   maintenance="0.59" 
   tire_wear="0.17" 
   value_loss="0.44" 
%}

> **Reality Check:** Som du kan se i beregneren ovenfor, æder slitagen på bilen hurtigt overskuddet. Hvis lejeren kører 150 km, ender en dagsudlejning til 325 kr. med kun at give en **reel nettoindtægt på ca. 80 kr.** på bundlinjen.

### ⚖️ Er 80 kroner besværet værd?
Når overskuddet ikke er større, skal du opveje det mod dit eget tidsforbrug og de risici, der er forbundet med udlejning:

1. **Skat og bundfradrag:** Heldigvis er reglerne skruet sådan sammen, at der findes et ret pænt skattefrit bundfradrag for privat biludlejning (lidt ligesom ved udlejning via Airbnb). Det betyder, at du ofte kan udleje bilen skattefrit i op til ca. 40 dage om året. 
2. **Tidsforbrug:** Du skal kommunikere med lejeren, overdrage nøgler, tjekke bilen for skader bagefter og sørge for, at den er ren. 
3. **Forsikringsfælden:** Selvom GoMore forsikrer bilen under selve udlejningen, kræver det ofte, at din bil allerede er kaskoforsikret. Vær desuden meget opmærksom på dit årlige kilometerloft i din egen forsikring – hvis udlejningen presser dig over grænsen, risikerer du at være underforsikret.

**Konklusionen:** Udlejning kan være en fin lille skattefri bonus, men forvent ikke, at det fuldt ud kan finansiere at have en dyr bil stående. 

**💡 FIRE-Hacket: Samkørsel frem for udlejning**
Hvis du vil optimere din biløkonomi uden ekstra slitage, er *samkørsel* (at tilbyde et lift via GoMore, når du alligevel selv skal køre ruten) ofte en markant bedre forretning. Her har du ingen ekstra udgifter til dækslid eller værditab, fordi bilen alligevel skulle køre turen. Passagerens betaling går dermed direkte til at barbere toppen af din egen brændstofregning.
{ .notice--info }

---

<div class="notice--info" markdown="1">
## 💡 Hvad jeg har tænkt over – og hvorfor

I mange år kørte jeg selv i en ældre Citroën Berlingo. Ved at føre minutiøst regnskab opdagede jeg, at bilen kostede mig nøjagtigt **2,89 kr. pr. kilometer** (og **1,70 kr./km** hvis brændstoffet blev fraregnet). 

Da bilen i 2020 stod overfor et syn med reparationskrav på over 22.000 kr., brugte jeg præcis de beregninger, du finder i denne guide. Konklusionen var klar: Bilen blev skrottet for skrotpræmien på 2.200 kr., og vi valgte i en lang periode at leve helt uden bil og i stedet benytte GoMore og cykler. Det sendte vores opsparingsrate direkte i vejret.

👉 **[Læs hele historien om min Berlingo, Autobutler-chokket og skiftet til bilfri i min personlige logbog på Min FIRE-historie](/min-firehistorie/)**
</div>

{% include disclaimer.md %}