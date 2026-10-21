---
statblock: true
layout: Basic 5e Layout
name: Warrior
source: DC
size: Medium
type: humanoid
alignment: ''
ac: 21 (plate, shield)
hp: 78
hit_dice: 12d8 + 24
speed: 30 ft.
stats:
- 18
- 14
- 14
- 10
- 12
- 10
saves:
- con: 6
skillsaves:
- athletics: 8
- perception: 5
- survival: 5
senses: passive Perception 15
languages: Common, plus one of your choice
cr: ''
traits:
- name: Battle Readiness
  desc: The warrior has advantage on initiative rolls.
- name: Improved Critical
  desc: The warrior's attack rolls score a critical hit on a roll of 19 or 20 on the d20.
- name: Improved Defense
  desc: The warrior's AC increases by 1.
- name: Indomitable (1/Day)
  desc: The warrior can reroll a saving throw that it fails, but it must use the new result.
- name: Martial Role
  desc: |-
    The warrior has one of the following traits of your choice:
    - **Attacker** The warrior gains a +2 bonus to attack rolls.
    - **Defender** The warrior gains the Protection reaction below.
- name: Second Wind (Recharges after a Short or Long Rest)
  desc: The warrior can use a bonus action on its turn to regain hit points equal to 1d10 + its level.
actions:
- name: Extra Attack
  desc: The warrior can attack three times, instead of once, whenever it takes the attack action on its turn.
- name: Longsword
  desc: 'Melee Weapon Attack: +8 to hit, reach 5 ft., one target. Hit: 8 (1d8 + 4) slashing damage, or 9 (1d10 + 4) slashing damage if used with two hands.'
- name: Longbow
  desc: 'Ranged Weapon Attack: +6 to hit, range 150/600 ft., one target. Hit: 6 (1d8 + 2) piercing damage.'
reactions:
- name: Protection (Defender Only)
  desc: When a creature the warrior can see attacks a target other than the warrior that is within 5 feet of the warrior, the warrior can use their reaction to impose disadvantage on the attack roll. The warrior must be wielding a shield.
---
