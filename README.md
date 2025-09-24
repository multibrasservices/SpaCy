# Graphe de Connaissances Unifié - Bibliothèque spaCy

[![Website](https://img.shields.io/badge/Accéder_au_graphe-Live-blue?style=for-the-badge)](https://multibrasservices.github.io/SpaCy/)

Ce projet présente un **graphe de connaissances interactif unifié** pour l'apprentissage de la bibliothèque Python **spaCy**. Il fusionne deux perspectives :

1.  Les **concepts fondamentaux** de spaCy (objets `Doc`, `Token`, `Span`, `Matcher`, etc.).
2.  Le **flux de travail pratique** d'un projet de Reconnaissance d'Entités Nommées (NER), de la lecture des données à l'entraînement du modèle.

L'objectif est de fournir une ressource d'apprentissage complète et dynamique, montrant non seulement les "briques" de spaCy, mais aussi comment les assembler dans un projet concret.

**[➡️ Accéder à la version live du graphe](https://multibrasservices.github.io/SpaCy/)**

## ✨ Aperçu

*(N'oubliez pas de mettre à jour la capture d'écran pour montrer le nouveau graphe fusionné !)*

![Aperçu du graphe de connaissances unifié spaCy](kg.PNG)

## 🚀 Fonctionnalités

*   **Vue d'Ensemble Complète** : Visualisez sur un seul graphe les objets principaux de spaCy et leur application dans un pipeline de projet NER.
*   **Relations Logiques** : Les arêtes (flèches) illustrent les interactions clés (ex: un `Modèle (nlp)` *produit* un `Objet Doc` qui *contient* des `Token`).
*   **Panneau d'Information Dynamique** : Cliquez sur n'importe quel nœud pour afficher dans le panneau de droite une description détaillée et les opérations ou attributs Python associés.
*   **Groupement par Couleur** : Les nœuds sont regroupés par couleur pour identifier instantanément leur rôle (Flux de données, Cœur de spaCy, Annotations, Entraînement, Outils...).

## 📄 Source & Crédits

Ce graphe a été initialement inspiré par le contenu et la structure de l'excellent tutoriel **"Initiation à la reconnaissance d'entités nommées avec spaCy"** de **Joseph Chazalon**. Ce cours reste une ressource fondamentale pour une compréhension approfondie du sujet.

➡️ **[Dépôt GitHub du tutoriel original : jchazalon/hn-ariane-ner-tuto-2023](https://github.com/jchazalon/hn-ariane-ner-tuto-2023)**

Le projet a ensuite été étendu pour intégrer les concepts de base de spaCy afin de créer une ressource d'apprentissage unifiée.

## 🛠️ Technologies utilisées

*   **HTML5** : Structure de la page.
*   **CSS3** : Style et mise en page.
*   **JavaScript (ES6)** : Logique d'interaction et manipulation des données.
*   **[Vis.js Network](https://visjs.github.io/vis-network/docs/network/)** : La bibliothèque Javascript qui génère et anime le graphe interactif.

## 💻 Utilisation locale

Si vous souhaitez exécuter ou modifier ce projet sur votre machine :

1.  Clonez le dépôt :
    ```bash
    git clone https://github.com/MultiBrasServices/SpaCy.git
    ```
2.  Naviguez vers le dossier du projet :
    ```bash
    cd SpaCy
    ```

3.  Ouvrez le fichier `index.html` directement dans votre navigateur web.
