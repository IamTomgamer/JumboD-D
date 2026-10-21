---
statblock: true
layout: Basic 5e Layout
name: Beholder Zombie
source: XMM
size: Large
type: undead
alignment: neutral evil
ac: 15
hp: 93
hit_dice: 11d10 + 33
speed: 5 ft., fly 20 ft. (hover) (hover)
stats:
- 14
- 8
- 16
- 3
- 8
- 5
saves:
- wis: 2
damage_immunities: poison
condition_immunities: exhaustion, poisoned, prone
senses: Darkvision 60 ft., passive Perception 9
languages: understands Deep Speech and Undercommon but can't speak
cr: '5'
traits:
- name: Undead Fortitude
  desc: If damage reduces the zombie to 0 Hit Points, it makes a Constitution saving throw (DC 5 plus the damage taken) unless the damage is Radiant or from a Critical Hit. On a successful save, the zombie drops to 1 Hit Point instead.
actions:
- name: Multiattack
  desc: The zombie uses Eye Rays twice.
- name: Bite
  desc: 'm +5, reach 5 ft. Hit: 16 (4d6 + 2) Piercing damage.'
- name: Eye Rays
  desc: |-
    The zombie randomly shoots one of the following magical rays at a target it can see within 120 feet of itself (roll 1d4; reroll if the zombie has already used that ray during this turn):
    - **1: Paralyzing Ray** con DC 14.  The target has the Paralyzed condition and repeats the save at the end of each of its turns, ending the effect on itself on a success. After 1 minute, it succeeds automatically.
    - **2: Fear Ray** wis DC 14.  13 (3d8) Psychic damage, and the target has the Frightened condition until the end of its next turn.
    - **3: Enervation Ray** con DC 14.  10 (3d6) Necrotic damage, and the target has the Poisoned condition until the end of its next turn. While Poisoned, the target can't regain Hit Points.  Half damage only.
    - **4: Disintegration Ray** dex DC 14.  27 (5d10) Force damage. If the target is a nonmagical object or a creation of magical force, a 10-foot Cube of it disintegrates into dust.  Half damage.  If the target is a creature and this damage reduces it to 0 Hit Points, it disintegrates into dust.
---
