# Advanced-Gang-Zones
Draw numbers and borders on the map. This is an updated version of my old project beaZone.inc<br>
SA:MP Forum Topic Link: http://forum.sa-mp.com/showthread.php?t=618475 (Does not work.)
Portal SA:MP (pt-BR) Link: https://portalsamp.com/showthread.php?tid=3469
Open.MP Link: https://forum.open.mp/showthread.php?tid=2374


# Limitations
SA:MP Limit for gang zones is 1024. Numbers can take up to 10 gang zones to create and 4 for borders.<br>

# Update - 25/03/2023 (pushline)
Now that i updated the include, take notes that the gangzones, can go up to higher numbers than 99 and equal less than 999.
<br>
The number creation is one of the hards/ugly parts that i've had to seen in the include. So if u have a better idea, please, fork this project and do a pull request.

# Functions

> CreateZone(Float:MinX, Float:MinY, Float:MaxX, Float:MaxY)

Creates a gang zone.<br>
**Returns the ID of the created gang zone.**
<br><br>
> DestroyZone(zoneid)

Destroys a gang zone.<br>
**Returns (0 - a gang zone does not exist, 1 - successful)**
<br><br>
> ShowZoneForPlayer(playerid,zoneid,color,ncolor = ZCOLOR_NUMBER,bcolor = ZCOLOR_BORDER)

Show a gangzone for a player. (Including a number and borders)<br>
**Returns (0 - a gang zone does not exist, 1 - successful)**<br>
**ncolor and bcolor arguments are optional**
<br><br>
> ShowZoneForAll(zoneid,color,ncolor = ZCOLOR_NUMBER,bcolor = ZCOLOR_BORDER)

Show a gangzone for all players. (Including a number and borders)<br>
**Returns (0 - a gang zone does not exist, 1 - successful)**<br>
**ncolor and bcolor arguments are optional**
<br><br>
> CreateZoneNumber(zoneid,number,Float:numsize = 0.7)

Attach a number to a gang zone.<br>
A gang zone must be shown again to players in order to display a number.<br>
**Returns (0 - a gang zone does not exist or numsize is invalid, 1 - successful)**
<br><br>
> DestroyZoneNumber(zoneid)

Destroys a number.<br>
**Returns (0 - a gang zone does not exist or a number was not created before, 1 - successful)**
<br><br>
> CreateZoneBorders(zoneid)

Attach borders to a gang zone.<br>
A gang zone must be shown again to players in order to display borders.<br>
**Returns (0 - a gang zone does not exist, 1 - successful)**
<br><br>
> DestroyZoneBorders(zoneid)

Destroys borders.<br>
**Returns (0 - a gang zone does not exist or borders were not created before, 1 - successful)**


> **Added in 2.1** - HideZoneForPlayer(playerid,zoneid)

> **Added in 2.1** - HideZoneForAll(zoneid)

> **Added in 2.1** - ZoneFlashForPlayer(playerid,zoneid,color)

> **Added in 2.1** - ZoneStopFlashForPlayer(playerid,zoneid)

> **Added in 2.1** - ZoneFlashForAll(zoneid,color)

> **Added in 2.1** - ZoneStopFlashForAll(zoneid)

> **Added in 2.1** - ZoneBordersFlashForPlayer(playerid,zoneid,color)

> **Added in 2.1** - ZoneBordersStopFlashForPlayer(playerid,zoneid)

> **Added in 2.1** - ZoneBordersFlashForAll(zoneid,color)

> **Added in 2.1** - ZoneBordersStopFlashForAll(zoneid)

> **Added in 2.1** - ZoneNumberFlashForPlayer(playerid,zoneid,color)

> **Added in 2.1** - ZoneNumberStopFlashForPlayer(playerid,zoneid)

> **Added in 2.1** - ZoneNumberFlashForAll(zoneid,color)

> **Added in 2.1** - ZoneNumberStopFlashForAll(zoneid)





