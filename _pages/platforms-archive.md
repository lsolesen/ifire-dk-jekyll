---
layout: single
title: Crowdlending platforme
excerpt: "Oversigt over crowdlending platforme, jeg investerer i eller har kendskab til."
permalink: /crowdlending-platforme/
redirect_from:
  - /platforme/
author_profile: true
classes: wide
---

{% include disclosure.html %}

{% include crowdlending-warning.html %}

{% assign site_posts = site.platforms | where: "tags", "crowdlending" | sort: "title" %}

{% if site_posts.size > 0 %}
  {% for post in site_posts %}
    {% include archive-single.html type="grid" %}
  {% endfor %}
{% else%}
  Fandt i øjeblikket ikke lige nogen platforme på iFire. Vi arbejder på det.
{% endif %}
