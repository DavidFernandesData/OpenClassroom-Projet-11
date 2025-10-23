🐔 Étude de marché internationale — La Poule qui Chante
🌍 Contexte du projet

La Poule qui Chante est une entreprise française spécialisée dans l’élevage et la commercialisation de poulets sous le label “Poulet Agriculture Biologique”.
Jusqu’à présent, son activité est concentrée sur le marché français.

Son PDG, Patrick, souhaite désormais évaluer les opportunités d’expansion à l’international et identifier les pays les plus pertinents pour y développer son activité.

Afin de guider cette décision stratégique, j’ai été mandaté en tant que Data Analyst consultant pour réaliser une étude de marché mondiale basée sur des données économiques, politiques et sociales.

🎯 Objectifs du projet

Identifier des groupes de pays homogènes selon leurs caractéristiques socio-économiques et politiques.

Déterminer les zones prioritaires où l’entreprise pourrait s’implanter efficacement.

Fournir des recommandations stratégiques basées sur une analyse de données fiable et transparente.

Produire une présentation claire et non technique, adaptée à un public de direction.

🧩 Données utilisées

Les données proviennent principalement de sources ouvertes et fiables :

FAO (Food and Agriculture Organization) : données agricoles et alimentaires.

Banque mondiale : PIB, croissance, urbanisation, utilisation d’Internet.

World Governance Indicators : stabilité politique et qualité des institutions.

Données internes nettoyées et fusionnées dans un jeu final df_merged_clean.csv.

Indicateurs clés retenus :

Population totale

Disponibilité alimentaire

Stabilité politique

Urbanisation

Croissance démographique

Utilisation d’Internet

Surface agricole

Croissance du PIB

PIB par habitant

Facilité d’importation

Les données couvrent plus de 100 pays représentant environ 60 % de la population mondiale.

🧠 Méthodologie
1. Prétraitement et préparation des données

Nettoyage, harmonisation et fusion des différentes sources.

Vérification de la cohérence et du format des variables.

Standardisation des valeurs (z-scores) pour comparabilité.

Suppression de valeurs aberrantes (notamment Chine et Inde, trop influentes).

2. Analyse exploratoire

Étude statistique descriptive des variables.

Identification de corrélations et des profils de pays.

Visualisations : cartes, nuages de points, heatmaps.

3. Réduction de dimension : Analyse en composantes principales (ACP)

Visualisation du cercle des corrélations.

Analyse de la variance expliquée (méthode du coude).

Projection des pays sur les axes factoriels.

Interprétation des composantes principales.

4. Segmentation : CAH puis K-Means

CAH (Classification ascendante hiérarchique) pour détecter la structure naturelle des pays.

K-Means pour obtenir des clusters stables et compacts.

Test de plusieurs k avec le Silhouette Score pour valider le nombre optimal.

Comparaison entre résultats CAH et K-Means.

5. Analyse et interprétation des clusters

Calcul des centroïdes et des statistiques descriptives par cluster.

Profilage des groupes : pays développés, émergents, vulnérables, etc.

Création d’un ranking “neutre” basé sur les indicateurs standardisés pour prioriser les pays.

📊 Résultats et enseignements

Cinq profils de pays ont été identifiés :

🌱 Pays à fort potentiel agricole émergent

💰 Économies développées à marché saturé

🌍 Nations en transition

🚧 Pays vulnérables ou instables

🌾 Marchés intermédiaires en croissance durable

L’analyse révèle une forte corrélation entre :

la stabilité politique et la facilité d’importation ;

le niveau d’urbanisation et l’accès aux technologies.

Les pays à fort potentiel pour “La Poule qui Chante” sont ceux combinant :

stabilité politique,

pouvoir d’achat croissant,

forte disponibilité agricole,

besoins en modernisation de la filière biologique.

💡 Recommandations stratégiques
1. Ciblage des marchés

Prioriser les pays du cluster 1 (émergents stables) comme premières cibles d’expansion.

Éviter les marchés du cluster 4 (instables) malgré leur demande potentielle.

2. Approche commerciale différenciée

Développer des partenariats agricoles locaux dans les pays à fort potentiel.

Adapter les stratégies marketing selon le niveau de développement et la culture alimentaire.

3. Suivi et monitoring

Mettre en place un tableau de bord de veille économique pour suivre les indicateurs clés.

Actualiser régulièrement l’analyse pour s’adapter aux évolutions politiques et économiques.

🧰 Outils utilisés

Python (Jupyter Notebook) : nettoyage, ACP, CAH, K-Means, visualisations (Matplotlib / Seaborn).

Excel : vérification manuelle et consolidation initiale.

PowerPoint : présentation au COMEX.

Power BI / Tableau (optionnel) : visualisations interactives.

🧑‍💻 Compétences démontrées

Intégration et harmonisation de données multi-sources.

Application d’une ACP et d’un clustering (CAH & K-Means).

Interprétation statistique et business des résultats.

Construction d’indicateurs synthétiques et de classements pertinents.

Communication claire des analyses auprès d’un public non technique.

📎 Livrables

df_merged_clean.csv : base de données finale harmonisée.

notebook_preparation_nettoyage.ipynb : traitement des données.

notebook_acp_clustering.ipynb : analyses ACP + K-Means + CAH.

slides_presentation_COMEX.pptx : synthèse des résultats et recommandations.

👤 Auteur

David Fernandes
Data Analyst - OpenClassrooms
