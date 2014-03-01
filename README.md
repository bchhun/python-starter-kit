# python-starter-kit


Pour faciliter la vie de mes mentorés ALTIMaître.

Le but de ce petit projet est de faciliter le démarrage d'un environnement de travail pythonique, et ce, peu importe la nature du système d'exploitation hôte.

## Dépendances

### [VirtualBox](https://www.virtualbox.org/)

Téléchargez et installez la dernière version correspondant à l'architecture et au système d'exploitation de votre ordinateur.

### [Vagrant](http://www.vagrantup.com/downloads.html)

Téléchargez et installez la dernière version correspondant à l'architecture et au système d'exploitation de votre ordinateur.

## Procédures pour monter la VM de développement

1. Installez les dépendances mentionnées plus haut
2. Déposez le code de votre projet dans le dossier *src*
2. Rendez vous dans le dossier *vagrant*
3. Tapez la commande ```vagrant up```
4. Une fois que tout le processus de la création de la VM a été finalisé, tapez ```vagrant ssh```
5. Vous êtes maintenant dans la machine virtuel et votre code est partagé ici dans le dossier ```/home/vagrant/python-starter-kit```

## FAQ

### Quels sont les commandes vagrant utiles ?

Toutes les commandes ci-dessous doivent être éxécutés dans le dossier vagrant de la manière suivante:

    vagrant [nom de la commande]

* **up**: pour créer la machine virtuel
* **destroy**: détruire la machine virtuel
* **ssh**: pour se connecter en SSH sur la machine virtuel
* **suspend**: pour mettre la machine virtuel en pause
* **resume**: pour remettre une machine virtuel en marche

