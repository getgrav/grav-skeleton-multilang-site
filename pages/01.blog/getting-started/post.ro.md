---
title: Noțiuni de bază despre Grav
date: 09:55 07-07-2015
headline: Grav este foarte ușor de instalat, doar urmează pașii...
taxonomy:
    category: blog
    tag: [grav]
---

Grav este foarte ușor de instalat. Pentru că nu are nevoie de o bază de date, instalarea poate fi simplă precum dezarhivarea fișierelor de bază (sau a skeleton) în folderul de pe server, unde dorești sa instalezi Grav.

Singura cerință pe care o are Grav, este ca serverul tău să ruleze PHP 5.4 sau mai nou. Poți să folosești Grav cu Apache, Ngix, LiteSpeed, IIs etc.

---

## Opțiunea 1: Instalarea cu arhivă ZIP

Cea mai ușoară cale să instalezi Grav este să folosești pachetul ZIP:

1. Descarcă cea mai nouă și minunată arhivă de bază Grav de la pagina de [Descărcări](http://getgrav.org/downloads).
2. Extrage fișierele din arhiva ZIP în webroot pe server-ul tău, e.g. `~/webroot/grav`.

Dacă ai descărcat fișierele ZIĂ și apoi dorești să le muți în webroot, mută **tot folderul** pentă că el conține multe fișiere ascunse (precum `.htaccess`) care nu va fi selectat implicit. Omisiunea acestor fișiere ascunse poate cauza probleme când rulezi Grav.

---

## Opțiunea 2: Instalează de pe GitHub

Metoda alternativă este să instalezi Grav din repozitoriul GitHub, iar apoi să rulezi un simplu script pentru instalarea dependenței:

Clonează repozitoriul Grav de pe GitHub într-un folder în webroot pe serverul tau, e.g. `~/webroot/grav`. Deschide un `Terminal` sau `Command Line` și navighează în folderul webroot:

```text
$ cd ~/webroot
$ git clone https://github.com/getgrav/grav.git
```

Instalează **pluginul** și theme  **dependencies** utilizând [aplicația Grav CLI](http://learn.getgrav.org/advanced/grav-cli) `bin/grav`:

```text
$ cd ~/webroot/grav
$ bin/grav install
This will automatically clone the required dependencies from GitHub directly into this Grav installation.
```

Vezi găsi mai multe informații despre instalarea Grav vizitând [documentația oficială](http://learn.getgrav.org/basics/installation).
