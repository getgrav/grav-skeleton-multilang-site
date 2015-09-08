---
title: Zacznij przygodę z Grav-em
date: 09:55 07-07-2015
headline: Grav jest niewiarygodnie łatwy w instalacji, po prostu podążaj za instrukcją...
taxonomy:
    category: blog
    tag: [grav]
---

Grav jest bardzo prosty w instalacji ponieważ nie wymaga posiadania bazy danych. Instalacja jest tak banalna, jak wypakowanie podstawy Grav (lub szkieletu) do katalogu na serwerze.

Tak naprawdę jedynym wymaganiem Grav-a jest posiadanie serwera z PHP 5.4 lub wyżej. Możesz używać Grav-a z serwerami Apache, Nginx, LiteSpeed, IIS, itd.. 

---

## Wariant 1: Instalacja z pakietu ZIP

Najłatwiejszym sposobem na instalacje Grav-a jest użycie pakietu ZIP:

1. Pobierz najnowszą i najlepszą Podstawę Grav ze strony [Downloads](http://getgrav.org/downloads).
2. Wypakuj plik ZIP do katalogu głównego na twoim serwerze np. `~/webroot/grav`.

Jeśli w przyszłości chciałbyś umieścić zawartość **Grav-a** bezpośrednio w katalogu głównym (bez podkatalogów), pamiętaj aby przenieść  **cały folder** łącznie z ukrytymi plikami (jak np `.htaccess`). Pominięcie jakichkolwiek plików może spowodować problemy w działaniu Grav-a.

---

## Wariant 2: Instalacja z repozytorium GitHub

Alternatywną metodą jest instalacja Grav-a z repozytorium GitHub-a i uruchomienie prostego skryptu który ustawi zależności:


Sklonuj repozytorium Grav-a z GitHuba do folderu w katalogu głównym twojego serwera np. `~/webroot/grav`. Potem uruchom `Terminal` lub `Wiersz Poleceń` i przejdź do katalog głównego swojego serwera:

```text
$ cd ~/webroot
$ git clone https://github.com/getgrav/grav.git
```

Zainstaluj **wtyczkę** i **zależności** szablonu używając [aplikacji Grav CLI](http://learn.getgrav.org/advanced/grav-cli) `bin/grav`:

```text
$ cd ~/webroot/grav
$ bin/grav install
This will automatically clone the required dependencies from GitHub directly into this Grav installation.
```

Więcej informacji na temat aktualizacji i instalacji Grav-a możesz znaleźć w [oficjalnej dokumentacji](http://learn.getgrav.org/basics/installation) (wersja anglojęzyczna).
