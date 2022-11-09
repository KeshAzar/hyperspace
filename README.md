# Hyperspace
Simuler l'hyperspace avec seulement du css

# Installation sur le serveur
-> Création d'une VM sur Apache
-> Connexion en SSH
-> Mise à jour préventive d'apt-get et installation d'apache
```sh
apt-get update
apt-get install apache2
```
-> Création d'une clé SSH et ajout de la clé dans le profil Github
``` sh
ssh-keygen -t rsa*
```
-> Récupération du git via git clone 
``` sh
git clone git@github.com:KeshAzar/hyperspace.git
```
-> Ajout des fichiers clonés dans le dossier apache
```sh
cp /hyperspace/* /var/www/html
```
