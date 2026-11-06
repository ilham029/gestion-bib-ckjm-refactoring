# Gestion de Bibliothèque — Refactoring CKJM

Ce projet a été réalisé dans le cadre du TP d'analyse des métriques orientées objet avec CKJM.

## Objectif
Analyser la complexité, le couplage et la cohésion des classes Java, puis proposer des améliorations.

## Modifications réalisées
- Déplacement de `complexMethodExample()` de `Book` vers `NumberAnalyzer`.
- Modification de `LibraryApp` pour utiliser la nouvelle classe.
- Analyse et comparaison des métriques CKJM avant et après refactoring.

## Technologies
- Java
- CKJM 1.8

## Résultats
Le refactoring a permis de réduire certaines métriques de `Book`, notamment WMC, RFC et LCOM.
