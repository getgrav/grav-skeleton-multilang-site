---
title: Aan de slag met Grav
date: 09:55 07-07-2015
headline: Grav is heel eenvoudig te installeren, volg ons...
taxonomy:
    category: blog
    tag: [grav]
---

Grav is heel eenvoudig te installeren. Omdat er geen databank komt bij kijken. Het kan werkelijk zo eenvoudig als het uitpakken van Grav's basis (of schema) in de map van de web server.

De vrijwel enige voorwaarde is dat uw server beschikt over PHP 5.4 of hoger. Je kan Grav gebruiken met Apache, Nginx, LiteSpeed, IIS enz.


---

## Mogelijkheid 1: installeer middels een ZIP archief

De eenvoudigste manier om Grav te installeren is middels een ZIP archief als volgt:

1. Laad het allernieuwste Grav basis archief van de [Downloads](http://getgrav.org/downloads) pagina.
2. Pak dit ZIP archief uit in de webroot van uw web server, bijvoorbeeld `~/public_html/grav`.

Indien u het reeds uitgepakte ZIP archief wil verplaatsen naar de webroot, let erop de **hele map** te verplaatsen vanwege de verborgen bestanden (zoals `.htaccess`) die standaard niet geselecteerd worden. Wanneer deze verborgen bestanden ontbreken, zou de werking van Grav kunnen haperen.

---

## Mogelijkheid 2: installeer middels GitHub

Een alternative manier bestaat erin Grav te installeren vanuit zijn GitHub repository en vervolgens het eenvoudig afhankelijkheden installatie script uit te voeren.

Clone de Grav GitHub repository in de webroot van uw web server, bv. `/public_html/grav`. Activeer een `Terminal` of `Command Line` en plaats je in de webroot:

```text
$ cd ~/public_html
$ git clone https://github.com/getgrav/grav.git
```

Installeer de **plugin** and **thema** afhankelijkheden middels de [Grav CLI toepassing](http://learn.getgrav.org/advanced/grav-cli) `bin/grav`:

```text
$ cd ~/public_html/grav
$ bin/grav install
Dit zal automatisch alle nodige afhankelijkheden vanuit GitHub rechtstreeks in de Grav installatie clonen.
```

Meer informatie over de installatie en het vernieuwen van Grav vindt u terug in de [officiële documentatie](http://learn.getgrav.org/basics/installation).
