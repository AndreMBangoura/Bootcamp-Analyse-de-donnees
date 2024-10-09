# 📊 Projet Dat’Assur Habitation

## 📋 Contexte
Le projet **Dat’Assur Habitation** est conduit par la société **Dat’Assur**, spécialisée dans l’assurance habitation pour les particuliers. L’objectif principal est d’analyser le portefeuille de contrats actuels afin de revoir la politique tarifaire de l’entreprise et de se démarquer de la concurrence grâce à une approche **"Data-Driven"**. L’objectif est de standardiser les tarifs pour offrir des prix compétitifs et lisibles selon le profil du client et la localisation des biens.

## 🎯 Objectifs du projet
1. **Créer une base de données unifiée** contenant les informations sur les contrats d’assurance actuels et leur répartition géographique.
2. **Analyser le portefeuille** pour identifier les différences de tarification en fonction des régions, du type de bien (maison/appartement) et du statut (propriétaire/locataire).
3. **Standardiser la politique tarifaire** pour proposer une stratégie de prix plus lisible et cohérente.
4. **Créer des rapports et présentations** pour exposer les résultats et la méthodologie.

## 🏗️ Structure de la base de données
La base de données est nommée **`DATAssur`** et contient deux tables principales :

- **Table `Contrats`** :
  - Informations sur les contrats d’assurance.
  - **Colonnes principales** : `Contrat_ID`, `Type_Contrat`, `Surface`, `Formule`, `Valeur_Biens`, `Prix_Cotisation`.

- **Table `Regions`** :
  - Informations sur les régions géographiques où les contrats sont répartis.
  - **Colonnes principales** : `Region_ID`, `Nom_Region`.

Les fichiers CSV d’origine utilisés pour charger les données sont **`Contrat.csv`** et **`Region.csv`**.

## 🚀 Plan d’actions et Analyses Réalisées
Le plan d’actions initial inclut les analyses suivantes :

### 🔍 Analyses SQL

1. **Contrats à Caen** : Lister les numéros de contrat (`CONTRAT_ID`) avec leur surface pour la commune de Caen.
2. **Contrats en Saône-et-Loire** : Lister les numéros de contrat avec le type de contrat et leur formule pour les maisons du département de la Saône-et-Loire (`Département 71`).
3. **Liste des Régions** : Lister le nom des régions de France.
4. **Nombre total de contrats** : Nombre total de contrats sur les résidences principales.
5. **Surface moyenne à Paris** : Surface moyenne des logements avec un contrat à Paris.
6. **Top 5 des surfaces** : Lister les 5 contrats qui ont les surfaces les plus élevées.
7. **Prix moyen** : Calculer le prix moyen de la cotisation mensuelle.
8. **Répartition des contrats par valeur des biens** : Nombre de contrats pour chaque catégorie de valeur des biens déclarés.
9. **Top 10 des départements par prix moyen** : Classement des 10 départements où le prix moyen de la cotisation est le plus élevé.
10. **Formules intégrales** : Nombre de contrats avec des formules intégrales pour la région Pays de la Loire.
11. **Communes populaires** : Liste des communes ayant au moins 150 contrats.
12. **Nombre de contrats par région** : Nombre de contrats pour chaque région.

### 📊 Résultats des Analyses
Voici les résultats principaux issus des analyses :

1. **Contrats pour la commune de Caen** : Les surfaces varient de 20 à 99 m².
2. **Contrats en Saône-et-Loire** : Les contrats incluent les formules `Classique` et `Integral`.
3. **Régions françaises** : Liste des 19 régions françaises.
4. **Nombre total de contrats** : 25 620 sur les résidences principales.
5. **Surface moyenne des logements à Paris** : 51,77 m².
6. **Top 5 des plus grandes surfaces** : Les surfaces varient de 559 à 815 m².
7. **Prix moyen de la cotisation mensuelle** : 19,33 euros.
8. **Répartition des contrats par valeur des biens** :
   - 0 - 25 000 euros : 22 720 contrats.
   - 25 000 - 50 000 euros : 6 815 contrats.
   - 50 000 - 100 000 euros : 696 contrats.
   - Plus de 100 000 euros : 104 contrats.
9. **Top 10 des départements par cotisation** :
   - Paris : 36,4 euros.
   - Hauts-de-Seine : 26,25 euros.
   - Val-de-Marne : 19,82 euros.
10. **Formules intégrales dans Pays de la Loire** : 590 contrats.
11. **Communes avec plus de 150 contrats** : Paris (plusieurs arrondissements), Nice, Bordeaux, Nantes, Grenoble, Toulouse, etc.
12. **Nombre de contrats par région** :
   - Île-de-France : 14 179.
   - Provence-Alpes-Côte d’Azur : 3 279.
   - Auvergne-Rhône-Alpes : 3 056.
   - Autres régions : Moins de 2 000 contrats chacune.

## 📂 Documentation technique
La documentation technique est disponible sous le nom **`BANGOURA_Andre_Mamadouba_1_Documentation_technique_082024`**. Elle inclut :

- La description des tables et des champs.
- Les dictionnaires de données.
- Le modèle de requêtes SQL.
- Les étapes méthodologiques suivies pour chaque analyse.

## 📑 Présentation du projet
Une présentation en PDF intitulée **`BANGOURA_ANDRE_3_Présentation_082024.pdf`** expose la méthodologie utilisée, les étapes suivies, et les principaux résultats. Cette présentation comprend :

- La création de la base de données.
- L’importation des tables.
- L’exploration des données.
- Les résultats détaillés.
- Les conclusions stratégiques pour la standardisation des tarifs.

## 🔚 Conclusion
Ce projet a permis de dresser un état des lieux de la tarification actuelle chez Dat’Assur Habitation. Les résultats obtenus serviront de base pour élaborer une nouvelle stratégie tarifaire plus compétitive et segmentée.

## ✒️ Auteur
Projet réalisé par : **André Mamadouba Bangoura** - Data Analyst.
## 📞 Contact
andrembangoura@gmail.com
