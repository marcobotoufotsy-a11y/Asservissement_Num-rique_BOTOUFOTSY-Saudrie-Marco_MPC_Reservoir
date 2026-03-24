# Asservissement_Num-rique_BOTOUFOTSY-Saudrie-Marco_MPC_Reservoir
Projet de régulation du niveau d’un réservoir d’eau utilisant la commande prédictive (MPC) sous MATLAB/Simulink, avec comparaison des performances avec un contrôleur PID et étude du rejet de perturbations.
# Commande Prédictive (MPC) pour un Réservoir d’Eau

## Description
Ce projet consiste à étudier et simuler la régulation du niveau d’un réservoir d’eau à l’aide d’un contrôleur MPC (Model Predictive Control) sous MATLAB/Simulink.

---

## Objectifs
- Modéliser un réservoir d’eau
- Implémenter un contrôleur MPC
- Assurer le suivi de consigne
- Étudier le rejet de perturbations
- Comparer les performances avec un contrôleur PID

---

## Modèle du système

Le système est modélisé par l’équation :

dx/dt = -0.5x + u - d

où :
- x : niveau du réservoir
- u : débit de la pompe
- d : perturbation

---

## Outils utilisés
- MATLAB
- Simulink
- MPC Toolbox

---

## Instructions d’exécution

1. Ouvrir MATLAB  
2. Exécuter le fichier :
   main.m  
3. Ouvrir le modèle Simulink :
   model.slx  
4. Lancer la simulation  

---

## Résultats

Le contrôleur MPC permet :
- un bon suivi de consigne  
- une réponse rapide  
- un rejet efficace des perturbations  
- une meilleure performance que le PID  

---

## Contenu du projet

- main.m → script principal  
- model.slx → modèle Simulink  
- figures → résultats de simulation  

---

##  Auteur

Nom : BOTOUFOTSY Saudrie Marco  
École : ESPA (École Supérieure Polytechnique d’Antsiranana)
