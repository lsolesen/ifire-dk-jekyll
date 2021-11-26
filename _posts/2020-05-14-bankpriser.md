---
layout: splash
title: "Hvad koster de forskellige banker?"
permalink: /bankpriser/
category:
  - Privatøkonomi
tags:
  - bank
  - opsparing
excerpt: "Hvad er priserne i de forskellige banker - jeg har tjekket SparNord, Merkur Bank, Lån & Spar Bank, Arbejdernes Landsbank, Lunar og Basisbank?"
header:
  overlay_image: https://images.unsplash.com/photo-1542222024-c39e2281f121?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1500&q=5
  teaser: https://images.unsplash.com/photo-1542222024-c39e2281f121?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=400&q=5
  caption: Photo by Viktor Forgacs on Unsplash
classes: wide
toc: false
last_modified_at: 2020-05-14T16:11:00+08:00
---

<table class="table">
  {% for row in site.data.bankpriser %}
    {% if forloop.first %}
    <thead>
    <tr>
      {% for pair in row %}
        <th>{{ pair[0] }}</th>
      {% endfor %}
    </tr>
    </thead>
    {% endif %}

    {% tablerow pair in row %}
      {{ pair[1] | markdownify }}
    {% endtablerow %}
  {% endfor %}
</table>
