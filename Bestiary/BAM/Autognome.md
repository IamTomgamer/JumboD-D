---
statblock: true
layout: Basic 5e Layout
name: Autognome
source: BAM
size: Small
type: construct
alignment: any alignment
ac: 16 (natural armor)
hp: 39
hit_dice: 6d6 + 18
speed: 20 ft.
stats:
- 13
- 6
- 16
- 4
- 11
- 6
saves:
- con: 5
- wis: 2
- cha: 0
damage_immunities: poison
condition_immunities: paralyzed, petrified, poisoned
senses: darkvision 60 ft., passive Perception 10
languages: Common, Gnomish
cr: '2'
traits:
- name: Malfunction
  desc: |-
    Whenever the autognome takes 15 damage or more from a single source and isn't reduced to 0 hit points by that damage, roll a d20 to determine if it suffers a malfunction:
    - **1-10: "All Fine Here!"** No malfunction occurs.
    - **11-12: "My Mind Is Going. I Can Feel It."** The autognome is incapacitated for 1 minute.
    - **13-14: "You've Disarmed Me!"** One of the autognome's arms falls off, reducing the number of Shock attacks it can make by 1 until a creature uses an action to reattach the arm.
    - **15-16: "Who Turned Out the Lights?"** The autognome's head falls off and deactivates, causing the autognome to be blinded and deafened until a creature uses an action to reattach the head, which reactivates it.
    - **17-20: "Have a Magical Day!"** The autognome explodes and is destroyed. Each creature within 20 feet of the exploding autognome must make a DC 11 Dexterity saving throw, taking 22 (4d10) slashing damage on a failed save, or half as much damage on a successful one.
    - **Unusual Nature** The autognome doesn't require air, food, drink, or sleep.
actions:
- name: Multiattack
  desc: The autognome makes two Shock attacks.
- name: Shock
  desc: 'Melee or Ranged Weapon Attack: +3 to hit, reach 5 ft. or range 60 ft., one target. Hit: 7 (2d6) lightning damage.'
---
