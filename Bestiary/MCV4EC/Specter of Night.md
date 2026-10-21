---
statblock: true
layout: Basic 5e Layout
name: Specter of Night
source: MCV4EC
size: Huge
type: undead
alignment: typically neutral evil
ac: 15 (natural armor)
hp: 142
hit_dice: 15d12 + 45
speed: 60 ft., fly 60 ft.
stats:
- 22
- 18
- 17
- 12
- 13
- 12
saves:
- dex: 8
- wis: 5
skillsaves:
- perception: 5
damage_resistances: necrotic
damage_immunities: poison
condition_immunities: exhaustion, poisoned
senses: darkvision 120 ft., passive Perception 15
languages: understands Common but can't speak
cr: '12'
traits:
- name: Legendary Resistance (3/Day)
  desc: If the specter fails a saving throw, it can choose to succeed instead.
- name: Magic Resistance
  desc: The specter has advantage on saving throws against spells and other magical effects.
actions:
- name: Multiattack
  desc: The specter uses Mournful Keening if available, then makes one Hooves attack and one Reaping Scythe attack.
- name: Hooves
  desc: 'Melee Weapon Attack: +10 to hit, reach 10 ft., one target. Hit: 16 (3d6 + 6) bludgeoning damage plus 28 (8d6) necrotic damage. If the target is a Medium or smaller creature, it must succeed on a DC 18 Strength saving throw or have the prone condition.'
- name: Mournful Keening (Recharge 6)
  desc: |-
    The specter utters a keening wail, calling to those close to death. Each non-Undead creature within 120 feet of the specter must make a DC 15 Constitution saving throw. On a failure, the creature hears the wail and is marked for death.
    A creature marked for death can't regain hit points, has disadvantage on death saving throws, and all attack rolls against it are made with advantage. This effect lasts for 1 minute or until the creature is targeted by a remove curse spell or similar magic.
- name: Reaping Scythe
  desc: 'Melee Weapon Attack: +10 to hit, reach 10 ft., one target. Hit: 12 (1d12 + 6) slashing damage plus 28 (8d6) necrotic damage. If the target is a creature, it must succeed on a DC 15 Constitution saving throw or gain a level of exhaustion.'
---
