## Twitch
- Adds a filthy, ugly, smelly, disgusting rat

[![](https://cdn.discordapp.com/attachments/469291841859092488/721322400318226432/ass.png)]()

ping/dm me in the modding discord for any feedback/bugs- @rob#2365

## Important, Read Me
Mod doesn't work, what do?
Use r2modman
Update R2API
Make sure everybody has the same mods installed
Please please please please don't use SteamBuildID, SetBuildID, UnmoddedClients or anything of the sort, it won't work
If it still doesn't work then @ me in the discord with output logs

## Overview
Twitch is a high damage survivor who excels in shredding beefy targets with his powerful debuff, venom.

Venom is applied on every shot from his primary, Crossbow, and each stack reduces attack speed and armor by a small amount. There is no cap, though stacks fall off separately, making it effectively soft capped by your attack speed. Enough stacks of venom will leave an enemy crippled and pretty much unable to attack.

Having some of the lowest defensive stats in the game, Twitch is reliant on his utility skill, Ambush, to avoid damage. The cooldown is rather long but the long invisibility combined with the extremely powerful offensive buff makes it a perfect tool for getting into position to clear the screen with high damage piercing shots.

Twitch's special, Expunge, is an extremely powerful skill when used right but can end up being detrimental if used poorly. The damage scales up with venom stacks, and can reach absurd damage numbers. The downside, however, is that it can only be used once per target as it grants them an immunity to venom, keeping the current stat reductions. Using it too early can cripple your damage output and deny you a large chunk of burst damage. But using it at the right time can permanently debilitate an enemy or stop dangerous attacks like the Clay Dunestrider's big succy succ.

While harsh and unforgiving, Twitch is greatly rewarded for good positioning and patient play.

He also comes with several different loadout choices that offer different playstyles.

[![](https://cdn.discordapp.com/attachments/469291841859092488/721319328095404042/Screenshot_289.png)]()

[![](https://cdn.discordapp.com/attachments/469291841859092488/721322901378170930/unknown.png)]()

## Known Issues
- Crossbow's cooldown refund doesn't work for clients
- Menu animation is not networked
- Bazooka's rocket doesn't rotate properly
- Using Expunge with a grenade in hand will cause a slight visual bug

## Changelog
`1.2.3`
- Fixed drone bug

`1.2.2`
- Fixed Ukulele scaling
- Added SkinAPI compatibility

`1.2.1`
- Updated for 1.0

`1.2.0`
- Added skins!
- Includes a simple skin that's more fitting for RoR2's art style and a tar skin by Ruxbieno
- More skins to come eventually

`1.1.0`
- New utility skill: Scurry
- Acts as a mini Ambush with a shorter cooldown and a short dash
- Startup time on all primary attacks decreased, fire rate unchanged
- Crossbow damage increased to 225%
- Shotgun damage increased to 4x90%
- Shotgun proc coefficient reduced from 0.5 to 0.4
- Shotgun range slightly increased
- Shotgun spread slightly decreased
- Tommy Gun damage increased to 3x85%
- Tommy Gun proc coefficient increased from 0.7 to 0.75
- Tommy Gun spread decreased
- Venom Cask radius decreased
- Venom Cask dot proc coefficient increased, making the venom last longer
- Venom armor reduction per stack increased to 1.5
- Expunge knife hitbox size increased
- Expunge bonus damage per stack reduced to 70%
- Expunged armor reduction per stack increased to 5
- Venom/Expunged attack speed reduction made more effective at lower stack counts
- Added more sounds
- New skill icons for Tommy Gun and Street Sweeper
- Item displays attached to the weapon are now visible with all weapons
- Slight model tweaks to make some more room for item displays

`1.0.5`
- Completely redone item displays, all items should be visible and look much better now

`1.0.4`
- Lowered the spread on empowered Street Sweeper attacks, range is the same
- Fixed Ambush not working properly with Hardlight Afterburner
- Fixed Cheese animation
- Added flinch animation
- Made Ambush buff visuals a bit more noticeable

`1.0.3`
- Included missing R2API dependencies that were causing names, sounds and debuffs not to work, sorry!
- Fixed an issue with arrows sometimes hitting the wall behind you
- Fixed an issue with shotgun bullets randomly hitting you, inconsistently lowering its damage output
- Some VFX improvements
- Tweaked shotgun texture
- Lowered Street Sweeper damage to 4x85%- light nerf because while it's a bit too strong it's still a healthy playstyle that has a lot of risk attached
- Removed increased Street Sweeper bonus range with Ambush buff which was never actually intended
- Lowered attack speed growth from 0.025% to 0.02%
- Venom armor reduction reduced to 1 per stack
- Expunged armor reduction increased to 4 per stack- lower overall damage output but much greater reward for a well timed expunge

`1.0.2`
- Fixed an issue with missing particle textures, thanks to Carrion for finding the cause

`1.0.1`
- Fixed page oopsies

`1.0.0`
- Initial release

##To Do
- Fix Bazooka
- Make weapons visible in character select
- HarbCrate item display support
- Support for Skills++
- Support for ClassicItems Ancient Scepter
- Network the menu animation