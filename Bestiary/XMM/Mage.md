---
statblock: true
layout: Basic 5e Layout
name: Mage
source: XMM
size: Small or Medium
type: humanoid
subtype: wizard
alignment: neutral
ac: 15
hp: 81
hit_dice: 18d8
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
- perception: 4
senses: passive Perception 14
languages: Common plus three other languages
cr: '6'
traits:
- name: Spellcasting
  desc: |-
    The mage casts one of the following spells, using Intelligence as the spellcasting ability (spell save DC 14):
    At will: Detect Magic, Light, Mage Armor (included in AC), Mage Hand, Prestidigitation
    2/day each: Fireball (level 4 version), Invisibility
    1/day each: Cone of Cold, Fly
- name: Misty Step (3/Day)
  desc: |-
    The mage casts Misty Step, using the same spellcasting ability as Spellcasting.
    3/day: Misty Step
- name: Protective Magic (3/Day)
  desc: |-
    The mage casts Counterspell or Shield in response to the spell's trigger, using the same spellcasting ability as Spellcasting.
    3/day: Counterspell, Shield
actions:
- name: Multiattack
  desc: The mage makes three Arcane Burst attacks.
- name: Arcane Burst
  desc: 'm,r +6, reach 5 ft. or range 120 ft. Hit: 16 (3d8 + 3) Force damage.'
---
