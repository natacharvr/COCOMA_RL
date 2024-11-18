# Projet MARL

Ce projet a été réalisé dans le cadre de l'UE CoCoMa (Coordination et Consensus multiagents) du Master ANDROIDE (maintenant AI2D) à Sorbonne Université.

## Travail effectué

Dans l'environnement Multiwalker de pettingzoo, nous avons entraîné trois agents avec plusieurs algorithmes d'apprentissage par renforcement (DDPG, MADDPG) de différentes manières pour leur faire apprendre à exécuter une tâche.

Nous avons ensuite comparé ces méthodes et cherché des améliorations.

## Organisation des fichiers

Les différentes versions des implémentations des algorithmes sont disponibles dans les fichiers ipynb suivants :

- ```multi_agent_ddpg.ipynb```
- ```multi_buffer_commun.ipynb```
- ```one_agent_to_rule_them_all.ipynb```

Les vidéos de certains résultats sont disponibles dans le dossier ```videos```.

Les modèles entraînés sont disponibles dans le dossier ```models```.

## Librairies

Les librairies nécessaires pour exécuter les fichiers Jupyter Notebook sont :

```python 
agilerl==0.1.16
pettingzoo[classic, sisl]==1.23.1
SuperSuit==3.9.0
torch==2.0.1
numpy>=1.24.2
tqdm>=4.65.0
fastrand==1.3.0
gymnasium>=0.28.1
imageio>=2.31.1
Pillow>=9.5.0
PyYAML>=5.4.1
wandb>=0.13.10
```