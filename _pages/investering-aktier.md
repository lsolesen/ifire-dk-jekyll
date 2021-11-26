---
layout: single
title: Investering i aktier og værdipapirer
permalink: /investering-aktier/
header:
  overlay_image: https://images.unsplash.com/photo-1466692476868-aef1dfb1e735?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1900&q=5
#  actions:
#    - label: "Presale: Kursus i minimalistik investering"
#      url: "https://ifire.thinkific.com/courses/minimalistisk-investering"
author_profile: true
classes: wide
feature_row_own:
  - image_path: /assets/images/logo/nordnet.png
    excerpt: 'Jeg bruger selv [Nordnet](/go/nordnet/) til at opbygge min portefølje via deres kurtagefri månedsopsparing og aldersopsparingen.'
  - image_path: /assets/images/logo/saxoinvestor.png
    excerpt: Desuden bruger jeg [SaxoInvestor](/go/saxoinvestor/) til min aktiesparekonto og handel uden minimumskurtage.'
  - image_path: /assets/images/logo/nord.png
    alt: "Nord.Investments"
    title: "Nord.Investments"
    excerpt: "[Nord.Investments](/go/nord/){: rel='sponsored nofollow noopener' } er en investeringsrobot, som ud fra din risikoprofil automatisk sætter dine investeringer op for et relativt lille beløb. De tilbyder et [gratis investeringsforslag](/go/nord/){: rel='sponsored nofollow noopener' }."
---

Aktier og værdipapirer er en meget populær måde at investere på. Hvis du penge til overs, så kan du sætte dem i aktier og obligationer. Du kan enten investere i enkeltaktier, investeringsforeninger, ETF'er og fonde. 

{% comment %}
Køb aktier for begyndere [2021] - Lær at handle med aktier
Få ekspertens 9 bedste råd til at investere i aktier - ALT.dk
Investering i aktier [2021] - stor guide til aktiehandel! - Invested 
Investering: 100 kr. om måneden kan blive til en mindre formue
Investering i aktier | Sådan kommer du i gang med ... - Mybanker
Investering i aktier og obligationer - Finans Danmark

***
{% endcomment %}

At investere i aktier, obligationer og værdipapirer er altså bare en måde, du kan [lave investeringer](/investering/) på. Jeg forsøger selv at minimere min risiko ved at følge verdensmarkedet gennem passiv indeksfonde og ETF'er.

## Investering i aktier for begyndere

Jeg samler her på siden en masse sider, hvor du kan læse mere om aktier for begyndere. Inden du kaster dig ud i investeringer, så anbefaler jeg virkelig, at du lige tygger de her blog posts igennem.

- [Start med hvorfor?](/start-med-hvorfor/)
- [Råd til at investere](/raad-til-investeringer/)
- [Adfærdspsykologi på markedet](/adfaerdspsykologi-aktiemarkedet/)
- [Økonomisk krisehåndtering - min 3 punktsplan](/kriseplan/)
- [Hvornår kan jeg gå ind i markedet](/hvornaar-ind-i-markedet/)
- [Passiv investering slår aktiv investering](/passiv-investering-slaar-aktiv/)
- [Warren Buffett anbefaler indeksfond](/warren-buffett-anbefaler-passive-indekser/)

## Aktier 

Når du køber aktier, så køber du en lille del af en virksomhed. Du kan så tjene penge på, at virksomheden enten betaler udbytte eller stiger i værdi. Prisen af virksomheden fastsættes på det frie marked på forskellige børser rundt omkring i verden. Hvis flere gerne vil købe en aktie, så går prisen op. Hvis flere gerne vil sælge aktier, så går prisen ned.

## Obligationer

Obligationer har traditionelt været det sikre valg til opsparing og til at balancere risikoen i din samlede investering i værdipapirer. Renteniveauet i øjeblikket gør det vanskeligere at få et højt afkast på obligationerne.

Læs mere om [investering i obligationer]({% link _posts/2020-03-09-obligationer.md %}).

## Investeringsforeninger, fonde og ETF'er

Hvis du ikke vil i gang med selv at udvælge gode stabile aktier, så kan du købe investeringsforeninger eller fonde, som vælger aktierne for dig.

## Passiv eller aktiv investering

<div class="feature__wrapper">

{% assign site_posts = site.posts | where: "category", "Investering" | where: "tags", "passiv investering" | sort: "last_modified_at" | reverse %}

