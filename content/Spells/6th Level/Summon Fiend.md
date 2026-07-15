---
tags:
  - RAW
  - Spell
  - Conjuration
  - Warlock
  - Wizard
  - 6th
casting_time: "Action"
ritual: false
range: "90 feet"
components: "V, S, M (a bloody vial worth 600+ GP)"
component_consumed: false
duration: "Concentration, up to 1 hour"
---
_Level 6 Conjuration (Warlock, Wizard)_

**Casting Time:** [[Action]]  
**Range:** 90 feet  
**Components:** V, S, M (a bloody vial worth 600+ GP)  
**Duration:** [[Concentration]], up to 1 hour

You call forth a fiendish spirit. It manifests in an unoccupied space that you can see within range and uses the **Fiendish Spirit** stat block. When you cast the spell, choose Demon, Devil, or Yugoloth. The creature resembles a Fiend of the chosen type, which determines certain details in its stat block. The creature disappears when it drops to 0 [[Hit Points]] or when the spell ends.

The creature is an ally to you and your allies. In combat, the creature shares your [[Initiative]] count, but it takes its turn immediately after yours. It obeys your verbal commands (no [[action]] required by you). If you don’t issue any, it takes the [[Dodge|Dodge action]] and uses its [[Rules/Combat/Movement/Movement|movement]] to avoid danger.

***Using a Higher-Level Spell Slot.*** Use the spell slot’s level for the spell’s level in the stat block.

### Fiendish Spirit

```statblock
columns: 2
forceColumns: true
name: Fiendish Spirit
source: Summon Fiend
size: Large Fiend
alignment: neutral
ac: "12 + the spell's level"
hp: "50 (Demon only), 40 (Devil only), or 60 (Yugoloth only) + 15 for each spell level above 6"
hit_dice: ""
speed: 40 ft.; climb 40 ft. (Demon only); fly 60 ft. (Devil only)
stats:
  - 13
  - 16
  - 15
  - 10
  - 10
  - 16
saves:
  - strength: 1
  - dexterity: 3
  - constitution: 2
  - intelligence: 0
  - wisdom: 0
  - charisma: 3
damage_resistances: fire
damage_immunities: poison
condition_immunities: poisoned
senses: darkvision 60 ft., passive Perception 10
languages: Abyssal, Infernal, telepathy 60 ft.
bestiary: true
traits:
  - name: Death Throes (Demon Only)
    desc: "When the spirit drops to 0 [[hit points]] or the spell ends, the spirit explodes. Dexterity Saving Throw: DC equals your spell save DC, each creature in a 10-foot emanation originating from the spirit. Failure: 2d10 plus the spell's level fire damage. Success: Half damage."
    attack_bonus: 0
    damage_dice: 2d10
  - name: Devil's Sight (Devil Only)
    desc: "Magical darkness doesn't impede the spirit's darkvision."
    attack_bonus: 0
  - name: Magic Resistance
    desc: "The spirit has advantage on saving throws against spells and other magical effects."
    attack_bonus: 0
actions:
  - name: Multiattack
    desc: "The spirit makes a number of attacks equal to half the spell's level, rounded down."
    attack_bonus: 0
  - name: Bite (Demon Only)
    desc: "Melee Attack Roll: Bonus equals your spell attack modifier, reach 5 ft., one target. Hit: 1d12 + 3 + the spell's level necrotic damage."
    attack_bonus: 0
    damage_dice: 1d12
    damage_bonus: 3
  - name: Claws (Yugoloth Only)
    desc: "Melee Attack Roll: Bonus equals your spell attack modifier, reach 5 ft., one target. Hit: 1d8 + 3 + the spell's level slashing damage. Immediately after the attack hits or misses, the spirit can teleport up to 30 feet to an unoccupied space it can see."
    attack_bonus: 0
    damage_dice: 1d8
    damage_bonus: 3
  - name: Fiery Strike (Devil Only)
    desc: "Melee or Ranged Attack Roll: Bonus equals your spell attack modifier, reach 5 ft. or range 150 ft., one target. Hit: 2d6 + 3 + the spell's level fire damage."
    attack_bonus: 0
    damage_dice: 2d6
    damage_bonus: 3
```