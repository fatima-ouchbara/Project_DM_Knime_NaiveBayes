# Analyse des Commentaires sur les Robes - Projet Mini

Ce projet a pour objectif d'évaluer la satisfaction des clientes concernant les robes achetées en utilisant l'analyse des sentiments. Les étapes clés du projet sont décrites ci-dessous.
Ce projet utilise KNIME pour l'analyse des commentaires clients sur les robes. Pour simplifier l'utilisation, veuillez suivre les étapes ci-dessous pour télécharger et exécuter le workflow KNIME.

## Instructions d'Utilisation

1. **Téléchargement du Workflow :**
   - Téléchargez le fichier `Data_Mining_Project.knwf` à partir du répertoire principal de ce projet.

2. **Importation dans KNIME :**
   - Ouvrez KNIME Analytics Platform.
   - Allez dans "File" -> "Import Workflow" -> "Local Workflow Archive".
   - Sélectionnez le fichier `Data_Mining_Project.knwf` téléchargé.

3. **Exécution du Workflow :**
   - Double-cliquez sur le fichier importé dans le "Explorer" pour ouvrir le workflow.
   - Exécutez chaque nœud du workflow séquentiellement en cliquant sur le bouton "Execute" en haut à droite.

4. **Visualisation des Résultats :**
   - Les résultats seront générés et visualisés dans le workflow.
   - Consultez les nœuds "View" pour explorer les visualisations.

## Étapes du Projet

### 1. Lecture des Données

- Les données brutes sont stockées dans le dossier `Data/`.

### 2. Conversion des Commentaires en Documents

- Les commentaires sont convertis en documents pour faciliter le traitement.

### 3. Prétraitement des Données

- Suppression des valeurs manquantes.
- Calcul de la polarité des commentaires.
- Détermination des catégories grammaticales.
- Suppression des nombres, des signes de ponctuation, et des mots vides.
- Normalisation du texte (en minuscules).
- Filtrage des parties du discours (POS).

### 4. Extraction des Caractéristiques

- Construction d'un sac de mots pour les documents.
- Extraction de vecteurs caractéristiques.

### 5. Visualisation

- Exploration visuelle des commentaires et des caractéristiques extraites.

### 6. Entraînement et Test du Modèle

- Algorithme utilisé : Naive Bayes.
- Spécification de la variable cible.
- Filtrage des colonnes pour garder les caractéristiques pertinentes.
- Gestion du déséquilibre de la base de données.

### 7. Mesures de Performances

- Précision du modèle (Accuracy).

## Structure du Répertoire

- **Data/:** Emplacement des données brutes.
- **Scripts/:** Scripts Python pour les fonctions spécifiques.
- **Models/:** Sauvegarde des modèles entraînés.
- **Visualizations/:** Graphiques et visualisations générés.
- **README.md :** Guide d'utilisation et d'exécution du projet.

**Auteur**: OUCHBARA Fatima Zohra


