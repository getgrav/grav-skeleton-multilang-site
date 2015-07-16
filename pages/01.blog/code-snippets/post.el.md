---
title: Αποσπάσματα Κωδίκων
date: 09:57 08-05-2015
headline: Συμπεριλαμβάνοντας κώδικα στις δημοσιεύσεις
taxonomy:
    category: blog
    tag: [grav, tips]
---


Μπορεί να συμπεριλάβει κανείς κομμάτια κώδικα στο περιεχόμενο της σελίδας του εύκολα και γρήγορα. Αυτά τα κομμάτια κώδικα πορούν να γραφτούν μαζί με το υπόλοιπο κείμενο στον κανονικό επεξεργαστή με τη μόνη διαφορά ότι θα φαίνονται με διαφορετική ορφοποίηση ώστε να φαίνετε η διαφορά τους από το υπόλοιπο περιεχόμενο, ή τοποθετόντας το σε ένα μπλόκ κώδικα μέσα στον πόλοιπο κώδικα. Αυτός ο οδηγός θα σας βοηθήσει ώστε να ξεκινήσετε.


===

## Κώδικας μέσα στο κείμενο

Inline code is handy when you want to insert a string of code, or a specific file or function name without breaking your sentence. o do this, simply wrap your snippets with `` ` ``. Εδώ έχουμε ένα παράδειγμα:

```text
In this example, `<section></section>` should be wrapped as **code**.
```

Αποδίδεται ως:

In this example, `<section></section>` should be wrapped as **code**.

> Inline code will not include syntax highlighting. It is only intended for quick snippets.

## Στοιχίζοντας τον κώδικα.

Στοιχίζοντας τον κώδικα σου είναι ένας γρήγορος και εύκολος δρόμος για να δημιουργήσεις ένα μπλόκ κώδικα. Στοιχίζοντας τον ώδικά σου με το λιγότερο τέσσερα κενά, το Grav θα το αποδώσει ως μπλόκ κώδικα.

<pre>
  // Some comments
  line 1 of code
  line 2 of code
  line 3 of code
</pre>

Αποδίδεται ως:

    // Some comments
    line 1 of code
    line 2 of code
    line 3 of code

## Μπλοκ Κώδικα "Fences"

Αυτή είναι άνετα η πιο δυνατή μέθοδος δημιουργίας ενός μπλόκ κώδικα, καθώς δίνει τον οπτικό έλεγχο της εξόδου. Τοποθετείτε κάθε ραμμή που θέλετε να φαίνεται στο μπλόκ κώδικα χωρίς αγκύλες, αποτελούμενο από τρείς `` ` `` χαρακτήρες, Τοποθετόντας ακριβώς ετά τον τύπο του κώδικα που είναι να παρουσιαστεί στο μπλόκ κώδικα.
Για παράδειγμα:

<pre>
``` markup
Sample text here...
```
</pre>

Μεταφέρετε ως:

```
Sample text here...
```

Παράδειγμα HTML:

``` html
<HTML>
   <HEAD>
      <TITLE>
         Ένα μικρό Γειά.
      </TITLE>
   </HEAD>
<BODY>
   <H1>Hi</H1>
   <P>Αυτό είναι ένα πολύ απλό  "hello world" HTML document.</P>
</BODY>
</HTML>
```

Μπορείτε να βρείτε έναν πιο αναλυτικό οδηγό για τη χρήση Markdown στα περιεχόμενα της ιστοσελίδας σας στο [official Grav documentation](http://learn.getgrav.org/content/markdown).
