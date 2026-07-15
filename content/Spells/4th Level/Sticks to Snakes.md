---
tags:
  - RAW
  - Spell
  - Transmutation
  - Cleric
  - Druid
  - Ranger
  - 4th
casting_time: "Action"
ritual: false
range: "90 feet"
components: "V, S, M"
component_consumed: false
duration: "Concentration, up to 1 minute"
---
_Level 4 Transmutation (Cleric, Druid, Ranger)_

**Casting Time:** [[Action]]  
**Range:** 90 feet  
**Components:** V, S, M (a small piece of bark and several snake scales)  
**Duration:** [[Concentration]], up to 1 minute

You can choose up to four nonmagical sticks no longer than a Quarterstaff (or similar pieces of nonmagical wood, such as Torches, Spears, etc.) that you can see within range to shape-shift into snakes. Creatures that are holding a targeted object can make a [[Saving Throws|Charisma saving throw]], preventing the target from shape-shifting on a success. Each shape-shifted target uses the _Venomous Snake_ stat block.

Each of these snakes is Friendly to you and your allies. In combat, it shares your [[Initiative]] count and takes its turn immediately after yours.

Until the spell ends, you can take a [[Bonus Action]] to mentally command any creature you made with this spell if the creature is within 500 feet of you (if you control multiple creatures, you can command any of them at the same time, issuing the same command to each one). If you issue no commands, the creature takes the [[Dodge|Dodge action]] and moves only to avoid harm. When the creature drops to 0 [[Hit Points]], it reverts to its object form, and any remaining damage carries over to that form.

***Using a Higher-Level Spell Slot.*** You can target two additional objects for each spell slot level above 4.

### Venomous Snake

```statblock
forceColumns: true
columns: 2
name: Venomous Snake
source: ""
size: Tiny
type: beast
subtype: ""
alignment: unaligned
ac: 12
hp: 5
hit_dice: 2d4
speed: 30 ft., swim 30 ft.
stats:
  - 2
  - 15
  - 11
  - 1
  - 10
  - 3
saves:
  - strength: -4
  - dexterity: 2
  - constitution: 0
  - intelligence: -5
  - wisdom: 0
  - charisma: -4
skillsaves: []
damage_vulnerabilities: ""
damage_resistances: ""
damage_immunities: ""
condition_immunities: ""
senses: blindsight 10 ft., passive Perception 10
languages: none
cr: "1/8"
bestiary: true
actions:
  - name: Bite
    desc: "Melee Attack Roll: +4, reach 5 ft., one target. Hit: 4 (1d4 + 2) piercing damage plus 3 (1d6) poison damage."
    attack_bonus: 4
    damage_dice: 1d4 + 1d6
    damage_bonus: 2
```