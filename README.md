# Modélisation de l'Évolution de la Température Globale Moyenne sur Terre

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![MATLAB](https://img.shields.io/badge/MATLAB-R2019b%2B-orange)
![License](https://img.shields.io/badge/License-MIT-green)

## 📋 Description

Ce projet propose une analyse comparative de **4 modèles climatiques** de complexité croissante pour simuler l'évolution de la température moyenne terrestre. Le travail s'inscrit dans le cadre du cours INFO-F305 : Modélisation et simulation.

### Modèles implémentés

1. **Modèle 1** : Équilibre radiatif simple (sans atmosphère)
2. **Modèle 2** : Inclusion de l'émissivité atmosphérique (effet de serre)
3. **Modèle 3** : Paramétrisation linéaire du rayonnement sortant (OLR)
4. **Modèle 4** : Albédo variable avec rétroaction glace-température

## 🎯 Objectifs

- Comprendre les mécanismes physiques du bilan énergétique terrestre
- Quantifier l'effet de serre naturel (~34 K)
- Analyser les rétroactions climatiques (albédo-glace)
- Comparer les prédictions avec les observations (T_moy ≈ 15°C)

## 📊 Résultats Principaux

| Modèle | T_équilibre (°C) | Écart vs. Obs. | Erreur relative |
|--------|------------------|----------------|-----------------|
| Modèle 1 | -18.7 | -33.7 K | 11.7% |
| Modèle 2 | **15.1** | +0.1 K | **0.03%** |
| Modèle 3 | 19.7 | +4.7 K | 1.6% |
| Modèle 4 | 14.8 | -0.2 K | 0.07% |
| **Observation** | **15.0** | — | — |

## 🚀 Installation et Utilisation

### Prérequis

#### Pour Python
```bash
# Python 3.8 ou supérieur
python --version

# Bibliothèques requises
pip install numpy scipy matplotlib
