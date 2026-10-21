---
statblock: true
layout: Basic 5e Layout
name: Levistus
source: CoA
size: Medium
type: fiend
subtype: devil
alignment: lawful evil
ac: 23 (natural armor)
hp: 336
hit_dice: 32d8 + 192
speed: 0 ft.
stats:
- 19
- 26
- 22
- 25
- 28
- 26
saves:
- dex: 16
- con: 14
- int: 15
- wis: 17
skillsaves:
- acrobatics: 24
- deception: 16
- intimidation: 16
- perception: 25
- persuasion: 16
- stealth: 16
damage_resistances: bludgeoning, piercing, slashing from nonmagical attacks that aren't silvered
damage_immunities: cold, fire, poison
condition_immunities: charmed, poisoned
senses: darkvision 120 ft., passive Perception 35
languages: Celestial, Common, Draconic, Infernal, telepathy 1,000 ft.
cr: '26'
traits:
- name: Armor of Ice
  desc: Levistus is always entombed in ice. The ice provides 100 temporary hit points. While Levistus has these temporary hit points, he has vulnerability to fire damage. If Levistus starts his turn with no temporary hit points from the ice, he regains 100 temporary hit points.
- name: Devil's Sight
  desc: Magical darkness doesn't impede Levistus's darkvision.
- name: Legendary Resistance (3/Day)
  desc: If Levistus fails a saving throw, he can choose to succeed instead.
- name: Magic Resistance
  desc: Levistus has advantage on saving throws against spells and other magical effects.
- name: Sub-zero
  desc: Cold damage dealt by Levistus ignores resistances and immunities.
- name: Spellcasting
  desc: |-
    Levistus casts one of the following spells, requiring no material components and using Intelligence as the spellcasting ability (spell save DC 23):
    At will: Cone of Cold, Darkness, Ice Storm, Wall of Ice
actions:
- name: Multiattack
  desc: Levistus makes three Touch of Stygia or Ice Bolt attacks. He can replace one of the attacks with Blizzard (if available).
- name: Touch of Stygia
  desc: 'Melee Spell Attack: +15 to hit, reach 5 ft., one target. Hit: 20 (3d8 + 7) psychic damage, and the target must succeed on a DC 23 Intelligence saving throw or have the stunned condition for 1 minute. The target may repeat the saving throw at the end of its turns, ending the effect on a success. A creature that succeeds on the saving throw is immune to this effect for 1 hour.'
- name: Ice Bolt
  desc: 'Ranged Spell Attack: +15 to hit, range 120 ft., one target. Hit: 23 (3d10 + 7) cold damage.'
- name: Blizzard (Recharge 4-6)
  desc: Levistus chooses a point he can see within 300 feet of him. Each creature in a 20-foot-radius, 40-foot-high cylinder centered on that point must make a DC 23 Dexterity saving throw. Targets take 13 (3d8) force damage plus 13 (3d8) cold damage on a failed save, or half as much damage on a successful one.
reactions:
- name: Counterspell
  desc: As a reaction to a creature he can see casting a spell, Levistus can attempt to prevent the casting. Levistus makes an Intelligence check (+7) against a DC of (10 + spell level). On a success, the creature's spell fails and has no effect.
legendary_actions:
- name: Amnesia
  desc: Levistus selects a stunned creature that he can see. The creature must succeed on a DC 23 Charisma saving throw or Levistus erases a specific memory from the target. The memory must be one that the target experienced in the last 24 hours and that lasted no more than 10 minutes. The memory can only be restored with a Remove Curse or a Greater Restoration spell.
- name: Froststrike
  desc: Levistus makes an Ice Bolt attack. On a hit, the target falls and has the prone condition.
- name: Call Underling (Costs 3 Actions)
  desc: Levistus summons an allied ice devil in an unoccupied space that he can see.
legendary_description: The levistus can take 3 legendary actions, choosing from the options below. Only one legendary action option can be used at a time and only at the end of another creature's turn. The levistus regains spent legendary actions at the start of its turn.
---
