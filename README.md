<div align="center">

# Ilyass R'BAAI

### Data Engineering · Business Intelligence · Intelligence artificielle

Élève ingénieur en dernière année à l’EMSI, Marrakech.<br>
Je développe des pipelines de données, des modèles analytiques et des applications intégrant l’IA.

**À la recherche d’un stage PFE en Data Engineering, Data Analytics ou AI Engineering.**

[LinkedIn](https://www.linkedin.com/in/ilyass-r%E2%80%99baai-4a601b390/) · [Contact](mailto:ilyassrbai@gmail.com) · [Projets](#projets) · [Compétences](#compétences)

</div>

---

## À propos

Mon intérêt principal est la Data Engineering : relier l’ingestion, la transformation, le stockage et l’analyse pour rendre les données exploitables. Je travaille avec Python et SQL, Azure et Databricks, ainsi que Power BI pour présenter les résultats.

Ce portfolio rassemble **12 projets publics**, avec leurs codes, ressources et documentations. Mes projets en machine learning et en développement logiciel complètent ce parcours.

## Projets

### SQL Data Warehouse & Power BI — projet à découvrir

**Objectif :** réunir des données CRM et ERP dans un entrepôt SQL, puis analyser les ventes, les produits et les clients avec Power BI.

**Parcours des données :** fichiers CSV → Bronze → Silver → Gold → Power BI.

- **Intégration :** six fichiers sources chargés dans SQL Server.
- **Transformation :** nettoyage, déduplication, standardisation et rapprochement des données CRM/ERP.
- **Modélisation :** vues Gold de clients, produits et ventes, complétées par une table Calendrier dans Power BI.
- **Analyse :** 16 mesures DAX et trois pages en français, avec filtres par année, pays et catégorie.
- **Validation :** comparaison des indicateurs SQL et DAX ; limites des données documentées.

| Lignes de ventes | Commandes distinctes | Clients actifs | Pages Power BI |
| :---: | :---: | :---: | :---: |
| 60 398 | 27 659 | 18 484 | 3 |

**Technologies :** SQL Server · T-SQL · Power BI · Power Query · DAX.

[Code et documentation](https://github.com/Ilyass-rbaai/sql-data-warehouse-project) · [Rapport Power BI](https://github.com/Ilyass-rbaai/sql-data-warehouse-project/tree/main/powerbi) · [Résultats de validation](https://github.com/Ilyass-rbaai/sql-data-warehouse-project/blob/main/powerbi/validation.md)

#### Vue d’ensemble des ventes

[![Vue d’ensemble des ventes — SQL Data Warehouse et Power BI](https://raw.githubusercontent.com/Ilyass-rbaai/sql-data-warehouse-project/main/powerbi/screenshots/01-synthese.png)](https://github.com/Ilyass-rbaai/sql-data-warehouse-project)

<details>
<summary>Voir les pages Produits et Clients</summary>

#### Performance des produits

![Performance des produits](https://raw.githubusercontent.com/Ilyass-rbaai/sql-data-warehouse-project/main/powerbi/screenshots/02-produits.png)

#### Analyse des clients

![Analyse des clients](https://raw.githubusercontent.com/Ilyass-rbaai/sql-data-warehouse-project/main/powerbi/screenshots/03-clients.png)

</details>

Le Data Warehouse s’appuie sur le tutoriel de **Data With Baraa**, prolongé par un rapport Power BI en français. Les données sont des données d’exemple ; la devise n’est pas précisée et certaines années sont partielles.

### Data Engineering & Analytics

| Projet | Réalisation | Technologies principales |
| --- | --- | --- |
| [Spotify Azure Data Platform](https://github.com/Ilyass-rbaai/SpotifyAzureProject) | Ingestion incrémentale par watermark, data lake, transformations Bronze/Silver/Gold et modèle analytique. | Azure Data Factory, ADLS Gen2, Azure SQL, Databricks, Delta Lake, Unity Catalog |
| [Modern Data Pipeline](https://github.com/Ilyass-rbaai/modern-data-pipeline) | Pipeline e-commerce orchestré : extraction, validation, transformation, chargement PostgreSQL et rapports SQL/CSV. | Python, Pandas, Airflow, PostgreSQL, Docker Compose |
| [BigMart Sales Pipeline](https://github.com/Ilyass-rbaai/BigMart-Sales-Pipeline) | Nettoyage de données commerciales, tables Delta et agrégats par magasin, catégorie et localisation. | PySpark, Spark SQL, Databricks, Delta Lake |
| [Azure Data Factory Pipelines](https://github.com/Ilyass-rbaai/ADF_piplines) | Ingestion incrémentale, appels REST avec pagination, routage de fichiers et transformations Data Flows. | Azure Data Factory, SQL, REST API, Data Flows |

### Business Intelligence

#### [Sales & Operations Analytics — Power BI](https://github.com/Ilyass-rbaai/powerbi-sales-operations-analytics)

Rapport interactif construit à partir d’un jeu de données Excel pour analyser les ventes et le suivi des commandes.

- **Sales Overview :** ventes, commandes, clients actifs, panier moyen, objectifs, régions et top 10 produits.
- **Orders & Payments :** dates de paiement renseignées ou absentes, délais et détail des commandes.
- **Interactions :** filtres, navigation, réinitialisation et infobulles.
- **Contrôles :** cohérence des totaux, relations de dates et interprétation des objectifs selon les filtres.

**Technologies :** Power BI · Power Query · DAX · Excel.

[![Sales & Operations Analytics — aperçu](https://raw.githubusercontent.com/Ilyass-rbaai/powerbi-sales-operations-analytics/main/03_SalesOverView_visualisation.png)](https://github.com/Ilyass-rbaai/powerbi-sales-operations-analytics)

<details>
<summary>Voir l’analyse des commandes et paiements</summary>

![Analyse des commandes et paiements](https://raw.githubusercontent.com/Ilyass-rbaai/powerbi-sales-operations-analytics/main/04_orders%26payments_visual.png)

Le jeu de démonstration contient 80 commandes, dont 60 avec une date de paiement. Une date renseignée ne prouve pas le règlement intégral d’une commande.

</details>

### Intelligence artificielle & Machine Learning

| Projet | Réalisation | Technologies principales |
| --- | --- | --- |
| [CrowdAI](https://github.com/Ilyass-rbaai/CrowdAI) | Prototype de crowdfunding : diagnostic de risque, prédiction de ROI et assistant avec recherche documentaire. | FastAPI, PostgreSQL, Streamlit, XGBoost, FAISS, Groq |
| [AutoML — Intrusion Detection](https://github.com/Ilyass-rbaai/AutoML) | Expérimentation de modèles incrémentaux, sélection adaptative par bandits et détection de dérive. | Python, River, ADWIN, UCB1, FastAPI |
| [Plant Disease Detection](https://github.com/Ilyass-rbaai/Plant-Disease-Detection) | Classification d’images de feuilles de pomme de terre avec API et interface d’envoi d’images. | TensorFlow, Keras, CNN, FastAPI, React |

Les dépôts détaillent les données et les évaluations de ces prototypes.

### Développement logiciel

| Projet | Réalisation | Technologies principales |
| --- | --- | --- |
| [EQUIPOSTE](https://github.com/Ilyass-rbaai/Application_EQUIPOSTE) | Inventaire informatique, affectation des équipements aux bureaux et import Excel. | PHP, Laravel, Blade |
| [EmploiPublique](https://github.com/Ilyass-rbaai/Application_EmploiPublique) | Offres d’emploi, candidatures, CV et favoris ; API pour un client Android décrit dans le dépôt. | Laravel, Sanctum, MySQL |
| [Système de gestion scolaire](https://github.com/Ilyass-rbaai/Systeme_gestion_scolaire) | Gestion des étudiants, enseignants, modules, inscriptions et notes. | Java, Swing, JDBC, MySQL |

## Compétences

| Domaine | Compétences mises en pratique | Outils |
| --- | --- | --- |
| Data Engineering | ETL/ELT, orchestration, ingestion incrémentale, architecture Bronze/Silver/Gold | Python, SQL, Azure Data Factory, ADLS Gen2, Databricks, PySpark, Delta Lake, Airflow |
| Business Intelligence | Modélisation dimensionnelle, mesures DAX, filtres, reporting, validation SQL | SQL Server, Power BI, Power Query, DAX, Excel |
| Machine Learning & IA | Classification, prédiction, apprentissage incrémental, dérive, recherche vectorielle | TensorFlow, Keras, XGBoost, River, FAISS, Groq |
| Applications & bases de données | API REST, interfaces, modèles relationnels et accès aux données | FastAPI, Streamlit, Laravel, React, PostgreSQL, MySQL, JDBC |
| Environnement de développement | Versionnement, conteneurs, notebooks et observation de services | Git, GitHub, Docker, Jupyter, Prometheus, Grafana |

<details>
<summary>Autres langages et outils de mon parcours</summary>

Python, SQL, R, JavaScript, TypeScript, PHP, Java, C, C++, C#, HTML, CSS, Shell et PowerShell. Notions de Hadoop et de CI/CD.

Outils de développement : Visual Studio Code, Jupyter Notebook, Postman, Android Studio et pgAdmin.

</details>

## Expériences professionnelles

### Smart Automation Technologies — Stage Data et IA

**Juillet – septembre 2026**

Développement de **CrowdAI** : backend FastAPI, base PostgreSQL, interface Streamlit, diagnostic de risque, prédiction XGBoost et assistant conversationnel avec FAISS et Groq.

### Barid Al-Maghrib / Poste Maroc — Stage en développement web

**Juillet – août 2025**

Développement d’**EQUIPOSTE**, une application Laravel pour centraliser l’inventaire des équipements informatiques, gérer les affectations et importer des données Excel.

## Contact

Je recherche un stage PFE pour contribuer à des projets de données et approfondir mes compétences en Data Engineering, Analytics ou IA.

[LinkedIn](https://www.linkedin.com/in/ilyass-r%E2%80%99baai-4a601b390/) · [ilyassrbai@gmail.com](mailto:ilyassrbai@gmail.com)

---

Dernière mise à jour : octobre 2026.
