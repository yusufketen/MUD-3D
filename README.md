# AnatoliaMUD 3D Renderer

## Introduction
The project aims to make a 3D game client for a MUD (multi-user dungeon) game. Since MUD includes huge content our aim was to create a MUD client that can be playable in very basic aspects and create the connection between the MUD server and our client.

## How to play
Just download the client and start playing.

### System requirements:
- Windows 10 or higher (64-bit)
- GTX 1050 or higher GPU
- 8 GB of RAM


[Click here to download the client](https://drive.google.com)


## Team

Yusuf Keten

Osman Fatih Çakır



## Implementation Details

### Server
Anatolia MUD server uses C as the programming language and uses Telnet for networking. Telnet connection is not a secure connection type, so there is encryption for data between the server and the client.Since Anatolia MUD is a text-based game, the server creates the data with concatenating strings to produce a readable text. In addition to texts, the data between the server and the client consists of the color data to colorize the text.

Therefore, we decided to not to change the network and implement our features with sending data between texts. For each data that the server creates, we added a client data part and parse it on the client.

### Client
The client is developed with the Unity game engine since Unity has a lot of game development tools such as UI, scripting, 3D renderer, etc. We implemented a Telnet connection with C# since Unity scripting language is C#. Unity also has a big advantage which is community. Since Unity has a lot of users Unity Store also has a lot of assets that we can use.



## About MUD

### What is the MUD?
A MUD (multi-user dungeons) is a multiplayer real-time virtual world, usually text-based or storyboarded. MUDs combine elements of role-playing games, hack and slash, player versus player, interactive fiction, and online chat.MUD clients are computer applications that make the MUD telnet interface more accessible to users, with features such as syntax highlighting, keyboard macros, and connection assistance.

### MUD History
The first popular computer adventure game was called Adventure, created by Will Crowther and Don Woods in the mid 1970's. The first MUD, an adventure game with multiple players, was invented by Roy Trubshaw and Richard Bartle at Essex University in England in 1978.

MUDs are not popular anymore since people prefer more visual games. Nonetheless there are a few active MUD servers that have active players. 

Some active MUD games can be reached from this website: https://www.topmudsites.com

### MUD Gameplay
The typical MUD will describe to the player the room or area they are standing in, listing the objects, players, and non-player characters (NPCs) in the area, as well as all of the exits. To carry out a task the player would enter a text command such as take apple or attack dragon. Movement around the game environment is generally accomplished by entering the direction (or an abbreviation of it) in which the player wishes to move, for example typing north or just n would cause the player to exit the current area via the path to the north.

### AnatoliaMUD
Anatolia MUD is a role-playing, player-killing, and adventure-filled multi-user dungeon game, however, it is text-based. Anatolia Mud is based on Rom 2.4 and Rom is based on Merc Diku Mud. Merc Mud is a Diku Mud with many enhancements and contributions.

**Webpage:** http://anatoliamud.com