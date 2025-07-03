Présentation
Streamsin est une application web développée avec Angular, conçue pour reproduire l’expérience utilisateur d’une plateforme de streaming comme Netflix. L’idée du projet est née de l’envie de construire une interface fluide, esthétique et interactive qui permette à l’utilisateur de parcourir des films, consulter des informations détaillées, et lancer des bandes-annonces, le tout à partir d’une base de données externe. Streamsin met l’accent sur l’expérience visuelle et l’accessibilité à l’information, avec une navigation simple et une organisation claire des contenus.

Entités principales
Le cœur de l’application repose sur plusieurs entités essentielles :

Film : contient le titre, l'affiche, le résumé, l’identifiant, et parfois un lien vers une vidéo (bande-annonce).

Acteur : chaque film est associé à un ou plusieurs acteurs, affichés avec leur nom, leur rôle (voice ou personnage), et leur photo.

Recherche : l’utilisateur peut effectuer une recherche par mot-clé, et la liste des résultats est générée dynamiquement.

Vidéo : certaines pages permettent l’affichage d’un lecteur pour visionner une bande-annonce intégrée.

Ces entités sont représentées sous forme de composants Angular et récupérées via des appels API.

Technologies utilisées
Pour développer Streamsin, plusieurs technologies modernes du web ont été utilisées :

Angular : framework principal pour construire l’interface en mode SPA (Single Page Application)

TypeScript : langage fort typé permettant une meilleure lisibilité et organisation du code

HTML / CSS : pour structurer et styliser l’interface utilisateur

JavaScript : pour certains comportements dynamiques côté client

API REST : pour récupérer en temps réel les données des films, des acteurs et des bandes-annonces

GitHub Pages : utilisé pour le déploiement de l’application

Cahier des charges
Le projet devait répondre à plusieurs objectifs fonctionnels précis :

Permettre à l’utilisateur d’effectuer une recherche de films ou séries à partir d’un mot-clé

Afficher une liste de résultats sous forme de vignettes avec le titre et l’affiche

Offrir la possibilité de consulter une fiche détaillée avec le synopsis, les acteurs et la bande-annonce

Afficher le casting complet d’un film, avec les rôles et les images des comédiens

Proposer une navigation fluide entre les pages principales : accueil, recherche, détails

Assurer un design responsive pour s’adapter à tous les écrans

Le tout devait être fonctionnel sans authentification, et basé uniquement sur des données accessibles via une API publique (type TMDB ou équivalent).

Conclusion
Avec Streamsin, le défi a été de reproduire une plateforme de streaming moderne en s’appuyant uniquement sur des technologies front-end. Le projet démontre comment Angular permet de construire une interface modulaire, réactive et maintenable, en interaction avec des services externes. Grâce à une architecture bien pensée et une séparation claire des responsabilités, l’application reste facilement évolutive. À terme, Streamsin pourrait être enrichi par de nouvelles fonctionnalités comme l’ajout de favoris, de comptes utilisateurs ou la gestion de playlists.
Page D'accueil : 
![Capture d'écran 2025-07-03 102844](https://github.com/user-attachments/assets/949853d5-6dcf-485d-90e6-379e2f1ba183)

Page détail

![Capture d'écran 2025-07-03 102914](https://github.com/user-attachments/assets/2efd7709-4d1f-45e1-960a-2e7ed3b4c69d)

Visionnage video

![Capture d'écran 2025-07-03 103029](https://github.com/user-attachments/assets/735f4734-6bb2-4a7e-a3b6-1977df3987bb)

Page recherche

![Capture d'écran 2025-07-03 103311](https://github.com/user-attachments/assets/18c52138-0294-43bc-888f-177681f851ac)
