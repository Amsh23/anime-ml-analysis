# Anime Recommendation System

This project is a Jupyter notebook analysis for building an anime recommendation workflow. It collects anime data from the Jikan API, stores it in `anime.csv`, performs data cleaning and exploratory data analysis, and applies clustering and classification models. The notebook includes a simple recommendation demo based on KMeans clusters.

## Main technologies

- Python
- Jupyter Notebook
- pandas
- requests
- matplotlib
- seaborn
- scikit-learn
- SciPy
- hdbscan

## Setup

Install the Python packages used by the notebook:

```bash
pip install pandas requests matplotlib seaborn scikit-learn scipy hdbscan
```

## Run

Start Jupyter and open the notebook:

```bash
jupyter notebook anime-recommendation-system.ipynb
```

## Project structure

- `anime-recommendation-system.ipynb` - main notebook for data collection, analysis, modeling, and recommendation demo.
- `anime.csv` - anime dataset used by the notebook.
- `1-miku.jpg`, `2-bleach.jpg`, `3-shizuku.jpg`, `4-art.jpg` - images used in the notebook presentation.
