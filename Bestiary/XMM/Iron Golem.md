---
statblock: true
layout: Basic 5e Layout
name: Iron Golem
source: XMM
size: Large
type: construct
alignment: unaligned
ac: 20
hp: 252
hit_dice: 24d10 + 120
speed: 30 ft.
stats:
- 24
- 9
- 20
- 3
- 11
- 1
damage_immunities: fire, poison, psychic
condition_immunities: charmed, exhaustion, frightened, paralyzed, petrified, poisoned
senses: Darkvision 120 ft., passive Perception 10
languages: understands Common plus two other languages but can't speak
cr: '16'
traits:
- name: Fire Absorption
  desc: Whenever the golem is subjected to Fire damage, it regains a number of Hit Points equal to the Fire damage dealt.
- name: Immutable Form
  desc: The golem can't shape-shift.
- name: Magic Resistance
  desc: The golem has Advantage on saving throws against spells and other magical effects.
actions:
- name: Multiattack
  desc: The golem makes two attacks, using Bladed Arm or Fiery Bolt in any combination.
- name: Bladed Arm
  desc: 'm +12, reach 10 ft. Hit: 20 (3d8 + 7) Slashing damage plus 10 (3d6) Fire damage.'
- name: Fiery Bolt
  desc: 'r +10, range 120 ft. Hit: 36 (8d8) Fire damage.'
- name: Poison Breath (Recharge 6)
  desc: con DC 18, each creature in a 60-foot Cone.  55 (10d10) Poison damage.  Half damage.
---
