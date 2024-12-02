# Knowledge check module 8

## Question 1

**Question: Quelle affirmation décrit les utilisateurs de Gestion des identités et des accès AWS (AWS IAM) ?**

- A. Les utilisateurs IAM permettent de contrôler l'accès à une ressource AWS spécifique.
- B. Les noms d'utilisateur IAM peuvent représenter un ensemble de personnes.
- C. Dans un compte, chaque utilisateur IAM doit avoir un nom unique.
- D. Chaque nom d'utilisateur IAM est unique dans l'ensemble des comptes AWS.

Réponse: C

## Question 2

**Comment pouvez-vous accorder le même niveau d'autorisations à plusieurs utilisateurs dans un même compte ?**

- A. Appliquer une politique de Gestion des identités et des accès AWS (AWS IAM) à un groupe IAM
- B. Appliquer une politique de Gestion des identités et des accès AWS (AWS IAM) à un rôle IAM
- C. Créer une politique basée sur les ressources
- D. Créer une organisation dans AWS Organizations

Réponse: A

## Question 3

**Quelles affirmations décrivent les rôles de Gestion des identités et des accès AWS (AWS IAM) ? (Sélectionnez DEUX réponses.)**

- A. Ils sont associés de manière unique à une personne.
- B. Ils peuvent uniquement être utilisés par des comptes associés à la personne qui crée le rôle.
- C. Ils peuvent être endossés par des utilisateurs, des applications et des services.
- D. Ils fournissent des justificatifs de sécurité temporaires.
- E. Ils fournissent des justificatifs de sécurité permanents.

Réponse: C, D

## Question 4

**Quelle affirmation décrit une politique basée sur les ressources ?**

- A. Elle peut être appliquée à n'importe quelle ressource AWS.
- B. Il peut s'agir d'une politique gérée par AWS.
- C. Elle est jointe à un utilisateur ou à un groupe.
- D. Il s'agit toujours d'une politique en ligne.

Réponse: D

## Question 5

**Comment le service Gestion des identités et des accès AWS (AWS IAM) évalue-t-il une politique ?**

- A. Il recherche les déclarations d'autorisation explicite avant de rechercher les déclarations de refus explicite.
- B. Il recherche les déclarations de refus explicite avant de rechercher les déclarations d'autorisation explicite.
- C. En l'absence de toute déclaration d'autorisation explicite et de toute déclaration de refus explicite, les utilisateurs disposent par défaut de l'accès.
- D. Une déclaration de refus explicite ne l'emporte pas sur une déclaration d'autorisation explicite.

Réponse: B

## Question 6

**Une équipe de développeurs a besoin d'accéder à plusieurs services et ressources dans un cloud privé virtuel (VPC) pendant une durée de 9 mois. Comment pouvez-vous utiliser Gestion des identités et des accès AWS (AWS IAM) pour leur accorder cet accès ?**

- A. Créer un seul utilisateur IAM pour l'équipe de développeurs et lui joindre les politiques IAM requises
- B. Créer un utilisateur IAM pour chaque développeur et joindre les politiques IAM requises à chaque utilisateur IAM
- C. Créer un utilisateur IAM pour chaque développeur, placer tous les utilisateurs dans un groupe IAM et joindre les politiques IAM requises à ce groupe IAM
- D. Créer un seul utilisateur IAM pour l'équipe de développeurs, le placer dans un groupe IAM et joindre les politiques IAM requises à ce groupe IAM

Réponse: C

## Question 7

**Comment la fédération d'identité accroît-elle la sécurité d'une application intégrée à Amazon Web Services (AWS) ?**

- A. Les utilisateurs peuvent utiliser l'option Single Sign-On (SSO) pour accéder à l'application par le biais d'une identité authentifiée existante.
- B. L'application peut synchroniser les noms d'utilisateur et les mots de passe des utilisateurs dans Gestion des identités et des accès AWS (AWS IAM) avec leurs comptes de réseaux sociaux.
- C. Le navigateur peut établir une relation d'approbation avec l'application pour contourner la nécessité d'une authentification multifactorielle (MFA).
- D. Les utilisateurs peuvent utiliser leurs comptes Gestion des identités et des accès AWS (AWS IAM) pour se connecter aux systèmes sur site.

Réponse: A

## Question 8

**Quels services pouvez-vous utiliser pour activer la fédération d'identité pour vos applications intégrées à Amazon Web Services (AWS) ? (Sélectionnez DEUX réponses.)**

- A. AWS WAF
- B. AWS Key Management Service (AWS KMS)
- C. Service de jetons de sécurité AWS (AWS STS)
- D. AWS CloudHSM
- E. Amazon Cognito

Réponse: C, E

## Question 9

**Quel service vous permet de gérer la facturation de manière centralisée, de contrôler l'accès, la conformité et la sécurité, et de partager les ressources entre vos différents comptes Amazon Web Services (AWS)?**

- A. Gestion des identités et des accès AWS (AWS IAM)
- B. AWS Control Tower
- C. AWS Organizations
- D. Appairage Amazon Virtual Private Cloud (Amazon VPC)

Réponse: C

## Question 10

**Les employés d'une entreprise technologique se connectent à leurs comptes Amazon Web Services (AWS) par le biais d'utilisateurs de Gestion des identités et des accès AWS (AWS IAM). Ils disposent d'un accès administrateur et d'un accès aux utilisateurs racine. Quelle ressource peut les empêcher de supprimer les journaux AWS CloudTrail?**

- A. Une politique IAM jointe à chaque utilisateur IAM
- B. Une stratégie de contrôle des services (SCP) jointe à l'unité organisationnelle (OU)
- C. Une politique de compartiment Amazon S3 jointe à des compartiments de journalisation
- D. Les utilisateurs IAM disposant d'un accès administratif peuvent l'emporter sur les politiques de compartiment S3.

Réponse: B
