---
layout: single
title: Kryptovaluta portefølje
permalink: /cryptovaluta/
excerpt: "Her kan du se min samlede cryptovaluta portefølje - med intern rente, totalt investeret og indkomst."
author_profile: true
toc: false
last_modified_at: 2020-05-12T10:00:00+08:00
feature_row_solutions:
  - image_path: /assets/images/logo/kraken.png
    alt: "Kraken"
    title: "Kraken"
    excerpt: "[Kraken*](/go/kraken/) er min foretrukne børs til at købe krypto. Den har et fint udvalg og er let at bruge."
    url: /go/kraken/
    btn_label: "Gå til Kraken*"
    btn_class: "btn--info"
  - image_path: /assets/images/logo/coinbase.png
    alt: "Coinbase"
    title: "Coinbase"
    excerpt: "[Coinbase*](/go/coinbase/) er et let sted at købe kryptovaluta. Hvis du bruger mit link, så får du for 10 USD, når du køber for 100 USD."
    url: /go/coinbase/
    btn_label: "Få 66 DKK på Coinbase*"
    btn_class: "btn--info"
  - image_path: /assets/images/logo/ledger.png
    alt: "Ledger"
    title: "Ledger"
    excerpt: "Den sikreste måde at opbevare kryptovaluta er i en offline hardware wallet. [Ledger*](/go/ledger/) er førende på markedet."
    url: /go/ledger/
    btn_label: "Køb Ledger*"
    btn_class: "btn--info"
---

{% include disclosure.html %}

## Mine artikler om kryptovaluta

<div class="feature__wrapper">

{% assign site_posts = site.posts | where: "tags", "kryptovaluta" | sort: "date" %}

{% for post in site_posts %}
  {% include archive-single.html type="grid" %}
{% endfor %}

</div>

## Porteføljeværdi

{% include figure image_path="/assets/images/status/crypto-value.jpg" caption="Samlede værdi af kryptovaluta" %}

## Sammensætning af kryptoportefølje

{% include figure image_path="/assets/images/status/crypto-allocation.jpg" caption="Sammensætning af kryptovaluta-porteføljen" %}

## Performance

{% include figure image_path="/assets/images/status/crypto-performance.jpg" caption="Performance for kryptovaluta-porteføljen" %}

{% include feature_row id="feature_row_solutions" %}

{% include disclaimer.md %}
