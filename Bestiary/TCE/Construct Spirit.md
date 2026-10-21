---
statblock: true
layout: Basic 5e Layout
name: Construct Spirit
source: TCE
size: Medium
type: construct
alignment: unaligned
ac: 13 + the level of the spell (natural armor)
hp: 40 + 15 for each spell level above 4th
speed: 30 ft.
stats:
- 18
- 10
- 18
- 14
- 11
- 5
damage_resistances: poison
condition_immunities: charmed, exhaustion, frightened, incapacitated, paralyzed, petrified, poisoned
senses: darkvision 60 ft., passive Perception 10
languages: understands the languages you speak
cr: ''
traits:
- name: Heated Body (Metal Only)
  desc: A creature that touches the construct or hits it with a melee attack while within 5 feet of it takes 1d10 fire damage.
- name: Stony Lethargy (Stone Only)
  desc: When a creature the construct can see starts its turn within 10 feet of the construct, the construct can force it to make a Wisdom saving throw against your spell save DC. On a failed save, the target can't use reactions and its speed is halved until the start of its next turn.
actions:
- name: Multiattack
  desc: The construct makes a number of attacks equal to half this spell's level (rounded down).
- name: Slam
  desc: 'Melee Weapon Attack:  to hit, reach 5 ft., one target. Hit: 1d8 + 4 + summonSpellLevel bludgeoning damage.'
reactions:
- name: Berserk Lashing (Clay Only)
  desc: When the construct takes damage, it makes a slam attack against a random creature within 5 feet of it. If no creature is within reach, the construct moves up to half its speed toward an enemy it can see, without provoking opportunity attacks.
---
