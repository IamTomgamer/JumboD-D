---
statblock: true
layout: Basic 5e Layout
name: Undying Councilor
source: ERLW
size: Medium
type: undead
alignment: neutral good
ac: 17 (natural armor)
hp: 104
hit_dice: 16d8 + 32
speed: 30 ft.
stats:
- 16
- 10
- 14
- 17
- 21
- 16
saves:
- con: 6
- int: 7
- wis: 9
skillsaves:
- arcana: 7
- history: 11
- insight: 9
- perception: 9
- religion: 7
damage_vulnerabilities: necrotic
damage_immunities: poison, radiant
condition_immunities: charmed, exhaustion, frightened, paralyzed, poisoned
senses: darkvision 120 ft., passive Perception 19
languages: Common, Elvish
cr: '10'
traits:
- name: Aura of Radiance
  desc: The councilor magically sheds bright light in a 15-foot radius and dim light for an additional 15 feet. The councilor can extinguish or restore this light as a bonus action. If the bright light overlaps with an area of darkness created by a spell of 3rd level or lower, the spell that created that darkness is dispelled.
- name: Magic Resistance
  desc: The councilor has advantage on saving throws against spells and other magical effects.
- name: Spellcasting
  desc: |-
    The councilor is a 13th-level spellcaster. Its spellcasting ability is Wisdom (spell save DC 17, +9 to hit with spell attacks). It has the following cleric spells prepared:
    Cantrips (at will): guidance, mending, sacred flame, spare the dying, thaumaturgy
    1st level (4 slots): bless, command, create or destroy water
    2nd level (3 slots): augury, calm emotions, hold person
    3rd level (3 slots): daylight, dispel magic, spirit guardians
    4th level (3 slots): banishment, divination, guardian of faith
    5th level (2 slots): dispel evil and good, flame strike (see "Actions" below), scrying
    6th level (1 slot): forbiddance, planar ally
    7th level (1 slot): plane shift
actions:
- name: Multiattack
  desc: The councilor makes two Radiant Touch attacks.
- name: Radiant Touch
  desc: 'Melee Spell Attack: +9 to hit, reach 5 ft., one target. Hit: 15 (3d6 + 5) radiant damage.'
- name: Healing Touch (3/Day)
  desc: The councilor touches another creature. The target magically regains 18 (3d8 + 5) hit points and is freed from one curse afflicting it (councilor's choice).
- name: Flame Strike (5th-Level Spell; Requires a Spell Slot)
  desc: The councilor chooses a point it can see within 60 feet of it. Each creature in a 10-foot-radius, 40-foot-high cylinder centered on that point must make a DC 17 Dexterity saving throw. A creature takes 14 (4d6) fire damage and 14 (4d6) radiant damage on a failed save, or half as much damage on a successful one. If the councilor casts this spell using a spell slot of 6th level or higher, the fire damage or the radiant damage (its choice) increases by 1d6 for each slot level above 5th.
legendary_actions:
- name: Touch
  desc: The councilor makes one attack with its Radiant Touch.
- name: Shimmering Aura (Costs 2 Actions)
  desc: The councilor channels positive energy into its Aura of Radiance. Until the end of the councilor's next turn, it sheds bright light in a 30-foot radius and dim light for an additional 30 feet. Any creature that starts its turn in the bright light must succeed on a DC 17 Constitution saving throw or be blinded until the end of the councilor's next turn.
legendary_description: The undying councilor can take 2 legendary actions, choosing from the options below. Only one legendary action option can be used at a time and only at the end of another creature's turn. The undying councilor regains spent legendary actions at the start of its turn.
---
