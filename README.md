Protector urban planning mod [protect]

Protector redo for minetest is a mod that protects a players builds by placing
a block that stops other players from digging or placing blocks in that area.

based on glomie's mod, remade by Zeg9 and reworked by TenPlus1. Urban planning features added by rnd.


Released under WTFPL

Urban planning features(short version):

Placing protectors is expensive around spawn (more centers can be added). Placing several protectors at one place makes that place expensive.
You can place protector in expensive place but after 5 minutes it can be dug up by anyone.


detailed features:
- set up several centers around which placing protectors is costly ( requires upgrade )
- upon placing/digging protectors a network of protectors is built and counts of all nearby protectors is updated
- if certain protector count is exceeded in the network placing new protectors requires upgrade. If protector is placed far away from
	existing network new network is formed with its own count
- protector requiring upgrade has no owner and can be dug up by everyone 5 minutes after place, before that only by placer
- upon upgrade ( paying it with enough mese crystals ) the ownership is assigned to player who completed upgrade

INSTALLATION: extract into directory called "protector" inside minetest mod directory