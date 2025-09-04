# 📊 Analyse du Profil de Pauvreté au Burkina Faso - EMC 2014

## 📑 Table des matières

- [🎯 Vue d'ensemble du projet](#-vue-densemble-du-projet)
  - [📋 Objectifs spécifiques](#-objectifs-spécifiques)
- [🛠️ Technologies et Méthodologies](#️-technologies-et-méthodologies)
  - [💻 Stack technique](#-stack-technique)
  - [📊 Méthodologies appliquées](#-méthodologies-appliquées)
- [📁 Structure du projet](#-structure-du-projet)
- [🎓 Compétences techniques acquises](#-compétences-techniques-acquises)
  - [📈 Analyse de données](#-analyse-de-données)
  - [🔢 Statistiques appliquées](#-statistiques-appliquées)
  - [💻 Programmation R](#-programmation-r)
  - [📊 Visualisation](#-visualisation)
- [🌍 Pertinence et Impact](#-pertinence-et-impact)
  - [🎯 Pertinence académique](#-pertinence-académique)
  - [🌟 Pertinence professionnelle](#-pertinence-professionnelle)
  - [🏛️ Pertinence institutionnelle](#️-pertinence-institutionnelle)
- [📊 Résultats clés](#-résultats-clés)
  - [🔍 Principales découvertes](#-principales-découvertes)
  - [📈 Indicateurs calculés](#-indicateurs-calculés)
- [🚀 Utilisation du projet](#-utilisation-du-projet)
  - [📋 Prérequis](#-prérequis)
  - [🔧 Exécution](#-exécution)
  - [📊 Données requises](#-données-requises)
- [👨‍💻 Auteur](#️-auteur)
  - [🎓 Contexte académique](#-contexte-académique)
- [📚 Références et Documentation](#-références-et-documentation)
- [🏆 Compétences démontrées](#-compétences-démontrées)
  - [✅ Compétences techniques](#-compétences-techniques)
  - [✅ Compétences méthodologiques](#-compétences-méthodologiques)
  - [✅ Compétences analytiques](#-compétences-analytiques)

---

## 🎯 Vue d'ensemble du projet

Ce projet constitue une **analyse approfondie de la pauvreté** au Burkina Faso basée sur l'**Enquête Modulaire et Continue (EMC) 2014**. L'objectif principal est de définir et caractériser le profil de pauvreté en utilisant des méthodes statistiques avancées et des techniques d'analyse de données complexes.

### 📋 Objectifs spécifiques
- **Détermination des seuils de pauvreté** (alimentaire et non-alimentaire)
- **Construction d'un panier de consommation** représentatif
- **Calcul des dépenses de consommation** par catégories
- **Identification des profils socio-économiques** des ménages pauvres

---

## 🛠️ Technologies et Méthodologies

### 💻 Stack technique
- **R** - Langage de programmation statistique
- **Quarto** - Documentation reproductible
- **Tidyverse** - Manipulation et visualisation de données
- **Haven** - Import/export de fichiers Stata (.dta)
- **Labelled** - Gestion des labels de variables
- **Questionr** - Analyses statistiques descriptives

### 📊 Méthodologies appliquées
- **Méthode du coût des besoins fondamentaux** (CBN)
- **Construction de panier de consommation** (90% de la consommation totale)
- **Imputation de loyer** par régression linéaire
- **Calcul de seuils de pauvreté** alimentaire et non-alimentaire
- **Analyse de données longitudinales** (4 passages d'enquête)

---

## 📁 Structure du projet

```
emc2014_TP/
├── 📊 Données sources
│   ├── emc2014_p1_*.dta          # Données Passage 1
│   ├── emc2014_p2_*.dta          # Données Passage 2
│   ├── emc2014_p3_*.dta          # Données Passage 3
│   ├── emc2014_p4_*.dta          # Données Passage 4
│   ├── emc2014_agri_*.dta        # Données agricoles
│   └── emc2014_ponderations.dta  # Pondérations
├── 📋 Documentation
│   ├── ddi-documentation-french-86.pdf
│   ├── correpondnace_unite.xlsx
│   └── correspondance.xlsx
├── 🔬 Analyse
│   └── Projet ODD (Définir le profil de pauvret).qmd
├── 📄 Résultats
│   └── Rapport_ODD_Final.docx
└── 📖 Documentation
    └── README.md
```

---

## 🎓 Compétences techniques acquises

### 📈 Analyse de données
- **Manipulation de grandes bases de données** (plus de 45 fichiers)
- **Fusion et jointure** de bases de données complexes
- **Gestion des données manquantes** et imputation
- **Calcul de variables composites** et indicateurs

### 🔢 Statistiques appliquées
- **Régression linéaire** pour l'imputation de loyer
- **Calcul de seuils de pauvreté** selon la méthode CBN
- **Analyse descriptive** multidimensionnelle
- **Pondération** des données d'enquête

### 💻 Programmation R
- **Tidyverse** : dplyr, tidyr, ggplot2
- **Manipulation de facteurs** et recodage
- **Fonctions personnalisées** et pipelines
- **Documentation reproductible** avec Quarto

### 📊 Visualisation
- **Graphiques statistiques** avec ggplot2
- **Représentations géographiques** par région
- **Tableaux de bord** interactifs

---

## 🌍 Pertinence et Impact

### 🎯 Pertinence académique
- **Application pratique** des concepts d'économie du développement
- **Maîtrise des méthodes** d'analyse de la pauvreté
- **Compétences en recherche** quantitative
- **Rédaction scientifique** et présentation de résultats

### 🌟 Pertinence professionnelle
- **Analyse de politiques publiques** et programmes sociaux
- **Évaluation d'impact** de projets de développement
- **Conseil en stratégie** pour organisations internationales
- **Recherche appliquée** dans le domaine social

### 🏛️ Pertinence institutionnelle
- **Contribution aux ODD** (Objectifs de Développement Durable)
- **Aide à la décision** pour les gouvernements
- **Base de données** pour la recherche future
- **Méthodologie reproductible** pour d'autres pays

---

## 📊 Résultats clés

### 🔍 Principales découvertes
- **Seuil de pauvreté alimentaire** : Calculé selon la méthode CBN
- **Seuil de pauvreté non-alimentaire** : Déterminé par régression
- **Taux de pauvreté national** : Estimé avec pondération appropriée
- **Profil socio-économique** des ménages pauvres

### 📈 Indicateurs calculés
- Dépenses de consommation par catégorie
- Panier de consommation représentatif
- Caractéristiques des logements
- Accès aux services de base
- Niveau d'éducation et santé

---

## 🚀 Utilisation du projet

### 📋 Prérequis
```r
# Packages R requis
install.packages(c("haven", "dplyr", "labelled", "questionr", 
                   "tidyverse", "ggplot2", "readxl", "openxlsx"))
```

### 🔧 Exécution
1. **Cloner le repository**
2. **Installer les dépendances R**
3. **Exécuter le fichier Quarto** : `Projet ODD (Définir le profil de pauvret).qmd`
4. **Consulter le rapport final** : `Rapport_ODD_Final.docx`

### 📊 Données requises
- Fichiers EMC 2014 (.dta)
- Tables de correspondance (.xlsx)
- Documentation méthodologique (.pdf)

---

## 👨‍💻 Auteur

**Boniface SAWADOGO**  
*Étudiant en Licence 3 - Analyse de données et statistiques*

### 🎓 Contexte académique
- **Formation** : Licence en Statistiques et Analyse de données
- **Spécialisation** : Économie du développement et analyse de la pauvreté
- **Méthodologie** : Approche quantitative et reproductible

---

## 📚 Références et Documentation

- **Documentation EMC 2014** : `ddi-documentation-french-86.pdf`
- **Méthode CBN** : Cost of Basic Needs approach
- **Standards internationaux** : Banque Mondiale, PNUD
- **Littérature académique** : Économie du développement

---

## 🏆 Compétences démontrées

### ✅ Compétences techniques
- [x] **Programmation R** avancée
- [x] **Analyse statistique** multivariée
- [x] **Manipulation de données** complexes
- [x] **Documentation reproductible**
- [x] **Visualisation de données**

### ✅ Compétences méthodologiques
- [x] **Méthodes d'enquête** et échantillonnage
- [x] **Calcul de seuils de pauvreté**
- [x] **Analyse de consommation**
- [x] **Imputation statistique**
- [x] **Pondération des données**

### ✅ Compétences analytiques
- [x] **Pensée critique** et analyse
- [x] **Résolution de problèmes** complexes
- [x] **Communication scientifique**
- [x] **Gestion de projet** de recherche
- [x] **Travail en autonomie**

---

*Ce projet démontre une maîtrise complète des outils et méthodes d'analyse de la pauvreté, avec une approche rigoureuse et reproductible conforme aux standards internationaux de recherche en économie du développement.*