# symfony-assignment

L’objectif de cet exercice est de créer une application web permettant d’afficher une liste de vols via un tableau.
Cette liste de vols sera administrable via un back-office sécurisé en fonction d’une hiérarchie de rôles.
– le numéro du vol (il devra être généré aléatoirement grâce à une chaîne de caractères et devra comporter deux
lettres et quatre chiffres. Ex. : NG4567) ;
– l’horaire de départ (il s’agit d’une propriété de type datetime) ;
– la ville de départ ;
– l’horaire d’arrivée (il s’agit d’une propriété de type datetime) ;
– la ville d’arrivée ;
– le prix ;
– l’étiquette de réduction (booléen) ;
– le nombre de places à réserver.
Les villes auront seulement un nom pour attribut.
Fig.1 Un tableau avec les vols © Skill and You
Administration.
Création des formulaires pour :
– créer un nouveau vol ;
– éditer un nouveau vol ;
– supprimer un nouveau vol ;
– ajouter une ville.

Proposer la création d’une ville et d’un vol directement sur la page d’accueil uniquement lorsque l’utilisateur
connecté a le rôle Administrateur.
