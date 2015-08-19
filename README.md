# BuildToolbox
SpigotMC's BuildTools fork that allows easier creation of Spigot custom builds
## Building BuildToolbox
Just use Maven 3. Simple and fast.

## How To
* Fork any of Bukkit/CraftBukkit/Spigot/Builddata repository
* Make your changes to the code - I don't care about what you do - and push them to a git repository
* Create a file ``settings.json`` inside the JAR folder
* A full ``settings.json`` file looks like this: 
```
{
 "bukkitRepo":"https://user@mygitserver.tld/bukkit.git",
 "craftbukkitRepo":"https://user@mygitserver.tld/craftbukkit.git",
 "spigotRepo":"https://user@mygitserver.tld/spigot.git",
 "builddataRepo":"https://user@mygitserver.tld/builddata.git",
 "versionUrl":"https://mywebserver.tld/versions/"
}
```
* Every field of the ``settings.json`` file is optional, missing values will be replace with standard BuildTools' ones.
  * Make sure to create a correct versions system, just reply [SpigotMC's one](https://hub.spigotmc.org/versions/) and place your commits hashes - if you leave SpigotMC's one, you'll build standard Spigot sources!
* Run your JAR
* If you're lucky ( ¯\_(ツ)_/¯ ) you should get your nice custom Spigot JAR, as well as CraftBukkit one
## Disclaimer
A big chunk of this tool is unchanged code from Spigot BuildTools repository, I own very few rights on it. This tool is released under the same license as the original tool.
Also, please forgive any mistake in this text as I am not an English native speaker.
