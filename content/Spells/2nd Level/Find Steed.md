---
tags:
  - RAW
  - Spell
  - Conjuration
  - Paladin
  - 2nd
casting_time: "Action"
ritual: false
range: "30 feet"
components: "V, S"
component_consumed: false
duration: "Instantaneous"
---
_Level 2 Conjuration (Paladin)_

**Casting Time:** [[Action]]  
**Range:** 30 feet  
**Components:** V, S  
**Duration:** Instantaneous

You summon an otherworldly being that appears as a loyal steed in an unoccupied space of your choice within range. This creature uses the **Otherworldly Steed** stat block. If you already have a steed from this spell, the steed is replaced by the new one.

The steed resembles a Large, rideable animal of your choice, such as a horse, a camel, a dire wolf, or an elk. Whenever you cast the spell, choose the steed’s creature type—Celestial, Fey, or Fiend—which determines certain traits in the stat block.

***Combat.*** The steed is an ally to you and your allies. In combat, it shares your [[Initiative]] count, and it functions as a controlled mount while you ride it (as defined in the rules on mounted combat). If you have the [[Incapacitated]] condition, the steed takes its turn immediately after yours and acts independently, focusing on protecting you.

***Disappearance of the Steed.*** The steed disappears if it drops to 0 [[Hit Points]] or if you die. When it disappears, it leaves behind anything it was wearing or carrying. If you cast this spell again, you decide whether you summon the steed that disappeared or a different one.

***Using a Higher-Level Spell Slot.*** Use the spell slot’s level for the spell’s level in the stat block.


```statblock
forceColumns: true
columns: 2
name: Otherworldly Steed
source: Find Steed
size: Large
type: celestial, fey, or fiend (your choice)
alignment: neutral
ac: "10 + 1 per spell level"
hp: "5 + 10 per spell level"
hit_dice: "A number of d10s equal to the spell's level"
speed: 60 ft., fly 60 ft. (requires level 4+ spell)
stats:
  - 18
  - 12
  - 14
  - 6
  - 12
  - 8
saves:
  - strength: 4
  - dexterity: 1
  - constitution: 2
  - intelligence: -2
  - wisdom: 1
  - charisma: -1
senses: passive Perception 11
languages: telepathy 1 mile (works only with you)
bestiary: true
traits:
  - name: Life Bond
    desc: When you regain [[hit points]] from a level 1+ spell, the steed regains the same number of [[hit points]] if you're within 5 feet of it.
    attack_bonus: 0
actions:
  - name: Otherworldly Slam
    desc: "Melee Attack Roll: Bonus equals your spell attack modifier, reach 5 ft., one target. Hit: 1d8 plus the spell's level Radiant damage if the steed is a Celestial, Psychic damage if the steed is a Fey, or Necrotic damage if the steed is a Fiend."
    attack_bonus: 0
    damage_dice: 1d8
    damage_bonus: 0
bonus_actions:
  - name: Fell Glare (Fiend Only; Recharges after a [[Resting|Long Rest]])
    desc: "Wisdom Saving Throw: DC equals your spell save DC, one creature within 60 feet of the steed that the steed can see. Failure: The target has the frightened condition until the end of your next turn."
    attack_bonus: 0
  - name: Fey Step (Fey Only; Recharges after a Long Rest)
    desc: The steed teleports, along with its rider, to an unoccupied space of your choice up to 60 feet away from itself.
    attack_bonus: 0
  - name: Healing Touch (Celestial Only; Recharges after a Long Rest)
    desc: One creature within 5 feet of the steed regains a number of [[hit points]] equal to 2d8 plus the spell's level.
    attack_bonus: 0
    damage_dice: 2d8
    damage_bonus: 0
```
