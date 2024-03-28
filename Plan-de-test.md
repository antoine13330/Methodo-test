# Strategie de test

## Identifiant du plan de test
PT001

## Références
Projet 2 : Gestion d’une concession

## Introduction
Cette strategie de test vise a definir la politique de test precedente dans le but d'avoir une 
reelle visualisation et comprehension plus approfondie du produit pour l'ensemble des poles de l'entreprise.

## Éléments à tester
- Affichage de la liste des marques sans doublons
- Affichage de la liste des vehicules
- Suppression d'une voiture
- Ajout d'une voiture ( non mentionne dans les exigences )
- Modification des informations d'une voiture

## Problèmes de risque logiciel
- Erreurs de base de données lors de l'affichage ou de la suppression des voitures
- Affichage incorrect des marques ou des voitures
- Probleme de traduction 

## Approche
Les tests seront effectués de maniere automatisee a chaques nouvelles versions de developpement et production du projet.

## Critères de réussite/échec
- Succès : Toutes les fonctionnalités se comportent comme prévu sans erreurs.
- Échec : Une ou plusieurs fonctionnalités ne se comportent pas comme prévu.

## Critères de suspension et exigences de reprise
- Suspension : Si une fonctionnalité ne peut pas être testée en raison d'un défaut logiciel, les tests seront suspendus jusqu'à ce que le défaut soit corrigé. Ceci met donc le projet sur une situation d'echec temporaire et la majorite des ressources techniques seront allouees la resolution du defaut defini auparavant.

## Documentation
- La documentation des tests doit-etre comprehensible pour chacuns ainsi :
    - Chaques tests doivent etre definis par un titre representant la raison d'existence du test.
    - Chaques tests doivent pointees vers le fichier et la ligne testee

## Approbation
L'approbation doit se faire dans une direction verticale comme suit:
- Chef de projet: ...
- Product manager: ...
- Client: ...
