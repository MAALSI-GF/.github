# Projet Good Food

## Description du Projet

Nous sommes une équipe d'école travaillant sur le projet **Good Food**, une application en microservices, composée de deux applications mobiles et d'une application web. Le projet reprend le fonctionnement de **Uber Eats**, permettant aux utilisateurs de commander des repas auprès de restaurants partenaires et de recevoir leurs commandes à domicile.

## GitHub Workflow

- **Branch `main`** : Représente l'environnement de production.
- **Branch `dev`** : Contient les fonctionnalités validées et en attente de mise en production.
- **Branches de fonctionnalités** : Chaque branche est nommée selon le ticket Jira associé, par exemple `feature/TICKET-123`.

## Nomenclature des Commits

- **`feat:`** : Utilisé pour une nouvelle fonctionnalité.
- **`fix:`** : Utilisé pour une correction de bug.
- **`conf:`** : Utilisé pour les changements de configuration.
- **`hotfix:`** : Utilisé pour une correction urgente sur la branche `dev` en cas de gros problème.

## Fonctionnement de l'Équipe

- Les tickets et les fonctionnalités sont réalisées en binôme, avec un développeur back-end et un développeur front-end.
- À la fin de chaque sprint (environ 1 mois), une **Sprint Review** est effectuée pour valider les tâches, tester les fonctionnalités, et préparer les changements à intégrer dans la branche `dev`.
- Les tâches doivent être terminées, validées, et testées avant d'être mises sur la branche `dev` en vue de leur mise en production.

