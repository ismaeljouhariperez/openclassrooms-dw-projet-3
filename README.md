# Projet 3 OpenClassrooms : Concevez une carte interactive de location de vélos

[![forthebadge](https://forthebadge.com/images/badges/uses-html.svg)](http://forthebadge.com)  [![forthebadge](https://forthebadge.com/images/badges/uses-css.svg)](http://forthebadge.com)  [![forthebadge](https://forthebadge.com/images/badges/made-with-javascript.svg)](http://forthebadge.com)

Vous devez développer une page de type "Single page Application" simulant la réservation de vélos dans une ville. Ces vélos sont répartis dans de nombreuses stations dans la ville. L'utilisateur doit pouvoir réserver un vélo depuis son navigateur. La réservation est alors temporairement enregistrée sur le navigateur du visiteur.

Cette application doit notamment, en s'appuyant sur JavaScript, afficher une carte avec la liste des stations de location de vélos disponibles dans la ville. 

## Instructions

- Vous devez afficher en haut de la page un diaporama de photos et de textes expliquant le fonctionnement de l'application. La logique du diaporama doit être écrite par vos soins. L’utilisation de tout plugin automatisant la logique de l’application est proscrite.

- En-dessous du diaporama se trouve une carte affichant en temps réel la liste des stations de location de vélos ainsi que leur disponibilité. La localisation de toutes les stations de vélos est affichée à l’aide de marqueurs.

- Un clic sur un marqueur affiche l’état de la station dans un panneau construit en HTML et CSS à côté de la carte.

### Fonctionnalités

- La localisation et l'état de chaque station (ouverte, en travaux, combien de vélos et de places sont disponibles, etc.) est fourni via la plateforme OpenData de JC Decaux.

- Les données de réservation seront stockées dans le navigateur à l’aide de l’API Web Storage et affichées en dessous du panneau. L'état de la réservation (s’il y en a une) est ainsi affiché, avec un décompte dynamique du temps restant avant expiration de la réservation.

- La carte doit être générée dynamiquement via un service de cartographie.

- Il doit être possible de réserver un vélo disponible à la station sélectionnée en signant dans un champ libre implémenté à l’aide de l’API HTML5 Canvas. Aucun plugin n’est autorisé.

### Contraintes techniques

Le code JavaScript doit être conçu en Programmation Orientée Objet.

Le code doit exploiter une API cartographique et l'API temps réel de API JCDecaux. Il doit également utiliser les API Web Storage et Canvas.

## URL du site hébergé

* [Site de l'application Bike Luxembourg](http://projet-3-oc.ismaeljouhari.com/)

## Fabriqué avec

* [LeafletJS](https://leafletjs.com/) - Librairie JS Open Source
* [Mapbox](https://www.mapbox.com/) - Affichage du layer de la carte
* [API JCDecaux](https://developer.jcdecaux.com/#/home) - API pour afficher stations en temps réel

## Versions
**Dernière version stable :** 1.0
**Dernière version :** 1.0
Liste des versions : [Cliquer pour afficher](https://github.com/mschmrn/openclassrooms-dw-projet-3/contributors/tags)

## Auteurs
Listez le(s) auteur(s) du projet ici !
* **Ismaël Jouhari** _alias_ [@mschmrn](https://github.com/mschmrn)

Lisez la liste des [contributeurs](https://github.com/mschmrn/openclassrooms-dw-projet-3/contributors) pour voir qui à aidé au projet !

