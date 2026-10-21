---
statblock: true
layout: Basic 5e Layout
name: Soul Shaker
source: JttRC
size: Large
type: undead
alignment: typically chaotic evil
ac: 13 (natural armor)
hp: 76
hit_dice: 8d10 + 32
speed: 20 ft.
stats:
- 20
- 8
- 18
- 8
- 11
- 14
damage_resistances: necrotic
damage_immunities: poison
condition_immunities: charmed, exhaustion, frightened, grappled, paralyzed, petrified, poisoned, prone, restrained
senses: blindsight 60 ft. (blind beyond this radius), passive Perception 10
languages: telepathy 60 ft.
cr: '4'
traits:
- name: Enthralled Lure (1/Day)
  desc: The soul shaker can cast the geas spell, requiring no spell components and using Charisma as the spellcasting ability (spell save DC 12).
- name: Reconstruction
  desc: When the soul shaker is reduced to 0 hit points, it explodes into 7 (1d4 + 5) crawling claws. After 6 (1d12) days, if at least two of those crawling claws are alive, they teleport to the location of the soul shaker's death and merge together, whereupon the soul shaker reforms and regains all its hit points.
- name: Unusual Nature
  desc: The soul shaker doesn't require air, food, drink, or sleep.
actions:
- name: Crushing Grasp
  desc: 'Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 14 (2d8 + 5) bludgeoning damage. If the target is a Medium or smaller creature, it is grappled (escape DC 15). The soul shaker can have only one creature grappled in this way at a time.'
bonus_actions:
- name: Consume Vitality
  desc: The soul shaker targets a creature it is grappling. If the target is not a Construct or an Undead, the target must succeed on a DC 14 Constitution saving throw or take 7 (2d6) necrotic damage. The target's hit point maximum is reduced by an amount equal to the necrotic damage taken, and the soul shaker regains hit points equal to that amount. This reduction lasts until the target finishes a long rest. The target dies if its hit point maximum is reduced to 0.
---
