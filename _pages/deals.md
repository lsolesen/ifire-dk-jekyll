---
layout: single
title: "Deals, affiliate og referrallinks på iFire"
permalink: /deals/
excerpt: "Her er nogle af de bedste deals."
author_profile: true
toc: true
---

## Crowdlending og crowdfunding

{% assign site_posts = site.redirects | where: "tags", "crowdlending" | sort: "date" %}

{% if site_posts.size > 0 %}
  {% for post in site_posts %}
    {% if post.excerpt.size > 1 %}
### {{ post.title }}
{{ post.excerpt }}
[Gå til {{ post.title }}*]({{ post.redirect_to }}){: .btn .btn--large .btn--info}
    {% endif %}
  {% endfor %}
{% else%}
  Fandt i øjeblikket ikke lige nogen deals på iFire. Vi arbejder på det.
{% endif %}

***

{% assign site_posts = site.redirects | where: "tags", "crowdlending" | sort: "date" %}

{% if site_posts.size > 0 %}
  {% for post in site_posts %}
    {% if post.excerpt.size <= 1 %}
### {{ post.title }}
{{ post.excerpt }}
[Gå til {{ post.title }}*]({{ post.redirect_to }}){: .btn .btn--large .btn--info}
    {% endif %}
  {% endfor %}
{% else%}
  Fandt i øjeblikket ikke lige nogen deals på iFire. Vi arbejder på det.
{% endif %}

***

## Betalingskort og bankkonti

{% assign site_posts = site.redirects | where: "tags", "betalingskort" | sort: "date" %}

{% if site_posts.size > 0 %}
  {% for post in site_posts %}
    {% if post.excerpt.size > 1 %}
### {{ post.title }}
{{ post.excerpt }}
[Gå til {{ post.title }}*]({{ post.redirect_to }}){: .btn .btn--large .btn--info}
    {% endif %}
  {% endfor %}
{% else%}
  Fandt i øjeblikket ikke lige nogen deals på iFire. Vi arbejder på det.
{% endif %}

***

{% assign site_posts = site.redirects | where: "tags", "betalingskort" | sort: "date" %}

{% if site_posts.size > 0 %}
  {% for post in site_posts %}
    {% if post.excerpt.size <= 1 %}
### {{ post.title }}
{{ post.excerpt }}
[Gå til {{ post.title }}*]({{ post.redirect_to }}){: .btn .btn--large .btn--info}
    {% endif %}
  {% endfor %}
{% else%}
  Fandt i øjeblikket ikke lige nogen deals på iFire. Vi arbejder på det.
{% endif %}

***

## Investering i værdipapirer

{% assign site_posts = site.redirects | where: "tags", "investering" | sort: "date" %}

{% if site_posts.size > 0 %}
  {% for post in site_posts %}
    {% if post.excerpt.size > 1 %}
### {{ post.title }}
{{ post.excerpt }}
[Gå til {{ post.title }}*]({{ post.redirect_to }}){: .btn .btn--large .btn--info}
    {% endif %}
  {% endfor %}
{% else%}
  Fandt i øjeblikket ikke lige nogen deals på iFire. Vi arbejder på det.
{% endif %}

***

{% assign site_posts = site.redirects | where: "tags", "investering" | sort: "date" %}

{% if site_posts.size > 0 %}
  {% for post in site_posts %}
    {% if post.excerpt.size <= 1 %}
### {{ post.title }}
{{ post.excerpt }}
[Gå til {{ post.title }}*]({{ post.redirect_to }}){: .btn .btn--large .btn--info}
    {% endif %}
  {% endfor %}
{% else%}
  Fandt i øjeblikket ikke lige nogen deals på iFire. Vi arbejder på det.
{% endif %}

***

## Deals til rejsen

{% assign site_posts = site.redirects | where: "tags", "rejse" | sort: "date" %}

{% if site_posts.size > 0 %}
  {% for post in site_posts %}
    {% if post.excerpt.size > 1 %}
### {{ post.title }}
{{ post.excerpt }}
[Gå til {{ post.title }}*]({{ post.redirect_to }}){: .btn .btn--large .btn--info}
    {% endif %}
  {% endfor %}
{% else%}
  Fandt i øjeblikket ikke lige nogen deals på iFire. Vi arbejder på det.
{% endif %}

***

{% assign site_posts = site.redirects | where: "tags", "rejse" | sort: "date" %}

{% if site_posts.size > 0 %}
  {% for post in site_posts %}
    {% if post.excerpt.size <= 1 %}
### {{ post.title }}
{{ post.excerpt }}
[Gå til {{ post.title }}*]({{ post.redirect_to }}){: .btn .btn--large .btn--info}
    {% endif %}
  {% endfor %}
{% else%}
  Fandt i øjeblikket ikke lige nogen deals på iFire. Vi arbejder på det.
{% endif %}

***

{% include disclaimer.md %}
