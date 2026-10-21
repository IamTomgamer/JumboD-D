---
statblock: true
layout: Basic 5e Layout
name: Githzerai Enlightened
source: MPMM
size: Medium
type: humanoid
subtype: gith
alignment: any alignment
ac: 18 (psychic defense)
hp: 112
hit_dice: 15d8 + 45
speed: 40 ft.
stats:
- 14
- 19
- 16
- 17
- 19
- 13
saves:
- str: 6
- dex: 8
- int: 7
- wis: 8
skillsaves:
- arcana: 7
- insight: 8
- perception: 8
senses: passive Perception 18
languages: Gith
cr: '10'
traits:
- name: Psychic Defense
  desc: While the githzerai is wearing no armor and wielding no shield, its AC includes its Wisdom modifier.
- name: Spellcasting (Psionics)
  desc: |-
    The githzerai casts one of the following spells, requiring no spell components and using Wisdom as the spellcasting ability (spell save DC 16):
    At will: mage hand (the hand is invisible)
    3/day: see invisibility
    1/day each: plane shift, teleport
actions:
- name: Multiattack
  desc: The githzerai makes three Unarmed Strike attacks.
- name: Unarmed Strike
  desc: 'Melee Weapon Attack: +8 to hit, reach 5 ft., one target. Hit: 13 (2d8 + 4) bludgeoning damage plus 18 (4d8) psychic damage.'
- name: Temporal Strike (Recharge 6)
  desc: 'Melee Weapon Attack: +8 to hit, reach 5 ft., one creature. Hit: 13 (2d8 + 4) bludgeoning damage plus 52 (8d12) psychic damage. The target must succeed on a DC 16 Wisdom saving throw or move 1 round forward in time. A target moved forward in time vanishes for the duration. When the effect ends, the target reappears in the space it left or in an unoccupied space nearest to that space if it''s occupied.'
reactions:
- name: Slow Fall
  desc: When the githzerai falls, it reduces any falling damage it takes by 50.
---
