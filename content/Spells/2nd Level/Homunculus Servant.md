---
tags:
  - RAW
  - Spell
  - Conjuration
  - Artificer
  - 2nd
casting_time: "1 hour"
ritual: true
range: "10 feet"
components: "V, S, M (a gem worth 100+ GP)"
component_consumed: false
duration: "Instantaneous"
---
_Level 2 Conjuration (Artificer)_

**Casting Time:** 1 hour or Ritual  
**Range:** 10 feet  
**Components:** V, S, M (a gem worth 100+ GP)  
**Duration:** Instantaneous

You summon a special homunculus in an unoccupied space within range. This creature uses the Homunculus Servant stat block. If you already have a homunculus from this spell, the homunculus is replaced by the new one. You determine the homunculus’s appearance, such as a mechanical-looking bird, winged vials, or miniature animate cauldrons.

***Combat.***  The homunculus is an ally to you and your allies. In combat, it shares your [[Initiative]] count, but it takes its turn immediately after yours. It obeys your commands (no [[action]] required by you). If you don’t issue any, it takes the [[Dodge|Dodge action]] and uses its [[Rules/Combat/Movement/Movement|movement]] to avoid danger.

***Using a Higher-Level Spell Slot***  
Use the spell slot’s level for the spell’s level in the stat block.


```statblock
forceColumns: true
columns: 2
name: Homunculus Servant
source: Homunculus Servant
size: Tiny
type: construct
alignment: neutral
ac: 13
hp: "5 + 5 per spell level"
hit_dice: "A number of d4s equal to the spell's level"
speed: 20 ft., fly 30 ft.
stats:
  - 4
  - 15
  - 12
  - 10
  - 10
  - 7
saves:
  - strength: -3
  - dexterity: 2
  - constitution: 1
  - intelligence: 0
  - wisdom: 0
  - charisma: -2
damage_immunities: poison
condition_immunities: exhaustion, poisoned
senses: darkvision 60 ft., passive Perception 10
languages: telepathy 1 mile (works only with you)
bestiary: true
traits:
  - name: Evasion
    desc: If the homunculus is subjected to an effect that allows it to make a Dexterity saving throw to take only half damage, the homunculus instead takes no damage if it succeeds on the save and only half damage if it fails. It can't use this trait if it has the incapacitated condition.
    attack_bonus: 0
  - name: Magic Bond
    desc: The homunculus adds the spell's level to any ability check or saving throw it makes.
    attack_bonus: 0
actions:
  - name: Force Strike
    desc: "Melee or Ranged Attack Roll: Bonus equals your spell attack modifier, reach 5 ft. or range 30 ft., one target. Hit: 1d6 plus the spell's level Force damage."
    attack_bonus: 0
    damage_dice: 1d6
    damage_bonus: 0
reactions:
  - name: Channel Magic
    desc: "Trigger: You cast a spell that has a range of touch while the homunculus is within 120 feet of you. Response: The homunculus delivers the spell through its touch."
    attack_bonus: 0
```