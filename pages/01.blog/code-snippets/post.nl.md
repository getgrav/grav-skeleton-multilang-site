---
title: Code fragmenten
date: 09:57 08-05-2015
headline: Stukjes code aan uw post toevoegen is poepsimpel
taxonomy:
    category: blog
    tag: [grav, tips]
---


U kan eenvoudig code fragmenten aan de inhoud toevoegen. Code fragmenten die in de tekst vloeien (inline), worden opgemaakt zodat ze afsteken tegen de normale tekst, of gescheiden in een hun eigen paragraaf om de structuur te bewaren en de syntax te belichten. Deze gids zet je verder op weg.

===

## Een inline code fragment

Inline code is handig om een string, een bestand- of functienaam toe te voegen zonder de structuur van de tekst te onderbreken. Hiervoor moet u het code fragment tussen 1 `` ` `` teken plaatsen. Bijvoorbeeld:

```text
In dit voorbeeld zou `<section></section>` als **code** moeten opgemaakt worden.
```

Het resultaat is als volgt:

In dit voorbeeld zou `<section></section>` als **code** moeten opgemaakt worden.

> Inline code krijgt geen speciale syntax opmaak. Het is enkel bedoeld voor kleine fragmentjes.


## Een inspringend code fragment

Uw tekst met code met minstens 4 spaties doen inspringen, is een andere manier om dit als code fragment te laten opmaken door Grav.

<pre>
    // Enkele opmerkingen
    code lijn 1
    code lijn 2
    code lijn 3
</pre>

wordt opgemaakt als:

    // Enkele opmerkingen
    code lijn 1
    code lijn 2
    code lijn 3


## Een code fragment middels omsluitende hekjes

Dit is zonder twijfel de krachtigste wijze om code fragmenten toe te voegen vanwege de volledige controle over de structuur. Elke lijn die u wenst op te maken als een code fragment plaats u tussen hekjes die bestaan uit 3 `` ` `` tekens. Voeg onmiddellijk na het openingshekje het type code toe voor een correcte syntax herkenning en opmaak. Bijvoorbeeld:

<pre>
``` markup
Sample text here...
```
</pre>

wordt opgemaakt als:

``` markup
Sample text here...
```

Een ander code fragment, voorbeeld HTML:

``` html
<HTML>
   <HEAD>
      <TITLE>
         A Small Hello
      </TITLE>
   </HEAD>
<BODY>
   <H1>Hi</H1>
   <P>This is very minimal "hello world" HTML document.</P>
</BODY>
</HTML>
```

U vindt een completere Markdown leidraad voor de inhoud van uw website in de [officiële Grav documentatie](http://learn.getgrav.org/content/markdown).
