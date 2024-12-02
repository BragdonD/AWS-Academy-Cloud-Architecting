# Knowledge check module 9

## Question 1

**Question: Quelle affirmation concernant Amazon EC2 Auto Scaling est correcte ?**

- A. Le service nécessite que le client achète des instances réservées.
- B. Le service peut lancer des instances Amazon Elastic Compute Cloud (Amazon EC2) dans plusieurs zones de disponibilité.
- C. Le service peut lancer des instances Amazon Elastic Compute Cloud (Amazon EC2), mais les clients doivent résilier les instances lorsqu'ils n'en ont plus besoin.
- D. Le service peut lancer de nouvelles instances Amazon Elastic Compute Cloud (Amazon EC2) en fonction d'une planification.

Réponse: B

## Question 2

**Question: Vous avez détecté que la demande sur une flotte d'instances Amazon Elastic Compute Cloud (Amazon EC2) dans un groupe Auto Scaling augmente d'une quantité fixe chaque jour. Quel type de mise à l'échelle convient le mieux pour ce scénario?**

- A. Planifiée
- B. Dynamique
- C. Prédictive
- D. Manuelle

Réponse: A

## Question 3

**Question: Une flotte d'instances Amazon Elastic Compute Cloud (Amazon EC2) est lancée dans un groupe Auto Scaling derrière un équilibreur de charge Elastic Load Balancing. Les instances EC2 doivent conserver une utilisation de l'UC de 50%. Quel type de mise à l'échelle présente le moyen le plus simple d'y parvenir?**

- A. Mise à l'échelle par étapes
- B. Mise à l'échelle simple
- C. Mise à l'échelle avec suivi des objectifs
- D. Mise à l'échelle manuelle

Réponse: C

## Question 4

**Question: Comment mettre à l'échelle verticalement une base de données Amazon Relational Database Service (Amazon RDS) ?**

- A. En ajoutant des réplicas en lecture
- B. En créant des nœuds de lecture et d'écriture dédiés
- C. En partitionnant la base de données
- D. En changeant la classe d'instances

Réponse: D

## Question 5

**Question: Comment mettre à l'échelle horizontalement une base de données Amazon Aurora ?**

- A. En ajoutant des instances de réplica Aurora
- B. En augmentant la taille de la configuration du cache de mémoire tampon
- C. En créant des alarmes Amazon CloudWatch
- D. En changeant de type d'instance

Réponse: A

## Question 6

**Question: Comment le service Amazon DynamoDB procède-t-il à la mise à l'échelle automatique ?**

- A. Il ajoute et supprime des instances de base de données en réponse aux variations du trafic.
- B. Il ajoute des réplicas en lecture en réponse à une augmentation de la demande de lecture.
- C. Il ajuste la capacité allouée en réponse aux modèles de trafic.
- D. Il change le type d'instance en réponse aux variations de la charge de traitement.

Réponse: C

## Question 7

**Question: Une flotte d'instances Amazon Elastic Compute Cloud (Amazon EC2) se lance dans un groupe Auto Scaling. Les instances exécutent une application qui utilise un protocole personnalisé sur le port TCP 42000. Les connexions depuis des systèmes client sur Internet doivent être réparties entre les instances. Quelle solution de répartition de charge garantit la disponibilité la plus élevée ?**

- A. DNS en tourniquet (round robin)
- B. Application Load Balancer
- C. Network Load Balancer
- D. Équilibreur de charge basé sur une instance

Réponse: C

## Question 8

**Question: Les utilisateurs situés à l'emplacement A se connectent à une application dans la région A. Les utilisateurs situés à l'emplacement B se connectent à la même application dans la région B. Si l'application dans la région A devient défectueuse, les clients situés à l'emplacement A doivent être redirigés vers l'application dans la région B. Quelle solution répond à cette exigence ?**

- A. Utiliser un équilibreur Application Load Balancer avec des alarmes Amazon CloudWatch
- B. Utiliser le routage par géolocalisation avec enregistrements de basculement dans Amazon Route 53
- C. Utiliser le routage basé sur la latence dans Amazon Route 53 avec des alarmes Amazon CloudWatch
- D. Utiliser le routage par géoproximité et un équilibreur Network Load Balancer joint aux deux régions

Réponse: B

## Question 9

**Question: Une entreprise doit créer un site web hautement disponible qui utilise des scripts côté serveur pour distribuer des pages HTML dynamiques. Quelle solution fournit la disponibilité la plus élevée pour un coût et une complexité moindres?**

- A. Un groupe Auto Scaling lance des instances Amazon EC2, qui sont distribuées par un équilibreur Application Load Balancer. La résolution de noms DNS pointe vers l'équilibreur de charge.
- B. Amazon S3 héberge le site web. La résolution de noms DNS pointe vers le compartiment S3.
- C. Un groupe Auto Scaling lance des instances Amazon EC2, qui sont distribuées par un équilibreur Network Load Balancer. Amazon Route 53 utilise le routage basé sur la latence.
- D. Un second serveur web est déployé dans une autre région. Amazon Route 53 utilise le routage par basculement pour la reprise après sinistre.

Réponse: A

## Question 10

**Question: Vous avez créé un compte Amazon Web Services (AWS) pour votre développement et vos tests personnels. Vous souhaitez que votre compte reste dans le cadre de l'offre gratuite AWS et ne génère pas de coûts imprévus. Quelle approche sera efficace et nécessitera le moins d'efforts?**

- A. Se connecter à la console de gestion AWS tous les mois et vérifier le tableau de bord de facturation
- B. Créer une stratégie de contrôle des services (SCP) pour restreindre tous les services qui ne sont pas inclus dans l'offre gratuite AWS
- C. Créer une alarme Amazon CloudWatch pour qu'un e-mail vous soit envoyé quand la facturation du compte dépassera O USD
- D. Créer une métrique Amazon CloudWatch pour surveiller la facturation du compte et la limiter à O USD

Réponse: C
