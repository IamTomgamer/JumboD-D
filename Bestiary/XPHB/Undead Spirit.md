---
statblock: true
layout: Basic 5e Layout
name: Undead Spirit
source: XPHB
size: Medium
type: undead
alignment: neutral
ac: 11 + the spell's level
hp: 30 (Ghostly and Putrid only) or 20 (Skeletal only) + 10 for each spell level above 3
speed: 30 ft., fly 40 ft. (hover) (hover; Ghostly only)
stats:
- 12
- 16
- 15
- 4
- 10
- 9
damage_immunities: necrotic, poison
condition_immunities: exhaustion, frightened, paralyzed, poisoned
senses: Darkvision 60 ft., passive Perception 10
languages: understands the languages you know
cr: ''
traits:
- name: Festering Aura (Putrid Only)
  desc: con DC equals your spell save DC, any creature (other than you) that starts its turn within a 5-foot Emanation originating from the spirit.  The creature has the Poisoned condition until the start of its next turn.
- name: Incorporeal Passage (Ghostly Only)
  desc: The spirit can move through other creatures and objects as if they were Difficult Terrain. If it ends its turn inside an object, it is shunted to the nearest unoccupied space and takes 1d10 Force damage for every 5 feet traveled.
actions:
- name: Multiattack
  desc: The spirit makes a number of attacks equal to half this spell's level (round down).
- name: Deathly Touch (Ghostly Only)
  desc: 'm Bonus equals your spell attack modifier, reach 5 ft. Hit: 1d8 + 3 + summonSpellLevel Necrotic damage, and the target has the Frightened condition until the end of its next turn.'
- name: Grave Bolt (Skeletal Only)
  desc: 'r Bonus equals your spell attack modifier, range 150 ft. Hit: 2d4 + 3 + summonSpellLevel Necrotic damage.'
- name: Rotting Claw (Putrid Only)
  desc: 'm Bonus equals your spell attack modifier, reach 5 ft. Hit: 1d6 + 3 + summonSpellLevel Slashing damage. If the target has the Poisoned condition, it has the Paralyzed condition until the end of its next turn.'
---
