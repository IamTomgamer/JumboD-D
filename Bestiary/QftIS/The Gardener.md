---
statblock: true
layout: Basic 5e Layout
name: The Gardener
source: QftIS
size: Medium
type: fey
subtype: archfey, druid
alignment: neutral good
ac: 17 (natural armor)
hp: 209
hit_dice: 22d8 + 110
speed: 30 ft.
stats:
- 21
- 16
- 20
- 17
- 20
- 18
saves:
- dex: 7
- con: 9
- wis: 9
- cha: 8
skillsaves:
- insight: 9
- nature: 11
- perception: 9
- survival: 13
damage_resistances: cold, fire
damage_immunities: poison
condition_immunities: charmed, frightened, poisoned
senses: truesight 120 ft., passive Perception 19
languages: Common, Druidic, Elvish, Sylvan
cr: '12'
traits:
- name: Fey Rebirth
  desc: If the Gardener dies in the Eternal Garden, they revive with all their hit points 1d4 days later in a safe location within the garden.
- name: Legendary Resistance (3/Day)
  desc: If the Gardener fails a saving throw, they can choose to succeed instead.
- name: Unfettered Steps
  desc: The Gardener is unaffected by difficult terrain.
- name: Spellcasting
  desc: |-
    The Gardener casts one of the following spells, requiring no material components and using Wisdom as the spellcasting ability (spell save DC 17):
    At will: Druidcraft, Speak with Animals, Speak with Plants
    2/day each: Awaken (as an action), Goodberry, Plant Growth (as an action only)
    1/day each: Heroes' Feast (as an action), Teleport
actions:
- name: Multiattack
  desc: The Gardener makes two Vine attacks and can use Breath of Tranquility if available.
- name: Vine
  desc: 'Melee Weapon Attack: +9 to hit, reach 10 ft., one target. Hit: 11 (1d12 + 5) bludgeoning damage plus 9 (2d8) psychic damage, and if the target is a Large or smaller creature, the vine wraps around the target, and the target has the grappled condition (escape DC 17). The vine vanishes when the target is no longer grappled, or when the Gardener wills it to (no action required). A creature reduced to 0 hit points by the vine has the unconscious condition but is stable instead of dying.'
- name: Breath of Tranquility (Recharge 5-6)
  desc: The Gardener exhales soporific vapor in a 30-foot cone. Each creature in that area must succeed on a DC 17 Constitution saving throw or have the poisoned condition. A poisoned creature must repeat the saving throw at the end of its next turn. On a failed save, it has the unconscious condition, and on a successful save, the effect ends on it. An unconscious creature is no longer poisoned and remains unconscious for 1 hour, until it takes damage, or until a creature uses an action to shake it awake.
reactions:
- name: Pacification
  desc: When a creature within 120 feet of the Gardener damages the Gardener, that creature takes 10 (3d6) psychic damage, and the Gardener teleports, along with anything they are wearing or carrying, to an unoccupied space they can see within 15 feet. A creature reduced to 0 hit points by the psychic damage has the unconscious condition and is stable instead of dying.
- name: Spell Refuge
  desc: When the Gardener or a creature within 30 feet of the Gardener takes damage from a spell, the Gardener chooses up to 5 creatures within 30 feet of themself. The Gardener and the chosen creatures have resistance to all damage from the triggering spell.
---
