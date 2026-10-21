---
statblock: true
layout: Basic 5e Layout
name: Mind Flayer Clairvoyant
source: PaBTSO
size: Medium
type: aberration
alignment: typically lawful evil
ac: 15 (breastplate)
hp: 156
hit_dice: 24d8 + 48
speed: 30 ft., fly 60 ft. (hover) (hover)
stats:
- 11
- 12
- 15
- 21
- 17
- 18
saves:
- int: 9
- wis: 7
- cha: 8
skillsaves:
- arcana: 9
- insight: 7
- perception: 7
- stealth: 5
damage_resistances: psychic
condition_immunities: blinded, charmed, frightened
senses: darkvision 120 ft., truesight 15 ft., passive Perception 17
languages: Deep Speech, telepathy 120 ft., Undercommon
cr: '11'
traits:
- name: Legendary Resistance (3/Day)
  desc: If the mind flayer fails a saving throw, it can choose to succeed instead.
- name: Magic Resistance
  desc: The mind flayer has advantage on saving throws against spells and other magical effects.
- name: Spellcasting (Psionics)
  desc: |-
    The mind flayer casts one of the following spells, requiring no spell components and using Intelligence as the spellcasting ability (spell save DC 17):
    At will: detect magic, detect thoughts, mage hand (the hand is invisible)
    1/day: plane shift (self only)
    3/day each: clairvoyance (as an action), dispel magic
actions:
- name: Multiattack
  desc: The mind flayer makes two Tentacle attacks.
- name: Tentacle
  desc: 'Melee Weapon Attack: +9 to hit, reach 5 ft., one creature. Hit: 21 (3d10 + 5) psychic damage. If the target is Medium or smaller, it has the grappled condition (escape DC 17) and must succeed on a DC 17 Intelligence saving throw or have the incapacitated condition until the grapple ends.'
- name: Extract Brain
  desc: 'Melee Weapon Attack: +9 to hit, reach 5 ft., one incapacitated Humanoid grappled by the mind flayer. Hit: 55 (10d10) piercing damage. If this damage reduces the target to 0 hit points, the mind flayer kills it by extracting and devouring its brain.'
- name: Unleash Void (Recharge 5-6)
  desc: The mind flayer opens a rift into the Far Realm, centered on a point the mind flayer can see within 60 feet of itself, and a tentacle lashes across creatures near the rift. Each creature other than mind flayers within 30 feet of the rift must make a DC 17 Intelligence saving throw, after which the tentacle disappears and the rift closes. On a failed save, a creature takes 18 (4d8) cold damage from the rift plus 18 (4d8) psychic damage from the tentacle and has the stunned condition for 1 minute. On a successful save, a creature takes half as much damage only. A stunned creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.
reactions:
- name: Warp Reality
  desc: When hit by an attack roll, the mind flayer gains a +4 bonus to its AC against that attack roll, potentially causing it to miss. Then the mind flayer, along with any equipment it is wearing or carrying, magically teleports up to 60 feet to an unoccupied space it can see.
---
