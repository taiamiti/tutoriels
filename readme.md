# Introduction au Machine Learning

**Date** : 03/04/2023  
**Auteur** : Taiamiti Edmunds (taiamiti.edmunds@ml4everyone.com)  
**Objectifs** : L'objectif de ce projet est de fournir es exemples pratiques d'utilisation du ML classique sur des données tabulaires et des séries temporelles. Il met en lumière la stack technique suivante : miniconda, python, jupyter notebook, scikit-learn, pandas, prophet, ipywidget, plotly


Ce projet contient un ensemble de notebooks Jupyter qui servent de tutoriels pour les bibliothèques Python Scikit-Learn et Prophet. Ces bibliothèques sont largement utilisées pour l'apprentissage automatique et l'analyse de séries temproelles respectivement, et sont des outils précieux pour tout scientifique des données ou développeur d'apprentissage automatique.

## 1. Installation

Utilisation de `Miniconda` comme environement virtuel.
1. Téléchargez la version appropriée de Miniconda pour votre système d'exploitation à partir du site web officiel de Anaconda : https://docs.conda.io/en/latest/miniconda.html

2. Suivez les instructions d'installation pour votre système d'exploitation :

Pour Windows : https://conda.io/projects/conda/en/latest/user-guide/install/windows.html  
Pour macOS : https://conda.io/projects/conda/en/latest/user-guide/install/macos.html  
Pour Linux : https://conda.io/projects/conda/en/latest/user-guide/install/linux.html  

3. Une fois que vous avez installé Miniconda, vous pouvez créer un environnement conda pour ce projet nomé `tuto`. Pour cela, ouvrez une ligne de commande (ou un terminal) et naviguez jusqu'au répertoire du projet, puis exécutez la commande suivante :

```bash
conda create -n tuto python=3.9  # création d'un env conda
conda activate tuto  # activation de l'env
pip install -r requirements.txt  # installation des packages
```

Lancez Jupyter Notebook en exécutant la commande suivante :
```bash
# run jupyter
jupyter notebook
```

## Prérequis
Avant de commencer, assurez-vous de remplir les conditions suivantes :

Vous avez installé Python 3.6 ou une version ultérieure sur votre machine locale.
Vous avez installé les paquets Python requis. Vous pouvez les installer en exécutant la commande pip install -r requirements.txt depuis le répertoire du projet.
Pour commencer
Pour commencer, clonez ce dépôt sur votre machine locale et accédez au répertoire du projet. De là, vous pouvez lancer le serveur Jupyter Notebook en exécutant la commande jupyter notebook, puis sélectionner le notebook sur lequel vous souhaitez travailler.

## Notebooks
Ce projet contient les notebooks suivants :

Scikit-Learn Tutorial.ipynb : Ce notebook fournit une introduction à la bibliothèque Scikit-Learn, notamment la façon de charger des données, de les prétraiter, de les diviser en ensembles d'apprentissage et de test, et de former et d'évaluer des modèles d'apprentissage automatique.

Prophet Tutorial.ipynb : Ce notebook fournit une introduction à la bibliothèque Prophet, notamment la façon de charger des données de séries chronologiques, de les prétraiter, et de former et d'évaluer des modèles de séries chronologiques.

## Ressources
Si vous souhaitez en savoir plus sur Scikit-Learn ou Prophet, les ressources suivantes peuvent être utiles :

- Documentation de Scikit-Learn : La documentation officielle de Scikit-Learn, qui comprend des tutoriels, des exemples et une référence API.

- Documentation de Prophet : La documentation officielle de Prophet, qui comprend des tutoriels, des exemples et une référence API.

## Remerciements

Les tutoriels ont été récupérés sur 

## Contribution
Si vous trouvez des erreurs ou si vous souhaitez contribuer à ce projet, n'hésitez pas à ouvrir une issue ou une pull request sur GitHub.

## Licence
Ce projet est sous licence MIT. Veuillez consulter le fichier LICENSE pour plus de détails.