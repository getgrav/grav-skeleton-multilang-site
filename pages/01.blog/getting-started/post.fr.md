---
title: Premiers pas avec Grav
date: 09:55 07-07-2015
headline: Grav est ultra facile à installer, il suffit de suivre ainsi…
taxonomy:
    category: blog
    tag: [grav]
---

Grav est très facile à installer. Parce qu’il ne nécessite aucune base de données, l’installation peut être aussi simple que la décompression du noyau de Grav (ou d'un squelette) dans le répertoire du serveur où vous souhaitez installer votre site Grav.

La seule véritable exigence de Grav est que votre serveur peut exécuter PHP 5.4 ou supérieur. Vous pouvez utiliser Grav avec Apache, Nginx, LiteSpeed, IIS, etc.

---

## Option 1: Installation du paquet ZIP

Le moyen le plus facile pour installer Grav est d’utiliser le paquet d’installation ZIP:

1. Téléchargez le dernier paquet de l’installation de base de Grav à partir de la page des [téléchargements](http://getgrav.org/downloads).
2. Extraire le fichier ZIP dans le dossier webroot de votre serveur web, par exemple, `~/webroot/grav`.

Si vous avez téléchargé le fichier ZIPet ensuite envisagez de le déplacer à votre webroot, déplacer **l’ensemble du dossier**, car il contient plusieurs fichiers cachés (comme `.htaccess`) qui ne seront pas sélectionnés par défaut. L’omission de ces fichiers cachés peut causer des problèmes lors de l’exécution Grav.

---

## Option 2: Installation à partir de GitHub

L’autre méthode consiste à installer Grav à partir du référentiel de GitHub et ensuite exécuter un simple script d’installation des dépendances:

Cloner le référentiel Grav de GitHub dans un dossier dans le webroot de votre serveur, par exemple, `~/webroot/grav`. Démarrer un Terminal ou une ligne de commande et accédez au dossier webroot:

```text
$ cd ~/webroot
$ git clone https://github.com/getgrav/grav.git
```

Installer les dépendances du plugin et du thème en utilisant [l’application CLI de Grav](http://learn.getgrav.org/advanced/grav-cli) `bin/grav`:

```text
$ cd ~/webroot/grav
$ bin/grav install
```

Cela va cloner automatiquement les dépendances requises à partir de GitHub directement dans l’installation de Grav.

Vous pouvez trouver plus d’informations sur l’installation et la mise à jour de Grav en consultant [la documentation officielle](http://learn.getgrav.org/basics/installation) de Grav.
