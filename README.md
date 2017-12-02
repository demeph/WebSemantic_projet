# WebSemantic_projet

## Description

L’objectif du projet est de transformer les données ouvertes de l'Enseignement supérieur, de la Recherche et de l'Innovation (https://data.esr.gouv.fr/FR/) en données sémantiques et de lier ces données sémantiques au cloud.

**Provenance des données :** https://data.enseignementsup-recherche.gouv.fr/explore/dataset/fr_esr_budgets-de-recherche-et-de-transfert-de-technologie-rt-des-collectivites-/

## Organisation du dépot :

-> Le répertoire **data** contient les jeux de données .csv
-> Le répertoire **inférence** contient les fichiers liés aux inférences, ils s'éxécutent à l'aide de Apache-Jena Fuseki
-> Le répertoire **linked_data** contient les jeux de données, les constructs et les fichiers rdf obtenus pour liés nos données
-> Le répertoire **query** contient le construct de base ainsi que quelques requêtes
-> Le répertoire **rapport** contient le rapport de projet
-> Le réperoire **slides_presentation** contient les slides de la présentation du 7 novembre 2017
-> le répertoire **VoID** contient un fichier descrivant notre jeux de données à la manière Vocabulary of Interlinked Datasets

## Outils :

**TARQL :** utilisé pour générer les fichiers rdf
**Apache-Jena Fuseki :** utilisé pour tester les requêtes et faire l'inférence
