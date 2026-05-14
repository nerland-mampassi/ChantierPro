# ChantierPro
CHANTIERPRO est une application web complète de gestion administrative et opérationnelle des chantiers de construction. Elle permet de centraliser et de suivre l’ensemble des activités liées aux projets, aux équipes terrain, aux stocks de matériaux et aux rapports financiers.
Voici une **description professionnelle** pour votre projet **CHANTIERPRO**, prête à être utilisée dans votre maquette, votre dossier ou votre présentation :

---

## 📌 DESCRIPTION GÉNÉRALE DU PROJET

**CHANTIERPRO** est une application web complète de gestion administrative et opérationnelle des chantiers de construction. Elle permet de centraliser et de suivre l’ensemble des activités liées aux projets, aux équipes terrain, aux stocks de matériaux et aux rapports financiers.

L’application s’adresse à trois types d’utilisateurs distincts : l’**administrateur**, le **chef de chantier** et le **magasinier**, chacun disposant d’un espace adapté à ses responsabilités.

---

## 🎯 OBJECTIFS PRINCIPAUX

- **Centraliser** la gestion des chantiers, du personnel et des stocks.
- **Automatiser** le suivi des présences, des dépenses et des demandes de matériel.
- **Faciliter** la communication entre les équipes terrain et l’administration.
- **Générer** des rapports journaliers et financiers pour un meilleur pilotage des projets.
- **Sécuriser** l’accès aux données par un système d’authentification et de gestion des rôles.

---

## 👥 RÔLES ET FONCTIONNALITÉS

### 🔵 Administrateur
- Gestion complète des chantiers (création, modification, clôture)
- Gestion du personnel (ajout, modification, suppression)
- Consultation des rapports financiers et de la paie
- Validation des demandes de matériel
- Supervision générale des stocks

### 🟢 Chef de chantier
- Recrutement et gestion des ouvriers
- Pointage quotidien des équipes
- Enregistrement des dépenses terrain
- Suivi des tâches et demandes de matériel
- Envoi d’un rapport journalier à l’administration

### 🟡 Magasinier
- Gestion des entrées et sorties de stock
- Traitement des demandes de matériel
- Consultation de l’historique des mouvements
- Génération d’un rapport de consommation par projet

---

## 🛠️ TECHNOLOGIES UTILISÉES

| Composant | Technologie |
|-----------|-------------|
| Backend | Laravel (PHP) |
| Base de données | MySQL |
| Frontend | Blade, Bootstrap, JavaScript |
| Graphiques | Chart.js |
| Authentification | Laravel Auth + Middleware rôles |
| Messagerie interne | Laravel avec modèles dédiés |

---

## 📊 APERÇU DES FONCTIONNALITÉS CLÉS

| Module | Description |
|--------|-------------|
| **Gestion des chantiers** | Création, suivi budgétaire, progression, historique |
| **Gestion du personnel** | Fiche collaborateur, rôles, statuts, salaires |
| **Gestion des ouvriers** | Recrutement par chef, pointage, calcul automatique des coûts |
| **Gestion des stocks** | Inventaire central, alertes de rupture, mouvements tracés |
| **Demandes de matériel** | Circuit complet (demande → validation → réception) |
| **Rapports** | Financiers (admin) et journaliers (chef) |
| **Messagerie** | Communication interne entre utilisateurs |

---

## 📈 BÉNÉFICES ATTENDUS

- ✅ Réduction des tâches administratives répétitives
- ✅ Meilleure traçabilité des dépenses et des présences
- ✅ Communication simplifiée entre terrain et direction
- ✅ Vision claire de l’état d’avancement des chantiers
- ✅ Centralisation des données dans une interface unique

---

## 📁 STRUCTURE DE L’APPLICATION (APERÇU)

```
CHANTIERPRO/
├── Espace Admin
│   ├── Dashboard
│   ├── Chantiers
│   ├── Personnel
│   ├── Stocks
│   ├── Rapports
│   └── Paie
├── Espace Chef
│   ├── Dashboard
│   ├── Ouvriers
│   ├── Pointage
│   ├── Dépenses
│   ├── Demandes matériel
│   └── Rapport journalier
└── Espace Magasinier
    ├── Dashboard
    ├── Demandes à traiter
    ├── Entrées stock
    └── Historique mouvements
```


