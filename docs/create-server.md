# Créer un serveur

---

## Choisir un type de serveur

Il y a plusieurs types de serveurs disponibles. Si vous créez votre premier serveur ou si ces types de serveurs sont nouveaux pour vous, il est important que vous sachiez ce que chacun font et ce qu'ils apportent.

Certains se concentrent sur les fonctionnalités, les performances, ou les deux.

> Plus d'informations peuvent être trouvées sur la page [Types de serveurs](./server-types.md)

![Part of a screenshot of the create instance window, slightly faded out towards the bottom](assets/screenshots/create_server_type.png)

## Détails et acceptation de la licence de Minecraft

C'est le moment de modifier tous les détails de votre serveur.

Nom du réglage | Description
--- | ---
Server Name | Le nom de votre serveur, visible seulement par vous.
Folder Path | Un chemin unique pour votre serveur, stocké dans le dossier /servers.
Startup Line | La ligne de commande pour démarrer le serveur. Il est tentant de changer la variable <var>[RAM]</var>, mais il est  fortement déconseillé de le faire. À la place, utilisez le champ approprié :  <var>Server Ram</var> <br><br> ***Par défaut :*** `java -Xms256M -Xmx[RAM]M -jar {0}.jar --nojline`
Server Ram | La quantité de RAM que votre serveur pourra utiliser. Si c'est votre premier serveur, gardez la valeur par défaut et augmentez si nécessaire. <br><br>***Par défaut :*** 1024 Mo
Server Port | Ceci est le port logiciel de votre ordinateur qui sera utilisé par le serveur pour envoyer et recevoir des données. Le port par défaut est le <var>25565</var>, si vous voulez avoir plusieurs serveurs en même temps, vous pouvez simplement l'augmenter de 1 à chaque fois.<br><br> **Par défaut :** 25565

![La fenêtre de création du serveur](assets/screenshots/create_server_eula.png)

Acceptez la [licence](https://account.mojang.com/documents/minecraft_eula) (EULA) pour continuer.

## Ajouter les fichiers du serveur avec l'updater

![Screenshot of the create instance window](assets/screenshots/create_server_files.png)

Cliquez sur 'Open Updater Tool'. Depuis la version 10.0.4.4, les fichiers des serveurs ne sont plus fournis. Vous devrez utiliser  [l'updater tool](./update-server) pour les obtenir.

Une fois cette étape terminée, cliquez sur 'Create Server', cela devrait prendre seulement quelques secondes.

## Finaliser

Tout est terminé ! Facile non ?

![Screenshot of the create instance window](assets/screenshots/create_server_finished.png)
