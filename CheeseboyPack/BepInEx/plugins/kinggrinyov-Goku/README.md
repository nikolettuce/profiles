# Overview
Son Goku has finally arrived in the world of Risk Of Rain 2.

Unlike other ROR2 characters, Goku does not have cooldowns nor skill stocks,
But has his own Ki based resource System instead!

His primary skill will generate him Ki, whilst other skills consume Ki.
He will passivily gain max ki and ki regen over time, increasing per level.

Items that modify cooldown reduction will reduce ki cost of skills instead.
Items that modify skill stocks will increase Max Ki instead.

Now it wouldnt be Goku if he didnt have his transformations.
Tapping the Transform Key ('F' by Default), he can transform into many different forms.
Additionally, when holding the Transform Key instead, Goku will undergo his unique Kaioken transformations.
And Yes, They stack. Super Kaioken bby.

His Main Transformations consume Ki over time, but yeild a great Damage & Armor Boost.
Running out of ki will lose the transformation.

Main Transformations also have a unique ultimate skill, which can be activated by pressing the Ultimate Skill Key ('V' by Default).

His Kaioken Transformations grant bonus damage, attack speed, move speed and ki regen. 
Kaioken does not consume Ki, but instead places a great strain on the body, which if active for too long,
will stun him and forcefully revert him back to his Base Form.

Transformations become available based on Goku's power level, which increases based on his level/experience.
You can see if a Main Transformation is available with the arrows on the bottom right of the In-Game GUI.
Currently, all kaioken transformation are available from the start. (so use them at your own risk :P )

Tapping the Power Down Key ('X' by Default) will revert goku back to his Base form.
- If a kaioken transformation is active, it will be reverted first.

Goku is also capable of flight, where holding the jump key will cause him to enter a flight state; Draining ki Per second.
- You fly by pressing your normal movement keys and facing in the direction you want to go!
- Releasing the jump key or running out of ki will stop the flight.

Goku also capable of Zenkai Boosting, where if a death is survived, he will permenantly gain bonus stats.
- This is displayed with the Zenkai Counter GUI next to the Health/Ki Bar.

# Configurable Settings
- Settings have been moved to KingModUtilities

# Instructions for install:
place the dll in your plugins folder

