# Planification des Sprints

Le développement est découpé en sprints de 2 semaines. Le Sprint 1 est focalisé sur le MVP (Socle de l'application) pour un "Time-to-Market" rapide, incluant la fonctionnalité IA de base.

| N° Sprint | Durée | Objectif Principal | User Stories Incluses (ID) | Charge du Sprint (jours-homme) |
| :--- | :--- | :--- | :--- | :--- |
| **Sprint 1** | 2 semaines | Socle de l'application : compte, photo et 1ère recommandation. | 1, 2, 3, 8, 15, 16 | 13 jours |
| **Sprint 2** | 2 semaines | Amélioration des recos, parcours d'achat et préférences. | 4, 5, 9, 10, 11, 12, 17 | 10.5 jours |
| **Sprint 3 (Optionnel)** | 2 semaines | Enrichissement de l'expérience (les "Could have"). | 6, 7, 13 | 10 jours |

---

# Backlog Produit (Product Backlog)

Voici le backlog complet des User Stories, priorisé selon la méthode MoSCoW.

| ID | User Story | Priorité (MoSCoW) | Charge (Jours) | DS (%) | Dev (%) | UX/UI (%) | PM (%) | PO (%) |
| :--- | :--- | :--- | :---: | :---: | :---: | :---: | :---: | :---: |
| **Recommandation par Photo (Cœur IA)** | | | | | | | | |
| 1 | En tant que nouvel utilisateur, je veux créer un compte avec mon email et un mot de passe afin de sauvegarder mes photos et préférences. | **Must** | 1 | 0 | 40 | 40 | 10 | 10 |
| 2 | En tant qu'utilisateur connecté, je veux me prendre en photo ou télécharger une photo depuis ma galerie afin d'alimenter ma collection. | **Must** | 1,5 | 5 | 50 | 30 | 10 | 5 |
| 3 | En tant qu'utilisateur connecté, je veux recevoir des recommandations d'articles basées sur une de mes photos afin de découvrir des produits qui correspondent à mon style. | **Must** | 4 | 60 | 20 | 5 | 10 | 5 |
| 4 | En tant qu'utilisateur, je veux donner un avis (note/like/dislike) sur une recommandation afin d'améliorer les futures propositions. | **Should** | 1,5 | 15 | 40 | 30 | 10 | 5 |
| 5 | En tant qu'utilisateur, je veux consulter ma collection de photos et supprimer celles que je ne veux plus. | **Should** | 1,5 | 0 | 50 | 40 | 5 | 5 |
| 6 | En tant qu'utilisateur, je veux visualiser un vêtement recommandé directement sur ma photo afin de mieux juger du rendu. | **Could** | 6,5 | 50 | 35 | 10 | 5 | 0 |
| 7 | En tant qu'utilisateur, je veux pouvoir changer la couleur d'un vêtement recommandé afin de l'adapter à mes goûts. | **Could** | 2,5 | 40 | 30 | 20 | 5 | 5 |
| **Achat des articles** | | | | | | | | |
| 8 | En tant qu'utilisateur, je veux ajouter un article recommandé à mon panier afin de l'acheter plus tard. | **Must** | 1,5 | 0 | 50 | 40 | 5 | 5 |
| 9 | En tant qu'utilisateur, je veux valider mon panier et passer commande afin de finaliser mes achats. | **Must** | 1 | 0 | 50 | 40 | 5 | 5 |
| 10 | En tant qu'utilisateur, je veux payer ma commande par carte bancaire afin de terminer ma transaction en toute sécurité. | **Must** | 1 | 0 | 60 | 20 | 10 | 10 |
| 11 | En tant qu'utilisateur, je veux choisir mon mode de livraison afin de recevoir mes articles où je le souhaite. | **Should** | 1 | 0 | 50 | 40 | 5 | 5 |
| **Recommandation par Préférences** | | | | | | | | |
| 12 | En tant qu'utilisateur, je veux pouvoir définir mes styles préférés parmi une liste afin de recevoir des recommandations personnalisées. | **Should** | 2,5 | 10 | 35 | 40 | 10 | 5 |
| 13 | En tant qu'utilisateur, je veux pouvoir sélectionner mes marques préférées afin d'affiner les recommandations. | **Could** | 1,5 | 5 | 40 | 40 | 10 | 5 |
| 14 | En tant qu'utilisateur, je veux pouvoir lier mes influenceurs/blogs favoris afin que l'algorithme s'inspire des tendances que j'aime. | **Won't** | 6,5 | 50 | 30 | 5 | 10 | 5 |
| **Gestion des Données (RGPD)** | | | | | | | | |
| 15 | En tant qu'utilisateur, je veux pouvoir accéder à mes données personnelles (photos, préférences) afin de les modifier. | **Must** | 1,5 | 0 | 50 | 35 | 10 | 5 |
| 16 | En tant qu'utilisateur, je veux pouvoir supprimer mon compte et toutes mes données personnelles afin de respecter mon droit à l'oubli. | **Must** | 1,5 | 0 | 60 | 20 | 10 | 10 |
| 17 | En tant qu'utilisateur, je veux être informé de la politique de conservation de mes données et qu'elles soient purgées automatiquement après inactivité. | **Must** | 1 | 20 | 60 | 0 | 10 | 10 |
