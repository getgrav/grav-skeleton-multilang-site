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

## Indented Code

Intending your code is a quick and easy way to create a code block. By intending your code with at least four spaces, Grav will render it in a code block.

<pre>
  // Some comments
  line 1 of code
  line 2 of code
  line 3 of code
</pre>

Renders to:

    // Some comments
    line 1 of code
    line 2 of code
    line 3 of code

## Block Code "Fences"

This is easily the most powerful method of creating a code block as it gives you optimal control over the output. You place any lines you would like to have appear in the code block within fences, consisting of three `` ` `` characters, with the first instance being followed directly by the type of code being presented in the code block. For example:

<pre>
``` markup
Sample text here...
```
</pre>

Renders as:

```
Sample text here...
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

You can find a more complete guide for using Markdown in your site's content in the [official Grav documentation](http://learn.getgrav.org/content/markdown).
