# Knowledge check module 14

## Question 1

**Question: Que sont les objectifs de temps de récupération (RTO) et de point de récupération (RPO)?**

- A. Le RPO représente la perte de données acceptable maximale, mesurée en octets. Le RTO représente le délai moyen nécessaire pour récupérer.
- B. Le RPO représente la perte de données acceptable maximale, mesurée en temps. Le RTO représente le délai moyen nécessaire pour récupérer.
- C. Le RPO représente la perte de données acceptable maximale, mesurée en octets. Le RTO représente la perte de données acceptable maximale, mesurée dans le temps.
- D. Le RPO représente le délai de récupération cible. Le RTO représente le délai moyen nécessaire pour récupérer.

Réponse: B

## Question 2

**Question: Que pouvez-vous faire pour répliquer ou redéployer rapidement des environnements en cas de sinistre ?**

- A. Utiliser AWS CodeBuild pour déployer des conteneurs d'applications dans un nouveau VPC.
- B. Utiliser AWS OpsWorks pour reconstruire des instances Amazon Relational Database Service (Amazon RDS).
- C. Utiliser des modèles AWS CloudFormation pour déployer des environnements dupliqués dans la même région.
- D. Utiliser AWS Elastic Beanstalk pour déployer un nouveau VPC et des sous-réseaux dans une autre région.

Réponse: C

## Question 3

**Question: Une entreprise stocke des données dans un compartiment Amazon Simple Storage Service (Amazon S3). Quelle solution offre le moyen le plus efficace de garantir que tous les objets et toutes les métadonnées, qu'ils soient nouveaux ou existants, sont copiés dans une autre région pour la reprise après sinistre ?**

- A. Activer la réplication entre régions sur le compartiment et copier des objets existants dans ce compartiment.
- B. Utiliser une fonction AWS Lambda pour copier des objets, afin que tous les événements de création d'objets déclenchent la fonction.
- C. Créer un flux de travail avec AWS Step Functions et AWS Lambda pour synchroniser les compartiments.
- D. Copier les objets existants dans le compartiment cible et configurer les clients afin qu'ils écrivent les nouveaux fichiers dans les compartiments.

Réponse: A

## Question 4

**Question: Quelle stratégie est la plus efficace pour la reprise après sinistre Amazon Elastic Compute Cloud (Amazon EC2) ?**

- A. Sauvegarder les instances régulièrement.
- B. Stocker les données essentielles en dehors de l'instance et développer des processus de reconstruction rapide pour les instances de calcul.
- C. Synchroniser les instances avec des instances de secours sur une base quasi continue.
- D. Reconstruire les instances à l'aide d'images Amazon Machine Image (AMI) à partir d'AWS Marketplace

Réponse: B

## Question 5

**Question: Quel service offre un basculement automatique entre plusieurs points de terminaison afin de prendre en charge une stratégie de reprise après sinistre géographique ?**

- A. Amazon Virtual Private Cloud (Amazon VPC)
- B. AWS Direct Connect
- C. Elastic Load Balancing
- D. Amazon Route 53

Réponse: D

## Question 6

**Question: Parmi les affirmations suivantes à propos du modèle de sauvegarde et de reprise après sinistre, laquelle est vraie ?**

- A. C'est le modèle le plus rentable, mais avec le RTO le plus élevé
- B. C'est le modèle le plus rentable, mais avec le RPO le plus élevé
- C. C'est le modèle avec le RTO le plus faible, mais c'est le moins efficace
- D. C'est le modèle avec le RPO le plus faible, mais c'est le moins efficace

Réponse: A

## Question 7

**Question: Quelle est la différence entre les modèles de reprise après sinistre de type <<< veille >> et de type << secours à chaud » ? (Sélectionner DEUX réponses.)**

- A. Le modèle de reprise après sinistre de type « veille >> utilise une version réduite de toute infrastructure qui s'exécute jusqu'à ce qu'un sinistre se produise.
- B. Le modèle de reprise après sinistre de type <<< secours à chaud >> utilise une version réduite de toute infrastructure qui s'exécute jusqu'à ce qu'un sinistre se produise.
- C. Le modèle de reprise après sinistre de type << secours à chaud >> dispose d'un ensemble d'infrastructure entièrement fonctionnel qui s'exécute tout le temps.
- D. Le modèle de reprise après sinistre de type << veille >> dispose d'une infrastructure minimale qui s'exécute en permanence. Le reste ne s'exécute pas jusqu'à ce qu'un sinistre se produise.
- E. Avec le modèle de reprise après sinistre de type << secours à chaud », toute infrastructure s'exécute en mode veille et est réveillée lorsqu'un sinistre se produit.

Réponse: B, D

## Question 8

**Question: Qu'implique le modèle de reprise après sinistre multisite ?**

- A. Un basculement automatique vers un second système entièrement opérationnel situé sur un autre site.
- B. La charge est distribuée sur plusieurs sites géographiquement éloignés afin de limiter l'impact des sinistres.
- C. Les sauvegardes sont stockées dans différents sites afin d'être protégées en cas de sinistre.
- D. Le basculement vers un autre site qui ne s'exécute que lorsque cela s'avère nécessaire.

Réponse: A

## Question 9

**Question: Une entreprise a besoin d'une solution de reprise après sinistre pour une application critique fournissant un objectif de temps de récupération (RTO) et un objectif de point de récupération (RPO) de l'ordre de quelques minutes. Cependant, elle ne souhaite pas payer plus cher que nécessaire pour couvrir ses besoins. Quel modèle de reprise après sinistre répondrait le plus probablement à ces exigences ?**

- A. Sauvegarde et restauration
- B. Veille
- C. Secours à chaud
- D. Multisite

Réponse: 

## Question 10

**Question: Que vous permet de faire AWS Storage Gateway? (Sélectionner TROIS réponses.)**

- A. Utiliser SMB (Server Message Block) ou NFS (Network File System) pour vous connecter à Amazon Simple Storage Service (Amazon S3)
- B. Accorder aux applications situées dans un VPC l'accès aux volumes de stockage par bloc sur site
- C. Transférer des tâches de sauvegarde de systèmes de bande ou de systèmes VTL (bibliothèque de bandes virtuelles) dans le cloud
- D. Se connecter à Amazon Simple Storage Service (Amazon S3) au moyen d'une interface de programmation d'application (API)
- E. Présenter des volumes de stockage par bloc iSCSI (Internet Small Computer Systems Interface) basés sur le cloud à des applications sur site

Réponse: A, C, E
