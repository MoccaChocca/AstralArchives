---
tags:
  - RAW
  - Spell
  - Necromancy
  - Cleric
  - Warlock
  - Wizard
  - 6th
casting_time: "1 minute"
ritual: false
range: "10 feet"
components: "V, S, M (one 150+ GP black onyx stone for each corpse)"
component_consumed: false
duration: "Instantaneous"
---
_Level 6 Necromancy (Cleric, Warlock, Wizard)_

**Casting Time:** 1 minute  
**Range:** 10 feet  
**Components:** V, S, M (one 150+ GP black onyx stone for each corpse)  
**Duration:** Instantaneous

You can cast this spell only at night. Choose up to three corpses of Medium or Small Humanoids within range. Each one becomes a Ghoul under your control.

As a [[Bonus Action]] on each of your turns, you can mentally command any creature you animated with this spell if the creature is within 120 feet of you (if you control multiple creatures, you can command any of them at the same time, issuing the same command to them). You decide what [[Action]] the creature will take and where it will move on its next turn, or you can issue a general command, such as to guard a particular place. If you issue no commands, the creature takes the [[Dodge|Dodge action]] and moves only to avoid harm. Once given an order, the creature continues to follow the order until its task is complete.

The creature is under your control for 24 hours, after which it stops obeying any command you’ve given it. To maintain control of the creature for another 24 hours, you must cast this spell on the creature before the current 24-hour period ends. This use of the spell reasserts your control over up to three creatures you have animated with this spell rather than animating new ones.

***Using a Higher-Level Spell Slot.*** If you use a level 7 spell slot, you can animate or reassert control over four Ghouls. If you use a level 8 spell slot, you can animate or reassert control over five Ghouls or two Ghasts or Wights. If you use a level 9 spell slot, you can animate or reassert control over six Ghouls, three Ghasts or Wights, or two Mummies. See the Monster Manual for these stat blocks.

### Ghoul
```statblock
columns: 2
forceColumns: true
name: Ghoul
source: 5e SRD
size: Medium
type: undead
subtype: ""
alignment: chaotic evil
ac: 12
hp: 22
hit_dice: 5d8 + -1
speed: 30 ft.
stats:
  - 13
  - 15
  - 10
  - 7
  - 10
  - 6
damage_vulnerabilities: ""
damage_resistances: ""
damage_immunities: ""
condition_immunities: poisoned
senses: darkvision 60 ft., passive Perception 10
languages: Common
cr: "1"
bestiary: true
actions:
  - name: Bite
    desc: "Melee Weapon Attack: +2 to hit, reach 5 ft., one creature. Hit: 9 (2d6 + 2) piercing damage."
    attack_bonus: 2
    damage_dice: 2d6
    damage_bonus: 2
  - name: Claws
    desc: "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 7 (2d4 + 2) slashing damage. If the target is a creature other than an elf or undead, it must succeed on a DC 10 Constitution saving throw or be paralyzed for 1 minute. The target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success."
    attack_bonus: 0

```