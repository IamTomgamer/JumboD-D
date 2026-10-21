---
statblock: true
layout: Basic 5e Layout
name: Drowned Master
source: GoS
size: Medium
type: undead
alignment: chaotic evil
ac: 14 (natural armor)
hp: 157
hit_dice: 21d8 + 63
speed: 30 ft.
stats:
- 17
- 12
- 16
- 9
- 14
- 12
saves:
- con: 7
- wis: 6
skillsaves:
- perception: 10
damage_immunities: poison
condition_immunities: poisoned
senses: darkvision 60 ft., passive Perception 20
languages: understands the languages it knew in life but can't speak
cr: '9'
traits:
- name: Bound Together
  desc: The drowned master shares its mind with every other drowned one within 1 mile of it, and can communicate its thoughts and observations to them instantaneously and without limitation.
- name: Cold Aura
  desc: At the start of each of the drowned master's turns, each creature within 5 feet of it takes 5 (1d10) cold damage. A creature that touches the drowned master or hits it with a melee attack while within 5 feet of it takes 5 (1d10) cold damage.
- name: Undead Fortitude
  desc: If damage reduces the drowned master to 0 hit points, it must make a Constitution saving throw with a DC of 5 + the damage taken, unless the damage is radiant or from a critical hit. On a success, the drowned master drops to 1 hit point instead.
actions:
- name: Multiattack
  desc: 'The drowned master makes two attacks: one with its greatsword and one with its Life-Draining Tentacle.'
- name: Greatsword
  desc: 'Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 10 (2d6 + 3) slashing damage plus 14 (4d6) cold damage, and the target must succeed on a DC 12 Constitution saving throw or contract bluerot (see the "Bluerot" in notes).'
- name: Life-Draining Tentacle
  desc: 'Melee Weapon Attack: +7 to hit, reach 15 ft., one target. Hit: 10 (2d6 + 3) necrotic damage. The target must succeed on a DC 15 Constitution saving throw or have its hit point maximum reduced by an amount equal to the damage taken. The target dies if this effect reduces its hit point maximum to 0. This reduction lasts until the target finishes a long rest. On a failed save, the target also contracts bluerot (see the "Bluerot" in notes).'
- name: Necrotic Ink (Recharge 5-6)
  desc: The drowned master discharges foul ink in front of itself in a 30-foot cone. Each creature caught in the ink must make a DC 15 Constitution saving throw, taking 27 (6d8) necrotic damage on a failed save or half as much damage on a successful one. A creature that fails this saving throw is blinded until the end of its next turn and contracts bluerot (see the "Bluerot" in notes).
---
