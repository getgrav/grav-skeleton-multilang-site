---
title: Empezando con Grav
date: 09:55 07-07-2015
headline: Grav es una super fácil de instalar, solo sigue leyendo...
taxonomy:
    category: blog
    tag: [grav]
---

Grav es muy fácil de instalar. Debido a que no requiere una base de datos, la instalación puede ser tan simple como extraer un zip con el Grav core (o un esqueleto) en el directorio del servidor en el que desees que Grav install aparezca.

El único requerimiento real de Grav es que tu servidor este corriendo PHP 5.4 o mayor. Puedes usar Grav con Apache, Nginx, LiteSpeed, IIS, etc.

---

## Opción 1: Instalar con el paquete ZIP

La manera más fácil de instalar Grav es usar el paquete ZIP e instalarlo:

1. Descarga el último-y-mejor paquete Grav Base de la página de [Descargas](http://getgrav.org/downloads).
2. Descomprime el archivo ZIP en el webroot de tu web server, ejem. `~/webroot/grav`.

Si has descargado el archivo ZIP y luego planeas moverlo a tu webroot, por favor mueve la **carpeta completa** porque contiene varios archivos ocultos (como `.htaccess`) que no será seleccionado por defecto. La omición de estos archivos ocultos pueden generar problemas cuando intentes correr Grav.

---

## Opción 2: Instala desde Github

El método alternativo es instalar Grav desde el repositorio de Github y luego ejecutar un simple script de instalación de dependencias.

Clona el repositorio de Grav desde Github a una carpeta en el webroot de tu server, ejem. `~/webroot/grav`. Abre un `Terminal` o `Línea de Comando` y navega a la carpeta de tu webroot:

```texto
$ cd ~/webroot
$ git clone https://github.com/getgrav/grav.git
```

Instala el **plugin** y las **dependencias** usando el [Grav CLI application](http://learn.getgrav.org/advanced/grav-cli) `bin/grav`:

```texto
$ cd ~/webroot/grav
$ bin/grav install
Esto automáticamente clonará las dependencias requeridas desde Github directamente a tu instalación de Grav.
```

Puedes encontrar más información sobre instalar y actualizar Grav visitando la [Documentación Oficial](http://learn.getgrav.org/basics/installation) de Grav.
