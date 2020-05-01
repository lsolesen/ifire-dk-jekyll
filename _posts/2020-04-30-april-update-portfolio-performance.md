---
title: "#15 April - Portfolio Performance"
permalink: /opdateringer/april-2020-update/
category:
  - Opdateringer
tags:
  - rigdomsformularen
  - status
excerpt: "Jeg er gået lidt kold i mit gamle hjemmelavede regneark, og er ved at lægge tallene ind i Portfolio Performance."
feature_row:
  - image_path: https://imgcdn.saxo.com/_9788702260069/0x500
    alt: "Ét liv, én tid, ét menneske"
    title: "Ét liv, én tid, ét menneske"
    excerpt: "I _Ét liv Én tid Ét menneske_ kritiserer den danske filosof og erhvervsleder Morten Albæk idéen om, at man ved at sætte klarere grænser mellem arbejdstid og fritid, kan løse dette seriøse problem. Ifølge Morten Albæk findes svaret snarere ved at skabe sig et meningsfuldt liv."
    url: https://www.partner-ads.com/dk/klikbanner.php?partnerid=28187&bannerid=43264&htmlurl=https://www.saxo.com/dk/et-liv-en-tid-et-menneske_morten-albaek_haeftet_9788702260069
    btn_label: "Læs mere"
    btn_class: "btn--success"
  - image_path: https://imgcdn.saxo.com/_9780143115762/0x500
    alt: "Your Money or Your Life"
    title: "Your Money or Your Life"
    excerpt: "Start the new year with a fully revised edition of one of the most influential books ever written on personal finance with more than a million copies sold"
    url: https://www.partner-ads.com/dk/klikbanner.php?partnerid=28187&bannerid=43264&htmlurl=https://www.saxo.com/dk/your-money-or-your-life_vicki-robin_paperback_9780143115762
    btn_label: "Læs mere"
    btn_class: "btn--success"
---

Tak fordi du læser med. Jeg er endnu ikke helt færdig med min opdatering, men har fået nogenlunde styr på crowdlending porteføljen, så den præsenterer jeg lige.

Jeg er nemlig blevet lidt træt af mit hjemmelavede regneark, så jeg gik i gang med at eksperimentere med det gratis open source program [PortfolioPerformance.info](http://www.portfolio-performance.info). Jeg håber, at jeg både kan tracke min almindelige investeringer, crowdlending og måske endda min kryptovaluta der.

Jeg er ved at skrive på en artikel om, hvordan jeg bruger det, så kig tilbage om nogle dage.

### Crowdlending

{% include crowdlending-warning.html %}

Jeg er fortsat ved at reducere min eksponering mod crowdlending, men du kan se en oversigt over min månedlige indtjening her.

{% include figure image_path="/assets/images/posts/2020-april-p2p-earnings.jpg" caption="Månedlig indtjening på crowdlending" %}

Jeg har altså en urealiseret gevinst på **1.808 DKK på crowdlending** i denne måned.

Når man kigger på, hvilke platforme der klarer sig godt, så 

{% include figure image_path="/assets/images/posts/2020-april-xirr.jpg" caption="Intern rente på crowdlending" %}

Samlet set har jeg en vægtet intern rente på 3,47% på crowdlending, som stadig har det lidt vanskeligt ved tabene på Envestio og Agrikaab. Jeg har endnu ikke afskrevet Grupeer, men så kan tallet få endnu et dyk nedad.

Mange har været bekymrede omkring [FastInvest\*](/go/fastinvest/), men alle udbetalinger kommer planmæssigt. Jeg forventer dog fortsat at reducere eksponeringen endnu mere.

Mit eksperiment med at trække alle penge ud af [RoboCash\*](/go/robocash/) er i øvrigt endt bedre end frygtet. Som du kan se i oversigten, så er jeg endt med en intern rente på 8,83%. De har lige lovet højere renter, men der er jo stadig et lille stykke op til de 12-14% platformen reklamerer med. Det er dog formentligt det samme for alle platformene, da man først kan se den reelle interne rente, når man realiserer renteindtægterne.

[Kuflink\*](/go/kuflink/) er ejendomsinvestering i britiske pund, og de giver en ret generøs bonus, hvis man investerer i mere end et år, så den interne rente ligger meget højt lige nu, men den kommer til at dale til de omkring 7% platformen forventer at kunne levere.

Ellers er øvelsen fortsat at sænke eksponeringen mod crowdlending og reducere antallet af platforme stille og roligt som lånene løber ud.

[Få 10EUR hos Trine\*](/go/trine/){: .btn .btn--large .btn--warning } eller [Få 25EUR hos Lendahand\*](/go/lendahand/){: .btn .btn--large .btn--danger }

Jeg opdaterer senere med resten af min månedsoversigt, så kig tilbage om nogle dage, hvor jeg forhåbentlig har fået alle oplysningerne ind i Portfolio Performance-programmet.

Det betyder imidlertid også, at jeg formentlig skal til at retænke graferne på mine platform-oversigter. Det tager virkelig lang tid at lave dem. Jeg håber at PP kan være med til at gøre det lidt lettere, men måske kommer jeg til at savne automatiseringen direkte fra Google Sheets til sitet. Jeg går i tænkeboks og vender tilbage.

<div class="grid__wrapper">

{% assign site_posts = site.platforms | where: "tags", "crowdlending" | sort: "title" %}

{% for post in site_posts %}
  {% include archive-teaser-images.html type="grid" %}
{% endfor %}

</div>

{% include disclaimer.md %}
