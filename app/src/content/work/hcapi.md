---
title: Haute Couture API
publishDate: 2020-03-02 00:00:00
img: /assets/hcapi.png
img_alt: Iridescent ripples of a bright blue and pink liquid
description: |
  Une API donnant différentes informations sur les maisons qui possédant le label haute couture
tags:
  - Développement back end
  - NodeJS / Express
  - Vercel
---

### Présentation

Cette api est publié sur RapidAPI à l'adresse suivante : https://rapidapi.com/christmknd/api/hautecouture-api1

La source principale des informations de cette API vienne de la Fédération de la Haute Couture et de la Mode.

Les maisons sont classés en trois catégories :

les membres permanents
les membres correspondants
les membres invités
Pour rappel , les maisons qui possèdent l'appellation haute couture (appellation juridiquement controlé), sont des maisons de luxe qui correspondent aux critères suivants :

- Vêtements réalisés sur mesure
- Travail à la main
- Avoir un atelier de maison de couture, avec un atelier flou et un atelier tailleur
- Les ateliers doivent compter une dizaine de personnes
- Défiler deux fois par an , avec minimu 25 modèles par collection

Pour être accepté dans la liste des membres permanents, elle doit être déja inscrit en tant qu'invité depuis 4 ans et être parainée par une autre maison de couture.

Le statut haute couture n'existe qu'à Paris, valable qu'un an , et est accordé chaque par le ministère en charge de l'Industrie , sur proposition d'une liste de la Chambre Syndicale de la Haute Couture.

### Usages

##### Lancement du projet

Pour lancer le projet en local , tapez la commande suivante : npm start
Aller sur votre navigateur et tapez http://localhost:5000/

Vous pouvez aussi tester toutes ces requêtes directement sur le site en production : https://haute-couture-api.vercel.app/

#### Requêtes

Voici la liste exhaustif des requêtes que vous pouvez effectuez avec cette API :

- Récupérer la liste toutes les maisons
  get /api/maisons

- Récupérer tous les maison dans une catégorie spécifique
  get /api/maisons/category/{category}

- Récuperer la liste des maisons par pays
  get /api/maisons/country/{country}

- Récupérer une maison aléatoirement
  get /api/maisons/random

- Récupérer le nom d'une maison par son ID
  get /api/maisons/{id}

- Récupérer la liste tous les directeurs artistiques (DA)
  get /api/directors

- Récupérer le nom d'un directeur artistique (DA) aléatoirement
  get /api/directors/random

- Récuperer la liste des directeurs artistiques d'une catégorie précise
  get /api/directors/category/:{category}

- Recupérer la liste des directeurs artistiques par pays
  get /api/directors/country/{country}

- Récupérer toutes les catégories de maisons
  get /api/categories

#### Environnement technique

- Langage : Javascript
- Serveur : Node JS , Express
- Versionning : Github
- Déploiement : Vercel
- Lien Github : https://github.com/christmknd/HauteCouture-API
- Lien en production : https://haute-couture-api.vercel.app/
