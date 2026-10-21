---
statblock: true
layout: Basic 5e Layout
name: Snow Golem
source: IDRotF
size: Medium
type: construct
alignment: unaligned
ac: 8
hp: 39
hit_dice: 6d8 + 12
speed: 10 ft.
stats:
- 15
- 6
- 14
- 1
- 6
- 1
damage_vulnerabilities: fire
damage_immunities: cold; poison; bludgeoning, piercing, slashing from nonmagical attacks
condition_immunities: charmed, exhaustion, frightened, paralyzed, petrified, poisoned
senses: blindsight 60 ft. (blind beyond this radius), passive Perception 8
languages: —
cr: '3'
traits:
- name: Cold Absorption
  desc: Whenever the golem is subjected to cold damage, it takes no damage and instead regains a number of hit points equal to the cold damage dealt.
- name: Immutable Form
  desc: The golem is immune to any spell or effect that would alter its form.
- name: Melt
  desc: While in an area of extreme heat, the golem loses 1d6 hit points at the start of each of its turns.
- name: Unusual Nature
  desc: The golem doesn't require air, food, drink, or sleep.
actions:
- name: Multiattack
  desc: The golem makes three melee attacks.
- name: Slam
  desc: 'Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 5 (1d6 + 2) bludgeoning damage plus 7 (2d6) cold damage.'
- name: Snowball
  desc: 'Ranged Weapon Attack: +0 to hit, range 60 ft., one target. Hit: 9 (2d6 + 2) cold damage.'
---
