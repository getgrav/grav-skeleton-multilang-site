---
title: Fragmente de cod
date: 09:57 08-05-2015
headline: Să incluzi fragmente de cod in postarea ta este simplicitatea în sine.
taxonomy:
    category: blog
    tag: [grav, tips]
---


Poți să adaugi blocuri de cod în conținutul tau rapid și cu ușurință. Aceste blocuri de cod pot fi în linie cu textul tau, evidențiate astfel încât sa iasă în evidență față de restul conținutului, sau puse deoparte în propriul bloc pentru a păstra formatarea și a permite evidențierea sintaxei. Acest ghid te va ajuta să înțelegi noțiunile de bază.

===

## Cod în linie

Codul în linie este folositor atunci când dorești să introduci un șir de cod, sau un fișier specific sau o funcție fără a întrerupe propoziția. Pentru a face acest lucru, pur și simplu scrie codul în interiorul `` ` ``. Aici este un exemplu:

```text
In acest exemplu, `<section></section>` va fi afișat **code**.
```

Afișat ca:

În acest exeplu, `<section></section>` ar trebui să fie afișat **code**.

> Codul in linie nu include evidențierea sintaxei. Acesta este destinat numai pentru fragmente rapide.

## Indented Code

Spațierea codului este o cale rapida de a crea blocuri de cod. Prin spațierea codului cu cel puțin patru spații, Grav il va afișa ca un bloc de cod.

<pre>
  // Some comments
  line 1 of code
  line 2 of code
  line 3 of code
</pre>

Va fi afișat:

    // Some comments
    line 1 of code
    line 2 of code
    line 3 of code

## Block Code "Garduri"

Aceasta este cea mai puternică metoda de a crea blocuri de cod, pentru că îți dă control optim aspura rezultatului final. Poți scrie orice linie de cod care dorești să apară în blocul de cod, în interiorul "gardului", constând în trei `` ` `` caractere,prima instanță fiind urmărită direct de tipul de cod ce urmează a fi prezentat în blocul de cod. De exemplu:

<pre>
``` markup
Textul va fi aici...
```
</pre>

Va fi afișat ca:

```
Textul va fi aici...
```

HTML example:

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

Vei găsi mai multe informații despre folosirea Markdown în conținutul de pe site-ul tau în [Documentația oficială Grav](http://learn.getgrav.org/content/markdown).
