Synopsis – Projet de fin de formation : Quiz interactif

Titre : Quiz Battle

Description générale :
Quiz Battle est une application web interactive permettant aux utilisateurs de tester leurs connaissances grâce à des quiz à choix multiples. Les utilisateurs peuvent parcourir une liste de quiz, sélectionner celui qui les intéresse et répondre aux questions pour obtenir un score final. L’application propose une interface simple et intuitive pour naviguer entre les quiz, répondre aux questions et consulter le score. Un espace administrateur protégé par authentification JWT permet de créer, modifier et supprimer des quiz.

Objectifs pédagogiques :
- Mettre en place un projet full stack (front-end et back-end).
- Maîtriser les concepts d’API REST, authentification JWT et sécurisation des routes.
- Manipuler une base de données relationnelle (MySQL) et l’intégrer à une application Express.
- Développer une interface utilisateur moderne avec React ou Angular.
- Mettre en place une gestion dynamique des données (CRUD) pour les quiz et les questions.

Fonctionnalités principales :
- Front-end :
  - Liste des quiz disponibles.
  - Page quiz interactif avec questions à choix multiples.
  - Calcul et affichage du score final.
  - Interface d’authentification administrateur (email et mot de passe).
  - Espace d’administration pour la création, modification et suppression des quiz.

- Back-end :
  - API REST Express avec les routes publiques (/quizzes et /quiz/:id) pour l’affichage des quiz.
  - Authentification JWT pour les routes protégées (/quiz POST, PUT, DELETE).
  - Sécurisation des mots de passe avec bcrypt.
  - Gestion des quiz, des questions et des réponses dans une base de données MySQL.

Stack technique :
- Front-end : React (ou Angular) pour l’interface utilisateur.
- Back-end : Node.js avec Express, MySQL, bcrypt et jsonwebtoken.
- Base de données : MySQL/MariaDB via Docker.
- Outils : Docker, VSCode, Postman pour tester les routes API.

Public cible :
- Toute personne souhaitant tester ses connaissances sur différents thèmes de quiz.
- Administrateur du site (compte protégé) pour gérer le contenu des quiz.

Durée estimée : 1 semaine.

Conclusion :
Quiz Battle est un projet complet qui démontre les compétences acquises durant la formation : mise en place d’un serveur back-end sécurisé, gestion d’une base de données relationnelle, création d’un front-end dynamique et intégration des concepts d’authentification et de sécurisation JWT. Il constitue un excellent projet de fin de formation pour valider les acquis et enrichir le portfolio professionnel.

