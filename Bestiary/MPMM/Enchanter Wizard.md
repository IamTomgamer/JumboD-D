---
statblock: true
layout: Basic 5e Layout
name: Enchanter Wizard
source: MPMM
size: Medium
type: humanoid
alignment: any alignment
ac: 12, 15 with mage armor
hp: 49
hit_dice: 11d8
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
cr: '5'
traits:
- name: Spellcasting
  desc: |-
    The enchanter casts one of the following spells, using Intelligence as the spellcasting ability (spell save DC 14):
    At will: friends, mage hand, message
    2/day each: charm person, mage armor, hold person, invisibility, suggestion, tongues
actions:
- name: Multiattack
  desc: The enchanter makes three Arcane Burst attacks.
- name: Arcane Burst
  desc: 'Melee or Ranged Spell Attack: +6 to hit, reach 5 ft. or range 120 ft., one target. Hit: 19 (3d10 + 3) psychic damage.'
reactions:
- name: Instinctive Charm (Recharge 4-6)
  desc: When a visible creature within 30 feet of the enchanter makes an attack roll against it, the enchanter forces the attacker to make a DC 14 Wisdom saving throw. On a failed save, the attacker redirects the attack roll to the creature closest to it, other than the enchanter or itself. If multiple eligible creatures are closest, the attacker chooses which one to target.
---
