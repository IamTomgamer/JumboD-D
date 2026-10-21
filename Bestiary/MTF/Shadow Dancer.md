---
statblock: true
layout: Basic 5e Layout
name: Shadow Dancer
source: MTF
size: Medium
type: humanoid
subtype: elf
alignment: neutral
ac: 15 (studded leather)
hp: 71
hit_dice: 13d8 + 13
speed: 30 ft.
stats:
- 12
- 16
- 13
- 11
- 12
- 12
saves:
- dex: 6
- cha: 4
skillsaves:
- stealth: 6
damage_resistances: necrotic
condition_immunities: charmed, exhaustion
senses: darkvision 60 ft., passive Perception 11
languages: Common, Elvish
cr: '7'
traits:
- name: Fey Ancestry
  desc: The shadow dancer has advantage on saving throws against being charmed, and magic can't put it to sleep.
- name: Shadow Jump
  desc: As a bonus action, the shadow dancer can teleport up to 30 feet to an unoccupied space it can see. Both the space it teleports from and the space it teleports to must be in dim light or darkness. The shadow dancer can use this ability between the weapon attacks of another action it takes.
actions:
- name: Multiattack
  desc: The shadow dancer makes three spiked chain attacks.
- name: Spiked Chain
  desc: |-
    Melee Weapon Attack: +6 to hit, reach 10 ft., one target. Hit: 10 (2d6 + 3) piercing damage, and the target must succeed on a DC 14 Dexterity saving throw or suffer one additional effect of the shadow dancer's choice:
    - The target is grappled (escape DC 14) if it is a Medium or smaller creature. Until the grapple ends, the target is restrained, and the shadow dancer can't grapple another target.
    - The target is knocked prone.
    - The target takes 22 (4d10) necrotic damage.
---
