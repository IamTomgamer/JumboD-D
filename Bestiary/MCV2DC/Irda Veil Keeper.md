---
statblock: true
layout: Basic 5e Layout
name: Irda Veil Keeper
source: MCV2DC
size: Medium
type: giant
subtype: sorcerer
alignment: any alignment
ac: 13
hp: 49
hit_dice: 9d8 + 9
speed: 30 ft.
stats:
- 9
- 16
- 13
- 14
- 17
- 19
saves:
- int: 4
- wis: 5
- cha: 6
skillsaves:
- arcana: 4
- insight: 7
- perception: 7
condition_immunities: charmed, frightened
senses: darkvision 60 ft., truesight 5 ft., passive Perception 17
languages: Common, Giant, Sylvan
cr: '4'
traits:
- name: Spellcasting
  desc: |-
    The veil keeper casts one of the following spells, requiring no material components and using Charisma as the spellcasting ability (spell save DC 14):
    At will: dancing lights, minor illusion
    1/day: hallucinatory terrain (as an action)
    2/day each: invisibility, major image, phantasmal force
actions:
- name: Multiattack
  desc: The veil keeper uses Augment Physicality, if available, and makes two Mirage Flare attacks.
- name: Mirage Flare
  desc: 'Melee or Ranged Spell Attack: +6 to hit, reach 5 ft. or range 60 ft., one target. Hit: 11 (2d6 + 4) radiant damage, and the target must succeed on a DC 14 Wisdom saving throw or be charmed by the veil keeper until the start of the veil keeper''s next turn. While charmed in this way, a creature is incapacitated as it is beset by hypnotic, illusory visions.'
- name: Augment Physicality (1/Day)
  desc: For 1 minute, the veil keeper magically obscures it location, heightens its physical ability, and increases in size, along with anything it is wearing or carrying. While the veil keeper is augmented, attack rolls against it have disadvantage, it is Large, and it makes Strength and Dexterity saving throws with advantage. If the veil keeper lacks the room to become Large, it attains the maximum size possible in the space available. These augmentations end if the veil keeper is incapacitated.
- name: Change Shape (3/Day)
  desc: The veil keeper magically transforms to look and feel like a Medium Humanoid it has seen. Any equipment the veil keeper is wearing or carrying isn't transformed, and the veil keeper's statistics don't change. The veil keeper reverts to its true form if the veil keeper is reduced to 0 hit points or if the veil keeper uses an action to end the transformation.
reactions:
- name: Obscuring Mist
  desc: If a creature that the veil keeper can see within 30 feet of itself is targeted by an attack, the veil keeper surrounds the creature with illusory mist, granting the creature 3 until the start of the veil keeper's next turn.
---
