---
title: Kodebiter
date: 09:57 08-05-2015
headline: Å inkludere kode i innleggene dine er enkelheten selv
taxonomy:
    category: blog
    tag: [grav, tips]
---

Du kan legge til kodeblokker til innholdet ditt svært enkelt. Disse kodeblokkene kan være på linje med teksten din, uthevet slik at de skiller seg ut mot resten av innholdet, eller satt til side i sin egen blokk for å bevare formateringen og aktivere syntaksuthevingen. Denne veiledningen vil hjelpe deg å komme i gang.

===

## Innebygd kode

Innebygd kode er nyttig når du ønsker å sette inn en streng med kode, en bestemt fil, eller et funksjonsnavn uten å bryte setningen din. For å gjøre dette, pakk inn kodebitene dine med `` ` ``. Her er et eksempel:

```tekst
I dette eksempelet skal `<section></section>` være pakket inn som **kode**.
```

Vises som:

I dette eksempelet skal `<section></section>` være pakket inn som **kode**.

> Innrykket kode vil ikke inkludere syntaksutheving. Det er bare ment brukt for raske kodebiter.

## Innrykket kode

Å innrykke koden din er en enkel måte å skape en kodeblokk. Ved å innrykke koden din med minst fire mellomrom så vil Grav vise den i en kodeblokk.

<pre>
  // Noe kode
  linje en med kode
  linje to med kode
  linje tre med kode
</pre>

Vises som:

	// Noe kode
	linje en med kode
	linje to med kode
	linje tre med kode

## Kodeblokk-"Gjerder"

Dette er den mest effektive fremgangsmåten å skape kodeblokker på, ettersom den gir deg optimal kontroll over utfallet. Du plasserer alle linjer du ønsker vist i kodeblokken innenfor gjerdene, som består av tre `` ` `` tegn, der det første tilfellet etterfølges direkte av typen kode som brukes i kodeblokken. For eksempel:

<pre>
``` kode
Eksempeltekst her ...
```
</pre>

Vises som:

```
Eksempeltekst her ...
```

HTML-eksempel:

``` html
<HTML>
   <HEAD>
      <TITLE>
         Et lite hei
      </TITLE>
   </HEAD>
<BODY>
   <H1>Hei</H1>
   <P>Dette er et minimalt "hei verden" HTML-dokument.</P>
</BODY>
</HTML>
```

Du kan finne en mer komplett guide for bruken av Markdown på siden i den [offisielle Grav-dokumentasjonen](http://learn.getgrav.org/content/markdown).
