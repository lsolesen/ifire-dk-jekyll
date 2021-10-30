---
layout: single
title: Anmeldelser
excerpt: "Anmeldelser af forskellige platforme, som kan hjælpe på vejen til økonomisk uafhængighed og finansiel frihed."
permalink: /anmeldelser/
entries_layout: grid # list (default), grid
sort_by: date # date (default) title
sort_order: forward # forward (default), reverse
author_profile: true
---

Jeg laver også [nøjagtige opdateringer af alle de platforme, jeg har investeret på](/platforme/).

{% assign site_posts = site.posts | where: "tags", "anmeldelse" | sort: "title" %}

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
