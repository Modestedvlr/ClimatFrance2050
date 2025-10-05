# Nom du projet : ClimatFrance2050

Visualisation interactive des émissions de CO₂ et prédiction des sécheresses en France d’ici 2050

## Objectif

Ce projet vise à analyser l’évolution des émissions de gaz à effet de serre en France, à explorer les effets de la transition énergétique, et à prédire les zones susceptibles de subir des sécheresses d’ici 2050. Il s’appuie sur des données publiques et propose une interface web interactive.

## Technologies utilisées

- Python 3.11+
- Quarto
- Pandas, Geopandas, Scikit-learn
- Folium, Plotly, Matplotlib
- GitHub Pages (déploiement)
- GitHub Actions (CI)

## Structure du projet
/ClimatFrance2050
_site/ # Pages du site web Quarto

_module/ # Code Python (data, modèle, visualisation)

_roadmap/ # Aperçu du projet à mi-parcours

_slider/ # Diaporama final 

_tests/ # Tests unitaires

_requirements.txt # Dépendances Python


## Sources de données

- [Météo-France](https://meteofrance.com)
- [Drias – Les futurs du climat](https://www.drias-climat.fr)
- [ADEME – Base Carbone](https://www.basecarbone.ademe.fr)
- [OpenStreetMap](https://www.openstreetmap.org)
- [Kaggle](https://www.kaggle.com)

## Installation

```bash
git clone https://github.com/Modestedvlr/ClimatFrance2050.git
cd ClimatFrance2050
pip install -r requirements.txt


