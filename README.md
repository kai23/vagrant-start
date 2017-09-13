# Le fit de démarrage du bon développeur JS sous windows

## Télécharger et installer Vagrant

Vagrant un outil de virtualisation disponible pour Windows.

Celui-ci est disponible ici : https://www.vagrantup.com/downloads.html

## cloner le projet

En faisant quelque chose d'aussi simple que `git clone https://github.com/kai23/vagrant-start`

## Télécharger la box nécessaire dans le projet

En utilisant le lien suivant : http://s.kai23.fr/vagrant.box

## Mettre à jour son fichier host

En rajoutant la ligne suivante :

```
127.0.0.1 site.lo
```

## Lancer vagrant

en faisant un `vagrant up --provision` dans le dossier.

## Lancer le projet

1. Faire un `vagrant ssh` dans le dossier
2. `cd /vagrant/projet`
3. `node index.js`

Puis ouvrir son navigateur sur `http://site.lo` 

