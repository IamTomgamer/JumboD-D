---
statblock: true
layout: Basic 5e Layout
name: Monastic Infiltrator
source: CRCotN
size: Small or Medium
type: humanoid
subtype: monk
alignment: any alignment
ac: 18 (Unarmored Defense)
hp: 112
hit_dice: 15d8 + 45
speed: 50 ft.
stats:
- 13
- 20
- 16
- 15
- 17
- 16
saves:
- dex: 8
- wis: 6
skillsaves:
- acrobatics: 8
- deception: 9
- perception: 6
- stealth: 11
damage_resistances: psychic
condition_immunities: charmed
senses: passive Perception 16
languages: Common plus three other languages
cr: '6'
traits:
- name: Guarded Mind
  desc: Spells and other effects can't read the infiltrator's thoughts or determine if the infiltrator is lying. Creatures can communicate telepathically with the infiltrator only if it allows such contact.
- name: Unarmored Defense
  desc: While the infiltrator is wearing no armor and wielding no shield, its AC includes its Wisdom modifier.
- name: Spellcasting
  desc: |-
    The infiltrator casts one of the following spells, requiring no material components and using Wisdom as the spellcasting ability (spell save DC 14):
    At will: disguise self
    2/day each: detect thoughts, invisibility
    1/day each: dimension door, zone of truth
actions:
- name: Multiattack
  desc: The infiltrator makes three Unarmed Strike attacks.
- name: Unarmed Strike
  desc: 'Melee Weapon Attack: +8 to hit, reach 5 ft., one target. Hit: 10 (1d10 + 5) force damage.'
bonus_actions:
- name: Cunning Action
  desc: The infiltrator takes the Dash or Disengage action.
reactions:
- name: Retaliating Strike
  desc: When a creature within 5 feet of the infiltrator hits or misses the infiltrator with a melee attack, the infiltrator makes one Unarmed Strike attack against the attacker.
---
