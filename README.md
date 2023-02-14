# StageCampus
Projet de stage pour une recherche de texte dans des repository Github

# Recherche Github
[![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://dimoscore-orange-space-happiness-575gxppxg4j3pxxg.github.dev/)

## Présentation de mon stage
Objectif du stage : trouver un code et l'utiliser pour avoir un programme de recherche d'informations dans des projets sur Github et identifier dans ces projets des chaines de caractères qui ne doivent pas s'y trouver, pour des raisons de sécurité.

* Ce projet utilise un environnement de développement virtuel nommé CodeSpaces et proposé aux développeurs par Github. Et qui permet de développer sur le projet depuis n'importe où,
* Le composant utilisé est écrit en Python et permet de faire des recherches dans des "repositories" de code,
* L'objectif est de disposer d'un outil pour faire des recherches de chaînes de caractères dans du code et identifier des problèmes pour les corriger.

## Exemples d'utilisations
### Récupérer tout mon projet Marvel
```
curl https://github.com/Dimoscore/Site-Marvel
```
### Récupérer mon projet Marvel avec les header HTTP
```
curl -- include https://github.com/Dimoscore/Site-Marvel
```

# Références de stage
* Article : https://stateful.com/blog/github-search-api