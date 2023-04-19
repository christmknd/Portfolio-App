---
title: Green IT
publishDate: 2020-03-04 00:00:00
img: /assets/greenit.png
img_alt: Pearls of silky soft white cotton, bubble up under vibrant lighting
description: |
  Calcul de l'indice de fragilité des villes en France
tags:
  - Developpement full stack
  - Eco-Conception
  - Performance
---

#### Présentation

Application qui permet de calculer l'indice de fragilité des villes en France

L'indice de fragilité d'une ville est calculé à partir de :

- l'accès à l'information
- l'accès aux interfaces numériques
- la capacité d'usage des interfaces numériques
- compétences administratives

#### Technos

- Langage : Javascript => langage stable, avec un temps d'execution rapide et un taux d'énergie faible.

- Backend : Express JS
- Frontend : React
  Pas de biblothèque supplémentaire coté front ( ex : Materialize ). React est une librairie avec une approche basé sur les composants , qui peuvent être facilement réutilisé dans d'autres projets. Le fait que React soit une librairie et non un framework ( comme Angular ) le rend plus simple a utiliser et surtout moins volumineux.

#### Setup du projet

- Cloner le projet en local
- Executer le scropt de bash avec la commande "./lancement-project-docker.sh"
- Se rendre sur http://localhost:3000/

#### Outils d'éco-conception

Pour étudier les différents scores de notre site concernent l'éco-conception de notre site , on peut utiliser :

- Lighthouse (extension Chrome)
- GTmetrix
- PageSpeedInsights

#### Performance

- Installer k6 ( installation différentes selon les OS)
- Executé les scripts : k6 run node-app/src/performance_testing_k6/<script_filename>
