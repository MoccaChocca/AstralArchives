---
tags:
  - Subclass
  - RAW
  - Artificer
---
 *Command a Construct Guardian*  
  
A Battle Smith is a combination of protector and medic, an expert at defending others and repairing both materiel and personnel. To aid in their work, Battle Smiths are accompanied by a Steel Defender, a protective companion of their own creation.  
  
## Level 3: Tool Proficiency  
  
You gain proficiency with Smith’s Tools. If you already have this proficiency, you gain proficiency with one other type of Artisan’s Tools of your choice.  
  
In addition, when you craft an ordinary or magic weapon, the amount of time required to craft it is halved.  
  
## Level 3: Battle Smith Spells  
  
When you reach an Artificer level specified in the Battle Smith Spells table, you thereafter always have the listed spells prepared.  
  
| Artificer Level | Spells                                    |
| --------------: | ----------------------------------------- |
|               3 | *[[Heroism]], [[Shield]]*                   |
|               5 | *[[Shining Smite]], [[Warding Bond]]*       |
|               9 | *[[Aura of Vitality]], [[Conjure Barrage]]* |
|              13 | *[[Aura of Purity]], [[Fire Shield]]*       |
|              17 | *[[Banishing Smite]], [[Mass Cure Wounds]]* |
  
## Level 3: Battle Ready  
  
Your combat training and your experiments with magic have paid off in two ways:  
  
***Arcane Empowerment.*** When you attack with a magic weapon, you can use your [[Intelligence]] modifier, instead of [[Strength]] or [[Dexterity]] modifier, for the attack and damage rolls.  
  
***Weapon Knowledge.*** You gain proficiency with Martial weapons.  
  
## Level 3: Steel Defender  
  
Your tinkering has borne you a companion, a Steel Defender. You determine the defender’s appearance and whether it has two legs or four; your choices don’t affect the defender’s game statistics.  
  
The Steel Defender is Friendly to you and your allies and obeys you. It vanishes if you die.  
  
***The Defender in Combat.*** In combat, the defender acts during your turn. It can move and take its [[Reaction]] on its own, but the only action it takes is the [[Dodge|Dodge action]] unless you take a [[Bonus Action]] to command it to take an action. If you have the [[Incapacitated]] condition, the defender acts on its own and isn’t limited to the [[Dodge|Dodge action]].  
  
***Restoring or Replacing the Defender.*** If the defender has died within the last hour, you can take a [[Magic action]] to touch it and expend a spell slot. The defender returns to life after 1 minute with all its [[Hit Points]] restored.  
  
Whenever you finish a [[Resting|Long Rest]], you can create a new Steel Defender if you have Smith’s Tools in hand. If you already have a defender from this feature, the first one vanishes.  
  
### Steel Defender

```statblock
columns: 2
forceColumns: true
name: Steel Defender
source: Battle Smith
size: Medium Construct
alignment: unaligned
ac: 15
hp: "5 + five times your Artificer level"
hit_dice: "A number of d8s equal to your Artificer level"
speed: 40 ft.
stats:
  - 14
  - 12
  - 14
  - 4
  - 10
  - 6
saves:
  - strength: 2
  - dexterity: 1
  - constitution: 2
  - intelligence: -3
  - wisdom: 0
  - charisma: -2
damage_immunities: poison
condition_immunities: charmed, exhaustion, poisoned
senses: darkvision 60 ft., passive Perception 10
languages: understands the languages you know
bestiary: true
traits:
  - name: Steel Bond
    desc: "The defender adds your [[proficiency bonus]] to any ability check or saving throw it makes."
    attack_bonus: 0
actions:
  - name: Force-Empowered Rend
    desc: "Melee Attack Roll: Bonus equals your spell attack modifier, reach 5 ft., one target. Hit: 1d8 + 2 plus your Intelligence modifier force damage."
    attack_bonus: 0
    damage_dice: 1d8
    damage_bonus: 2
  - name: Repair (3/Day)
    desc: "The defender, or one construct or object it can see within 5 feet of it, regains a number of [[hit points]] equal to 2d8 plus your Intelligence modifier."
    attack_bonus: 0
    damage_dice: 2d8
    damage_bonus: 0
reactions:
  - name: Deflect Attack
    desc: "Trigger: A creature the defender can see within 5 feet of it makes an attack roll targeting a different creature. Response: The triggering creature makes the attack roll with disadvantage."
    attack_bonus: 0
```


## Level 5: Extra Attack

You can attack twice instead of once whenever you take the [[Attack action]] on your turn.

## Level 9: Arcane Jolt

When either you hit a target with an [[Attack Rolls|attack roll]] using a magic weapon or your Steel Defender hits a target, you can channel magical energy through the strike to create one of the following effects:

***Destructive Energy.*** The target takes an extra 2d6 Force damage.

***Restorative Energy.*** Choose one creature or object you can see within 30 feet of the target. Healing energy flows into the chosen recipient, restoring 2d6 [[Hit Points]] to it.

You can use this energy a number of times equal to your [[Intelligence]] modifier (minimum of once), but you can do so no more than once a turn. You regain all expended uses when you finish a [[Resting|Long Rest]].

## Level 15: Improved Defender

Your Arcane Jolt and Steel Defender have become more powerful, granting these benefits:

***Improved Jolt.*** The extra damage and healing of your Arcane Jolt both increase to 4d6.

***Fortified Defender.*** Your Steel Defender gains a +2 bonus to Armor Class.

***Improved Deflection.*** Whenever your Steel Defender uses its Deflect Attack, the attacker takes Force damage equal to 1d4 plus your [[Intelligence]] modifier.

### Improved Steel Defender
```statblock
columns: 2
forceColumns: true
name: Improved Steel Defender
source: Battle Smith
size: Medium Construct
alignment: unaligned
ac: 17
hp: "5 + five times your Artificer level"
hit_dice: "A number of d8s equal to your Artificer level"
speed: 40 ft.
stats:
  - 14
  - 12
  - 14
  - 4
  - 10
  - 6
saves:
  - strength: 2
  - dexterity: 1
  - constitution: 2
  - intelligence: -3
  - wisdom: 0
  - charisma: -2
damage_immunities: poison
condition_immunities: charmed, exhaustion, poisoned
senses: darkvision 60 ft., passive Perception 10
languages: understands the languages you know
bestiary: true
traits:
  - name: Steel Bond
    desc: "The defender adds your proficiency bonus to any ability check or saving throw it makes."
    attack_bonus: 0
actions:
  - name: Force-Empowered Rend
    desc: "Melee Attack Roll: Bonus equals your spell attack modifier, reach 5 ft., one target. Hit: 1d8 + 2 plus your Intelligence modifier force damage."
    attack_bonus: 0
    damage_dice: 1d8
    damage_bonus: 2
  - name: Repair (3/Day)
    desc: "The defender, or one construct or object it can see within 5 feet of it, regains a number of [[hit points]] equal to 2d8 plus your Intelligence modifier."
    attack_bonus: 0
    damage_dice: 2d8
    damage_bonus: 0
reactions:
  - name: Deflect Attack
    desc: "Trigger: A creature the defender can see within 5 feet of it makes an attack roll targeting a different creature. Response: The triggering creature takes 1d4 plus your Intelligence force damage, and makes the triggering attack roll with disadvantage."
    attack_bonus: 0
```