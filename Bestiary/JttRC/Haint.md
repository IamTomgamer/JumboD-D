---
statblock: true
layout: Basic 5e Layout
name: Haint
source: JttRC
size: Medium
type: undead
alignment: typically neutral
ac: 12
hp: 75
hit_dice: 10d8 + 30
speed: 30 ft., fly 30 ft. (hover) (hover)
stats:
- 7
- 15
- 17
- 10
- 13
- 17
skillsaves:
- deception: 6
- stealth: 8
damage_resistances: acid; fire; thunder; bludgeoning, piercing, slashing from nonmagical attacks
damage_immunities: cold, necrotic, poison
condition_immunities: charmed, exhaustion, frightened, grappled, paralyzed, petrified, poisoned, prone, restrained
senses: darkvision 60 ft., passive Perception 11
languages: any languages it knew in life
cr: '7'
traits:
- name: Incorporeal Movement
  desc: The haint can move through other creatures and objects as if they were difficult terrain. It takes 5 (1d10) force damage if it ends its turn inside an object.
- name: Unusual Nature
  desc: The haint doesn't require air, food, drink, or sleep.
actions:
- name: Multiattack
  desc: The haint makes two Sorrowful Touch attacks.
- name: Sorrowful Touch
  desc: 'Melee Spell Attack: +6 to hit, reach 5 ft., one creature. Hit: 21 (4d8 + 3) psychic damage.'
- name: Change Shape
  desc: The haint magically assumes the appearance of the Humanoid it was in life, while retaining its game statistics. The assumed appearance ends if the haint is reduced to 0 hit points or uses an action to end it.
bonus_actions:
- name: Shared Sorrow
  desc: |-
    The haint targets one creature it can see within 60 feet of itself that is missing any hit points, sharing its own torment with this pained soul. The target must succeed on a DC 14 Wisdom saving throw or be incapacitated.
    A creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. If a creature's saving throw is successful or the effect ends for it, the creature is immune to the haint's Shared Sorrow for the next 24 hours.
---
