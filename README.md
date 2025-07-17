# 📊 Moulinette Inventaire - Gestion Automatisée des Stocks de Production

---

## 🚀 Contexte du Projet
Aujourd’hui, le traitement des inventaires de production est **manuel**, chronophage, et source d’erreurs.  
Ce projet vise à automatiser le **traitement des inventaires mensuels** via une application web simple et intuitive.  
Objectif : **gain de temps**, **réduction des erreurs humaines**, **suivi clair des écarts de stock**.

---

## 🛠️ Stack Technique
- **Backend** : Python + Flask  
- **Frontend** : Vue.js  
- **Base de Données** : MySQL  
- **Librairies clés** : Pandas, OpenPyXL, XlsxWriter  
- **Hébergement** : Serveur interne  
- **Outils Agile** : Scrum

---

## 📅 Organisation du projet - Méthodologie **SCRUM**

### 🔥 Sprint 0 : Préparation
- Rédaction du **cahier des charges**
- Constitution du **Product Backlog initial**
- Mise en place des **outils** (Git, Jira/Trello, Notion, etc.)

---

### 🏃‍♂️ Sprints prévus (2 semaines / sprint)

| Sprint      | Objectifs Principaux                              |
|-------------|----------------------------------------------------|
| **Sprint 1** | Authentification / Import CSV / Validation format   |
| **Sprint 2** | Agrégation données / Génération fichier Excel       |
| **Sprint 3** | Réimport fichier / Calcul écarts / Répartition lots |
| **Sprint 4** | Génération fichier final / Dashboard simple         |
| **Sprint 5** | Historique / Exports / Finalisation du MVP          |

---

### 🔄 Rituels Scrum
- **Daily Scrum** : 15 minutes / jour
- **Sprint Planning** : Définir les priorités du sprint
- **Sprint Review** : Démo des nouvelles fonctionnalités
- **Sprint Retrospective** : Identifier les axes d’amélioration

---

## 📋 Product Backlog (extraits clés)

- Authentification simple
- Import de fichiers CSV
- Validation des formats
- Agrégation des quantités par codeArticle
- Génération de fichiers Excel pour saisie manuelle
- Réimport de fichiers corrigés
- Calcul d’écarts + logique de correction par ancienneté de lots
- Dashboard de suivi
- Historique et exports des rapports

---

## ✅ Critères de Succès (Definition of Done)
- Le traitement complet d’un inventaire se fait en moins de 10 minutes
- Tous les fichiers générés sont exploitables et conformes
- Les erreurs utilisateur sont systématiquement anticipées et traitées
- L’interface est claire et exploitable par un utilisateur non technique
- La logique d’écart respecte les consignes de priorisation des lots

---

## 🗂️ Arborescence du Projet (exemple)
```bash
    moulinette-inventaire/
  ├── backend/
  │ ├── app.py
  │ ├── services/
  │ ├── models/
  │ └── utils/
  ├── frontend/
  │ ├── components/
  │ ├── views/
  │ └── store/
  ├── database/
  │ └── schema.sql
  ├── docs/
  │ ├── cahier-des-charges.pdf
  │ └── user-guide.md
  └── README.md
```


---

## 🎨 Design attendu
- Interface **épurée**, **professionnelle**, pensée entreprise
- Tableaux interactifs et graphiques clairs
- Dashboard centralisé, ergonomique

---

## 📄 Documentation attendue en livraison
- **Guide utilisateur**
- **Documentation technique**
- **Changelog / Historique des Sprints**

---

## 📌 Livrables clés (MVP)
1. Application Web opérationnelle
2. Gestion automatisée complète des inventaires
3. Tableau de bord de suivi des écarts
4. Exports Excel et historiques exploitables

---

## 🔮 Phase 2 (à planifier)
- Support des fichiers XML
- Notifications automatiques d’anomalies
- Reporting avancé (PDF / Email)
- Améliorations UX/UI

---

> _« On n’attend pas que le stock soit parfait pour avancer. On automatise, on mesure, on ajuste, et on progresse. »_ 🚀
