# Knowledge check module 6

## Question 1

**Question: Quelle définition décrit un cloud privé virtuel (VPC) ?**

- A. Un réseau privé virtuel (VPN) dans le Cloud AWS
- B. Une extension d'un réseau sur site dans Amazon Web Services (AWS)
- C. Un réseau virtuel isolé de manière logique que vous définissez dans le Cloud AWS
- D. Un service entièrement géré qui étend le Cloud AWS aux sites du client

Réponse: C

## Question 2

**Question: Quelles actions constituent de bonnes pratiques pour concevoir un cloud privé virtuel (VPC) ? (Sélectionnez TROIS réponses.)**

- A. Faire correspondre la taille du bloc CIDR (Classless Inter-Domain Routing) du VPC au nombre d'hôtes requis pour une charge de travail.
- B. Utiliser le même bloc CIDR (Classless Inter-Domain Routing) que pour votre réseau sur site.
- C. Diviser l'étendue du réseau VPC uniformément dans toutes les zones de disponibilité disponibles.
- D. Créer un sous-réseau par zone de disponibilité pour chaque groupe d'hôtes ayant des exigences de routage uniques.
- E. Réserver des espaces d'adressage pour une utilisation future.

Réponse: C, D, E

## Question 3

**Question: Une entreprise souhaite exécuter un niveau web hautement disponible à l'aide de deux instances EC2 et d'un équilibreur de charge. Quelle conception est valide et offre la disponibilité la plus élevée ?**

- A. Un sous-réseau dans une zone de disponibilité. Le sous-réseau contient deux instances EC2.
- B. Un sous-réseau, qui couvre deux zones de disponibilité. Chaque zone de disponibilité contient une instance EC2.
- C. Deux sous-réseaux différents dans la même zone de disponibilité. Chaque sous-réseau contient une instance EC2.
- D. Deux sous-réseaux différents, un par zone de disponibilité. Chaque sous- réseau contient une instance EC2.

Réponse: D

## Question 4

**Question: Le VPC d'une entreprise comporte le bloc d'adresse CIDR 172.16.0.0/21 (2048 adresses). Il comporte deux sous-réseaux (A et B). Chaque sous-réseau doit maintenant prendre en charge 100 adresses utilisables, mais le nombre risque d'augmenter rapidement à 254 adresses utilisables. Quel schéma d'adressage de sous-réseau répond aux exigences et respecte les bonnes pratiques AWS ?**

