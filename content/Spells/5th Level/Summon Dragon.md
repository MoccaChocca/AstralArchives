---
tags:
  - RAW
  - Spell
  - Conjuration
  - Wizard
  - 5th
casting_time: "Action"
ritual: false
range: "60 feet"
components: "V, S, M (an object with the image of a dragon engraved on it worth 500+ GP)"
component_consumed: false
duration: "Concentration, up to 1 hour"
---

_Level 5 Conjuration (Wizard)_

**Casting Time:** Action  
**Range:** 60 feet  
**Components:** V, S, M (an object with the image of a dragon engraved on it worth 500+ GP)  
**Duration:** [[Concentration]], up to 1 hour

You call forth a Dragon spirit. It manifests in an unoccupied space that you can see within range and uses the **Draconic Spirit** stat block. The creature disappears when it drops to 0 [[Hit Points]] or when the spell ends.

The creature is an ally to you and your allies. In combat, the creature shares your [[Initiative]] count, but it takes its turn immediately after yours. It obeys your verbal commands (no [[action]] required by you). If you don’t issue any, it takes the [[Dodge|Dodge action]] and uses its [[Rules/Combat/Movement/Movement|movement]] to avoid danger.

***Using a Higher-Level Spell Slot.*** Use the spell slot’s level for the spell’s level in the stat block.

### Draconic Spirit

```statblock
columns: 2
forceColumns: true
name: Draconic Spirit
source: Summon Draconic Spirit
size: Large Dragon
alignment: neutral
ac: "14 + the spell's level"
hp: "50 + 10 for each spell level above 5"
hit_dice: ""
speed: 30 ft., fly 60 ft., swim 30 ft.
stats:
  - 19
  - 14
  - 17
  - 10
  - 14
  - 14
saves:
  - strength: 4
  - dexterity: 2
  - constitution: 3
  - intelligence: 0
  - wisdom: 2
  - charisma: 2
damage_resistances: acid, cold, fire, lightning, poison
condition_immunities: charmed, frightened, poisoned
senses: blindsight 30 ft., darkvision 60 ft., passive Perception 12
languages: Draconic, understands the languages you know
bestiary: true
traits:
  - name: Shared Resistances
    desc: "When you summon the spirit, choose one of its resistances. You have resistance to the chosen damage type until the spell ends."
    attack_bonus: 0
actions:
  - name: Multiattack
    desc: "The spirit makes a number of Rend attacks equal to half the spell's level, rounded down, and it uses Breath Weapon."
    attack_bonus: 0
  - name: Rend
    desc: "Melee Attack Roll: Bonus equals your spell attack modifier, reach 10 ft., one target. Hit: 1d6 + 4 + the spell's level piercing damage."
    attack_bonus: 0
    damage_dice: 1d6
    damage_bonus: 4
  - name: Breath Weapon
    desc: "Dexterity Saving Throw: DC equals your spell save DC, each creature in a 30-foot cone. Failure: 2d6 damage of a type this spirit has resistance to, chosen when you cast the spell. Success: Half damage."
    attack_bonus: 0
    damage_dice: 2d6
```