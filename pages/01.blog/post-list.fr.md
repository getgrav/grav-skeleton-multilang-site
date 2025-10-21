---
title: Accueil
slug: accueil
class: home
sitemap:
    changefreq: monthly
content:
    items: '@self.children'
    order:
        by: date
        dir: desc
    limit: 5
    pagination: true
feed:
    description: 'Titre Flux RSS'
    limit: 10
---

