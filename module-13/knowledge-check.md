# Knowledge check module 13

## Question 1

**Question: Quelles sont les caractéristiques des composants d'une architecture de microservices ? (Sélectionner TROIS réponses.)**

- A. Code open source
- B. Interfaces standard
- C. Implémentation cachée
- D. Fonction spécialisée
- E. Communication HTTP(S)
- F. Indépendance par rapport aux autres composants

Réponse: C, D, F

## Question 2

**Question: Qu'est-ce qu'un conteneur ?**

- A. Un système d'exploitation qui exécute une machine virtuelle
- B. Une méthode de virtualisation du système d'exploitation
- C. Un emplacement de stockage virtuel dans le cloud
- D. Un package de code et de bibliothèque portable

Réponse: B

## Question 3

**Question: Quelle est l'utilisation la plus efficace d'Amazon Elastic Container Service (Amazon ECS) lors de la refactorisation d'une application monolithique pour utiliser une architecture de microservices ?**

- A. Créer des services fournissant chacun une fonction distincte de l'application et exécuter chaque service dans un conteneur distinct géré par Amazon ECS.
- B. Créer des services fournissant chacun une fonction distincte de l'application et exécuter chaque service dans un même conteneur géré par Amazon ECS.
- C. Transférer l'application dans une nouvelle image et l'exécuter dans un conteneur géré par Amazon ECS.
- D. Refactoriser l'application et centraliser les fonctions courantes pour créer une présence de code plus faible.

Réponse: A

## Question 4

**Question: Qu'est-ce qu'AWS Fargate ?**

- A. Un service entièrement géré pour orchestrer les clusters de conteneur
- B. Un outil pour développer un logiciel qui utilise des réseaux de portes programmables in situ (FPGA)
- C. Un service qui étend de manière transparente des services AWS à des appareils périphériques
- D. Un service qui vous permet d'exécuter des conteneurs sans avoir à gérer des serveurs ou des clusters

Réponse: D

## Question 5

**Question: Qu'est-ce qu'une architecture sans serveur dans Amazon Web Services (AWS) ?**

- A. Une architecture qui n'utilise aucun serveur sur site
- B. Une architecture qui utilise uniquement des services gérés
- C. Une architecture dans laquelle vous ne mettez pas en service et ne gérez pas d'infrastructure
- D. Une architecture qui utilise des microservices au lieu de services monolithiques

Réponse: C

## Question 6

**Question: Quels sont les avantages du calcul sans serveur dans Amazon Web Services (AWS)? (Sélectionner TROIS réponses.)**

- A. Coût total de possession inférieur
- B. Architectures logicielles moins compliquées
- C. Plus de concentration sur l'application
- D. Possibilité de créer des applications de microservices
- E. Couplage plus faible entre les composants
- F. Tolérance aux pannes automatique

Réponse: A, C, D

## Question 7

**Question: Comment pouvez-vous mettre à l'échelle des fonctions AWS Lambda afin de garantir une haute disponibilité ?**

- A. Mettre en service suffisamment d'instances de fonctions pour faire face à la charge prévue maximale
- B. Lancer des fonctions dans les groupes Auto Scaling
- C. Activer la mise à l'échelle automatique dans la fonction
- D. Ne rien faire de spécial, car les fonctions se mettent automatiquement à l'échelle

Réponse: D

## Question 8

**Question: Une organisation dans le domaine des sciences de l'environnement souhaite accorder un accès HTTPS en lecture seule à ses capteurs et bases de données à tous les utilisateurs à l'échelle mondiale. L'objectif est de permettre aux utilisateurs de créer leurs propres visualisations de données en temps réel personnalisées afin d'aider à améliorer la climatologie. Quelle solution est efficace et sure?**

- A. Créer des serveurs proxy web sur des instances Amazon EC2 dans un groupe Auto Scaling, servi par un équilibreur de charge Elastic Load Balancing.
- B. Créer des comptes utilisateur dans les systèmes de l'organisation pour autoriser l'accès.
- C. Créer une interface publique pour les capteurs et les bases de données à l'aide d'Amazon API Gateway.
- D. Créer une architecture de microservices à l'aide d'Amazon Elastic Container Service (Amazon ECS).

Réponse: C

## Question 9

**Question: Quels flux de travail sont pris en charge par AWS Step Functions? (Sélectionner TROIS réponses.)**

- A. Mettre à jour l'inventaire et lancer l'expédition lorsqu'un client achète un article sur un site de commerce électronique
- B. Envoyer des messages à plusieurs instances Amazon EC2 lorsqu'un fichier est créé ou modifié dans un compartiment Amazon S3
- C. Consolider des données de plusieurs bases de données dans des rapports unifiés
- D. Notifier un groupe d'adresses e-mail lorsque les coûts d'un compte AWS dépassent un seuil
- E. Déployer différents types d'infrastructure basés sur des variables
- F. Coordonner des analyses en plusieurs étapes et des flux de travail d'apprentissage automatique

Réponse: A, C, F

## Question 10

**Question: Parmi les solutions suivantes, laquelle est une solution sans serveur pour créer un formulaire web simple ?**

- A. Héberger des ressources statiques dans un compartiment Amazon S3, utiliser une table Amazon DynamoDB et utiliser des fonctions Amazon API Gateway et AWS Lambda pour interagir avec la base de données.
- B. Héberger des ressources de site web dans un conteneur dans un cluster Amazon ECS, utiliser une table Amazon DynamoDB et utiliser des scripts côté serveur pour interagir avec la base de données.
- C. Héberger des ressources statiques dans un compartiment Amazon S3, utiliser une base de données Amazon RDS et utiliser des fonctions Amazon API Gateway et AWS Lambda pour interagir avec la base de données.
- D. Héberger des ressources de site web dans un conteneur dans un cluster Amazon ECS, utiliser une base de données Amazon RDS et utiliser des scripts côté serveur pour interagir avec la base de données.

Réponse: A
