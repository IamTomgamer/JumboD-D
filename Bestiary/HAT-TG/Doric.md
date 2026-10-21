---
statblock: true
layout: Basic 5e Layout
name: Doric
source: HAT-TG
size: Medium
type: humanoid
subtype: druid
alignment: neutral good
ac: 14 (leather armor)
hp: 104
hit_dice: 16d8 + 32
speed: 30 ft.
stats:
- 12
- 16
- 14
- 16
- 19
- 10
saves:
- int: 6
- wis: 7
skillsaves:
- insight: 7
- nature: 6
- perception: 7
- survival: 7
damage_resistances: fire
senses: darkvision 60 ft., passive Perception 17
languages: Common, Druidic, Elvish, Infernal, Sylvan
cr: '5'
traits:
- name: Spellcasting
  desc: |-
    Doric casts one of the following spells, using Wisdom as the spellcasting ability (spell save DC 15):
    At will: animal messenger, beast sense, speak with animals
    2/day each: cure wounds, entangle, faerie fire, thunderwave
actions:
- name: Multiattack
  desc: Doric makes two Shaped Claw or Sling attacks. She can replace one attack with a use of Spellcasting.
- name: Shaped Claw
  desc: 'Melee Spell Attack: +7 to hit, reach 5 ft., one target. Hit: 8 (1d8 + 4) slashing damage.'
- name: Sling
  desc: 'Ranged Weapon Attack: +6 to hit, range 30/120 ft., one target. Hit: 8 (2d4 + 3) bludgeoning damage.'
bonus_actions:
- name: Change Shape (5/Day)
  desc: |-
    Doric magically transforms into a Beast with a challenge rating of 3 or less or into an owlbear (see the Monster Manual).
    Doric can remain in that form for up to 2 hours. She can choose whether her equipment falls to the ground, melds with her new form, or is worn by the new form. Doric reverts to her true form if she is incapacitated or dies. She can revert to her true form using a bonus action.
    While Doric is transformed, her stat block is replaced by the stat block of that form, except she keeps her current hit points, her hit point maximum, this bonus action, her alignment, and her Intelligence, Wisdom, and Charisma scores.
reactions:
- name: Fiery Rebuke (3/Day)
  desc: When Doric is damaged by a creature that she can see within 60 feet of herself, she magically engulfs the creature in flames. The creature must make a DC 15 Dexterity saving throw, taking 16 (3d10) fire damage on failed save, or half as much damage on a successful one.
---
