---
title: "Fordeling af aktiver i investeringen? #5"
last_modified_at: 2019-04-26T20:12:02+02:00
permalink: /investering-vol5/
category:
  - Opdateringer
tags:
  - investering
  - aktier
  - obligationer
  - værdipapirer
excerpt: "Sammenligning af fordeling af aktiver i en portefølje - og hvordan backtester man den med historiske data?"
classes: wide
header:
  teaser: https://images.unsplash.com/photo-1466692476868-aef1dfb1e735?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&h=300&w=400&q=10
---

Man bliver [lige](/investering/) [lidt](/investering-vol2/) [klogere](/investering-vol3/) [hele](/investering-vol4/) tiden.

Jeg vil som udgangspunkt gerne lave en _hands off_-investeringsstrategi. Derfor er sammensætningen af min portefølje en vigtig beslutning.

En rigtig god portefølje skal bestå både af investering og opsparing, men hvordan skal sammenhængen mellem de enkelte elementer være?

Til at hjælpe med at kvalificere valget, kan man lave en _backtest_ af sin strategi rigtig let med [Portfolio Visualizer](https://www.portfoliovisualizer.com/). Der kan man teste forskellige sammensætninger af sine aktiver i porteføljen. Selvom tidligere _performance_ ikke er garanti for fremtidige afkast, så kan det alligevel give en indikation af, hvordan forskellige fordelinger præsterer i forskellige økonomiske situationer.

En _hands off_-investeringsstrategi kræver at investeringen præsterer godt under forskellige økonomiske situationer.

| Økonomisk situation   | Kommentar                                                                     |
|-----------------------|-------------------------------------------------------------------------------|
| Prosperity (velstand) | Aktier klarer sig generelt godt i stigende velstand                           |
| Inflation             | Guldet og ædelmetaller klarer sig godt ved stigende inflation                 |
| Deflation             | Lange obligationer klarer sig godt, når der er deflation                      |
| Recession             | Kontanter klarer sig bedre end de fleste andre investeringsformer i recession |

## Porteføljefordeling handler om aktier og obligationer

Klassisk har investering og sammensætning af porteføljer ofte været en fordeling af aktier og obligationer. [Trinity-studiet](https://www.researchgate.net/publication/265279441_Retirement_Savings_Choosing_a_Withdrawal_Rate_That_Is_Sustainable) brugte en portefølje med 50% aktier og 50% obligationer og kunne lave simulationer, der fortalte at man relativt sikkert over tid kunne hive 4% ud af porteføljen uden at den ville falde. Med andre ord ville porteføljen altså over tid vækste med mindst 4%. Hvis man vægter aktier højere i porteføljen, vil man kalde den mere risikobetonet, og vægter man obligationer højere mindre risikobetonet (men så vil afkastet også være lavere langsigtet). Det er altså værd at teste sin porteføljesammensætning op mod 50/50 fordelingen som benchmark.

{% include figure image_path="/assets/images/posts/portfolio-3-trinity.png" alt="Trinity-studiets portefølje" caption="Trinity-studiets portefølje" %}

## Porteføljefordeling med ejendomme og ædelmetaller

Flere har imidlertid foreslået, at det også er givtigt at inkludere andre typer aktiver i porteføljen for at gøre den mere stabil over tid i forskellige økonomiske situationer.

Forståelsen for aktivklassernes mønstre har været med til at inspirere de to meget omtalte porteføljer.

- **The Permanent Portfolio** sammensat af Harry Browne ([Failsafe Investing](https://www.partner-ads.com/dk/klikbanner.php?partnerid=28187&bannerid=43264&htmlurl=https://www.saxo.com/dk/fail-safe-investing_harry-browne_paperback_9780312263218){: rel="sponsored nofollow noopener" }). Porteføljen indeholder 25% aktier, 25% lange obligationer, 25% guld og 25% kontanter.

{% include figure image_path="/assets/images/posts/portfolio-2-permanent-portfolio.png" alt="Harry Brownes Permanent Portfolio" caption="Harry Brownes Permanent Portfolio" %}

- **The All Weather Portfolio** sammensat af Ray Dalio og beskrevet i [Tony Robbins bog Money - Master the Game](https://www.partner-ads.com/dk/klikbanner.php?partnerid=28187&bannerid=43264&htmlurl=https://www.saxo.com/dk/money-master-the-game_tony-robbins_paperback_9781471143359){: rel="sponsored nofollow noopener" }. Porteføljen indeholder 30% aktier, 55% obligationer (både mellem- og lange), 7,5% guld og 7,5% _commodities_.

## Hvordan vælger man porteføljesammensætning?

Med [Portfolio Visualizer](https://www.portfoliovisualizer.com/) kan vi [teste de forskellige aktiv-sammensætninger op mod hinanden](https://www.frinans.dk/pensionsportefoeljen-del-2-min-pensionsportefoelje/). Den traditionelle 50/50 klarer sig samlet bedst fra 2007 - 2019, men det er også den sammensætning, der har de største fald i perioden. Fordi der kun er data for _commodities_ siden 2007, kan testen ikke gå længere tilbage.

Når man investerer for at opnå økonomisk uafhængighed, kan der altså være en ide i at inkludere andre typer aktiver i sin portefølje, så porteføljen også er stærk i nedgangstider.

[Få en gratis investeringsplan hos Nord](/go/nord/){: .btn .btn--large .btn--info rel='sponsored nofollow noopener' }

## Findes der andre sammensætninger?

Ejendomme fylder en del, når man læser forskellige _blogs_ om finansiel uafhængighed. Jeg her stødt på [The Obvious Investor](https://obviousinvestor.com/my-investments/growth-portfolio/) som har forfinet _The Permanent Portfolio_ til det han kalder _Growth Portfolio_. Porteføljen består af 25% aktier, 25% lange obligationer, 25% guld og 25% ejendomme. Han har udvalgt nogle helt særlige REITs, som gør at hans portefølje præsterer noget bedre end hvis han havde valgt et indeks, fx Vanguards VNQ.

{% include figure image_path="/assets/images/posts/portfolio-1-growth-portfolio.png" alt="The Obvious Investors Growth Portfolio" caption="The Obvious Investors Growth Portfolio" %}

Når Mark fra Obvious Investor laver sin _backtest_, så har han ikke kontanter med i The Permanent Portfolio, da han mener, at det trækker værdien uretfærdigt nedad i Portfolio Vizualizer, men hans portefølje klarer sig samlet noget bedre end markedet i perioden. Jeg har valgt at tage kontanter med i mine tests på denne side.
{: .notice--info}

Når man sammenligner Growth Portfolio (Portfolio 1), Permanent Portfolio (Portfolio 2) og 50/50 (Portfolio 3), så klarer Growth Portfolio sig altså i perioden fra 2005-2019 noget bedre sammenlagt uden at klare sig dårligere i _worst year_ og _max. drawdown_.

{% include figure image_path="/assets/images/posts/portfolio-returns.png" alt="Udvikling i de tre porteføljer" caption="Udvikling i de tre porteføljer" %}

{% include figure image_path="/assets/images/posts/portfolio-returns-graf.png" alt="Udvikling i de tre porteføljer" caption="Udvikling i de tre porteføljer" %}

Og det giver følgende årlige afkast:

{% include figure image_path="/assets/images/posts/annual-returns.png" alt="Udvikling i de tre porteføljer" caption="Udvikling i de tre porteføljer" %}

Men hvordan vil Growth Portfolio egentlig klare sig, hvis man vælger en ETF til at tracke ejendomsmarkedet i stedet for specifikke REITs.

{% include figure image_path="/assets/images/posts/portfolio-4-growth-portfolio-reit-etf.png" alt="The Obvious Investors Growth Portfolio med en REIT-ETF" caption="The Obvious Investors Growth Portfolio med en REIT-ETF" %}

Med ETF’en falder CAGR med cirka 1%-point, det værste år med cirka 5%-point og max. drawdown med 9%-point. Med de historiske data er [Federal Realty Investment Trust](http://tools.morningstar.dk/dk/stockreport/default.aspx?Site=dk&id=0P00000241), [National Retail Properties](http://tools.morningstar.dk/dk/stockreport/default.aspx?Site=dk&id=0P000001DX) og [Universal Health Realty Income Trust](http://tools.morningstar.dk/dk/stockreport/default.aspx?Site=dk&id=0P000005OB) altså med til at beskytte porteføljen noget bedre end [Vanguard Real Estate ETF](https://www.morningstar.com/etfs/arcx/vnq/quote).

{% include figure image_path="/assets/images/posts/portfolio-return-reit-etf.png" alt="Sammenligning mellem REIT-picks i originale Growth Portfolio (1) og en udvalgt ETF (2)" caption="Sammenligning mellem REIT-picks og ETF i Growth Portfolio" %}

## Backteste danske og europæiske forhold?

Desværre så kan Portfolio Vizualizer ikke bruge europæiske data (hvilket de dog arbejder på at finde en løsning på), så man kan ikke _back teste_ den præcise sammensætning af sin portefølje med europæisk og dansk islæt.

Det er ganske vist [let at importere data](https://www.portfoliovisualizer.com/manage-benchmarks#import), men langt de fleste europæiske UCITS fonde har ikke et langt historisk datasæt, og jeg kunne slet ikke finde et historisk datasæt til de danske investeringsforeninger fra fx SparInvest.

Jeg fandt historiske data til udtræk i en CSV-fil på [Investing.com](http://www.investing.com)).
{: .notice--info}

Man må altså famle en lille smule i (historisk _backtest_) blinde, hvis man gerne vil sammensætte sin portefølje med værdipapirer, man kan købe hos de danske børsmæglere.

## Min egen fordeling?

Jeg er inspireret af The Growth Portfolio. Som [tidligere skrevet](/investering-vol4/) opererer jeg overordnet med to forskellige porteføljer.

I den ene vil jeg nok ramme en fordeling, der ligner _Growth Portfolio_ - primært med akkumulerende ETF’er.

I min anden portefølje vil jeg nok i højere grad gå efter de danske index-fonde fra SparInvest, som betaler udbytte. Spørgsmålet er også om den skal suppleres op med specifikke udbytteaktier eller andre fonde, der betaler udbytte, så jeg kan få en løbende udbetalt indtægt.

Det næste jeg bør gøre mig overvejelser om at lave en strategi for er altså vægten mellem mine to primære værdipapir-porteføljer skal være, men også hvordan valutaer skal være vægtet i mine værdipapirer.

[Få en gratis investeringsplan hos Nord](/go/nord/){: .btn .btn--large .btn--info rel='sponsored nofollow noopener' }

{% include disclaimer.md %}
