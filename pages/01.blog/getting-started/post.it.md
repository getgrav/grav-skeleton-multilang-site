---
title: Primi passi con Grav
date: 09:55 07-07-2015
headline: Grav è super facile da installare, basta seguire ...
taxonomy:
    category: blog
    tag: [grav]
---

Grav è molto facile da installare. Poiché non richiede un database, l'installazione è semplice come può esserlo decomprimere il nucleo Grav (o uno scheletro) nella cartella del server in cui si desidera che appaia l'installazione Grav.

Praticamente l'unico vero requisito di Grav è che sul server sia in esecuzione PHP 5.4 o superiore. È possibile utilizzare Grav con Apache, Nginx, LiteSpeed, IIS, ecc.

---

## Opzione 1: installare con il pacchetto ZIP

Il modo più semplice per installare Grav è quello di usare il pacchetto ZIP e installarlo:

1. Scaricare il più recente pacchetto di base di Grav dalla pagina [Downloads](http://getgrav.org/downloads).
2. Estrarre il file ZIP nella webroot del proprio server web, ad esempio, `~/webroot/grav`.

Se si scarica il file ZIP prevedendo di spostarlo nella propria webroot, spostare **l'intera cartella** poiché contiene diversi file nascosti (come `.htaccess`) che altrimenti non sarebbero selezionati. L'omissione di questi file nascosti possono causare problemi durante l'esecuzione di Grav.

---

## Opzione 2: Installazione da GitHub

Il metodo alternativo è quello di installare Grav dal repository GitHub ed eseguire un semplice script di installazione delle dipendenze:

Clonare il repository Grav da GitHub in una cartella nella webroot del server, ad esempio, `~/webroot/grav`. Eseguire da `Terminal` o `Command Line` posizionandosi nella cartella webroot:

```text
$ cd ~/webroot
$ git clone https://github.com/getgrav/grav.git
```

Installare il **plugin** e il tema **dependencies** usando l'[applicazione Grav CLI](http://learn.getgrav.org/advanced/grav-cli) `bin/grav`:

```text
$ cd ~/webroot/grav
$ bin/grav install
This will automatically clone the required dependencies from GitHub directly into this Grav installation.
```

Si possono trovare ulteriori informazioni sull'installazione ed aggiornamenti Grav visitando la  [documentazione ufficiale](http://learn.getgrav.org/basics/installation) di Grav.
