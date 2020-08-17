- Code, UI, and other stuff by me
- Model, Textures and Animations by Drag
- Sounds by Violet Chaolan


Feedback and bug reports are welcome, feel free to join my [discord server](https://discord.gg/jXGFN4k), I also do beta testing for new features and content there.

Fully compatible with multiplayer with no errors or desync as long as everyone has the mod installed. If you happen to find an issue, please let me know (preferably with the console logs from all players involved)


## Showcase

[![Showcase video](https://img.youtube.com/vi/Au6AzQewzQg/0.jpg)](https://youtu.be/Au6AzQewzQg)

## Overview
### New in this update (1.0.7):
###1.0.7
```
    Bugfix:
- Deleted an in-progress ammo type that is no longer possible to make due to r2api update
```

### Installation
- Unzip the Sniper folder to `[RoR2InstallFolder]/BepInEx/Plugins/Sniper`
- (Create the sniper folder if it isn't there)
- If you run into issues, try using [r2modman](https://thunderstore.io/package/ebkr/r2modman/) by ebkr
- To uninstall, simply delete the Sniper folder from `[RoR2InstallFolder]/BepInEx/Plugins/`

### General info
Sniper is a long ranged, single-target dps that incorperates some elements of an assassin to stay alive.

They excel at taking down bosses and high priority targets but struggle against larger groups of weak enemies.

### Skills
See the in game descriptions, maintaining two copies of all the information tends to just result in a mess of conflicting information.

## FAQ
### I can't fire my primary!
Most likely a conflict with another mod, in particular skills++ is known to cause this issue.

### What does '1.0x' mean?
Any skill with that type of notation in its description means that a multiplier is being layered on top of another skill, usually your primary. So, for example, say an attack from your primary would deal 500% damage. If your ammo type has a 2.0x multiplier, that attack would be multiplied by 2.0, and deal 1000% damage. 

### How do I use this in multiplayer?
As with all custom characters, everyone must have the mod installed. If you still run into issues, verify that everyone has the exact same installed mods, including versions. There is usually some level of leeway here, but when in doubt that should be the first thing you try.

### How do I unlock the skills?
For now, they are not unlockable. The locked skills are still WIP. 

### Can I use this on console?
Unfortunately no, there currently is no modding for console RoR2. This would require complete official mod support from Hopoo for both PC and consoles, which is no small task.

### How do I zoom in on controller?
Unfortunately, you can't do it just yet. I'm working on a fix for this. You can still use secondary, you just can't scroll to increase zoom and enter scoped.

## Known Issues
### Incompatibilities
If you find any, please let me know.
- Skills++ (Symptoms: Unable to fire primary)
    Unfortunately nothing I can do to fix this. There are a lot of problems that show up and solutions would generally require me to remove features from sniper which is a red line for me
- Achievement Loader (Symptoms: weirdness with loadout selection)
    Anything that depends on achievement loader should be switched over to use the upcoming unlockablesAPI in r2api.
- Fixed splitscreen (Symptoms: loadout screen is totally blank)
    IDeathHD has a fix for this issue in the works (or maybe even released already)

### Bugs/issues
Again, if you find any let me know.
- No death animation.
- Does not work with vengance artifact (May be better this way. Aimbot hitscan long range AI does not sound like fun)
- Untested interactions with Visions of Heresy (but why)
- Ricochet tracer appears to fire from odd places in multiplayer (Only visual)

## Changelog
###1.0.7
```
    Bugfix:
- Deleted an in-progress ammo type that is no longer possible to make due to r2api update
```

###1.0.6
```
    Adjustments:
-Backflip distance increased
-Backflip is now more stable while firing
-Updated default crosshair
-Added configuration options for crosshair, there are quite a few to work with
-Added configuration option for scope zoom sensitivity
-3 new item displays

    Bugfixes:
-Fixed bug that prevented eclipse progress from saving
-Networking is now stable
```
###1.0.5
```
    Adjustments:
-Backflip cooldown: 8s -> 5s
-Backflip backflip duration now decreases with movespeed.
-Backflip distance and height reduced.
    This makes backflip much more usable to do quick reloads and then fire.

    Bugfix:
-Now works properly on eclipse
-Decoy now has the same item display setup as Sniper
-Decoy cooldown no longer resets when decoy dies
```
###1.0.4
```
-Now compatible with 1.0 update.
    Adjustments:
-Decoy reactivation delay: 2s -> 0.75s
-Decoy cloak duration: 2.5s -> 3s
-Decoy cloak now gives 40% movespeed
-Decoy cooldown is now not visible until reactivation (it already didn't start until then)

-Backflip now stuns and knocks back enemies
-Backflip now automatically grants a perfect reload on use

-Explosive ammo bullet radius: 0.1 -> 0.5
-Explosive ammo damage: 0.45x -> 0.4x
-Explosive ammo description now more clearly indicates that it will deal damage two times to the main target.
    Explosive ammo is generally a more forgiving option compared to FMJ. Overall it was a bit overtuned.

-Ricochet shots more reliably hit enemies

-Reloading before too early now incurrs a small delay before able to fire (equal to waiting for bar to reach the start of good region)
    This elimates potential abuse cases at higher attack speeds where mashing primary would yield more dps than perfect reloads.
-Bad reload multiplier: 0.8x -> 1.0x
-Good reload multiplier: 1.4x -> 1.2x
-Perfect reload multiplier: 2.0x -> 1.5x
-Snipe base damage: 450% -> 600%
    The resulting %s on reloads:
    Bad reload: 360% -> 600%
    Good reload: 630% -> 720%
    Perfect reload: 900% -> 900%
        Due to fixing that abuse case, the penalties for missing a perfect reload can be made much less severe (more in line with ror1 values)
        This also should help with making attack speed feel less risky to take.

-Added 14 item displays
-Adjusted crosshair UI
-Added icon for decoy reactivation
-Added quickscope icon
-Updated steady aim icon
```

###1.0.3
```
    Bugfixes:
- Fixed reload UI not working on artifact hidden stage.
```

###1.0.2
```
    Adjustments:
- The impact of attack speed on the reload bar is now smoother
    Essentially, when your attack speed changes, the bar move speed gradually shifts over half a second to that new speed.
    This should make items like berserkers, predatory, war horn, and tonic less jarring upon activation.
    While this does mean that you don't get the full benefits of conditional attack speed items immediately, you do get to keep them a bit longer because of the falloff time.

    Bugfixes:
- Fixed various UI issues for clients in multiplayer
```

###1.0.1:
```    
    Adjustments:
-Quickscope cooldown: 4s -> 5s
    Quickscope was allowing too many successive shots without items.

-Steady aim max damage: 6.5x -> 6x
-Steady aim min damage: 1.5x -> 1.25x
-Steady aim delay: 0.35s -> 0.5s
    Steady aim was a bit too strong with backup mags

-Decoy cooldown: 18s -> 12s
-Decoy stealth duration: 2s -> 2.5s
    Decoy was not up enough to do its job of keeping you safe

-Precise aim now also gives +1% crit chance per character level
    Precise aim relied on items too much.

-Remade scope UI and added a new shader for it
-Greatly reduced size of reload bar
-Moved reload bar to upwards
-Reload bar now has some transparency
-Charge indicator outline thickness reduced
-Improved perfect reload sound
-Improved some ability descriptions
-Slimmed down crosshair

    Bugfixes:
-Steady aim properly restarts delay between shots 
-Fixed issues with ricochet sounds on fmj
-Fixed ricochet being limited to 2 bounces
-Fixed reload bar hiding on death
-Fixed reload bar being visible on other characters
-Corrected version number
-Fixed reload bar not being visible after revive
-Fixed issue with quickscope not starting aim animations
```

###1.0.0:
```
-First release
```