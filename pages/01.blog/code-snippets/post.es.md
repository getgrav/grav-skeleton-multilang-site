---
title: Snippets de Código
date: 09:57 08-05-2015
headline: Incluyendo bloques de código en tus posts es bastante simple
taxonomy:
    category: blog
    tag: [grav, consejos]
---

Puedes agregar bloques de código a tu contenido de forma rápida y fácil. Estos bloques de código pueden estar en la misma línea que el texto, pueden ser resaltados para que mejorar su visibilidad, o posicionados en su propio bloque para preservar el formato y activar el resaltado por sintaxis. Esta guía te ayudara a empezar.

===

## Código Inline

Código Inline (en la misma línea) es útil cuando desees insertar una línea de código, o un archivo específico, o un nombre de función sin quebrar tu oración. Para hacer esto, solamente envuelve tus snippets con `` ` ``. Acá hay te dejamos un ejemplo:

```texto
En este ejemplo, `<section></section>` debería ser envuelto como **código**
```

Se mostrará como:

En este ejemplo, `<section></section>` debería ser envuelto como **código**.

> Código Inline no incluirá resaltado de sintaxis. La idea es usarlo para snippets cortos.

## Código Indentado

Indentar tu código es una forma rápida y fácil de crear un bloque de código. Indentar tu código con al menos cuatro espacios, Grav lo mostrará en un bloque de código.

<pre>
  // Algunos comentarios
  línea 1 de código
  línea 1 de código
  línea 1 de código
</pre>

Se mostrará como:

    // Algunos comentarios
    línea 1 de código
    línea 1 de código
    línea 1 de código

## Bloque de Código "Vallas"

Este es probablemente el método más poderoso de crear un bloque de código, debido a que te da control optimo sobre el resultado. Inserta cualquier línea que te gustaría que aparezca en el bloque de código entre las vallas, consistiendo de tres caracteres `` ` ``, con la primera instancia seguida directamente con el tipo de código que está siendo presentado en tu bloque de código. Por ejemplo:

<pre>
``` markup
Texto de ejemplo aquí...
```
</pre>

Se mostrará como:

```
Texto de ejemplo aquí...
```

Ejemplo en HTML:

``` html
<HTML>
   <HEAD>
      <TITLE>
         Un Pequeño Hola
      </TITLE>
   </HEAD>
<BODY>
   <H1>Hola</H1>
   <P>Este es un documento "Hola Mundo" simple en HTML.</P>
</BODY>
</HTML>
```
Puedes encontrar una guía para el uso de Markdown en el contenido de tu web en la [documentación oficial de Grav](http://learn.getgrav.org/content/markdown).
