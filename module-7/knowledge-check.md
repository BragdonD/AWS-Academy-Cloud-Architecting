# Knowledge check module 7

## Question 1

**Question: Qu'est-ce qu'AWS Site-to-Site VPN?**

- A. Un service qui fournit des liens chiffrés par SSL entre les sites web dans AWS
- B. Une solution qui fournit des sessions chiffrées entre AWS et des systèmes sur site à l'aide du protocole TLS
- C. Un service qui permet d'accéder aux réseaux AWS et sur site à l'aide de clients OpenVPN
- D. Une solution qui fournit une connexion entre un VPC et un réseau sur site à l'aide d'IPsec

Réponse: D

## Question 2

**Question: Que fournit AWS Direct Connect?**

- A. Une connexion réseau dédiée à partir d'un réseau sur site vers AWS, qui utilise 802.1q
- B. Un circuit de télécommunications privé à partir d'un réseau sur site directement vers AWS qui utilise le protocole PPP (Point-to-Point Protocol)
- C. Un tunnel chiffré qui connecte un réseau sur site à AWS sur Internet
- D. Une extension d'AWS Cloud dans les centres de données des clients qui utilise le matériel AWS installé sur site

Réponse: A

## Question 3

**Question: Une entreprise compte deux VPC. Le VPC A comporte un bloc d'adresse CIDR (Classless Inter-Domain Routing) de 10.1.0.0/16. Le VPC B comporte un bloc d'adresse CIDR de 10.2.0.0/16. Les deux VPC appartiennent au même compte Amazon Web Services (AWS). Quel est le moyen le plus simple de connecter les deux VPC pour qu'ils puissent acheminer l'ensemble du trafic de l'un à l'autre ?**

- A. AWS Site-to-Site VPN
- B. AWS Direct Connect
- C. Appairage de VPC
- D. Points de terminaison d'un VPC

Réponse: C

## Question 4

**Question: Une entreprise implémente un système pour sauvegarder des systèmes sur site sur Amazon Web Services (AWS). Quelle méthode de connectivité réseau fournira une solution proposant les performances les plus cohérentes?**

- A. AWS Site-to-Site VPN
- B. AWS Direct Connect
- C. Appairage de VPC
- D. Points de terminaison d'un VPC

Réponse: B

## Question 5

**Question: Des systèmes se trouvant dans un sous-réseau sécurisé d'un VPC doivent accéder à un compartiment dans Amazon Simple Storage Service (Amazon S3). Quelle solution empêche le trafic de passer par Internet?**

- A. Créer un point de terminaison de passerelle VPC pour Amazon S3
- B. Utiliser une adresse IP privée pour le système
- C. Utiliser l'adresse IP privée d'Amazon S3
- D. Créer une connexion d'appairage de VPC à Amazon S3

Réponse: A

## Question 6

**Question: Une entreprise compte trois VPC. Les VPC A, B et C disposent de blocs d'adresse CIDR (Classless Inter-Domain Routing) qui ne se chevauchent pas. Les VPC A et Cont des connexions d'appairage de VPC distinctes avec le VPC B. En revanche, le VPC A ne peut pas communiquer avec le VPC C. Quel est le moyen le plus simple et le plus rentable d'établir une communication complète entre les VPC A et C?**

- A. Ajouter des routages au VPC B pour permettre le trafic entre les VPC A et C via le VPC B.
- B. Ajouter une connexion d'appairage entre les VPC A et C, et acheminer le trafic entre les VPC A et C via la connexion d'appairage.
- C. Relier les trois VPC via un VPC de transit et acheminer l'ensemble du trafic via le VPC de transit.
- D. Créer des points de terminaison de VPC dans les VPC A et C pour les hôtes individuels ayant besoin de communiquer les uns avec les autres.

Réponse: B

## Question 7

**Question: Suite à une catastrophe naturelle, une entreprise a déplacé un centre de données secondaire vers une installation temporaire ayant une connectivité Internet. L'entreprise a besoin d'une connexion sécurisée et opérationnelle dès que possible vers son VPC. Le centre de données sera à nouveau déplacé dans deux semaines. Quelle option répond aux exigences?**

- A. Appairage de VPC
- B. Points de terminaison d'un VPC
- C. C AWS Site-to-Site VPN
- D. AWS Direct Connect

Réponse: C

## Question 8

**Question: Quel est le moyen le plus simple d'interconnecter 100 VPC?**

- A. Créer un réseau en étoile à l'aide d'AWS VPN CloudHub
- B. Enchaîner des VPC à l'aide de l'appairage de VPC
- C. Connecter chaque VPC à tous les autres VPC à l'aide de l'appairage de VPC
- D. Connecter les VPC à AWS Transit Gateway

Réponse: D

## Question 9

**Question: L'administrateur de la sécurité d'une entreprise a besoin que les instances EC2 d'un sous-réseau spécifique se connectent à Amazon DynamoDB via un point de terminaison de VPC. Les normes du réseau de l'entreprise exigent que l'infrastructure prenne en charge une haute disponibilité. Quelle action respecte ces exigences en termes d'architecture sans ajouter de sous-réseau ?**

- A. Associer un point de terminaison de VPC unique au sous-réseau
- B. Associer deux points de terminaison de VPC au sous-réseau
- C. Associer deux points de terminaison d'un VPC au sous-réseau et utiliser Elastic Load Balancing
- D. Associer des points de terminaison de VPC via un groupe Auto Scaling connecté à Elastic Load Balancing

Réponse: A

## Question 10

**Question: Une entreprise utilise une connexion AWS Direct Connect unique entre son réseau sur site et son VPC. Elle souhaite garantir une connectivité réseau hautement disponible en ajoutant une connexion de sauvegarde. Quelle méthode de connectivité réseau offre la solution la plus rentable pour la connexion de sauvegarde?**

- A. Une autre connexion AWS Direct Connect via le même emplacement Direct Connect
- B. Une autre connexion AWS Direct Connect via un autre emplacement Direct Connect
- C. Une connexion AWS Client VPN à la demande sur Internet
- D. Une connexion AWS Site-to-Site VPN à la demande sur Internet

Réponse: D
