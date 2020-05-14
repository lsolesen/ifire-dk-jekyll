---
layout: splash
title: "Hvad koster de forskellige banker?"
permalink: /bankpriser/
category:
  - Opsparing
tags:
  - bank
excerpt: "Hvad er priserne i de forskellige banker - jeg har tjekket SparNord, Merkur Bank, Lån & Spar Bank, Arbejdernes Landsbank, Lunar og Basisbank?"
header:
  overlay_image: https://images.unsplash.com/photo-1542222024-c39e2281f121?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1500&q=80
  teaser: https://images.unsplash.com/photo-1542222024-c39e2281f121?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=400&q=80
  caption: Photo by Viktor Forgacs on Unsplash
feature_row_solutions:
  - image_path: /assets/images/logo/coinbase.png
    alt: "Coinbase"
    title: "Coinbase"
    excerpt: "[Coinbase\\*](/go/coinbase/) har et rigtig godt _Earn_-program, hvor jeg flere gange har lært meget om forskellige krypotvalutaer. Du får op til 66 DKK Bitcoins ved at købe på Coinbase med [mit link\\*](/go/coinbase/)."
  - image_path: /assets/images/logo/kraken.png
    alt: "Kraken"
    title: "Kraken"
    excerpt: "Jeg køber kryptovaluta og bitcoins på [Kraken\\*](/go/kraken/), som er den billigeste kryptobørs, jeg har kunnet finde. Den er ret let at bruge."
  - image_path: /assets/images/logo/ledger.png
    alt: "Ledger"
    title: "Ledger"
    excerpt: "[Ledger\\*](/go/ledger/) er en hardware wallet til dine kryptovalutaer. Det er helt nødvendigt, hvis du tager sikkerheden seriøst."
classes: wide
toc: false
---

<table>
  {% for row in site.data.bankpriser %}
    {% if forloop.first %}
    <tr>
      {% for pair in row %}
        <th>{{ pair[0] }}</th>
      {% endfor %}
    </tr>
    {% endif %}

    {% tablerow pair in row %}
      {{ pair[1] | markdownify }}
    {% endtablerow %}
  {% endfor %}
</table>
