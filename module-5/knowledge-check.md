# Knowledge check module 5

## Question 1

**Question: Quels cas d'utilisation indiquent qu'une base de données non relationnelle peut s'avérer mieux adaptée qu'une base de données relationnelle? (Sélectionnez DEUX réponses.)**

- A. Mise à l'échelle horizontale pour un volume de données massif
- B. Conformité ACID pour toutes les transactions de base de données
- C. Données avec attributs imprévisibles
- D. Forte cohérence de lecture après écriture
- E. Haute disponibilité et tolérance aux pannes

Réponse: A, C

## Question 2

**Question: Quelle affirmation comparant un service de base de données géré par Amazon Web Services (AWS) à une base de données sur une instance Amazon Elastic Compute Cloud (Amazon EC2) est correcte ?**

- A. Vous n'avez pas besoin de configurer les sauvegardes pour une base de données sur un service de base de données géré.
- B. AWS gère les correctifs de base de données pour une base de données sur un service de base de données géré.
- C. AWS gère les correctifs du système d'exploitation pour une base de données sur une instance EC2.
- D. Vous n'avez pas besoin de configurer les sauvegardes pour une base de données sur une instance EC2.

Réponse: B

## Question 3

**Question: Quels exemples représentent des cas d'utilisation appropriés pour Amazon Relational Database Service (Amazon RDS) ? (Sélectionner TROIS réponses.)**

- A. Des milliers d'écritures simultanées distribuées par seconde
- B. Une application qui nécessite que la base de données applique des règles de syntaxe
- C. Une application qui nécessite des jointures complexes de données
- D. Un entrepôt de données d'une capacité de l'ordre du pétaoctet
- E. L'exécution d'un serveur Microsoft SQL Server dans Amazon Web Services (AWS)
- F. Des bases de données pour les architectures serverless

Réponse: B, C, E

## Question 4

**Question: Une petite entreprise doit choisir quel service utiliser pour le système d'inscription de son site web de formation en ligne. Les choix possibles sont MySQL sur Amazon Elastic Compute Cloud (Amazon EC2), MySQL sur Amazon Relational Database Service (Amazon RDS) et Amazon DynamoDB. Quelle association de cas d'utilisation suggère d'utiliser Amazon RDS? (Sélectionner TROIS réponses.)**

- A. Les données et les transactions doivent être chiffrées pour protéger les informations personnelles.
- B. Les données sont très structurées.
- C. Les données des élèves, des cours et des inscriptions sont stockées dans un grand nombre de tables différentes.
- D. Le système d'inscription doit être hautement disponible.
- E. L'entreprise ne souhaite pas gérer les correctifs de la base de données.

Réponse: B, C, E

## Question 5

**Question: Quels scénarios constituent des cas d'utilisation appropriés pour Amazon DynamoDB ? (Sélectionner TROIS réponses.)**

- A. Des bases de données pour les architectures serverless
- B. Des applications nécessitant des transactions ACID
- C. Des applications associant des données d'un grand nombre de tables
- D. Une base de données orientée graphe pour suivre les relations entre les entités
- E. Une base de données de documents pour des documents basés sur JSON (JavaScript Object Notation)
- F. Un stockage d'objets BLOB (objets binaires volumineux)

Réponse: A, B, E

## Question 6

**Question: Une petite entreprise de jeux vidéo conçoit un jeu en ligne, dans lequel des milliers de joueurs peuvent créer leurs propres objets de jeu. La conception actuelle utilise une base de données MySQL dans Amazon Relational Database Service (Amazon RDS) pour stocker les données des objets créés par les joueurs. Quels cas d'utilisation suggèrent que DynamoDB pourrait être mieux adapté ? (Sélectionnez DEUX réponses.)**

- A. Un ensemble d'attributs communs à tous les objets créés par les joueurs
- B. Des attributs imprévisibles pour les objets créés par les joueurs
- C. Un grand nombre d'objets créés par les utilisateurs, comportant chacun des attributs différents
- D. La recherche et la récupération rapides des objets créés par les joueurs
- E. Une quantité élevée d'activités de lecture sur les objets créés par les joueurs

Réponse: B, C

## Question 7

**Question: Quelles techniques devez-vous utiliser pour sécuriser une base de données Amazon Relational Database Service (Amazon RDS) ? (Sélectionner TROIS réponses.)**

- A. Des politiques de Gestion des identités et des accès AWS (AWS IAM) pour définir l'accès au niveau des tables, des lignes et des colonnes
- B. Des groupes de sécurité pour contrôler l'accès réseau aux instances individuelles
- C. Un point de terminaison de passerelle Amazon Virtual Private Cloud (Amazon VPC) pour empêcher le trafic de passer par Internet
- D. Une passerelle de réseau privé virtuel (VGW) pour filtrer le trafic des réseaux limités
- E. Un cloud privé virtuel (VPC) pour fournir l'isolation des instances et la protection par pare-feu
- F. Un chiffrement pour protéger les données sensibles

Réponse: B, E, F

## Question 8

**Question: Quelles techniques devez-vous utiliser pour sécuriser Amazon DynamoDB ? (Sélectionner TROIS réponses.)**

- A. Un cloud privé virtuel (VPC) pour fournir l'isolation des instances et la protection par pare-feu
- B. Un chiffrement pour protéger les données sensibles
- C. Une passerelle de réseau privé virtuel (VGW) pour filtrer le trafic des réseaux limités
- D. Des groupes de sécurité pour contrôler l'accès réseau aux instances individuelles
- E. Des politiques de Gestion des identités et des accès AWS (AWS IAM) pour définir l'accès au niveau des tables, des éléments ou des attributs
- F. Un point de terminaison de passerelle Amazon Virtual Private Cloud (Amazon VPC) pour empêcher le trafic de passer par Internet

Réponse: B, E, F

## Question 9

**Question: Une entreprise souhaite procéder à la migration de sa base de données Oracle sur site vers Amazon Aurora MySQL. Quel processus décrit les étapes de haut niveau ?**

- A. Utiliser AWS Database Migration Service (AWS DMS) pour la migration de la base de données Oracle vers Amazon Aurora MySQL.
- B. Utiliser AWS Database Migration Service (AWS DMS) pour la migration des données, puis utiliser l'outil de conversion des schémas AWS pour convertir le schéma.
- C. Utiliser l'outil de conversion des schémas AWS pour convertir le schéma, puis utiliser AWS Database Migration Service (AWS DMS) pour migrer les données.
- D. Utiliser l'outil de conversion des schémas AWS pour convertir de manière synchrone le schéma et migrer les données.

Réponse: C

## Question 10

**Question: Vous devez effectuer une migration hétérogène de votre installation sur site vers une base de données située dans un cloud privé virtuel (VPC). Vous allez utiliser AWS Snowball Edge et AWS Database Migration Service (AWS DMS). À quel moment utilisez-vous l'outil de conversion des schémas AWS (AWS SCT) ?**

- A. Au début, pour extraire des données de la base de données source vers Snowball Edge, avant d'expédier l'appareil
- B. Après avoir extrait les données de la base de données source à l'aide d'AWS DMS, mais avant d'expédier l'appareil Snowball Edge
- C. Une fois que les données se trouvent dans le VPC, mais avant d'utiliser AWS DMS pour charger les données dans la base de données cible
- D. Après avoir utilisé AWS DMS pour charger les données dans la base de données cible située dans le VPC

Réponse: A
