---
statblock: true
layout: Basic 5e Layout
name: Enchanter
source: VGM
size: Medium
type: humanoid
subtype: any race
alignment: any alignment
ac: 12, 15 with mage armor
hp: 40
hit_dice: 9d8
speed: 30 ft.
stats:
- 9
- 14
- 11
- 17
- 12
- 11
saves:
- int: 6
- wis: 4
skillsaves:
- arcana: 6
- history: 6
senses: passive Perception 11
languages: any four languages
cr: '5'
traits:
- name: Spellcasting
  desc: |-
    The enchanter is a 9th-level spellcaster. Its spellcasting ability is Intelligence (spell save DC 14, +6 to hit with spell attacks). The enchanter has the following wizard spells prepared:
    Cantrips (at will): friends, mage hand, mending, message
    1st level (4 slots): charm person*, mage armor, magic missile
    2nd level (3 slots): hold person*, invisibility, suggestion*
    3rd level (3 slots): fireball, haste, tongues
    4th level (3 slots): dominate beast*, stoneskin
    5th level (2 slots): hold monster*
    *Enchantment spell of 1st level or higher
actions:
- name: Quarterstaff
  desc: 'Melee Weapon Attack: +2 to hit, reach 5 ft., one target. Hit: 2 (1d6 - 1) bludgeoning damage, or 3 (1d8 - 1) bludgeoning damage if used with two hands.'
reactions:
- name: Instinctive Charm (Recharges after the Enchanter Casts an Enchantment Spell of 1st level or Higher)
  desc: |-
    The enchanter tries to magically divert an attack made against it, provided that the attacker is within 30 feet of it and visible to it. The enchanter must decide to do so before the attack hits or misses.
    The attacker must make a DC 14 Wisdom saving throw. On a failed save, the attacker targets the creature closest to it, other than the enchanter or itself. If multiple creatures are closest, the attacker chooses which one to target.
---
