# serveur-DHCP
- Aller sur la VM Windows Server 2022

## Gestionnaire de serveur:
- Gerer
- Ajouter des rôles et fonctionnalités

### Assistant Ajout rôles et fonctionnalités.
Suivre l'assistant étapes par étapes

#### Rôles de serveurs
- séléctionner "Serveur DHCP"
- Fonctionnalité (laiser comme c'est)
Puis installer le serveur.

Revenir dans le gestionnaire de serveur, aller sur le drapeau en haut à droite, cliquer dessus, et faire terminer configuration.

Aller dans le menu démarrer, outils d'administration windows, cliquer sur DHCP.

## console DHCP
- Dérouler la flèche
- Séléctionner IPv4, puis clique gauche nouvelle étendu.


### Assistant nouvelle étendu
- Donner un nom à l'étendu
- Mettre une plage d'adresse IP (début et fin)
Faire suivant jusqu'à la confirmation de l'étendu.

## Changer son IP
Il faut aller dans les parametres de connexion afin de changer, l'IP de sa machine server, afin que les autres VM puisse obtenir une adresse. 
