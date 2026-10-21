---
statblock: true
layout: Basic 5e Layout
name: Autumn Eladrin
source: MPMM
size: Medium
type: fey
subtype: elf
alignment: Typically chaotic neutral
ac: 19 (natural armor)
hp: 165
hit_dice: 22d8 + 66
speed: 30 ft.
stats:
- 12
- 16
- 16
- 14
- 17
- 18
skillsaves:
- insight: 7
- medicine: 7
damage_resistances: psychic
senses: darkvision 60 ft., passive Perception 13
languages: Common, Elvish, Sylvan
cr: '10'
traits:
- name: Enchanting Presence
  desc: |-
    Any non-eladrin creature that starts its turn within 60 feet of the eladrin must make a DC 16 Wisdom saving throw. On a failed save, the creature becomes charmed by the eladrin for 1 minute. On a successful save, the creature becomes immune to any eladrin's Enchanting Presence for 24 hours.
    Whenever the eladrin deals damage to the charmed creature, the charmed creature can repeat the saving throw, ending the effect on itself on a success.
- name: Magic Resistance
  desc: The eladrin has advantage on saving throws against spells and other magical effects.
- name: Spellcasting
  desc: |-
    The eladrin casts one of the following spells, requiring no material components and using Charisma as the spellcasting ability (spell save DC 16):
    At will: hold person
    2/day each: cure wounds (as a 5th-level spell), lesser restoration
    1/day each: greater restoration, revivify
actions:
- name: Multiattack
  desc: The eladrin makes two Longsword or Longbow attacks. It can replace one attack with a use of Spellcasting.
- name: Longsword
  desc: 'Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 5 (1d8 + 1) slashing damage, or 6 (1d10 + 1) slashing damage if used with two hands, plus 22 (5d8) psychic damage.'
- name: Longbow
  desc: 'Ranged Weapon Attack: +7 to hit, range 150/600 ft., one target. Hit: 7 (1d8 + 3) piercing damage plus 22 (5d8) psychic damage.'
bonus_actions:
- name: Fey Step (Recharge 4-6)
  desc: The eladrin teleports, along with any equipment it is wearing or carrying, up to 30 feet to an unoccupied space it can see.
reactions:
- name: Foster Peace
  desc: If a creature charmed by the eladrin hits with an attack roll while within 60 feet of the eladrin, the eladrin magically causes the attack to miss, provided the eladrin can see the attacker.
---
