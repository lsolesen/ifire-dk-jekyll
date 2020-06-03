---
title: "Hvad tjener jeg egentlig - forklaring af XIRR"
category:
  - Investering
tags:
  - investering
  - xirr
excerpt: "XIRR er en måde at finde ud af, hvad du tjener på en investering?"
last_modified_at: 2017-01-10T14:22:02+02:00
mathjax: true
classes: wide
---

Jeg investerer for at få afkast. På de fleste platforme lover de dig et afkast, fx har [Envestio\*](/go/envestio/) relativt høje renter sine lån, og [Mintos\*](/go/mintos/) har på _dashboard_ en angivelse af _net annual return percentage_. Men platformene kan bruge forskellige metoder til at lave udregningerne. Så hvordan beregner man egentlig selv sit afkast af en investering,, som man kan bruge til at sammenligne platformene?

## Return on investment (ROI)



## Intern rente (XIRR)

Man kan bruge _intern rente_, som står for _Internal Rate of Return_. Beregningen tager ikke højde for inflation eller andre alternative omkostninger. Den tager ganske enkelt højde for, hvornår man har investeret penge - og hvad værdien af investeringen er på et givent tidspunkt. Du kan bruge beregningen til alle typer investeringer, fx værdipapirer, crowdlending og cryptovaluta.

Beregningen af intern rente kræver kun, at du har en liste med transaktioner (datoer og beløb) på din konto. 

## Beregn den interne rente (XIRR)

Sådan beregnes XIRR AKA intern rente
Takket være de fantastiske mennesker som opfandt regnearket, er det ikke nødvendigt at hive lommeregneren frem og forsøge at huske det, vi lærte i matematiktimerne. Man skal bare bruge en simpel formel, der tager sig af alle mellemregningerne.

 

I Google Spreadsheets og den engelsksprogede version af Excel indtaster man:
XIRR([bevægelseskolonne],[datakolonne])

I dansk Excel er formlen således:
INTERN.RENTE([bevægelseskolonne];[datakolonne])

 



I eksemplet til højre blev der 1. januar overført 4.000 kr. til en investeringskonto.

Senere blev der tilført 700 kr. og efterfølgende udtrukket 350 kr.

Ved årsopgørelsen har kontoen en samlet værdi på 5.240 kr. Bemærk, at beløbet er skrevet med omvendt fortegn.

Ved hjælp af XIRR-formlen kan jeg hurtigt konstatere, at årets afkast har været 19,72 %.

Intern rente og crowdlending
Ved nogle former for crowdlending risikerer man at tabe penge, hvis låntageren aldrig betaler det, han skylder. Det kan godt være, at et lån i restance medregnes som aktiv i en periode, men hvis det kun udbetales delvist (eller slet ikke), bør dette modregnes det forventede afkast.

Og med tilstrækkelig indsigt i låntagernes ageren, kan man relativt let foretage nogle vurderinger af forventede afskrivninger og inddrage dem i sin beregning af intern rente. Vi kan kort sagt gennemføre en longitudinal analyse og bruge resultatet til at prognosticere fremtidige afvigelser fra idealet. Det er fancy-talk for at bruge tidligere perioders erfaring til at tage højde for de låntagere, som ikke betaler deres gæld.

Fx hvis vi erfaringsmæssigt ved, at 10 % af de låntagere som er 1 – 10 dage bagud aldrig betaler, så kan jeg inkludere det i beregningen. Det gøres ved at tilføje nogle kolonner for forventet tab og lægge det til kontoens samlede værdi. I eksemplet nedenfor falder kontoens værdi med 551,20 kr. og XIRR falder til 7,5 %.



Det var let, ikke?

Men jeg lovede jo også en gave. Og den gave er et regneark! Ja, jeg ved ikke med dig, men jeg elsker regneark. Derfor har jeg lavet en simpel skabelon, som du kan bruge til at analysere dine egne investeringer. Filen kan hentes her: Pengepugerens XIRR skabelon.








ROI

XIRR or extended internal rate of return is a measure of return used when multiple investments (at different points in time) are made in a financial instrument. A look at what XIRR represents and how it is different from CAGR.

## What is CAGR?

First, we need to answer a much simpler question.

If I invest Rs. 12,000, and after 5 years the value is Rs. 22,991. What is the average rate at which my investment has compounded year after year?

To find this, we write

$$ 22991 = 12000 x (1+ CAGR)^5 $$

or

$$ 22991 = 12000 x (1+ CAGR) x (1+ CAGR) x (1+ CAGR) x (1+ CAGR) x (1+ CAGR) $$

Here CAGR represents the year on year compounded growth and is known as compounded annualized growth rate

In the present case, CAGR = 13.9%


CAGR is obviously necessary only when the annual returns vary. If the returns are the same (like in an FD), the maturity value will be known the moment you create the FD.

## CAGR vs XIRR

Suppose I invest Rs. 12,000 once a year for 12 years and wish to know what is the average rate at which my investments have compounded year after year, the quantity that gives me information is the XIRR.

We will now see what the XIRR represents and how it is calculated.

This is the annual SIP investment schedule. The investment is made once at the start of each year.  A monthly SIP will follow the same logic but is a bit more difficult to perceive.

SIP schedule for XIRR calculation

The total value after 12 years is 5,17,524

The same schedule can be viewed in a different way.

alternative way to view the SIP schedule for XIRR computation

The first instalment has 12 years to grow. The second instalment has 11 years to grow, and so on.

We now calculate the final value of each instalment.

The first instalment after 12 years grows to 1,42,693 at a CAGR of 22.9%

The second instalment after 11 years grows to 73,308 at a CAGR of 17.9% and so on.

Each instalment has its own CAGR as the investment tenure varies.  The total value of all the investments must be equal to 5,17,524

Instead of assigning each instalment a different CAGR, what if we assigned a common CAGR?

That is each instalment is perceived to grow at the same CAGR. The aim is to adjust this common CAGR until the  total value of all the investments becomes equal to 5,17,524

## How is XIRR calculated?

How is XIRR calculated an example

The last column is the adjusted CAGR. Now all instalments have the same CAGR and  total value of all the investments is indeed equal to 5,17,524

This adjusted CAGR is known as XIRR

So our aim should be to adjust the CAGR until the total value of all the investments equals the actual total final value.

Excel does this adjustment for us automatically using an approximation technique called the Newton-Raphson method (remember that from school?). The technique is not without flaws. Read more here: IRR/XIRR : Limitations of Calculating Complex Cash Flow Returns

In the above illustration, the investments are spaced exactly 365 days apart. In an actual annual or monthly SIP, due to non-business days, the spacing will be greater/less than 365 or 30 days. The spacing does not matter for XIRR. If the spacing is exact, things become simpler and this is often known as an IRR calculation.


{% include disclaimer.md %}
