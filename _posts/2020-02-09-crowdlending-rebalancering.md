---
title: "Rebalancering af crowdlending ud fra risk-reward"
last_modified_at: 2020-02-10T09:20:02+02:00
permalink: /crowdlending-rebalancering/
category:
  - Investering
tags:
  - crowdlending
excerpt: "Crowdlending er en højrisikoinvestering, men platformene er meget forskellige. Med Risk-Reward kan vi give et bud på, hvilke platforme der er risikoen værd?"
classes: wide
---

Når man investerer i crowdlending kan det være let at miste fokus og ende med et en rodet portefølje, fordi man bliver lokket af _cash back_, _sign up_-bonusser, lovninger om høje renter. De fleste platforme er jeg endt med at skrive mig op til ved at have læst en blogger, der nævner platformen og samtidig lover en _sign up_-bonus. Bloggeren har formentlig skrevet om platformen, fordi vedkommende samtidig har en _referral_-aftale med platformen. (Min egen side er ingen undtagelse. Hvis du bruger et link på min side, er det typisk et referral-link.)

Udfordringerne med Kuetzal og Envestio (som jeg selv havde investeret i) og bekymringerne ift. nogle af de andre platforme har mindet mig om, at jeg skal have rebalanceret min crowdlending-portefølje. Først og fremmest skal jeg have bragt min investering lidt ned, men jeg skal også have rebalanceret mellem platformene.

