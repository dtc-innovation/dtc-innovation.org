---
name: Livres numériques multi-support
short_description: >
  Prototypage de livres numériques pour le web, en e-book et imprimables à la demande à partir d'une source unique.
image: images/projects/livres-numeriques.jpg
customer: louvre-editions
labels:
  - Publishing
  - Ingéniérie administrative
  - Web to print
highlights_order: 3
current_stage: Écriture des livrables du marché public
next_stage: Inscription du marché au budget 2019
resources:
  - name: Code source
    url: 'https://gitlab.com/louvre'
---

# Contexte

Les [éditions du Louvre][] ont pris connaissance du travail de
[Getty Publications][] et du [mémoire d'Antoine Fauchié][].
Leur envie était d'expérimenter un nouveau format de publication scientifique,
consultable par le grand public.

# Un code source, des artéfacts multiples

![Extrait du livre en format web]({{ 'images/projects/livres-numeriques/louvre-web.png' | relative_url }})

Un enjeu fort est de rassembler en un seul endroit (un dépôt Git), des fichiers qui contiennent des textes (Markdown) et des données structurées (CSV, YAML).
Un automate se charge d'assembler le site web duquel sont dérivées les formats détachables : le PDF primable et l'e-book pour sa liseuse numérique.

Si l'écriture perdure sous Word, les textes définitifs, leurs corrections et les images sont remachinées à chaque changement.

# Formalisation du processus

Nous nous asseyons aux côté d'une éditrice des Éditions du Louvre pour prototyper des livres numériques à partir de deux livres déjà publiés.

Nous apprenons de nos métiers respectifs : les outils pour écrire en Markdown, versionner avec Git ainsi que la rigueur des publications scientifiques.

Nous dessinons ainsi le chemin que prendrait chaque livre numérique à paraître, pour mieux comprendre quelles sont les compétences demandées, à quelle(s) étape(s) d'un projet de livre numérique.

# Documentation du marché public

![Extrait du livre en format imprimable]({{ 'images/projects/livres-numeriques/louvre-pdf.png' | relative_url }})

Le Louvre est un établissement public. L'ouverture d'un marché public est indispensable pour créer des œuvres en formats numériques sans avoir à tout développer en interne.

La production des prototypes indique précise les points importants à faire figurer sur le cahier des charges attaché au marché public : quels outils, quelles méthodes, quelle ouverture. 

[éditions du Louvre]: http://editions.louvre.fr/
[Getty Publications]: http://www.getty.edu/publications/
[mémoire d'Antoine Fauchié]: https://memoire.quaternum.net/
