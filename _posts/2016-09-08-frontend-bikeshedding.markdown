---
layout:     post
title:      Frontend Bikeshedding
date:       2016-09-07 11:31:19
summary:    Summerar här några tankar om webbprojekt i agil form
categories: bikeshed
---
Utan att riktigt veta varför börjar jag knappa in lite bokstäver här i ett markdown-dokument.
Okej, så här, jag ville formulera ett argument kring detta med teknik i presentationslagret på webben och i appar idag. Så här ligger det till, i min projektinriktade skalle (har arbetat både agilt och traditionellt i kaskad) tänker jag att tekniksnack gällande val av frameworks och mjukvara och högt flygande motiveringar till dessa kan sammanfattas som bikeshedding. Se [1](https://sv.wiktionary.org/wiki/cykelst%C3%A4llsfr%C3%A5ga), [2](https://css-tricks.com/what-is-bikeshedding/), och [3](http://bikeshed.com/). 

Bikeshedding är en omskrivning för Parkinsons trivialitetslag, som gör gällande att långa samtal kring helt ovidkommande saker ofta solkar ned den väsentliga diskussionen och de viktiga besluten i en organisation.

Rent konkret tror jag att rådande standard och best practices bör efterfrågas i utveckling, idag kan dessa sammanfattas i mobile first, accesibility, graceful degradation och agile development. 

## Alltså: 

 * Designa för alla typer av skärmar, utgå från den minsta och anpassa budskapet till denna och skala därefter upp både kommunikation som funktion till de sekundära enheterna. 
 * Förutsätt inte att alla har samma förförståelse som du kring teknik eller samma läsvana, och tänk på att alla bör kunna ta del av ditt budskap eller innehåll, även de utanför din förmodade målgrupp. 
 * Laborera kring de senaste trenderna och nyheterna, men se för fan till att det spelar på äldre plattformar och browsers med lite värdighet!
 * Sist men inte minst: utveckla iterativt – tänk, pröva, testa, läs av och tänk sedan om.

### Sammanfattningsvis

Jag anser att ett framgångsrikt gränssnitt föds ur ett konceptarbete som baseras på insikter ur användartester, strategiska målsättningar och en stor dos acceptans för misslyckanden. En framgångsrik App som älskas av sina användare och träffar de strategiska (och ekonomiska) målen som satts upp har med andra ord en väldigt lite att göra med <em>SPA-Frontend-Javascript-Frameworks. </em>

Dessa tekniker och ramverk bidrar i många fall endast till att skapa visuellt kreativ höjd på produkten (drar till minnes Flash och tidigt 2000-tal) som av många, däribland användbarhetsexperten Jacob Nielsen, anses vara till användares förtret snarare än fördel. 

Nielsen nämner bl a i [NNGs Rapport](https://www.nngroup.com/reports/mobile-website-and-application-usability/) om [Mobil UX](https://www.nngroup.com/articles/mobile-ux/) att portabla enheter bäddar för kortare och avbrutna sessions (72s i snitt), att användare förväntar sig träffa på och hitta verklig och användbar information på en sajt eller app istället för att undersöka nya och animerade menyfunktioner som endast bidrar till en högre kognitiv belastning.


## Okej hur gör man en SPA?

Visst, man kan inte komma så här långt och dissa JavaScript och höja Nielsen till skyarna. Har därför kollat upp den stora [GitHub-listan för Javascript-ramverk](https://github.com/showcases/front-end-javascript-frameworks) och listar de väsentligaste här, med en personlig anmärkning.

![Github Javascript Frameworks]({{ site.url }}/images/github-js.png){: .center-image }

Har tittat på listan och även projekten i sig för att förstå populariteten kring dessa. Om vi bortser från Google-drivna Angular och Facebook-drivna React verkar följande tre projekt som de mest intressanta för att ingå i ett modernt frontendprojekt (oberoende av varandra).

* [Ember.js](http://emberjs.com/) – ett ramverk som "helt enkelt fungererar", ökar produktiviteten och har ett följe av användare och utvecklare bakom sig.
* [D3.js](https://d3js.org/) - Ett bibliotek som faller utanför SPA-norm, men som erbjuder underverk för gränssnittet!
* [Backbone](http://backbonejs.org/) - När du vill "keep it simple, stupid" ska du hålla dig till detta MVC-ramverk.



Källor till denna sammandragning [Länk 0](https://github.com/showcases/front-end-javascript-frameworks?s=stars), [Länk 1](http://noeticforce.com/best-Javascript-frameworks-for-single-page-modern-web-applications), [Länk 2](https://www.sitepoint.com/top-javascript-frameworks-libraries-tools-use/), [Länk 3](https://www.lullabot.com/articles/choosing-the-right-javascript-framework-for-the-job)