---
layout: single
created_at: 2019-05-16T10:00:00+08:00
title: Kryptovaluta portefølje
permalink: /kryptovaluta/
redirect_from:
  - /cryptovaluta/
excerpt: "Her kan du se min samlede kryptovaluta portefølje - med intern rente, totalt investeret og indkomst."
author_profile: true
toc: true
last_modified_at: 2020-05-12T10:00:00+08:00
tags:
  - overblik
header:
  teaser: https://images.unsplash.com/photo-1550565360-6986a92b7169?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=400&q=80
  caption: Photo by Dmitry Demidko on Unsplash
feature_row_solutions:
  - image_path: /assets/images/logo/kraken.png
    alt: "Kraken"
    title: "Kraken"
    excerpt: "[Kraken](/go/kraken/){: rel='sponsored nofollow noopener' } er min foretrukne børs til at købe krypto. Den har et fint udvalg og er let at bruge."
    url: /go/kraken/
    btn_label: "Gå til Kraken"
    btn_class: "btn--info"
    rel: sponsored nofollow noopener
  - image_path: /assets/images/logo/coinbase.png
    alt: "Coinbase"
    title: "Coinbase"
    excerpt: "[Coinbase](/go/coinbase/){: rel='sponsored nofollow noopener' } er et let sted at købe kryptovaluta. Hvis du bruger mit link, så får du for 10 USD, når du køber for 100 USD."
    url: /go/coinbase/
    btn_label: "Få 66 DKK på Coinbase"
    btn_class: "btn--info"
    rel: sponsored nofollow noopener
  - image_path: /assets/images/logo/ledger.png
    alt: "Ledger"
    title: "Ledger"
    excerpt: "Den sikreste måde at opbevare kryptovaluta er i en offline hardware wallet. [Ledger](/go/ledger/){: rel='sponsored nofollow noopener' } er førende på markedet."
    url: /go/ledger/
    btn_label: "Tjek prisen"
    btn_class: "btn--info"
    rel: sponsored nofollow noopener
---

Jeg har skrevet en guide til at komme i gang med kryptovaluta og Bitcoins, som indeholder alle de spørgsmål, jeg selv havde, da jeg gik i gang med at investere i kryptovaluta.

## Kryptovaluta guide

Da jeg ville i gang med at investere i kryptovaluta, så stod jeg med en lang række spørgsmål:

- hvad er en kryptovaluta?
- hvilken kryptovaluta kan man investere i?
- hvor handler man kryptovaluta?
- hvordan betaler man skat af kryptovaluta?

Før du kan komme i gang med at lave en **investering i kryptovaluta**, skal du altså vide mere om, hvad det er for en **digital valuta**, og hvordan man laver en **kryptovaluta handel**.

## Bitcoins

Bitcoins er den ældste og mest kendte kryptovaluta. Jeg har skrevet en komplet [guide til, hvad Bitcoins er](/bitcoins/) her.

## Hvilken kryptovaluta skal man investere i?

Der er virkelig mange forskellige kryptovalutaer og _coins_. Det mest kendte er Bitcoins og Ethereum, men listen er lang. Det er samtidig et ureguleret marked, hvor du hurtigt kan brænde nallerne.

Jeg har skrevet en guide til, [hvilken kryptovaluta man kan investere i her]({% link _posts/2019-05-03-crypto-porfolio.md %})

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
