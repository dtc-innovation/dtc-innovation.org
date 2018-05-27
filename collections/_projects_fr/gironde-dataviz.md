---
name: Datavisualisation des données budgétaires
short_description: >
  Comprendre d'où vient l'argent du Département et où il est investi.
labels:
  - Datavisualisation
  - Open Data
customer: cd33
highlights_order: 1
current_stage: Terminé
next_stage: Répliquer dans un autre collectivité locale
resources:
  GitHub: 'https://github.com/dtc-innovation/dataviz-finances-gironde'
  Site web: 'https://www.gironde.fr/un-budget-au-service-des-solidarites-humaine-et-territoriale#'
  Vu chez Etalab: https://avent.data.gouv.fr/2017/07.html
---

We **design and develop** _open source software_ and _graphic materials_ for the Gironde county in order to illustrate their annual budget and financial report.

The aim is to deliver a **reusable and editorialised datavisualisation** based on an open dataset.

### Public Budget Parser

French counties publish their annual budget and financial report under the **M52 standard**. We designed it to be a **standalone NodeJS and JavaScript library**.

We use the M52 library to **validate**, to **lint** and to help the department of finance **to improve the quality of the dataset**.

### Editorial Focus

We organise **user testing sessions** to get an understanding of possible audience expectations and to validate a few hypothesis.

We facilitate **focus groups** with county agents to reflect their mission and financial report in order to match user expectations.

### Datavisualisation Components

We use **React** and the **Redux** pattern to drive the user interface with data and user interactions.

Editorial content is managed with a collaborative spreadsheet which becomes a datasource of the React application.
