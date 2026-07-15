---
tags:
  - RAW
  - Spell
  - Conjuration
  - Druid
  - Ranger
  - 2nd
casting_time: "Action"
ritual: false
range: "90 feet"
components: "V, S, M (a feather, tuft of fur, and fish tail inside a gilded acorn worth 200+ GP)"
component_consumed: false
duration: "Concentration, up to 1 hour"
---
_Level 2 Conjuration (Druid, Ranger)_

**Casting Time:** Action  
**Range:** 90 feet  
**Components:** V, S, M (a feather, tuft of fur, and fish tail inside a gilded acorn worth 200+ GP)  
**Duration:** [[Concentration]], up to 1 hour

You call forth a bestial spirit. It manifests in an unoccupied space that you can see within range and uses the **Bestial Spirit** stat block. When you cast the spell, choose an environment: Air, Land, or Water. The creature resembles an animal of your choice that is native to the chosen environment, which determines certain details in its stat block. The creature disappears when it drops to 0 [[Hit Points]] or when the spell ends.

The creature is an ally to you and your allies. In combat, the creature shares your Initiative count, but it takes its turn immediately after yours. It obeys your verbal commands (no action required by you). If you don’t issue any, it takes the Dodge action and uses its movement to avoid danger.

**Using a Higher-Level Spell Slot.** Use the spell slot’s level for the spell’s level in the stat block.


```statblock
forceColumns: true
columns: 2
name: Bestial Spirit
source: Summon Beast
size: Small Beast
alignment: neutral
ac: "11 + the spell's level"
hp: "20 (Air only) or 30 (Land and Water only) + 5 for each spell level above 2"
speed: 30 ft.; climb 30 ft. (Land only); fly 60 ft. (Air only); swim 30 ft. (Water only)
stats:
  - 18
  - 11
  - 16
  - 4
  - 14
  - 5
saves:
  - strength: 4
  - dexterity: 0
  - constitution: 3
  - intelligence: -3
  - wisdom: 2
  - charisma: -3
senses: darkvision 60 ft., passive Perception 12
languages: understands the languages you know
bestiary: true
traits:
  - name: Flyby (Air Only)
    desc: The spirit doesn't provoke opportunity attacks when it flies out of an enemy's reach.
    attack_bonus: 0
  - name: Pack Tactics (Land and Water Only)
    desc: The spirit has advantage on an attack roll against a creature if at least one of the spirit's allies is within 5 feet of the creature and the ally doesn't have the incapacitated condition.
    attack_bonus: 0
  - name: Water Breathing (Water Only)
    desc: The spirit can breathe only underwater.
    attack_bonus: 0
actions:
  - name: Multiattack
    desc: The spirit makes a number of Rend attacks equal to half the spell's level, rounded down.
    attack_bonus: 0
  - name: Rend
    desc: "Melee Attack Roll: Bonus equals your spell attack modifier, reach 5 ft., one target. Hit: 1d8 + 4 + the spell's level piercing damage."
    attack_bonus: 0
    damage_dice: 1d8
    damage_bonus: 4
```