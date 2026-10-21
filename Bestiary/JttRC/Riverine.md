---
statblock: true
layout: Basic 5e Layout
name: Riverine
source: JttRC
size: Large
type: fey
alignment: any alignment
ac: 14
hp: 204
hit_dice: 24d10 + 72
speed: 30 ft., swim 60 ft.
stats:
- 20
- 19
- 17
- 12
- 16
- 21
saves:
- int: 5
- wis: 7
- cha: 9
skillsaves:
- insight: 7
- nature: 5
- perception: 7
damage_resistances: acid, fire
senses: blindsight 60 ft., passive Perception 17
languages: Aquan, Common, Sylvan
cr: '12'
traits:
- name: Amphibious
  desc: The riverine can breathe air and water.
- name: Legendary Resistance (3/Day)
  desc: If the riverine fails a saving throw, it can choose to succeed instead.
- name: Spellcasting
  desc: |-
    The riverine casts one of the following spells, requiring no material components and using Charisma as the spellcasting ability (spell save DC 17):
    At will: control water, fog cloud
    1/day: greater restoration
actions:
- name: Multiattack
  desc: The riverine makes two Flood Strike attacks.
- name: Flood Strike
  desc: 'Melee Weapon Attack: +9 to hit, reach 10 ft., one target. Hit: 14 (2d8 + 5) bludgeoning damage plus 10 (3d6) cold damage.'
bonus_actions:
- name: Whirlpool Step
  desc: The riverine magically teleports to an unoccupied space it can see within 30 feet of itself. Both the space it leaves and its destination must be in or on the surface of water.
legendary_actions:
- name: Whirlpool Rush
  desc: The riverine uses its Whirlpool Step. Immediately after it teleports, each creature within 5 feet of the riverine's destination space takes 5 (1d10) cold damage.
- name: Raging Deluge (Costs 2 Actions)
  desc: The riverine unleashes a torrent of river water in a 30-foot line that is 5 feet wide. Each creature in that area must make a DC 17 Dexterity saving throw. On a failed save, a creature takes 11 (2d10) bludgeoning damage and is knocked prone. On a successful save, a creature takes half as much damage and isn't knocked prone.
legendary_description: The riverine can take 3 legendary actions, choosing from the options below. Only one legendary action option can be used at a time and only at the end of another creature's turn. The riverine regains spent legendary actions at the start of its turn.
---
