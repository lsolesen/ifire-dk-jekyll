---
layout: single
title: &title "Min investeringsportefølje: Status og aktivallokering"
permalink: /portfolio/
excerpt: "Her kan du se opbygningen af min samlede investeringsportefølje. Efter mange år med komplekse eksperimenter er alt i dag skåret helt ind til benet med fokus på indeksfonde."
author_profile: true
toc: true
last_modified_at: 2026-07-06T12:00:00+02:00
tags:
  - overblik
header:
  teaser: https://images.unsplash.com/photo-1526628953301-3e589a6a8b74?auto=format&fit=crop&h=300&w=400&q=10
  caption: *title
---

{{ page.excerpt }}

Jeg har investeret på de finansielle markeder i mange år. Gennem tiden har jeg bevæget mig vidt omkring og eksperimenteret med alt fra enkeltaktier, komplekse ejendoms-ETF'er, crowdlending, guld og kryptovaluta for at jage det optimale afkast.

Men erfaring avler modenhed. I dag har jeg gennemført en omfattende hovedrengøring og strømlinet hele min formuestruktur. 

Min investeringsfilosofi som 50-årig kan koges ned til tre simple principper: **Minimer omkostningerne (ÅOP), maksimer renters rente gennem brede indeks, og hold administrationen på et absolut minimum.** Jeg ejer ingen mursten, så hele mit økonomiske fundament arbejder passivt i markedet.

Du kan læse den fulde historie om min omlægning her: **[Fra komplekst til knivskarpt: Mit komplette investeringssetup](/egen-investering/)**.

---

## Min overordnede aktivallokering (Asset Allocation)

Hvor jeg tidligere havde spredt mine midler ud over mange spekulative aktivklasser, er min portefølje i dag centreret omkring én stor kerne:

### 1. Aktier og Indeksfonde (Kernen)

Den absolut største del af min formue er placeret i brede, markedsvægtede og billige aktieindeks. I mine frie midler bruger jeg den realisationsbeskattede *Sparinvest Index Globale Aktier KL* for at udskyde skatten mest muligt, mens mine pensionsmidler (Velliv) og min Aktiesparekonto er sat på fuldstændig passiv autopilot via globale ETF'er.

* **[Dyk ned i min aktieportefølje og depotstruktur](/investeringer/)**

### 2. Crowdlending (Satellitten)

Efter at have testet over 20 platforme og mistet penge på uregulerede svindelnumre undervejs, har jeg likvideret 80-90 % af mine crowdlending-midler. Jeg betragter i dag udelukkende crowdlending som et mindre satellit-aktiv. De eneste platforme, der har overlevet min udskilning, er de fuldt regulerede aktører *Mintos*, *PeerBerry* og skandinaviske *Kameo*.

* **[Læs min begynderguide og erfaringer med crowdlending](/crowdlending/)**

### 3. Alternativ allokering (Guld og Krypto)

Tidligere fyldte kryptovaluta (især Bitcoin og Ethereum) samt eksperimenter med råvarer en del i mine overvejelser. I dag er spekulativ krypto skåret helt væk, fordi det er for besværligt. Jeg har bevaret en meget lille, symbolsk flig af råvarer (f.eks. fysisk sikret guld via *Xetra-Gold*) placeret udelukkende inde i mit pensionsmiljø (Aldersopsparingen), hvor  lagerbeskatningen og beskatning som kapitalindkomst er til at leve med.

---

## Strategi: Hvorfor enkelhed slår alt

Mange investorer bruger timevis hver uge på at overvåge grafer, læse årsregnskaber eller jagte den næste populære aktivklasse. Min erfaring viser dog, at det sjældent betaler sig, når man modregner tidsforbrug, handelsomkostninger og skattebøvl.

Ved at vælge en minimalistisk tilgang opnår jeg:

* **Maksimeret renters rente:** Ingen unødvendig minimumskurtage eller hyppige ombytninger, der udløser unødig beskatning.
* **Intet administrativt cash drag:** Midlerne geninvesteres automatisk med det samme i stedet for at stå som døde kontanter.
* **Fuld automatisering:** Min Månedsopsparing og mine pensionsindbetalinger passer sig selv. Jeg skal ikke logge ind på 20 forskellige dashboards for at bevare overblikket.

---

## Detaljeret overblik over mine investeringer

Herunder kan du klikke dig videre ind på mine specifikke statussider for de enkelte aktivklasser, hvor jeg løbende opdaterer mine guides, platformanmeldelser og strategiske overvejelser.

<div class="feature__wrapper">
{% assign site_posts = site.pages | where: "tags", "overblik" | sort: "created_at" %}
{% if site_posts.size > 0 %}
  {% for post in site_posts %}
    {% unless post.url == page.url %}
      {% include archive-single.html type="grid" %}
    {% endunless %}
  {% endfor %}
{% endif %}
</div>

{% include disclaimer.md %}