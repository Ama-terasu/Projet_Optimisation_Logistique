# 📦 Supply Chain Logistics Optimization & Penalty Dashboard

## 📊 Présentation du Projet
Ce projet avancé simule une optimisation logistique pour un distributeur de matériel électronique international. L'objectif était de calculer automatiquement les dérives de livraison, de cartographier l'impact financier des retards via un système de pénalités dynamiques par transporteur, et de fournir une analyse d'aide à la décision.

## 🛠️ Fonctionnalités & Formules implémentées
* **Gestion des seuils de retard :** Formule permettant de calculer l'écart de jours sans générer de retards négatifs.
* **Liaison de bases de données (XLOOKUP) :** Extraction dynamique des coûts de pénalité journaliers par transporteur depuis un onglet de référence pour calculer l'impact financier en temps réel.
* **Logique conditionnelle (IF/SI) :** Automatisation du statut de livraison ("Retard" vs "A temps").
* **Mise en forme conditionnelle avancée :** Alerte visuelle automatique sur les lignes critiques générant plus de 300 € de pénalités.
* **Business Intelligence (TCD) :** Analyse croisée de la performance financière et des volumes de vente par transporteur pour optimiser le choix des futurs prestataires logistiques.
