# Prédiction du poids des enfants à partir de l'âge et de la taille

## Description

Ce projet utilise un modèle de régression linéaire pour prédire le poids des enfants en fonction de leur âge et de leur taille.  
Le modèle a été entraîné sur un jeu de données fictif comprenant 100 collégiens.

## Contenu

- `data/` : dossier contenant les données utilisées (si applicable)  
- `notebook.ipynb` : notebook Python avec l’analyse, le modèle et les visualisations  
- `script.py` : script Python pour entraîner le modèle et faire des prédictions  
- `README.md` : ce fichier  

## Résultats

- Le modèle montre que la taille a un impact plus fort sur le poids que l'âge.  
- Le coefficient de détermination (R²) est de 0.47, indiquant que le modèle explique environ 47% de la variance du poids.  
- L’erreur quadratique moyenne (RMSE) est de 13.46 kg, suggérant des marges d’erreur à améliorer.  

## Installation

Pour exécuter ce projet, vous aurez besoin de Python 3 et des librairies suivantes :

```bash
pip install numpy pandas scikit-learn matplotlib seaborn
