---
statblock: true
layout: Basic 5e Layout
name: Leviathan
source: MTF
size: Gargantuan
type: elemental
alignment: neutral
ac: 17
hp: 328
hit_dice: 16d20 + 160
speed: 40 ft., swim 120 ft.
stats:
- 30
- 24
- 30
- 2
- 18
- 17
saves:
- wis: 10
- cha: 9
damage_resistances: bludgeoning, piercing, slashing from nonmagical attacks
damage_immunities: acid, poison
condition_immunities: exhaustion, grappled, paralyzed, petrified, poisoned, prone, restrained, stunned
senses: darkvision 60 ft., passive Perception 14
languages: —
cr: '20'
traits:
- name: Legendary Resistance (3/Day)
  desc: If the leviathan fails a saving throw, it can choose to succeed instead.
- name: Partial Freeze
  desc: If the leviathan takes 50 cold damage or more during a single turn, the leviathan partially freezes; until the end of its next turn, its speeds are reduced to 20 feet, and it makes attack rolls with disadvantage.
- name: Siege Monster
  desc: The leviathan deals double damage to objects and structures (included in Tidal Wave).
- name: Water Form
  desc: The leviathan can enter a hostile creature's space and stop there. It can move through a space as narrow as 1 inch wide without squeezing.
actions:
- name: Multiattack
  desc: 'The leviathan makes two attacks: one with its slam and one with its tail.'
- name: Slam
  desc: 'Melee Weapon Attack: +16 to hit, reach 20 ft., one target. Hit: 15 (1d10 + 10) bludgeoning damage plus 5 (1d10) acid damage.'
- name: Tail
  desc: 'Melee Weapon Attack: +16 to hit, reach 20 ft., one target. Hit: 16 (1d12 + 10) bludgeoning damage plus 6 (1d12) acid damage.'
- name: Tidal Wave (Recharge 6)
  desc: |-
    While submerged, the leviathan magically creates a wall of water centered on itself. The wall is up 250 feet long, up to 250 feet high, and up to 50 feet thick. When the wall appears, all other creatures within its area must each make a DC 24 Strength saving throw. A creature takes 33 (6d10) bludgeoning damage on failed save, or half as much damage on a successful one.
    At the start of each of the leviathan's turns after the wall appears, the wall, along with any other creatures in it, moves 50 feet away from the leviathan. Any Huge or smaller creature inside the wall or whose space the wall enters when it moves must succeed on a DC 24 Strength saving throw or take 27 (5d10) bludgeoning damage. A creature takes this damage no more than once on a turn. At the end of each turn the wall moves, the wall's height is reduced by 50 feet, and the damage creatures take from the wall on subsequent rounds is reduced by 1d10. When the wall reaches 0 feet in height, the effect ends.
    A creature caught in the wall can move by swimming. Because of the force of the wave, though, the creature must make a successful DC 24 Strength (Athletics) check to swim at all during that turn.
legendary_actions:
- name: Slam (Costs 2 Actions)
  desc: The leviathan makes one slam attack.
- name: Move
  desc: The leviathan moves up to its speed.
legendary_description: The leviathan can take 3 legendary actions, choosing from the options below. Only one legendary action option can be used at a time and only at the end of another creature's turn. The leviathan regains spent legendary actions at the start of its turn.
---
