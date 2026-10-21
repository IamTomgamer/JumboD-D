---
statblock: true
layout: Basic 5e Layout
name: Aurak Draconian
source: DSotDQ
size: Medium
type: monstrosity
subtype: sorcerer
alignment: typically lawful evil
ac: 17 (natural armor)
hp: 67
hit_dice: 9d8 + 27
speed: 35 ft.
stats:
- 13
- 14
- 16
- 16
- 11
- 17
saves:
- int: 6
- wis: 3
- cha: 6
skillsaves:
- perception: 3
condition_immunities: charmed
senses: truesight 60 ft., passive Perception 13
languages: Common, Draconic
cr: '6'
traits:
- name: Aura of Command
  desc: The draconian radiates a commanding presence in a 20-foot-radius sphere centered on itself. A draconian in the aura that can see or hear the aurak can't be charmed and has advantage on saving throws made to avoid or end the frightened condition on itself.
- name: Death Throes
  desc: When the draconian is reduced to 0 hit points, its magical essence lashes out as a ball of lightning at the closest creature within 30 feet of it before arcing out to up to two other creatures within 15 feet of the first. Each creature must make a DC 14 Dexterity saving throw. On a failed save, the creature takes 9 (2d8) lightning damage and is stunned until the end of its next turn. On a successful save, the creature takes half as much damage and isn't stunned.
- name: Spellcasting
  desc: |-
    The draconian casts one of the following spells, requiring no material components and using Charisma as the spellcasting ability (spell save DC 14):
    At will: invisibility, mage hand
    1/day: dominate person
    2/day each: dimension door, disguise self, sending
actions:
- name: Multiattack
  desc: The draconian makes three Rend or Energy Ray attacks.
- name: Rend
  desc: 'Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 8 (1d12 + 2) slashing damage.'
- name: Energy Ray
  desc: 'Ranged Spell Attack: +6 to hit, range 60 ft., one target. Hit: 8 (1d10 + 3) force damage.'
- name: Noxious Breath (Recharge 5-6)
  desc: The draconian exhales a 15-foot cone of noxious gas. Each creature in that area must make a DC 14 Constitution saving throw. On a failed save, the creature takes 21 (6d6) poison damage and gains 1 level of exhaustion. On a successful save, the creature takes half as much damage, doesn't gain exhaustion, and is immune to all draconians' Noxious Breath for 24 hours.
---
