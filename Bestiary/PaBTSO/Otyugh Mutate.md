---
statblock: true
layout: Basic 5e Layout
name: Otyugh Mutate
source: PaBTSO
size: Large
type: aberration
alignment: typically neutral
ac: 16 (natural armor)
hp: 76
hit_dice: 8d10 + 32
speed: 30 ft.
stats:
- 19
- 11
- 18
- 10
- 15
- 6
saves:
- str: 7
- con: 7
damage_immunities: poison
condition_immunities: poisoned
senses: darkvision 120 ft., passive Perception 12
languages: Otyugh, telepathy 120 ft.
cr: '6'
traits:
- name: Virulent Breath
  desc: Noxious gas from the mutate's digestion of previous meals spews from its mouth. At the start of the mutate's turn, each creature within 5 feet of it must succeed on a DC 15 Constitution saving throw or take 3 (1d6) poison damage.
actions:
- name: Multiattack
  desc: The mutate makes two Bite or Tentacle attacks. It can replace one of these attacks with Chitin Slam.
- name: Bite
  desc: 'Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 13 (2d8 + 4) piercing damage. If the target is a creature, it must succeed on a DC 15 Constitution saving throw or have the poisoned condition. Every 24 hours that elapse, the target must repeat the saving throw, reducing its hit point maximum by 5 (1d10) on a failure. On a successful save, the target is no longer poisoned. The target dies if its hit point maximum is reduced to 0. This reduction to the target''s hit point maximum lasts until it no longer has the poisoned condition.'
- name: Tentacle
  desc: 'Melee Weapon Attack: +7 to hit, reach 10 ft., one target. Hit: 13 (2d8 + 4) bludgeoning damage, and if the target is a Medium or smaller creature, it has the grappled condition (escape DC 15) and the restrained condition until this grapple ends. The mutate has two tentacles that can grapple one target each.'
- name: Chitin Slam
  desc: The mutate targets one creature it is grappling, slamming the creature against its chitinous plating. The creature must succeed on a DC 15 Constitution saving throw or take 16 (3d10) bludgeoning damage and have the stunned condition until the end of the mutate's next turn.
---
