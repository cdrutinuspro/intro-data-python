# Introduction à NumPy, pandas et Matplotlib

Notebooks d'introduction pour l'analyse de données en Python.
Aucune installation n'est nécessaire : cliquez sur un lien ci-dessous.

- **Colab** : nécessite un compte Google. Pensez à faire *Fichier → Enregistrer une copie dans Drive* pour conserver votre travail.
- **Binder** : sans compte, mais démarrage lent (1 à 3 min) et rien n'est sauvegardé : téléchargez votre notebook avant de fermer.

## Parcours conseillé

NumPy (1 → 3), puis pandas (1 → 3), puis Matplotlib (1 → 2, et 3 en option).

| Notebook | Contenu | Colab | Binder |
|---|---|---|---|
| NumPy 1 | Création d'arrays | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/cdrutinuspro/intro-data-python/blob/main/notebooks/numpy_1_creation.ipynb) | [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/cdrutinuspro/intro-data-python/main?urlpath=lab/tree/notebooks/numpy_1_creation.ipynb) |
| NumPy 2 | Indexation, slicing, masques | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/cdrutinuspro/intro-data-python/blob/main/notebooks/numpy_2_indexation_masques.ipynb) | [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/cdrutinuspro/intro-data-python/main?urlpath=lab/tree/notebooks/numpy_2_indexation_masques.ipynb) |
| NumPy 3 | Agrégation, broadcasting | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/cdrutinuspro/intro-data-python/blob/main/notebooks/numpy_3_agregation_broadcasting.ipynb) | [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/cdrutinuspro/intro-data-python/main?urlpath=lab/tree/notebooks/numpy_3_agregation_broadcasting.ipynb) |
| pandas 1 | Lecture (`read_csv`) et exploration | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/cdrutinuspro/intro-data-python/blob/main/notebooks/pandas_1_lecture_exploration.ipynb) | [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/cdrutinuspro/intro-data-python/main?urlpath=lab/tree/notebooks/pandas_1_lecture_exploration.ipynb) |
| pandas 2 | Masques, `loc` / `iloc` | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/cdrutinuspro/intro-data-python/blob/main/notebooks/pandas_2_masques_indexation.ipynb) | [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/cdrutinuspro/intro-data-python/main?urlpath=lab/tree/notebooks/pandas_2_masques_indexation.ipynb) |
| pandas 3 | `groupby`, `merge`, `concat` | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/cdrutinuspro/intro-data-python/blob/main/notebooks/pandas_3_groupby_merge_concat.ipynb) | [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/cdrutinuspro/intro-data-python/main?urlpath=lab/tree/notebooks/pandas_3_groupby_merge_concat.ipynb) |
| Matplotlib 1 | `plot` et `scatter` | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/cdrutinuspro/intro-data-python/blob/main/notebooks/matplotlib_1_plot_scatter.ipynb) | [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/cdrutinuspro/intro-data-python/main?urlpath=lab/tree/notebooks/matplotlib_1_plot_scatter.ipynb) |
| Matplotlib 2 | Mise en forme, `subplots`, barres | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/cdrutinuspro/intro-data-python/blob/main/notebooks/matplotlib_2_mise_en_forme.ipynb) | [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/cdrutinuspro/intro-data-python/main?urlpath=lab/tree/notebooks/matplotlib_2_mise_en_forme.ipynb) |
| Matplotlib 3 *(option)* | Histogrammes, boxplots, heatmaps | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/cdrutinuspro/intro-data-python/blob/main/notebooks/matplotlib_3_distributions.ipynb) | [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/cdrutinuspro/intro-data-python/main?urlpath=lab/tree/notebooks/matplotlib_3_distributions.ipynb) |

## Données (`data/`)

| Fichier | Description |
|---|---|
| `titanic.csv` | 891 passagers du Titanic (jeu de données classique) |
| `ports.csv` | codes des ports d'embarquement (pour le `merge`) |
| `temperatures.csv` | températures mensuelles moyennes approximatives de 3 villes françaises (illustratif) |
