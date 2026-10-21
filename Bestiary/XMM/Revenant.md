---
statblock: true
layout: Basic 5e Layout
name: Revenant
source: XMM
size: Medium
type: undead
alignment: neutral
ac: 13
hp: 127
hit_dice: 15d8 + 60
speed: 30 ft.
stats:
- 18
- 14
- 18
- 13
- 16
- 18
saves:
- str: 7
- con: 7
- wis: 6
- cha: 7
damage_resistances: necrotic, psychic
damage_immunities: poison
condition_immunities: charmed, exhaustion, frightened, paralyzed, poisoned, stunned
senses: Darkvision 60 ft., passive Perception 13
languages: Common plus one other language
cr: '5'
traits:
- name: Regeneration
  desc: The revenant regains 10 Hit Points at the start of each of its turns. If the revenant takes Fire or Radiant damage, this trait doesn't function at the start of its next turn. Its body is destroyed only if it starts its turn with 0 Hit Points and doesn't regenerate.
- name: Undead Restoration
  desc: If the revenant dies, it revives 24 hours later in a different body unless Dispel Evil and Good is cast on its corpse. If it revives, it animates a Humanoid corpse elsewhere on the same plane of existence; it now looks different but uses the same stat block and returns with all its Hit Points.
actions:
- name: Multiattack
  desc: The revenant uses Vengeful Glare and makes two Slam attacks.
- name: Slam
  desc: 'm +7, reach 5 ft. Hit: 11 (2d6 + 4) Necrotic damage.'
- name: Vengeful Glare
  desc: wis DC 15, one creature the revenant can see within 30 feet.  The target has the Frightened condition and repeats the save at the end of each of its turns, ending the effect on itself on a success. After 1 minute, it succeeds automatically. If the Frightened target is cursed by the revenant (see Vow of Revenge), the target also has the Paralyzed condition for the duration.
bonus_actions:
- name: Vow of Revenge (1/Day)
  desc: The revenant curses one creature it can see within 30 feet of itself. The revenant knows the distance to and direction of the cursed target, even if it is on a different plane of existence. The curse ends on the target if the revenant uses this Bonus Action on a different creature.
---
