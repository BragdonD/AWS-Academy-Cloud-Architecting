# Knowledge check module 3

## Question 1

**Question: Quels attributs sont des raisons de choisir Amazon Elastic Compute Cloud (Amazon EC2) ? (Sélectionnez DEUX réponses.)**

- A. Capacité à exécuter tout type de charge de travail
- B. Capacité à exécuter des applications serverless
- C. Gestion des correctifs du système d'exploitation par Amazon Web Services (AWS)
- D. Gestion de la sécurité du système d'exploitation par AWS
- E. Contrôle complet des ressources informatiques

Réponse: A, E

## Question 2

**Question: Quels avantages présente l'utilisation d'une image Amazon Machine Image (AMI) ? (Sélectionner TROIS réponses.)**

- A. Migration de données sur site vers des instances Amazon EC2
- B. Lancement d'instances avec une même configuration
- C. Automatisation des paramètres des groupes de sécurité pour les instances
- D. Utilisation d'une image AMI en tant que sauvegarde du serveur pour les instances Amazon Elastic Compute Cloud (Amazon EC2)
- E. Commercialisation ou partage de solutions logicielles regroupées sous la forme d'une image AMI

Réponse: B, D, E

## Question 3

**Question: Un administrateur système doit changer les types d'instances de plusieurs instances Amazon Elastic Compute Cloud (Amazon EC2) en cours d'exécution. Les instances ont été lancées avec une combinaison d'images AMI (Amazon Machine Image) basées sur Amazon Elastic Block Store (Amazon EBS) et d'images AMI basées sur le stockage d'instances. Quelle méthode constitue un moyen valide de changer le type d'instance ?**

- A. Changer le type d'instance d'une instance basée sur Amazon EBS sans l'arrêter
- B. Changer le type d'instance d'une instance basée sur le stockage d'instances sans l'arrêter
- C. Arrêter une instance basée sur Amazon EBS, changer son type d'instance et démarrer l'instance
- D. Arrêter une instance basée sur le stockage d'instances, changer son type d'instance et démarrer l'instance

Réponse: C

## Question 4

**Question: Une charge de travail nécessite un accès élevé en lecture/écriture à des jeux de données locaux volumineux. Quels types d'instances seraient les plus efficaces pour cette charge de travail ? (Sélectionnez DEUX réponses.)**

- A. À usage général
- B. Optimisée pour le calcul
- C. Optimisée pour la mémoire
- D. Calcul accéléré
- E. Optimisée pour le stockage

Réponse: C, E

## Question 5

**Question: Une application a besoin de l'adresse MAC (Media Access Control) de l'instance Amazon Elastic Compute Cloud (Amazon EC2) hôte. L'architecture utilise un groupe AWS Auto Scaling pour lancer et résilier dynamiquement les instances. Quel est le meilleur moyen pour que l'application obtienne l'adresse MAC ?**

- A. Écrire l'adresse MAC dans le fichier de configuration de l'application de chaque instance
- B. Inclure l'adresse MAC dans l'image Amazon Machine Image (AMI) utilisée pour lancer toutes les instances dans le groupe AWS Auto Scaling
- C. Inclure l'adresse MAC dans une image AMI personnalisée pour chaque instance du groupe AWS Auto Scaling
- D. Utiliser les données utilisateur de chaque instance pour accéder à l'adresse MAC via les métadonnées de l'instance

Réponse: D

## Question 6

**Question: Une charge de travail transactionnelle sur une instance Amazon Elastic Compute Cloud (Amazon EC2) effectue un grand nombre d'opérations de lecture et d'écriture fréquentes. Quel type de volume Amazon Elastic Block Store (Amazon EBS) convient le mieux à cette charge de travail ?**

- A. Disque SSD (Solid State Drive) à usage général
- B. Disque dur (HDD) à froid
- C. Disque SSD (Solid State Drive) à IOPS alloués
- D. Disques durs (HDD) à débits optimisés

Réponse: C

## Question 7

**Question: Il est possible de créer un partage NFS sur une instance Linux basée sur Amazon EBS en installant et en configurant un serveur NFS sur l'instance. Ainsi, plusieurs systèmes Linux peuvent partager le système de fichiers de cette instance. Quels avantages apporte Amazon Elastic File System (Amazon EFS), par rapport à cette solution ? (Sélectionnez DEUX réponses.)**

- A. Cohérence forte
- B. Mise à l'échelle automatique
- C. Haute disponibilité
- D. Verrouillage de fichier
- E. Pas besoin de sauvegardes

Réponse: B, C

## Question 8

**Question: Quelle fonctionnalité fournit Amazon FSx for Windows File Server ?**

- A. Des serveurs de fichiers Windows entièrement gérés
- B. Un serveur Microsoft Active Directory (Microsoft AD) pour les serveurs de fichiers Windows
- C. Une solution de sauvegarde pour les serveurs de fichiers Windows sur site
- D. L'agent de gestion Amazon pour les serveurs de fichiers Windows

Réponse: A

## Question 9

**Question: Quelles descriptions des options de tarification Amazon Elastic Compute Cloud (Amazon EC2) sont correctes ? (Sélectionnez DEUX réponses.)**

- A. Les instances à la demande vous permettent de payer la capacité de calcul en fonction du temps d'utilisation, sans engagement à long terme.
- B. Les instances réservées sont des serveurs physiques qui vous sont exclusivement réservés.
- C. Les Savings Plans sont des outils de budgétisation qui vous aident à gérer les coûts Amazon EC2.
- D. Les hôtes dédiés sont des serveurs dédiés à un seul objectif, par exemple à un pare-feu.
- E. Les instances Spot offrent une capacité de calcul de rechange à prix réduit et
- F. peuvent être interrompues.

Réponse: A, E

## Question 10

**Question: Une entreprise dispose de trois instances de calcul à hautes performances qui doivent communiquer entre elles. L'entreprise souhaite atteindre une performance réseau optimale entre les instances. Il est essentiel que ces systèmes ne partagent pas le même rack. Quelle stratégie de placement doivent-elles utiliser ?**

- A. Par défaut
- B. Partition
- C. Répartition
- D. Cluster

Réponse: C
