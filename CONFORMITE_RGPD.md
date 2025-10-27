# Registre de Traitement (RGPD) - Synthèse

Synthèse du registre de traitement pour la fonctionnalité d'analyse de photos.

* **Finalité Principale :** Fournir des recommandations personnalisées de produits basées sur le style vestimentaire analysé sur une photo.

* **Données Traitées :**
    * Photos/Images de l'utilisateur.
    * Données dérivées par l'algorithme (ex: style, couleur dominante).
    * Préférences utilisateur (avis sur les recommandations).

* **Statut des Données :** Les photos téléchargées sont considérées comme des **données sensibles** car elles peuvent contenir des caractéristiques physiques identifiables (visage, morphologie).

* **Base Légale :** Consentement explicite de l'utilisateur lors du téléchargement.

* **Personnes Concernées :** Clients / Utilisateurs de l'application.

* **Destinataires des Données :**
    * Service interne (Équipe Data Science).
    * Sous-traitant (Hébergeur cloud, ex: Microsoft Azure).

* **Durée de Conservation :** 3 ans après la dernière activité de l'utilisateur, puis suppression automatique.

* **Mesures de Sécurité :**
    * Pseudonymisation des données pour l'entraînement.
    * Chiffrement du stockage des données sur Azure.
    * Gestion des accès restreinte à l'équipe Data Science.
