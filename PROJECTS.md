# Projets sélectionnés

Cette page complète le README principal avec une lecture plus détaillée de mes projets publics et de certaines réalisations professionnelles présentées de manière anonymisée. L’objectif n’est pas de lister tous mes dépôts, mais de montrer les projets qui racontent le mieux mon profil : applications métier, santé/data, IA, C++ desktop et outils utiles.

---

## Lecture rapide

| Projet | Catégorie | Pourquoi le regarder |
|---|---|---|
| [Cap RH+](./CAP_RH_PLUS.md) | Projet professionnel | Premier projet d’entreprise réalisé end-to-end : besoin métier, app web, backend, exports, mails, tests, documentation. |
| [ScanGUI](https://github.com/P-Pix/ScanGUI) | C++ desktop | Reprise d’un ancien projet étudiant et modernisation vers architecture en couches, serveur local C++ et PostgreSQL. |
| [Core-CHU](https://github.com/P-Pix/Core-CHU) | Architecture santé | Prototype de plateforme hospitalière modulaire avec sécurité, RBAC et modules métier. |
| [ChatLegalGPT](https://github.com/P-Pix/ChatLegalGPT) | IA générative | Assistant expérimental spécialisé sur le droit français. |
| [Copilote IA médical](https://github.com/P-Pix/Copilote-IA-de-compr-hension-et-r-daction-de-comptes-rendus-m-dicaux) | IA santé | Application d’aide à la compréhension et rédaction de comptes rendus médicaux. |
| [Modern Paint Local](https://github.com/P-Pix/Modern_paint_local) | Outil local | Application frontend-only de manipulation d’images sans serveur. |
| [meta-descripteur-dataset-graphs](https://github.com/P-Pix/meta-descripteur-dataset-graphs) | Data science | Travaux sur graphes, méta-descripteurs et explicabilité. |

---

## Projet professionnel anonymisé

### Cap RH+

**Stack :** JavaScript, HTML/CSS, Node.js, Express, Excel/CSV, JSON runtime, XLSX, nodemailer, tests Node.js.

Cap RH+ est le projet le plus important à mettre en avant car il représente une vraie réalisation professionnelle. Le logiciel a été développé pour répondre à un besoin métier RH interne en environnement public / santé. Il couvre toute la chaîne : préparation des données, interface utilisateur, backend, sessions, droits, exports, mails, tests et documentation.

Le projet est présenté publiquement sous forme d’étude de cas anonymisée. Le code complet et les données ne sont pas publiés afin de respecter la confidentialité des informations RH et des paramètres internes.

**Ce que le projet démontre :**

- capacité à gérer un projet end-to-end ;
- compréhension d’un processus métier réel ;
- interface adaptée à des utilisateurs non techniques ;
- backend Express structuré ;
- pipeline de transformation Excel/CSV/JSON ;
- exports XLSX ;
- automatisation de mails ;
- tests et documentation ;
- travail en environnement sensible.

➡️ [Lire l’étude de cas Cap RH+](./CAP_RH_PLUS.md)

---

## Applications métier et architecture

### ScanGUI

**Stack :** C++, GTKmm, CMake, serveur HTTP local C++, PostgreSQL, Doxygen.

ScanGUI est un ancien projet desktop C++ développé pendant mes études, repris ensuite comme exercice de modernisation logicielle. L’intérêt du projet n’est pas uniquement l’application en elle-même, mais le travail de professionnalisation : séparation du cœur métier, abstraction de la source de données, serveur local C++ écrit sans framework web, API REST, indexation PostgreSQL et documentation Doxygen.

**Ce que le projet démontre :**

- développement desktop natif ;
- C++ orienté application ;
- architecture en couches ;
- serveur HTTP minimal en C++ ;
- manipulation du système de fichiers ;
- PostgreSQL ;
- reprise et refactorisation d’un ancien code.

➡️ [Voir le dépôt ScanGUI](https://github.com/P-Pix/ScanGUI)

### Core-CHU

**Stack :** Python, FastAPI, TypeScript, PostgreSQL, Docker.

Core-CHU est un prototype de plateforme hospitalière modulaire. Le projet sert à explorer une architecture logicielle pensée pour des environnements sensibles : modules métier, sécurité, RBAC, séparation des responsabilités, documentation, qualité de code et évolutivité.

**Ce que le projet démontre :**

- réflexion d’architecture applicative ;
- structuration de modules métier ;
- sécurité et droits ;
- backend API ;
- frontend TypeScript ;
- projection vers des usages hospitaliers.

➡️ [Voir le dépôt Core-CHU](https://github.com/P-Pix/Core-CHU)

### Modern Paint Local

**Stack :** HTML, CSS, JavaScript.

Modern Paint Local est un outil frontend-only de manipulation d’images. Le projet est pensé pour fonctionner localement, sans backend, avec une interface simple et un usage direct dans le navigateur.

**Ce que le projet démontre :**

- interface web légère ;
- manipulation d’images côté navigateur ;
- logique offline ;
- expérimentation UX/UI sur outil local.

➡️ [Voir le dépôt Modern Paint Local](https://github.com/P-Pix/Modern_paint_local)

---

## IA, data et santé

### Copilote IA médical

**Stack :** Python, React, NLP.

Ce projet explore l’analyse et la rédaction assistée de comptes rendus médicaux. Il s’inscrit dans mon intérêt pour les outils d’aide à la compréhension de documents, l’extraction d’informations et l’assistance aux tâches rédactionnelles en santé.

**Ce que le projet démontre :**

- NLP appliqué à des documents spécialisés ;
- interface utilisateur pour la synthèse ;
- logique full-stack ;
- sensibilité aux données médicales et à leur structuration.

➡️ [Voir le dépôt](https://github.com/P-Pix/Copilote-IA-de-compr-hension-et-r-daction-de-comptes-rendus-m-dicaux)

### ChatLegalGPT

**Stack :** Python, IA générative, interface web.

ChatLegalGPT est un assistant expérimental visant à interroger le droit français. Le projet s’inscrit dans une logique de spécialisation d’un assistant IA sur un domaine documentaire précis.

**Ce que le projet démontre :**

- IA générative spécialisée ;
- structuration documentaire ;
- interface de question/réponse ;
- réflexion sur les limites d’un assistant spécialisé.

➡️ [Voir le dépôt ChatLegalGPT](https://github.com/P-Pix/ChatLegalGPT)

### meta-descripteur-dataset-graphs

**Stack :** Python, graphes, data science.

Ce projet porte sur la caractérisation de datasets de graphes à l’aide de méta-descripteurs. Il s’inscrit dans mon parcours IA/data et dans mes travaux autour de l’explicabilité.

**Ce que le projet démontre :**

- manipulation de graphes ;
- analyse de datasets ;
- extraction de descripteurs ;
- réflexion sur l’explicabilité et la généralisation.

➡️ [Voir le dépôt](https://github.com/P-Pix/meta-descripteur-dataset-graphs)

---

## C++ et visualisation

### 2DMotor

**Stack :** C++, SDL2.

Projet d’expérimentation autour d’un moteur 2D. Il montre mon intérêt pour le C++ appliqué à la visualisation, au rendu et aux outils proches de la machine.

➡️ [Voir le dépôt 2DMotor](https://github.com/P-Pix/2DMotor)

### 3DMotorRayTracing

**Stack :** C++, rendu 3D, ray tracing.

Expérimentation autour d’un moteur 3D et du ray tracing. Le projet est davantage exploratoire, mais il montre une curiosité technique pour les sujets bas niveau et graphiques.

➡️ [Voir le dépôt 3DMotorRayTracing](https://github.com/P-Pix/3DMotorRayTracing)

### Probleme-N-Corps

**Stack :** simulation, visualisation.

Projet de visualisation autour du problème des N corps. Il combine simulation, représentation graphique et logique mathématique.

➡️ [Voir le dépôt Probleme-N-Corps](https://github.com/P-Pix/Probleme-N-Corps)

---

## Comment lire mon GitHub

Mes projets ne sont pas tous au même niveau de maturité. Certains sont des expérimentations, d’autres des prototypes, et Cap RH+ correspond à une réalisation professionnelle réelle mais anonymisée.

Les projets à regarder en priorité pour comprendre mon profil sont :

1. **Cap RH+** pour le côté projet professionnel complet ;
2. **ScanGUI** pour le C++ desktop et la refactorisation ;
3. **Core-CHU** pour l’architecture santé ;
4. **Copilote IA médical** pour l’IA appliquée à la santé ;
5. **ChatLegalGPT** pour l’IA spécialisée ;
6. **Modern Paint Local** pour les outils web locaux.