# Videos
[![Networking Update Trailer](https://i.imgur.com/AjhwxUm.png)](https://www.youtube.com/watch?v=gQehbg0gCYM)
[![Transformations Update Trailer](https://i.imgur.com/ZstQqpq.png)](https://www.youtube.com/watch?v=p5dVhXI8mOs)
[![Trailer](https://i.imgur.com/ehH0XWn.png)](https://www.youtube.com/watch?v=1vDLwYeJjpY)

# Screenshots
![](https://i.imgur.com/DXWx9mo.png)
![](https://i.imgur.com/xPddrMi.png)
![](https://i.imgur.com/JrmEYxo.png)
![](https://i.imgur.com/FPTQuP3.png)

# Feedback
As always, Feedback is greatly appreciated!
You can DM me on Discord, @ me on the modding discord, or even Email me!

# Donations
After numerous requests to do this, I'd like to mention a few things:
- Donations are not required, these mods are free and always will be.
- I make mods as a passion and that alone!
- But if you still wish to donate; you can do so by clicking the donation link below.
- https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=QE4H55NZ2Z69A&currency_code=AUD&source=url

# Discord
- My own personal discord for my mods, feel free to join!
- https://discord.gg/XUFRcS9

# Changelog

2.7.0
- Fixed/Updated for 1.0
- Config Options moved to KingModUtilities
- Balancing Spirit Bomb (Ki Cost Increased, Exploding is now free, increased base damage, reduced charge damage)
- Spirit Bomb Skill FX are slighty more transparent.
- Flight Ki cost is now cheaper and flight speed is now faster.
- Skin Changes should now only occur on your charcter in the lobby (KingModUtilities)
- Renamed Config Option; EnableGokuVoice => EnableCharacterVoice (KingModUtilities)
- UI Reworked to fit new 1.0 UI (KingModUtilities)

2.6.5
- Minor animation overhaul (Idle, Run, Kamehameha)
- New Primary Skill : Melee Strike; A combo based melee attack that targets enemies.
- Movespeed stat increased
- Meteor Crash's Attack speed ki cost scaling removed.
- Ultra Instinct Now activates automatically when unlocked for clients on multiplayer.
- Kaioken now boosts Ki Regen.
- Tweaked kaioken stats
- Kaioken Transformation Cutscene now gives temporary bonus armor.
- Instant Transmission can be aimed at enemies
- Kaioken strain no longer increases during kaioken transformation cutscenes.

2.6.2
- Fixed Bug with Kaioken Transformation Animation playing with no transformation :P

2.6.1
- Fixed Online bug with Pop Up Text appearing for players who were not playing as Goku.
- Kaioken Transformations now trigger mini-Cutscene (Faster version of regular transformation mini-cutscene)
- Buffed Kaioken

2.6.0
- Removed MiniRPCLib And its Dependancy.
- Implemented Full Networking Overhaul (UNET Weaver)
- 99% of Audio & Skill FX are networked.
- Skins now Networked!
- Ultra Instinct now available in Multiplayer.
- Spirit Bomb no longer gets insta-destroyed when attempting to fire another one.
- Spirit Bomb Lifetime extended to 60 secs.
- Fixed Bug with Spirit Bomb Explosion FX not appearing.
- Fixed Bug with Permanent Invisibility when using Instant Transmission with Kaioken.
- Audio Now has Positional & Volume Attenuation.
- Tweaked base/per level Stats.
- Tweaked Meteor Crash. (ki drain now is a % per second, less damage, extra attack speed increases ki drain rate)
- Tweaked Triple Kick. (less damage, faster, improved collisions, procCoefficient => 1.0)
- Ultimate Skill Key now displays In-Game.
- Fixed bug with Transformation Menu dissapearing in character select menu after a Run.
- Added New Config Option : Mastery Time Mult (Controls how fast you gain Masteries)
- You can now only have up to 8 Transformations added (In transformation menu).
- New Transformation : Super Saiyan God 3
- Added New Config Option : Individual Transformation Keys (Allows you to use 1-9 to Transform)

2.5.2
- Tweaked/Balanced all Ultimate skills. (they were too OP, lol)
- Meteor Crash Buff. (moves way faster and scales with movement speed)
- Meteor Crash & Ki Blast Barrage no longer need a key press to trigger. (EG; can now trigger if skill key is held)
- Fixed bug with Upper body animation getting stuck if you're stunned whilst ki blasting.
- Fixed Multiplayer bug with client using ultimate skills, causing the game to softlock...
- Tweaked Bonus Transformations.

2.5.1
- Enabled Ultimate Skills... (im stoopid)

2.5.0
- All Transformations now have a unique ultimate skill. (Pressing the Unique Skill Key)
- New input key for Ultimate Skills. (Default is 'V', can be configurable)
- Added Ultimate Skill : Angry Kamehameha.
- Added Ultimate Skill : Ki Blast Barrage.
- Added Ultimate Skill : Dragon Fist.
- Added Ultimate Skill : God Bind.
- Added Ultimate Skill : God Fist Kamehameha.
- Added Ultimate Skill : Godly Display.
- Added Ultimate Skill : Black Kamehameha.
- Added Ultimate Skill : Kamehameha x10.
- Reworked In-Game power level UI.
- First time Transformations now trigger mini-cutscene. (invincibility applies temporarily)
- Meteor Crash Buff. (More Damage & Armor Bonus)
- Fixed bugs with sprinting.
- Flight system now uses sprinting as a boost mechanic.
- Flight system's vertical movement tweaked.
- Ki Charge Tweaked. (weaker in air, slighty better on ground, becomes less effective when ki is above certain %)
- Spirit Bomb Explosion Visual. (reduced visual explosion size as it was a bit misleading)
- Nerfed Spirit bomb damage.
- Bonus Ki given from items are now displayed on the Ki bar.
- Death Sounds Implemented.
- Ultra instinct dodging will no longer trigger when invincible.
- Alternative Skin Implemented. (Goku Black Costume)
- Custom Skin Selection Menu Implemented.
- Fixed bug with Super Saiyan Rose aura sound not looping.

2.2.0
- Meteor crash now will execute for minimum 1 second with no per second ki cost drain.
- Zenkai Boost Implemented (Permenantly gain bonus stats if you survive death, stacks)
- Reworked Ki Blast skill to be a Double Ki Blast; same ki cost; minor damage decrease.
- Implemented Additional Jump Animation
- Fixed Bug with Flight not exiting after releasing Jump Key

2.1.0
- Tweaked Transformation : Super Saiyan Blue 3
- New Transformation : Super Saiyan Rose
- Fixed Bug with getting softlocked whilst exploding spirit bomb as it's lifetime runs out.
- Fixed Bug with the stationary turrets not shooting (because apparently turrets want to jump!?)
- Flight activates faster
- Flight now deactivates when spacebar is released
- Whilst flying, if ki runs out, flight is temporarily disabled.
- Flight no longer ends when hitting ground.
- Skills can now be used whilst in Flight (it will exit the flight state)
- When using a skill that allows for hovering, holding the Jump Key will let you Hover.

2.0.1
- Fixed Transformation Menu Not Appearing
- Fixed Volume Issues

2.0.0
- Transformation Menu Implemented (Replaces Overview Button In Character Selection Menu)
- Full Character Model Rework & VFX Update!
- Implemented Multi-Layered Animations.
- Kamehameha skill is no longer stationary!
- Kamehameha Skill's Bonus Armor reduced.
- Minimum Charge time for Kamehameha Skill reduced
- If Instant Transmission is equipped, you can use it once during a Kamehameha.
- Implemented a flight system (Holding jump key enters the flight state, at the cost of Ki per second)
- Goku no longer takes fall damage
- Goku now has an additional jump
- Added Ultra Instinct Transformation (Its power is based on your strongest main transformation) (Singleplayer Only)
- Added Bonus Transformation(s)
- Added Meteor Crash Skill (secondary)
- Added Spirit Bomb Skill (special)
- Added Ki Charge Skill (utility)
- Tweaked overall Volume
- Bug Fixes

1.4.0
- god forms now give bonus health regen (is canon!)
- Implemented Transformation Masteries (After using a transformation for a period of time, you will first master it; reducing the ki drain rate by a minor amount, if you continue to use it, you will perfect it and greatly reduce the ki drain rate)

1.3.1
- added audio mixers (Mod's SFX now works with SFX slider)

1.3.0
- added bonus armor when using kamehameha skill
- raised goku's base armor by 2
- Cooldown reduction reduces ki cost of skills. (Ki cost Minimum is 1)
- additional skill stocks now grant bonus max ki (bonus max ki is based of skill slot)
- kamehameha ki drain rate now affected by cooldown reduction

1.2.1
- added Hard Mini-Rpc-Lib Dependency

1.2.0
- there is now a stressed ki bar GUI when kaioken nears full strain
- tweaked transformation strain values (strain multipliers reduced, SSB can handle kaioken better than SSJ3/SSG)
- text pop up now displays when next main transformation is unlocked

1.1.2
- Goku should now be functional after reviving (EG: Dio's Best Friend)
- moved and resized transformation GUI (so its not blocking equipment stocks)
- tweaked kamehameha skill's collision radius
- kamehameha skill's distance now scales with charge

1.1.1
- whilst (Triple Kick / Ki Blast) Skills are active, you can hover by holding Jump (at the small cost of ki per second)
- fixed Ki Blast damage bug
- animations should transition smoother now.
- tweaked kamehameha size
- Changed Ki Blast Animation (Experimenting with custom animations, warning they are not great :P )
- Ki blasts now fire from the middle (should be more accurate now)
- tweaked ki blast damage & collision radius
- moar crash fixes


1.1.0
- removed debug ball of doom
- removed attack speed cap
- kaioken attack speed boost increased
- increased strain limit for kaioken usage (increased per level strain limit)
- Fixed Crashes (caused by OnDestroys / game quits / animation plays)
- Kamehameha procCoefficient : 0.15 => 1.0
- Kamehameha charge per sec damage increased by 200%
- Kamehameha now stuns.
- tweaked Main Transformation ki drain rates
- fixed overflow bug with power level display
- fixed invalid scaling for transformation availability GUI
- Tweaked Damage of Triple Kick & Ki Blast
- instant transmission slightly slower (but whilst in kaioken, it is faster)

1.0.1
- fixed character selection sound (should work with other survivor mods now)
- Improved instant transmission and sped up animation.

1.0.0
- Initial Release!

# Special Thanks
- The Modding Community
- The ROR2 Community
- Friends
- Bubby

