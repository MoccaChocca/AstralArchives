---
tags:
  - RAW
  - Spell
  - Conjuration
  - Druid
  - 4th
casting_time: "Action"
ritual: false
range: "60 feet"
components: "V, S"
component_consumed: false
duration: "Concentration, up to 10 minutes"
---
_Level 4 Conjuration (Druid)_

**Casting Time:** [[Action]]  
**Range:** 60 feet  
**Components:** V, S  
**Duration:** [[Concentration]], up to 10 minutes

You summon a giant centipede, spider, or wasp (chosen when you cast the spell). It manifests in an unoccupied space you can see within range and uses the **Giant Insect** stat block. The form you choose determines certain details in its stat block. The creature disappears when it drops to 0 [[Hit Points]] or when the spell ends.

The creature is an ally to you and your allies. In combat, the creature shares your [[Initiative]] count, but it takes its turn immediately after yours. It obeys your verbal commands (no [[action]] required by you). If you don’t issue any, it takes the [[Dodge|Dodge action]] and uses its [[Rules/Combat/Movement/Movement|movement]] to avoid danger.

***Using a Higher-Level Spell Slot.*** Use the spell slot’s level for the spell’s level in the stat block.

### Giant Insect

```statblock
columns: 2
forceColumns: true
name: Giant Insect
source: Giant Insect
size: Large Beast
alignment: unaligned
ac: "11 + the spell's level"
hp: "30 + 10 for each spell level above 4"
hit_dice: ""
speed: 40 ft., climb 40 ft., fly 40 ft. (Wasp only)
stats:
  - 17
  - 13
  - 15
  - 4
  - 14
  - 3
saves:
  - strength: 3
  - dexterity: 1
  - constitution: 2
  - intelligence: -3
  - wisdom: 2
  - charisma: -4
senses: darkvision 60 ft., passive Perception 12
languages: understands the languages you know
bestiary: true
traits:
  - name: Spider Climb
    desc: "The insect can climb difficult surfaces, including along ceilings, without needing to make an ability check."
    attack_bonus: 0
actions:
  - name: Multiattack
    desc: "The insect makes a number of attacks equal to half the spell's level, rounded down."
    attack_bonus: 0
  - name: Poison Jab
    desc: "Melee Attack Roll: Bonus equals your spell attack modifier, reach 10 ft., one target. Hit: 1d6 + 3 plus the spell's level piercing damage plus 1d4 poison damage."
    attack_bonus: 0
    damage_dice: 1d6 + 1d4
    damage_bonus: 3
  - name: Web Bolt (Spider Only)
    desc: "Ranged Attack Roll: Bonus equals your spell attack modifier, range 60 ft., one target. Hit: 1d10 + 3 plus the spell's level bludgeoning damage, and the target's speed is reduced to 0 until the start of the insect's next turn."
    attack_bonus: 0
    damage_dice: 1d10
    damage_bonus: 3
bonus_actions:
  - name: Venomous Spew (Centipede Only)
    desc: "Constitution Saving Throw: DC equals your spell save DC, one creature the insect can see within 10 feet. Failure: The target has the poisoned condition until the start of the insect's next turn."
    attack_bonus: 0
```