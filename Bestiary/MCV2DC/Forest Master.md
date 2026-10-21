---
statblock: true
layout: Basic 5e Layout
name: Forest Master
source: MCV2DC
size: Large
type: celestial
subtype: unicorn
alignment: neutral good
ac: 16 (natural armor)
hp: 105
hit_dice: 14d10 + 28
speed: 50 ft.
stats:
- 18
- 14
- 15
- 13
- 19
- 17
saves:
- int: 4
- wis: 7
skillsaves:
- insight: 7
- nature: 4
- perception: 7
damage_immunities: poison
condition_immunities: charmed, paralyzed, poisoned
senses: darkvision 60 ft., passive Perception 17
languages: Celestial, Elvish, Sylvan, telepathy 60 ft.
cr: '8'
traits:
- name: Legendary Resistance (2/Day)
  desc: If the Forest Master fails a saving throw, he can choose to succeed instead.
- name: Magic Resistance
  desc: The Forest Master has advantage on saving throws against spells and other magical effects.
- name: Master of Beasts
  desc: The Forest Master can comprehend and communicate with any Beast, even if the Beast knows no languages.
- name: Spellcasting
  desc: |-
    The Forest Master casts one of the following spells, requiring no material components and using Wisdom as the spellcasting ability (spell save DC 15):
    At will: druidcraft, fog cloud, guidance
    2/day each: goodberry, greater restoration, pass without trace, speak with plants
actions:
- name: Multiattack
  desc: The Forest Master makes either two Hooves attacks, two Moon Bolt attacks, or one of each.
- name: Hooves
  desc: 'Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 11 (2d6 + 4) bludgeoning damage.'
- name: Moon Bolt
  desc: 'Ranged Spell Attack: +7 to hit, range 60 ft., one target. Hit: 11 (2d6 + 4) radiant damage.'
bonus_actions:
- name: Erupting Briars (Recharge 4-6)
  desc: |-
    The Forest Master touches his horn to the earth and causes a 5-foot-tall wall of briars to erupt in a 90-foot line that is 10 feet wide. When the wall appears, each creature in its area is pushed into the nearest unoccupied space adjacent to the wall and must make a DC 15 Dexterity saving throw, taking 27 (6d8) piercing damage on a failed save or half as much damage on a successful one.
    The wall of briars lasts until the start of the Forest Master's next turn. The wall blocks line of sight and counts as difficult terrain for all creatures except the Forest Master. The first time a creature enters the wall's area on a turn, that creature must succeed on a DC 15 Dexterity saving throw or take 13 (3d8) piercing damage.
reactions:
- name: Misty Escape
  desc: If the Forest Master takes damage from a melee attack, he, along with any equipment he is wearing or carrying, teleports to an unoccupied space within 30 feet that he can see.
---
