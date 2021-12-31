---
title: &title "Populære blog posts på Ifire i 2021 🥇"
permalink: /populaere-posts/
language: da
header:
  overlay_image: https://images.unsplash.com/photo-1461263895214-7761d3a942de?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=1984&q=5
  teaser: https://images.unsplash.com/photo-1461263895214-7761d3a942de?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=400&q=5
  caption: *title
tags:
  - blog
category:
  - Opdateringer
last_modified_at: 2021-12-31T18:21:26Z
popular_posts_2021:
  - /lagerbeskatning-etf-fordel-eller-ulempe/
  - /skat-af-aktier/
  - /madbudget-undgaa-luksusfaelden-med-madplan/
  - /danske-investeringsforeninger-med-passive-indeksfonde/
  - /bagestaal-vs-bagesten-anmeldelse/
  - /beregn-timeloen/
  - /investering-vol9/
  - /dansk-crowdlending/
  - /gratis-tv-online-nettet/
  - /investering-vol3/
popular_posts_2020:
  - /lagerbeskatning-etf-fordel-eller-ulempe/
  - /skat-af-aktier/
  - /investering-vol3/
  - /investering-vol9/
  - /hvad-er-okonomisk-frihed/
  - /ejendomme-i-portefoljen/
  - /hvad-er-investeringsforeninger-og-etfer/
  - /dansk-crowdlending/
  - /nordnet-maanedsopsparing-problemer/
  - /hvordan-tracker-jeg-min-portefolje/
---

Det har været et godt år på Ifire. Vi har skrevet en del artikler, og vores besøgstal er virkelig gået i vejret.

Her har vi samlet de mest populære blog posts. Der er nogle ældre blog posts, men en del af de nye artikler har også fundet vej til top {{ page.popular_posts_2021.size }} listen.

## De {{ page.popular_posts_2021.size }} mest populære blog posts i løbet af 2021

I alt havde vi 36.346 brugere, der læste på 64.373 sider på ifire.dk i løbet af 2021. Du kan se de mest populære blog posts her:

{% for permalink in page.popular_posts_2021 %}

{% assign site_posts = site.posts | where: "permalink", permalink %}

{% if site_posts.size > 0 %}
  {% for post in site_posts %}
    {% include archive-single.html %}
  {% endfor %}
{% endif %}

{% endfor %}

## De {{ page.popular_posts_2020.size }} mest populære blog posts i løbet af 2020

{% for permalink in page.popular_posts_2020 %}

{% assign site_posts = site.posts | where: "permalink", permalink %}

{% if site_posts.size > 0 %}
  {% for post in site_posts %}
    {% include archive-single.html %}
  {% endfor %}
{% endif %}

{% endfor %}

## Blog posts skrevet i 2020-2021

{% assign date_from = '2020-01-01' | date: '%s' %}
{% assign date_to = '2021-12-31' | date: '%s' %}

{% assign site_posts = site.posts | where_exp: "post", "post.url != page.url" | sort: "last_modified_at" %}

<div class="feature__wrapper">

{% if site_posts.size > 0 %}
  {% for post in site_posts %}
    {% capture current_year %}{{ post.date | date: "%Y" }}{% endcapture %}
    {% if current_year == '2020' %}
      {% include archive-single.html type="grid" %}
    {% endif %}
  {% endfor %}
{% endif %}

</div>
