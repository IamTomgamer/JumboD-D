---
statblock: true
layout: Basic 5e Layout
name: Oracle of Strixhaven
source: SCC
size: Medium
type: humanoid
subtype: human, wizard
alignment: neutral good
ac: 12
hp: 150
hit_dice: 20d8 + 60
speed: 30 ft., fly 15 ft. (hover) (hover)
stats:
- 12
- 15
- 16
- 21
- 20
- 18
saves:
- con: 8
- int: 10
- wis: 10
- cha: 9
skillsaves:
- arcana: 15
- insight: 15
- investigation: 15
- nature: 10
- perception: 10
condition_immunities: charmed, frightened
senses: passive Perception 20
languages: all
cr: '15'
traits:
- name: Legendary Resistance (3/Day)
  desc: If the Oracle fails a saving throw, she can choose to succeed instead.
- name: Spellcasting
  desc: |-
    The Oracle casts one of the following spells, requiring no material components and using Intelligence as the spellcasting ability (spell save DC 18):
    At will: detect magic
    2/day each: dispel magic, mage armor, remove curse, sending
    1/day each: power word stun, scrying (as an action), wall of force
actions:
- name: Multiattack
  desc: The Oracle makes two Magic Flare attacks. She can also use Paradoxy, if available.
- name: Magic Flare
  desc: 'Melee or Ranged Spell Attack: +10 to hit, reach 5 ft. or range 60 ft., one target. Hit: 24 (3d12 + 5) force damage.'
- name: Paradoxy (Recharge 4-6)
  desc: Momentary warps in reality appear at three different points the Oracle can see within 120 feet of her. Each creature in a 20-foot-radius sphere centered on each point must make a DC 18 Strength saving throw. On a failed save, a creature takes 33 (6d10) force damage and is pulled up to 15 feet in a straight line toward the center of the sphere. On a successful save, the creature takes half as much damage and isn't pulled. A creature caught in the area of multiple warps is affected by only one, which the Oracle chooses.
- name: Teleport
  desc: The Oracle teleports, along with any equipment she is wearing or carrying, to an unoccupied space she can see within 60 feet of herself.
legendary_actions:
- name: Vector Shift
  desc: The Oracle teleports one creature she can see within 60 feet of herself, along with any equipment it is wearing or carrying, to an unoccupied space within 30 feet of herself. An unwilling target must succeed on a DC 18 Charisma saving throw to avoid the effect.
- name: Spellcasting (Costs 2 Actions)
  desc: The Oracle uses Spellcasting.
- name: Vortex Jaunt (Costs 2 Actions)
  desc: The Oracle uses Teleport, and immediately after she disappears, each creature within 30 feet of the space she left must succeed on a DC 18 Constitution saving throw or take 16 (3d10) force damage.
legendary_description: The oracle of strixhaven can take 3 legendary actions, choosing from the options below. Only one legendary action option can be used at a time and only at the end of another creature's turn. The oracle of strixhaven regains spent legendary actions at the start of its turn.
---
