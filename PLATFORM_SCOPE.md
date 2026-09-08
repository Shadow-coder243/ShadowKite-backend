# ShadowKite Backend — Laravel

Ce dépôt contient uniquement le socle Laravel initialisé pour l’API et les services backend de ShadowKite. Il ne contient pas encore les modèles métier, les migrations finales, les endpoints fonctionnels ni les règles d’accès définitives.

## Responsabilité

Le backend Laravel prendra en charge l’authentification, les comptes, les profils, les CV, les formations, les expériences, les compétences, les langues, les certifications, les projets, la publication du portfolio, les URL publiques, les permissions, la validation, la sécurité, les sauvegardes et le contrat d’API consommé par Angular et Flutter.

## Tâches principales du backend

- [ ] Définir le contrat API et la stratégie d’authentification.
- [ ] Préparer la connexion à Neon et les variables d’environnement documentées.
- [ ] Concevoir le schéma des utilisateurs, profils, CV, projets et préférences.
- [ ] Définir les migrations, modèles, relations, ressources et validations.
- [ ] Implémenter les comptes, permissions, visibilité et URL publiques.
- [ ] Préparer l’upload contrôlé des médias et la génération/export PDF.
- [ ] Ajouter les tests d’API, contrôles d’accès, limitation d’abus et sauvegardes.
- [ ] Publier la documentation du contrat consommé par Angular et Flutter.
- [ ] Reporter les tâches transversales 1 à 80 dans `PROJECT_TASKS.md` et cocher uniquement les livrables réellement terminés.

## Socle initialisé

Le projet est généré avec Laravel et PHP. Les dépendances et la configuration de production restent à finaliser par l’équipe ; cette initialisation n’ajoute pas de logique métier.

## À ne pas faire dans cette initialisation

Ne pas créer les tables finales, ne pas exposer de routes métier, ne pas configurer de secrets réels et ne pas connecter Neon à un environnement de production avant validation de l’architecture et des accès.
