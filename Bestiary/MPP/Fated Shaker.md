---
statblock: true
layout: Basic 5e Layout
name: Fated Shaker
source: MPP
size: Small or Medium
type: humanoid
alignment: any alignment
ac: 13, 16 with mage armor
hp: 76
hit_dice: 17d8
speed: 30 ft.
stats:
- 10
- 16
- 10
- 15
- 16
- 15
saves:
- int: 5
- wis: 6
skillsaves:
- insight: 6
- investigation: 5
- perception: 6
senses: passive Perception 16
languages: Common plus two more languages
cr: '5'
traits:
- name: Spellcasting
  desc: |-
    The shaker casts one of the following spells, requiring no material components and using Wisdom as the spellcasting ability (spell save DC 14):
    At will: mage armor, mage hand
    1/day each: enlarge/reduce, fly, suggestion
actions:
- name: Multiattack
  desc: The shaker makes two Golden Rod or Radiant Bolt attacks.
- name: Golden Rod
  desc: 'Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 6 (1d6 + 3) bludgeoning damage plus 9 (2d8) radiant damage.'
- name: Radiant Bolt
  desc: 'Ranged Spell Attack: +6 to hit, range 120 ft., one target. Hit: 14 (2d10 + 3) radiant damage.'
bonus_actions:
- name: Commanding Words
  desc: |-
    The shaker speaks magical words to order a creature it can see within 30 feet of itself. The target must succeed on a DC 14 Wisdom saving throw or be affected by one of the following effects (choose one or roll a d4):
    - **1-2: Grovel** The target takes 14 (4d6) psychic damage, drops whatever it is holding, and has the prone condition.
    - **3-4: Cower** The target takes 10 (3d6) psychic damage and has the frightened condition until the end of its next turn.
---
