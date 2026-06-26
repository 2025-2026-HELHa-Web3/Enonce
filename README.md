# Projet Web 3 - 2025-2026

*Pluquet Frédéric - HELHa*

## Description

La description du projet a été donnée oralement au cours (GitHub pour la création automatique de repositories pour les projets d'années au sein de la HELHa) et ne sera pas répétée ici. Vous devez avoir pris des notes durant le cours.

## Fonctionnalités

Chaque étudiant a dû prendre note des fonctionnalités demandées. Comme pour un vrai client, le cahier des charges doit être raffiné avec le client (le professeur). Vous devez donc me poser des questions pour clarifier les fonctionnalités demandées. 

Le client sera content quand vous aurez implémenté les fonctionnalités demandées. Si vous avez complètement fini les fonctionnalités demandées, vous pouvez ajouter des fonctionnalités supplémentaires. Vous devez me demander si ces fonctionnalités supplémentaires sont acceptables. Vous pourrez alors obtenir des points bonus si ces fonctionnalités sont bien implémentées.

## Technologies

- Frontend : *React*
    - Client HTTP : *Axios*
    - Router : *React Router* ou celui de *nextjs*
    - *Architecture claire avec des composants réutilisables et des contextes pour gérer les données*
    - Design : *CSS ou SASS/SCSS de préférence*. Utilisez une bibliothèque de composants React (Material-UI, Ant Design, etc.), ou Bootstrap, ou Tailwind CSS, ... pour accélérer le développement et avoir un design cohérent et maintenable dans le temps.
    - Tout en *TypeScript* pour la partie React
    - *Bonne gestion des erreurs (surtout liées à l'API)*
- Backend : *Node.js avec Express*
    - Base de données : *MongoDB ou MariaDB*
    - Avec Object Relational Mapping (ORM) : *Mongoose ou TypeORM ou Prisma*
    - API : *L'API de GitHub*. *Vous stockerez le token des utilisateurs de votre application (les professeurs) dans votre base de données pour faire des requêtes à l'API de GitHub en leur nom. Attention à respecter les limites de l'API de GitHub (nombre de requêtes par heure, etc.). Vous devez également gérer les erreurs liées à l'API de GitHub (token invalide, limite de requêtes atteinte, etc.).*
    - Authentification : *JSON Web Token (JWT)*
    - Tout en *TypeScript*
- *Scripts dans vos `package.json`*
    - Afin de lancer facilement votre application en mode développement et en mode production, vous devez ajouter des scripts dans vos `package.json`. 
- Versionning : *GitHub*
- Déploiement : 
    - *sur votre propre serveur, si vous en avez un*
    - ou, par exemple *sur GitHub Pages (pour le frontend uniquement) et/ou sur alwaysdata, Vercel, Render, Railway, Heroku ou... (pour le backend uniquement)*
- Tests :
    - En TypeScript
    - Tests unitaires : Jest
    - Tests d'intégration : Jest
    - Tests end-to-end : Cypress (local)
- Documentation :
    - En *Markdown* (pas de pdf ou autres).
    - *Elle doit être lisible directement sur GitHub.*
    - *Dans le dossier `docs` à la racine du projet, la documentation technique doit permettre de comprendre comment installer et utiliser l'application. Vous devez également indiquer ce qu'il faut mettre en place pour configurer les processus en arrière-plan (crontab, ...) ou autre.*
- Sécurité :
    - Protection contre les attaques *XSS* et *CSRF*
    - Protection contre les *injections SQL* (si vous utilisez une base de données relationnelle)
    - *Bonne gestion des mots de passe* (hachage avec bcrypt, etc.)
    - Utilisation de *HTTPS* (pour le déploiement votre application)
    - *Validation des données* (avec Joi, Yup, etc.)


Toutes les fonctionnalités ne sont pas obligatoires mais l'ensemble de vos fonctionnalités doit recouvrir tout ce qui est en *italique*. Ce qui est en *italique* est donc la partie obligatoire pour ce projet. Tout ce qui n'est pas en italique est optionnel. Vous pouvez ajouter d'autres technologies si vous le souhaitez.
    
## Equipe

- Vous devrez travailler en équipe de 1 à 3 personnes. Vous devrez utiliser GitHub pour gérer votre projet. Vous devrez utiliser des branches pour travailler sur des fonctionnalités différentes. Vous pouvez utiliser des pull requests pour fusionner vos branches. Vous devrez utiliser des issues pour gérer les tâches à réaliser.
- Vous devez travailler avec la méthodologie *Scrum*. Vous devrez organiser votre travail en sprints de 2 semaines. Vous devrez faire une réunion de planification au début de chaque sprint pour définir les tâches à réaliser. Vous devrez faire une réunion de revue et de rétrospective à la fin de chaque sprint pour faire le point sur ce qui a été fait et ce qui n'a pas été fait.
- Voici les dates des sprints :
    - Sprint 1 : du 23 septembre 2025 au 6 octobre 2025
    - Sprint 2 : du 7 octobre 2025 au 20 octobre 2025
    - Sprint 3 : du 21 octobre 2025 au 3 novembre 2025
    - Sprint 4 : du 4 novembre 2025 au 11 novembre 2025 (on prendra un peu de temps pour fixer le sprint durant les heures de programmation DevOps)


## Planning

- Le projet a commencé le 23 septembre 2025 et se terminera le 11 novembre 2025 à 22h.
- Chaque sprint commencera par une réunion de planification (le mardi) et se terminera par une réunion de revue et de rétrospective. Le professeur prendra un code d'une équipe au hasard pour le corriger. Il pourra poser des questions sur l'utilisation de GitHub, des branches, des pull requests, des issues, des tests, de la documentation, etc.
- Chaque membre de l'équipe devra travailler sur une tâche à la fois. Les tâches seront distribuées équitablement entre les membres de l'équipe et devront être réalisées dans le sprint en cours. Si une tâche n'est pas terminée à la fin du sprint, elle sera reportée au sprint suivant. Toutes les tâches seront notées sur le tableau de bord (de GitHub ou autres).
- Vos points seront calculés en fonction de la quantité et de la qualité de votre travail. Vous devrez respecter les délais et les consignes pour obtenir des points. Vous devrez aussi participer activement aux réunions de planification, de revue et de rétrospective pour obtenir des points.
- Votre présence est donc obligatoire à toutes les séances de planification. Si vous ne pouvez pas être présent à une des ces séances, vous devrez prévenir à l'avance et vous devrez rattraper le travail manqué.
- Afin de noter au mieux chaque membre de l'équipe, vous devrez utiliser des branches pour travailler sur des fonctionnalités différentes. Vous pourrez être interrogés sur l'utilisation de ces outils lors de la revue de projet.

## Modalité de l'examen Q1

- Vous devez remettre votre projet sur votre repository GitHub pour **le 11 novembre 2025 à 22h maximum**.
- L'application doit être fonctionnelle et respecter les fonctionnalités obligatoires. Si ce n'est pas le cas, alors l'examen ne pourra pas être réussi (mieux vaut le repasser en Q3 alors).
- Pour cette même date, vous ferez une vidéo de présentation de votre projet (une vidéo par groupe). Vous devrez expliquer les fonctionnalités de votre application, les technologies utilisées, les difficultés rencontrées, l'architecture de votre code, etc. Vous devrez montrer votre application en fonctionnement. Vous mettrez le lien de la vidéo dans le fichier `README.md` de votre projet.
- Vous passerez un examen oral durant la semaine du 24 novembre 2025 par groupe. Chaque membre du groupe doit être capable d'expliquer l'ensemble du code du projet, les tests (si présents), la documentation, etc. Chaque membre devra aussi répondre à des questions sur les technologies utilisées, les choix que vous avez faits, les difficultés rencontrées, etc. Vous devez également être capable de montrer votre application en fonctionnement.
- Prenez chacun vos ordinateurs portables pour l'examen oral. Vous serez potentiellement interrogés simultanément via une application en ligne. 
- Les interrogations durant l'année compte pour 20%, le projet pour 30% et l'examen pour 50% de la note finale.
- Il n'y a pas d'examen durant la session de janvier.

## Modalité de l'examen Q3

- **Date butoir : le 20 août 2026 à 18h maximum.**
- Si vous n'avez pas réussi à obtenir la moyenne à l'examen Q1, vous devrez remettre une version améliorée de votre projet.
- Si vous ne souhaitez **pas modifier le code** de votre projet, vous le pouvez : vous obtiendrez alors **la même note de projet** que celle reçue au Q1 (si une note vous a été attribuée).
- Vous pouvez continuer à travailler en équipe ou seul pour améliorer votre projet. Vous devrez remettre votre projet sur GitHub pour la date butoir indiquée ci-dessus. Si vous n'avez pas de repository GitHub, je dois vous le créer pour vous (merci alors de le demander pour **le 7 août 2026** au plus tard).
- Si vous aviez travaillé en **groupe** au Q1, que **plus d'un membre** doit repasser l'examen en Q3 et que vous ne souhaitez **plus travailler ensemble**, vous devez **absolument** me demander la création d'un **nouveau repository** (pour chaque nouvelle composition d'équipe ou pour un travail individuel).
- L'énoncé de projet reste le même (fonctionnalités et livrables). 
- Vous devrez également remettre une documentation textuelle expliquant les améliorations que vous avez apportées à votre projet depuis le Q1 (le cas échéant).
- Vous devrez remettre **une seule vidéo** de présentation de votre projet (une vidéo par groupe, pas une vidéo par membre). Cette vidéo doit expliquer rapidement les fonctionnalités mises en place, l'architecture de votre code et montrer l'application en fonctionnement. **Si vous avez continué un projet remis en Q1, la vidéo doit surtout mettre en avant les modifications et améliorations apportées depuis le Q1** (en complément d'un bref rappel du contexte). Vous mettrez le lien de la vidéo dans le fichier `README.md` de votre projet.
- Tout ce qui précède est obligatoire pour réussir l'examen Q3 et doit être rendu pour **le 20 août 2026 à 18h maximum**.
- Vous passerez un examen oral par groupe. Chaque membre du groupe doit être capable d'expliquer l'ensemble du code du projet, les tests, la documentation, etc. Chaque membre devra aussi répondre à des questions sur les technologies utilisées, les choix que vous avez faits, les difficultés rencontrées, etc. Vous devez également être capable de montrer votre application en fonctionnement.
- Prenez chacun vos ordinateurs portables pour l'examen oral. Vous serez potentiellement interrogés simultanément via une application en ligne.
- Les interrogations durant l'année sont oubliées et le projet pour 40% et l'examen pour 60% de la note finale.

### *Bon travail !*

