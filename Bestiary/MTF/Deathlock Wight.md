---
statblock: true
layout: Basic 5e Layout
name: Deathlock Wight
source: MTF
size: Medium
type: undead
alignment: lawful evil
ac: 12, 15 with mage armor
hp: 37
hit_dice: 5d8 + 15
speed: 30 ft.
stats:
- 11
- 14
- 16
- 12
- 14
- 16
saves:
- wis: 4
skillsaves:
- arcana: 3
- perception: 4
damage_resistances: necrotic; bludgeoning, piercing, slashing from nonmagical attacks
damage_immunities: poison
condition_immunities: exhaustion, poisoned
senses: darkvision 60 ft., passive Perception 14
languages: the languages it knew in life
cr: '3'
traits:
- name: Sunlight Sensitivity
  desc: While in sunlight, the wight has disadvantage on attack rolls, as well as on Wisdom (Perception) checks that rely on sight.
- name: Innate Spellcasting
  desc: |-
    The wight's innate spellcasting ability is Charisma (spell save DC 13). It can innately cast the following spells, requiring no verbal or material components:
    At will: detect magic, disguise self, mage armor
    1/day each: fear, hold person, misty step
actions:
- name: Multiattack
  desc: The wight attacks twice with Grave Bolt.
- name: Grave Bolt
  desc: 'Ranged Spell Attack: +5 to hit, range 120 ft., one target. Hit: 7 (1d8 + 3) necrotic damage.'
- name: Life Drain
  desc: |-
    Melee Weapon Attack: +4 to hit, reach 5 ft., one creature. Hit: 9 (2d6 + 2) necrotic damage. The target must succeed on a DC 13 Constitution saving throw or its hit point maximum is reduced by an amount equal to the damage taken. This reduction lasts until the target finishes a long rest. The target dies if this effect reduces its hit point maximum to 0.
    A humanoid slain by this attack rises 24 hours later as a zombie under the wight's control, unless the humanoid is restored to life or its body is destroyed. The wight can have no more than twelve zombies under its control at one time.
---
