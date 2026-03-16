# Analyse des animés 🎌

## Description
Analyse simple d'un dataset d'animés : nettoyage des données et classement des 10 meilleurs.

## Données
- **Fichier :** `animes.csv`
- **59 lignes brutes** (58 animés uniques après suppression des doublons)

## Comment exécuter
1. Installer les bibliothèques : `pip install pandas numpy matplotlib`
2. Ouvrir `analyse_animes.ipynb` dans Jupyter ou VS Code
3. Exécuter toutes les cellules (Run All)

## Ce qu'on fait
1. Charger le CSV
2. Remplacer les valeurs vides, convertir les types
3. Supprimer les doublons
4. Calculer un score : `0.6 × Note_Globale + 0.4 × popularité`
5. Afficher le Top 10 et un graphique

## Résultat
Un classement des 10 meilleurs animés basé sur leur note et leur popularité.

## Réflexions
- Le nombre d'épisodes est un proxy imparfait pour la popularité
- 25 animés sur 58 n'ont pas de note et sont exclus
- On utilise le logarithme pour éviter qu'One Piece (1090 épisodes) écrase tout le monde

## Auteur
Ahmed – Mars 2026
