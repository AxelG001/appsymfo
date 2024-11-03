# Application Todo List avec Symfony et React

## Description

J'ai développé cette application de type "Todo List" en utilisant Symfony et React. Le but principal était de me familiariser avec les concepts de base de Symfony, tout en créant un projet simple et fonctionnel.

### Objectifs :

- **Apprendre les bases de Symfony** : J'ai utilisé les entités, les contrôleurs, Doctrine pour gérer la base de données, Symfony UX pour intégrer React, et Webpack Encore pour gérer les assets.
- **Avoir une interface interactive** : Le front-end est en React, ce qui rend l'interface fluide et agréable pour ajouter, modifier ou supprimer des tâches.
- **Surmonter les problèmes de dépendances** : J’ai eu pas mal de difficultés avec certains packages et dépendances en suivant d’autres tutoriels. Finalement, j'ai opté pour un projet plus simple (une todo list) pour bien comprendre les concepts de base.

## Fonctionnalités

- Ajouter, modifier et supprimer des tâches
- Voir les tâches avec leurs titres, descriptions et états
- Front-end en React intégré avec Symfony UX
- Mise en forme rapide avec Tailwind CSS

## Installation

### Prérequis

- PHP 8.2 ou supérieur
- Composer
- Node.js et npm

### Étapes

1. **Cloner le dépôt** :
   ```bash
   git clone https://github.com/AxelG001/appsymfo.git
   cd todo-app
## ⚙️ Composer

 composer install


 
## 🔋 Dépendance


-npm install
## Base de donnée

Créez un fichier .env.local avec les infos de connexion :

DATABASE_URL="mysql://db_user:db_password@127.0.0.1:3306/db_name"

- **Créez la base de données et faites les migrations** :

php bin/console doctrine:database:create

php bin/console doctrine:migrations:migrate

**ensuite**:

npm run dev

**Pour lancer le server** :

symfony server:start

## Notation


| Critère                                 | Note sur 5 | Commentaire                                                                                                                                   |
|:----------------------------------------|:----------:|-----------------------------------------------------------------------------------------------------------------------------------------------:|
| Modélisation et structure des données   |    2   | Compréhension de la structure des données et de la modélisation des entités.                                                                   |
| Maîtrise du routage                     |     2      | Utilisation correcte et adéquate des routes pour organiser les fonctionnalités de l’application.                                               |
| Utilisation des contrôleurs             |    3     | Création et gestion des contrôleurs pour structurer la logique applicative.                                                                    |
| Intégration de React avec Symfony UX    |    4     | Maîtrise de Symfony UX React pour intégrer le front-end de manière réactive.                                                                   |
| Utilisation de Webpack Encore           |    5     | Exploitation de Webpack Encore pour la gestion des assets, y compris le front en React.                                                        |
| Gestion des erreurs et débogage         |    3.5     | Capacité à gérer les erreurs rencontrées avec Composer et les dépendances.                                                                     |
| Respect des concepts principaux de Symfony |     3  | Intégration des notions essentielles : entités, contrôleurs, Twig, etc.                                                                        |
| Clarté et structure du code             |     4    | Lisibilité et bonne structure du code, respectant les conventions Symfony.                                                                     |



Note finale: 3.5/5
