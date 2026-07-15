---
tags:
  - RAW
  - Spell
  - Conjuration
  - Artificer
  - Wizard
  - 4th
casting_time: "Action"
ritual: false
range: "90 feet"
components: "V, S, M (a lockbox worth 400+ GP)"
component_consumed: false
duration: "Concentration, up to 1 hour"
---
_Level 4 Conjuration (Artificer, Wizard)_

**Casting Time:** [[Action]]  
**Range:** 90 feet  
**Components:** V, S, M (a lockbox worth 400+ GP)  
**Duration:** [[Concentration]], up to 1 hour

You call forth the spirit of a Construct. It manifests in an unoccupied space that you can see within range and uses the **Construct Spirit** stat block. When you cast the spell, choose a material: Clay, Metal, or Stone. The creature resembles an animate statue (you determine the appearance) made of the chosen material, which determines certain details in its stat block. The creature disappears when it drops to 0 [[Hit Points]] or when the spell ends.

The creature is an ally to you and your allies. In combat, the creature shares your [[Initiative]] count, but it takes its turn immediately after yours. It obeys your verbal commands (no [[action]] required by you). If you don’t issue any, it takes the [[Dodge|Dodge action]] and uses its [[Rules/Combat/Movement/Movement|movement]] to avoid danger.

***Using a Higher-Level Spell Slot.*** Use the spell slot’s level for the spell’s level in the stat block.

### Construct Spirit
```statblock
columns: 2
forceColumns: true
name: Construct Spirit
source: Summon Construct
size: Medium
type: construct
subtype: ""
alignment: neutral
ac: "13 + the spell's level"
hp: "40 + 15 for each spell level above 4"
hit_dice: ""
speed: 30 ft.
stats:
  - 18
  - 10
  - 18
  - 14
  - 11
  - 5
saves:
  - strength: 4
  - dexterity: 0
  - constitution: 4
  - intelligence: 2
  - wisdom: 0
  - charisma: -3
skillsaves: []
damage_vulnerabilities: ""
damage_resistances: poison
damage_immunities: ""
condition_immunities: charmed, exhaustion, frightened, paralyzed, poisoned
senses: darkvision 60 ft., passive Perception 10
languages: understands the languages you know
cr: "0"
bestiary: true
traits:
  - name: Heated Body (Metal Only)
    desc: "A creature that hits the spirit with a melee attack or that starts its turn in a grapple with the spirit takes 1d10 fire damage."
    attack_bonus: 0
    damage_dice: 1d10
  - name: Stony Lethargy (Stone Only)
    desc: "When a creature starts its turn within 10 feet of the spirit, the spirit can target it with magical energy if the spirit can see it. Wisdom Saving Throw: DC equals your spell save DC, the target. Failure: Until the start of its next turn, the target can't make opportunity attacks, and its speed is halved."
    attack_bonus: 0
actions:
  - name: Multiattack
    desc: "The spirit makes a number of Slam attacks equal to half the spell's level, rounded down."
    attack_bonus: 0
  - name: Slam
    desc: "Melee Attack Roll: Bonus equals your spell attack modifier, reach 5 ft., one target. Hit: 1d8 + 4 + the spell's level bludgeoning damage."
    attack_bonus: 0
    damage_dice: 1d8
    damage_bonus: 4
reactions:
  - name: Berserk Lashing (Clay Only)
    desc: "Trigger: The spirit takes damage from a creature. Response: The spirit makes a Slam attack against that creature if possible, or the spirit moves up to half its speed toward that creature without provoking opportunity attacks."
    attack_bonus: 0
```