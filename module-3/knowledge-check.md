# Knowledge check module 3

## Question 1

**Question: Pour quel cas d'utilisation le service Amazon Simple Storage Service (Amazon S3) offre-t-il une solution adaptée ?**

- A. Un entrepôt de données de business intelligence
- B. Un emplacement de stockage accessible par Internet pour les fichiers vidéo auxquels accède un site web externe
- C. Un stockage horaire de fichiers temporaires fréquemment consultés
- D. Un cluster d'installations Apache Spark et Apache Hadoop traditionnelles pour le traitement du Big Data

Réponse: B

## Question 2

**Question: Une entreprise souhaite utiliser Amazon Simple Storage Service (Amazon S3) seul pour héberger son site web, plutôt que d'utiliser un serveur web traditionnel. Quels types de contenu Amazon S3 prend-il en charge pour l'hébergement web statique ? (Sélectionner TROIS réponses.)**

- A. Fichiers HTML et fichiers image
- B. Scripts côté client
- C. Scripts côté serveur
- D. Fichiers HTML dynamiques
- E. Fichiers vidéo et audio

Réponse: A, B, E

## Question 3

**Question: Quels scénarios représentent un cas d'utilisation approprié d'Amazon Simple Storage Service (Amazon S3) ? (Sélectionnez DEUX réponses.)**

- A. Hébergement du volume racine d'un système d'exploitation réel
- B. Fourniture d'un système de fichiers montable pour les charges de travail Linux
- C. Sauvegarde de données critiques
- D. Exposition d'une bibliothèque de bandes virtuelles à des systèmes de sauvegarde sur site
- E. Stockage de données de calcul et d'analytique

Réponse: C, E

## Question 4

**Question: Une entreprise souhaite utiliser un compartiment S3 pour stocker des données sensibles. Quelles actions peut-elle entreprendre pour protéger ses données ? (Sélectionnez DEUX réponses.)**

- A. Téléchargement de fichiers non chiffrés dans Amazon S3, car Amazon S3 chiffre les fichiers par défaut
- B. Activation du chiffrement côté serveur sur le compartiment S3 avant de charger des données sensibles
- C. Activation du chiffrement côté serveur sur le compartiment S3 après avoir chargé des données sensibles
- D. Utilisation du chiffrement côté client pour protéger les données en transit
- E. Utilisation du protocole sécurisé de transfert de fichiers (SFTP) pour se connecter directement à Amazon S3

Réponse: B, D

## Question 5

**Question: Une entreprise doit créer un emplacement commun pour stocker des fichiers partagés. Quelles exigences le service Amazon Simple Storage Service (Amazon S3) prend-il en charge ? (Sélectionnez DEUX réponses.)**

- A. Récupérer les fichiers supprimés
- B. Conserver différentes versions des fichiers
- C. Verrouiller un fichier afin qu'une seule personne puisse le modifier à la fois
- D. Joindre des commentaires aux fichiers
- E. Comparer le contenu de plusieurs fichiers

Réponse: A, B

## Question 6

**Question: L'équipe d'un service clientèle accède à des données de demandes tous les jours pendant une période allant jusqu'à 30 jours. Les demandes peuvent être rouvertes et doivent être immédiatement accessibles pendant 1 an après leur fermeture. Quelle solution répond à ces exigences de la manière la plus rentable ?**

- A. Stocker les données de toutes les demandes dans S3 Standard afin qu'elles soient disponibles en cas de besoin.
- B. Stocker les données des demandes dans S3 Standard. Utiliser une politique de cycle de vie pour déplacer les données dans S3 Standard - Accès peu fréquent après 30 jours.
- C. Stocker les données des demandes dans S3 Standard. Utiliser une politique de cycle de vie pour déplacer les données dans Amazon S3 Glacier après 30 jours.
- D. Stocker les données des demandes dans S3 Intelligent-Tiering afin de déplacer automatiquement les données d'un niveau à un autre en fonction de la fréquence d'accès.

Réponse: B

## Question 7

**Question: Quels transferts de données non accélérés Amazon Simple Storage Service (Amazon S3) ont un coût associé ? (Sélectionnez DEUX réponses.)**

- A. En entrée depuis Internet
- B. En sortie vers Internet
- C. En sortie vers d'autres régions AWS
- D. En sortie vers d'autres services AWS de la même région AWS
- E. En sortie vers Amazon CloudFront

Réponse: B, C

## Question 8

**Question: Une entreprise procède à la migration de 100 téraoctets (To) de données de son centre de données sur site vers Amazon Simple Storage Service (Amazon S3). L'entreprise se connecte à Amazon Web Services (AWS) à l'aide d'une connexion Internet de 155 mégabits par seconde (Mbit/s). Quelle option de transfert de données est la plus rapide et la plus économique ?**

- A. Console de gestion AWS
- B. Chargements partitionnés Amazon S3
- C. AWS Snowball
- D. AWS Snowmobile

Réponse: C

## Question 9

**Question: Un producteur vidéo doit régulièrement transférer plusieurs fichiers vidéo vers Amazon Simple Storage Service (Amazon S3). La taille des fichiers varie de 100 à 700 Mo. La connexion Internet s'est avérée non fiable, ce qui a entraîné l'échec de certains chargements. Quelle solution offre le moyen le plus rapide, le plus fiable et le plus économique de transférer ces fichiers vers Amazon S3 ?**

- A. AWS Snowball
- B. Console de gestion AWS
- C. Chargements partitionnés Amazon S3
- D. AWS Snowmobile

Réponse: C

## Question 10

**Question: Quelles qualités varient en fonction de la région AWS? (Sélectionnez DEUX réponses.)**

- A. Rentabilité des charges de travail
- B. Confidentialité des données
- C. Haute disponibilité des charges de travail
- D. Disponibilité des services et des fonctionnalités
- E. Capacité pour un plus grand nombre de clients

Réponse: A, D
