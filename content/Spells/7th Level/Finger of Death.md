---
tags:
  - RAW
  - Spell
  - Necromancy
  - Sorcerer
  - Warlock
  - Wizard
  - 7th
casting_time: "Action"
ritual: false
range: "60 feet"
components: "V, S"
component_consumed: false
duration: "Instantaneous"
---
_Level 7 Necromancy (Sorcerer, Warlock, Wizard)_

**Casting Time:** [[Action]]  
**Range:** 60 feet  
**Components:** V, S  
**Duration:** Instantaneous

You unleash negative energy toward a creature you can see within range. The target makes a [[Saving Throws|Constitution saving throw]], taking 7d8 + 30 Necrotic damage on a failed save or half as much damage on a successful one.

A Humanoid killed by this spell rises at the start of your next turn as a Zombie that follows your verbal orders.

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
    desc: If damage reduces the zombie to 0 [[hit points]], it must make a Constitution saving throw with a DC of 5+the damage taken, unless the damage is radiant or from a critical hit. On a success, the zombie drops to 1 [[Hit Points|hit point]] instead.
    attack_bonus: 0
actions:
  - name: Slam
    desc: "Melee Weapon Attack: +3 to hit, reach 5 ft., one target. Hit: 4 (1d6 + 1) bludgeoning damage."
    attack_bonus: 3
    damage_dice: 1d6
    damage_bonus: 1

```