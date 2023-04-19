---
title: La carte des animaux
publishDate: 2019-12-01 00:00:00
img: /assets/cartedespets.png
img_alt: A bright pink sheet of paper used to wrap flowers curves in front of rich blue background
description: |
  Site d'adoption et de perte d'animaux
tags:
  - Developement fullstack
  - PHP
  - Symfony
---

#### Présentation

Projet annuel de 4ème année de licence, réalisé en groupe

URL : https://lacartedesanimaux.online

#### Fonctionnalités

- Création d'annonces pour adoption ou de signalement de pertes d'animaux
- Création d'évènement associatif
- Recherche d'annonces en ligne via carte et/ou filtre de recherche

#### Technos

##### Back-end

- Langage : PHP
- Framework : Symfony
- Contenairisation : Docker
- Base de données : MYSQL , Doctrine (ORM)

##### Front-end

- Template : Twig
- CSS : Sass

#### Setup

En local :

- Initialiser les images docker : docker-compose build --no-cache
- Lancer les containers docker : docker-compose up -d
