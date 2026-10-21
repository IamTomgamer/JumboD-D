---
statblock: true
layout: Basic 5e Layout
name: Mummy Lord
source: XMM
size: Small or Medium
type: undead
subtype: cleric
alignment: lawful evil
ac: 17
hp: 187
hit_dice: 25d8 + 75
speed: 30 ft.
stats:
- 18
- 10
- 17
- 11
- 19
- 16
saves:
- int: 5
- wis: 9
skillsaves:
- history: 5
- perception: 9
- religion: 5
damage_vulnerabilities: fire
damage_immunities: necrotic, poison
condition_immunities: charmed, exhaustion, frightened, paralyzed, poisoned
senses: Truesight 60 ft., passive Perception 19
languages: Common plus three other languages
cr: '15'
traits:
- name: Legendary Resistance (3/Day, or 4/Day in Lair)
  desc: If the mummy fails a saving throw, it can choose to succeed instead.
- name: Magic Resistance
  desc: The mummy has Advantage on saving throws against spells and other magical effects.
- name: Undead Restoration
  desc: If destroyed, the mummy gains a new body in 24 hours if its heart is intact, reviving with all its Hit Points. The new body appears in an unoccupied space within the mummy's lair. The heart is a Tiny object that has AC 17, HP 10, and Immunity to all damage except Fire.
- name: Spellcasting
  desc: |-
    The mummy casts one of the following spells, requiring no Material components and using Wisdom as the spellcasting ability (spell save DC 17, +9 to hit with spell attacks):
    At will: Dispel Magic, Thaumaturgy
    1/day each: Animate Dead, Harm, Insect Plague (level 7 version)
- name: Dread Command
  desc: The mummy casts Command (level 2 version), using the same spellcasting ability as Spellcasting. The mummy can't take this action again until the start of its next turn.
actions:
- name: Multiattack
  desc: The mummy makes one Rotting Fist or Channel Negative Energy attack, and it uses Dreadful Glare.
- name: Rotting Fist
  desc: 'm +9, reach 5 ft. Hit: 15 (2d10 + 4) Bludgeoning damage plus 10 (3d6) Necrotic damage. If the target is a creature, it is cursed. While cursed, the target can''t regain Hit Points, it gains no benefit from finishing a Long Rest, and its Hit Point maximum decreases by 10 (3d6) every 24 hours that elapse. A creature dies and turns to dust if reduced to 0 Hit Points by this attack.'
- name: Channel Negative Energy
  desc: 'r +9, range 60 ft. Hit: 25 (6d6 + 4) Necrotic damage.'
- name: Dreadful Glare
  desc: wis DC 17, one creature the mummy can see within 60 feet.  25 (6d6 + 4) Psychic damage, and the target has the Paralyzed condition until the end of the mummy's next turn.
reactions:
- name: Whirlwind of Sand
  desc: ' The mummy is hit by an attack roll.  The mummy adds 2 to its AC against the attack, possibly causing the attack to miss, and the mummy teleports up to 60 feet to an unoccupied space it can see. Each creature of its choice that it can see within 5 feet of its destination space has the Blinded condition until the end of the mummy''s next turn.'
legendary_actions:
- name: Glare
  desc: The mummy uses Dreadful Glare. The mummy can't take this action again until the start of its next turn.
- name: Necrotic Strike
  desc: The mummy makes one Rotting Fist or Channel Negative Energy attack.
legendary_description: The mummy lord can take 3 legendary actions, choosing from the options below. Only one legendary action option can be used at a time and only at the end of another creature's turn. The mummy lord regains spent legendary actions at the start of its turn.
---
