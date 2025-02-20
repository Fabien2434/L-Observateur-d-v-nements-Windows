# 🔬 Exercice

### Tâche:
#### Lance Event Viewer en utilisant Windows + R, tape eventvwr, et appuie sur Entrée.

Explore l'interface : quels sont les principaux types de journaux que tu vois ?

  - Application
  - Sécurité
  - Installation
  - Systéme
  - Evénement transférés

# 🔬 Exercice

### Tâche:

#### Crée un filtre dans le journal Sécurité pour montrer uniquement les événements de connexion des dernières 24 heures.

Analyse un événement d'information du journal Système : que te dit l'ID de l'événement ?

  - 4798

# 🔬 Exercice

### Tâche:

Trouve un événement critique ou d'erreur récent dans le journal Système.
  - 6008
Utilise l'ID de l'événement pour rechercher une solution ou des informations supplémentaires en ligne.

  - https://support.microsoft.com/fr-fr/topic/id-d-%C3%A9v%C3%A9nement-6008-est-enregistr%C3%A9-de-mani%C3%A8re-inattendue-dans-le-journal-des-%C3%A9v%C3%A9nements-syst%C3%A8me-une-fois-que-vous-arr%C3%AAtez-et-red%C3%A9marrez-votre-ordinateur-2e517ea0-e592-b3ad-d572-501c033f4567


<?xml version="1.0" encoding="utf-8" standalone="yes"?>
<Events><Event xmlns='http://schemas.microsoft.com/win/2004/08/events/event'><System><Provider Name='Microsoft-Windows-DNS-Server-Service' Guid='{71a551f5-c893-4849-886b-b5ec8502641e}'/><EventID>4013</EventID><Version>0</Version><Level>3</Level><Task>0</Task><Opcode>0</Opcode><Keywords>0x8000000000020000</Keywords><TimeCreated SystemTime='2025-02-19T13:25:02.6560439Z'/><EventRecordID>183</EventRecordID><Correlation/><Execution ProcessID='2868' ThreadID='3112'/><Channel>DNS Server</Channel><Computer>SRVWIN-EKO.Ekoloclast.lan</Computer><Security UserID='S-1-5-18'/></System><EventData Name='DNS_EVENT_DS_OPEN_WAIT'></EventData><RenderingInfo Culture='fr-FR'><Message>Le serveur DNS attend que les services de domaine Active Directory indiquent que la synchronisation initiale du répertoire est terminée. Ce service du serveur DNS ne peut pas démarrer tant que la synchronisation initiale n’est pas terminée car les données DNS essentielles ne sont peut-être pas encore répliquées sur ce contrôleur de domaine. Si les événements du journal des événements des services de domaine Active Directory indiquent un problème de résolution de nom DNS, envisagez d’ajouter l’adresse IP d’un autre serveur DNS de ce domaine à la liste des serveurs DNS dans les propriétés de protocole Internet de cet ordinateur. Cet événement sera consigné toutes les deux minutes jusqu’à ce que les services de domaine Active Directory indiquent que la synchronisation initiale est terminée.</Message><Level>Avertissement</Level><Task></Task><Opcode>Informations</Opcode><Channel></Channel><Provider>Microsoft-Windows-DNS-Server-Service</Provider><Keywords></Keywords></RenderingInfo></Event></Events>
