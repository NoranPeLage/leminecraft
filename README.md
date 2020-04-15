# leminecraft

papermc doc : https://paper.readthedocs.io/en/latest/server/getting-started.html

pour lancer le serveur : 
java -Xms2G -Xmx2G -jar paper-###.jar

The amount of RAM can be set by changing the numbers in the -Xms and -Xmx arguments. Genre la cest 2Go de RAM

Pour rendre le serveur visible de l'exterieur:
faire une regle NAT dans la config de sa box pour transferer les requetes sur le port 25565 vers la machine sur laquelle tourne le serveur

Pour avoir une adresse stylée plutot qu'une IP, faire un dynDNS sur noip.com par exemple
