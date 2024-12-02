# Knowledge check module 11

## Question 1

**Question: Qu'est-ce que la mise en cache?**

- A. Une couche de stockage de données haut débit
- B. Un moyen de stocker des mots de passe
- C. Un réseau mondial pour la diffusion de contenu
- D. Une base de données en mémoire

Réponse: A

## Question 2

**Question: Quels types de données devez-vous mettre en cache ?**

- A. Les données qui peuvent être récupérées rapidement grâce à des requêtes simples
- B. Le contenu web généré dynamiquement
- C. Les données statiques fréquemment consultées
- D. Les données spécialisées nécessaires à un sous-ensemble d'utilisateurs

Réponse: C

## Question 3

**Question: Parmi les propositions suivantes, laquelle présente un avantage de la mise en cache ?**

- A. Réduction de la latence des réponses
- B. Répartition de la charge d'une application
- C. Plus grande fiabilité de votre application
- D. Diminution des coûts

Réponse: A

## Question 4

**Question: Que permet Amazon CloudFront ?**

- A. La mise en cache bidirectionnelle entre les utilisateurs et un hôte de l'origine
- B. La mise en cache de contenu à plusieurs niveaux et par région
- C. Le traitement transactionnel avec une base de données en mémoire
- D. La création automatique d'une valeur de durée de vie

Réponse: B

## Question 5

**Question: Comment le service Amazon CloudFront utilise-t-il les emplacements périphériques?**

- A. Il met en cache l'ensemble du contenu d'une distribution de l'origine à l'emplacement périphérique et diffuse le contenu aux clients via l'emplacement périphérique le plus rapide.
- B. Il met en cache le contenu local aux emplacements périphériques. Il diffuse le contenu mis en cache aux clients via l'emplacement périphérique qui nécessite le nombre de sauts de réseau le moins important pour atteindre ces clients.
- C. Il met en cache les données fréquemment consultées aux emplacements périphériques. Il diffuse le contenu mis en cache aux clients via l'emplacement périphérique présentant la latence la plus faible vers ces clients.
- D. Il met en cache les données régionales à des emplacements périphériques régionaux et diffuse le contenu aux clients via leurs emplacements périphériques régionaux.

Réponse: C

## Question 6

**Question: Où sont mises en cache les données des sessions des applications lors de l'utilisation de sessions permanentes ?**

- A. Serveur web
- B. Navigateur web
- C. Équilibreur de charge Elastic Load Balancing
- D. Amazon CloudFront

Réponse: A

## Question 7

**Question: Quel énoncé décrit le mieux un moyen efficace de diffuser du contenu en streaming à la demande à l'aide d'Amazon CloudFront ?**

- A. CloudFront ne traite pas le contenu en streaming.
- B. Une bonne pratique consiste à créer des serveurs d'origine séparés pour chaque région où vous diffusez du contenu en streaming.
- C. Une bonne pratique consiste à créer des distributions pour chaque région où vous diffusez du contenu en streaming.
- D. Une bonne pratique consiste à créer des segments vidéo et à les stocker dans un compartiment Amazon Simple Storage Service (Amazon S3). Utilisez ensuite CloudFront pour mettre en cache les segments.

Réponse: D

## Question 8

**Question: Qu'est-ce qu'Amazon DynamoDB Accelerator (DAX) ?**

- A. Un cache en mémoire entièrement géré et hautement disponible pour DynamoDB
- B. Une fonction de DynamoDB qui ajuste automatiquement la capacité en lecture/écriture pour traiter la charge
- C. Un cache entièrement géré et hautement disponible reposant sur DynamoDB
- D. Une fonction de DynamoDB qui permet d'effectuer une recherche rapide des éléments à l'aide de clés secondaires

Réponse: A

## Question 9

**Question: Comment une application peut-elle utiliser Amazon ElastiCache pour améliorer la performance de lecture des bases de données ? (Sélectionner DEUX réponses.)**

- A. Commencer par lire les données de la base de données et écrire les données les plus fréquemment lues dans ElastiCache.
- B. Diriger toutes les demandes de lecture vers la base de données et configurer la lecture à partir d'ElastiCache en cas d'absence de cache.
- C. Commencer par lire les données à partir d'ElastiCache et écrire dans ElastiCache en cas d'absence de cache.
- D. Écrire les données dans ElastiCache dès que l'application écrit dans la base de données.
- E. Répliquer la base de données dans ElastiCache et diriger toutes les lectures vers ElastiCache et toutes les écritures vers la base de données.

Réponse: C, D

## Question 10

**Question: Quel rôle Amazon CloudFront joue-t-il dans la protection contre les attaques par déni de service (DDoS)?**

- A. Le service achemine le trafic via des emplacements périphériques
- B. Le service contrôle le trafic en fonction des adresses IP source des demandes
- C. Le service limite le trafic en fonction de la zone géographique afin de contribuer au blocage des attaques provenant de certains pays
- D. Le service procède à une inspection approfondie des paquets afin de détecter les attaques

Réponse: A
