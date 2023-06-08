Telnet to Az:Net//GRID

Type your new username in the provided field.
A private key will be downloaded to your system. Back this up and keep it safe!
After this you may use telnet, SSH, or our provided client to log in. 
Your key logs you in automatically.

When you log in you will only see a terminal at first.
Type 'AP' to open your Browser window.
A new panel will be opened to the right.

You are the @ located in the center of your screen.
Your first two bots are listed as B.
They are currently patrolling your data fort and keeping you safe. Best to leave them as is for now.

All of your file folders exist as rooms.
Type 'ls' and their names will show up, both in the terminal and above their respective doors within your Browser window.
Only some folders can have their name changed.

Type 'cd foldername' to teleport to a folder, or you can walk there manually.
For now, let's go to your ~/Docs/Weapons folder by first typing 'ls' then entering the Docs room, and then ls again to find and enter the Weapons room.
You can also type 'cd ~/Docs/Weapons' to teleport there instantly. 

Here you will find a melee weapon file called NewUser.Melee
Select it by clicking on it. Move it to your Docs folder by walking there after highlighting.
You can also type 'mv NewUser.Melee ..'
(.. Specifies the next highest folder, mv is to move a file. If you are not currently in the Weapons folder, you must instead use 'mv ~/Docs/Weapons/NewUser.Melee ~/Docs')

Once your new weapon is in your Docs folder type 'edit NewUser.Melee'
In this file you can see the hash of the item as well as it's stats and lore.
Enter your name in the appropriate field and type ctrl+x.
Press y to save the file.
You may then name this weapon anything that you desire, or keep its starter name. Keep the extension as .Melee or it will not be functional.
Be sure to use your proper chosen username when putting your name in via edit. Doing this will 'soulbind' the item to you, allowing you to respawn with it after a reset. If your item isn't soulbound, you will drop it upon your death.
(Note, some hacks can remove your soulbindings!)
If you lose your starter weapon, you can buy a new one from Navi, located in B1 of the Core on grid.

Double click the Weapon to equip it, or type equip weapon_name.Melee
(Weapons and armor must be in the same folder as you are to equip them)
Use your weapon by pressing space.

In the top corners of the room you will see your CPU cores. Currently you only have access to max 4 cores, one in each corner, so try to find a CPU block and upgrade them as soon as able. A block holds 4 CPU cores in a single corner.
Each CPU Core allows you to have one bot or virus running.
All of your bots share the same processors, so be sure to unload bots that are taking up required resources for attack or defense.
1 CPU Core = 1 active bot or virus (run in either CPU or RAM)

In the center of the room above your spawn point is your RAM.
This essentially acts simultaneously as both your hotbar as well as your inventory.
Right now you only have one slot, so you will be very limited in the additional scripts you can run while on grid.
You always have access to basic commands like ls and mv on grid, but you may not be able to move something into RAM from grid if all your slots are occupied. 
Without a doubler, max RAM is 4.
Max doublers is 2.

If you type ls -a it will show you two new folders and rooms that you couldn't see before.
One is titled 'Loot', and the other 'X'.
You may rename the subfolders under ~/.Loot/ to whatever you desire.
These folders can be used to store whatever you want.

Go inside the folder titled ~/.X using your preferred method.
(The door wall is non-solid to anyone with root access in your filesystem)
Here you will see three subfolders;
Bot, AI, and Virus
The Bot folder holds all of your .bot files used for on- and off-grid companionship.
The Virus folder holds any .virus, .rat, and .worm files you acquire or design. Viruses serve multiple purposes and are similar to bots, except they can only be run inside a root folder. 
They're mostly used for infecting your enemies, but you can also infect yourself if you run a virus from your own CPU.

The AI folder is used for a feature you will be introduced to later. Ignore it for now.

Enter your Bot folder.

Here you will see your first two bot scripts:
Tag.bot and Smack.bot
Tag runs ls to find any entity that appears as hostile and marks it as red.
Smack finds any marked entities and attempts to deal damage to them by moving within 1-tile of them.
Currently, both are protecting your data fort.

Type cd ~/ to return to your root folder

Approach one of your CPU and stand atop it. Type 'kill Smack.bot'
You can start and stop bots and viruses in your root folder like this using the 'run' and 'kill' commands.
Leave Tag running in CPU for now.

Now walk over to your RAM, located in the center of your folder above your spawn console.
While standing atop it, type 'load Smack.bot'
You have now loaded this bot to be used with you on the grid. Once you spawn in using your Access Point, any bots loaded in your RAM will spawn along side you and their normal functions will automatically run.
You can manually mark enemies for Smack to attack by shift-clicking on them while on grid.
Software and script are entered and removed from RAM via the 'load' and 'unload filename' commands

While we're here, walk down to your spawn console and type 'pin'.
Choose a 3-digit pin to lock your console. To access root filesystems, you must enter this pin upon login.
This is a security measure that enemies must bypass to gain access to your hidden folders and files.

In the top-center of your root folder you will find the Access Point. You can use 'AP' to access it from anywhere in your filesystem, just like when you first spawned in (running 'AP' twice in a row after logging in will immediately load you onto the grid using last setting, useful after a reset.
Stand atop the O and type 'load' or type 'AP load' from anywhere in your filesystem.

You will be shown a list of your available VPNs  in your terminal and be given a chance to set up proxy chains here. 
All new Users begin with access to our Core Network VPN.
A VPN will both hide your IP as well as dictate your spawnpoint on the grid.
If you spawn in without a VPN, your IP will be located somewhere at the inner side of The Edge, close to the pvp zones.
Using the Core Network VPN will put you in the center of the main city hub, with access to everything you will need as a new player.
To select your exit node, type '1' for 'Core VPN'.
Since you have no others, the VPN will then close out in the terminal, and load you into the grid.

To continue the newuser journey, find the Core area listed as B1 and read the info boards there.

To find this document again, 
check ~/Docs/newuser.txt

To change your settings, 
check ~/Docs/config.txt

To see a list of commands type 'help' in your terminal.
To see what a command does type 'help commandname'

(newuser.txt can be moved, deleted, renamed or edited as desired.
config.txt must follow the proper formatting and stay within the ~/Docs folder. If config.txt is deleted or moved, a new copy will be made on the next server sync and your settings will be set to default. If the config is improperly formatted, settings are reset to default and an error is given)

Enjoy your first run on 
the Az:Net//GRID!!!
