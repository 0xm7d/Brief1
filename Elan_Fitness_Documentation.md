# Élan Fitness — Documentation des acquis

**Projet :** Amélioration d'un site web de fitness  
**Technologies :** HTML5, CSS3  
**Organisation :** Trello  
**Durée du projet :** 4 jours (du 6 au 9 octobre 2026)

## 1. Quel était le contexte du projet et quels étaient les objectifs ?

Le site Élan Fitness était initialement composé d'une seule page (*One Page*) regroupant toutes les sections.

Mon travail consistait à le transformer en un site *Multi Page*. J'ai réparti les sections existantes sur trois pages : Accueil, Programmes et À propos. J'ai ensuite ajouté une page Contact, en essayant de conserver le style du site d'origine.

J'ai également réalisé une page de connexion (*Login*) avec des champs pour l'adresse e-mail et le mot de passe. L'objectif principal était de mieux organiser les contenus et de faciliter la navigation entre les pages.

## 2. Comment avez-vous analysé le site One Page existant ?

Avant de modifier le code, j'ai commencé par explorer le site Élan Fitness afin de comprendre son organisation et les différentes sections de la page unique.

J'ai ensuite identifié les contenus à répartir et déterminé les pages nécessaires. Une fois cette analyse terminée, je suis passé au code pour séparer les sections et les organiser dans des fichiers HTML distincts.

## 3. Comment avez-vous organisé votre travail pendant les quatre jours ?

J'ai utilisé **Trello** pour planifier le travail et suivre l'avancement des tâches.

- **Jour 1 — Mardi :** analyse du projet, séparation du site One Page en plusieurs pages et résolution d'un problème lié à GitHub.
- **Jour 2 — Mercredi :** recherche et choix d'un logo, puis travail sur la page Contact.
- **Jour 3 — Jeudi :** finalisation de la page Contact, révision du code et début de la documentation.
- **Jour 4 — Vendredi :** déploiement sur GitHub Pages, tests et finalisation de la documentation.

Le planning a évolué : la page Contact a été terminée le troisième jour au lieu du deuxième, et la mise en ligne sur GitHub Pages a été effectuée le quatrième jour. Trello m'a aidé à distinguer les tâches à faire, en cours et terminées, et à mieux gérer le délai.

## 4. Comment avez-vous choisi le logo et respecté l'identité visuelle du site ?

J'ai trouvé le logo utilisé pour Élan Fitness sur **Pinterest**. Je l'ai choisi en cherchant un visuel qui correspond au domaine du sport et du fitness, tout en restant cohérent avec les couleurs et l'apparence générale du site.

Pour la nouvelle page Contact, j'ai essayé de conserver le même style visuel que celui des autres pages. Cette étape m'a appris l'importance d'une identité graphique cohérente sur l'ensemble d'un site.

## 5. Comment avez-vous structuré les pages avec HTML5 ?

J'ai organisé les quatre pages principales du site dans les fichiers suivants :

- `index.html` : accueil ;
- `programmes.html` : programmes ;
- `a&propos.html` : à propos ;
- `contact.html` : contact.

En plus de ces quatre pages, j'ai créé **une page Login**, avec un formulaire contenant un champ e-mail et un champ mot de passe. Son nom de fichier n'est pas précisé ici.

J'ai utilisé des balises sémantiques HTML5, notamment `header`, `nav`, `main`, `section` et `footer`, pour structurer le contenu. Les quatre pages principales disposent d'une barre de navigation et d'un pied de page, avec des liens permettant de naviguer entre elles.

Cette étape m'a permis de mieux comprendre l'organisation d'un projet HTML multipage.

## 6. Comment avez-vous organisé le CSS du projet ?

J'ai regroupé les styles CSS du projet dans un seul fichier, **`style.css`**, afin de gérer la présentation des différentes pages au même endroit.

J'ai utilisé **CSS Flexbox** pour aligner et organiser des éléments sur la page. Cela m'a permis de mieux comprendre la séparation entre la structure HTML et la présentation CSS.

Je n'ai **pas réalisé de travail spécifique sur le Responsive Design** dans ce projet ; je ne le présente donc pas comme une fonctionnalité développée.

## 7. Quelles pages et fonctionnalités supplémentaires avez-vous réalisées ?

J'ai principalement travaillé sur deux éléments ajoutés au site :

- **Page Contact :** création d'une page dédiée contenant un formulaire de contact. Je n'affirme pas que l'envoi des messages vers un serveur est fonctionnel, car cela n'a pas été vérifié.
- **Page Login :** réalisation d'une interface de connexion avec deux champs de saisie : **e-mail** et **mot de passe**. L'authentification réelle des utilisateurs n'a pas été confirmée.

Ces ajouts m'ont permis de pratiquer la création de formulaires HTML et l'organisation de pages distinctes, tout en conservant une présentation cohérente.

## 8. Comment avez-vous évalué l'accessibilité, le SEO et les performances ?

J'ai utilisé **Google Lighthouse** pour vérifier la qualité du site et identifier les points à améliorer. Parmi les améliorations effectuées, je peux citer :

- l'ajout d'attributs `alt` aux images ;
- l'utilisation de balises sémantiques HTML5 ;

La dernière capture d'écran fournie affiche les scores suivants :

| Catégorie Lighthouse | Score affiché |
| --- | ---: |
| Performance | **100/100** |
| Accessibility | **95/100** |
| Best Practices | **96/100** |
| SEO | **100/100** |

Ces chiffres décrivent **un audit précis**, et les résultats peuvent varier d'un test à l'autre. Ils ne prouvent pas à eux seuls une conformité complète aux normes WCAG ou W3C.

## 9. Quelles difficultés avez-vous rencontrées et qu'avez-vous appris en les résolvant ?

L'une des principales difficultés a été de comprendre et d'améliorer les résultats de **Google Lighthouse**, surtout pour l'**accessibilité**. Je souhaitais obtenir le meilleur score possible dans chaque catégorie.

Les premiers audits ont signalé des problèmes d'accessibilité, en particulier des champs de formulaire sans label associé et des contrastes de couleurs insuffisants pour certains éléments. J'ai notamment ajouté des labels aux champs concernés et relancé les tests pour suivre l'évolution du score.

Au fil des audits communiqués pendant le projet, le score d'accessibilité a progressé depuis **84/100** ; la dernière capture affiche **95/100**. J'ai compris qu'un site ne doit pas seulement être agréable à regarder : il faut aussi vérifier sa structure et son accessibilité.

## 10. Quelles compétences avez-vous acquises et que pourriez-vous améliorer ?

Ce premier projet HTML/CSS m'a surtout permis de progresser dans trois domaines :

- **Accessibilité et Lighthouse :** apprendre à lire les résultats d'un audit et à repérer les problèmes à corriger.
- **Recherche et résolution de problèmes :** analyser les erreurs et chercher des solutions adaptées.
- **Organisation avec Trello :** découper le projet en tâches et suivre leur état d'avancement.

Pour mes prochains projets, je souhaite avant tout **améliorer ma gestion du temps**. Grâce à Trello, j'ai pu voir clairement ce qu'il restait à faire, ce qui était en cours et ce qui était terminé. Cette méthode m'a aidé à mieux suivre le planning et à respecter les délais. Je souhaite continuer à l'utiliser pour anticiper les étapes et mieux gérer les imprévus.

---

## Liens du projet

- **Dépôt GitHub :** : https://github.com/0xm7d/Brief1
- **Site déployé sur GitHub Pages :** : https://0xm7d.github.io/Brief1/index.html

*Documentation rédigée à partir de mon retour d'expérience sur le projet Élan Fitness.*
