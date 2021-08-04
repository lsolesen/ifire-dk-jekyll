---
layout: single
title: Crowdlending, crowdfunding og P2P-platforme
excerpt: "Danske og udenlandske platforme for crowdlending, crowdfunding og P2P-investeringer, som jeg investerer i"
permalink: /crowdlending-platforme/
redirect_from:
  - /platforme/
author_profile: true
classes: wide
feature_row:
  - image_path: https://www.opheliainvest.dk/wp-content/uploads/2020/05/Screenshot-2020-05-04-at-18.36.12.png
    alt: "Den lille guide til Crowdlending"
    title: "Den lille guide til Crowdlending"
    excerpt: "I denne bog får du en grundig og lettilgængelig indføring i emnet crowdlending, som er en passiv investeringsform. Formålet er at skabe et fast, løbende afkast. Guiden introducerer dig for lånemarkedet, og giver svar på alle de gængse spørgsmål vedrørende risikostyring, skat, valg af investeringsplatform og meget mere."
    url: https://www.opheliainvest.dk/vare/den-lille-guide-til-crowdlending/?ref=507
    btn_label: "Læs mere"
    btn_class: "btn--success"
---

{% include disclosure.html %}

{% comment %}

## Search intent
De bedste crowdlending platforme i 2021 ⇒ Se Top 5 | LÆS ...
Crowdlending for begyndere ⇒ Find den bedste platform her 
Crowdlending platforme ⇒ Se de bedste 5 platforme her [2021 ]
Crowdlending i Danmark - Find 5 platforme her | LendMe
Crowdlending for begyndere - Kopier vores strategi [2021]

{% endcomment %}

## Danske crowdlending og crowdfunding sites

{% assign site_posts = site.platforms | where: "tags", "Danmark" | where: "tags", "crowdlending" | sort: "title" %}

<div class="feature__wrapper">

{% if site_posts.size > 0 %}
  {% for post in site_posts %}
    {% include archive-single.html type="grid" %}
  {% endfor %}
{% else%}
  Fandt i øjeblikket ikke lige nogen platforme på iFire. Vi arbejder på det.
{% endif %}

</div>

## Alle crowdlending, P2P-investeringer og crowdfunding sites

{% assign site_posts = site.platforms | where: "tags", "crowdlending" | sort: "title" %}

<div class="feature__wrapper">

{% if site_posts.size > 0 %}
  {% for post in site_posts %}
    {% include archive-single.html type="grid" %}
  {% endfor %}
{% else%}
  Fandt i øjeblikket ikke lige nogen platforme på iFire. Vi arbejder på det.
{% endif %}

</div>

{% include feature_row type="left" %}
