---
statblock: true
layout: Basic 5e Layout
name: Deathlock Mastermind
source: MTF
size: Medium
type: undead
alignment: lawful evil
ac: 13, 16 with mage armor
hp: 110
hit_dice: 20d8 + 20
speed: 30 ft.
stats:
- 11
- 16
- 12
- 15
- 12
- 17
saves:
- int: 5
- cha: 6
skillsaves:
- arcana: 5
- history: 5
- perception: 4
damage_resistances: necrotic; bludgeoning, piercing, slashing from nonmagical attacks that aren't silvered
damage_immunities: poison
condition_immunities: exhaustion, poisoned
senses: darkvision 120 ft. (including magical darkness), passive Perception 14
languages: the languages it knew in life
cr: '8'
traits:
- name: Turn Resistance
  desc: The deathlock has advantage on saving throws against any effect that turns undead.
- name: Innate Spellcasting
  desc: |-
    The deathlock's innate spellcasting ability is Charisma (spell save DC 14). It can innately cast the following spells, requiring no material components:
    At will: detect magic, disguise self, mage armor
- name: Spellcasting
  desc: |-
    The deathlock is a 10th-level spellcaster. Its spellcasting ability is Charisma (spell save DC 14, +6 to hit with spell attacks). It regains its expended spell slots when it finishes a short or long rest. It knows the following warlock spells:
    Cantrips (at will): chill touch, mage hand, minor illusion, poison spray
    5th level (2 slots): arms of Hadar, blight, counterspell, crown of madness, darkness, dimension door, dispel magic, fly, hold monster, invisibility
actions:
- name: Deathly Claw
  desc: 'Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 13 (3d6 + 3) necrotic damage.'
- name: Grave Bolts
  desc: 'Ranged Spell Attack: +6 to hit, range 120 ft., one or two targets. Hit: 18 (4d8) necrotic damage. If the target is Large or smaller, it must succeed on a DC 16 Strength saving throw or become restrained as shadowy tendrils wrap around it for 1 minute. A restrained target can use its action to repeat the saving throw, ending the effect on itself on a success.'
---
