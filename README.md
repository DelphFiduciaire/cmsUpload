# CRM pour Delph Fiduciaire
## Description
Ce CRM (Customer Relationship Management) a été développé 
spécialement pour le cabinet d'expertise comptable Delph 
Fiduciaire. Il s'agit d'une plateforme en ligne permettant 
aux clients de déposer les fichiers nécessaires pour que les 
comptables puissent les traiter. Le CRM est conçu pour répondre
aux besoins spécifiques du cabinet Delph Fiduciaire en matière 
de gestion des clients, des fichiers et des utilisateurs. <br>

## Fonctionnalités principales

### 1. Gestion des rôles

Le CRM comporte trois rôles distincts avec des autorisations spécifiques :

<b>Administrateur :</b>  L'administrateur a un accès complet à l'ensemble du site. Il peut gérer les comptables, les clients, les fichiers, et effectuer toutes les actions disponibles sur la plateforme.

<b>Comptable : </b> Les comptables ont la capacité d'ajouter, de modifier, de supprimer des clients, ainsi que de gérer les fichiers associés. Ils peuvent également consulter les informations clients et les fichiers nécessaires à leur travail.

<b>Client : </b>Les clients peuvent consulter, modifier ou supprimer leurs propres données, ainsi que télécharger et envoyer des fichiers importants pour leur comptabilité.


### 2. Gestion des clients
Le CRM permet aux administrateurs et aux comptables de créer, mettre à jour et supprimer des fiches clients. Ces fiches peuvent contenir des informations essentielles telles que les coordonnées du client, son statut, etc.

### 3. Gestion des fichiers
Les fichiers sont au cœur de cette plateforme. Les comptables peuvent ajouter, modifier et supprimer des fichiers en fonction des besoins de chaque client. Les clients, quant à eux, peuvent télécharger des fichiers et les envoyer aux comptables pour traitement.

### 4. Technologie utilisée
Ce CRM a été développé en utilisant Symfony 6, un framework PHP populaire, qui offre une base solide pour le développement web sécurisé et évolutif.

## Configuration
### Installation
Clonez ce dépôt sur votre serveur : <br>

`bash
git clone git@github.com:DelphFiduciaire/cmsUpload.git
`
Assurez-vous que votre serveur web est configuré pour prendre en charge Symfony 6. <br>
Configurez la base de données en modifiant le fichier .env pour refléter vos paramètres de base de données. <br>
Exécutez les migrations pour créer la base de données : <br>

`bash
php bin/console doctrine:migrations:migrate
`
<br>

Démarrez le serveur de développement Symfony : <br>
`bash
php bin/console server:start
`<br>

### Configuration des rôles
L'attribution des rôles et des autorisations doit être gérée dans le code source du CRM en utilisant les outils de sécurité de Symfony. <br>

## Utilisation
Une fois le CRM installé et configuré, vous pouvez commencer à l'utiliser en suivant ces étapes : <br>

Connectez-vous en tant qu'administrateur pour gérer les utilisateurs, les clients et les fichiers.
Créez des comptes pour les comptables et les clients en attribuant les rôles appropriés.
Les clients peuvent se connecter et commencer à déposer leurs fichiers.
Les comptables peuvent consulter les fichiers des clients, les traiter et les mettre à jour au besoin. <br>


## Auteur
Orel Abecassis 
