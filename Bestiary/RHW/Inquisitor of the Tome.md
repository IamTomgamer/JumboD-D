---
statblock: true
layout: Basic 5e Layout
name: Inquisitor of the Tome
source: RHW
size: Small or Medium
type: humanoid
alignment: lawful neutral
ac: 14
hp: 88
hit_dice: 16d8 + 16
speed: 30 ft.
stats:
- 10
- 12
- 12
- 19
- 16
- 15
saves:
- int: 7
- wis: 6
- cha: 5
skillsaves:
- arcana: 10
- history: 7
- nature: 7
- religion: 10
condition_immunities: charmed, frightened
senses: Truesight 30 ft., passive Perception 13
languages: Common plus two other languages
cr: '8'
traits:
- name: Spellcasting
  desc: |-
    The inquisitor casts one of the following spells, requiring no spell components and using Intelligence as the spellcasting ability (spell save DC 15):
    At will: Detect Magic, Dispel Magic, Mage Armor (included in AC), Mage Hand (the hand is Invisible), Sending
    1/day each: Otiluke's Resilient Sphere, Telekinesis
actions:
- name: Multiattack
  desc: The inquisitor makes three Force Blade attacks. It can replace one attack with a use of Spellcasting to cast Otiluke's Resilient Sphere or Telekinesis if available.
- name: Force Blade
  desc: 'm,r +7, reach 5 ft. or range 120 ft. Hit: 22 (4d8 + 4) Force damage. If the target is a Large or smaller creature, it is pushed up to 10 feet straight away from the inquisitor.'
bonus_actions:
- name: Implode (Recharge 4-6)
  desc: dex DC 15, each creature in a 20-foot-radius Sphere centered on a point the inquisitor can see within 120 feet.  27 (6d8) Force damage, and the target has the Prone condition and is pulled up to 20 feet straight toward the Sphere's center.  Half damage only.
---
