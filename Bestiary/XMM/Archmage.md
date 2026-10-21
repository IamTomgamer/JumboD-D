---
statblock: true
layout: Basic 5e Layout
name: Archmage
source: XMM
size: Small or Medium
type: humanoid
subtype: wizard
alignment: neutral
ac: 17
hp: 170
hit_dice: 31d8 + 31
speed: 30 ft.
stats:
- 10
- 14
- 12
- 20
- 15
- 16
saves:
- int: 9
- wis: 6
skillsaves:
- arcana: 13
- history: 9
- perception: 6
damage_immunities: psychic
condition_immunities: charmed (with Mind Blank)
senses: passive Perception 16
languages: Common plus five other languages
cr: '12'
traits:
- name: Magic Resistance
  desc: The archmage has Advantage on saving throws against spells and other magical effects.
- name: Spellcasting
  desc: |-
    The archmage casts one of the following spells, using Intelligence as the spellcasting ability (spell save DC 17):
    At will: Detect Magic, Detect Thoughts, Disguise Self, Invisibility, Light, Mage Armor (included in AC), Mage Hand, Prestidigitation
    2/day each: Fly, Lightning Bolt (level 7 version)
    1/day each: Cone of Cold (level 9 version), Mind Blank (cast before combat), Scrying, Teleport
- name: Misty Step (3/Day)
  desc: |-
    The mage casts Misty Step, using the same spellcasting ability as Spellcasting.
    3/day: Misty Step
- name: Protective Magic (3/Day)
  desc: |-
    The archmage casts Counterspell or Shield in response to the spell's trigger, using the same spellcasting ability as Spellcasting.
    3/day: Counterspell, Shield
actions:
- name: Multiattack
  desc: The archmage makes four Arcane Burst attacks.
- name: Arcane Burst
  desc: 'm,r +9, reach 5 ft. or range 150 ft. Hit: 27 (4d10 + 5) Force damage.'
---
