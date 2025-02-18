# Projet 7: Implémentez un modèle de scoring

Lien Dashboard : https://ocr7-92bf8f2ff8e1.herokuapp.com/

# Contexte
En tant que Data Scientist chez Prêt à dépenser, une société financière spécialisée dans les crédits à la consommation, j'ai été chargé de développer un modèle de scoring pour évaluer la probabilité de remboursement des prêts par les clients. Ce modèle permettra de classifier automatiquement les demandes de crédit en tant qu'approuvées ou refusées, en se basant sur des données variées telles que les comportements des clients et les informations provenant d'autres institutions financières.
Objectif du Projet

# Le projet vise à :

  1. Élaboration du Modèle de Scoring : Construire un modèle de machine learning capable de prédire la probabilité de défaut de paiement d'un client et de classifier sa demande de crédit.
  2. MLOps et Mise en Production : Déployer le modèle de scoring sous forme d'une API dans le cloud, gérer son cycle de vie via une approche MLOps, et surveiller les performances en production.

# Étapes de l'Analyse

  1. Prétraitement et Feature Engineering :
     - Préparation des données, gestion des variables catégorielles et création de nouvelles variables.
     - Transformation des distributions de variables et normalisation lorsque nécessaire.

  2. Modélisation et Évaluation :
     - Sélection et entraînement de plusieurs modèles de machine learning.
     - Optimisation des hyperparamètres via validation croisée et évaluation des performances des modèles selon des critères techniques (AUC, accuracy) et métier (minimisation des coûts d'erreur).

  3. Suivi du Cycle de Vie du Modèle (MLOps) :
     - Utilisation de MLFlow pour le suivi des expérimentations, le stockage des modèles et la gestion de leur déploiement.
     - Mise en œuvre d'un pipeline CI/CD pour automatiser le déploiement de l'API sur le cloud avec GitHub Actions.

  4. Détection du Data Drift :
     - Utilisation de la librairie evidently pour détecter les éventuels drifts des données en production et maintenir la performance du modèle.
