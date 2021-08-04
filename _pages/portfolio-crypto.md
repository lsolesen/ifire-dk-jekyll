---
layout: single
created_at: 2019-05-16T10:00:00+08:00
title: Kryptovaluta portefølje
permalink: /mine-investeringer/kryptovaluta/
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

Her kan du læse om mine erfaringer med investering i kryptovaluta. Det er ikke helt så let at komme i gang med som [investering i aktier]({% link _pages/investering-aktier.md %}), men faktisk er det heller ikke så bøvlet som man skulle tro.

Inden du går i gang, så kan du med fordel læse min [guide til investering i kryptovaluta]({% link _pages/investering-crypto.md %}). Jeg har investeret i et par forskellige digitale valutaer, men [Bitcoins](/bitcoins/) og [Ethereum](/ethereum/) fylder mest i porteføljen.

Jeg havde flere overvejelser, inden jeg begyndte at investere i nogle af de digitale *coins*, og du kan læse om nogle af [mulighederne for at investere i kryptovalutaher]({% link _posts/2019-05-03-crypto-porfolio.md %})

{% include disclosure.html %}

## Porteføljeværdi

{% include figure image_path="/assets/images/status/crypto-value.jpg" caption="Samlede værdi af kryptovaluta" %}

## Sammensætning af kryptoportefølje

{% include figure image_path="/assets/images/status/crypto-allocation.jpg" caption="Sammensætning af kryptovaluta-porteføljen" %}

## Performance

{% include figure image_path="/assets/images/status/crypto-performance.jpg" caption="Performance for kryptovaluta-porteføljen" %}

## Anbefalinger

{% include feature_row id="feature_row_solutions" %}

## Mine artikler om kryptovaluta

<div class="feature__wrapper">

{% assign site_posts = site.posts | where: "tags", "kryptovaluta" | sort: "date" %}

{% for post in site_posts %}
  {% include archive-single.html type="grid" %}
{% endfor %}

</div>

{% include disclaimer.md %}
