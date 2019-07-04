---
title: Design et Intelligence Spatiale
short_description: |
  Facilitation d'une journée d'ateliers et développement d'un prototype pour interagir avec un corpus de données dans une interface informatique non-limitative.
labels:
  - Design
  - Agile
  - Développement web
customer: ensad-lab
current_stage: Terminé
highlights_order: 3
image: /images/projects/workshop-dis/dis-panels.png
with:
- name: Julie
  url: http://julie-blanc.fr
resources:
- name: Première journée de workshop
  url: https://gitlab.com/dis-project/workshop-mars-notes/blob/master/jour-1.md
- name: Code source de la maquette
  url: https://gitlab.com/dis-project/journee-etude
- name: Maquette d'étude
  url: https://dis-project.gitlab.io/journee-etude/selma-a/
---

Le laboratoire de recherche de l'[École nationale supérieure des Arts Décoratifs][Ensad] a dirigé des efforts sur un projet de **Design en Intelligence Spatiale**.

L'EnsadLab était à la fois en demande de la facilitation d'un travail exploratoire ainsi que de la réalisation de plusieurs interfaces.

# Facilitation d'atelier

Le souhait des chercheur·se·s était d'inviter plusieurs personnes d'univers variés à partager les limites rencontrées dans les interfaces informatiques ainsi que leurs travaux — typographie, images, textes.

La journée a été préparée pour que les interactions entre participant·es nourrissent les réflexions et stimulent des partages d'idées et de solutions.

Les participant·es sont reparti·es avec une perspective nouvelle sur l'organisation de leurs données (corpus) dans l'espace… ainsi qu'avec l'attente de voir les différentes maquettes réalisées par des designeur·ses du groupe.

![]({{ 'images/projects/workshop-dis/dis-atelier.jpg' | relative_url }})


# Développement d'un prototype en 2 jours

Le prototype explore un double accès à l'information :

- un rangement hiérarchique sous forme d'arbre infini ;
- des annotations rangées dans l'espace, et dans des tiroirs.


![]({{ 'images/projects/workshop-dis/dis-tree.png' | relative_url }})

Son développement s'est basé sur des croquis de [Selma Lepart][] et sur un corpus initial matérialisé sous forme d'un fichier JSON.

Le prototype a été développé avec [Vue.js][] et sans outillage supplémentaire, simplement avec des modules ES2015 et des variables CSS, pilotées par le déplacement d'un curseur dans un état global.

![]({{ 'images/projects/workshop-dis/dis-board.png' | relative_url }})

[Ensad]: https://www.ensad.fr/recherche/ensadlab
[Vue.js]: https://vuejs.org
[Selma Lepart]: http://www.selmalepart.org/
