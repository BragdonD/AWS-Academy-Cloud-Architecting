# Knowledge check module 12

## Question 1

**Question: Quelle affirmation décrit la différence entre des architectures fortement et faiblement couplées ?**

- A. Les composants d'une architecture fortement couplée dépendent fortement les uns des autres, ce qui n'est pas le cas dans une architecture faiblement couplée.
- B. Les architectures faiblement couplées doivent utiliser des services gérés. Les architectures fortement couplées n'ont pas cette contrainte.
- C. Coupler fortement une partie d'une architecture signifie que l'ensemble de l'architecture est fortement couplée. Ce principe ne s'applique pas à une architecture faiblement couplée.
- D. Les architectures fortement couplées présentent un plus grand risque d'échec que les architectures faiblement couplées.

Réponse: A

## Question 2

**Question: Quelles formules décrivent Amazon Simple Queue Service (Amazon SQS) ? (Sélectionner TROIS réponses.)**

- A. Envoie des notifications push aux consommateurs
- B. Stocke et chiffre des messages jusqu'à ce qu'ils soient traités et supprimés
- C. Prend en charge les e-mails et la messagerie texte
- D. Vous permet de découpler et de mettre à l'échelle les microservices, les systèmes distribués et les applications serverless
- E. Utilise un mécanisme d'extraction (pull)
- F. Prend en charge les files d'attente standard et les files d'attente dernier entré, premier sorti (LIFO)

Réponse: B, D, E

## Question 3

**Question: Quels scénarios indiquent que vous devriez utiliser une file d'attente Amazon Simple Queue Service (Amazon SQS) standard? (Sélectionnez DEUX réponses.)**

- A. Un message peut devoir être livré plusieurs fois.
- B. La hiérarchisation des messages est nécessaire.
- C. Les messages doivent être traités dans l'ordre dans lequel ils sont envoyés.
- D. Un message doit être traité une fois seulement.
- E. Les messages peuvent être envoyés dans n'importe quel ordre.

Réponse: A, E

## Question 4

**Question: Une flotte d'instances Amazon Elastic Compute Cloud (Amazon EC2) traite les vidéos chargées par les utilisateurs. Quelle fonction Amazon Simple Queue Service (Amazon SQS) peut-il remplir dans cette application ?

- A. Une file d'attente SQS reçoit les messages de l'application et informe toutes les instances EC2 disponibles de la disponibilité des vidéos.
- B. L'application place les messages de travail dans une file d'attente SQS.
- C. Les instances EC2 disposant d'une capacité de traitement extraient (pull) le message de tâche suivant de la file d'attente.
- D. L'application écrit les fichiers vidéo dans une file d'attente SQS. Les instances EC2 disposant d'une capacité de traitement extraient (pull) la vidéo suivante de la file d'attente.
- E. Les instances EC2 placent les fichiers vidéo édités dans une file d'attente SQS. L'application extrait les vidéos de la file d'attente.

Réponse: B

## Question 5

**Question: Qu'est-ce qu'Amazon Simple Notification Service (Amazon SNS) ?**

- A. Un service de messagerie électronique rentable, flexible et pouvant être mis à l'échelle qui permet aux développeurs d'envoyer des e-mails à partir de n'importe quelle application.
- B. Un bus d'événements serverless qui permet une connexion aisée des applications en utilisant les données de vos propres applications, des applications SaaS (logiciel en tant que service) intégrées et des services AWS.
- C. Un service de messagerie entièrement géré pour les communications de système à système et d'application à personne (A2P), qui utilise les modèles de publication/abonnement (pub/sub).
- D. Un service flexible et pouvant être mis à l'échelle de communication marketing entrante et sortante, qui utilise les canaux de communication par e-mail, SMS, push ou voix.

Réponse: C

## Question 6

**Question: Quels sont les principaux cas d'utilisation pour Amazon Simple Notification Service (Amazon SNS) ? (Sélectionner TROIS réponses.)**

- A. Rassembler des données de streaming de plusieurs systèmes
- B. Notifier plusieurs systèmes que la saisie de l'utilisateur est prête à être traitée
- C. Déclencher une seule fonction AWS Lambda lorsqu'un objet est créé dans un compartiment Amazon Simple Storage Service (Amazon S3)
- D. Suspendre la saisie jusqu'à ce qu'elle puisse être traitée dans l'ordre de réception
- E. Envoyer une notification push à des applications mobiles lorsqu'une nouvelle mise à jour logicielle est disponible
- F. Envoyer un message texte aux opérateurs système lorsqu'une activité inhabituelle est détectée

Réponse: B, E, F

## Question 7

**Question: Quelles sont les principales fonctionnalités d'Amazon Simple Notification Service (Amazon SNS) ? (Sélectionner TROIS réponses.)**

- A. La transmission de messages à une file d'attente Amazon Simple Queue Service (Amazon SQS)
- B. Le rappel des messages envoyés
- C. La transmission garantie des messages
- D. La transmission des messages à une URL
- E. La prise en charge du chiffrement
- F. Le tri automatique des messages en fonction de l'heure

Réponse: A, D, E

## Question 8

**Question: Qu'est-ce qu'Amazon MQ?**

- A. Service de file d'attente géré
- B. Service d'agent de messages
- C. Service de fournisseur d'identité
- D. Service de requête de messages

Réponse: B

## Question 9

**Question: Parmi les cas d'utilisation suivants, lequel correspond à Amazon MQ?**

- A. Connexion d'un cloud privé virtuel (VPC) à un réseau sur site
- B. Découplage de composants dans une nouvelle application native cloud
- C. Chargement d'un site web statique autonome dans Amazon Web Services
- D. Migration d'une application sur site existante qui utilise Apache ActiveMQ pour communiquer entre les microservices

Réponse: D

## Question 10

**Question: Deux fonctions AWS Lambda doivent traiter simultanément des fichiers PDF lorsqu'ils sont chargés dans un compartiment Amazon Simple Storage Service (Amazon S3). La notification d'événement S3 autorise une seule action quand les fichiers PDF sont chargés. Quelle solution fournit le moyen le plus simple et le plus efficace de déclencher les deux fonctions Lambda ?**

- A. Envoyer l'événement S3 vers Amazon MQ afin qu'il soit distribué aux deux fonctions Lambda.
- B. Envoyer l'événement S3 vers une file d'attente Amazon Simple Queue Service (Amazon SQS) interrogée par les deux fonctions Lambda.
- c. Envoyer l'événement S3 vers une rubrique Amazon Simple Notification Service (Amazon SNS) à laquelle les deux fonctions Lambda sont abonnées.
- D. Charger deux copies de chaque fichier PDF en utilisant des préfixes de clé d'objet différents.

Réponse: C
