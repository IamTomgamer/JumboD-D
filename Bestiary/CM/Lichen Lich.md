---
statblock: true
layout: Basic 5e Layout
name: Lichen Lich
source: CM
size: Medium
type: undead
alignment: ''
ac: 20 (natural armor)
hp: 225
hit_dice: 30d8 + 90
speed: 30 ft.
stats:
- 11
- 16
- 16
- 14
- 20
- 16
saves:
- con: 9
- int: 8
- wis: 11
- cha: 9
skillsaves:
- medicine: 11
- nature: 14
- perception: 11
- survival: 11
damage_resistances: cold, necrotic
damage_immunities: poison
condition_immunities: charmed, exhaustion, frightened, paralyzed, poisoned, stunned
senses: truesight 120 ft., passive Perception 21
languages: Common, Druidic, Sylvan
cr: '18'
traits:
- name: Legendary Resistance (3/Day)
  desc: If the lich fails a saving throw, it can choose to succeed instead.
- name: Rejuvenation
  desc: If it has a phylactery, a destroyed lich gains a new body in 1d10 days, regaining all its hit points and becoming active again. The new body appears within 5 feet of the phylactery.
- name: Spellcasting
  desc: |-
    The lich casts one of the following spells using Wisdom as the spellcasting ability (save DC 19):
    At will: druidcraft
    3/day each: detect magic, fog cloud, pass without trace
    1/day each: antilife shell, dispel magic, speak with plants, transport via plants, fire storm
actions:
- name: Multiattack
  desc: The lich makes four attacks.
- name: Poisonous Touch
  desc: 'Melee Weapon Attack: +9 to hit, reach 10 ft., one creature. Hit: 17 (5d6) poison damage, and the target must succeed on a DC 19 Constitution saving throw or be poisoned for 1 minute. The target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.'
- name: Wither
  desc: 'Ranged Spell Attack: +9 to hit, range 60 ft., one target. Hit: 14 (4d6) necrotic damage.'
- name: Fire Storm (7th-Level Spell; 1/Day)
  desc: The lich fills up to ten 10-foot cubes with fire. Every cube must be within 150 feet of the lich and occupy a space the lich can see, and each cube must have at least one face adjacent to the face of another cube. Each creature in the area must make a DC 19 Dexterity saving throw, taking 38 (7d10) fire damage on a failed save, or half as much damage on a successful one. The fire ignites flammable objects in the area that aren't being worn or carried. If the lich chooses, plant life in the area is unaffected by the spell.
legendary_actions:
- name: Attack
  desc: The lich makes an attack.
- name: Poison Prick (Cost 2 Actions)
  desc: The lich targets one poisoned creature it can see within 30 feet of it. The target must succeed on a DC 19 Constitution saving throw or fall unconscious until the poisoned condition ends on it.
- name: Sap Life (Costs 2 Actions)
  desc: The lich targets one creature it can see within 30 feet of it. The target must succeed on a DC 19 Constitution saving throw or take 11 (2d10) necrotic damage. The lich regains a number of hit points equal to the amount of damage that the creature takes.
legendary_description: The lichen lich can take 3 legendary actions, choosing from the options below. Only one legendary action option can be used at a time and only at the end of another creature's turn. The lichen lich regains spent legendary actions at the start of its turn.
---
