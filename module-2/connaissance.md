# Module 2 knowledge test 

## Question 1

**Question: Quelle est la meilleure définition de l'architecture cloud ?**

A. Association de logiciels et de composants frontaux et dorsaux (front-end, back-end) pour créer des services web hautement disponibles et évolutifs qui répondent aux besoins d'une organisation
B. Application de caractéristiques cloud à une solution qui utilise des fonctions et des services cloud pour répondre à des besoins techniques et commerciaux
C. Conception d'applications dans une infrastructure informatique basée sur le cloud à l'aide de machines virtuelles et de magasins de données tolérants aux pannes dans le cloud
D. Déplacement de centres de données sur site traditionnels vers des centres de données accessibles sur Internet gérés par un fournisseur

Réponse: B

## Question 2

**Question: Le cadre AWS Well-Architected comporte cinq piliers. La sécurité et l'excellence opérationnelle sont deux des piliers. Quels sont les autres piliers du cadre Well-Architected? (Sélectionner TROIS réponses.)**

A. Fiabilité
B. Gouvernance
C. Confidentialité
D. Efficacité des performances
E. Gestion du risque
F. Optimisation des coûts

Réponse: A, D, F

## Question 3

**Question: Quelles actions sont en cohérence avec le pilier Excellence opérationnelle du cadre AWS Well-Architected? (Sélectionner DEUX réponses.)**

A. Appliquer les principes et la méthodologie de l'ingénierie logicielle à l'laC (Infrastructure as code).
B. Examiner et améliorer les processus et les procédures en continu.
C. Vérifier les modifications des documents du personnel des opérations dans l'infrastructure.
D. Planifier et gérer l'intégralité du cycle de vie des ressources matérielles.
E. Évaluer les structures et les rôles organisationnels pour identifier les lacunes de compétences.

Réponse: A, B

## Question 4

**Question: Une application nécessite un niveau Web frontal (front-end) de plusieurs serveurs qui communiquent avec un niveau Application dorsal (back-end) de plusieurs serveurs. Quelle conception applique le plus fidèlement les bonnes pratiques Amazon Web Services (AWS)?**

A. Affecter un serveur d'application dédié et une connexion dédiée à chaque serveur web.
B. Créer plusieurs instances combinant chacune un front-end web et un back-end d'applications dans la même instance.
C. Concevoir le niveau web pour communiquer avec le niveau d'applications via le service Elastic Load Balancing.
D. Créer un réseau maillé complet entre les niveaux Web et Application, afin que chaque serveur web puisse communiquer directement avec chaque serveur d'applications.

Réponse: C

## Question 5

**Question: Un architecte de solutions développe un processus pour gérer les défaillances rencontrées par le serveur. Quel processus applique le plus fidèlement les bonnes pratiques Amazon Web Services (AWS)?**

A. Le service des opérations détecte une défaillance du système. Le service informe l'administrateur systèmes qui met en service un nouveau serveur à l'aide d'AWS Management Console.
B. Amazon CloudWatch détecte une défaillance du système. Le service informe l'administrateur systèmes qui met en service un nouveau serveur à l'aide d'AWS Management Console.
C. Le service des opérations détecte une défaillance du système. Le service déclenche l'automatisation afin de mettre en service un nouveau serveur.
D. Amazon CloudWatch détecte une défaillance du système. Le service déclenche l'automatisation afin de mettre en service un nouveau serveur.

Réponse: D

## Question 6

**Question: Une entreprise souhaite modifier certaines fonctionnalités de son site web. Elle ne sait pas ce qui se produira si les modifications sont effectuées. Quelle approche applique le plus fidèlement les bonnes pratiques Amazon Web Services (AWS)?**

A. Modifier le site de production pendant qu'il est en ligne. Utiliser des sauvegardes pour annuler les modifications.
B. Modifier le site de production pendant les heures de maintenance hors ligne. Utiliser des sauvegardes pour annuler les modifications.
C. Mettre en service un nouveau serveur et y apporter les modifications. Utiliser DNS pour procéder à la migration progressive des utilisateurs vers le nouveau serveur. Arrêter le serveur d'origine une fois que tous les utilisateurs ont migré.
D. Tester les modifications sur un serveur de développement existant. Modifier le site de production pendant les heures de maintenance hors ligne. Utiliser des sauvegardes pour annuler les modifications.

Réponse: C

## Question 7

**Question: Une entreprise stocke des données en lecture seule dans Amazon Simple Storage Service (Amazon S3). La plupart des utilisateurs se trouvent dans le même pays que le siège social d'entreprise. Certains utilisateurs sont basés ailleurs dans le monde. Quelle décision de conception applique le plus fidèlement les bonnes pratiques Amazon Web Services (AWS)?**

A. Utiliser un compartiment dans la région AWS la plus proche du siège social de l'entreprise.
B. Utiliser un compartiment dans la région AWS dont la latence moyenne est la plus faible pour tous les utilisateurs.
C. Répliquer des objets sur des compartiments dans d'autres régions AWS. Les utilisateurs accèdent au compartiment dans la région AWS la plus proche d'eux.
D. Utiliser un compartiment dans la région AWS la plus proche du siège social de l'entreprise. Tous les utilisateurs accèdent aux données via Amazon CloudFront.

Réponse: D

## Question 8

**Question: Un consultant doit accéder à un objet volumineux dans un compartiment S3. Il lui faut une journée pour accéder au fichier. Quelle méthode d'attribution d'accès applique le plus fidèlement les bonnes pratiques Amazon Web Services (AWS)?**

A. Créer une URL présignée pour l'objet qui expire sous un délai de 24 heures et la donner au consultant.
B. Activer l'accès public au compartiment S3. Donner l'URL de l'objet au consultant.
C. Copier l'objet dans un nouveau compartiment S3. Activer l'accès public au nouveau compartiment. Dans le nouveau compartiment, obtenir l'URL de l'objet et la donner au consultant.
D. Créer un compte utilisateur pour le consultant. Accorder au compte utilisateur les autorisations d'accéder au compartiment S3 via AWS Management Console.

Réponse: A

## Question 9

**Question: Quelles sont les principales considérations qui influencent le choix de la région AWS à utiliser ? (Sélectionner DEUX réponses.)**

A. Contrôle de la sécurité et des accès
B. Réduction de la latence pour les utilisateurs finaux
C. Protection contre les catastrophes naturelles localisées
D. Résilience des applications pendant les défaillances du système
E. Conformité aux lois et aux réglementations

Réponse: B, E

## Question 10

**Question: Quelles sont les principales considérations qui influencent le choix des zones de disponibilité à utiliser ? (Sélectionner DEUX réponses.)**

A. Contrôle de la sécurité et des accès
B. Réduction de la latence pour les utilisateurs finaux
C. Protection contre les catastrophes naturelles localisées
D. Résilience des applications pendant les défaillances du système
E. Conformité aux lois et aux réglementations

Réponse: C, D
