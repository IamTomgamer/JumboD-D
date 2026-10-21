---
statblock: true
layout: Basic 5e Layout
name: Bard
source: MPMM
size: Medium
type: humanoid
alignment: any alignment
ac: 15 (chain shirt)
hp: 44
hit_dice: 8d8 + 8
speed: 30 ft.
stats:
- 11
- 14
- 12
- 10
- 13
- 14
saves:
- dex: 4
- wis: 3
skillsaves:
- acrobatics: 4
- perception: 5
- performance: 6
senses: passive Perception 15
languages: any two languages
cr: '2'
traits:
- name: Spellcasting
  desc: |-
    The bard casts one of the following spells, using Charisma as the spellcasting ability (spell save DC 12):
    At will: dancing lights, mage hand, prestidigitation
    1/day each: charm person, invisibility, sleep
actions:
- name: Multiattack
  desc: The bard makes two Shortsword or Shortbow attacks. It can replace one attack with a use of Spellcasting.
- name: Shortsword
  desc: 'Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 5 (1d6 + 2) piercing damage.'
- name: Shortbow
  desc: 'Ranged Weapon Attack: +4 to hit, range 80/320 ft., one target. Hit: 5 (1d6 + 2) piercing damage.'
- name: Cacophony (Recharge 4-6)
  desc: Each creature in a 15-foot cube originating from the bard must make a DC 12 Constitution saving throw. On a failed save, a creature takes 9 (2d8) thunder damage and is pushed up to 10 feet away from the bard. On a successful save, a creature takes half as much damage and isn't pushed.
bonus_actions:
- name: Taunt (2/Day)
  desc: The bard targets one creature within 30 feet of it. If the target can hear the bard, the target must succeed on a DC 12 Charisma saving throw or have disadvantage on ability checks, attack rolls, and saving throws until the start of the bard's next turn.
---
