---
title: Fragmenty kodu
date: 09:57 08-05-2015
headline: Wstawianie kodu do twojej strony jest bardzo proste
taxonomy:
    category: blog
    tag: [grav, tips]
---


Możesz dodać fragmenty kodu do swojego wpisu, które będą się wyświetlać zaraz obok twojego tekstu. Kod jest wtedy delikatnie podświetlony, tak, aby wyróżniał się od pozostałej treści. Twój kod może być również umieszczony w nowej linijce, zyskuje wtedy na czytelności i korzysta z podświetlania składni. Poniższa prezentacja pomoże ci wybrać odpowiednie rozwiązanie.

===

## Kod w tej samej linii

Umieszczenie kodu w tej samej linii, jest użyteczne kiedy chcesz umieścić fragment kodu bez przerywania zdania. Aby to zrobić, umieść swój fragment pomiędzy `` ` ``. Oto przykład:

```text
W tym przykładzie znacznik, `<section></section>` powinien zostać przedstawiony jako **kod**.
```

Wyświetli się jako:

W tym przykładzie znacznik, `<section></section>` powinien zostać przedstawiony jako **kod**.

> Kod umieszczony w tej samej linii nie zawiera podświetlania składni. Ta funkcja jest dedykowana tylko do krótkich wstawek.

## Kod z wcięciami

Stworzenie wcięć w kodzie, jest najłatwiejszym sposobem na przedstawienie fragmentu kodu w osobnym bloku. Jeśli twój kod będzie miał wcięcia składające się przynajmniej z 4 spacji, Grav wyrenderuje go jako osobny blok.

<pre>
  // Jakiś komentarz
  1 linijka kodu
  2 linijka kodu
  3 linijka kodu
</pre>

Wyświetli się jako:

    // Jakiś komentarz
    1 linijka kodu
    2 linijka kodu
    3 linijka kodu


## Blok kodu "Barierki"

To jest najlepsza metoda tworzenia bloków kodu, ponieważ daje optymalną kontrolę nad wyświetlaniem. Umieszczasz dowolną treść pomiędzy barierkami składającymi się z trzech `` ` `` znaków, a pierwszy wyraz definiuje typ kodu jaki ma zostać wyświetlony w bloku. Przykładowo

<pre>
``` markup
Przykładowy tekst tutaj...
```
</pre>

Wyświetli się jako:

```
Przykładowy tekst tutaj...
```

Przykład HTML:

``` html
<HTML>
   <HEAD>
      <TITLE>
         Siema siema
      </TITLE>
   </HEAD>
<BODY>
   <H1>Cześć</H1>
   <P>To jest bardzo podstawowy dokument "witaj świecie".</P>
</BODY>
</HTML>
```

Kompletny przewodnik dot. Markdown możesz znaleźć odwiedzając [oficjalną dokumentację Grav](http://learn.getgrav.org/content/markdown) (wersja w języku angielskim). 
