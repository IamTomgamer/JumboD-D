---
statblock: true
layout: Basic 5e Layout
name: Nauk
source: MaBJoV
size: Medium
type: humanoid
subtype: half-orc
alignment: lawful evil
ac: 18 (plate)
hp: 170
hit_dice: 20d8 + 80
speed: 30 ft.
stats:
- 20
- 12
- 18
- 10
- 12
- 14
saves:
- str: 9
- dex: 5
- con: 8
skillsaves:
- intimidation: 10
- persuasion: 6
senses: passive Perception 11
languages: Common, Goblin, Orc, Undercommon
cr: '9'
traits:
- name: Potion Mishap
  desc: |-
    When Nauk uses the Imbibe Potion action more than once in an hour, roll 1d4 for what happens:
    - 1. The potion works normally.
    - 2. The potion works normally. In addition, Nauk turns invisible for 1 minute or until Nauk attacks or casts a spell.
    - 3. The potion has no effect.
    - 4. Instead of the normal effect, the potion causes fire to explode out of Nauk's mouth in a 15 foot cone. Nauk and any creature in the cone take 21 (6d6) fire damage.
- name: Relentless
  desc: When Nauk is reduced to 0 hit points but not killed outright, he can drop to 1 hit point instead. He can't use this feature again for 24 hours
- name: Special Items
  desc: Nauk wears adamantine plate armor. He wields a +1 maul and a +1 heavy crossbow which is already factored into his stats. He has 2 potions of resistance (cold), 2 potions of resistance (fire), 2 potions of resistance (lightning). He has 2 potions of heroism and 4 potions of superior healing.
actions:
- name: Multiattack
  desc: Nauk makes three Magic Maul attacks. Nauk may substitute one of those attacks for the Imbibe Potion action.
- name: Magic Maul
  desc: 'Melee Weapon Attack: +10 to hit, reach 5 ft., one creature. Hit: 13 (2d6 + 6) bludgeoning damage.'
- name: Heavy Crossbow
  desc: 'Ranged Weapon Attack: +6 to hit, ranged 100/400 ft., one target. Hit: 7 (1d10 + 2) piercing damage.'
- name: Imbibe Potion
  desc: |-
    Nauk drinks a potion from the following list:
    - Potion of heroism: Nauk gains 10 temporary hit points for 1 hour. For the same duration, Nauk is under the effect of the bless spell (no concentration required).
    - Potion of resistance: Nauk gains resistance from one damage type for 1 hour. Nauk chooses from one of these damage types: cold, fire, lightning.
    - Potion of superior healing: Nauk regains 28 hit points.
reactions:
- name: Parry
  desc: Nauk adds 4 to his AC against one melee attack that would hit him. To do so, Nauk must see the attacker and be wielding a melee weapon.
---
