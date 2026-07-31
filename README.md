# 🎯 Les points sur les i

[![License: AGPL v3](https://img.shields.io/badge/License-AGPL_v3-blue.svg)](https://www.gnu.org/licenses/agpl-3.0)

**Les points sur les i** est une plateforme open source d'aide à la décision et de suivi pédagogique préventif. 

Contrairement aux outils classiques de gestion de notes, cette application se concentre sur la **détection et l'agrégation des signaux faibles** (comportement, fatigue, isolement) pour permettre aux équipes éducatives de prévenir le décrochage scolaire avant qu'il ne s'installe.

---

## 💡 Philosophie du projet

Le suivi d'un élève ressemble souvent à un puzzle dont les pièces sont réparties entre de multiples intervenants (professeurs, surveillants, coordinateurs). Un signal faible isolé (un oubli de matériel, une baisse soudaine de participation) passe souvent inaperçu. 

L'objectif de ce projet est de :
1. **Offrir une saisie à "zéro friction"** pour les équipes sur le terrain (moins de 10 secondes pour remonter une observation factuelle).
2. **Croiser les données algorithmiquement** pour repérer les redondances et les ruptures de comportement.
3. **Fournir un tableau de bord clair** aux décideurs (direction, responsables de niveau) pour agir avec des faits concrets.

## ✨ Fonctionnalités Principales

* **Saisie Rapide & Objectivée :** Interface mobile/web optimisée pour une saisie via des tags standardisés (ex: *Baisse d'attention*, *Isolement*, *Devoir non rendu*), évitant la charge mentale de la rédaction libre.
* **Moteur d'Agrégation :** Détection automatique des motifs récurrents (ex: 3 alertes de fatigue par 3 professeurs différents dans la même semaine déclenchent un statut de vigilance).
* **Tableau de Bord Décisionnel :** Vue d'ensemble des statuts (Vert, Orange, Rouge) avec historique contextuel filtrable pour préparer les entretiens avec les élèves ou les parents.
* **Sécurité & RGPD By Design :** Architecture conçue pour isoler strictement les données des mineurs avec des règles d'accès au niveau de la ligne (Row Level Security).

## 🛠 Stack Technique (Architecture)

* **Frontend (Client Multiplateforme) :** Flutter (iOS, Android, Web)
* **Backend & Base de données :** Supabase (PostgreSQL)
* **Moteur d'analyse & API :** Python (FastAPI) pour la logique d'agrégation complexe.
* **Sécurité :** RLS (Row Level Security) natif via PostgreSQL.

## 🚀 Installation & Déploiement (Développement)

*(À compléter avec tes instructions spécifiques)*

1. Cloner le dépôt :
   ```bash
   git clone [https://github.com/ton-profil/les-points-sur-les-i.git](https://github.com/ton-profil/les-points-sur-les-i.git)
