---
statblock: true
layout: Basic 5e Layout
name: Witchkite
source: MCV4EC
size: Huge
type: dragon
subtype: warlock
alignment: typically chaotic evil
ac: 16 (natural armor)
hp: 220
hit_dice: 21d12 + 84
speed: 40 ft., fly 80 ft.
stats:
- 23
- 10
- 18
- 15
- 17
- 19
saves:
- dex: 5
- wis: 8
- cha: 9
skillsaves:
- arcana: 7
- perception: 8
- stealth: 5
damage_resistances: fire, psychic
senses: darkvision 120 ft., passive Perception 18
languages: Draconic
cr: '15'
traits:
- name: Legendary Resistance (3/Day)
  desc: If the witchkite fails a saving throw, it can choose to succeed instead.
- name: Spellcasting
  desc: |-
    The witchkite casts one of the following spells, requiring no material components and using Charisma as the spellcasting ability (spell save DC 17):
    At will: detect magic, minor illusion, speak with dead
    1/day each: detect thoughts, dimension door, hold monster
actions:
- name: Multiattack
  desc: The witchkite makes two Rend attacks and uses Malevolent Flare once.
- name: Rend
  desc: 'Melee Weapon Attack: +11 to hit, reach 10 ft., one target. Hit: 16 (3d6 + 6) slashing damage.'
- name: Malevolent Flare
  desc: |-
    The witchkite spits magical, green-tinged flame at one creature it can see within 60 feet of itself. The target must make a DC 17 Dexterity saving throw. On a failed save, the target takes 22 (5d8) fire damage and suffers one of the following effects of the witchkite's choice:
    - The target must use its reaction to make a melee attack against another creature of the witchkite's choice that is within the target's reach.
    - The target takes 13 (2d12) psychic damage.
    On a successful save, the target takes half as much damage only.
reactions:
- name: Enchanting Gaze
  desc: When a creature the witchkite can see moves within 10 feet of it, the witchkite emits an enchanting gaze at the creature. The creature must succeed on a DC 17 Wisdom saving throw or take 10 (3d6) psychic damage and have the charmed condition until the end of its next turn.
- name: Retribution
  desc: Immediately after taking damage from a melee attack, the witchkite makes one Rend attack against the attacker.
---
