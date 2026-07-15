---
tags:
  - RAW
  - Spell
  - Conjuration
  - Cleric
  - Paladin
  - 5th
casting_time: "Action"
ritual: false
range: "90 feet"
components: "V, S, M (a reliquary worth 500+ GP)"
component_consumed: false
duration: "Concentration, up to 1 hour"
---

_Level 5 Conjuration (Cleric, Paladin)_

**Casting Time:** [[Action]]  
**Range:** 90 feet  
**Components:** V, S, M (a reliquary worth 500+ GP)  
**Duration:** [[Concentration]], up to 1 hour

You call forth a Celestial spirit. It manifests in an angelic form in an unoccupied space that you can see within range and uses the **Celestial Spirit** stat block. When you cast the spell, choose Avenger or Defender. Your choice determines certain details in its stat block. The creature disappears when it drops to 0 [[Hit Points]] or when the spell ends.

The creature is an ally to you and your allies. In combat, the creature shares your [[Initiative]] count, but it takes its turn immediately after yours. It obeys your verbal commands (no [[action]] required by you). If you don’t issue any, it takes the [[Dodge|Dodge action]] and uses its [[Rules/Combat/Movement/Movement|movement]] to avoid danger.

***Using a Higher-Level Spell Slot.*** Use the spell slot’s level for the spell’s level in the stat block.

### Celestial Spirit

```statblock
columns: 2
forceColumns: true
name: Celestial Spirit
source: Summon Celestial
size: Large Celestial
alignment: neutral
ac: "11 + the spell's level + 2 (Defender only)"
hp: "40 + 10 for each spell level above 5"
hit_dice: ""
speed: 30 ft., fly 40 ft.
stats:
  - 16
  - 14
  - 16
  - 10
  - 14
  - 16
saves:
  - strength: 3
  - dexterity: 2
  - constitution: 3
  - intelligence: 0
  - wisdom: 2
  - charisma: 3
damage_resistances: radiant
condition_immunities: charmed, frightened
senses: darkvision 60 ft., passive Perception 12
languages: Celestial, understands the languages you know
bestiary: true
actions:
  - name: Multiattack
    desc: "The spirit makes a number of attacks equal to half the spell's level, rounded down."
    attack_bonus: 0
  - name: Radiant Bow (Avenger Only)
    desc: "Ranged Attack Roll: Bonus equals your spell attack modifier, range 600 ft., one target. Hit: 2d6 + 2 + the spell's level radiant damage."
    attack_bonus: 0
    damage_dice: 2d6
    damage_bonus: 2
  - name: Radiant Mace (Defender Only)
    desc: "Melee Attack Roll: Bonus equals your spell attack modifier, reach 5 ft., one target. Hit: 1d10 + 3 + the spell's level radiant damage, and the spirit can choose itself or another creature it can see within 10 feet of the target. The chosen creature gains 1d10 [[temporary hit points]]."
    attack_bonus: 0
    damage_dice: 1d10
    damage_bonus: 3
  - name: Healing Touch (1/Day)
    desc: "The spirit touches another creature. The target regains [[hit points]] equal to 2d8 + the spell's level."
    attack_bonus: 0
    damage_dice: 2d8
    damage_bonus: 0
```