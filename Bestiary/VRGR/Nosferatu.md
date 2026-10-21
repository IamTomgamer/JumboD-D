---
statblock: true
layout: Basic 5e Layout
name: Nosferatu
source: VRGR
size: Medium
type: undead
alignment: ''
ac: 17 (natural armor)
hp: 85
hit_dice: 9d8 + 45
speed: 40 ft.
stats:
- 20
- 18
- 21
- 6
- 17
- 14
saves:
- dex: 7
- con: 8
- wis: 6
skillsaves:
- perception: 6
- stealth: 10
damage_resistances: necrotic
condition_immunities: charmed, frightened
senses: darkvision 120 ft., passive Perception 16
languages: the languages it knew in life
cr: '8'
traits:
- name: Regeneration
  desc: The nosferatu regains 10 hit points at the start of each of its turns if it has at least 1 hit point and isn't in sunlight. If the nosferatu takes radiant damage, this trait doesn't function until the start of the nosferatu's next turn.
- name: Spider Climb
  desc: The nosferatu can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.
- name: Sunlight Hypersensitivity
  desc: The nosferatu takes 20 radiant damage when it starts its turn in sunlight. While in sunlight, it has disadvantage on attack rolls and ability checks.
- name: Unusual Nature
  desc: The nosferatu doesn't require air.
actions:
- name: Multiattack
  desc: The nosferatu makes two Claw attacks followed by one Bite attack. If both Claw attacks hit the same creature, the Bite attack is made with advantage.
- name: Claw
  desc: 'Melee Weapon Attack: +8 to hit, reach 5 ft., one target. Hit: 9 (1d8 + 5) slashing damage.'
- name: Bite
  desc: |-
    Melee Weapon Attack: +8 to hit, reach 5 ft., one creature. Hit: 9 (1d8 + 5) piercing damage plus 7 (2d6) necrotic damage. If the target is missing any of its hit points, it instead takes 11 (2d10) necrotic damage.
    The target's hit point maximum is reduced by an amount equal to the necrotic damage taken, and the nosferatu regains hit points equal to that amount. The reduction lasts until the target finishes a long rest. The target dies if its hit point maximum is reduced to 0. A Humanoid slain in this way and then buried in the ground rises as a nosferatu after 1d10 days.
- name: Blood Disgorge (Recharge 5-6)
  desc: The nosferatu vomits blood in a 15-foot cone. Each creature in that area must make a DC 16 Constitution saving throw. On a failed save, a creature takes 18 (4d8) necrotic damage, and it can't regain hit points for 1 minute. On a successful save, the creature takes half as much damage with no additional effects.
---
