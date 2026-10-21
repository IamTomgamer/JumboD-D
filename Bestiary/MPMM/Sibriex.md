---
statblock: true
layout: Basic 5e Layout
name: Sibriex
source: MPMM
size: Huge
type: fiend
subtype: demon
alignment: Typically chaotic evil
ac: 19 (natural armor)
hp: 150
hit_dice: 12d12 + 72
speed: 0 ft., fly 20 ft. (hover) (hover)
stats:
- 10
- 3
- 23
- 25
- 24
- 25
saves:
- int: 13
- cha: 13
skillsaves:
- arcana: 13
- history: 13
- perception: 13
damage_resistances: cold; fire; lightning; bludgeoning, piercing, slashing from nonmagical attacks
damage_immunities: poison
condition_immunities: poisoned
senses: truesight 120 ft., passive Perception 23
languages: all, telepathy 120 ft.
cr: '18'
traits:
- name: Contamination
  desc: The sibriex emits an aura of corruption 30 feet in every direction. Vegetation withers in the aura, and the ground in the aura is 3 for other creatures. Any creature that starts its turn in the aura must succeed on a DC 20 Constitution saving throw or take 14 (4d6) poison damage. A creature that succeeds on the save is immune to this sibriex's Contamination for 24 hours.
- name: Legendary Resistance (3/Day)
  desc: If the sibriex fails a saving throw, it can choose to succeed instead.
- name: Magic Resistance
  desc: The sibriex has advantage on saving throws against spells and other magical effects.
- name: Spellcasting
  desc: |-
    The sibriex casts one of the following spells, requiring no material components and using Charisma as the spellcasting ability (spell save DC 21):
    At will: command, dispel magic, hold monster
    1/day: feeblemind
actions:
- name: Multiattack
  desc: The sibriex makes three Chain attacks, and it uses Squirt Bile.
- name: Chain
  desc: 'Melee Weapon Attack: +13 to hit, reach 15 ft., one target. Hit: 20 (2d12 + 7) force damage.'
- name: Squirt Bile
  desc: The sibriex targets one creature it can see within 120 feet of it. The target must succeed on a DC 20 Dexterity saving throw or take 31 (9d6) acid damage.
- name: Warp Creature
  desc: The sibriex targets up to three creatures it can see within 120 feet of it. Each target must make a DC 20 Constitution saving throw. On a successful save, a creature becomes immune to this sibriex's Warp Creature. On a failed save, the target is poisoned, which causes it to also gain 1 level of exhaustion. While poisoned in this way, the target must repeat the saving throw at the start of each of its turns. Three successful saves against the poison end it, and ending the poison removes any levels of exhaustion caused by it. Each failed save causes the target to gain another level of exhaustion. Once the target reaches 6 levels of exhaustion, it dies and instantly transforms into a living manes under the sibriex's control. The transformation of the body can be undone only by a wish spell.
legendary_actions:
- name: Cast a Spell
  desc: The sibriex uses Spellcasting.
- name: Spray Bile
  desc: The sibriex uses Squirt Bile.
- name: Warp (Costs 2 Actions)
  desc: The sibriex uses Warp Creature.
legendary_description: The sibriex can take 3 legendary actions, choosing from the options below. Only one legendary action option can be used at a time and only at the end of another creature's turn. The sibriex regains spent legendary actions at the start of its turn.
---
