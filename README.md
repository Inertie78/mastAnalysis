# 🏗️ Analyse d’un mât haubané à deux niveaux
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Ce projet présente une modélisation complète d’un mât triangulé en aluminium soumis à des efforts de vent, stabilisé par haubans à deux niveaux. Il combine calcul analytique, visualisation 2D, décomposition vectorielle 3D et vérification de flambage.

## 📐 Objectifs

- Calculer les efforts dus au vent sur le mât et la lampe
- Répartir les tensions dans les haubans selon leur orientation
- Vérifier l’équilibre des forces et des moments
- Évaluer la stabilité du mât via le flambage d’Euler
- Visualiser les efforts et la géométrie en 2D

## 🧮 Technologies utilisées

- Python (NumPy, SymPy, Matplotlib)
- Jupyter Notebook
- Visualisation vectorielle 2D
- Calcul de flambage (Euler corrigé)

## 📁 Fichiers

- `calcul_03.pdf` : rapport technique complet
- `mast_model.py` : script Python principal
- `mast_analysis.ipynb` : notebook interactif
- `mat_haubane.png` : visualisation 2D annotée

## 📦 Installation

```bash
git clone https://github.com/Inertie78/mast_analysis.git
cd mast_analysis
pip install -r requirements.txt
```

## 📚 Utilisation

Lancez le notebook mast_analysis.ipynb pour explorer les calculs, visualiser les forces et ajuster les paramètres du mât.

## 🧠 Contexte pédagogique

Ce projet s’inscrit dans le cadre de la formation MAS RAD et illustre l’intégration entre modélisation physique, automatisation numérique et documentation technique.
