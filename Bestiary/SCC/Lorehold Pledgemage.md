---
statblock: true
layout: Basic 5e Layout
name: Lorehold Pledgemage
source: SCC
size: Small or Medium
type: humanoid
subtype: wizard
alignment: any alignment
ac: 13
hp: 60
hit_dice: 11d8 + 11
speed: 30 ft.
stats:
- 10
- 16
- 13
- 17
- 12
- 11
saves:
- con: 3
- int: 5
skillsaves:
- history: 7
- insight: 3
- investigation: 7
senses: passive Perception 11
languages: Common plus any two languages
cr: '4'
traits:
- name: Spellcasting
  desc: |-
    The pledgemage casts one of the following spells, requiring no material components and using Intelligence as the spellcasting ability (spell save DC 13):
    At will: guidance, light
    2/day each: comprehend languages, locate object
    1/day each: mage armor, speak with dead, stone shape
actions:
- name: Multiattack
  desc: The pledgemage makes two Scroll Bash attacks.
- name: Scroll Bash
  desc: 'Melee Spell Attack: +5 to hit, reach 30 ft., one target. Hit: 8 (1d10 + 3) bludgeoning damage plus 9 (2d8) thunder damage.'
- name: Reduce to Memory (Recharge 5-6)
  desc: Thundering golden energy erupts around a creature the pledgemage can see within 90 feet of it. The creature must make a DC 13 Constitution saving throw, taking 44 (8d10) thunder damage on a failed save, or half as much damage on a successful one. A Construct has disadvantage on the saving throw.
bonus_actions:
- name: Chronal Break (1/Day)
  desc: The pledgemage chooses a point within 30 feet of itself, shunting the minds of nearby creatures out of this moment in time. Each creature in a 10-foot-radius sphere centered on that point must succeed on a DC 13 Wisdom saving throw or be incapacitated until the end of the pledgemage's next turn.
reactions:
- name: Learn from the Past (2/Day)
  desc: When another creature within 60 feet of the pledgemage misses a target with an attack roll, the pledgemage magically enables the attacker to reroll the attack roll. It must use the new roll.
---
