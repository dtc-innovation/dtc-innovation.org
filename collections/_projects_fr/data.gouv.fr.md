---
name: data.gouv.fr
short_description: |
  Améliorer l'expérience utilisateur de la plate-forme open data de l'État.
labels:
  - Open Data
  - Recherche utilisateurs
  - Développement web
highlights_order: 2
customer: etalab
current_stage: En pause
image: /images/projects/datagouv.png
resources:
- name: GitHub
  url: https://github.com/opendatateam/udata
- name: Site web
  url: https://www.data.gouv.fr
- name: Recherche utilisateurs
  url: https://github.com/etalab/user-research
---

Nous améliorons la qualité de l'expérience utilisateur du portail
[data.gouv.fr][] sur la base d'une approche centrée utilisateurs.

# Des entretiens utilisateurs

Nous avons mené des entretiens avec une dizaine d'utilisateurs et utilisatrices de la plate-forme [data.gouv.fr][] : journalistes, développeurs, datascientists, designers et citoyen·ne·s.

Ces entretiens ont été [documentés, publiés et consolidés][user-research] sous forme d'une matrice fonctionnelle.

![]({{ 'images/projects/data.gouv.fr/summary-201710.jpg' | relative_url }})

Plusieurs axes et pistes d'amélioration ont émergé des entretiens :

- l'expérience de recherche ;
- la compréhension de la présentation des jeux de données ;
- l'accès aux données.

# Prototypage et itérations fonctionnelles

Les fonctionnalités et améliorations de l'expérience utilisateurs
ont été dérivées des entretiens.

Elles ont été développées petit à petit et de deux manières :

1. des **captures d'écran** illustrant la proposition de valeur ;
2. des **prototypes fonctionnels** pour explorer des pistes possibles.

![]({{ 'images/projects/data.gouv.fr/posters.jpg' | relative_url }})

Dans les deux cas, l'idée est de construire les bases solides pour dialoguer ainsi qu'une feuille de route partagée par l'équipe.

Les développements se sont faits dans un contexte applicatif _Flask_ (Python) et _Vue_ (JavaScript).

# Des ateliers collaboratifs

Nous avons organisé plusieurs types d'ateliers collaboratifs avec les équipes d'[Etalab][etalab] :

- théâtre d'improvisation pour mieux accepter la prise de risque et l'acceptation des erreurs ;
- formations/déjeuner pour renforcer sa pratique de JavaScript, Node.js et npm ;
- revues de code au vidéoprojecteur ;
- cliniques d'écriture pour co-écrire les articles du [calendrier de l'Avent][]

![]({{ 'images/projects/data.gouv.fr/cercle-de-parole.jpg' | relative_url }})

Ces ateliers croisent les pratiques et les expériences pour rééquilibrer les équipes et leur capacité à s'entraider.

[etalab]: https://www.etalab.gouv.fr
[data.gouv.fr]: https://www.data.gouv.fr
[calendrier de l'Avent]: https://avent.data.gouv.fr
[user-research]: https://github.com/etalab/user-research
