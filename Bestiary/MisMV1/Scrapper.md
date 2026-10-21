---
statblock: true
layout: Basic 5e Layout
name: Scrapper
source: MisMV1
size: Large
type: construct
alignment: unaligned
ac: 18 (natural armor)
hp: 126
hit_dice: 12d10 + 60
speed: 30 ft.
stats:
- 20
- 10
- 20
- 3
- 10
- 1
skillsaves:
- perception: 6
damage_resistances: lightning
damage_immunities: poison, psychic
condition_immunities: charmed, exhaustion, frightened, paralyzed, petrified, poisoned
senses: darkvision 120 ft., passive Perception 16
languages: understands the languages of its creator but can't speak
cr: '8'
traits:
- name: Electrified Chassis
  desc: A creature that hits the scrapper with a melee attack while within 5 feet of it takes 19 (3d12) lightning damage.
actions:
- name: Multiattack
  desc: The scrapper makes two Spike Punch attacks. It can replace one of those with a Wires attack.
- name: Spike Punch
  desc: 'Melee Weapon Attack: +8 to hit, reach 5 ft., one target. Hit: 14 (2d8 + 5) bludgeoning damage plus 5 (1d10) piercing damage.'
- name: Wires
  desc: 'Melee Weapon Attack: +8 to hit, reach 20 ft., one Large or smaller creature. Hit: The target has the grappled condition (escape DC 16) and must succeed on a DC 16 Strength saving throw or be pulled into an unoccupied space within 5 feet of the scrapper and take 19 (3d12) lightning damage. The scrapper can have only one creature grappled in this way at a time.'
- name: Eye Beam (Recharge 5-6)
  desc: The scrapper shoots a magical beam from its extended eye at one creature it can see within 120 feet of itself. The target must make a DC 16 Dexterity saving throw, taking 44 (8d10) force damage on a failed save, or half as much damage on a successful one.
---
