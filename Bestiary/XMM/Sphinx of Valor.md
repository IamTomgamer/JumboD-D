---
statblock: true
layout: Basic 5e Layout
name: Sphinx of Valor
source: XMM
size: Large
type: celestial
alignment: lawful neutral
ac: 17
hp: 199
hit_dice: 19d10 + 95
speed: 40 ft., fly 60 ft.
stats:
- 22
- 10
- 20
- 16
- 23
- 18
saves:
- dex: 6
- con: 11
- int: 9
- wis: 12
skillsaves:
- arcana: 9
- perception: 12
- religion: 15
damage_resistances: necrotic, radiant
damage_immunities: psychic
condition_immunities: charmed, frightened
senses: Truesight 120 ft., passive Perception 22
languages: Celestial, Common
cr: '17'
traits:
- name: Inscrutable
  desc: No magic can observe the sphinx remotely or detect its thoughts without its permission. Wisdom (Insight) checks made to ascertain its intentions or sincerity are made with Disadvantage.
- name: Legendary Resistance (3/Day, or 4/Day in Lair)
  desc: If the sphinx fails a saving throw, it can choose to succeed instead.
- name: Spellcasting
  desc: |-
    The sphinx casts one of the following spells, requiring no Material components and using Wisdom as the spellcasting ability (spell save DC 20):
    At will: Detect Evil and Good, Thaumaturgy
    1/day each: Detect Magic, Dispel Magic, Greater Restoration, Heroes' Feast, Zone of Truth
actions:
- name: Multiattack
  desc: The sphinx makes two Claw attacks and uses Roar.
- name: Claw
  desc: 'm +12, reach 5 ft. Hit: 20 (4d6 + 6) Slashing damage.'
- name: Roar (3/Day)
  desc: |-
    The sphinx emits a magical roar. Whenever it roars, the roar has a different effect, as detailed below (the sequence resets when it takes a Long Rest):
    - **First Roar** wis DC 20, each enemy in a 500-foot Emanation originating from the sphinx.  The target has the Frightened condition for 1 minute.
    - **Second Roar** wis DC 20, each enemy in a 500-foot Emanation originating from the sphinx.  The target has the Paralyzed condition, and it repeats the save at the end of each of its turns, ending the effect on itself on a success. After 1 minute, it succeeds automatically.
    - **Third Roar** con DC 20, each enemy in a 500-foot Emanation originating from the sphinx.  44 (8d10) Thunder damage, and the target has the Prone condition.  Half damage only.
legendary_actions:
- name: Arcane Prowl
  desc: The sphinx can teleport up to 30 feet to an unoccupied space it can see, and it makes one Claw attack.
- name: Weight of Years
  desc: con DC 16, one creature the sphinx can see within 120 feet.  The target gains 1 Exhaustion level. While the target has any Exhaustion levels, it appears 3d10 years older.  The sphinx can't take this action again until the start of its next turn.
legendary_description: The sphinx of valor can take 3 legendary actions, choosing from the options below. Only one legendary action option can be used at a time and only at the end of another creature's turn. The sphinx of valor regains spent legendary actions at the start of its turn.
---
