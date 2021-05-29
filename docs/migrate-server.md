# Migrer un serveur existant

## Choisir un type de serveur

Il y a quelques types de serveurs parmi lesquels choisir. Sélectionnez celui qui correspond au serveur que vous voulez importer.

![Part of a screenshot of the create instance window, slightly faded out towards the bottom](assets/screenshots/migrate_server_type.png)

## Détails et importation de l'ancien serveur

Vous allez maintenant modifier les détails de votre serveur.

Nom du réglage | Description
--- | ---
Server Name | Un nom pour votre serveur, visible seulement par vous.
Folder Path | Un chemin unique vers le serveur, stocké dans le dossier /servers.
Startup Line | La ligne de commande pour démarrer le serveur. Il est tentant de changer la variable ***[RAM]*** mais il est déconseillé de le faire. À la place, utilisez le champ approprié : ***Server Ram***
Server Ram | La quantité de RAM que votre serveur pourra utiliser.


![Screenshot of the migrate instance window where you can change the server settings](assets/screenshots/migrate_server_settings.png)

Ensuite, cliquez sur l'icône de dossier verte et naviguez jusqu'à l'emplacement du serveur que vous migrez. Sélectionnez le jar du serveur.

![Part of a screenshot of the migrate instance window, slightly faded out towards the bottom](assets/screenshots/migrate_server_start.png)

Avant de cliquer sur 'Migrate', assurez-vous que l'ancien serveur est éteint.

## Finaliser

Tout est terminé !

![Screenshot of the create instance window](assets/screenshots/migrate_server_finished.png)
