# projetNOsql

#OBJECTIF

Réalisé une application web  de gestion de stock  d'un magasin.

Front : 

2 page , une page pour saisir un nouvel article et l'enregistrer dans la base mongodb , et une page de recherche

back :

#Etape 1

Charger une collection mongoDB avec des articles ( designation , prix unitaire)

#Etape 2

faire un système de recherche qui me permet de chercher des articles dans la base mongo

#Etape 3

chaque recherche est stocké dans une base redis  (durée de vie 1h)

#Etape 4 

A chaque recherche on vient vérifier sur l'articles est présent dans redis si oui on le recupère de redis sinon de mongoDB
