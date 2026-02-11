# Projet-criminalite-de-Los-angeles
Analyse de la criminalité à Los Angeles:  Vers une stratégie de prévention efficace
📌 Description du projet

Ce projet vise à analyser la criminalité dans la ville de Los Angeles à partir d’un dataset public contenant plus de 980 000 incidents criminels enregistrés.
L’objectif principal est de comprendre les dynamiques temporelles, spatiales et sociales du phénomène criminel et d’en dégager des pistes de prévention.

Le projet combine des méthodes statistiques, des analyses spatio-temporelles et des visualisations interactives à l’aide de Python (Jupyter) et Power BI.

🎯 Objectifs

Identifier les tendances temporelles du crime (année, saison, heure, jour).

Analyser la répartition spatiale et détecter les hotspots criminels.

Étudier le profil sociodémographique des victimes (âge, sexe, origine).

Construire des visualisations interactives pour appuyer les décisions de prévention.

Proposer des recommandations stratégiques pour une sécurité urbaine fondée sur les données.

🧩 Démarche analytique
1. Préparation et nettoyage des données

Vérification de la structure (df.info(), df.describe()), gestion des valeurs manquantes.

Création de variables dérivées : Year, Month, DayOfWeek, Season, Vict Age Group.

Normalisation et suppression des doublons.

2. Analyse exploratoire (EDA)
🔹 Analyse univariée

Étude des distributions individuelles (évolution annuelle, saisonnière, âge, sexe).
→ Objectif : identifier les tendances générales et les anomalies.

🔹 Analyse bivariée

Exploration des corrélations entre deux variables (ex. type de crime × jour).
→ Objectif : comprendre les mécanismes de concentration criminelle.

🔹 Analyse multivariée

Combinaison des dimensions temporelle, spatiale et sociale.
→ Objectif : observer la migration du crime dans le temps et dans l’espace.

🌍 Visualisations interactives
🗺️ Carte Folium (Python)

Carte dynamique illustrant la répartition géographique des crimes par année.
→ Permet de visualiser les zones à risque et leur évolution.

🔥 Heatmap Power BI

Carte de densité (latitude / longitude) mettant en évidence les hotspots criminels.
→ Facilite la planification opérationnelle et la prévention.

📊 Graphiques temporels et catégoriels

Évolution annuelle et mensuelle des crimes.

Répartition par type de crime et par zone.

Profil des victimes (âge, sexe, origine).

📈 Principaux résultats
Dimension	Observation clé	Interprétation
Temporelle	Hausse 2020–2023, pic l’été et le week-end	Influence du mode de vie urbain
Spatiale	Concentration dans Downtown et South LA	Densité et vulnérabilité socio-économique
Sociale	Jeunes hommes (20–40 ans) les plus touchés	Risques liés à mobilité et activités nocturnes
💡 Recommandations

Renforcer la présence policière dans les zones à haut risque.

Adapter la prévention aux périodes critiques (soirée, week-end, été).

Développer des programmes communautaires pour les jeunes adultes.

Exploiter la cartographie prédictive pour anticiper les zones sensibles.

⚙️ Technologies utilisées
Outil	Utilisation principale
Python (Pandas, Matplotlib, Seaborn)	Analyse exploratoire et visualisations
Folium	Cartographie interactive
Power BI	Tableau de bord et heatmaps
Jupyter Notebook	Environnement d’expérimentation
GitHub	Versionning et partage du projet
