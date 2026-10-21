---
statblock: true
layout: Basic 5e Layout
name: Lohezet
source: DSotDQ
size: Medium
type: humanoid
subtype: human, wizard
alignment: neutral evil
ac: 12
hp: 137
hit_dice: 25d8 + 25
speed: 30 ft.
stats:
- 9
- 14
- 12
- 20
- 14
- 11
saves:
- con: 5
- wis: 6
skillsaves:
- arcana: 9
- history: 9
- medicine: 6
damage_immunities: poison
condition_immunities: poisoned
senses: passive Perception 12
languages: Common, Dwarvish, Elvish, Infernal
cr: '12'
traits:
- name: Toxic Mastery
  desc: Lohezet ignores a creature's resistance to poison damage.
- name: Spellcasting
  desc: |-
    Lohezet casts one of the following spells, requiring no material components and using Intelligence as the spellcasting ability (spell save DC 17):
    At will: detect magic, light, prestidigitation
    2/day each: dimension door, mage armor
    1/day each: arcane eye, dominate person, wall of force
actions:
- name: Multiattack
  desc: Lohezet makes three Withering Blast attacks and uses Miasma if it's available. He can replace one of the attacks with a use of Spellcasting.
- name: Withering Blast
  desc: 'Melee or Ranged Spell Attack: +9 to hit, reach 5 ft. or range 60 ft., one target. Hit: 18 (2d12 + 5) necrotic damage.'
- name: Miasma (Recharge 4-6)
  desc: Lohezet magically conjures a billowing cloud of purple fog in a 20-foot-radius sphere centered on a point within 120 feet of himself. The area within the sphere is 2, and when a creature starts its turn in the sphere or enters the sphere for the first time on a turn, it must make a DC 17 Constitution saving throw. On a failed save, the creature takes 39 (6d12) poison damage and is poisoned until the start of its next turn. On a successful save, the creature takes half as much damage and isn't poisoned. The cloud lasts for 1 minute, until Lohezet ends it early (no action required), or until Lohezet uses this action again. A strong wind disperses the cloud.
reactions:
- name: Noxious Rebuke (3/Day)
  desc: When a creature within 60 feet of Lohezet damages him, Lohezet magically retaliates with a spray of foul, purple mist. The creature must make a DC 17 Constitution saving throw, taking 16 (2d10 + 5) poison damage on a failed save, or half as much damage on a successful one.
---
