🎯 Objectif de la mission

Proposer une analyse des groupements de pays à cibler pour l’exportation de poulets, en te basant sur les données de la FAO et en utilisant des méthodes de clustering (CAH, k-means) avec éventuellement une ACP pour visualiser les résultats.

⸻

✅ Étapes recommandées

1. 📦 Collecte & compréhension des données
	•	Ouvre et explore les données de la FAO fournies (en pièce jointe).
	•	Identifie les variables clés : production, consommation, importations, exportations de volaille, prix, population, etc.
	•	Si besoin, complète avec d’autres données sur le site de la FAO (critères PESTEL possibles : données économiques, démographiques, politiques…).

2. 🧼 Préparation et nettoyage
	•	Nettoie les données : gestion des valeurs manquantes, doublons, noms de pays, formats…
	•	Standardise les données (normalisation ou standardisation) pour le clustering.

3. 📊 Analyse exploratoire (EDA)
	•	Analyse univariée et bivariée (distributions, corrélations, outliers, etc.).
	•	Visualise les variables importantes par pays pour détecter des patterns.

4. 🌲 CAH (Classification Ascendante Hiérarchique)
	•	Calcule une matrice de distance (souvent euclidienne).
	•	Utilise un dendrogramme pour visualiser les regroupements.
	•	Décide du nombre optimal de clusters (ruptures dans le dendrogramme).

5. 🔘 K-means
	•	Choisis un nombre de clusters (issu de la CAH ou par la méthode du coude / silhouette).
	•	Exécute le clustering k-means.
	•	Analyse les centroïdes : profils types de chaque groupe.
	•	Visualise les clusters (avec ACP si possible).

6. 🔍 Analyse en Composantes Principales (ACP)
	•	Réduit la dimension pour :
	•	Visualiser les pays dans l’espace des composantes.
	•	Visualiser les clusters obtenus.
	•	Mieux comprendre les variables qui expliquent les regroupements.

⸻

📁 Organisation des livrables

1. 📓 Notebook ou script principal

Un notebook clair, structuré avec ces sections :

1. Chargement des données
2. Préparation et nettoyage
3. Analyse exploratoire
4. CAH (visualisation + interprétation)
5. K-means (choix du k, clustering, interprétation)
6. ACP (si réalisée)
7. Conclusion / Recommandations
2. 📊 Présentation

Un support vulgarisé (PowerPoint, Google Slides, PDF) avec :
	•	Le contexte du projet
	•	Ta démarche (approche pédagogique)
	•	Les résultats visuels (graphiques, cartes, clusters…)
	•	Une recommandation stratégique sur les pays/groupes à cibler

⸻

💡 Conseils bonus
	•	Pense à créer un profil-type de pays par cluster.
	•	Mets en évidence les critères discriminants entre les clusters.
	•	Si tu as le temps, explore un classement des pays par attractivité (score composite, ranking…).
	•	Prépare une slide “next steps” pour montrer ta vision d’un approfondissement de l’analyse.