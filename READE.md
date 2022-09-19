# La Méthide Merise En Conception Des Données

# L'énoncé du projet 👮‍♀️

- Votre client, une agence de voyages, souhaite proposer la possibilité de réserver en ligne des billets d'avion à leurs clients.

- Votre mission est de concevoir à l'aide du standard UML la modélisation de la plateforme.

---

    La plateforme devra permettre que :

    * Un vol est ouvert à la réservation et refermé sur ordre de la compagnie.
    * Un vol peut être annulé par la compagnie
    * Un client peut réserver un ou plusieurs vols, pour des passagers différents.
    * Une réservation concerne un seul vol et un seul passager.
    * Une réservation peut être annulée ou confirmée.
    * Un vol a un aéroport de départ et un aéroport d’arrivée.
    * Un vol a un jour et une heure de départ, et un jour et une heure d’arrivée.
    * Un vol peut comporter des escales dans des aéroports.
    * Une escale a une heure d’arrivée et une heure de départ.
    * Chaque aéroport dessert une ou plusieurs villes.
    * Des compagnies aériennes proposent différents vols.

---

# Modalités pédagogiques 🛠

    - Travail en individuel.
    - Livraison pour Mardi 20 Septembre 2022 09h00.

# Critères de performance ⚙️

    - Un readme répertoriant les informations principales.
    - Tous les diagrammes doivent correspondre à la notation officielle du standard UML et Merise
    - Les diagrammes doivent être exportés en format images facilement consultables (jpeg, png).
    - Minimum d'un commit par diagramme.
    - La conception Merise doit respecter au minimum les 3 premières formes normales.

# Modalités d'évaluation 👍

    - Correction en groupe et revue des diagrammes sur Github

# Livrables ⏳

    Dans un dépôt Github :
    Pour la base de données :
    * Un MCD
    * Un MLD
    * Un MPD

    Pour l'application :
    * Un dictionnaire de données
    * Des règles de gestion
    * Un diagramme de cas d'utilisation
    * Un diagramme de classe
    * Un diagramme de Séquence.

# Règles de gestion ⛓  

        --------RESERVATION 🧾--------  
    - Un email de contact
    - Un numéro de téléphone
    - Nom
    - Prenom
    - Un n° de passport
    - Peu être annuler par le client
    - Une réservation ne peu être que pour une seul personne et un seul vol
    - Numéro de réservation
    - Peu être confirmé par l'agence

        --------VOL 🛫--------
    - Le vol contient un numero de vol  
    - aeroport de depart, une date, une heure
    - Aeroport d'arrive, une date, une heure  
    - Vol avec un ou plusieur passager  
    - Un vol ne peux pas être reservable ou non  
    - Un vol peut faire des escale
    - Le vol est un trajet d'un aeroport à un autre
    - Un vol peut être annulé par la compagnie
     

        --------COMPAGNIE 🏪--------
    - Contiens un nom
    - Peu avoir un ou plusieurs vol

        ---------ESCALE 🔗---------
    - Une date et une heure d'arrivé  
    - Une date et une heure de départ  
    - Un aeroport d'arrivé  
    - Un aeroport de dépar 

        --------AEROPORT 🛩--------
    - Ue trouve dans une ville  

        --------VILLE 🌇--------

    - Un nom de ville
    - Se trouve dans un pays

        --------PAYS🌎--------
    - Nom de pays


  