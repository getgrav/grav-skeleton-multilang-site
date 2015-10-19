---
title: Code Schnipsel
date: 09:57 08-05-2015
headline: Code in deinen Beitrag zu integrieren ist so einfach wie noch nie
taxonomy:
    category: blog
    tag: [grav, tips]
---

Du kannst einen Code Schnipsel schnell und einfach in deinen Beitrag integrieren. Diesen Code Schnipsel kannst du sowohl in deinen bestehenden Absatz integrieren, als auch in einem separaten Absatz eingefügen. Dieses Tutorial zeigt Dir wie es geht.

===

## Code Schnipsel im Absatz

Code in einer Zeile Absatz einzufügen ist sehr einfach – du kannst eine spezielle Datei oder Funktion einzufügen, ohne deinen Satz zu unterbrechen. Wenn du etwas einfügen möchtest, setze es in Anführungszeichen  `` ` ``. Hier ist ein Beispiel:


Code in einer Zeile einzufügen ist sinnvoll wenn du nur ein kurzen Code einfügen möchtest.

```text
In diesem Beispiel, `<section></section>` wird umschlossen mit **code**.
```

Dargestellt als:

In diesem Beispiel, `<section></section>` wird umschlossen mit **code**.

> Code innerhalb eines Satzes wird nicht als Syntax highlighting dargestellt. Es ist sinnvoll für kurze Codezeilen.

## Eingerückter Code

Eingerückter Code ist ein schneller und einfacher Weg um einen Codeblock zu erstellen. Durch Einrücken des Codes mit mindestens vier Leerschlägen (Spaces) wird Grav diesen als Codeblock darstellen.

<pre>
  // Einige Kommentare
  Codezeile 1
  Codezeile 2
  Codezeile 3
</pre>

Wird zu:

    // Einige Kommentare
    Codezeile 1
    Codezeile 2
    Codezeile 3

## Block Code "Fences"

Dies ist die leistungsstärkste Methode zum Erstellen eines Codeblocks, welche die beste Kontrolle über die Ausgabe bietet. Füge einfach die Codezeilen die du darstellen möchtest in einem Block bestehend aus drei  `` ` `` Zeichen am Anfang und Ende deines Codes. An die eröffnenden `` ` `` fügst du den Typ des Codes in dem Codeblock ein. Zum Beispiel:

<pre>
``` markup
Beispieltext hier...
```
</pre>

Wird folgendermassen dargestellt:

```
Beispielstext hier...
```

HTML Beispiel:

``` html
<HTML>
   <HEAD>
      <TITLE>
         Ein kleines Hallo
      </TITLE>
   </HEAD>
<BODY>
   <H1>Hi</H1>
   <P>Dies ist ein wirklich minimalistisches "Hallo Welt" HTML Dokument.</P>
</BODY>
</HTML>
```

Du findest eine ausführlichere Anleitung über das Verwenden von Markdown im Inhalt der Website in der [offiziellen Grav Dokumentation](http://learn.getgrav.org/content/markdown).
