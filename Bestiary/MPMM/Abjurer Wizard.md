---
statblock: true
layout: Basic 5e Layout
name: Abjurer Wizard
source: MPMM
size: Medium
type: humanoid
alignment: any alignment
ac: 12, 15 with mage armor
hp: 104
hit_dice: 16d8 + 32
speed: 30 ft.
stats:
- 9
- 14
- 14
- 18
- 12
- 11
saves:
- int: 8
- wis: 5
skillsaves:
- arcana: 8
- history: 8
senses: passive Perception 11
languages: any four languages
cr: '9'
traits:
- name: Spellcasting
  desc: |-
    The abjurer casts one of the following spells, using Intelligence as the spellcasting ability (spell save DC 16):
    At will: dancing lights, mage hand, message, prestidigitation
    2/day each: dispel magic, lightning bolt, mage armor
    1/day each: arcane lock, banishment, globe of invulnerability, invisibility, wall of force
actions:
- name: Multiattack
  desc: The abjurer makes three Arcane Burst attacks.
- name: Arcane Burst
  desc: 'Melee or Ranged Spell Attack: +8 to hit, reach 5 ft. or range 120 ft., one target. Hit: 20 (3d10 + 4) force damage.'
- name: Force Blast
  desc: Each creature in a 20-foot cube originating from the abjurer must make a DC 16 Constitution saving throw. On a failed save, a creature takes 36 (8d8) force damage and is pushed up to 10 feet away from the abjurer. On a successful save, a creature takes half as much damage and isn't pushed.
reactions:
- name: Arcane Ward (Recharge 4-6)
  desc: When the abjurer or a creature it can see within 30 feet of it takes damage, the abjurer magically creates a protective barrier around itself or the other creature. The barrier reduces the damage to the protected creature by 26 (4d10 + 4), to a minimum of 0, and then vanishes.
---
