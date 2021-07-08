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
    excerpt: "[Nord.Investments](/go/nord/){: rel='sponsored nofollow noopener' } er en investeringsrobot, som ud fra din risikoprofil automatisk sætter dine investeringer op for et relativt lille beløb."
    url: /go/nord/
    btn_label: "Få gratis investeringsprofil"
    btn_class: "btn--info"
  - image_path: /assets/images/logo/themany.jpg
    alt: "The Many"
    title: "The Many"
    excerpt: "[The Many](/go/themany/){: rel='sponsored nofollow noopener' } gør det let at lave ejendomsinvesteringer uden selv at skulle stå for administrationen og udlejningen af ejendommene. Du investere i ejendomme for helt ned til 5.000 DKK."
    url: /go/themany/
    btn_label: "Få 250 DKK på The Many"
    btn_class: "btn--info"
  - image_path: /assets/images/logo/mintos.png
    alt: "Mintos"
    title: "Mintos"
    excerpt: "[Mintos](/go/mintos/){: rel='sponsored nofollow noopener' } er den største europæiske crowdlending-platform, hvor du får adgang til et meget diversificeret lånemarked og tjen mere end 9%+"
    url: /go/mintos/
    btn_label: "Få Mintos"
    btn_class: "btn--info"
feature_row_own:
  - image_path: /assets/images/logo/nordnet.png
    excerpt: 'Jeg bruger selv [Nordnet](/go/nordnet/) til at opbygge min portefølje via deres kurtagefri månedsopsparing og aldersopsparingen.'
  - image_path: /assets/images/logo/saxoinvestor.png
    excerpt: Desuden bruger jeg [SaxoInvestor](/go/saxoinvestor/) til min aktiesparekonto og handel uden minimumskurtage.'
---

En investering er når du sætter dine penge i noget, som du forventer vil give et afkast. Afkastet kan både komme over tid ved at beholde investeringen, eller det kan være penge investoren håber at kunne få hjem ved et fremtidigt salg. 

Investeringer kan være en af [mange ideer til at skabe passiv indkomst](/passiv-indkomst/). Du kan både investere tid, men du kan også investere penge. Og selvom du investerer penge, så kræver det også lidt tid.

En investering kan være i mange ting, men her fokuserer jeg på investeringer i aktier og værdipapirer, crowdlending, metaller og kryptovaluta.

{% comment %}

## Hvad er en investering?

Der er mange måder at investere dine penge på. Du kan investere i en ejendom eller i en række af aktier. Det, der ligger i ordet investering, er, at du bruger dine penge eller ressourcer på noget, som du satser på, vil give dig flere penge på den lange bane. Det gælder både, hvad enten du så køber en ejerlejlighed eller investerer penge i aktier i en fremadstormende virksomhed.

Når du investerer penge, vil det altid være med en forventning eller et håb om, at du får flere penge ud af din investering i sidste ende. Men der er aldrig garanti, når det kommer til en investering. Du kan både gøre gode investeringer og dårlige investeringer.

Gode og dårlige investeringer
En investering kan være mange forskellige ting. De typiske investeringer, som privatpersoner foretager, er i værdipapirer, som aktier og obligationer, eller ved køb af ejendomme eller biler.

Det er meget forskelligt, om en aktie eller en ejendom ender ud med at være en god investering. Det er der ingen, der kan forudsige med hundrede procent sikkerhed. Biler derimod er i langt de fleste tilfælde en dårlig investering, da de meget hurtigt falder i værdi – dog vil eksempelvis antikke biler stige i værdi med tiden.

Bil versus ejendom
Har du købt en lejlighed, kan du sagtens ende ud med at få flere penge for den, end du selv har givet, da du købte den. Det vil meget sjældent være tilfældet med en bil.

Så snart en bil ikke er ny længere, men har kørt nogle kilometer, falder den betydeligt i værdi. Og det vil fortsætte år for år. En lejlighed vil ikke nødvendigvis tabe værdi, selvom den bliver brugt. Dens pris er afhængig af boligmarkedets udvikling og udviklingen og populariteten af området, som boligen ligger i.

Du kan altså både ende med at tabe eller vinde penge, når du investerer i ejendomme, mens du næsten kan være sikker på at tabe penge, når du køber en bil.

{% endcomment %}

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
