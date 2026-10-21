---
statblock: true
layout: Basic 5e Layout
name: Mordenheim's Monster
source: RHW
size: Medium
type: construct
alignment: neutral
ac: 18
hp: 161
hit_dice: 19d8 + 76
speed: 40 ft.
stats:
- 22
- 16
- 19
- 14
- 10
- 5
saves:
- str: 10
- dex: 7
skillsaves:
- acrobatics: 7
- athletics: 14
damage_resistances: bludgeoning, piercing, slashing
damage_immunities: lightning, poison
condition_immunities: charmed, exhaustion, frightened, paralyzed, petrified, poisoned
senses: Darkvision 60 ft., passive Perception 10
languages: Common plus one other language
cr: '12'
traits:
- name: Greater Lightning Absorption
  desc: Whenever the monster is subjected to Lightning damage, it regains a number of Hit Points equal to the Lightning damage dealt, and its Speed increases by 40 feet until the end of its next turn.
- name: Immutable Form
  desc: The monster can't shape-shift.
- name: Magic Resistance
  desc: The monster has Advantage on saving throws against spells and other magical effects.
actions:
- name: Multiattack
  desc: The monster makes two Slam attacks and uses Crush or Throw.
- name: Slam
  desc: 'm +10, reach 5 ft. Hit: 13 (2d6 + 6) Bludgeoning damage plus 7 (2d6) Lightning damage. If the target is a Medium or smaller creature, it has the Grappled condition (escape DC 18) from one of two hands.'
- name: Crush
  desc: str DC 18, one creature Grappled by the monster.  13 (2d6 + 6) Bludgeoning damage plus 7 (2d6) Lightning damage, and the target has the Restrained condition. While Restrained, the target is suffocating.
- name: Throw
  desc: The monster throws a creature Grappled by it to a space it can see within 30 feet of itself that isn't in the air. dex DC 18, the creature thrown and each creature in the destination space.  13 (2d6 + 6) Bludgeoning damage, and the target has the Prone condition.  Half damage only.
bonus_actions:
- name: Violent Leap
  desc: The monster spends 10 feet of movement to jump to a space within 40 feet that contains one or more Medium or smaller creatures. dex DC 18, each creature in the monster's destination space.  14 (4d6) Bludgeoning damage, and the target has the Prone condition.  The target moves to the nearest unoccupied space.
---
