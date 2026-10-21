---
statblock: true
layout: Basic 5e Layout
name: Martial Arts Adept
source: VGM
size: Medium
type: humanoid
subtype: any race
alignment: any alignment
ac: 16
hp: 60
hit_dice: 11d8 + 11
speed: 40 ft.
stats:
- 11
- 17
- 13
- 11
- 16
- 10
skillsaves:
- acrobatics: 5
- insight: 5
- stealth: 5
senses: passive Perception 13
languages: any one language (usually Common)
cr: '3'
traits:
- name: Unarmored Defense
  desc: While the adept is wearing no armor and wielding no shield, its AC includes its Wisdom modifier.
actions:
- name: Multiattack
  desc: The adept makes three unarmed strikes or three dart attacks.
- name: Unarmed Strike
  desc: |-
    Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 7 (1d8 + 3) bludgeoning damage. If the target is a creature, the adept can choose one of the following additional effects:
    - The target must succeed on a DC 13 Strength saving throw or drop one item it is holding (adept's choice).
    - The target must succeed on a DC 13 Dexterity saving throw or be knocked prone.
    - The target must succeed on a DC 13 Constitution saving throw or be stunned until the end of the adept's next turn.
- name: Dart
  desc: 'Ranged Weapon Attack: +5 to hit, range 20/60 ft., one target. Hit: 5 (1d4 + 3) piercing damage.'
reactions:
- name: Deflect Missile
  desc: In response to being hit by a ranged weapon attack, the adept deflects the missile. The damage it takes from the attack is reduced by 1d10 + 3. If the damage is reduced to 0, the adept catches the missile if it's small enough to hold in one hand and the adept has a hand free.
---
