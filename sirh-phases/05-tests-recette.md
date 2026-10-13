# Phase 5 — Tests & Recette

## Objectif
Vérifier que le produit répond aux exigences et corriger les anomalies.

## Actions

### Tests internes
- **Tests unitaires** : valider chaque fonction/méthode isolément.
- **Tests d'intégration** : valider les interactions entre composants (contrôleurs, modèles, services IA, files de queue).
- **Tests fonctionnels** : valider les parcours utilisateur complets (ex. : upload d'un CV → extraction → validation).
- **Tests de performance** : vérifier que le temps de traitement d'un CV est < 30 secondes.
- **Tests de sécurité** : audits OWASP, vérification de la conformité RGPD.

### Recette utilisateur (UAT)
- Préparer des **scénarios métier** exécutés par les RH et recruteurs.
- Organiser des sessions de recette avec les utilisateurs finaux.
- Utiliser un outil de gestion des anomalies (Jira, Redmine, GitHub Issues).
- Corriger les anomalies par ordre de priorité.
- Livrable : **PV de recette**, version *release candidate*.

### Critères d'acceptation
- Taux d'extraction automatique correct > 85 % sans retouche.
- Temps de traitement d'un CV < 30 secondes.
- Tableau des candidats alimenté automatiquement et permettant la recherche par compétence, expérience, formation.
- Adoption par les recruteurs : 100 % des nouvelles candidatures passent par l'outil.

## Livrables
- Plan de tests
- Résultats des tests automatisés
- PV de recette
- Version release candidate

## Passage à la phase suivante
- [ ] PV de recette signé par le client/sponsor
- [ ] Anomalies critiques corrigées
- [ ] Critères d'acceptation atteints
- [ ] Release candidate approuvée
