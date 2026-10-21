---
statblock: true
layout: Basic 5e Layout
name: Qunbraxel
source: PaBTSO
size: Medium
type: aberration
subtype: mind flayer, warlock
alignment: lawful evil
ac: 12, 15 with mage armor
hp: 112
hit_dice: 15d8 + 45
speed: 30 ft.
stats:
- 11
- 14
- 17
- 19
- 15
- 19
saves:
- int: 8
- wis: 6
- cha: 8
skillsaves:
- arcana: 8
- insight: 6
- perception: 6
- stealth: 6
senses: darkvision 120 ft., passive Perception 16
languages: Deep Speech, telepathy 60 ft., Undercommon
cr: '9'
traits:
- name: Magic Resistance
  desc: Qunbraxel has advantage on saving throws against spells and other magical effects.
- name: Spellcasting (Psionics)
  desc: |-
    Qunbraxel casts one of the following spells, requiring no spell components and using Charisma as the spellcasting ability (spell save DC 16):
    At will: detect magic, detect thoughts, levitate, mage armor (self only), mage hand (the hand is invisible), prestidigitation
    2/day each: confusion, sending, telekinesis
    1/day each: dominate monster, plane shift (self only)
actions:
- name: Multiattack
  desc: Qunbraxel makes two Eldritch Bolt attacks, or one Eldritch Bolt attack and one Tentacle attack.
- name: Tentacle
  desc: 'Melee Weapon Attack: +8 to hit, reach 5 ft., one creature. Hit: 15 (2d10 + 4) psychic damage. If the target is Medium or smaller, it has the grappled condition (escape DC 16) and must succeed on a DC 16 Intelligence saving throw or have the stunned condition until the grapple ends.'
- name: Eldritch Bolt
  desc: 'Ranged Spell Attack: +8 to hit, range 120 ft., one target. Hit: 20 (3d10 + 4) force damage.'
- name: Extract Brain
  desc: 'Melee Weapon Attack: +8 to hit, reach 5 ft., one Humanoid with the stunned condition who is grappled by Qunbraxel. Hit: 55 (10d10) piercing damage. If this damage reduces the target to 0 hit points, Qunbraxel kills it by extracting and devouring its brain.'
- name: Mind Blast (Recharge 5-6)
  desc: Qunbraxel magically emits psychic energy in a 60-foot cone. Each creature in that area must succeed on a DC 16 Intelligence saving throw or take 26 (5d8 + 4) psychic damage and have the stunned condition for 1 minute. A stunned creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.
---
