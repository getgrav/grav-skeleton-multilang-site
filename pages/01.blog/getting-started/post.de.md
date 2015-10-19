---
title: Wie du mit Grav beginnst!
date: 09:55 07-07-2015
headline: Grav ist sehr einfach zu installieren, folge einfach …
taxonomy:
    category: blog
    tag: [grav]
---

Grav ist sehr einfach zu installieren. Weil es keine Datenbank benötigt – die Installation erfolgt durch das entpacken des Grav Basis-System (oder Basis-System mit einem Template) und das ablegen in das Server Verzeichnis – schon ist Grav installiert.

Das einzige was Grav benötigt, ist dass der Server mit einer PHP-Version von 5.4 oder höher läuft. Du kannst Grav mit Apache, Nginx, LiteSpeed, IIS, etc. nutzen.

---

## Option 1: Installieren mit dem Download der ZIP-Datei

Der einfachste Weg um Grav zu installieren ist die ZIP-Datei herunter zu laden und zu installieren:

1. Lade dir einfach die letzte Version von Grav unter [Downloads](http://getgrav.org/downloads) herunter.
2. Entpacke die ZIP-Datei und lege Sie in deinem Root Verzeichnis auf dem Server ab `~/webroot/grav`.

Wenn du die die ZIP-Datei herunter geladen hast und in dein Web-Verzeichnis kopieren möchtest, kopiere bitte den **gesamten Ordner**, das heisst mit allen versteckten Dateien (wie z.B. '.htaccess'). Diese wird beim normalen kopieren von Dateien nicht kopiert. Ohne diese versteckten Dateien kann es aber zu Fehlern der Installation kommen.

---

## Option 2: Das installieren über GitHub

Die alternative zum Download der ZIP-Datei ist die Installation über Github – ein ausführendes Script erledigt die Installation:

Kopiert wird die aktulle Version Version von Github in ein Web-Verzeichnis Eurer Wahl – wie z.B. `~/webroot/grav`. Öffnet das `Terminal` or `Befehlszeile`

```text
$ cd ~/webroot
$ git clone https://github.com/getgrav/grav.git
```

Installiere **Plugins** und Templates **dependencies** mit der Funktion [Grav CLI application](http://learn.getgrav.org/advanced/grav-cli) `bin/grav`:

```text
$ cd ~/webroot/grav
$ bin/grav install
This will automatically clone the required dependencies from GitHub directly into this Grav installation.
```

Du findest mehr Informationen über das Installieren und Aktualisieren in der [Gav Dokumentation](http://learn.getgrav.org/basics/installation).
