---
statblock: true
layout: Basic 5e Layout
name: Undead Spirit
source: TCE
size: Medium
type: undead
alignment: unaligned
ac: 11 + the level of the spell (natural armor)
hp: 30 (Ghostly and Putrid only) or 20 (Skeletal only) + 10 for each spell level above 3rd
speed: 30 ft., fly 40 ft. (hover) (ghostly only; hover)
stats:
- 12
- 16
- 15
- 4
- 10
- 9
damage_immunities: necrotic, poison
condition_immunities: exhaustion, frightened, paralyzed, poisoned
senses: darkvision 60 ft., passive Perception 10
languages: understands the languages you speak
cr: ''
traits:
- name: Incorporeal Passage (Ghostly Only)
  desc: The spirit can move through other creatures and objects as if they were 3. If it ends its turn inside an object, it is shunted to the nearest unoccupied space and takes 1d10 force damage for every 5 feet traveled.
- name: Festering Aura (Putrid Only)
  desc: Any creature, other than you, that starts its turn within 5 feet of the spirit must succeed on a Constitution saving throw against your spell save DC or be poisoned until the start of its next turn.
actions:
- name: Multiattack
  desc: The spirit makes a number of attacks equal to half this spell's level (rounded down).
- name: Deathly Touch (Ghostly Only)
  desc: 'Melee Weapon Attack:  to hit, reach 5 ft., one creature. Hit: 1d8 + 3 + summonSpellLevel necrotic damage, and the creature must succeed on a Wisdom saving throw against your spell save DC or be frightened of the undead until the end of the target''s next turn.'
- name: Grave Bolt (Skeletal Only)
  desc: 'Ranged Spell Attack:  to hit, range 150 ft., one target. Hit: 2d4 + 3 + summonSpellLevel necrotic damage.'
- name: Rotting Claw (Putrid Only)
  desc: 'Melee Weapon Attack:  to hit, reach 5 ft., one target. Hit: 1d6 + 3 + summonSpellLevel slashing damage. If the target is poisoned, it must succeed on a Constitution saving throw against your spell save DC or be paralyzed until the end of its next turn.'
---
