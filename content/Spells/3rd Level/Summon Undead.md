---
tags:
  - RAW
  - Spell
  - Necromancy
  - Warlock
  - Wizard
  - 3rd
casting_time: "Action"
ritual: false
range: "90 feet"
components: "V, S, M (a gilded skull worth 300+ GP)"
component_consumed: false
duration: "Concentration, up to 1 hour"
---
_Level 3 Necromancy (Warlock, Wizard)_

**Casting Time:** [[Action]]  
**Range:** 90 feet  
**Components:** V, S, M (a gilded skull worth 300+ GP)  
**Duration:** [[Concentration]], up to 1 hour

You call forth an Undead spirit. It manifests in an unoccupied space that you can see within range and uses the **Undead Spirit** stat block. When you cast the spell, choose the creature’s form: Ghostly, Putrid, or Skeletal. The spirit resembles an Undead creature with the chosen form, which determines certain details in its stat block. The creature disappears when it drops to 0 [[Hit Points]] or when the spell ends.

The creature is an ally to you and your allies. In combat, the creature shares your [[Initiative]] count, but it takes its turn immediately after yours. It obeys your verbal commands (no [[action]] required by you). If you don’t issue any, it takes the [[Dodge|Dodge action]] and uses its [[Rules/Combat/Movement/Movement|movement]] to avoid danger.

***Using a Higher-Level Spell Slot.*** Use the spell slot’s level for the spell’s level in the stat block.

### Undead Spirit
```statblock
forceColumns: true
columns: 2
name: Undead Spirit
source: Summon Undead
size: Medium, undead
alignment: neutral
ac: "11 + the spell's level"
hp: "30 (Ghostly and Putrid only) or 20 (Skeletal only) + 10 for each spell level above 3"
hit_dice: ""
speed: 30 ft.; fly 40 ft. (hover; Ghostly only)
stats:
  - 12
  - 16
  - 15
  - 4
  - 10
  - 9
saves:
  - strength: 1
  - dexterity: 3
  - constitution: 2
  - intelligence: -3
  - wisdom: 0
  - charisma: -1
damage_immunities: necrotic, poison
condition_immunities: exhaustion, frightened, paralyzed, poisoned
senses: darkvision 60 ft., passive Perception 10
languages: understands the languages you know
bestiary: true
traits:
  - name: Festering Aura (Putrid Only)
    desc: "Constitution Saving Throw: DC equals your spell save DC, any creature other than you that starts its turn within a 5-foot emanation originating from the spirit. Failure: The creature has the poisoned condition until the start of its next turn."
    attack_bonus: 0
  - name: Incorporeal Passage (Ghostly Only)
    desc: "The spirit can move through other creatures and objects as if they were difficult terrain. If it ends its turn inside an object, it is shunted to the nearest unoccupied space and takes 1d10 force damage for every 5 feet traveled."
    attack_bonus: 0
actions:
  - name: Multiattack
    desc: "The spirit makes a number of attacks equal to half the spell's level, rounded down."
    attack_bonus: 0
  - name: Deathly Touch (Ghostly Only)
    desc: "Melee Attack Roll: Bonus equals your spell attack modifier, reach 5 ft., one target. Hit: 1d8 + 3 + the spell's level necrotic damage, and the target has the frightened condition until the end of its next turn."
    attack_bonus: 0
    damage_dice: 1d8
    damage_bonus: 3
  - name: Grave Bolt (Skeletal Only)
    desc: "Ranged Attack Roll: Bonus equals your spell attack modifier, range 150 ft., one target. Hit: 2d4 + 3 + the spell's level necrotic damage."
    attack_bonus: 0
    damage_dice: 2d4
    damage_bonus: 3
  - name: Rotting Claw (Putrid Only)
    desc: "Melee Attack Roll: Bonus equals your spell attack modifier, reach 5 ft., one target. Hit: 1d6 + 3 + the spell's level slashing damage. If the target has the poisoned condition, it has the paralyzed condition until the end of its next turn."
    attack_bonus: 0
    damage_dice: 1d6
    damage_bonus: 3
```