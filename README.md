# Projet MARL

Ce projet a été réalisé dans le cadre de l'UE CoCoMa (Coordination et Consensus multiagents) du Master ANDROIDE (maintenant AI2D) à Sorbonne Université.

## Travail effectué

Dans l'environnement Multiwalker de pettingzoo, nous avons entraîner trois agents avec plusieurs algorithmes d'apprentissage par renforcement (DPG, MADDPG, TD3) de différentes manières pour leur faire apprendre à exécuter une tâche.

Nous avons ensuite comparé ces méthodes et cherché des améliorations.

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