---
tags:
  - RAW
  - Spell
  - Necromancy
  - Cleric
  - Wizard
  - 3rd
casting_time: "1 minute"
ritual: false
range: "10 feet"
components: "V, S, M"
component_consumed: false
duration: "Instantaneous"
---
_Level 3 Necromancy (Cleric, Wizard)_

**Casting Time:** 1 minute  
**Range:** 10 feet  
**Components:** V, S, M (a drop of blood, a piece of flesh, and a pinch of bone dust)  
**Duration:** Instantaneous

Choose a pile of bones or a corpse of a Medium or Small Humanoid within range. The target becomes an Undead creature: a Skeleton if you chose bones or a Zombie if you chose a corpse.

On each of your turns, you can take a [[Bonus Action]] to mentally command any creature you made with this spell if the creature is within 60 feet of you (if you control multiple creatures, you can command any of them at the same time, issuing the same command to each one). You decide what [[Action]] the creature will take and where it will move on its next turn, or you can issue a general command, such as to guard a chamber or corridor. If you issue no commands, the creature takes the [[Dodge|Dodge action]] and moves only to avoid harm. Once given an order, the creature continues to follow it until its task is complete.

The creature is under your control for 24 hours, after which it stops obeying any command you’ve given it. To maintain control of the creature for another 24 hours, you must cast this spell on the creature again before the current 24-hour period ends. This use of the spell reasserts your control over up to four creatures you have animated with this spell rather than animating a new creature.

***Using a Higher-Level Spell Slot.*** You animate or reassert control over two additional Undead creatures for each spell slot level above 3. Each of the creatures must come from a different corpse or pile of bones.

### Zombie

```statblock
columns: 2
forceColumns: true
name: Zombie
source: 5e SRD
size: Medium
type: undead
subtype: ""
alignment: neutral evil
ac: 8
hp: 22
hit_dice: 3d8 + 8
speed: 20 ft.
stats:
  - 13
  - 6
  - 16
  - 3
  - 6
  - 5
saves:
  - wisdom: 0
damage_vulnerabilities: ""
damage_resistances: ""
damage_immunities: ""
condition_immunities: poisoned
senses: darkvision 60 ft., passive Perception 8
languages: understands all languages it spoke in life but can't speak
cr: 1/4
bestiary: true
traits:
  - name: Undead Fortitude
    desc: If damage reduces the zombie to 0 hit points, it must make a [[Saving Throws|Constitution saving throw]] with a DC of 5+the damage taken, unless the damage is radiant or from a critical hit. On a success, the zombie drops to 1 [[Hit Points|hit point]] instead.
    attack_bonus: 0
actions:
  - name: Slam
    desc: "Melee Weapon Attack: +3 to hit, reach 5 ft., one target. Hit: 4 (1d6 + 1) bludgeoning damage."
    attack_bonus: 3
    damage_dice: 1d6
    damage_bonus: 1

```



### Skeleton

```statblock
columns: 2
forceColumns: true
name: Skeleton
source: 5e SRD
size: Medium
type: undead
subtype: ""
alignment: lawful evil
ac: 13
hp: 13
hit_dice: 2d8 + 4
speed: 30 ft.
stats:
  - 10
  - 14
  - 15
  - 6
  - 8
  - 5
damage_vulnerabilities: bludgeoning
damage_resistances: ""
damage_immunities: ""
condition_immunities: poisoned
senses: darkvision 60 ft., passive Perception 9
languages: understands all languages it spoke in life but can't speak
cr: 1/4
bestiary: true
actions:
  - name: Shortsword
    desc: "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 5 (1d6 + 2) piercing damage."
    attack_bonus: 4
    damage_dice: 1d6
    damage_bonus: 2
  - name: Shortbow
    desc: "Ranged Weapon Attack: +4 to hit, range 80/320 ft., one target. Hit: 5 (1d6 + 2) piercing damage."
    attack_bonus: 4
    damage_dice: 1d6
    damage_bonus: 2

```