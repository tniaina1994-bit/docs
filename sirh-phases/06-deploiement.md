# Phase 6 — Déploiement & Mise en production

## Objectif
Livrer l'application dans l'environnement cible, former les utilisateurs, basculer.

## Actions

### Préparation de la production
- Configurer le **serveur de production** (cloud AWS, OVH, DigitalOcean).
- Définir les **variables d'environnement** (fichier `.env` de production).
- Configurer les **certificats SSL** (HTTPS).
- Mettre en place le **stockage S3** pour les CV.
- Configurer les **files de queue** (Laravel Queues) pour le traitement asynchrone des CV.

### Migration de données
- Reprise de l'existant si nécessaire (import des données RH existantes).
- Vérification de l'intégrité des données migrées.

### Stratégie de déploiement
- Choisir une stratégie : blue/green, canary release.
- Planifier la fenêtre de déploiement (ex. : nuit, week-end).
- Préparer un **plan de rollback** en cas de problème.

### Formation & communication
- Organiser des sessions de **formation** pour les recruteurs et les RH.
- Rédiger des **manuels utilisateur** et une FAQ.
- Communiquer sur le lancement (annonce, supports).

### Documentation d'exploitation
- Rédiger la documentation d'exploitation (procédures de sauvegarde, monitoring, gestion des incidents).

## Livrables
- Application en production
- Documentation d'exploitation
- Guides utilisateur
- Plan de rollback

## Passage à la phase suivante
- [ ] Application déployée et accessible
- [ ] Données migrées et vérifiées
- [ ] Formations effectuées
- [ ] Documentation d'exploitation remise
- [ ] Communication réalisée
