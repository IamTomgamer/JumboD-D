---
statblock: true
layout: Basic 5e Layout
name: Quandrix Professor of Substance
source: SCC
size: Small or Medium
type: humanoid
subtype: wizard
alignment: any alignment
ac: 12
hp: 104
hit_dice: 16d8 + 32
speed: 30 ft.
stats:
- 11
- 14
- 14
- 19
- 14
- 13
saves:
- con: 5
- int: 7
- wis: 5
- cha: 4
skillsaves:
- arcana: 10
- investigation: 10
- nature: 7
- perception: 5
damage_resistances: force
senses: passive Perception 15
languages: Common plus any four languages
cr: '7'
traits:
- name: Spellcasting
  desc: |-
    The professor casts one of the following spells, requiring no material components and using Intelligence as the spellcasting ability (spell save DC 15):
    At will: guidance, mage hand, mending (as an action)
    1/day each: creation (as an action), dimension door, mage armor, plant growth, polymorph
actions:
- name: Multiattack
  desc: The professor makes two Spatial Blade attacks.
- name: Spatial Blade
  desc: 'Melee or Ranged Spell Attack: +7 to hit (the target can''t benefit from cover less than 3), reach 5 ft. or range 120 ft., one target. Hit: 13 (2d8 + 4) force damage, or 22 (4d8 + 4) force damage if the professor is Large or larger, and the professor can push the target horizontally up to 10 feet away.'
bonus_actions:
- name: Dilation (Recharge 5-6)
  desc: 'The professor magically alters its physical form until it uses this bonus action again, until it is incapacitated or dies, or until it dismisses the effect (no action required). Choose one of the following options:'
- name: Expand
  desc: The professor becomes Large if there is sufficient room for it to grow. It has advantage on attack rolls and on ability checks and saving throws that rely on Strength.
- name: Contract
  desc: The professor becomes Small. Its walking speed increases to 60 feet, attack rolls against it have disadvantage, and it has advantage on ability checks and saving throws that rely on Dexterity.
reactions:
- name: Avoidant Translation (2/Day)
  desc: When the professor is hit by an attack roll, it can increase its AC by 3 against that attack, potentially causing it to miss. The professor can then teleport, along with any equipment it is wearing or carrying, up to 30 feet to an unoccupied space it can see.
---
