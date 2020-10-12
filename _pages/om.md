---
layout: single
title: "Om iFire"
permalink: /om/
tags:
  - rigdomsformularen
excerpt: "Læs mere om iFire.dk og tankerne bagved."
author_profile: true
---

Velkommen til iFire.dk.

Jeg vil dele og lære mere om, hvordan jeg kan blive **finansiel uafhængig** så hurtigt og sikkert som muligt.

Jeg har altså sat mig for helt i tråd med **rigdomsformularen** at:

- tjene mere,
- forbruge mindre og
- investere (klogere)

Samtidig vil jeg gerne være med til at bryde pengetabuet og dele min strategi.

[Se min samlede portefølje](/portfolio/){: .btn .btn--large .btn--success }

## Tal

- Blogindlæg: {{ site.posts.size }}
- Platforme: {{ site.platforms.size }}

## Følg min status

{% assign site_posts = site.posts | where: "category", "Opdateringer" | sort: "date" %}

{% if site_posts.size > 0 %}
  {% for post in site_posts %}
    {% include archive-single.html %}
  {% endfor %}
{% endif %}

***

{% include disclaimer.md %}
