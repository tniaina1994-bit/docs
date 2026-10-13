# Phase 3 — Conception

## Objectif
Transformer les besoins en spécifications détaillées, préparer le développement.

## Actions

### Conception fonctionnelle (UX/UI)
- Réaliser les **wireframes** et les **maquettes** (Figma, Adobe XD).
- Définir les **parcours utilisateurs** et le zoning.
- Valider les maquettes avec les utilisateurs métier (RH, recruteurs).
- Livrable : **Dossier de conception fonctionnelle**

### Conception technique
- **Architecture logicielle** : MVC Laravel, composants, API.
- **Modélisation de la base de données** : entités, relations, schéma UML.
- **Architecture de l'IA** : micro-service ou package Laravel dédié, flux de données, file d'attente (Laravel Queues).
- **Choix techniques** :
  - Librairies et frameworks (Livewire / Inertia.js + Vue 3 ou React).
  - API externes (OpenAI, Google Document AI) ou solution open source (Tesseract + SpaCy).
  - Conteneurisation (Docker) pour l'environnement IA.
  - Stockage S3 pour les CV.
- Livrable : **Dossier d'architecture technique (DAT)**, schéma de base de données, contrat d'API.

### Preuve de concept (POC) IA
- Valider les performances sur un échantillon de CV (ex. 50 CV).
- Mesurer le taux d'extraction correct et le temps de traitement.
- Ajuster le modèle ou l'API en fonction des résultats.

## Livrables
- Dossier de conception fonctionnelle
- Dossier d'architecture technique (DAT)
- Schéma de base de données
- Contrat d'API
- PV de validation du POC IA

## Passage à la phase suivante
- [ ] Maquettes validées par les utilisateurs métier
- [ ] Architecture technique approuvée
- [ ] POC IA validé (taux d'extraction > 85 %, latence < 30s)
- [ ] Schéma de base de données figé
- [ ] Contrat d'API défini
