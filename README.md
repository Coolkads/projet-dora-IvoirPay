# Projet DORA – Mise en conformité d'IvoirPay

Étude de cas réalisée dans le cadre de mon Master GRC : diagnostic de conformité d'un établissement de paiement au règlement européen DORA (Digital Operational Resilience Act, règlement (UE) 2022/2554) et construction de la feuille de route associée.

> IvoirPay est une entreprise fictive. Les références réglementaires sont réelles.

## Contexte

IvoirPay est une fintech de paiement agréée par l'ACPR (38 M€ de chiffre d'affaires, 4 200 marchands), très dépendante de dix prestataires informatiques. DORA s'applique depuis janvier 2025, mais aucun chantier n'avait été lancé. Une panne de son processeur de paiement en 2026 a montré que l'entreprise ne savait pas si elle devait déclarer l'incident à l'ACPR.

Dans le rôle de chargé de mission conformité DORA, j'ai mesuré les écarts avec le règlement et proposé un plan d'actions priorisé pour le comité de direction.

## Ce que j'ai réalisé

Le livrable est un classeur Excel de suivi en 9 onglets :

| Onglet | Contenu |
|---|---|
| Synthèse | Taux de conformité par pilier, écarts prioritaires, avancement du plan (calculés automatiquement) |
| Gap analysis | 45 exigences DORA évaluées (0 / 1 / 2 / N/A), écart constaté, priorité, action |
| FCI | Fonctions critiques ou importantes, notes d'impact, RTO et RPO |
| Registre | Extrait du registre d'information (ITS 2024/2956), sous-traitance, substituabilité |
| Classif incidents | Classification selon le RTS 2024/1772 et échéances de notification (4 h / 72 h / 1 mois) |
| Art30 | Revue des contrats critiques au regard de l'article 30 |
| Plan tests 2027 | Programme de tests de résilience (articles 24 et 25) |
| Plan actions | 20 actions avec responsable, échéance, charge et priorité |
| Historique | Suivi des versions |

## Principaux résultats

- Taux de conformité global de **36 %**, le plus faible sur les prestataires TIC (22 %) et les incidents (25 %)
- **6 fonctions critiques** sur 10, dont les paiements carte (RTO 1 h, RPO nul)
- **17 écarts de priorité 1** : pas de fonction de contrôle indépendante, pas de grille de classification des incidents, pas de stratégies de sortie
- Un **risque de concentration caché** : le processeur de paiement est hébergé chez le même fournisseur cloud qu'IvoirPay
- Un plan de **20 actions**, soit 192 jours-homme d'ici juin 2027

## Contenu du dépôt

- `livrables/Sujet.pdf` : énoncé du projet
- `livrables/projet.xlsx` : classeur de suivi 


## Compétences mobilisées

Analyse réglementaire · Analyse d'écarts · Analyse d'impact (BIA) · Risque fournisseurs · Gestion des incidents · Plan de remédiation · Excel avancé
