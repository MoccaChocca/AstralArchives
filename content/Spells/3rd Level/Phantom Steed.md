---
tags:
  - RAW
  - Spell
  - Illusion
  - Wizard
  - 3rd
casting_time: "1 minute"
ritual: true
range: "30 feet"
components: "V, S"
component_consumed: false
duration: "1 hour"
---
_Level 3 Illusion (Wizard)_

**Casting Time:** 1 minute or [[Rituals|Ritual]]  
**Range:** 30 feet  
**Components:** V, S  
**Duration:** 1 hour

A Large, quasi-real, horselike creature appears on the ground in an unoccupied space of your choice within range. You decide the creature’s appearance, and it is equipped with a saddle, bit, and bridle. Any of the equipment created by the spell vanishes in a puff of smoke if it is carried more than 10 feet away from the steed.

For the duration, you or a creature you choose can ride the steed. The steed uses the Riding Horse stat block, except it has a Speed of 100 feet and can [[travel]] 13 miles in an hour. When the spell ends, the steed gradually fades, giving the rider 1 minute to dismount. The spell ends early if the steed takes any damage.

### Riding Horse

```statblock
forceColumns: true
columns: 2
name: Riding Horse
source: 5e SRD
size: Large
type: beast
subtype: ""
alignment: unaligned
ac: 10
hp: 13
hit_dice: 2d10 + 2
speed: 60 ft.
stats:
  - 16
  - 10
  - 12
  - 2
  - 11
  - 7
damage_vulnerabilities: ""
damage_resistances: ""
damage_immunities: ""
condition_immunities: ""
senses: passive Perception 10
languages: ""
cr: 1/4
bestiary: true
actions:
  - name: Hooves
    desc: "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 8 (2d4 + 3) bludgeoning damage."
    attack_bonus: 5
    damage_dice: 2d4
    damage_bonus: 3

```