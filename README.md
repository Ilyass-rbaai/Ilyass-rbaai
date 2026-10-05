<div align="center">

# Ilyass R'BAAI

### Data Engineering · Business Intelligence · Intelligence artificielle

Élève ingénieur en dernière année à l’EMSI, à Marrakech — je développe des pipelines de données, des rapports analytiques et des applications intégrant des modèles d’IA.

[Découvrir mes projets](#projets) · [Compétences et outils](#compétences-et-outils) · [Mon GitHub](https://github.com/Ilyass-rbaai)

[LinkedIn](https://www.linkedin.com/in/ilyass-r%E2%80%99baai-4a601b390/) · [Me contacter](mailto:ilyassrbai@gmail.com)

**Recherche de stage PFE en Data Engineering, Data Analytics ou AI Engineering**

</div>

---

## À propos

Ce portfolio rassemble mes projets publics, de l'ingestion de données à leur exploitation dans un dashboard ou une application. Mon parcours associe Python et SQL, les plateformes Azure et Databricks, Power BI, le machine learning et le développement logiciel.

Mon objectif principal est de progresser en Data Engineering : concevoir des systèmes qui relient ingestion, transformation, stockage, orchestration et analyse. Mes projets en IA et en développement logiciel complètent cette approche.

## Expériences professionnelles

**Smart Automation Technologies — Stage Data et IA**  
1er juillet au 1er septembre 2026

Conception et développement complet de **CrowdAI** : backend FastAPI, base PostgreSQL, interface Streamlit, diagnostic de risque, prédiction XGBoost et assistant conversationnel avec FAISS et Groq.

**Barid Al-Maghrib / Poste Maroc — Stage en développement web**  
1er juillet au 1er août 2025

Développement d’**EQUIPOSTE**, une application Laravel pour centraliser l’inventaire des équipements informatiques, gérer leurs affectations et importer des données Excel.

## Projets

### Data Engineering & Analytics

| Projet | Objectif et réalisation | Technologies |
| --- | --- | --- |
| [Spotify Azure Data Platform](https://github.com/Ilyass-rbaai/SpotifyAzureProject) | Pipeline de données de streaming musical : ingestion incrémentale par watermark, stockage dans un data lake, transformations Bronze/Silver/Gold et modèle analytique. | Azure SQL, Azure Data Factory, ADLS Gen2, Databricks, Delta Lake, Unity Catalog, Lakeflow/DLT, Databricks Asset Bundles |
| [BigMart Sales Pipeline](https://github.com/Ilyass-rbaai/BigMart-Sales-Pipeline) | Transformation de données commerciales brutes en tables Delta nettoyées et agrégats métier : ventes par magasin, catégorie et localisation. | Python, PySpark, Spark SQL, Databricks, Delta Lake, Unity Catalog |
| [Modern Data Pipeline](https://github.com/Ilyass-rbaai/modern-data-pipeline) | Pipeline e-commerce orchestré : extraction, validation, transformation, chargement PostgreSQL et génération de rapports SQL/CSV. | Python, Pandas, NumPy, Apache Airflow, PostgreSQL, SQLAlchemy, Docker Compose, pgAdmin |
| [Azure Data Factory Pipelines](https://github.com/Ilyass-rbaai/ADF_piplines) | Pipelines paramétrés : ingestion incrémentale, API REST avec pagination, routage de fichiers et transformations via Data Flows. | Azure Data Factory, SQL, REST API, Data Flows, Delta Lake |

### Business Intelligence

#### [Sales & Operations Analytics — Power BI](https://github.com/Ilyass-rbaai/powerbi-sales-operations-analytics)

Deux pages interactives pour comprendre les ventes et examiner le traitement des commandes.

- **Sales Overview :** ventes, commandes, clients actifs, panier moyen, atteinte des objectifs, régions et top 10 produits.
- **Orders & Payments :** dates de paiement renseignées ou absentes, délai moyen, évolution mensuelle et détail des commandes.
- **Interactions :** filtres, navigation, boutons de réinitialisation et infobulles avec effectifs.
- **Fiabilité :** contrôle des totaux, correction d'une relation de date contenant des heures, conservation des mois sans données et distinction entre objectifs globaux et sélections régionales.

**Outils :** Power BI Desktop, Power Query, DAX, Excel, modélisation en faits et dimensions.

![Vue d'ensemble des ventes](https://raw.githubusercontent.com/Ilyass-rbaai/powerbi-sales-operations-analytics/main/03_SalesOverView_visualisation.png)

![Analyse des commandes et paiements](https://raw.githubusercontent.com/Ilyass-rbaai/powerbi-sales-operations-analytics/main/04_orders%26payments_visual.png)

Les valeurs de démonstration comprennent 80 commandes, 60 avec une date de paiement et un taux d'atteinte des objectifs de 95,4 %. Une date renseignée ne prouve pas le règlement intégral d'une commande.

### Intelligence artificielle & Machine Learning

| Projet | Objectif et réalisation | Technologies |
| --- | --- | --- |
| [CrowdAI](https://github.com/Ilyass-rbaai/CrowdAI) | Prototype de crowdfunding avec diagnostic de risque par règles, prédiction de ROI et assistant conversationnel utilisant la recherche documentaire. | Python, FastAPI, PostgreSQL, Streamlit, XGBoost, Groq, FAISS, Docker |
| [AutoML — Intrusion Detection](https://github.com/Ilyass-rbaai/AutoML) | Expérimentation de modèles incrémentaux, sélection adaptative par bandits et détection de dérive, avec API et monitoring documentés. | Python, River, ADWIN, UCB1, FastAPI, Docker, Prometheus, Grafana |
| [Plant Disease Detection](https://github.com/Ilyass-rbaai/Plant-Disease-Detection) | Classification d'images de feuilles de pomme de terre : Healthy, Early Blight et Late Blight, avec interface d'upload et API de prédiction. | TensorFlow, Keras, CNN, FastAPI, NumPy, Pillow, React, Material UI, TensorFlow Serving |

Ces projets présentent des prototypes et des expérimentations. Les performances et prédictions doivent être interprétées avec les données et protocoles d'évaluation de chaque dépôt ; elles ne sont pas des garanties de fonctionnement en production.

### Développement web, mobile & desktop

| Projet | Fonctionnalités principales | Technologies |
| --- | --- | --- |
| [EQUIPOSTE](https://github.com/Ilyass-rbaai/Application_EQUIPOSTE) | Inventaire d'équipements informatiques, affectations aux bureaux, classification des machines et import de données Excel. | PHP, Laravel, Blade, modèles relationnels |
| [EmploiPublique](https://github.com/Ilyass-rbaai/Application_EmploiPublique) | Gestion des offres d'emploi, candidatures, CV et favoris. Le README décrit un client Android relié à une API Laravel. | PHP, Laravel, Sanctum, MySQL ; Java/Android documentés |
| [Système de gestion scolaire](https://github.com/Ilyass-rbaai/Systeme_gestion_scolaire) | Gestion des étudiants, enseignants, modules, inscriptions et notes, avec statistiques de suivi. | Java, Swing, JDBC, MySQL |

## Compétences et outils

**Langages de programmation :** Python, SQL, R, JavaScript, TypeScript, PHP, Java, C, C++, C#.  
**Scripts :** Shell et PowerShell.  
**Web et BI :** HTML, CSS, DAX et Power Query.  
**Fondamentaux complémentaires :** notions de Hadoop et de CI/CD.

| Domaine | Compétences pratiquées | Outils rencontrés dans les projets |
| --- | --- | --- |
| Programmation & analyse | Traitement de données, requêtes, transformations, agrégations | Python, SQL, Pandas, NumPy, Java, PHP |
| Data Engineering | ETL/ELT, orchestration, chargement incrémental, architecture Medallion, tables Delta | Azure Data Factory, ADLS Gen2, Azure SQL, Databricks, PySpark, Spark SQL, Delta Lake, Unity Catalog, Airflow |
| Business Intelligence | Modélisation dimensionnelle, mesures, KPI, contrôles de cohérence, filtres et reporting | Power BI, Power Query, DAX, Excel |
| Machine Learning | Apprentissage incrémental, dérive de concept, classification, modèles de prédiction | River, ADWIN, XGBoost, TensorFlow, Keras |
| IA conversationnelle | Recherche vectorielle et génération augmentée par récupération | Groq, FAISS, RAG |
| Applications & API | Endpoints REST, interfaces, gestion de données et authentification | FastAPI, Streamlit, React, Material UI, Laravel, Sanctum, Java Swing |
| Bases de données | Modèles relationnels, chargements et accès applicatif | PostgreSQL, MySQL, Azure SQL, SQLAlchemy, JDBC |
| Environnement & suivi | Conteneurisation, versionnement, observation de services | Docker, Docker Compose, Git, GitHub, Prometheus, Grafana, Databricks Asset Bundles |

### Outils de développement documentés

Visual Studio Code, Jupyter Notebook, Postman, Android Studio et pgAdmin apparaissent dans les ressources de mes projets. Leur utilisation dépend du projet et du composant concerné.

## Ce que ces projets m'ont appris

- Préparer des données brutes pour des usages analytiques via des étapes de nettoyage et d'agrégation.
- Concevoir des relations et KPI cohérents avec le niveau de détail des données.
- Relier un modèle de machine learning à une API et une interface utilisateur.
- Distinguer une donnée absente d'une valeur zéro et un prototype d'une solution de production.
- Documenter les architectures, limites et étapes de lancement pour rendre les projets compréhensibles.

## Explorer le portfolio

Les 11 projets sont accessibles depuis les liens de cette page. Leurs codes et ressources restent dans leurs dépôts respectifs pour éviter les copies et faciliter les mises à jour.

**Profil GitHub :** [Ilyass-rbaai](https://github.com/Ilyass-rbaai)

---

**Prochain objectif :** approfondir Kafka et Spark Structured Streaming dans un projet intégré de traitement d’événements.  
Dernière mise à jour : octobre 2026.
