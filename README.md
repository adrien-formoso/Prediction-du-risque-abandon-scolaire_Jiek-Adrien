
Contexte
Vous travaillez dans une structure éducative qui souhaite identifier les étudiants à risque d’abandon afin de mettre en place des actions de soutien. Un jeu de données a été constitué à partir des informations académiques et sociales des étudiants.
Objectif
Construire un modèle de classification permettant de prédire si un étudiant risque ou non d’abandonner ses études.
Jeu de données fourni
Chaque ligne correspond à un étudiant, avec les colonnes suivantes :
Age

Sexe
Taux_presence (en %)
Nombre_retards
Note_moyenne (sur 20)													
Situation_familiale (Célibataire, Marié, Enfants à charge, Divorcé)
Abandon (1 = a abandonné, 0 = n’a pas abandonné)


Objectifs pédagogiques
Maîtriser les étapes d’un projet de classification supervisée.

Comprendre et appliquer les métriques de performance (accuracy, precision, recall, f1-score).
Utiliser la validation croisée et le GridSearch pour ajuster les hyperparamètres.
Expérimenter plusieurs algorithmes vus en cours (KNN, arbre de décision, régression logistique).
Interpréter les résultats obtenus de façon critique.


Consignes Data-science
Appliquer et faire apparaître avec soin les 4 grandes étapes de la méthode CRISP-DM tel que vu en cours:
Compréhension et explication du besoin (mesures et métriques)
Compréhension de la donnée et nettoyage
Modélisation
Validation (mesures et métriques)
Approche technique minimale attendue
Prétraitement des données : gérer les variables catégorielles, vérifier les valeurs manquantes, explorer la distribution des variables.


Exploration des corrélations et visualisation des données (PCA ?).
Choix d’un ou plusieurs modèles de classification parmi ceux étudiés (KNN, arbre de décision, régression logistique, KMeans).
Évaluation des performances : utilisez accuracy, recall, precision, f1-score et matrice de confusion
Recherche des meilleurs hyperparamètres avec GridSearch et validation croisée.
Analyse critique des résultats :
Quels modèles fonctionnent le mieux ? Pourquoi ?
Quelles sont les limites du modèle ? Des données ?
Quelle interprétation peut-on faire des métriques obtenues ?
Que signifie une bonne ou mauvaise précision dans ce contexte ?
