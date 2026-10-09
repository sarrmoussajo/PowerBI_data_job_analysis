# PowerBI_data_job_analysis

# 📊 Dashboard des Métiers de la Data – Projet Power BI

Bienvenue ! Ce dépôt présente mon premier projet Power BI : un **dashboard interactif de deux pages** qui analyse le marché de l'emploi dans les métiers de la data (Data Analyst, Data Scientist, Data Engineer…) à partir d'offres d'emploi réelles publiées en 2024.

Ce projet a été réalisé dans le cadre du cours gratuit **[Power BI for Data Analytics](https://www.youtube.com/watch?v=FwjaHCVNBWA)** de [Luke Barousse](https://www.linkedin.com/in/luke-b).

![Power BI for Data Analytics](Resources/images/0_PowerBI_Thubmnail.png)

---

## 🎯 Objectif du projet

Répondre à des questions concrètes que se pose toute personne qui souhaite travailler dans la data :

- 💼 Quels sont les métiers de la data les plus demandés ?
- 💰 Quels salaires peut-on espérer selon le poste ?
- 🛠️ Quelles compétences (SQL, Python, Excel, Power BI…) sont les plus recherchées ?
- 🌍 Où se trouvent les offres, et quelle part est en télétravail ?
- 🎓 Les employeurs exigent-ils un diplôme ou une assurance santé est-elle proposée ?



---
![Projet 1 – Vue d'ensemble](/Resources/images/Project1_Dashboard_Overview.gif)
## 🖥️ Aperçu du dashboard

### Page 1 – Vue d'ensemble du marché
Une vue globale des offres d'emploi : nombre d'offres, salaires médians, répartition par type de poste, localisation et tendance mensuelle.

![Page 1 – Vue d'ensemble](/Resources/images/Project1_Dashboard_Page1.gif)

### Page 2 – Analyse détaillée (drill-through)
Une page d'exploration accessible par **drill-through** : en cliquant sur un métier depuis la page 1, on accède au détail de ce poste (compétences demandées, salaires, entreprises qui recrutent…).

![Page 2 – Drill-through](/Resources/images/Project1_Dashboard_Page2.gif)

---

## ✨ Fonctionnalités principales

| Fonctionnalité | Description |
|---|---|
| 📈 **Cartes KPI** | Nombre d'offres, salaire médian annuel et horaire, part du télétravail |
| 🔍 **Drill-through** | Navigation de la vue globale vers le détail d'un métier |
| 🎛️ **Filtres interactifs** | Segments (slicers) par métier, pays, période, type de contrat |
| 📊 **Visuels variés** | Graphiques en barres, courbes, cartes géographiques, matrices, jauges |
| 🔄 **Interactions croisées** | Un clic sur un visuel filtre automatiquement les autres |

---

## 🛠️ Compétences mises en pratique

- **Power Query** : import, nettoyage et transformation des données (ETL)
- **Modélisation des données** : relations entre tables
- **DAX** : création de mesures (médianes, ratios, comptages)
- **Data visualisation** : choix des visuels adaptés, mise en forme, cohérence graphique
- **Storytelling** : construction d'un rapport lisible, de la vue d'ensemble vers le détail

---

## 📂 Structure du dépôt

```
📁 Projet_1.0/
├── 📊 Data_Jobs_Dashboard_1.0.pbix      # Fichier Power BI du dashboard
📁 Projet_2.0/
├── 📊 Data_Jobs_Dashboard_2.0.pbix      # Fichier Power BI du dashboard
📁 Data/
│   └── 📄 job_postings_flat.csv     # Données des offres d'emploi 2024
📁 Resources/
│   └── 📁 images/                   # Captures d'écran du dashboard
📄 README.md
```

---

## 📊 Source des données

Les données proviennent d'**offres d'emploi réelles dans les métiers de la data publiées en 2024**, collectées et mises à disposition par Luke Barousse pour son cours.

Chaque ligne correspond à une offre et contient notamment : l'intitulé du poste, l'entreprise, la localisation, le salaire (annuel ou horaire), les compétences demandées, le télétravail, l'exigence de diplôme et la date de publication.

---

## 💡 Ce que j'ai appris
Ce projet m'a permis de mener une analyse de bout en bout : partir de données brutes, les nettoyer et les modéliser, puis les transformer en un rapport interactif prêt à être partagé.

- 📊 Choisir le bon visuel : j'ai exploré l'ensemble des types de graphiques proposés par Power BI et appris à sélectionner celui qui met le mieux en valeur chaque type de donnée (évolution, comparaison, répartition, géographie).
- 🔍 Guider l'utilisateur : la mise en place du drill-through et des bookmarks m'a appris à concevoir une navigation fluide, de la vue d'ensemble jusqu'au détail.
- 🧮 Calculer avec DAX : l'écriture de mesures m'a fait comprendre comment produire des indicateurs fiables et dynamiques qui réagissent aux filtres.

Au-delà de la technique, ce projet m'a appris à penser comme un analyste : partir des questions métier pour construire un dashboard clair et utile.

---

## 🙏 Crédits

- **Formateur** : [Luke Barousse](https://www.linkedin.com/in/luke-b)
- **Productrice du cours** : [Kelly Adams](https://www.linkedin.com/in/kellyjianadams)
- **Montage vidéo** : [Brannon Linder](https://www.linkedin.com/in/brannonlinder)
- **Cours complet** : [Power BI for Data Analytics – YouTube](https://www.youtube.com/watch?v=FwjaHCVNBWA)

---


⭐ *Si ce projet vous a été utile, n'hésitez pas à laisser une étoile sur le dépôt !*
