# README

Bienvenue à cette petite application conçu pour gérer la base des données qui contient la liste des magasins partenaires de Shopmium.

Quelques informations pour utiliser l'application:

* Version de Ruby : 2.4.0
          de Rails : 5.1.1
                 
* La base des données : mySQL2, veuillez changer le "username" et le "password" dans le fichier "config/database.yml" selon la configuration de votre ordinateur.
                        

* Initialisation de la base des données : 
            Pour créer la base des données il faut lancer cette commande sur le terminal : 
                        `ShopmiumIntern User$ rake db:create`
            Pour migrer la table avec tous ses attribus il faut lancer cette commande  sur le terminal :
                        `ShopmiumIntern User$ rake db:migrate`

* Gems ajoutés :                         
                        
                 # Pour utiliser bootstrap
                 gem 'twitter-bootstrap-rails', '~> 3.2', '>= 3.2.2'
                 
                 # Pour utiliser la carte geographique
                 gem 'geocoder', '~> 1.4', '>= 1.4.4'
                 
                 # Pour calculer les distances depuis une position
                 gem 'geokit-rails'

Pour installer un Gem il suffit d'éxecuter la commande : 
                 `ShopmiumIntern User$ gem install [nom du gem]`
                    
* Utilisation de l'application : - Demarrer le serveur avec la commande : `ShopmiumIntern User$ rails server`
                                 - Rendez vous sur un navigateur et allez sur le lien "localhost:3000/"
                                 - Dans la premiere page vous allez trouver un tableau qui contiendra la liste des magasins, avec des actions (voir, modifier, ou supprimer un magasin) à côté de chaque ligne. Vous allez aussi trouver une partie pour importer toute une liste depuis un fichier CSV.

