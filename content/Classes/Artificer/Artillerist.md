---
tags:
  - Subclass
  - RAW
  - Artificer
---
 *Wield Destructive Power from Afar*  
  
An Artillerist specializes in using magic to hurl energy, projectiles, and explosions on a battlefield.  
  
## Level 3: Tool Proficiency  
  
You gain proficiency with Woodcarver’s Tools. If you already have this proficiency, you gain proficiency with one other type of Artisan’s Tools of your choice.

In addition, when you craft a magic Wand, the amount of time required to craft it is halved.
  
## Level 3: Artillerist Spells  
  
When you reach an Artificer level specified in the Artillerist Spells table, you thereafter always have the listed spells prepared.

| Artificer Level | Spells                      |
| --------------: | --------------------------- |
|               3 | *[[Shield]], [[Thunderwave]]*         |
|               5 | *[[Scorching Ray]], [[Shatter]]*      |
|               9 | *[[Fireball]], [[Wind Wall]]*         |
|              13 | *[[Ice Storm]], [[Wall of Fire]]*     |
|              17 | *[[Cone of Cold]], [[Wall of Force]]* |

## Level 3: Eldritch Cannon  
Using Woodcarver’s Tools or Smith’s Tools, you can take a [[Magic action]] to create a Small or Tiny Eldritch Cannon in an unoccupied space on a horizontal surface within 5 feet of yourself. The cannon’s game statistics appear below. You determine its appearance, which includes your choice of legs or wheels. It disappears if it is reduced to 0 [[Hit Points]] or after 1 hour. You can command the cannon as a [[bonus action]] and you can dismiss it early as a [[Magic action]].

Once you create a cannon, you can’t do so again until you finish a [[Resting|Long Rest]] or expend a spell slot to create one. You can have only one cannon at a time and can’t create one while your cannon is present.

### Eldritch Cannon  

```statblock
columns: 2
forceColumns: true
name: Eldritch Cannon
source: Artillerist
size: Small or Tiny object
ac: 18
hp: "5 × your Artificer level"
speed: "Special; when activated, the cannon can move up to 15 ft. before or after the chosen option"
damage_immunities: poison, psychic
bestiary: true
traits:
  - name: Mending
    desc: "Casting Mending on the cannon restores 2d6 [[hit points]] to it."
    attack_bonus: 0
bonus_actions:
  - name: Activate Cannon
    desc: "Requires you to be within 60 feet of the cannon. As a bonus action, you order the cannon to use Flamethrower, Force Ballista, or Protector. You can direct the cannon to move up to 15 feet before or after using that option."
    attack_bonus: 0
  - name: Flamethrower
    desc: "The cannon exhales fire in a 15-foot cone. Each creature in that area makes a Dexterity saving throw against your spell save DC, taking 2d8 fire damage on a failed save or half as much damage on a successful one. Flammable objects in the cone that aren't being worn or carried start burning."
    attack_bonus: 0
    damage_dice: 2d8
  - name: Force Ballista
    desc: "Make a ranged spell attack originating from the cannon at one creature or object within 120 feet of it. On a hit, the target takes 2d8 force damage, and if the target is a creature, it is pushed up to 5 feet away from the cannon."
    attack_bonus: 0
    damage_dice: 2d8
  - name: Protector
    desc: "The cannon emits a burst of positive energy that grants itself and each creature of your choice within 10 feet of it a number of [[temporary hit points]] equal to 1d8 plus your Intelligence modifier, minimum of 1 [[Temporary Hit Points|temporary hit point]]."
    attack_bonus: 0
    damage_dice: 1d8
```

## Level 5: Arcane Firearm  
  
When you finish a [[Resting|Long Rest]], you can use Woodcarver’s Tools to carve special sigils into a Rod, Staff, or Wand and thereby turn it into your arcane firearm. The sigils disappear from the object if you later carve them on a different item. The sigils otherwise last indefinitely.  
  
You can use your arcane firearm as a Spellcasting Focus for your Artificer spells. When you cast an Artificer spell through the firearm, roll 1d8, and you gain a bonus to one of the spell’s damage rolls equal to the number rolled.  
  
## Level 9: Explosive Cannon  
  
Every Eldritch Cannon you create is now more destructive. You gain the following benefits:  
  
***Detonate.*** When your cannon is reduced to 0 Hit Points, you can take a [[Reaction]] to command the cannon to detonate if you are within 60 feet of it. Doing so destroys the cannon and forces each creature within 20 feet of it to make a [[Saving Throws|Dexterity saving throw]] against your spell save DC, taking 3d10 Force damage on a failed save or half as much damage on a successful one.  
  
***Firepower.*** The cannon’s damage rolls increase by 1d8.  
  
## Level 15: Fortified Position  
  
You’re a master at forming well-defended emplacements using your Eldritch Cannon. You gain the following benefits:  
  
***Double Firepower.*** You can now have two cannons at the same time. You can create two with the same [[Magic action]] (but not with the same spell slot), and you can activate both of them with the same [[Bonus Action]], ordering them to use the same activation option or different ones.
  
***Shimmering Field Projection.*** You and your allies have [[Cover|Half Cover]] while within 10 feet of your Eldritch Cannon.