{% if site_posts.size > 0 %}
  {% for post in site_posts %}
    {% include archive-single.html type="grid" %}
  {% endfor %}
{% endif %}

</div>

## Passivt forvaltede indeksfonde

Du kan vælge både aktivt forvaltede og passivt forvaltede indeksfonde. Formålet med en passivt forvaltet fond er at følge det indeks, som fonden skal afspejle. Jeg kan godt lide at købe fonde, som følger verdensmarkedet.

Du kan lade dig inspirere på vores [liste over danske investeringsforeninger og passive indeksfonde](/danske-investeringsforeninger-med-passive-indeksfonde/).

<div class="feature__wrapper">

{% assign site_posts = site.posts | where: "category", "Investering" | where: "tags", "indeksfonde" | sort: "last_modified_at" | reverse %}

{% if site_posts.size > 0 %}
  {% for post in site_posts %}
    {% include archive-single.html type="grid" %}
  {% endfor %}
{% endif %}

</div>

## Aktier og skat

Der er ret specifikke regler om, hvordan afkastet og udbytterne ved aktieinvestering og obligationsinvestering er beskattet.

Læs mere om [skat, realisationsbeskatning og lagerbeskatning af aktier her]({% link _posts/2020-06-06-aktiebeskatning.md %}).

## Aktieinvestering på aktiesparekonto

I Danmark har man lanceret en aktiesparekonto, som gør beskatningen lidt lettere. Jeg har lavet en [komplet guide til aktiesparekontoen]({% link _posts/2021-07-04-aktiesparekonto.md %}).

## Hvor kan du investere i aktier og værdipapirer?

Du kan investere i aktier, obligationer og værdipapirer i din bank eller gennem en børsmægler. Omkostningerne ved at investere betyder rigtig meget for dit langsigtede afkast. Derfor kan det betale sig at kigge lidt efter, hvad priserne er. Jeg har skrevet lidt mere om [kurtage og handelsomkostninger ved investeringer her]({% link _posts/2020-03-18-hvad-er-handelsomkostningerne.md %}).

Du kan fx oprette sætte investeringerne på autopilot gennem en [månedsopsparing hos Nordnet]({% link _posts/2019-04-05-nordnet-maanedsopsparing-problemer.md %}) eller få et gratis investeringsforslag hos [Nord Investments](/go/nord/){: rel="sponsored nofollow noopener" }.

## Bæredygtige investeringer i aktier

Jeg har lavet en liste med forslag til [grønne og bæredygtige aktier]({% link _posts/2021-08-05-groenne-aktier.md %}), men ellers kan du også finde [bæredygtige fonde, investeringsforeninger og ETF'er]({% link _posts/2019-04-06-hvordan-investering-baeredygtigt-vol3.md %}).

## Her handler jeg selv aktier og investeringsforeninger

{% include feature_row id="feature_row_own" %}

## Konklusion

Hvis du gerne vil i gang med at investere i aktier og obligationer, så er det altså relativt enkelt at komme i gang.

Hvis du vil bruge et minimum af tid på at sætte dig ind i alle aspekter af aktieinvestering, så kan en ide være at gøre det hele enkelt og starte med at købe fonde, der er passivt forvaltede og som følger verdensmarkedet.

Du kan også investere i [crowdlending og crowdfunding](/crowdlending/) eller i [kryptovaluta og Bitcoins]({% link _posts/2019-03-28-bitcoins.md %}). Jeg har også eksperimenteret med at investere i [investere i ejendomme gennem crowdlending]({% link _posts/2019-03-11-ejendomme-crowdlending.md %}).

## Indlæg om aktier, obligationer og værdipapirer

<div class="feature__wrapper">

{% assign site_posts = site.posts | where: "category", "Investering" | where: "tags", "værdipapirer" | sort: "last_modified_at" | reverse %}

{% if site_posts.size > 0 %}
  {% for post in site_posts %}
    {% include archive-single.html type="grid" %}
  {% endfor %}
{% endif %}

</div>

## Opdateringer om aktieinvesteringer

<div class="feature__wrapper">

{% assign site_posts = site.posts | where: "category", "Opdateringer" | where: "tags", "værdipapirer" | sort: "last_modified_at" | reverse %}

{% if site_posts.size > 0 %}
  {% for post in site_posts %}
    {% include archive-single.html type="grid" %}
  {% endfor %}
{% endif %}

</div>

{% include disclaimer.md %}
