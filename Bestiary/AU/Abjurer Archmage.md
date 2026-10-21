---
statblock: true
layout: Basic 5e Layout
name: Abjurer Archmage
source: AU
size: Medium
type: humanoid
subtype: wizard
alignment: neutral
ac: 16
hp: 198
hit_dice: 36d8 + 36
speed: 30 ft.
stats:
- 10
- 16
- 12
- 20
- 15
- 16
skillsaves:
- arcana: 15
- history: 10
- perception: 7
damage_immunities: psychic
condition_immunities: charmed
senses: passive Perception 17
languages: Common plus five other languages
cr: '15'
traits:
- name: Magic Resistance
  desc: The archmage has Advantage on saving throws against spells and other magical effects.
- name: Spellcasting
  desc: |-
    The archmage casts one of the following spells, using Intelligence as the spellcasting ability (spell save DC 18):
    At will: Arcane Lock, Detect Magic, Mage Armor (included in AC), Mage Hand, Prestidigitation
    2/day each: Fireball (level 7 version), Nondetection, Otiluke's Resilient Sphere
    1/day each: Mind Blank (cast before combat), Teleport
- name: Magic Disruption (2/Day)
  desc: |-
    The archmage casts Dispel Magic or Globe of Invulnerability, using the same spellcasting ability as Spellcasting.
    2/day: Dispel Magic, Globe of Invulnerability
- name: Counterspell (3/Day)
  desc: |-
    The archmage casts Counterspell in response to the spell's trigger, using the same spellcasting ability as Spellcasting.
    3/day: Counterspell
actions:
- name: Multiattack
  desc: The archmage makes three Arcane Burst attacks.
- name: Arcane Burst
  desc: 'm,r +10, reach 5 ft. or range 150 ft. Hit: 27 (4d10 + 5) Force damage.'
- name: Banishing Blast (Recharge 6)
  desc: cha DC 18, each creature in a 60-foot Cone.  45 (10d8) Force damage, and the target has the Incapacitated condition and is transported to a harmless demiplane until the start of the archmage's next turn, at which point it reappears in the space it left or in the nearest unoccupied space if that space is occupied.  Half damage only.
bonus_actions:
- name: Fortify (Recharge 4-6)
  desc: The archmage magically bolsters itself. The archmage gains 40 Temporary Hit Points.
---
