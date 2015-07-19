---
title: Blocchi di codice
date: 09:57 08-05-2015
headline: Includere codice nei messaggi è estremamente semplice
taxonomy:
    category: blog
    tag: [grav, tips]
---

È possibile aggiungere blocchi di codice nei propri contenuti in maniera rapida e semplice. Questi blocchi di codice possono essere in linea con il testo, evidenziati in modo da risaltare rispetto al resto del contenuto, o messi da parte in un blocco separato per mantenere la formattazione e attivare l'evidenziazione della sintassi. Questa guida aiuterà a iniziare.

===

## Codice in linea

Il codice in linea è utile quando si desidera inserire una stringa di codice, o di uno specifico file o nome di funzione senza interrompere la propria frase. Per fare questo, è sufficiente delimitare il blocco con `` ` ``. Ecco un esempio:

```text
In questo esempio, `<section></section>` dovrebbe essere delimitato come **codice**.
```

Viene reso così:

In questo esempio, `<section></section>` dovrebbe essere delimitato come **codice**.

> Il codice in linea non include l'evidenziazione della sintassi. Esso è destinato solo per blocchi veloci.

## Codice rientrato

Indentare il codice è un modo semplice e veloce per creare un blocco di codice. Con un rientro del codice con almeno quattro spazi, Grav lo rende come un blocco di codice.

<pre>
  // Alcuni commenti
  linea 1 del codice
  linea 2 del codice
  linea 3 del codice
</pre>

Viene reso così:

    // Alcuni commenti
    linea 1 del codice
    linea 2 del codice
    linea 3 del codice

## Blocco di codice virgolettato

Questo è di sicuro il metodo più potente per creare un blocco di codice che consente un controllo ottimale sul risultato. Posizionare tutte le linee che si desidera che appaiano nel blocco di codice all'interno del virgolettato, composto da tre caratteri `` ` ``, prima di tutto seguito direttamente dal codice presentato nel blocco di codice. Per esempio:

<pre>
``` marcatura
Testo di esempio qui...
```
</pre>

Viene reso così:

```
Testo di esempio qui...
```

Esempio HTML:

``` html
<HTML>
   <HEAD>
      <TITLE>
         Un piccolo ciao
      </TITLE>
   </HEAD>
<BODY>
   <H1>Ciao</H1>
   <P>Questo è un documento HTML molto minimale di "ciao mondo".</P>
</BODY>
</HTML>
```

Si può trovare una guida completa per l'uso di Markdown nel proprio sito nella [documentazione ufficiale di Grav](http://learn.getgrav.org/content/markdown).
