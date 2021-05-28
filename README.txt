Test Quantmetry

Ce répertoire contient 
- le document demandé avec les réponses aux questions
- le notebook final contenant tout les détails permettant de repondre aux questions
- le notebook en version html
- le notebook en version .py
- le notebook R final
- le notebook R en version html
- le notebook R en version .R


Ajouter le repertoire de rendu dans un dossier work.

Choix 1: 

Le code dans le notebook est basé sur l'image docker: jupyter/datascience-notebook.
Pour le démarrer (dans le dossier parent à work/): 
docker run -d --rm --name quant -p 8888:8888 -v $PWD/work:/home/jovyan/work -w /home/jovyan/work luluisco/quant start-notebook.sh --NotebookApp.token="quant"

Ensuite aller sur http://localhost:8888?token=quant .

Ensuite  Au début de chaque notebook il y a des instructions pour l'installation de packages éventuelles si besoin. 

Choix2:

aller sur https://mybinder.org/v2/gh/lucasiscovici/quant/master

ajouter le repertoire de rendu dans jupyter
