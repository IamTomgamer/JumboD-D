---
statblock: true
layout: Basic 5e Layout
name: Conjurer Wizard
source: MPMM
size: Medium
type: humanoid
alignment: any alignment
ac: 12, 15 with mage armor
hp: 58
hit_dice: 13d8
speed: 30 ft.
stats:
- 9
- 14
- 11
- 17
- 12
- 11
saves:
- int: 6
- wis: 4
skillsaves:
- arcana: 6
- history: 6
senses: passive Perception 11
languages: any four languages
cr: '6'
traits:
- name: Spellcasting
  desc: |-
    The conjurer casts one of the following spells, using Intelligence as the spellcasting ability (spell save DC 14):
    At will: dancing lights, mage hand, prestidigitation
    2/day each: fireball, mage armor, unseen servant
    1/day each: fly, stinking cloud, web
actions:
- name: Multiattack
  desc: The conjurer makes three Arcane Burst attacks.
- name: Arcane Burst
  desc: 'Melee or Ranged Spell Attack: +8 to hit, reach 5 ft. or range 120 ft., one target. Hit: 19 (3d10 + 3) force damage.'
bonus_actions:
- name: Benign Transportation (Recharge 4-6)
  desc: The conjurer teleports, along with any equipment it is wearing or carrying, up to 30 feet to an unoccupied space that it can see. If it instead chooses a space within range that is occupied by a willing Small or Medium creature, they both teleport, swapping places.
- name: Summon Elemental (1/Day)
  desc: The conjurer magically summons an air elemental, an earth elemental, a fire elemental, or a water elemental. The elemental appears in an unoccupied space within 60 feet of the conjurer, whom it obeys. It takes its turn immediately after the conjurer. It lasts for 1 hour, until it or the conjurer dies, or until the conjurer dismisses it as a bonus action.
---
