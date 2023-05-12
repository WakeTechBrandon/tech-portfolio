---
id: New Lead Developer
author: Brandon M. Biggs
authorURL: https://waketechbrandon.github.io/tech-portfolio/
title: Overwatch 2 New Lead Developer
---

# Prompt

You are now the lead devloper of Overwatch, what changes do you make?

<!--truncate-->

## Battlepass reworks

Battlepass grants 4 cosmetics every level up.

Every tier has both premium and free rewards.

Earning a new battlepass tier has the same animation as lootbox openings with an additional coin being added for each additional cosmetic in the tier.

### New Battlepass: Legacy Pass

There are now Legacy Passes. 
- Every Overwatch 1 item has been removed from the shop and is in 6 new legacy passes that each cost $10.
- Overwatch 2 passes enter the legacy pass shop after 1 year.
- Only one Legacy Pass can be active while the seasonal pass is active.
- You cannot earn Prestige Pass rewards from legacy passes.

### New Cosmetic Rewards

With the requirement to match the level of cosmetics from Overwatch 1 per Battlepass tier, more cosmetics are required to fulfill that need.

#### Expanded Title Customization

- Actual Text Content
- Materials
  - Common: White, Black, Red, Green, Blue
  - Rare: Gradient and RGB color wheel (Choose your own color)
  - Epic: Metal, Emissive
  - Legendary: Shifting Materials (Moving gradient)
- Special Effects
  - Epic: Wavy, Pixelized, Shift L->R
  - Legendary: Fire, Sparks, Beating Hearts

#### Battle Portraits
![Apex Legends Battle Portrait Example Image](../img/ApexLegends_Watson_Banner.PNG)

- 2 possible directions
  - Scoreboard:
    - Allow the portrait to the right of the scoreboard to change depending on selected player in match.
  - Quick Career Profile:
    - Popup when selecting a player's name card.
- Several different backgrounds.
  - Common: Solid colors
  - Rare: Gradients, Metals
  - Epic: King's Row, Hanamura, Locations
  - Legendary: Hero Artwork, Fire, moving backgrounds
- Border
  - Common: Solid colors
  - Rare: Gradients, Metals
  - Epic: Moving/Vines/Bubbles/Break rectangular frame effect
- Content
  - Epic: Hero Poses
  - Legendary: Hero Highlight Intros/Animated Heroes
- Multiple career specific rewards available to display such as:
  - current rank
  - season high
  - career high
  - other in-game challenge rewards.

## News Reel

With the introduction of the news reel in S3, this opens up massive in-game opportunities for gathering/providing data/information voluntarily from/to real players. 

### Weekly Survey

A survey that players may click on within the News Reel.

"How do you feel about the latest patch?"
- I Feel Good
- I Feel Neutral
- I Feel Bad

"After this patch, how do you feel about the heroes in the game? (You do not need to select every hero, click "next" when satisfied.)"
- *Heroes Icon Display Screen*
  - Clicking on an icon brings up the following checkboxes:
    - Is more fun to play?
    - Is more fun to play with?
    - Is fair to play against?
  - Any additional comments about this hero:
    - Free form empty text box to type a max of 500 words.

Clicking next will display a results screen that shows a graph of every player's answers plotted as a graph. 
- x-coord=time
- y-coord=survey answers
- viewing option for whole player base or color coded seperate lines per rank.

After submitting their answers for the day, players cannot change them until logging in the next day.

### Developer communication

A link will be available in the news reel that connects to the latest dev blog.

Daily tweets may show up in the news reel as well.

#### Compensation for severe mistakes

Players will recieve in-game currency (not skins) when a DDOS or otherwise substantial issue arises that affactes Overwatch and is out of the players' hands such as server issues, game-breaking bugs (A hero needs to be disabled), etc.

# Balance Update

## General

## All heros

50 more HP for all 250 and under heroes.
10% increase to ultimate costs for all heroes.

### Supports

Supports have off-screen-ally icons that appear on the edges of the screen (can be switched on/off/only critical allies in settings)

Supports also can see all allies' health bars above their own (can be switched on/off in settings.)

#### Kiriko

##### Suzu
- No longer applies a incorporeal effect.
- Cooldown is reduced to 7s (was 15s).

