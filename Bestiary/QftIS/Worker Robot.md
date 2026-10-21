---
statblock: true
layout: Basic 5e Layout
name: Worker Robot
source: QftIS
size: Medium
type: construct
alignment: typically neutral
ac: 13 (natural armor)
hp: 75
hit_dice: 10d8 + 30
speed: 30 ft., climb 30 ft.
stats:
- 20
- 9
- 16
- 10
- 12
- 10
skillsaves:
- athletics: 9
damage_resistances: acid, fire
damage_immunities: cold, poison
condition_immunities: exhaustion, poisoned
senses: darkvision 60 ft., passive Perception 11
languages: Common plus the languages spoken by its creator
cr: '3'
traits:
- name: Lightning Overload
  desc: When the robot takes lightning damage, it must succeed on a DC 10 Constitution saving throw or have the stunned condition until the start of its next turn.
actions:
- name: Multiattack
  desc: The robot makes two Cargo Tentacle attacks.
- name: Cargo Tentacle
  desc: 'Melee Weapon Attack: +7 to hit, reach 10 ft., one target. Hit: 9 (1d8 + 5) bludgeoning damage. If the target is a Medium or smaller creature, it has the grappled condition (escape DC 15). The robot has two cargo tentacles, each of which can grapple one target.'
- name: Tractor Beam
  desc: The robot casts Telekinesis, targeting only creatures with the incapacitated condition or objects. It requires no spell components and uses Wisdom as the spellcasting ability.
---
