# Simulateur de Gestion de Parking – GAMA Platform

## 📝 Description du projet
Ce projet est un **simulateur de gestion de parking** développé sous **GAMA Platform**.  
Il permet de modéliser et simuler le comportement d’un parking comprenant plusieurs types de places, différentes tailles de voitures, des points d’entrée et de sortie, ainsi qu’un système dynamique d'arrivée et de départ des véhicules.

Le simulateur vise à analyser :
- L’occupation des places
- Les flux d’entrée et de sortie
- Les conflits d’allocation
- L’efficacité globale du parking
- (Optionnel) L’optimisation de l’affectation via un algorithme génétique

Ce modèle peut servir de base à des études en :
- Gestion des transports
- Logistique urbaine
- Analyse des systèmes complexes
- Optimisation multi-agents

---

## 🧩 Fonctionnalités principales
- Génération automatique de voitures de tailles différentes
- Places de parking classées par catégories (petite, moyenne, grande)
- Attribution d’une place selon la taille du véhicule
- Gestion des entrées et sorties avec files d’attente
- Déplacement autonome des voitures jusqu’aux places
- Libération des places après un temps défini
- Visualisation en temps réel du parking
- Statistiques de simulation :
  - Taux d’occupation
  - Nombre de voitures acceptées / refusées
  - Temps moyen d’attente
  - Efficacité globale

### Fonctionnalités avancées (si activées)
- Optimisation par **algorithme génétique** (GAMA Genetic Operators)
- Recherche du meilleur schéma d’allocation ou meilleure disposition des places
- Comparaison entre stratégies (first-fit, best-fit, aléatoire)

---

## 🏗️ Structure du projet
