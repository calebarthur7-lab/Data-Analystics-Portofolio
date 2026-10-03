# 📊 Analyse des ventes & pilotage des stocks

## 🎯 Présentation

Ce projet consiste à concevoir un **dashboard Power BI orienté pilotage commercial et gestion des stocks**.

L’objectif est de transformer des données de ventes, d’inventaire et de satisfaction client en **indicateurs simples à exploiter**, afin de fournir à la fois une vision globale de la performance et une vue opérationnelle des produits nécessitant une attention particulière.

Le rapport est organisé autour de deux espaces complémentaires :

- **Vue Direction** : synthèse de la performance commerciale ;
- **Vue Alerte Stock** : identification des produits en situation de stock critique.

---

## 💡 Problématique métier

Comment permettre à une équipe de pilotage de :

- suivre rapidement le chiffre d’affaires ;
- mesurer l’activité commerciale ;
- suivre la satisfaction client ;
- comparer la contribution des catégories de produits ;
- analyser l’évolution du chiffre d’affaires dans le temps ;
- identifier les produits dont le niveau de stock nécessite une attention particulière ;
- disposer d’une information visuelle permettant de faciliter l’analyse et la prise de décision ?

---

## 🛠️ Technologies & compétences

| Domaine | Technologies / compétences |
|---|---|
| Business Intelligence | **Power BI** |
| Data preparation | **Power Query** |
| Calculs analytiques | **DAX** |
| Data modeling | Modèle sémantique, relations entre tables |
| Visualisation | KPI, graphiques, tableaux, mise en forme conditionnelle |
| Analyse | Performance commerciale, tendances, stocks, satisfaction |

---

## 🗂️ Modèle de données

Le modèle sémantique repose sur quatre tables principales :

- **Ventes** — transactions, dates, produits, quantités et montants ;
- **Inventaire** — produits, niveaux de stock, fréquence et date de réapprovisionnement ;
- **Avis-Clients** — retours clients et score de satisfaction ;
- **Calendrier** — dimension temporelle utilisée pour l’analyse des évolutions.

Les relations entre ces tables permettent de croiser les données commerciales, produits, clients et temporelles dans un même modèle analytique.

![Modèle sémantique](assets/modele-semantique.png)

---

## 📈 Vue Direction

La page **Vue Direction** propose une synthèse de la performance commerciale.

Les principaux KPI affichés dans le contexte analysé sont :

- **31,95 M€** de chiffre d’affaires total ;
- **50 transactions** ;
- **4,05 / 5** de score moyen de satisfaction.

Le dashboard permet également d'examiner :

- le chiffre d’affaires par catégorie de produit ;
- l’évolution mensuelle du chiffre d’affaires ;
- la performance selon la catégorie sélectionnée.

![Vue Direction](assets/vue-direction.png)

### 🔎 Premiers constats visibles dans le dashboard

Dans la vue présentée :

- les catégories **Vélo Piste** et **VTT** représentent chacune environ **6,8 M€** de chiffre d’affaires ;
- le **Vélo Randonnée** représente environ **4,7 M€** ;
- le **Vélo Enfant** représente environ **4,6 M€** ;
- le **Vélo Urbain** représente environ **4,5 M€** ;
- le chiffre d’affaires affiché passe de **16,70 M€ en avril** à **15,25 M€ en mai**, soit une baisse d’environ **1,45 M€** sur la période affichée.

Ces éléments illustrent l’intérêt du dashboard pour repérer rapidement les écarts de performance entre catégories et dans le temps.

---

## 🚨 Vue Alerte Stock

La seconde page est consacrée au **suivi des stocks critiques**.

Elle reprend les principaux indicateurs du pilotage commercial et ajoute un KPI dédié :

> **15 produits en situation de stock critique**

La page permet ensuite d’identifier les produits concernés et de consulter plusieurs informations associées :

- catégorie ;
- niveau de stock ;
- fréquence de réapprovisionnement ;
- nombre de transactions ;
- quantité vendue ;
- chiffre d’affaires ;
- score moyen de satisfaction.

![Vue Alerte Stock](assets/vue-alerte-stock.png)

### 🎯 Intérêt métier

Cette vue transforme une donnée opérationnelle — le niveau de stock — en **signal d’alerte directement exploitable**.

La mise en forme conditionnelle permet notamment de faire ressortir les niveaux de stock faibles et de faciliter le repérage des produits nécessitant une surveillance.

---

## 🔄 Démarche analytique

Le projet suit une logique de traitement de données allant de la donnée brute à la restitution métier :

```text
Sources de données
       ↓
Préparation & transformation
       ↓
Modèle sémantique
       ↓
Mesures & KPI avec DAX
       ↓
Visualisations Power BI
       ↓
Analyse des performances
       ↓
Aide au pilotage
```

Cette approche permet de séparer la préparation des données, leur modélisation et leur exploitation dans les rapports.

---

## 📊 Indicateurs suivis

| KPI / analyse | Utilité |
|---|---|
| Chiffre d’affaires total | Suivre la performance commerciale globale |
| Nombre de transactions | Mesurer le niveau d’activité |
| Satisfaction moyenne | Suivre l’expérience client |
| CA par catégorie | Comparer les contributions des catégories |
| CA mensuel | Identifier les évolutions temporelles |
| Stock critique | Repérer les produits nécessitant une attention |
| Quantité vendue | Analyser les volumes |
| Fréquence de réapprovisionnement | Suivre la dynamique d’inventaire |

---

## 🧠 Compétences mobilisées

Ce projet m’a permis de mettre en pratique plusieurs compétences clés du métier de **Data Analyst / BI Analyst** :

- conception d’un dashboard orienté métier ;
- préparation et transformation des données ;
- modélisation des données ;
- création d’indicateurs avec DAX ;
- analyse de la performance commerciale ;
- analyse temporelle ;
- suivi de la satisfaction client ;
- analyse et suivi des stocks ;
- data visualisation ;
- mise en forme conditionnelle ;
- restitution d’informations pour faciliter la prise de décision.

---

## 🚀 Pistes d’amélioration

Le projet peut être prolongé par plusieurs analyses :

- ajout d’une analyse de rentabilité / marge ;
- segmentation des clients ;
- analyse de la contribution des produits ;
- comparaison ventes / stock disponible ;
- prévision des ventes ;
- prévision des besoins de réapprovisionnement ;
- analyse plus poussée de la satisfaction ;
- automatisation de l’actualisation des données ;
- ajout d’indicateurs de performance avec objectifs et écarts.

---

## 👤 À propos

**Caleb Wanu**  
Data Analyst | Master spécialisé — Data Management & AI for Business

Je m’intéresse à la transformation des données en **insights compréhensibles et exploitables**, avec un intérêt particulier pour la Data Analysis, la Business Intelligence et les problématiques de Data Management.

---

### 📌 Projet réalisé avec

**Power BI · Power Query · DAX · Data Modeling · Data Visualization**

