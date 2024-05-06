# TF2-Automatic-Shooting-Script
Titanfall 2 mod that can be used for a variety of things relating to the fire rate and fire modes of weapons.

This mod can lower the rate of fire for any automatic weapon, and it can also make any semi-automatic weapon fully automatic. 

Along with these two things, the mod can reduce recoil on some weapons via automatic tap firing. 

## Convars

`ass_enabled` - Whether the ASS mod is enabled or not. Set to `1` to enable the mod, set to `0` to disable the mod.

`ass_use_all` - Whether the ASS mod should engage on all weapons or not. Set to `1` to enable this feature, set to `0` to disable it.

`ass_weapons` - What weapons to use with the ASS mod. This can be formated like so : `ass_weapons "weapon_name,weapon_name,weapon_name` Here's an example of how to use it : `ass_weapons "mp_weapon_r97,mp_weapon_hemlok_smg,mp_weapon_semipistol,mp_weapon_alternator_smg` a `,` character should separate each weapon name. If you have `ass_use_all` set to `0` then these are the weapons the ASS mod will engage for. Every other weapon will function as normal.

`ass_power` - This is the amount of the weapons normal firerate that the ASS mod will output. If set to `0.5`, then the mod will fire any weapons it's enabled for at half their normal speed. If set to `1.0` then the ASS mod will fire any weapons it's enabled for at their normal max firerate. For example : If you are using the ASS mod with a semi-automatic weapon, and this convar is set to `1.0`, then the mod will fire the semi-automatic weapon the fastest it can be fired, but if this ConVar is set to `0.25` then it will fire the semi-automatic weapon at 1/4th the max firerate. (I'm only explaining this for people who can't understand how this works from the first 2 sentences)
