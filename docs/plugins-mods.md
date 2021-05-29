# Comment ajouter des mods/plugins/datapacks à mon serveur ?

* ### Mods
    * #### Télécharger des Mods
        Vous pouvez télécharger des mods depuis des sites tels que [CurseForge](https://www.curseforge.com/) ou [Minecraft Mods](https://www.minecraftmods.com/).
    * #### Installer des Mods
        Pour installer les mods téléchargés, votre serveur doit forcément utiliser Forge. Pour en créer un de ce type, voir [ici](#setup-forge).
        Ensuite, naviguez vers le dossier de votre serveur. Il se situe dans le dossier d'installation de MCSS sous le chemin `/servers/<votre-serveur>`. Vous pouvez aussi y acceder directement depuis MCSS en cliquant sur `Server > Show in file explorer`.
        Il devrait y avoir un dossier `mods`, si il n'existe pas essayer de lancer le serveur puis de l'arrêter. Si vous ne voyez toujours pas ce dossier, créez-le : il doit s'appeler exactement `mods`. Pour finir, déposez les fichiers .jar de vos mods dans le dossier mods et (re)démarrez votre serveur.
* ### Plugins
    * #### Compatibilité des Plugin
        |  | Bukkit (serveur) | Spigot (serveur) | Paper (serveur) | Sponge (serveur) |
        |---|---|---|---|---|
        | Bukkit (plugin) | ✅ | ✅ | ✅ | ❌ |
        | Spigot (plugin) | ❌ | ✅ | ✅ | ❌ |
        | Paper (plugin) | ❌ | ❌ | ✅ | ❌ |
        | Sponge (plugin) | ❌ | ❌ | ❌ | ✅ |
    * #### Télécharger des Plugins
        Vous pouvez télécharger des plugins depuis des sites tels que [Spigot](https://www.spigotmc.org/resources/) ou [Bukkit](https://dev.bukkit.org/).
    * #### Installer des Plugins
        Pour installer les mods téléchargés, votre serveur doit forcément utiliser Spigot, Bukkit, Paper ou Sponge. Pour en créer un de ce type, voir [ici](./create-server.md).
        Ensuite, naviguez vers le dossier de votre serveur. Il se situe dans le dossier d'installation de MCSS sous le chemin `/servers/<votre-serveur>`. Vous pouvez aussi y acceder directement depuis MCSS en cliquant sur `Server > Show in file explorer`.
        Il devrait y avoir un dossier `plugins`, si il n'existe pas essayer de lancer le serveur puis de l'arrêter. Si vous ne voyez toujours pas ce dossier, créez-le : il doit s'appeler exactement `plugins`. Pour finir, déposez les fichiers .jar de vos plugins dans le dossier plugins et démarrez votre serveur.
* ### Datapacks
    * #### Télécharger des Datapacks
        Vous pouvez télécharger des mods depuis des sites tels que [Planet Minecraft](https://www.planetminecraft.com/data-packs/).
    * #### Installer des Datapacks
        Téléchargez le datapack. Il devrait avoir la forme d'un fichier .zip.
        Pour utiliser des datapacks, votre serveur doit forcément être en version 1.13 ou plus. Pour mettre à jour un serveur, voir [ici](./update-server.md).
        Ensuite, naviguez vers le dossier de votre serveur. Il se situe dans le dossier d'installation de MCSS sous le chemin `/servers/<votre-serveur>`. Vous pouvez aussi y acceder directement depuis MCSS en cliquant sur `Server > Show in file explorer`.
        Ouvrez le dossier contenant le monde de votre serveur (le plus souvent nommé `/world`). Dans celui-ci, vous trouverez un dossier `/Datapacks`, déposez-y les fichiers .zip de vos datapacks. Enfin, redémarrez le serveur.
        Vous pouvez vérifier que vos datapacks ont bien été activés en tapant `/datapacks list enabled` dans la console ou en tant qu'opérateur du serveur. Vous verrez alors la list de tous les datapacks actifs sur le serveur.

