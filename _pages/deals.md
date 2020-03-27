---
layout: single
title: "Deals, affiliate og referrallinks på iFire"
permalink: /deals/
excerpt: "Her er nogle af de bedste deals."
author_profile: true
toc: false
---

## Crowdlending og crowdfunding

{% assign deals = site.platforms | where: "tags", "crowdlending" | where_exp: "item", "item.deal != ''" %}
{% for d in deals %}
  {% if everything.size > 0 %}
    {% assign everything = d.deal | concat: everything %}
  {% else %}
    {% assign everything = d.deal %}
  {% endif %}
{% endfor %}
{% include feature_row array=everything %}

***

## Betalingskort og bankkonti

{% assign everything = "" %}
{% assign banks = site.platforms | where: "tags", "betalingskort" | where_exp: "item", "item.deal != ''" %}
{% for d in banks %}
  {% if everything.size > 0 %}
    {% assign everything = d.deal | concat: everything %}
  {% else %}
    {% assign everything = d.deal %}
  {% endif %}
{% endfor %}
{% include feature_row array=everything %}

***

## Investering i værdipapirer

{% assign everything = "" %}
{% assign investments = site.platforms | where: "tags", "investering" | where_exp: "item", "item.deal != ''" %}
{% for d in investments %}
  {% if everything.size > 0 %}
    {% assign everything = d.deal | concat: everything %}
  {% else %}
    {% assign everything = d.deal %}
  {% endif %}
{% endfor %}
{% include feature_row array=everything %}

***

## Deals til rejsen

{% assign everything = "" %}
{% assign travel = site.redirects | where: "tags", "rejse" | where_exp: "item", "item.deal != ''" %}
{% for d in travel %}
  {% if everything.size > 0 %}
    {% assign everything = d.deal | concat: everything %}
  {% else %}
    {% assign everything = d.deal %}
  {% endif %}
{% endfor %}
{% include feature_row array=everything %}

***

{% include disclaimer.md %}
