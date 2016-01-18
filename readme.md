#Laser Tag for Left 4 Dead & Left 4 Dead 2
Released on the AlliedModders forum - https://forums.alliedmods.net/showthread.php?p=1203196

Shotguns (every single pellet), Rifles, SMGs, Sniper Rifles, Pistols supported and can be disabled by convar.
Melee weapons and grenades are disabled.

##Configurable Variables (CONVARs)
* Laser Colour (Red, Green, Blue):
  * l4d_lasertag_red
  * l4d_lasertag_green
  * l4d_lasertag_blue
* Bots' Laser Colour (Red, Green, Blue):
  * l4d_lasertag_bots_red
  * l4d_lasertag_bots_green
  * l4d_lasertag_bots_blue
* Laser options (Width, Life, Transparency, Offset):
  * l4d_lasertag_width
  * l4d_lasertag_life
  * l4d_lasertag_alpha
  * l4d_lasertag_bots_alpha
  * l4d_lasertag_offset
* Enability (Enabled, Versus/Scavenge, Realism):
  * l4d_lasertag_enable
  * l4d_lasertag_vs
  * l4d_lasertag_realism
* Gun Types (Shotguns, Rifles, SMGs, Sniper Rifles, Pistols):
  * l4d_lasertag_shotguns
  * l4d_lasertag_rifles
  * l4d_lasertag_smgs
  * l4d_lasertag_snipers
  * l4d_lasertag_pistols
* Bots can Laser Tag?
  * l4d_lasertag_bots

##Changelog
```
v0.1
 - Initial Release
v0.2
 - Optimized code
 - Added different bots RGBA (see Convars) (default colour is Turquoise 0/255/75)
 - Removed width2
 - Fixed laser width cvar changing on-the-fly not working
 - Changed default width to 1.0
 - Changed default alpha to 100
 - Changed default life to 0.80
 - Changed default colour of Survivors laser to light blue (0/125/255)
 - Changed name to [L4D(2)] Laser Tag
```