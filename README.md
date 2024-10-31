# OPC_DATA_ANALYST_PROJET7
Analysez des indicateurs de l'égalité femme-homme avec Knime

# Diagnostic Égalité Femmes-Hommes - Cabinet de Consultant en Transformation Digitale

## Contexte

Je suis Data Analyst dans un cabinet de consultant spécialisé dans la transformation digitale des entreprises. Le cabinet, en pleine croissance, souhaite attirer des talents et améliorer sa marque employeur en adoptant une politique proactive en matière d’égalité femmes-hommes. Dans ce cadre, chaque année, il est nécessaire de publier un index de l’égalité femmes-hommes sur le site de l’entreprise avant le 1er mars, conformément à la réglementation.

Laura, la directrice des ressources humaines, m'a confié la mission d’aider Vincent, le contrôleur de gestion sociale, à automatiser la création d’un rapport diagnostique sur l’égalité professionnelle femmes-hommes.

## Objectifs du Projet

1. **Création d’un Workflow KNIME** : Automatiser le processus de création des graphiques pour le diagnostic en utilisant **KNIME**. Ce workflow doit être capable de générer des graphiques pour au moins 5 indicateurs clés de l’égalité professionnelle femmes-hommes, conformément aux recommandations du ministère du Travail.
   
2. **Préparation d’un Fichier CSV pour Tableau** : Transformer les données en un fichier `.csv` anonymisé, prêt à être utilisé dans **Tableau Software** pour de futures analyses.

3. **Respect des Normes RGPD** : Anonymiser les données issues du **Système d’Informations des Ressources Humaines (SIRH)** pour s’assurer de la conformité avec le RGPD.

## Étapes du Projet

### Étape 1 : Sélection des Indicateurs Clés

- **Objectif** : Choisir au minimum 5 indicateurs parmi ceux recommandés dans le document de présentation de l’outil Diagnostic Égalité, fourni par le ministère du Travail.
- **Indicateurs potentiels** :
  - Écart de rémunération entre les femmes et les hommes
  - Répartition des augmentations de salaire
  - Répartition des promotions
  - Part des femmes et des hommes dans les 10 plus hautes rémunérations
  - Écart de taux de promotion
- **Résultat** : Ces indicateurs seront utilisés dans le workflow pour générer des graphiques.

### Étape 2 : Création du Workflow KNIME

- **Objectif** : Construire un workflow dans **KNIME** pour générer automatiquement les graphiques des indicateurs sélectionnés.
- **Détails** :
  - Importer les données issues du SIRH.
  - Anonymiser les données sensibles pour respecter le RGPD.
  - Créer des visualisations pour chaque indicateur sélectionné.
  - Exporter les visualisations pour inclusion dans le rapport diagnostique.
- **Livrable** : Un workflow KNIME qui produit les graphiques du diagnostic.

### Étape 3 : Préparation du Fichier CSV pour Tableau

- **Objectif** : Préparer un fichier `.csv` anonymisé des données pour une utilisation future dans Tableau Software.
- **Détails** :
  - Structurer le fichier `.csv` pour qu'il soit compatible avec Tableau.
  - Assurer que les informations sensibles sont anonymisées.
  - Inclure les indicateurs sélectionnés dans le fichier.
- **Livrable** : Un fichier `.csv` prêt pour Tableau, contenant les indicateurs clés.

### Étape 4 : Présentation du Workflow et des Résultats

- **Objectif** : Présenter le fonctionnement du workflow et les graphiques générés à Laura et Vincent.
- **Détails** :
  - Expliquer les étapes du workflow, y compris l’anonymisation des données.
  - Montrer les graphiques pour les indicateurs sélectionnés et interpréter les résultats.
- **Livrable** : Une présentation en direct de KNIME, ou un document contenant les résultats du workflow.

## Détails Techniques

- **Fichiers** :
  - `donnees_sirh.zip` : Contient les données issues du Système d’Informations des Ressources Humaines, non anonymisées.
  - **Workflow KNIME** : Automatisation de la génération des graphiques de diagnostic.
  - **Fichier CSV** : Fichier de données anonymisé, prêt à être utilisé dans Tableau Software.

- **Outils Utilisés** :
  - **KNIME** pour l’automatisation des analyses et des visualisations.
  - **Tableau Software** pour les futures analyses de données.

- **Compétences Utilisées** :
  - Création de workflows automatisés pour le diagnostic de données.
  - Anonymisation des données pour conformité RGPD.
  - Préparation de données pour l’analyse dans Tableau.

## Résumé

Ce projet m’a permis d’automatiser la création d’un diagnostic sur l’égalité femmes-hommes au sein du cabinet, en répondant aux normes légales et aux exigences du RGPD. Grâce au workflow KNIME, nous avons optimisé la génération des indicateurs nécessaires, ce qui facilitera le suivi annuel de ces données et contribuera à renforcer notre marque employeur.