##### Swift Step
- Cooldown now scales 3s - 7s with teleport distance

#### Mercy

##### Guardian Angel (GA)
- Maximum downtime between consecutive GAs is 2.5s (was 3s)

##### Caduceus Staff
Staff now has a "beam strength" in which the attached beam looks physically smaller and less active the longer it is attached to an ally.
- 45hps boosted to 70hps for 1 second after attaching to a new ally.
- 15% damage amplification boosted to 30%
- Beam strength does not weaken during Valkyrie.

##### Resurrection
- Reduced cast time to instant.
- Reduced cooldown to 10s (was 30s).
- Restores the target by 200 HP (was Maximum Health)
- Now costs 20% ultimate charge to cast.
- Does not cost ultimate charge during Valkyrie
- Restored to Maximum Health during Valkryie.

##### Caduceus Blaster
- Can no longer damage enemies.
- Heals 10 on impact and 10 on Area-Of-Effect for allies.

##### New Alternate Fire Mode.
More precise hitbox, and blue bullets
- 20 impact damage toward enemies 
- Applies a 5% damage amplification effect against the target
- Duration 1 second
- Stacks up to 5 times
- Duration refreshes with each application.

#### Moira

##### Alternate Fire
- Alt fire reduced to 20dps (from 50) and 20hps (from 24)

##### Biotic Orb
- Orbs are now damageable. Dealing damage to the orb now reduces the pool of healing/damage the orb has.

##### Biotic Orb: Healing
- Allies attached to the orb recieve 50% more healing
- Healing reduced to 30hps (45 with boost) from 50

##### Biotic Orb: Damage
- Damage reduced to 41dps (45 with boost) from 65dps
- Enemies attached to the orb have "sickness" applied to them

##### Sickness
- Green tint to view.
- Far objects become blured.
- 10% damage amplification against victims.

#### Baptiste

##### Biotic Launcher
- Damage reduced to 5dmg-25dmg from 7.2dmg-25dmg
- Fall-off range decreased to 15m-45m from 25m-45m

##### Regenerative Burst
- Healing-Over-Time removed.
- Cooldown has been reduced to 10s from 15s.

##### Amplification Matrix
- Is now ability 2
- Amplification effect reduced to 25% from 100%
- Cooldown is 8s
- Duration is 6s

##### Immortality Field
- Is now Ultimate Ability
- Now all allies around Baptiste are prevented from losing HP
- Hacking Baptiste will deploy the Immortality Field at Baptiste's location
- Using the ultimate again will deploy the Immortality field as normal for remaining duration.
- Duration is increased to 15s
- Immortality Field (deployed) Health increased to 350 from 150.
- Area-Of-Effect increased to 10m
- Area-Of-Effect (deployed) increased to 7m from 6.5m
- Dying as Baptiste will deploy immortality field at his death location for the remaining duration.

#### Brigitte

##### Health Pool
- Health is 200 (this overrides general 50 additional health for all heroes)
- Armor is 100 

##### Inspire
- Passive Removed

##### Shield Bash
- Cooldown reduced to 4s from 5s

##### Repair Pack
- Overhealth is now generated by Heal-Over-Time when Full Health.
- Overhealth is removed after 2s after Repair Pack's Heal-Over-Time effect has ended.
- Overhealth Maximum is half the target's Maximum Health.
- Cooldown reduced to 3s from 6s.

#### Damage 

##### New Role Passive: Damage Cascade
- Damaging a hero increases damage against that hero for 2s. Stacks with itself.

#### Tank

##### Role Passive: 
- 30% Knockback Resistance.
- -30% Ultimate Charge Generated on Damaged/Healed.
- 50% Damage Amplification Resistance.
- 50% Stun Duration Reduction.

#### Doomfist

##### Power Block
- Split into two parts
  - Power Parry during first second of activation
  - Power Block after Power Parry ends
- No Longer awards Empowered Punch
- 50% Damage reduction
- 30% self-slow
- Infinte Duration

##### Power Parry
- Fortified Effect
- Has 100 Damage Blocked Threshold
  - Awards Empowered Punch
  - Ends the ability with no cooldown
  - Halves Power Parry's current Duration for 3 seconds
- Duration 1 second
- Cooldown 4 seconds




