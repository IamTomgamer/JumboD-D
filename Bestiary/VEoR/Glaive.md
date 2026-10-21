---
statblock: true
layout: Basic 5e Layout
name: Glaive
source: VEoR
size: Medium
type: construct
subtype: warforged
alignment: chaotic evil
ac: 16 (natural armor)
hp: 187
hit_dice: 22d8 + 88
speed: 30 ft. (50 ft. with overdrive)
stats:
- 20
- 16
- 19
- 11
- 16
- 9
saves:
- str: 9
- dex: 7
- wis: 7
skillsaves:
- athletics: 9
- perception: 7
- stealth: 7
- survival: 7
damage_resistances: poison
condition_immunities: charmed, exhaustion, frightened, poisoned
senses: passive Perception 17
languages: Common
cr: '11'
traits:
- name: Heatsink
  desc: When Glaive takes cold damage, her Overdrive immediately recharges.
- name: Pack Tactics
  desc: Glaive has advantage on attack rolls if at least one ally is within 5 feet of the creature she's attacking and the ally doesn't have the incapacitated condition.
actions:
- name: Multiattack
  desc: Glaive makes two Spiked Glaive attacks and two Serrated Bolt attacks.
- name: Spiked Glaive
  desc: 'Melee Weapon Attack: +9 to hit, reach 10 ft., one target. Hit: 10 (1d10 + 5) piercing or slashing damage, or 14 (1d10 + 9) piercing or slashing damage if Glaive is in overdrive.'
- name: Serrated Bolt
  desc: 'Ranged Weapon Attack: +7 to hit, range 60 ft., one target. Hit: 13 (3d6 + 3) piercing damage. If Glaive has advantage on the attack roll, the serrated bolt lodges in the target, and the target''s speed is reduced by 10 feet until the serrated bolt is removed. A target''s speed can be reduced by only one serrated bolt at a time. A creature can use its action to remove a serrated bolt lodged in itself or another creature within its reach; when the bolt is removed from a creature, that creature takes 5 (2d4) slashing damage.'
bonus_actions:
- name: Overdrive (Recharges after Finishing a Short or Long Rest)
  desc: |-
    Glaive enters a state of overdrive that lasts for 1 minute or until she has the incapacitated condition. While in overdrive, Glaive gains the following benefits:
    - Glaive has advantage on Strength checks and Strength saving throws.
    - When Glaive makes a melee weapon attack, she gains a +4 bonus to the damage roll.
    - Glaive's speed increases to 50 feet.
reactions:
- name: Self-Preservation
  desc: In response to being hit by a weapon attack, Glaive reduces the damage by 11 (2d10).
---
