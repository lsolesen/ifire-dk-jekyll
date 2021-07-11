---
layout: posts
permalink: /blog/
title: Blog
seo_title: "Blog om FIRE, økonomisk frihed og finansiel uafhængighed"
description: Blog om økonomisk og finansiel uafhængighed, FIRE og frihed igennem investering med tanker om bæredygtighed.
excerpt: "Blog om FIRE, økonomisk og finansiel uafhængighed, FIRE og frihed igennem investering med tanker om bæredygtighed."
classes: wide
author_profile: true
header:
  overlay_image: https://images.unsplash.com/photo-1466692476868-aef1dfb1e735?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1500&q=80
#  actions:
#    - label: "Presale: Kursus i minimalistik investering"
#      url: "https://ifire.thinkific.com/courses/minimalistisk-investering"
platforms:
  - excerpt: '[Se alle crowdlending platformene](/crowdlending/){: .btn .btn--large .btn--success }'
---

Blog om FIRE, økonomisk og finansiel uafhængighed, FIRE og frihed igennem investering med tanker om bæredygtighed.

Hvis du er interesseret i at læse alle mine [opdateringer, så har jeg samlet dem her](/opdateringer/).

<h2>Tjek de nyeste indlæg på ifire.dk</h2>

<div class="feature__wrapper">

{% assign site_posts = site.posts | sort: "last_modified_at" | reverse %}

{% if site_posts.size > 0 %}
  {% for post in site_posts limit:16 %}
    {% include archive-single.html type="grid" %}
  {% endfor %}
{% endif %}

</div>