Jeg har imidlertid ikke helt kunnet finde ud af, hvordan jeg ville gribe det an indtil jeg blev inspireret af [Risk Adjusting My P2P Lending Portfolio](https://www.onemillionjourney.com/risk-adjusting-my-p2p-lending-portfolio/) og [Nerd Factor’s Risk vs Return Analysis P2P Portfolio](https://factornerd.com/a-risk-vs-return-analysis-of-my-p2p-lending-portfolio/). De har lavet deres egne risiko-afkast-vurderinger af platformene, og det er dem jeg vil tage udgangspunkt i, når jeg laver min egen rebalancering af min portefølje.

Jeg tager kraftigt udgangspunkt i fremgangsmåden her [Risk Adjusting My P2P Lending Portfolio](https://www.onemillionjourney.com/risk-adjusting-my-p2p-lending-portfolio/). Analysen er baseret helt på mine egne vurderinger af de enkelte platforme, og der kan sagtens være ting, som jeg ikke har vurderet korrekt i dine øjne. Samtidig kan mine kriterier og pointgivningen i de enkelte kriterier også være genstand for (megen) diskussion.

Det her er imidlertid mit bud på mit eget ræsonnement for at vurdere risiko-afkast.

## Vurdering af afkast - Platform Return

_Platform return_ vurderer jeg ganske enkelt som den interne rente (XIRR). Det er relativt enkelt at regne ud med Google Sheets eller Excel. Jeg bruger ikke platformenes egne vurderinger eller reklamerne for platformene, da det ofte ikke matcher det reelle tal, man får i intern rente (som tager tidspunktet for investeringen og det reelle afkast i betragtning). 

Jeg husker at afkastet er _urealiseret_ indtil jeg faktisk har hævet pengene fra platformen, så der er en vis usikkerhed på den enkelte platform. Derfor er der også en vurdering af de enkelte platformes sikkerhed.

## Vurdering af sikkerhed - Risk Score

_Risk Score_ udregnes på baggrund af en række forskellige kriterier, der fortæller noget om sikkerheden på platformen. Jeg har valgt at koncentrere mig om følgende kriterier for at vurdere sikkerheden på platformene.

### Borrower Risk og Loan Security

- **Buy Backs.** Tilbyder platformen at købe lånene tilbage. På fx [Mintos\*](/go/mintos/) [Lenndy\*](/go/lenndy/) og flere andre tilbydes at lånene kan købes tilbage. Det er bl.a. også et af kritikpunkterne hos [FastInvest\*](/go/fastinvest/), som tilbyder _instant buy back_, for hvordan kan de dække det, hvis alle samtidig vil sælge deres lån tilbage. Det er vigtigt at vurdere om _buy back_ reelt kan realiseres fra platformen.
- **Provision Fund.** Fx opbygger [Crowdestor\*](/go/crowdestor/) en fond, der skal kunne dække defaults. Den er dog langt fra færdig endnu.
- **Collateral.** Fx har [Grupeer\*](/go/grupper/) en del lån, der har ejendomme som sikkerhed.

### Loan Originator Risk

- **LO Quantity.** Hvor mange låneudbydere er der på platformen. Risikoen hos platformen må vurderes højere, hvis den kun tilbyder få ift. flere. Fx er [Trine\*](/go/trine/) en låneudbyder, mens [Grupeer\*](/go/grupeer/) har 42 låneudbydere.
- **Credit Risk Scoring.** Laver platformen en risikovurdering af de enkelte lån, så man kan tage udgangspunkt i det i sine investeringer.

### Platform Risk

- **Financial Health.** Hvordan ser platformenes regnskaber ud.
- **Regulation.** Hvor reguleret er det marked, platformen opererer på. Fx er det estiske og afrikanske marked mindre reguleret end det danske marked.
- **Reputation.** Hvilket ry har platformen. Dette er naturligvis en subjektiv holdning.
- **Track Record.** Hvilken historie har firmaet. Fx har [Mintos\*](/go/mintos/) en noget længere historie end [EvoEstate\*](/go/evoestate/), hvilket taler til fordel for platformen.
- **Transparency.** Gennemsigtigheden i platformen er netop noget af det [FastInvest\*](/go/fastinvest/) i øjeblikket får en del dårlig omtale i crowdlendingmiljøet, mens fx [RoboCash\*](/go/robocash/) udgiver årlige rapporter og kommunikerer tydeligt om udfordringer med låneudbydere.

### Cash Drag

- **Auto-invest.** En platform med _auto invest_ gør det lettere at have sine midler investeret.
- **Loan Book.** Hvor mange lån udbydes på platformen. Fx har ejendomsplatformene noget færre lån end de platforme, som hovedsageligt har forbrugslån i porteføljen.

### Technology Risk

Sikkerheden på platformen betyder også noget ift. om hackere kan komme ind og hæve ens penge.

- **2Factor Authentication.**
- **Only withdraw to verified bank accounts.**

### Liquidity Risk

- **Secondary Market.** [Grupeer\*](/go/grupeer/) mangler fortsat et sekundært marked, hvor man kan sælge sine lån igen, mens [Mintos\*](/go/mintos/) har et utrolig likvidt sekundært marked.
- **Buybacks.** [FastInvest\*](/go/fastinvest/) tilbyder _instant buy back_, så kan hurtigt kan sælge sine lån.
- **Short loan term.** [PeerBerry\*](/go/peerberry/) har fx relativt korte lån, som man hurtigt kan komme ud af.

### Market Risk

- **Geo.** Hvor geografisk spredte kan man lave investeringer. Fx har nogle af ejendomsplatformene stort set kun en by, fx [Brickshare\*](/go/brickshare/), mens [PeerBerry\*](/go/peerberry/) opererer i mange lande.
- **Investment Type.** Nogle lånetyper er mere risikable end andre lånetyper, fx har [Crowdestor\*](/go/crowdestor/) nogle tilsyneladende meget risikable lån. I forhold til mine investeringer, så forsøger jeg at fravælge de mest risikable lånetyper, og det er baggrunden for min vurdering af platformen.

### Hvordan vægter parameterne? - Risk Relevance

Jeg tænker stadig over, hvordan man kan sætte endnu mere stramme kriterier op for pointgivningen for de enkelte parametre. Denne del skal altså finpudses.

De enkelte parametre har forskellig vægtning ift. vurderingen af risikoen for platformen. Nogle parametre er mere relevante end andre. Foreløbig benytter jeg den samme vægtning som i [Risk Adjusting My P2P Lending Portfolio](https://www.onemillionjourney.com/risk-adjusting-my-p2p-lending-portfolio/). Det betyder i praksis at platform-sikkerheden har større _impact_ på risikoen end _cash drag_.

<iframe width="600" height="385" seamless frameborder="0" scrolling="no" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vQKZZbdj1cM5A4yCXjtjhxowXHoMhioXI-OR-mEPmmGgqQhcSr250VUM8SGVvRkWZziWUYleizmqAC2/pubchart?oid=1616291260&amp;format=image"></iframe>

I praksis bliver risiko-scoren (_Risk Score_) udregnet på følgende måde i det bagvedliggende regneark.

{% include math formula="RiskScore=\frac{BR*20}{100}+\frac{LO*20}{100}+\frac{PR*30}{100}+\frac{CD*5}{100}+\frac{TR*5}{100}+\frac{LR*5}{100}+\frac{MR*15}{100}" %}

## Risiko-afkast vurdering - Risk-Reward

Platformen bliver altså vurderet ift. risiko-afkast ved at gange _Risk Score_ med _Platform Return_. Desto højere tallet er, desto bedre er platformen ift. risiko-afkast.

{% include math formula="RiskReturnNumber=\frac{RiskScore*PlatformReturn}{10}" %}

Jeg har i praksis vurderet alle de platforme, jeg er repræsenteret på lige nu. Jeg har forsøgt at gruppere dem lidt i rækkefølgen af platforme. Alle tallene skal tages med forbehold, og der kan sagtens være tal i forbindelse med de enkelte vurderinger, der ikke er præcise.

Hvis du har spørgsmål eller forslag til forbedring af vurderingerne for de enkelte platforme, så er de meget velkomne.

### Hvad har jeg lært?

Ifølge min selvanalyse, så er de bedste platforme for mig ift. risk-reward lige nu:

- [Mintos\*](/go/mintos/)
- [Grupeer\*](/go/grupper/)
- [Lenndy\*](/go/lenndy/)
- [PeerBerry\*](/go/peerberry/)

Af de platforme der retter sig mod ejendomsmarkedet, så må følgende fremhæves:

- [EstateGuru\*](/go/estateguru/)
- [EvoEstate\*](/go/evoestate/)

Det er værd at lægge mærke til, at [EvoEstate\*](/go/evoestate/), [FastInvest\*](/go/fastinvest/) og [Crowdestor\*](/go/crowdestor) lige nu har nogenlunde samme risk-reward-score. Det skyldes at FastInvest har relativt høj intern rente, mens Crowdestor ikke leverer så høj intern rente for mig (og jeg typisk undgår de lån med de højeste renter). Efter alt hvad man hører i crowdlendingmiljøet er min mavefornemmelse med Crowdestor bedst, men man må også sige, at de lokker med ret høje renter. Evoestate synes jeg er ret smart, fordi den samler lån fra forskellige platforme. 

Det smarte i det bliver tydeligt, når man ser i den anden ende af risk-reward-skalaen.

I den anden ende af skalaen har vi følgende: 

- [BulkEstate\*](/go/bulkestate/)
- [Housers\*](/go/housers/)
- [PropertyPartner\*](/go/propertypartner/)
- [Kuflink\*](/go/kuflink/)
- [ReInvest24\*](/go/reinvest24/)

Her er det tydeligt, at vi har med crowdlending platforme, der specialiserer sig i ejendomsmarkedet. Det er også dem, der scorer lavest. Jeg har brug for at undersøge [EvoEstate\*](/go/evoestate/) før jeg øger eksponeringen til den platform, men jeg vil helt sikkert sænke eksponeringen mod de ovenstående platforme ud fra min analyse.

Jeg har også [Trine\*](/go/trine/), [Lendahand\*](/go/lendahand/) og [Agrikaab\*](/go/agrikaab/), som jeg investerer i pga. bæredygtige og velgørende formål, så dem fastholder jeg, selvom deres risk-reward ratio ikke er fantastisk.

I følgende radar-graf kan du se, hvordan de enkelte platforme er blevet vurderet. Den **røde linje med risk-return vurderingen** er den vigtigste, men den **blå med platformsikkerheden** er også ret væsentlig. Fx scorer [Bondora\*](/go/bondora/) ikke så højt på risk-reward, men sikkerheden i platformen er ret høj.

<iframe width="890" height="492" seamless frameborder="0" scrolling="no" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vQKZZbdj1cM5A4yCXjtjhxowXHoMhioXI-OR-mEPmmGgqQhcSr250VUM8SGVvRkWZziWUYleizmqAC2/pubchart?oid=204663918&amp;format=image"></iframe>

## Min ideelle crowdlending allokering

På baggrund af ovenstående analyse har jeg forsøgt at sætte lidt procenter på min ideelle allokering i min crowdlending portefølje. Delvist baseret på fakta og delvist baseret på mavefornemmelse, men også et ønske om at gøre den samlede portefølje lidt mere enkel.

<iframe width="600" height="371" seamless frameborder="0" scrolling="no" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vQKZZbdj1cM5A4yCXjtjhxowXHoMhioXI-OR-mEPmmGgqQhcSr250VUM8SGVvRkWZziWUYleizmqAC2/pubchart?oid=232372279&amp;format=image"></iframe>

Hvordan ser det så ud ift. min nuværende allokering i de forskellige crowdlending platforme, kan du se i nedenstående oversigt.

<iframe width="600" height="505" seamless frameborder="0" scrolling="no" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vQKZZbdj1cM5A4yCXjtjhxowXHoMhioXI-OR-mEPmmGgqQhcSr250VUM8SGVvRkWZziWUYleizmqAC2/pubchart?oid=122354674&amp;format=image"></iframe>

{% include disclaimer.md %}
