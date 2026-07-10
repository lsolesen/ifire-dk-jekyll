---
layout: single
title: "Min Strategi: Fundamentet bag min finansielle frihed"
permalink: /min-strategi/
excerpt: "Her får du det samlede overblik over min personlige FIRE-strategi. Systemet er bygget op omkring fire søjler: Min økonomi, min investeringsstrategi, min portefølje og min investorrejse."
author_profile: true
toc: true
toc_sticky: true
header:
  overlay_image: https://images.unsplash.com/photo-1466692476868-aef1dfb1e735?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1500&q=5
  caption: "Min Strategi: Vejen til finansiel frihed"
---

{{ page.excerpt }}

Da jeg startede iFire, var det for at dokumentere min søgen efter økonomisk uafhængighed. Gennem årene har jeg draget mange erfaringer, begået dyre fejl og omlagt mine metoder flere gange. 

I dag står min samlede filosofi fuldstændig klart. Det er ikke raketvidenskab, men kan koges ned til den simple **Rigdomsformel**:

> **Tjene mere --> Forbruge mindre --> Investere klogere**

For at gøre strategien overskuelig, har jeg delt mit univers op i fire forbundne søjler. De dækker alt fra min adfærd i hverdagen til de konkrete fonde i mit maskinrum.

---

## De 4 søjler i min FIRE-strategi

### 1. Min Økonomi (Hverdagen og budgettet)
Investering er kun den ene halvdel af ligningen. Forudsætningen for at kunne sende penge ud at arbejde er, at du skaber et overskud i din hverdagsøkonomi. 

I denne sektion viser jeg min forbrugsfilosofi. Jeg fjerner bevidstløst klatforbrug og optimerer mine faste udgifter (som forsikringer og el) for at banke min opsparingsrate i vejret – uden at det går ud over min livskvalitet.

* **[Dyk ned i Min Økonomi og mine sparetips](/min-oekonomi/)**

### 2. Min Investeringsstrategi (Mit kompas)
Når overskuddet fra hverdagen er skabt, skal pengene placeres i markedet. Her følger jeg en række faste, ufravigelige principper: Jeg forsøger ikke at slå markedet, jeg timer ikke markedet, og jeg minimerer mine årlige omkostninger (ÅOP). 

Her kan du læse om min risikoprofil (hvorfor jeg kører 100% aktier på den lange bane) og mine overvejelser omkring de danske skatteregler.

* **[Læs hele Min Investeringsstrategi](/min-investeringsstrategi/)**

### 3. Min Portefølje (Maskinrummet)
Dette er siden, hvor jeg smider alle kortene på bordet. Her viser jeg præcis, hvordan min formue er fordelt i virkeligheden, og hvilke specifikke værdipapirer jeg ejer. 

Gennemgangen dækker alt fra min Aktiesparekonto og mine frie midler hos Nordnet til min firmapension hos Velliv og min kontante nødopsparing.

* **[Se kigget direkte ind i Min Portefølje](/portfolio/)**

### 4. Min Investorrejse (Historien og lærepengene)
Jeg er ikke landet på en simpel indeks-strategi ved et tilfælde. Vejen dertil har været et vildt eventyr fyldt med eksperimenter. 

Her finder du mit historiske arkiv og mine hudløst ærlige beretninger om dengang, jeg tabte bukserne på kryptovaluta og uregulerede crowdlending-platforme i udlandet. Det er mit private "museum", der beviser, hvorfor enkelhed altid vinder i sidste ende.

* **[Følg Min Investorrejse og se mine største fejl](/investorrejse/)**

---

## Tjek de nyeste betragtninger på bloggen

Selvom min overordnede strategi ligger fast, dukker der løbende nye overvejelser, sparetips og markedsbetragtninger op i hverdagen. Du kan dykke ned i de nyeste artikler her:

<div class="feature__wrapper">

{% assign site_posts = site.posts | sort: "last_modified_at" | reverse %}

{% if site_posts.size > 0 %}
  {% for post in site_posts limit:4 %}
    {% include archive-single.html type="grid" %}
  {% endfor %}
{% endif %}

</div>

{% include disclaimer.md %}