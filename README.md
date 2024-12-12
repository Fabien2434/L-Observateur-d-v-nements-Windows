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
Il faut aller dans les parametres de connexion, afin de changer l'IP de sa machine server, pour que les autres VM puisse obtenir une adresse. 
nous pouvons voir que cela est bon en faisant, un IPCONFIG qui nous prouve bien que la machine à obtenu une adresse IP, ou alors sur le serveur DHCP ou nous pouvons voir, notre utilisateur.

## Réservation IP
Dans le serveur DHCP, il y a un onglet réservation
- clique droit dessus
- réservation
- remplir les champs demander
- puis valider

C'est bon vous venez de faire votre premiére réservation, plus qu'a lancer votre machine elle aura directement cette adresse. 
Même si vous faites, un IPCONFIG /RELEASE & IPCONFIG /RENEW, elle gardera la même adresse.
