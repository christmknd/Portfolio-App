---
title: POC Rabbit MQ
publishDate: 2020-03-02 00:00:00
img: /assets/rabbitmq.png
img_alt: Projet réalisé pendant mon alternance au sein de Swisslife.
description: |
  Projet réalisé pendant mon alternance au sein de Swisslife.
tags:
  - Développement web back end
  - Projet professionnel
  - NodeJS
  - RabbitMQ
---

#### Problématique

Le but de ce projet était de faire communiquer entre elles deux applications internes de Swisslife, afin qu'elles puissent s'envoyer des informations. Pour se faire, j'ai choisi d'utiliser des messages brokers.

Après avoir fait un benchmark des messages brokers, les plus pertinents m'ont apparu être Kafka et RabbitMQ

Les principaux critères pour determiner mon choix ont été :

la facilité d'installation et d'utilisation
le fait que l'outil soit cross-plateforme (utilisables sur différents OS)
le fait que l'on puisse implémenter les cas d'usages en différents langages ( c'est ce facteur qui a fait la différence)
Mon choix s'est porté sur RabbitMQ, car il est possible d'implémenter des cas d'usages en utilisant de multiples langages contrairement a Kafka ( Java seulement)

Ce projet est donc un POC (Proof of Concept). Je l'ai développé avec Javascript et NodeJS car c'est le langage avec lequel je suis le plus à l'aise

### Usage

- npm install amqplib
- Direct exchange : node consumer.js
- Fanout exchange : node cons1.js & node cons2.js

#### Scenarios

- Direct Exchange : 1 producteur / 1 consommateur
- Fanout Exchange : 1 producteur / 2 consommateur
- Scenario 3 : 2 producteur / 2 consommateur / 1 channel de communication
- Scenario 4 : 2 producteur / 2 consommateur / 2 channel de communication

#### Technos

- Langage : Javascript
- Serveur : NodeJS
- Lien Github : https://github.com/christmknd/RabbitMQ
