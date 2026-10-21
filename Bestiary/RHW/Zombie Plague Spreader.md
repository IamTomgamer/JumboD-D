---
statblock: true
layout: Basic 5e Layout
name: Zombie Plague Spreader
source: RHW
size: Medium
type: undead
alignment: neutral evil
ac: 10
hp: 78
hit_dice: 12d8 + 24
speed: 30 ft.
stats:
- 16
- 10
- 15
- 3
- 5
- 5
damage_resistances: necrotic
damage_immunities: poison
condition_immunities: charmed, exhaustion, poisoned
senses: Darkvision 60 ft., passive Perception 7
languages: understands Common plus one other language but can't speak
cr: '4'
traits:
- name: Undead Fortitude
  desc: If damage reduces the zombie to 0 Hit Points, it makes a Constitution saving throw (DC 5 plus the damage taken) unless the damage is Radiant or from a Critical Hit. On a successful save, the zombie drops to 1 Hit Point instead.
- name: Viral Aura
  desc: con DC 12, any creature that starts its turn in a 10-foot Emanation originating from the zombie.  The target has the Poisoned condition until the start of its next turn. While Poisoned, the target can't regain Hit Points.  The creature is immune to this zombie's Viral Aura for 24 hours.
actions:
- name: Multiattack
  desc: The zombie makes two Slam attacks.
- name: Slam
  desc: 'm +5, reach 5 ft. Hit: 6 (1d6 + 3) Bludgeoning damage plus 9 (2d8) Necrotic damage.'
- name: Virulent Miasma (1/Day)
  desc: con DC 12, each creature in a 30-foot Emanation originating from the zombie.  14 (4d6) Poison damage.  Half damage.  If this damage reduces the target to 0 Hit Points, it dies and rises 1 minute later as a Zombie.
---