- A. Sous-réseau A: 172.16.0.0/25 (128 adresses) Sous-réseau B: 172.16.0.128/25 (1024 adresses)
- B. Sous-réseau A: 172.16.0.0/25 (128 adresses) Sous-réseau B: 172.16.0.128/25 (128 adresses)
- C. Sous-réseau A: 172.16.0.0/23 (512 adresses) Sous-réseau B: 172.16.2.0/23 (512 adresses)
- D. Sous-réseau A: 172.16.0.0/22 (1024 adresses) Sous-réseau B: 172.16.4.0/22 (128 adresses

Réponse: C

## Question 5

**Question: Quelle combinaison d'actions permet un accès direct à Internet pour les hôtes IPv4 dans un cloud privé virtuel (VPC) ? (Sélectionnez TROIS réponses.)**

- A. Activation de la résolution du système de noms de domaine (DNS) pour le VPC
- B. Configuration d'hôtes pour avoir ou obtenir une adresse pouvant être routée sur Internet
- C. Création d'une route pour 0.0.0.0/0 qui pointe vers la passerelle Internet
- D. Configuration du nom de domaine VPC dans un jeu d'options DHCP (Dynamic Host Configuration Protocol)
- E. Configuration de groupes de sécurité et de listes de contrôle d'accès réseau (ACL réseau) pour permettre le trafic Internet
- F. Création d'un routage par défaut qui pointe vers une passerelle de réseau privé virtuel

Réponse: B, C, E

## Question 6

**Question: Un groupe de consultants a besoin d'accéder à une instance EC2 à partir d'Internet pendant 3 jours consécutifs par semaine. Le reste de la semaine, l'instance est arrêtée. Le cloud privé virtuel (VPC) dispose d'un accès Internet. De quelle manière devez-vous affecter une adresse IPv4 à l'instance afin que les consultants puissent y accéder ?**

- A. Associer une adresse IP Elastic à l'instance EC2
- B. Activer l'affectation d'adresses automatique pour le sous-réseau
- C. Activer l'affectation d'adresses automatique pour l'instance EC2
- D. Affecter l'adresse IP dans la configuration de démarrage du système d'exploitation

Réponse: A

## Question 7

**Question: Plusieurs instances EC2 sont lancées dans un cloud privé virtuel (VPC) disposant d'un accès Internet. Ces instances ne doivent pas être accessibles à partir d'Internet, mais elles doivent pouvoir télécharger des mises à jour sur Internet. Comment les instances doivent-elles être lancées ?**

- A. Avec les adresses IP Elastic, dans un sous-réseau avec une route par défaut vers une passerelle Internet
- B. Avec les adresses IP publiques, dans un sous-réseau avec une route par défaut vers une passerelle Internet
- C. Sans adresse IP publique, dans un sous-réseau avec une route par défaut vers une passerelle Internet
- D. Sans adresse IP publique, dans un sous-réseau avec une route par défaut vers une passerelle de traduction d'adresses réseau (NAT)

Réponse: D

## Question 8

**Question: Vous configurez un hôte bastion pour accéder à des instances EC2 dans un cloud privé virtuel (VPC). Que devez-vous faire au niveau des groupes de sécurité ? (Sélectionnez DEUX réponses.)**

- A. Ajouter une règle à l'hôte bastion afin de refuser tout le trafic provenant d'Internet
- B. Ajouter une règle à l'hôte bastion afin d'autoriser le trafic à partir de votre adresse IP source
- C. Ajouter une règle à l'hôte bastion afin d'autoriser le trafic de retour vers votre adresse IP source
- D. Ajouter une règle aux instances EC2 du sous-réseau privé afin d'autoriser le trafic à partir du groupe de sécurité de l'hôte bastion
- E. Ajouter une règle aux instances EC2 du sous-réseau privé afin d'autoriser le trafic de retour vers le groupe de sécurité de l'hôte bastion

Réponse: B, D

## Question 9

**Question: Vous disposez d'un cloud privé virtuel (VPC) avec un sous-réseau public et un sous- réseau sécurisé. Toutes les instances EC2 du sous-réseau sécurisé doivent pouvoir communiquer avec des adresses Internet spécifiques. Comment pouvez-vous contrôler le trafic avec une liste de contrôle d'accès réseau (ACL réseau)?**

- A. Ajouter des règles à la liste ACL réseau par défaut afin d'autoriser le trafic depuis et vers les adresses Internet autorisées.
- B. Ajouter des règles à la liste ACL réseau par défaut afin d'autoriser le trafic depuis et vers les adresses Internet autorisées. Refuser tout autre trafic.
- C. Ajouter des règles à la liste ACL réseau personnalisée du sous-réseau afin d'autoriser le trafic depuis et vers les adresses Internet autorisées.
- D. Ajouter des règles à la liste ACL réseau personnalisée du sous-réseau afin d'autoriser le trafic depuis et vers les adresses Internet autorisées. Refuser tout autre trafic.

Réponse: C

## Question 10

**Question: Toutes les instances EC2 d'un sous-réseau peuvent communiquer avec un réseau IPv4 donné sur Internet. Comment devez-vous modifier les groupes de sécurité ou la liste de contrôle d'accès réseau (ACL réseau) actuelle afin de refuser le trafic vers et depuis plusieurs adresses restreintes de ce réseau ?**

- A. Dans la liste ACL réseau, refuser le trafic vers et depuis les adresses restreintes
- B. Dans les groupes de sécurité, refuser le trafic vers et depuis les adresses restreintes
- C. Dans la liste ACL réseau, autoriser le trafic uniquement vers et depuis les plages d'adresses qui excluent les adresses restreintes
- D. Dans les groupes de sécurité, autoriser le trafic uniquement vers et depuis les plages d'adresses qui excluent les adresses restreintes

Réponse: A
