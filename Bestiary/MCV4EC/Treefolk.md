---
statblock: true
layout: Basic 5e Layout
name: Treefolk
source: MCV4EC
size: Large
type: plant
subtype: druid
alignment: any alignment
ac: 17 (natural armor)
hp: 171
hit_dice: 18d10 + 72
speed: 30 ft.
stats:
- 23
- 12
- 18
- 10
- 20
- 11
saves:
- con: 8
- int: 4
- wis: 9
skillsaves:
- insight: 9
- nature: 8
- perception: 9
damage_vulnerabilities: fire
damage_resistances: bludgeoning, piercing
senses: blindsight 30 ft., passive Perception 19
languages: Common, Druidic, Sylvan
cr: '11'
traits:
- name: Plant Camouflage
  desc: The treefolk has advantage on Dexterity (Stealth) checks it makes in forest terrain.
- name: Tree Stride
  desc: Once on each of its turns, the treefolk can use 10 feet of its movement to step magically into one living tree within 5 feet of itself and emerge from a second living tree within 60 feet of itself that it can see, appearing in an unoccupied space within 5 feet of the second tree. Both trees must be at least as large as the treefolk.
- name: Spellcasting
  desc: |-
    The treefolk casts one of the following spells, requiring no material components and using Wisdom as the spellcasting ability (spell save DC 17):
    At will: detect poison and disease, druidcraft
    1/day: commune with nature (as an action)
    2/day each: enlarge/reduce, speak with plants
actions:
- name: Multiattack
  desc: The treefolk makes two Crushing Vine attacks, two Nightshade Bolt attacks, or one of each.
- name: Crushing Vine
  desc: 'Melee Weapon Attack: +10 to hit, reach 10 ft., one target. Hit: 25 (3d12 + 6) bludgeoning damage. If the target is a creature, it has the grappled condition (escape DC 18). While grappled, the creature also has the restrained condition. The treefolk can grapple up to six creatures this way.'
- name: Nightshade Bolt
  desc: 'Ranged Spell Attack: +9 to hit, range 60 ft., one target. Hit: 33 (6d10) poison damage.'
bonus_actions:
- name: Oaken Boon
  desc: The treefolk blesses one creature other than itself that it can see within 60 feet of itself with the might and wisdom of the forest. While blessed in this way, a creature can use the treefolk's Tree Stride trait and gains 5 (2d4) temporary hit points at the start of each of its turns. This blessing lasts for 1 minute, until the treefolk has the incapacitated condition, or until the treefolk uses this bonus action again.
---
