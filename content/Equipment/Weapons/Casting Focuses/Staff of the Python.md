---
tags:
  - RAW
  - Weapon
rarity: Uncommon
value: 500 GP
weight: 4 lb.
requires_attunement: true
item_type: Weapon
magic_item_category: Weapon
crafting_time: 2 days
---
*Staff, Uncommon (requires attunement)*

***Weight.*** 4 lb.
***Value.*** 500 GP

As a [[Magic action]], you can throw this staff so that it lands in an unoccupied space within 10 feet of you, causing the staff to become a Giant Constrictor Snake in that space. The snake is under your control and shares your [[Initiative]] count, taking its turn immediately after yours.

On your turn, you can mentally command the snake (no [[action]] required) if it is within 60 feet of you and you don’t have the [[Incapacitated]] condition. You decide what action the snake takes and where it moves during its turn, or you can issue it a general command, such as to attack your enemies or guard a location. Absent commands from you, the snake defends itself.

As a [[Bonus Action]], you can command the snake to revert to staff form in its current space, and you can’t use the staff’s property again for 1 hour. If the snake is reduced to 0 [[Hit Points]], it dies and reverts to its staff form; the staff then shatters and is destroyed. If the snake reverts to staff form before losing all its [[Hit Points]], it regains all of them.

### Giant Constrictor Snake
```statblock
columns: 2
forceColumns: true
name: Giant Constrictor Snake
source: 5e SRD
size: Huge
type: beast
subtype: ""
alignment: unaligned
ac: 12
hp: 60
hit_dice: 8d12 + 8
speed: 30 ft., swim 30 ft.
stats:
  - 19
  - 14
  - 12
  - 1
  - 10
  - 3
skillsaves:
  - perception: 2
damage_vulnerabilities: ""
damage_resistances: ""
damage_immunities: ""
condition_immunities: ""
senses: blindsight 10 ft., passive Perception 12
languages: ""
cr: "2"
bestiary: true
actions:
  - name: Bite
    desc: "Melee Weapon Attack: +6 to hit, reach 10 ft., one creature. Hit: 11 (2d6 + 4) piercing damage."
    attack_bonus: 6
    damage_dice: 2d6
    damage_bonus: 4
  - name: Constrict
    desc: "Melee Weapon Attack: +6 to hit, reach 5 ft., one creature. Hit: 13 (2d8 + 4) bludgeoning damage, and the target is grappled (escape DC 16). Until this grapple ends, the creature is restrained, and the snake can't constrict another target."
    attack_bonus: 6
    damage_dice: 2d8
    damage_bonus: 4

```