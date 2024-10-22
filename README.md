# Groupie Tracker

Groupie Tracker est une application web permettant de suivre et de gérer des informations sur des artistes et groupes via une API. Elle offre une interface utilisateur intuitive pour filtrer les données en fonction de différents critères (nom, genre musical, date de création, etc.). Le backend est développé en **Golang**, tandis que le frontend utilise **JavaScript**, **HTML**, et **CSS**.

## Fonctionnalités

- Récupération de données depuis une API externe sur des artistes et groupes.
- Filtrage des résultats en fonction des critères suivants :
  - Nom de l'artiste/groupe
  - Genre musical
  - Date de création
  - Membres du groupe
  - Lieu de concert (prochain concert)
- Affichage d'informations détaillées sur un artiste ou un groupe sélectionné.
- Interface utilisateur simple et réactive.

## Technologies utilisées

### Backend
- **Golang** : Utilisé pour la gestion du backend, des appels à l'API et du traitement des données.
  
### Frontend
- **JavaScript** : Utilisé pour la gestion des interactions dynamiques avec l'utilisateur, comme les filtres.
- **HTML** : Structure du site.
- **CSS** : Stylisation et mise en page de l'application.

## Prérequis

- **Go** version 1.18 ou supérieure
- **Node.js** et **npm** pour gérer les dépendances du frontend
- **API externe** : L'application utilise une API tierce pour obtenir les informations sur les artistes/groupes (à préciser dans le code).

## Installation

### Backend (Golang)
1. Clonez le repository :
    ```bash
    git clone https://github.com/username/groupie-tracker.git
    cd groupie-tracker
    ```

2. Installez les dépendances :
    ```bash
    go mod tidy
    ```

3. Lancez le serveur backend :
    ```bash
    go run main.go
    ```

Le serveur Go sera lancé sur `http://localhost:8080`.

## Utilisation

1. Accédez à l'interface web à l'adresse `http://localhost:8080`.
2. Utilisez les filtres disponibles pour affiner votre recherche :
   - Rechercher un artiste par nom.
   - Filtrer les résultats par genre musical.
   - Sélectionner les artistes en fonction de la date de création.
   - Rechercher les prochains concerts à un lieu donné.
3. Cliquez sur un artiste/groupe pour obtenir des informations plus détaillées (biographie, concerts, membres, etc.).
