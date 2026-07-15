---
tags:
  - RAW
  - Spell
  - Conjuration
  - Druid
  - Ranger
  - Warlock
  - Wizard
  - 3rd
casting_time: "Action"
ritual: false
range: "90 feet"
components: "V, S, M (a gilded flower worth 300+ GP)"
component_consumed: false
duration: "Concentration, up to 1 hour"
---
_Level 3 Conjuration (Druid, Ranger, Warlock, Wizard)_

**Casting Time:** [[Action]]  
**Range:** 90 feet  
**Components:** V, S, M (a gilded flower worth 300+ GP)  
**Duration:** [[Concentration]], up to 1 hour

You call forth a Fey spirit. It manifests in an unoccupied space that you can see within range and uses the **Fey Spirit** stat block. When you cast the spell, choose a mood: Fuming, Mirthful, or Tricksy. The creature resembles a Fey creature of your choice marked by the chosen mood, which determines certain details in its stat block. The creature disappears when it drops to 0 [[Hit Points]] or when the spell ends.

The creature is an ally to you and your allies. In combat, the creature shares your [[Initiative]] count, but it takes its turn immediately after yours. It obeys your verbal commands (no [[action]] required by you). If you don’t issue any, it takes the [[Dodge|Dodge action]] and uses its [[Rules/Combat/Movement/Movement|movement]] to avoid danger.

***Using a Higher-Level Spell Slot.*** Use the spell slot’s level for the spell’s level in the stat block.

### Fey Spirit

```statblock
columns: 2
forceColumns: true
name: Fey Spirit
source: Summon Fey
size: Small
type: fey
subtype: ""
alignment: neutral
ac: "12 + the spell's level"
hp: "30 + 10 for each spell level above 3"
hit_dice: ""
speed: 30 ft., fly 30 ft.
stats:
  - 13
  - 16
  - 14
  - 14
  - 11
  - 16
saves:
  - strength: 1
  - dexterity: 3
  - constitution: 2
  - intelligence: 2
  - wisdom: 0
  - charisma: 3
skillsaves: []
damage_vulnerabilities: ""
damage_resistances: ""
damage_immunities: ""
condition_immunities: charmed
senses: darkvision 60 ft., passive Perception 10
languages: Sylvan, understands the languages you know
cr: "0"
bestiary: true
actions:
  - name: Multiattack
    desc: "The spirit makes a number of Fey Blade attacks equal to half the spell's level, rounded down."
    attack_bonus: 0
  - name: Fey Blade
    desc: "Melee Attack Roll: Bonus equals your spell attack modifier, reach 5 ft., one target. Hit: 2d6 + 3 + the spell's level force damage."
    attack_bonus: 0
    damage_dice: 2d6
    damage_bonus: 3
bonus_actions:
  - name: Fey Step
    desc: "The spirit magically teleports up to 30 feet to an unoccupied space it can see. After teleporting, it uses one of the following mood effects."
    attack_bonus: 0
  - name: "Fey Step: Fuming"
    desc: "After the spirit uses Fey Step, it has advantage on the next attack roll it makes before the end of this turn."
    attack_bonus: 0
  - name: "Fey Step: Mirthful"
    desc: "After the spirit uses Fey Step, one creature the spirit can see within 10 feet of itself must make a Wisdom saving throw against your spell save DC. On a failed save, the target is charmed by you and the spirit for 1 minute or until the target takes any damage."
    attack_bonus: 0
  - name: "Fey Step: Tricksy"
    desc: "After the spirit uses Fey Step, it fills a 10-foot cube within 5 feet of itself with magical darkness, which lasts until the end of its next turn."
    attack_bonus: 0
```
