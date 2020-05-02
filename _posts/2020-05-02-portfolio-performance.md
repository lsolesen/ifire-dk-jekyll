---
title: "Hvordan tracker jeg min portefølje med Atlaz, Portfolio Performance og Cointracking.info?"
permalink: /hvordan-tracker-jeg-min-portefolje/
category:
  - Opdateringer
tags:
  - rigdomsformularen
  - status
excerpt: "Jeg bruger i øjeblikket Atlaz, Portfolio Performance og Cointracking.info til at få overblik over min samlede portefølje."
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



Jeg har længe siddet og bakset med et Google Sheets ark, som jeg manuelt hver måned har opdateret med investeringer, crowdlending og kryptovaluta. Jeg synes det er lidt besværligt og kunne godt tænke mig en lidt mere robust løsning til at få et overblik over økonomien, så jeg gik lidt på udkig efter en bedre løsning.

Inspireret af [Angelo](https://www.p2pinvesting.eu/how-to-track-your-investments-p2p-lending/) afprøvede jeg det gratis, open source [Portfolio Performance](http://www.portfolio-performance.info), som jeg ville se om det kunne være en mulighed til at tracke mine investeringer på en bedre måde. Programmet er lavet af en tysker, og meget af materialet er på tysk. Programmet kan fås både på Windows, Mac og Linux. Der er ingen reklamer og du skal ikke registrere dig for at bruge programmet. 

Når man investerer, så synes jeg det er vigtigt, at man holder styr på, hvad den interne rente på ens investeringer reelt er. Det er ikke altid det er helt præcist på de forskellige platforme, og udregningerne på platformene tager sjældent _cash drag_ med i beregningerne. Det er særligt væsentligt i forhold til P2P-crowdlending, hvor der er en en del meget lysegrønne løfter om afkast.

## Forudsætninger

Hvis du vil læse videre, så kan det være en god ide at installere programmet for at se dets muligheder. Du downloader det fra [Portfolio Performance](http://www.portfolio-performance.info).

I det følgende forsøger jeg at forklare, hvordan jeg bruger programmet til at tracke mine investeringer.

## Investeringer

Jeg har et stykke tid brugt [Atlaz\*](/go/atlaz/) til at få et samlet overblik over alle mine investeringer. Det fungerer virkelig godt med alle de danske investeringer, som den automatisk kan trække ind i systemet. Den gratis service er naturligvis ikke helt gratis, da du betaler med data om dine investeringer, men formålet med Atlaz er at få mange bruger, så de på sigt kan begynde at forhandle med bankerne og børsmæglerne om gebyrerne, fordi de gør det på baggrund af mange mennesker. Desværre kan Atlaz lige nu ikke levere historiske afkast, så man får først et overblik fra den dag, man investerer Atlaz. Atlaz kan imidlertid heller ikke hente data fra de udenlandske børser, fx [Etoro\*](/go/etoro/).

Ellers kan man også få et overblik på de enkelte børser - jeg bruger [Nordnet\*](/go/nordnet/) til mine frie midler og [SaxoInvestor\*](/go/saxoinvestor/) til min aktiesparekonto, men de skilter ikke just med et overblik over renteudgifter, valutaudgifter og kurtage i en let oversigt.

### Importere data ind i Portfolio Performance

Det er relativt let at importere data ind i programmet. Fra [Nordnet\*](/go/nordnet/) kan du ret enkelt downloade en CSV-fil. Hvis du ikke gider at lave for meget om i filen, så er tricket, når du vælger `Type` under importen, at du laver en mapping til de danske ord. Jeg fandt ikke en god måde at importere valutahandlerne, så dem har jeg efterfølgende oprettet manuelt. Jeg kunne ikke finde CSV-filer fra [SaxoInvestor\*](/go/saxoinvestor/), så det har jeg spurgt supporten om. 

Jeg har også spurgt supporten om CSV-export fra [Revolut Trading\*](/go/revolut/), mens jeg lige nu er lidt i tvivl om, hvordan jeg vil håndtere copytrading på [Etoro\*](/go/etoro/), men jeg opdaterer artiklen, så snart jeg har fundet ud af det.

#### Flere valutakonti

Hvis du handler i flere valutaer, skal du oprette flere `Deposit Accounts` med forskellige valutaer. Jeg importerede bare CSV-filen på alle konti, for den kan kun importere ting, der er i samme valuta.

### Det fede dashboard til alm. investeringer

Jeg er ved at få styr på alle mine investeringer i Portfolio Performance, og jeg vender tilbage, når jeg har lagt mig fast på en god måde at gøre det på - og et godt dashboard.

## Crowdlending

Mit hjemmestrikkede Google Sheets ark startede med, at jeg ville tracke den interne rente på min Crowdlending. Jeg synes det var blevet lidt tidskrævende, møjsommeligt og ikke robust nok.

Jeg har fundet ud af, at det faktisk er ret enkelt med Portfolio Performance. Tidligere havde jeg fordelen af, at mine ændringer i mit Google Sheet automatisk blev vist på mine oversigter, men jeg tror fordelene ved Portfolio Manager er så store, at jeg må finde en anden måde at få opdateret oversigterne på.

## Tilføj dine crowdlending konti

Under `Deposit Accounts` klikker du på det lille plus oppe i højre hjørne og vælger `Add account…`. Det letteste er med det samme at tilføje alle dine crowdlending platforme.

{% include figure image_path="/assets/images/posts/pp-add-account.webp" caption="Under Deposit Accounts skal du klikke på Add Account for at tilføje dine crowdlending platforme - [via](https://www.p2pinvesting.eu/how-to-track-your-investments-p2p-lending/)" %}

{% include figure image_path="/assets/images/posts/pp-p2p-accounts.webp" caption="Oversigt over alle dine crowdlending platforme - [via](https://www.p2pinvesting.eu/how-to-track-your-investments-p2p-lending/)" %}

{% include figure image_path="/assets/images/posts/pp-crowdlending-accounts.webp" caption="Se dine crowdlending konti - som bliver blandet med dine andre investeringskonti, hvis du bruger Portfolio Performance til andre investeringer også - [via](https://www.p2pinvesting.eu/how-to-track-your-investments-p2p-lending/)" %}

### Tilføj dine indskud og udbetalinger

Du højreklikker ganske enkelt på kontoen og vælger `Deposit` eller `Removal` alt efter om du indsætter penge eller trækker penge ud.

{% include figure image_path="/assets/images/posts/pp-add-p2p-deposit.webp" caption="Højreklik og vælg Add deposit for at lave et indskud på din konto - [via](https://www.p2pinvesting.eu/how-to-track-your-investments-p2p-lending/)" %}

{% include figure image_path="/assets/images/posts/pp-add-deposit.webp" caption="Vindue hvor du indtaster dit indskud - [via](https://www.p2pinvesting.eu/how-to-track-your-investments-p2p-lending/)" %}

### Tilføj dine månedlige renter

Hver måned når jeg laver en opdatering, så kigger jeg på værdien af min konto sidste måned med den nuværende værdi. Forskellen er en sammenblanding af rente, bonusser, gebyrer mv. For at gøre det lettest muligt, så bogfører jeg det samlede beløb som renter eller renteudgifter i programmet. På den måde stemmer min konto. 

Jeg husker naturligvis at det ikke er en realiseret indtægt, men den forventede renteindtægt, når jeg trækker pengene ud.
{: .notice .notice--info }

For at tilføje renterne højreklikker du bare på kontoen og vælger `Interest` i menuen, der kommer frem.

### Tilføj bonus

Jeg har valgt at tilføje de signup bonuses, jeg har fået på de enkelte platforme som renter også, da det er det mest enkle. Der er desværre ikke så vidt jeg kan se en rigtig god måde at adskille det på.

### Importere data

*[CSV]: Comma Separated Values

Jeg havde lavet månedlige opdateringer i mit Google Sheet med alle de nødvendige oplysninger. Jeg eksporterede dem som en CSV-fil. Derefter kan jeg højreklikke på kontoen og vælge `Import CSV`, hvilket gjorde, at jeg ret hurtigt havde et samlet overblik over mine data i Portfolio Performance.

### Mit crowdlending dashboard med udregning af intern rente

Nu er der jo ikke meget ved at have alle sine data i et robust og brugervenligt system, hvis ikke man kan få overblik. Det er heldigvis ret enkelt at lave et godt overblik i sit eget _dashboard_.

Du klikker på  `Performance`. Der kan du oprette et nyt Dashboard ved at klikke på **+** i hjørnet. Du kan fx navngive det P2P. Jeg startede med at fjerne alt på det nye dashboard ved at højreklikke og vælge `Delete`. Så kan du begynde at indsætte dine egne widgets.

Jeg har valgt `Common → Heading` og `Performance → Internal Rate of Return (IRR)`.

{% include figure image_path="/assets/images/posts/pp-widget-add-heading.webp" caption="Højreklik for at tilføje en Heading (overskrift) - [via](https://www.p2pinvesting.eu/how-to-track-your-investments-p2p-lending/)" %}

{% include figure image_path="/assets/images/posts/pp-widget-internal-rate-of-return.webp" caption="Højreklik for at tilføje widget med den interne rente - [via](https://www.p2pinvesting.eu/how-to-track-your-investments-p2p-lending/)" %}

Når du har indsat din IRR-widget, skal du højreklikke på den for at `Select data series`, så du kun får vist den platform, du gerne vil have vist. Jeg foretrækker at få vist den interne rente i hele perioden, jeg har investeret. Jeg startede med at investere i crowdlending omkring 01-01-2017, så jeg har bare oprettet en ny `Reporting period`, der starter derfra. Du kan også vælge `Use reporting period of dashboard`.

{% include figure image_path="/assets/images/posts/pp-widget-data-series.webp" caption="Højreklik for at vælge den rigtige dataserie for din widget - [via](https://www.p2pinvesting.eu/how-to-track-your-investments-p2p-lending/)" %}

Hvis du tilføjer alle dine crowdlending konti, så har du et hurtigt overblik.

{% include figure image_path="/assets/images/posts/pp-dashboard-overview.jpg" caption="Overblik over crowdlending - [via](https://passives-einkommen-mit-p2p.de/portfolio-performance-wie-du-deine-p2p-plattformen-einfach-verwalten-kannst/)" %}

### Opret din crowdlending som asset class

Hvis du vil tracke mere end din crowdlending portefølje, men gerne vil have en oversigt særskilt, så kan det være en god ide at gruppere dine crowdlending konti.

Du kan også lave en oversigt over hele din crowdlending portefølje. Det gør du ved at gruppere dine crowdlending platforme under `Asset class`.

{% include figure image_path="/assets/images/posts/pp-group-by-asset-class.jpg" caption="Lav en _asset class_ med crowdlending for let at kunne lave dine dashboards." %}

### Crowdlending baseret på shares eller andele

Jeg investerer i [Brickshare\*](/go/brickshare/) og [Funderbeam\*](/go/funderbeam/), som baserer sig på _shares_ eller andele, som kan stige og falde i pris. Det giver ikke helt mening og opgive dette som renter, så i stedet har jeg lavet en opsætning tilsvarende almindelige investeringer, hvor jeg har en `Deposits account` og en `Security Account`.

For eksempel så har jeg to investeringer i Brickshare. Dem har jeg oprettet som en security. Jeg har kaldt dem Brickshare: Projektnavn. Når jeg laver en opdatering, så opdaterer jeg værdien af andelene ved at højreklikke nederst i billedet under fanen `Historical Quotes`. På den måde så får jeg det mest retvisende billede med den interne rente for projekterne.

{% include figure image_path="/assets/images/posts/pp-brickshare-historical-values.jpg" caption="Opret dine Brickshare projekter og tilføj selv de historiske værdier for andelene" %}

Under min _widget_ på mit dashboard skal jeg huske at vælge `Brickshare + Brickshare` for at have både Deposit account og Security account med i beregningen. Jeg glæder mig fortsat til at få udbytte fra Brickshare.

{% include figure image_path="/assets/images/posts/pp-brickshare-widget.jpg" caption="På din Dashboard widget skal du vælge Brickshare + Brickshare for at få den korrekte interne rente." %}

Det samme kunne jeg formentlig gøre med [Kuflink\*](/go/kuflink/) og [PropertyPartner\*](/go/propertypartner/), men her er mine investeringer lidt mindre og for nemheds skyld, bruger jeg bare _rente-metoden_.

### Fine værktøjer til analyse af din crowdlending

Når du har styr på din portefølje i Portfolio Manager, så er der mange fine værktøjer, du kan benytte dig af.

{% include figure image_path="/assets/images/posts/pp-reports-holding-p2p-allocation.webp" caption="Få vist en rapport over din samlede fordeling i crowdlending - [via](https://www.p2pinvesting.eu/how-to-track-your-investments-p2p-lending/)" %}

{% include figure image_path="/assets/images/posts/pp-reports-p2p-earnings-per-year.webp" caption="Se indtjening pr. år - [via](https://www.p2pinvesting.eu/how-to-track-your-investments-p2p-lending/)" %}

{% include figure image_path="/assets/images/posts/pp-reports-p2p-earnings-month.webp" caption="Se indtjening pr. måned - [via](https://www.p2pinvesting.eu/how-to-track-your-investments-p2p-lending/)" %}

{% include figure image_path="/assets/images/posts/pp-reports-p2p-earnings-month-graph.webp" caption="Se indtjening pr. måned sammenlignet med tidligere år som graf - [via](https://www.p2pinvesting.eu/how-to-track-your-investments-p2p-lending/)" %}

{% include figure image_path="/assets/images/posts/pp-reports-calculation.webp" caption="Se oversigt over din crowdlending portefølje." %}

## Kryptovaluta

Jeg har brugt den gratis version af [cointracking.info\*](/go/cointracking/) til manuelt at holde styr på min kryptovaluta, de forskellige børser og wallets. Det fungerer ret godt, og jeg kan let hver måned aflæse realiserede og urealiserede gevinster og tab og den samlede nuværende værdi af min portefølje.

Der er ret smart funktioner i Portfolio Performance, hvor man bl.a. automatisk kan hente de aktuelle priser fra Kraken eller andre steder. Jeg opdaterer artiklen, når jeg finder ud af, hvordan jeg vil tracke kryptovaluta.

Det er let at oprette den enkelte kryptovaluta som `Security`, men der er lige en lille finurlighed, hvis den automatisk skal hente kurserne fra [Kraken\*](/go/kraken/), som jeg foretrækker som min egen børs. 

{% include figure image_path="/assets/images/posts/pp-crypto-symbol.webp" caption="Jeg har valgt Kraken til at hente `Historical Quotes` for kryptovaluta. For at den kan gøre det automatisk, skal du sætte Symbol til `XXBTZEUR` for Bitcoins." %}

## Andre referencer 

- [passives-einkommen-mit-p2p.de](https://passives-einkommen-mit-p2p.de/portfolio-performance-wie-du-deine-p2p-plattformen-einfach-verwalten-kannst/)

{% include disclaimer.md %}