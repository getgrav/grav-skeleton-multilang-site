---
title: Komme i gang med Grav
date: 09:55 07-07-2015
headline: Grav er kjempelett å installere, bare les videre...
taxonomy:
    category: blog
    tag: [grav]
---

Grav er svært lett å installere. Fordi det ikke trenger en database kan installasjonen være så enkel som å pakke ut Grav-kjernen (eller et skjelett) i server-mappen du ønsker at Grav-installasjonen skal plasseres i.

Stort sett det eneste kravet til Grav at serveren din kjører PHP 5.4 eller høyere. Du kan bruke Grav med Apache, Nginx, LiteSpeed, IIS og lignende.

---

## Valg 1: Installere med ZIP-pakke

Den letteste måten å installere Grav på er å bruke ZIP-pakken og installere den:

1. Last ned den nyeste og beste Grav-kjernepakken fra [Nedlastings](http://getgrav.org/downloads)-siden.
2. Pakk ut ZIP-filen i den øverste mappen på webserveren din, for eksempel `~/webroot/grav`.

Hvis du lastet ned ZIP-filen og planlegger å flytte den til den øverste mappen på webserveren din, vennligst flytt **hele mappen** da den inneholder flere skjulte filer (som `.htaccess`) som ikke vanligvis kommer med. Utelatelsen av disse filene kan skape problemer med å kjøre Grav.
