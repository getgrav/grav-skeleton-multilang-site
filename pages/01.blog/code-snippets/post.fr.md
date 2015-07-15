---
title: Fragments de code
date: 09:57 08-05-2015
headline: Incluant le code dans vos articles est le simplicité pure
taxonomy:
    category: blog
    tag: [grav, tips]
---


Vous pouvez ajouter des blocs de code dans votre contenu rapidement et facilement. Ces blocs de code peuvent être enligne avec votre texte, souligné afin qu’ils sont clairement visibles dans le reste du contenu, ou mis à part dans son propre bloc pour préserver le formatage et activer la coloration syntaxique. Ce guide va vous aider à commencer.

===

## Code Inline

Le code inline est très pratique lorsque vous souhaitez insérer une chaîne de code, ou le nom de fichier ou d’une fonction en respectant votre phrase. Pour ce faire, simplement envelopper vos extraits avec `` ` ``. Voici un exemple:

```text
Dans cet exemple, `<section></section>` doit être enveloppé comme **code**.
```

Apparaîtra comme ceci:

Dans cet exemple, `<section></section>` doit être enveloppé comme **code**.

> Code Inline ne comprendra pas la coloration syntaxique. Il est destiné uniquement à des fragments de code rapides.

## Code indenté

L’indentation de votre code est un moyen rapide et facile de créer un bloc de code. En indentant votre code avec au moins quatre espaces, Grav le rendra dans un bloc de code.

<pre>
  // Quelques commentaires
  ligne 1 du Code
  ligne 2 du Code
  ligne 3 du Code
</pre>

Apparaîtra comme ceci:

    // Quelques commentaires
    ligne 1 du Code
    ligne 2 du Code
    ligne 3 du Code

## Bloc de code "Fence"

Ceci est facilement la méthode la plus puissante de la création d’un bloc de code car il vous donne un contrôle optimal du résultat. Vous placez toutes les lignes que vous aimeriez avoir apparaissent dans le bloc de code l’intérieur des clôtures, composé de trois caractères `` ` ``. La première instance doit être suivie directement par le type de code étant présentée dans le bloc de code. Par exemple:

<pre>
``` markup
Texte d’exemple ici...
```
</pre>

Apparaîtra comme ceci:

```
Texte d’exemple ici...
```

Exemple HTML:

``` html
<HTML>
   <HEAD>
      <TITLE>
         Un petit bonjour
      </TITLE>
   </HEAD>
<BODY>
   <H1>bonjour</H1>
   <P>Ceci est document HTML très minime de "hello world".</P>
</BODY>
</HTML>
```

Vous pouvez trouver un guide plus complet d’utilisation de Markdown pour le contenu de votre site dans [la documentation officielle](http://learn.getgrav.org/content/markdown) de Grav.
