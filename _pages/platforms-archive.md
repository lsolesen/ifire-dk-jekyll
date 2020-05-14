---
layout: single
title: Crowdlending, crowdfunding og P2P-platforme
excerpt: "Oversigt over platofmre for crowdlending, crowdfunding og P2P-investeringer, som jeg investerer i eller har kendskab til."
permalink: /crowdlending-platforme/
redirect_from:
  - /platforme/
author_profile: true
classes: wide
---

{% include disclosure.html %}

{% include crowdlending-warning.html %}

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
