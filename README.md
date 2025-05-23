# FFXIV-Simpler-Buff-Icons

Ever felt oevrwhelmed during a raid because you got too many buffs and you don't know what they do ? This mod was made for you !
Simpler Buff Icons is a mod that replace common raid buff effect icons (such as Attack up, Shields, etc) by generic icons for easy understanding.

![Attack up](https://github.com/charlignon/FFXIV-Simpler-Buff-Icons/blob/main/src/assets/png/ATT_UP.png)
![Critique up](https://github.com/charlignon/FFXIV-Simpler-Buff-Icons/blob/main/src/assets/png/CRIT_UP.png)
![Healing over time](https://github.com/charlignon/FFXIV-Simpler-Buff-Icons/blob/main/src/assets/png/HoT.png) 
![Shield](https://github.com/charlignon/FFXIV-Simpler-Buff-Icons/blob/main/src/assets/png/SHIELD.png)
![Defense up](https://github.com/charlignon/FFXIV-Simpler-Buff-Icons/blob/main/src/assets/png/DEF_UP.png) 
![Magic defense up](https://github.com/charlignon/FFXIV-Simpler-Buff-Icons/blob/main/src/assets/png/MDEF_UP.png)
![Tank invuln](https://github.com/charlignon/FFXIV-Simpler-Buff-Icons/blob/main/src/assets/png/INVULN.png) 

## Requirements

- [Dalamud](https://github.com/goatcorp/Dalamud) plugin framework for FFXIV (installed via [XIVLauncher](https://github.com/goatcorp/FFXIVQuickLauncher/releases/latest) | [Linux version](https://flathub.org/apps/dev.goats.xivlauncher))
- [Penumbra](https://github.com/xivdev/Penumbra) mod loader for FFXIV+Dalamud

## Installation & usage

1. Download the latest version of this mod from [this repo](https://github.com/Charlignon/FFXIV-Simpler-Buff-Icons/tree/main/build) or from [XIV Mod Archive](https://www.xivmodarchive.com/modid/99380)
2. Start your game with Dalamud enabled. ⚠️ Stay on the title screen !*
4. Open you Penumbra settings, go to the Mods tab, then click on the import button
5. Select `Simpler Buff Icons.pmp` and validate
   - If you downloaded the folder and not the archive, you need to move it to your mod folder, then use Rediscover Mods in Penumbra
6. Set the mod priority. If this is your only mod that replaces icons, 0 is fine
7. Select for which classes the buff effect icons should be replaced. It will affect the effect given by said classes, not the class you are playing
   - I recommend you disable it for classes you play. Learn to play your class properly >:D
   - In some cases, the changes made may not apply immediately in-game. This is expected, you will need to force reload**
8. @ me on Twitter to tell me how much you love (or hate) this mod, and share with your friends :D

*_This is to prevent the icons to be loaded by the game before the mod is installed. Once an icon is loaded, it stay in memory for basically your whole game session. Same if you want to disable the mod: if the replacement icons were loaded once, they'll keep being displayed._

**_To force reload all the game icons, you need to either call the Aesthetician and start the character customisation screen then leave, or restart your game entirely. _

## Suggestions and Roadmap

I have listed all the actions along with the job, sprite, etc. in this [Google Sheet](https://docs.google.com/spreadsheets/d/1lNPv61yyH8SHQGdA3ALxqSabc02VpS5x-1IJwizMdKc/edit?usp=sharing). Feel free to have a look ! You can leave a comment on it, or open an issue here on Github. I recommend Github since I'll check it more often.
I haven't really defined a roadmap yet, but I do have a few ideas for improvements :
- Fix the last few missing icons
- Separate DPS between Melee, Caster and Ranged
- Invulnerabilities
- Separate icon for Magic def buff
- Self buff icons
- Debuff applied to ennemies
- And more ! Send me suggestions :)

## Contributing

<WIP> I plan on making a guide on how to make an icon mod ! It's quite the process, and I have seen very few of them so I thought I'd share my experience :)

## Acknowledgements

<WIP> as well, but goatcorp and their community for their launcher and Dalamud in general, and especially for [ffxiv-explorer-fork](https://github.com/goaaats/ffxiv-explorer-fork). The Penumbra community for their help on understanding icon reloads. And a few others that'll add at some point !
