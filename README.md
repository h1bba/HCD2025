# HCD
Testpersoon: <b>Darice</b>

[Youtube showcase](https://www.youtube.com/watch?v=9l1MLsNj_5o)

## Week 1

### Onderzoek
#### Introductie

Het vak Human Centered Design is gericht op het ontwerpen voor een testpersoon, deze testpersoon heeft een beperking, of dat nou slecht werkende ogen zijn of compleet niks kunnen horen ligt aan de testpersoon.
In mijn geval heb ik de kans gekregen om met Darice aan de slag te gaan.

Darice is op 27 jarige leeftijd haar gehoor kwijtgeraakt, waardoor ze wel voorheen wist hoe ze woorden moet uitspreken door geheugen van vroeger. Ook heeft Darice slecht zicht met haar linker oog, waardoor er voor haar soms nog wat dingen over het hoofd wordt gezien.
Darice die wilt graag mee kunnen genieten van een film, inclusief het geluid en muziek. Darice vind dat er weinig rekening wordt gehouden met slechthorende mensen en de subtitles zoals "*music starts playing*" niet genoeg is het gevoel te erkennen die het muziek je geeft bijvoorbeeld.

Ook zijn er nog andere pijnpunten, zoals bij closed captions waar er moeilijk bij valt te houden wie er praat als diegene niet in beeld is. Sommige emoties zoals verdriet is soms ook moeilijk te begrijpen doordat ze niet meekrijgt of iemand een trillende stem heeft of als er iemand bijvoorbeeld sarcastisch is. Darice geeft ook aan dat de subtitles vaak te snel verdwijnen waardoor je eigenlijk of alleen het beeld ziet of alleen de tekst. Mensen zonder gehoor die kunnen maar op 1 punt tegelijk focussen, waardoor als er meerdere dingen tegelijk gebeurt op het beeld, je de ondertiteling vaak mist.

#### Opdracht

Ik ga voor Darice een clip van een film moeten uitwerken, waar zij ook kan begrijpen wat voor gevoel en ritme audio kan geven. En waar duidelijk onderscheid in wie praat is te zien. Darice die gaf aan dat ze de Bims podcast of Odd Thomas wel zou uitgewerkt willen zien worden en daarom heb ik gekozen voor Odd Thomas.

De reden dat ik deze clip heb gekozen is omdat er meerdere personen praten, en er veel emotie is in de scene die ik wil laten zien. Ik moet zorgen dat deze film kijken voor Darice een betere UX is voor haar en makkelijker te volgen is.

Er zijn 4 testmomenten waarop we Darice mogen interviewen en ideeën delen.

### Ontwikkeling

Voor de ontwikkeling heb ik gebruik gemaakt van een repository die Vasilis voorheen heeft gemaakt, deze heb ik geforkt en aangepast voor mijn project.
De repo is een Youtube embed met pauzerende subtitles, timestamps voor subtitles en timestamps voor geluiden. Dit was ideaal voor mijn project.

Eerst heb ik op Youtube grondig zitten zoeken naar welke clip ik zou moeten gebruiken, daarna heb ik de audioscript (.srt bestand) gevonden waardoor ik de subtitles en de timestamps er van had.
Mijn doel hier was om een redelijk verwerkte basis te tonen in de week 2 test moment.


<details>
  <summary>
    Week 2
  </summary>
</details>

<details>
  <summary>
    Week 3
  </summary>
</details>

<details>
  <summary>
    Week 3
  </summary>
</details>


# Web Typography, 2020/2021

Als je doof bent, of als je om een andere reden geen geluid kunt horen, dan mis je veel informatie als je een film kijkt. Knisperende voetstappen, langzaam aanzwellende muziek, nerveus getik op een deur, je hoort het natuurlijk allemaal niet. Nu bestaat er zoiets als *closed caption*, wat een type ondertiteling is waarbij ook dingen als omgevingsgeluiden en de muziek beschreven worden. Hierdoor krijgt een kijker die informatie wel binnen.

Alleen wordt die auditieve informatie nogal neutraal beschreven. Het geluid van huilend persoon zou bijvoorbeeld beschreven kunnen worden als *snikgeluid op de achtergrond*. En iemand die lacht zou geschreven kunnen worden als *iemand lacht.* Heel neutraal, bijna zakelijk, en bovendien allebei in precies hetzelfde neutrale lettertype. Terwijl het toch echt over twee heel verschillende emoties gaat. 

Dat kan visueel sterker. 

En dat gaan jullie doen.

## Leerdoelen

- Je kan de kennis over vormgeving die je hebt opgedaan tijdens de minor technisch toepassen met behulp van CSS
- Je kan verborgen nuance uit een audiotrack overtuigend vertalen naar visuele (typografische) beelden
- Je kan je typografische keuzes onderbouwen.
- Je hebt de exclusive design principles gebruikt.

## Oplevering

Je levert een werkende versie op, gemaakt met HTML, CSS en JavaScript. Deze staat op Github. In een duidelijke readme documenteer en onderbouw je je ontwerpkeuzes. Je developmentgeschiedenis is terug te vinden op GitHub.

Je levert ook een *screen recording* met audio op van je fragment. Dit is een video van de definitieve versie, gemaakt van jouw browserscherm.

De beoordeling is mondeling en volgt [de rubric uit het beoordelingsformulier](web-typografie-beoordeling.pdf).

## Typografische restricties

Je *moet* een van deze twee opties kiezen, en je keuze moet je onderbouwen. In je readme staat een uitleg over je overwegingen om de ene of de andere restrictie te kiezen.

### Optie 1: Systeemfont

De eerste optie is dat je gebruik maakt van het zogenaamde *systeemfont* van degene die naar jouw werk kijkt. Dit font verschilt per operating system, en het verschilt soms zelfs per versie van het operating system. Het is ook aan te passen door de gebruiker zelf. 

Je hebt dus geen controle over welk lettertype er precies gebruikt wordt. Het levert dus een onzeker, en beperkt typografisch palet op. Je hebt geen *light* versies, of *extrabold*. En ook geen serif en sans-serif versie van dezelfde familie. In dit geval heb je alleen de beschikking over normal, **bold** en _italic_. Dit heeft natuurlijk ook zijn voordelen!

### Optie 2: Brenner

Je kan er ook voor kiezen om gebruik te maken van de complete Brenner familie. Dit is een zeer uitgebreid en uiterst flexibel font. [Hier kan je je verdiepen in dit font](https://www.typotheque.com/blog/brenner_an_unusual_typeface_family_with_distinct_voices). Als je kiest voor dit font dan heb je de beschikking over een *sans serif*, een *condensed*, een *serif*, een *monotype*, een *slab*, een *display* en een *script* versie. En veel van deze versies hebben varianten van *light* tot *bold*, en allemaal zowel *bold* als *italic*.

Met Brenner zijn er natuurlijk veel en veel meer mogelijkheden dan met systeemfonts. Dat kan zowel een voordeel als een nadeel zijn. 

Voor een overzicht, zie [de brenner.pdf](brenner.pdf).

## Het fragment

Ik heb een fragment voorbereid. Het gaat om twee scenes uit *Blade Runner 2049*. De captions staan in de HTML, en ze verschijnen in sync met de video. [Kijk maar](closed-captions/index.html).

### De captions

De captions staan in de html, in het bestand index.html. Je kan aan elke paragraaf eventueel een of meer classes toevoegen. Bijvoorbeeld `voice1` of `voice2 soft`. Classes voeg je handmatig toe in de html.

Met JavaScript worden er een paar dingen extra gedaan: 

- er wordt aan elke paragraaf een unieke class toegevoegd (`p0`, `p1`, etc)
- Elk woord wordt in een aparte `span` gezet. Hierdoor kan je elk woord apart stylen, en eventueel ook [na elkaar laten verschijnen](https://github.com/cmda-minor-vid/web-typography-18-19/blob/master/closed-captions/css.css#L41).

### Tijdens het afspelen

Tijdens het afspeelen wordt er een class `on` op de caption gezet als hij moet verschijnen, en een class `off` als hij klaar is. *Zowel class `on` als class `off` blijft op de caption staan!*

De timimg van de captions kan je aanpassen in [closed-captions/captions.js](closed-captions/captions.js).

Er verschijnen ook classes op de body op momenten dat er geluiden worden afgespeeld, zoals `sound1` en `sound2`. Je kan geluiden toevoegen in [closed-captions/sounds.js](closed-captions/sounds.js).

*let op,* de geluiden zijn niet compleet, dit zal je zelf moeten aanvullen.

## Een eigen fragment (afgeraden, uitgebreide onderbouwing is nodig)

Je kan er ook voor kiezen om een eigen, *beter* fragment te gebruiken. Dit wordt afgeraden. De tijd die je besteedt aan het zoeken naar dat fragment kan je beter besteden aan het werken aan de opdracht. Bovendien blijkt dat er vaak fragmenten worden gekozen die niet goed voldoen aan de opdracht. Als je een ander fragment kiest dan *moet* je dit goed onderbouwd voorleggen aan je docent. De deadline hiervoor is vrijdagochtend in de eerste week.

### Waar moet je op letten bij het kiezen van een eigen fragment.
Lees de opdracht nog eens goed door. Waar gaat het ook al weer precies om? 

Voor een goede onderbouwing van je keuze voor een ander fragment moet je deze vragen in elk geval beantwoorden:

- Welke informatie zit er in de audio die echt niet zichtbaar is?
- Welke rol speelt de audio in het fragment?
- Werkt de scene nog zonder geluid?
- Waarom is dit fragment beter dan het aangeboden fragment?

Je kan dan de nodige HTML en JavaScript genereren door gebruik te maken van [caption generator](https://cmda-minor-vid.github.io/web-typography-18-19/generator/) (in Google Chrome). 

Als je de closed captions wil bewerken dan kan je een tool zoals [Amber Script](https://www.amberscript.com/en) gebruiken. Daar kan je exporteren als `.srt`, en die kan je weer door de generator halen.
