# SIFT-classification
Nous utilisons l'algorithme SIFT pour résoudre un problème de classification appliqué à la reconnaissance de races de chiens.
Ces résultats doivent être comparés avec les méthodes reposant sur des réseaux de neurones convolutifs : https://github.com/Tannerversety/CNN-classification

Ce travail se décompose en : 

- un notebook validation_params dont l'objectif est de déterminer sur un sous ensemble de race
	les hyperparamètres et filtres (pre-processing SIFT et clustering) les plus efficaces. 
	(sélection sur un jeu de validation)
  
- un notebook selection_model dont l'objectif est d'implémenter divers modèles de classification 
	supervisé (random forrest/regression logistique/réseau de neurones) sur un sous ensemble de race
	de régler les hyperparamètres de régularisation. Ce notebook sert aussi à la visualisation du 
	pre-processing
  
- un notebook test_model dont l'objectif est d'évaluer la performance de la méthode classique sur
	l'ensemble des races.
