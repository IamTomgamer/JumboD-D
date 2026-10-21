---
statblock: true
layout: Basic 5e Layout
name: Zombie Clot
source: VRGR
size: Huge
type: undead
alignment: ''
ac: 12 (natural armor)
hp: 104
hit_dice: 11d12 + 33
speed: 40 ft.
stats:
- 20
- 10
- 16
- 3
- 8
- 10
saves:
- con: 6
damage_immunities: poison
condition_immunities: charmed, exhaustion, paralyzed, petrified, poisoned, stunned
senses: darkvision 60 ft., passive Perception 9
languages: understands the languages it knew in life but can't speak
cr: '6'
traits:
- name: Deathly Stench
  desc: Any creature that starts its turn within 10 feet of the zombie must succeed on a DC 14 Constitution saving throw or take 9 (2d8) poison damage and be poisoned until the start of the creature's next turn.
- name: Undead Fortitude
  desc: If damage reduces the zombie to 0 hit points, it must make a Constitution saving throw with a DC of 5 + the damage taken, unless the damage is radiant or from a critical hit. On a success, the zombie drops to 1 hit point instead.
- name: Unusual Nature
  desc: The zombie doesn't require air, food, drink, or sleep.
actions:
- name: Multiattack
  desc: The zombie makes two Slam attacks.
- name: Slam
  desc: 'Melee Weapon Attack: +8 to hit, reach 10 ft., one target. Hit: 18 (3d8 + 5) bludgeoning damage.'
- name: Flesh Entomb (Recharge 5-6)
  desc: |-
    The zombie flings a detached clump of corpses at a creature it can see within 30 feet of it. The target must succeed on a DC 16 Strength saving throw or take 16 (3d10) bludgeoning damage, and if the target is a Large or smaller creature, it becomes entombed in dead flesh.
    A creature entombed in the dead flesh is restrained, has 3 against attacks and other effects outside the dead flesh, and takes 10 (3d6) necrotic damage at the start of each of its turns. The creature can be freed if the dead flesh is destroyed. The dead flesh is a Large object with AC 10, 25 hit points, and immunity to poison and psychic damage.
---
