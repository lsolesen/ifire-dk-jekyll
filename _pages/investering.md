---
layout: single
title: Simpel minimalistisk investering
permalink: /investering/
header:
  overlay_image: https://images.unsplash.com/photo-1466692476868-aef1dfb1e735?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1900&q=80
#  actions:
#    - label: "Presale: Kursus i minimalistik investering"
#      url: "https://ifire.thinkific.com/courses/minimalistisk-investering"
excerpt: "Inspiration til at komme i gang med investeringer selv."
author_profile: true
classes: wide
feature_row_solutions:
  - image_path: /assets/images/logo/nord.png
    alt: "Nord.Investments"
    title: "Nord.Investments"
    excerpt: "[Nord.Investments*](/go/nord/){: rel='sponsored nofollow noopener' } er en investeringsrobot, som ud fra din risikoprofil automatisk sætter dine investeringer op for et relativt lille beløb."
    url: /go/nord/
    btn_label: "Få gratis investeringsprofil*"
    btn_class: "btn--info"
  - image_path: /assets/images/logo/themany.jpg
    alt: "The Many"
    title: "The Many"
    excerpt: "[The Many*](/go/themany/){: rel='sponsored nofollow noopener' } gør det let at lave ejendomsinvesteringer uden selv at skulle stå for administrationen og udlejningen af ejendommene. Du investere i ejendomme for helt ned til 5.000 DKK."
    url: /go/themany/
    btn_label: "Få 250 DKK på The Many*"
    btn_class: "btn--info"
  - image_path: /assets/images/logo/mintos.png
    alt: "Mintos"
    title: "Mintos"
    excerpt: "[Mintos*](/go/mintos/){: rel='sponsored nofollow noopener' } er den største europæiske crowdlending-platform, hvor du får adgang til et meget diversificeret lånemarked og tjen mere end 9%+"
    url: /go/mintos/
    btn_label: "Få Mintos*"
    btn_class: "btn--info"
feature_row_own:
  - image_path: /assets/images/logo/nordnet.png
    excerpt: 'Jeg bruger selv [Nordnet](/go/nordnet/) til at opbygge min portefølje via deres kurtagefri månedsopsparing og aldersopsparingen.'
  - image_path: /assets/images/logo/saxoinvestor.png
    excerpt: Desuden bruger jeg [SaxoInvestor](/go/saxoinvestor/) til min aktiesparekonto og handel uden minimumskurtage.'
---

{% include disclosure.html %}

## Inspiration til investeringer

- [Start med hvorfor?](/start-med-hvorfor/)
- [Råd til at investere](/raad-til-investeringer/)
- [Adfærdspsykologi på markedet](/adfaerdspsykologi-aktiemarkedet/)
- [Økonomisk krisehåndtering - min 3 punktsplan](/kriseplan/)
- [Hvornår kan jeg gå ind i markedet](/hvornaar-ind-i-markedet/)
- [Passiv investering slår aktiv investering](/passiv-investering-slaar-aktiv/)
- [Warren Buffett anbefaler indeksfond](/warren-buffett-anbefaler-passive-indekser/)

## Investeringsløsninger

{% include feature_row id="feature_row_solutions" %}

## Indlæg om investeringer

<div class="feature__wrapper">

{% assign site_posts = site.posts | where: "category", "Investering" | sort: "last_modified_at" | reverse %}

{% if site_posts.size > 0 %}
  {% for post in site_posts %}
    {% include archive-single.html type="grid" %}
  {% endfor %}
{% endif %}

</div>

## Mine investeringer

{% include feature_row id="feature_row_own" type="center" %}

{% include disclaimer.md %}
