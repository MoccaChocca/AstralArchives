---
tags:
  - RAW
  - Spell
  - Conjuration
  - Warlock
  - Wizard
  - 4th
casting_time: "Action"
ritual: false
range: "90 feet"
components: "V, S, M (a pickled tentacle and an eyeball in a platinum-inlaid vial worth 400+ GP)"
component_consumed: false
duration: "Concentration, up to 1 hour"
---
_Level 4 Conjuration (Warlock, Wizard)_

**Casting Time:** [[Action]]  
**Range:** 90 feet  
**Components:** V, S, M (a pickled tentacle and an eyeball in a platinum-inlaid vial worth 400+ GP)  
**Duration:** [[Concentration]], up to 1 hour

You call forth an aberrant spirit. It manifests in an unoccupied space that you can see within range and uses the **Aberrant Spirit** stat block. When you cast the spell, choose Beholderkin, Mind Flayer, or Slaad. The creature resembles an Aberration of that kind, which determines certain details in its stat block. The creature disappears when it drops to 0 [[Hit Points]] or when the spell ends.

The creature is an ally to you and your allies. In combat, it shares your [[Initiative]] count, but it takes its turn immediately after yours. It obeys your verbal commands (no [[action]] required by you). If you don’t issue any, it takes the [[Dodge|Dodge action]] and uses its [[Rules/Combat/Movement/Movement|movement]] to avoid danger.

***Using a Higher-Level Spell Slot.*** Use the spell slot’s level for the spell’s level in the stat block.

### Aberrant Spirit
```statblock
columns: 2
forceColumns: true
name: Aberrant Spirit
source: Summon Aberration
size: Medium
type: aberration
subtype: ""
alignment: neutral
ac: "11 + the spell's level"
hp: "40 + 10 for each spell level above 4"
hit_dice: ""
speed: 30 ft.; fly 30 ft. (hover; Beholderkin only)
stats:
  - 16
  - 10
  - 15
  - 16
  - 10
  - 6
saves:
  - strength: 3
  - dexterity: 0
  - constitution: 2
  - intelligence: 3
  - wisdom: 0
  - charisma: -2
skillsaves: []
damage_vulnerabilities: ""
damage_resistances: ""
damage_immunities: psychic
condition_immunities: ""
senses: darkvision 60 ft., passive Perception 10
languages: Deep Speech, understands the languages you know
cr: "0"
bestiary: true
traits:
  - name: Regeneration (Slaad Only)
    desc: "The spirit regains 5 [[hit points]] at the start of its turn if it has at least 1 [[Hit Points|hit point]]."
    attack_bonus: 0
  - name: Whispering Aura (Mind Flayer Only)
    desc: "At the start of each of the spirit's turns, the spirit emits psionic energy if it doesn't have the incapacitated condition. Wisdom Saving Throw: DC equals your spell save DC, each creature other than you within 5 feet of the spirit. Failure: 2d6 psychic damage."
    attack_bonus: 0
    damage_dice: 2d6
actions:
  - name: Multiattack
    desc: "The spirit makes a number of attacks equal to half the spell's level, rounded down."
    attack_bonus: 0
  - name: Claw (Slaad Only)
    desc: "Melee Attack Roll: Bonus equals your spell attack modifier, reach 5 ft., one target. Hit: 1d10 + 3 + the spell's level slashing damage, and the target can't regain [[hit points]] until the start of the spirit's next turn."
    attack_bonus: 0
    damage_dice: 1d10
    damage_bonus: 3
  - name: Eye Ray (Beholderkin Only)
    desc: "Ranged Attack Roll: Bonus equals your spell attack modifier, range 150 ft., one target. Hit: 1d8 + 3 + the spell's level psychic damage."
    attack_bonus: 0
    damage_dice: 1d8
    damage_bonus: 3
  - name: Psychic Slam (Mind Flayer Only)
    desc: "Melee Attack Roll: Bonus equals your spell attack modifier, reach 5 ft., one target. Hit: 1d8 + 3 + the spell's level psychic damage."
    attack_bonus: 0
    damage_dice: 1d8
    damage_bonus: 3
```