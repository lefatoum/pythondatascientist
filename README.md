![](/other/python-pour-le-data-scientist-dunod.jpeg)

# Python pour la data scientist

Ce répertoire rassemble des [Jupyter](http://jupyter.org/) notebooks ainsi que des données permettant d'illustrer l'ouvrage [Python pour le data scientist](https://www.dunod.com/sciences-techniques/python-pour-data-scientist-bases-du-langage-au-machine-learning) par Emmanuel Jakobowicz paru chez Dunod en octobre 2018.

Les notebooks sont divisés par chapitres ou sous-chapitres et sont rassemblés dans le répertoire [notebooks](/notebooks/).

Pour utiliser ce répertoire, vous truoverez [des détails plus bas](#utilisation).

## Organisation du répertoire

Les thèmes abordés sont les suivants :

- [*Chapitre 2* - Les bases du langage](/notebooks/02_python_from_scratch.ipynb)
- [*Chapitre 3* - Les structures pour traiter des données (NumPy / Pandas)](/notebooks/03_numpy_pandas_bases.ipynb)
- *Chapitre 4* - La préparation des données
  - [*4.1* - La récupération des données](/notebooks/04_01_recuperation_des_donnees.ipynb)
  - [*4.2* - La préparation des données et les premières statistiques](/notebooks/04_02_manipulation_description_des_donnees.ipynb)
- *Chapitre 5* - La data visualisation
  - [*5.1* - La data visualisation avec Matplotlib et Seaborn](/notebooks/05_01_Data_visualisation_ matplotlib_seaborn.ipynb)
  - [*5.2* - La cartographie](/notebooks/05_02_Data_visualisation_cartographie.ipynb)
  - [*5.3* - Les dataviz interactives](/notebooks/05_03_Visualisations_interactives.ipynb)
- *Chapitre 6* - Le machine learning et le deep learning
  - [*6.1* - Les approches supervisées](/notebooks/06_01_Machine_learning_supervise.ipynb)
  - [*6.2* - Les approches non supervisées](/notebooks/06_02_Machine_learning_non_supervise.ipynb)
  - [*6.3* - Le traitement des données textuelles (NLP)](/notebooks/06_03_NLP.ipynb)
  - [*6.4* - Le deep learning avec Keras](/notebooks/06_04_Deep_Learning.ipynb)
- *Chapitre 7* - Les traitements "big data"
  - [*7.1* - Récupérer des données depuis une infrastructure big data](/notebooks/07_01_Big_data_import.ipynb)
  - [*7.2* - PySpark pour Apache Spark](/notebooks/07_02_Spark.ipynb)

## Les données

Une partie des données utilisées dans l'ouvrage est disponible dans le répertoire [data](/data/), le reste des données est directement accessible par des liens dans les Notebooks (dans le cas où celles-ci sont trop volumineuses pour ce répertoire).

<a id="utilisation"></a>
## Utilisation de ce répertoire

Vous pouvez bien entendu parcourir ce répertoire et ses notebooks directement sur github.com mais ce que je vous conseille, c'est de télécharger tous le répertoire et d'installer Anaconda sur votre machine. Vous en trouverez une version ici :

[https://www.anaconda.com/download/](https://www.anaconda.com/download/)

Une fois que vous avez installé Anaconda, vous pouvez créer un environnement à partir du fichier [environment.yml](/environment.yml) disponible dans ce répertoire.

Utilisez le terminal ou la ligne de commande Anaconda (Conda Prompt). Utilisez la commande :
```
conda env create -f environment.yml
```

Il ne vous reste qu'à activer votre environnement en utilisant :
- Pour MacOS et Linux :
```
source activate myenv
```

- Pour Windows :
```
activate myenv
```

Pour vérifier l'installation, utilisez :
```
conda list
```

Une fois votre environnement activé, utilisez la commande :
```
jupyter notebook
```
ou
```
jupyter lab
```
C'est parti, vous pouvez commencer à coder !


## Utilisation et licence

Ce répertoire a pour but d'être évolutif, n'hésitez pas à la cloner et à vérifier son activité. Si vous avez des remarques ou si vous voulez ajouter des informations, faites-le-moi savoir !

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.
