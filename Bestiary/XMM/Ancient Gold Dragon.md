---
statblock: true
layout: Basic 5e Layout
name: Ancient Gold Dragon
source: XMM
size: Gargantuan
type: dragon
subtype: metallic
alignment: lawful good
ac: 22
hp: 546
hit_dice: 28d20 + 252
speed: 40 ft., fly 80 ft., swim 40 ft.
stats:
- 30
- 14
- 29
- 18
- 17
- 28
saves:
- dex: 9
- wis: 10
skillsaves:
- insight: 10
- perception: 17
- persuasion: 16
- stealth: 9
damage_immunities: fire
senses: Blindsight 60 ft., Darkvision 120 ft., passive Perception 27
languages: Common, Draconic
cr: '24'
traits:
- name: Amphibious
  desc: The dragon can breathe air and water.
- name: Legendary Resistance (4/Day, or 5/Day in Lair)
  desc: If the dragon fails a saving throw, it can choose to succeed instead.
- name: Spellcasting
  desc: |-
    The dragon casts one of the following spells, requiring no Material components and using Charisma as the spellcasting ability (spell save DC 24, +16 to hit with spell attacks):
    At will: Detect Magic, Guiding Bolt (level 4 version), Shapechange (Beast or Humanoid form only, no Temporary Hit Points gained from the spell, and no Concentration or Temporary Hit Points required to maintain the spell)
    1/day each: Flame Strike (level 6 version), Word of Recall, Zone of Truth
actions:
- name: Multiattack
  desc: The dragon makes three Rend attacks. It can replace one attack with a use of (A) Spellcasting to cast Guiding Bolt (level 4 version) or (B) Weakening Breath.
- name: Rend
  desc: 'm +17 to hit, reach 15 ft. Hit: 19 (2d8 + 10) Slashing damage plus 9 (2d8) Fire damage.'
- name: Fire Breath (Recharge 5-6)
  desc: dex DC 24, each creature in a 90-foot Cone.  71 (13d10) Fire damage.  Half damage.
- name: Weakening Breath
  desc: str DC 24, each creature that isn't currently affected by this breath in a 90-foot Cone.  The target has Disadvantage on Strength-based D20 Tests and subtracts 5 (1d10) from its damage rolls. It repeats the save at the end of each of its turns, ending the effect on itself on a success. After 1 minute, it succeeds automatically.
legendary_actions:
- name: Banish
  desc: cha DC 24, one creature the dragon can see within 120 feet.  24 (7d6) Force damage, and the target has the Incapacitated condition and is transported to a harmless demiplane until the start of the dragon's next turn, at which point it reappears in an unoccupied space of the dragon's choice within 120 feet of the dragon.  The dragon can't take this action again until the start of its next turn.
- name: Guiding Light
  desc: The dragon uses Spellcasting to cast Guiding Bolt (level 4 version).
- name: Pounce
  desc: The dragon moves up to half its Speed, and it makes one Rend attack.
legendary_description: The ancient gold dragon can take 3 legendary actions, choosing from the options below. Only one legendary action option can be used at a time and only at the end of another creature's turn. The ancient gold dragon regains spent legendary actions at the start of its turn.
---
