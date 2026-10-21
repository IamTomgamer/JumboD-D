---
statblock: true
layout: Basic 5e Layout
name: Draconic Spirit
source: XPHB
size: Large
type: dragon
alignment: neutral
ac: 14 + the spell's level
hp: 50 + 10 for each spell level above 5
speed: 30 ft., fly 60 ft., swim 30 ft.
stats:
- 19
- 14
- 17
- 10
- 14
- 14
damage_resistances: acid, cold, fire, lightning, poison
condition_immunities: charmed, frightened, poisoned
senses: Blindsight 30 ft., Darkvision 60 ft., passive Perception 12
languages: Draconic, understands the languages you know
cr: ''
traits:
- name: Shared Resistances
  desc: When you summon the spirit, choose one of its Resistances. You have Resistance to the chosen damage type until the spell ends.
actions:
- name: Multiattack
  desc: The spirit makes a number of Rend attacks equal to half the spell's level (round down), and it uses Breath Weapon.
- name: Rend
  desc: 'Melee Attack: Bonus equals your spell attack modifier, reach 10 feet. Hit: 1d6 + 4 + summonSpellLevel Piercing damage.'
- name: Breath Weapon
  desc: dex DC equals your spell save DC, each creature in a 30-foot Cone.  2d6 damage of a type this spirit has Resistance to (your choice when you cast the spell).  Half damage.
---
