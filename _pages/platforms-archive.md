---
layout: single
title: Crowdlending, crowdfunding og P2P-platforme
excerpt: "Danske og udenlandske platforme for crowdlending, crowdfunding og P2P-investeringer, som jeg investerer i"
permalink: /crowdlending-platforme/
redirect_from:
  - /platforme/
author_profile: true
classes: wide
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
