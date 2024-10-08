# README - Analyse des Départs de Clients pour Primero Bank

## Contexte du Projet

- Le projet d’analyse pour **Primero Bank** vise à **comprendre les raisons des départs des clients** et à **identifier les segments de clients actuels susceptibles de quitter la banque** à l'avenir.
- **Primero Bank** est une banque 100% en ligne qui propose des services bancaires variés. Elle a récemment observé une hausse de son taux d'attrition et souhaite prendre des mesures pour mieux fidéliser sa clientèle.
- Le projet a été réalisé à partir d’un fichier de données comprenant des informations démographiques, des détails sur les produits bancaires, et les comportements financiers des clients.
- L'analyse a été effectuée par **André Bangoura**, consultant chez **ESN Data**, en utilisant des **tableaux croisés dynamiques (TCD)** et divers graphiques pour visualiser les comportements clés, les segments à risque et les profils types des clients.

## Objectifs du Projet

1. **Analyser les caractéristiques communes** des clients ayant quitté la banque.
2. **Déduire des pistes d’analyse** sur les raisons potentielles de ces départs.
3. **Identifier les profils à risque** parmi les clients actuels.
4. **Proposer des recommandations** pour limiter les départs futurs et fidéliser les clients.

## Fichiers Fournis

### 1. Données de Primero Bank (`Données+Primero+Bank.xlsx`)
Ce fichier contient les informations brutes sur les clients actuels et ceux ayant quitté la banque. Les variables incluent :

- **Statut du client** : "Client actuel" ou "Client perdu"
- **Âge, Genre, Statut marital, Catégorie de revenu annuel**
- **Type de carte** (Blue, Silver, Gold, Platinum)
- **Durée d’engagement en mois**
- **Nombre de mois d’inactivité**
- **Nombre d’interactions** et **Nombre de transactions**
- **Montant de crédit renouvelé** et **Utilisation moyenne de la carte**

Le fichier contient également un glossaire des différentes variables pour clarifier les définitions et abréviations.

### 2. **Analyse des Données – Primero Bank (`BANGOURA_ANDRE_1_ANALYSE_072024.pdf`)**
- Contient une **description détaillée des données**, les nettoyages effectués, et les premiers résultats d’analyse.

### 3. **Visualisations de la Présentation (`BANGOURA_ANDRE_2_VISUALISATIONS_072024.pdf`)**
- Document de présentation avec les graphiques finaux illustrant les résultats de l'analyse.
- Utilisation de plusieurs types de graphiques (colonnes, barres, histogrammes) pour montrer les segments de clients et les comportements de départ.

### 4. **Données Corrigées et TCD (`Primero_Donnees_corrigees_et_TCD.pdf`)**
- Contient les premières lignes des **données corrigées** ainsi que les **tableaux croisés dynamiques (TCD)** utilisés pour identifier les caractéristiques des clients.
- Les TCD montrent des informations clés telles que la répartition des clients par type de carte, catégorie de revenu, genre, et niveau d’études.

## Étapes de l’Analyse

### Étape 1 : Exploration et Nettoyage des Données
- **Nettoyage** : Correction des abréviations (ex. "M" remplacé par "Homme" et "F" par "Femme") et normalisation des champs.
- **Segmentation** : Identification des principales variables influençant les départs (type de carte, catégorie de revenu, statut marital, nombre de mois d'inactivité).

### Étape 2 : Création des Tableaux Croisés Dynamiques (TCD)
- **TCD par Type de Carte** : Analyse du taux de départ par type de carte (Blue, Silver, Gold, Platinum).
- **TCD par Revenu Annuel** : Détermination des tranches de revenu les plus à risque (Moins de $40K, $60K - $80K, $120K+).
- **TCD par Genre et Niveau d’Études** : Évaluation de l'influence du genre et du niveau d’études sur la fidélité.
- **TCD par Statut Marital** : Visualisation de la répartition des départs selon le statut marital (Célibataire, Marié, Divorcé).
- Mais aussi les TCD selon le **comportement financier** des clients (transaction moyen, durée d'engagement, utilisation moyenne de la carte...) pour identifier des indicateurs de risque.

### Étape 3 : Visualisations et Présentation
- **Graphiques de comparaison** : Comparaison des taux d’attrition par variables clés.
- **Visualisations dynamiques** : Utilisation de barres, histogrammes empilés, etc., pour une meilleure lecture.

## Résultats Clés

1. **Taux d’attrition global** : 16,15%
2. **Types de cartes** :
  - La carte **Blue** enregistre la majorité des départs (**93% des clients perdus**).
  - La carte **Platinum** a le taux de départ le plus élevé (**70% des détenteurs ont quitté la banque**).
3. **Catégorie de revenu** : Les tranches **$60K - $80K** sont à risque. Tranches Moins de $40K et $120K+ plus stables.
4. **Durée d’engagement** : Plus faible pour les clients perdus.
5. **Utilisation de la carte** : Faible utilisation = risque de départ élevé.

## Recommandations

1. **Amélioration des offres** : Avantages spécifiques pour les clients à risque.
2. **Programmes de fidélisation** : Fidélisation pour segments à risque (faible utilisation, revenu moyen).
3. **Options de paiement flexibles**.
4. **Formation du personnel**.

## Démarrage du Projet
1. Ouvrir le fichier d’analyse (`BANGOURA_ANDRE_1_ANALYSE_072024.pdf`).
2. Consulter les visualisations (`BANGOURA_ANDRE_2_VISUALISATIONS_072024.pdf`).
3. Explorer les TCD dans le fichier `Primero_Donnees_corrigees_et_TCD.pdf`.

## Contact

Pour toute question ou suggestion, vous pouvez contacter :
**André Mamadouba Bangoura**, Data analyst : andrembangoura@gmail.com
