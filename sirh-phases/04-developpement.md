# Phase 4 — Développement / Implémentation

## Objectif
Coder les fonctionnalités par itérations, en respectant les normes de qualité.

## Actions

### Environnement de développement
- Mettre en place le **dépôt Git** (GitHub, GitLab, etc.).
- Configurer l'**intégration continue** (CI/CD) : GitHub Actions / GitLab CI.
- Définir les **règles de codage** (PSR-12, Laravel Pint).
- Configurer les outils de qualité : PHPStan, tests automatisés.

### Itérations (sprints)
Découper le développement en sprints (ex. 2 semaines) :

**Sprint 1 — Module Employés**
- Migrations, modèles, contrôleurs Laravel.
- CRUD employés, historique de poste, documents, organigramme.

**Sprint 2 — Module Recrutement (base)**
- Publication d'offres.
- Dépôt de candidatures (formulaire en ligne, envoi par email, import en masse).

**Sprint 3 — Module IA (scan CV)**
- Upload CV → File de queue → Service IA → Résultat en base → Notification.
- Interface de correction / validation humaine.
- Moteur d'extraction (API OpenAI / Google Document AI / solution open source).

**Sprint 4 — Module IA (matching & tableau des talents)**
- Répertoire des talents filtrable et triable.
- Matching automatique candidat/offre (scoring, suggestions).
- Pipeline de suivi des candidatures (nouveau, entretien, offre, refus), emails automatiques.

**Sprint 5 — Modules RH classiques**
- Congés & absences, temps de travail, formations, entretiens.
- Tableaux de bord et statistiques.

**Sprint 6 — Administration & sécurité**
- Gestion des rôles et permissions.
- Authentification multi-facteurs.
- Chiffrement des données sensibles.
- Conformité RGPD.

### Qualité
- Revues de code systématiques.
- Tests unitaires et d'intégration automatisés (PHPUnit, Pest).
- Respect des principes SOLID et du TDD si applicable.

## Livrables
- Code source fonctionnel
- Documentation technique
- Tests automatisés

## Passage à la phase suivante
- [ ] Tous les sprints validés par le Product Owner
- [ ] Couverture de tests suffisante
- [ ] Code reviewée et mergée
- [ ] Documentation technique à jour
