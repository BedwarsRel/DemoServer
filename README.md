# BedwarsRel Demo-Server

This project provides you with a complete Minecraft multiplayer server setup including a working [BedwarsRel](http://www.github.com/BedwarsRel/BedwarsRel) setup for demonstration purpose.

## How to use

- Clone the repository
- [Download](https://mcadmin.net) a Spigot or CraftBukkit `.jar` and place it in the repository directory
- Open a console and run `java -jar <FILENAME>.jar`
- Accept the EULA with editing eula.txt
- Open a console and run `java -jar <FILENAME>.jar` again
- Join your server via Minecraft multiplayer server list
- You may grant operator permissions to your account with typing `op <ACCOUNT>` in the console

## Commands we used for setting up the game

```
/bw addgame Demo 2
/bw setbuilder Demo BedwarsRel-Team
/bw regionname Demo Demo

/mvtp Arena
/bw addteam Demo Blue Blue 4
/bw setspawn Demo Blue
/bw setspawner Demo Bronze
/bw setspawner Demo Iron
/bw setspawner Demo Gold

/bw addteam Demo Red Red 4
/bw setspawn Demo Red
/bw setspawner Demo Bronze
/bw setspawner Demo Iron
/bw setspawner Demo Gold

/bw addteam Demo Yellow Yellow 4
/bw setspawn Demo Yellow
/bw setspawner Demo Bronze
/bw setspawner Demo Iron
/bw setspawner Demo Gold

/bw addteam Demo Green Green 4
/bw setspawn Demo Green
/bw setspawner Demo Bronze
/bw setspawner Demo Iron
/bw setspawner Demo Gold

/bw setregion Demo loc1
/bw setregion Demo loc2

/mvtp Lobby
/bw setlobby Demo

/bw save Demo
```
