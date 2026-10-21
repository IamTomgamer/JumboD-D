---
statblock: true
layout: Basic 5e Layout
name: Encephalon Cluster
source: PaBTSO
size: Large
type: aberration
alignment: unaligned
ac: 13 (natural armor)
hp: 110
hit_dice: 17d10 + 17
speed: 20 ft.
stats:
- 23
- 10
- 13
- 5
- 17
- 7
damage_resistances: psychic
condition_immunities: blinded
senses: blindsight 60 ft. (can't see beyond this radius), passive Perception 13
languages: —
cr: '10'
traits:
- name: Legendary Resistance (3/Day)
  desc: If the cluster fails a saving throw, it can choose to succeed instead.
- name: Magic Resistance
  desc: The cluster has advantage on saving throws against spells and other magical effects.
actions:
- name: Multiattack
  desc: The cluster makes two Slam attacks. It can replace one of these attacks with Spawn Progeny if available.
- name: Slam
  desc: 'Melee Weapon Attack: +10 to hit, reach 5 ft., one target. Hit: 17 (2d10 + 6) bludgeoning damage plus 10 (3d6) psychic damage, and if the target is a creature, the target must succeed on a DC 18 Strength saving throw or have the prone condition. If this attack reduces the target to 0 hit points, the target immediately dies and is consumed by the cluster.'
- name: Spawn Progeny (Recharges after a Short or Long Rest)
  desc: The cluster bulges and spews 1d4 mature eggs. Each egg lands in an unoccupied space of the cluster's choice within 30 feet of itself and immediately transforms into an encephalon gemmule. The gemmules obey the cluster's commands and take their turns immediately after it.
reactions:
- name: Aggressive Hunger
  desc: Immediately after being hit by an attack, the cluster moves up to its speed toward the attacker. This movement doesn't provoke opportunity attacks. If the cluster ends this movement within 5 feet of the attacker, it then makes one Slam attack against that attacker.
---
