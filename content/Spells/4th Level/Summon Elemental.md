---
tags:
  - RAW
  - Spell
  - Conjuration
  - Druid
  - Ranger
  - Wizard
  - 4th
casting_time: Action
ritual: false
range: 90 feet
components: V, S, M (air, a pebble, ash, and water inside a gold-inlaid vial worth 400+ GP)
component_consumed: false
duration: Concentration, up to 1 hour
---
_Level 4 Conjuration (Druid, Ranger, Wizard)_

**Casting Time:** [[Action]]  
**Range:** 90 feet  
**Components:** V, S, M (air, a pebble, ash, and water inside a gold-inlaid vial worth 400+ GP)  
**Duration:** [[Concentration]], up to 1 hour

You call forth an Elemental spirit. It manifests in an unoccupied space that you can see within range and uses the **Elemental Spirit** stat block. When you cast the spell, choose an element: Air, Earth, Fire, or Water. The creature resembles a bipedal form wreathed in the chosen element, which determines certain details in its stat block. The creature disappears when it drops to 0 [[Hit Points]] or when the spell ends.

The creature is an ally to you and your allies. In combat, the creature shares your [[Initiative]] count, but it takes its turn immediately after yours. It obeys your verbal commands (no [[action]] required by you). If you don’t issue any, it takes the [[Dodge|Dodge action]] and uses its [[Rules/Combat/Movement/Movement|movement]] to avoid danger.

***Using a Higher-Level Spell Slot.*** Use the spell slot’s level for the spell’s level in the stat block.

### Elemental Spirit
```statblock
columns: 2
forceColumns: true
name: Elemental Spirit
source: Summon Elemental
size: Medium
type: elemental
subtype: ""
alignment: neutral
ac: "11 + the spell's level"
hp: "50 + 10 for each spell level above 4"
hit_dice: ""
speed: 40 ft.; burrow 40 ft. (Earth only); fly 40 ft. (hover; Air only); swim 40 ft. (Water only)
stats:
  - 18
  - 15
  - 17
  - 4
  - 10
  - 16
saves:
  - strength: 4
  - dexterity: 2
  - constitution: 3
  - intelligence: -3
  - wisdom: 0
  - charisma: 3
skillsaves: []
damage_vulnerabilities: ""
damage_resistances: acid (Water only), lightning and thunder (Air only), piercing and slashing (Earth only)
damage_immunities: fire (Fire only), poison
condition_immunities: exhaustion, paralyzed, petrified, poisoned
senses: darkvision 60 ft., passive Perception 10
languages: Primordial, understands the languages you know
cr: "0"
bestiary: true
traits:
  - name: Amorphous Form (Air, Fire, and Water Only)
    desc: "The spirit can move through a space as narrow as 1 inch wide without it counting as difficult terrain."
    attack_bonus: 0
actions:
  - name: Multiattack
    desc: "The spirit makes a number of Slam attacks equal to half the spell's level, rounded down."
    attack_bonus: 0
  - name: Slam
    desc: "Melee Attack Roll: Bonus equals your spell attack modifier, reach 5 ft., one target. Hit: 1d10 + 4 + the spell's level bludgeoning damage if the spirit is Earth, cold damage if it is Water, lightning damage if it is Air, or fire damage if it is Fire."
    attack_bonus: 0
    damage_dice: 1d10
    damage_bonus: 4
```