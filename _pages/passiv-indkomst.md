---
layout: single
title: "Passiv indtægt og indkomst"
permalink: /passiv-indkomst/
excerpt: "Opdatering på indtjening af passiv indkomst"
toc: true
---

I marts 2019 startede jeg [mit projekt med at skabe lidt passiv indkomst ved hjælp af _affiliate_- og _referral_-marketing](/projekt-referral-affiliate/) uden at bruge al min tid.

Jeg har følgende sites:

- [Cykel-ruter.dk](http://www.cykel-ruter.dk)
- [Fodboldens Legestue](http://www.legestue.net)
- [Motionsplan.dk](http://www.motionsplan.dk)
- [Teambuildingsøvelser](http://www.teambuilder.dk)

Jeg bruger bl.a. følgende værktøjer:

- Google Adsense
- [Partner-Ads](/go/partnerads/){: rel='sponsored nofollow noopener' }
- [Ezoic](/go/ezoic/){: rel='sponsored nofollow noopener' }

## Indlæg om passiv indkomst

<div class="feature__wrapper">

{% assign site_posts = site.posts | where: "category", "Tjen penge" | sort: "last_modified_at" | reverse %}

{% if site_posts.size > 0 %}
  {% for post in site_posts %}
    {% include archive-single.html type="grid" %}
  {% endfor %}
{% endif %}

</div>

## Passiv indkomst

<iframe width="600" height="371" seamless frameborder="0" scrolling="no" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vQGW14RxupaNWMwAc41OkBrTZVizIehYyLkyKfnWEkKk-akTxGCzs40s8fIAaoqSY6CKALn0jQwhYQ3/pubchart?oid=1805344946&amp;format=image"></iframe>

{% include disclaimer.md %}
