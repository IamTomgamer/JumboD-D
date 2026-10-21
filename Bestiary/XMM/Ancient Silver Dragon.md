---
statblock: true
layout: Basic 5e Layout
name: Ancient Silver Dragon
source: XMM
size: Gargantuan
type: dragon
subtype: metallic
alignment: lawful good
ac: 22
hp: 468
hit_dice: 24d20 + 216
speed: 40 ft., fly 80 ft.
stats:
- 30
- 10
- 29
- 18
- 15
- 26
saves:
- dex: 7
- wis: 9
skillsaves:
- history: 11
- perception: 16
- stealth: 7
damage_immunities: cold
senses: Blindsight 60 ft., Darkvision 120 ft., passive Perception 26
languages: Common, Draconic
cr: '23'
traits:
- name: Legendary Resistance (4/Day, or 5/Day in Lair)
  desc: If the dragon fails a saving throw, it can choose to succeed instead.
- name: Spellcasting
  desc: |-
    The dragon casts one of the following spells, requiring no Material components and using Charisma as the spellcasting ability (spell save DC 23, +15 to hit with spell attacks):
    At will: Detect Magic, Hold Monster, Ice Knife (level 2 version), Shapechange (Beast or Humanoid form only, no Temporary Hit Points gained from the spell, and no Concentration or Temporary Hit Points required to maintain the spell)
    1/day each: Control Weather, Ice Storm (level 7 version), Teleport, Zone of Truth
actions:
- name: Multiattack
  desc: The dragon makes three Rend attacks. It can replace one attack with a use of (A) Paralyzing Breath or (B) Spellcasting to cast Ice Knife (level 2 version).
- name: Rend
  desc: 'm +17, reach 15 ft. Hit: 19 (2d8 + 10) Slashing damage plus 9 (2d8) Cold damage.'
- name: Cold Breath (Recharge 5-6)
  desc: con DC 24, each creature in a 90-foot Cone.  67 (15d8) Cold damage.  Half damage.
- name: Paralyzing Breath
  desc: con DC 24, each creature in a 90-foot Cone. 1 The target has the Incapacitated condition until the end of its next turn, when it repeats the save. 2 The target has the Paralyzed condition, and it repeats the save at the end of each of its turns, ending the effect on itself on a success. After 1 minute, it succeeds automatically.
legendary_actions:
- name: Chill
  desc: The dragon uses Spellcasting to cast Hold Monster. The dragon can't take this action again until the start of its next turn.
- name: Cold Gale
  desc: dex DC 23, each creature in a 60-foot-long, 10-foot-wide Line.  14 (4d6) Cold damage, and the target is pushed up to 30 feet straight away from the dragon.  Half damage only.  The dragon can't take this action again until the start of its next turn.
- name: Pounce
  desc: The dragon moves up to half its Speed, and it makes one Rend attack.
legendary_description: The ancient silver dragon can take 3 legendary actions, choosing from the options below. Only one legendary action option can be used at a time and only at the end of another creature's turn. The ancient silver dragon regains spent legendary actions at the start of its turn.
---
