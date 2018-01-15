# Windows_eedomus

Plugin pour gérer son PC Windows depuis sa Eedomus (Wake on lan si connecté en Ethernet, extinction, veille, redémarrage)
Vous devez par contre installer [Airytec](http://www.airytec.com/en/switch-off/get.aspx) et le configurer (Activer l'interface web et autoriser le port 8000 par ex)

## Configuration de Airytec

Aller dans votre systray

![systray](https://image.noelshack.com/fichiers/2018/02/7/1515934344-capture-d-ecran-2018-01-13-a-16-18-27.png)

Faites un clic droit sur l'icône puis options

![systray_clic](https://image.noelshack.com/fichiers/2018/02/7/1515934344-capture-d-ecran-2018-01-13-a-16-21-21.png)

Activer l'interface web

![options](https://image.noelshack.com/fichiers/2018/02/7/1515934344-capture-d-ecran-2018-01-13-a-16-18-38.png)

## Configuration du Firewall de Windows

Par défaut, le firewall de Windows va bloquer les connexions vers le port, il faut créer une règle pour laisser le port ouvert.
Voici la config sur Windows 7

Aller dans les paramètres avancés

![firewall](https://image.noelshack.com/fichiers/2018/02/7/1515934347-capture-d-ecran-2018-01-14-a-13-37.png)

Créer une nouvelle règle entrante

![firewallrule](https://image.noelshack.com/fichiers/2018/02/7/1515934346-capture-d-ecran-2018-01-14-a-13-45-39.png)

Celle-ci sera basée sur le port

![portforwarding](https://image.noelshack.com/fichiers/2018/02/7/1515934346-capture-d-ecran-2018-01-13-a-16-33-44.png)

Ajouter votre port

![port8000](https://image.noelshack.com/fichiers/2018/02/7/1515934858-capture-d-ecran-2018-01-14-a-13-59-25.png)

Autoriser la connexion

![autoriser](https://image.noelshack.com/fichiers/2018/02/7/1515934346-capture-d-ecran-2018-01-13-a-16-34-08.png)




