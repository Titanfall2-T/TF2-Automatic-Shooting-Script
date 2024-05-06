# TF2-Automatic-Shooting-Script
Titanfall 2 mod that can be used for a variety of things relating to the fire rate and fire modes of weapons.

This mod can lower the rate of fire for any automatic weapon, and it can also make any semi-automatic weapon fully automatic. 

Along with these two things, the mod can reduce recoil on some weapons via automatic tap firing. 

By default, the mod is set to use the max firerate of any weapons it's enabled for, and is enabled for the following weapons : Alternator, Volt, CAR, P2016, R97, 

I would recommend you read the ConVars listed below to get a better understanding of how to use this mod. You can change these convars through either the mod.json or the in-game console (using Northstar launcher)

## Convars

`ass_enabled` - Whether the ASS mod is enabled or not. Set to `1` to enable the mod, set to `0` to disable the mod.

`ass_use_all` - Whether the ASS mod should engage on all weapons or not. Set to `1` to enable this feature, set to `0` to disable it.

`ass_weapons` - What weapons to use with the ASS mod. This can be formated like so : `ass_weapons "weapon_name,weapon_name,weapon_name` Here's an example of how to use it : `ass_weapons "mp_weapon_r97,mp_weapon_hemlok_smg,mp_weapon_semipistol,mp_weapon_alternator_smg` a `,` character should separate each weapon name. If you have `ass_use_all` set to `0` then these are the weapons the ASS mod will engage for. Every other weapon will function as normal. If you do not enter the name of a weapon correctly, it will not function for that weapon. To find a list of weapon names and their associated weapons, read the list below :


`ass_power` - This is the amount of the weapons normal firerate that the ASS mod will output. If set to `0.5`, then the mod will fire any weapons it's enabled for at half their normal speed. If set to `1.0` then the ASS mod will fire any weapons it's enabled for at their normal max firerate. For example : If you are using the ASS mod with a semi-automatic weapon, and this convar is set to `1.0`, then the mod will fire the semi-automatic weapon the fastest it can be fired, but if this ConVar is set to `0.25` then it will fire the semi-automatic weapon at 1/4th the max firerate. (I'm only explaining this for people who can't understand how this works from the first 2 sentences)

`ass_attack_button` - This ConVar only exists in ASS v1.0.0, if you are using a newer version you will not have it. This convar is essentially just what key you use to fire your weapon. By default it is set to mouse1, however if you want to change it for whatever reason you can. PLEASE NOTE : Changing this to a button that is not your fire button will make the mod not work. idk don't worry about it just get the newest version, it pulls what your fire button is via a command to read what commands you have bound to what buttons lol
