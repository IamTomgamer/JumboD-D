---
statblock: true
layout: Basic 5e Layout
name: Archpriest
source: XMM
size: Small or Medium
type: humanoid
subtype: cleric
alignment: neutral
ac: 16
hp: 240
hit_dice: 32d8 + 96
speed: 30 ft.
stats:
- 16
- 12
- 17
- 14
- 21
- 14
saves:
- str: 7
- con: 7
- int: 6
- wis: 9
skillsaves:
- insight: 9
- medicine: 9
- perception: 9
- religion: 10
senses: passive Perception 19
languages: Common plus two other languages
cr: '12'
traits:
- name: Spellcasting
  desc: |-
    The archpriest casts one of the following spells, requiring no Material components and using Wisdom as the spellcasting ability (spell save DC 17):
    At will: Light, Thaumaturgy
    1/day each: Flame Strike (level 6 version), Greater Restoration, Raise Dead, Zone of Truth
- name: Divine Aid (3/Day)
  desc: |-
    The priest casts Bless, Dispel Magic, Healing Word, or Lesser Restoration, using the same spellcasting ability as Spellcasting.
    3/day: Bless, Dispel Magic, Healing Word, Lesser Restoration
actions:
- name: Multiattack
  desc: The archpriest makes three Radiant Burst attacks.
- name: Radiant Burst
  desc: 'm,r +9, reach 5 ft. or range 60 ft. Hit: 27 (4d10 + 5) Radiant damage.'
- name: Holy Word (Recharge 4-6)
  desc: wis DC 17, each enemy in a 20-foot Emanation originating from the archpriest.  21 (6d6) Radiant damage, and the target has the Stunned condition until the end of the archpriest's next turn.  Half damage only.
---
