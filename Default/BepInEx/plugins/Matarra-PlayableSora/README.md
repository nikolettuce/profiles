# PlayableSora - Play as Final Form Sora!
#### By Matarra

## Adds an entirely new custom survivor: Final Form Sora from Kingdom Hearts II Final Mix
### Passive Skill:
 - Superglide - Hold jump while midair to glide at high speed. Scales with movement speed.

### Primary Skill [M1]:
 - Final Arts - Sora attacks with both his keyblades, unleashing an attack dependent on whether you're grounded or not. 
  - Sora can seamlessly transition from grounded to aerial combos and vise versa if you manage to touch ground or become airborne during the combo.
  - Scales with attack speed up to a cap.
  - You have invincibility frames during the finisher attack.
  - You can cancel any non-finisher attack mid-combo with your Utility Skill - Quick Run.
  - You can input-buffer another attack, or a magic command mid-attack to cast it slightly faster.
  - Aerial attacks will move you towards the closest enemy, or whichever enemy you're pointing at via cursor.

### Secondary Skill [M2]:
 - Thundaga - Sora calls down 7 bolts of lightning to strike nearby enemies.
  - These bolts deal AoE damage.
  - These bolts will lock-on to nearby enemies, prioritizing closer enemies.
  - Costs 20 MP, can be casted even if less than 20 MP remain, which will consume any remaining MP.
  - Cannot be cancelled with Quick Run.

### Utility Skill [Shift]:
 - Quick Run - Sora performs a quick dash in given direction. Dashes in the direction he is moving, not facing.

### Special Skill [R]:
 - Magnega - Sora creates a vortex of magnetic force which draws in nearby enemies.
 - Will not draw in Elite or Boss type enemies.
 - Costs 65 MP, can be casted even if less than 65 MP remain, which will consume any remaining MP.

## Model / Anims
- Model, animations, and textures were ripped from Kingdom Hearts II Final Mix and imported / blended in unity. All keyblade movements were re-animated by me.

## Stats
 - Base Jump Power = 20
 - Base Jump Count = 2
 - Base Max Health = 145
 - Health per Level = 45
 - Base regen = 4
 - Regen per Level = 0.7
 - Base armor = 18
 - MP Restoration time = 20s
 - Everything else is the same as base Commando.

## Fully Multiplayer Compatible ✓
 - Currently aware of a bug that allows items on sora to be visible for other clients. (Items are not supposed to be visible on his character body).
 - Sounds are only audible for the client playing sora. This is not a bug, but a choice.

### Video Gameplay

[![Sora Gameplay](https://img.youtube.com/vi/W67jkMyy-LM/maxresdefault.jpg)](https://www.youtube.com/watch?v=W67jkMyy-LM)

### Installation Guide

- Copy `PlayableSora.dll` into your `BepInEx\Plugins` folder. Can create a folder for it if you want.

### Special Thanks

- IDeathHD - General help when needed. A great feller.
- Rein - Help assigning skills, and various other parts. A grumpy feller.
- Violet Chaolan - Taught me how to import custom sounds, as well as testing and providing feedback on sora in his early stages.
- Miss_Name - Provided an example of MiniRPC, only reason Sora works in multiplayer.
- Inzanity - Helped proof read the readme and supplied feedback across soras creation.

### Contact
 - To report a bug or provide feedback, I am available on the RoR2 modding discord @Matarra#3965. I also created a discord server for my mods if youd wish to join and report there. https://discord.gg/d4u8y5S

### Changelog

`1.0.8` - Updated for the release update of ror2

`1.0.7` - Updated once more to the newest version of R2API, 4/11/2020

`1.0.6` - Updated the mod to the newest version of R2API. Update if you receive errors about skins.

`1.0.5` - Potentially fixed a bug which would cause the mana bar to display twice.
 - Swapped from SkillAPI / EntityAPI to LoadoutAPI as they are being deprecated and will no longer function soon.

`1.0.4` - Added soras christmas skin! It will not display properly in pregame lobby, but it will display properly in game
 - Buffed Magnega to stun during the entire duration!
 - Buffed attack speed effectiveness on sora.
 - Buffed aerial chase speed when attacking in midair.
 - Buffed various attack radiuses
 - Dashing now grants brief invincibility frames
 - Heavily buffed his combo finisher to reward using it.
 - Dash speed / distance now scales with movement speed.

`1.0.3` - Fixed a bug that caused multiplayer games to crash between teleporter events.
 - Buffed a few aspects of soras kit:
 - Magnet AoE Succ radius increased from 15 meters to 25
 - Mana regen buffed from 20s to 15s recharge
 - Superglide speed buffed to always be 20% faster than sprinting normally
 - Primary attacks each buffed slightly
 - Invincibility frames from combo finisher now linger slightly

`1.0.2` - Rein taught me how to count. This literally just fixes the version number.

`1.0.1` - Fixed a prefabAPI error, that caused the mod not to boot with the newest version of r2 api.

`1.0.01` - Updated readme file for easier reading pleasure.

`1.0.0` - Initial release of the mod.