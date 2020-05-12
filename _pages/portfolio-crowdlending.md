---
layout: single
title: Crowdlending portefølje
permalink: /crowdlending/
excerpt: "Her kan du se min samlede portefølje crowdlending - med intern rente, totalt investeret og indkomst."
author_profile: true
toc: true
toc_sticky: true
last_modified_at: 2020-05-12T10:00:00+08:00
---

{% include disclosure.html %}

{% include crowdlending-warning.html %}

Jeg har en del penge investeret i crowdlending. Du kan se [præcise opdateringer om, hvordan det går med den enkelte platform](/platforme/).

## Udvikling i værdi af crowdlending

**Selvom der tilskrives renter løbende på de enkelte platforme, skal du være opmærksom på, at tallene er urealiseret indkomst indtil pengene er hævet fra platformen. En platform kan gå ned eller være svindel, som det ses i crowdlending. Crowdlending er en højrisiko investeringsform.**

{% include figure image_path="/assets/images/status/p2p-value.jpg" caption="Samlede værdi af crowdlending"  %}

## Fordeling på crowdlending platforme

{% include figure image_path="/assets/images/status/p2p-allocation.jpg" caption="Allokering mellem forskellige crowdlending platforme" %}

### Total indkomst fra crowdlending

{% include figure image_path="/assets/images/status/p2p-year-income-april-2020.jpg" caption="Income in crowdlending - status april 2020" %}

{% include figure image_path="/assets/images/status/p2p-income-april-2020.jpg" caption="Income in crowdlending - status april 2020" %}

### XIRR for crowdlending

Crowdlending har været udfordret i 2020, og jeg har haft nogle relativt store tab på Envestio og Agrikaab. Det fremgår tydeligt at nedenstående performancegraf, at der er udfordringer.

{% include figure image_path="/assets/images/status/p2p-performance.jpg" caption="Crowdlending ser voldsomt ud, når man mister hele indskuddet." %}

[Trine\*](/go/trine/){: .btn .btn--large .btn--warning }

#### Status april 2020

Herunder er et øjebliksbillede fra april 2020.

{% include figure image_path="/assets/images/status/p2p-xirr-april-2020.jpg" caption="Øjebliksbillede fra april 2020 på mine crowdlendingplatforme" %}

[Kom i gang med crowdlending på Mintos\*](/go/mintos/){: .btn .btn--large .btn--info }

## Forskellige typer crowdlending

Jeg har forsøgt at dele mine crowdlending investeringer op i almindelige forbrugslån, lån til projekter og endelig lån til ejendomsinvesteringer, som giver huslejeudbytte.

{% include figure image_path="/assets/images/status/p2p-allocation-groups.jpg" caption="Crowdlending fordelt på typer" %}

[Opret dig på Mintos\*](/go/mintos/){: .btn .btn--large .btn--info } eller [Bondora\*](/go/bondora/){: .btn .btn--large .btn--success }

## Crowdlending platforme

<div class="feature__wrapper">

{% assign site_posts = site.platforms | where: "tags", "crowdlending" | sort: "title" %}

{% for post in site_posts %}
  {% include archive-teaser-images.html type="grid" %}
{% endfor %}

</div>

{% include disclaimer.md %}
