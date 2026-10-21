---
statblock: true
layout: Basic 5e Layout
name: Sivis Scribe
source: EFA
size: Small
type: humanoid
subtype: gnome
alignment: neutral
ac: 15
hp: 56
hit_dice: 16d6
speed: 30 ft.
stats:
- 11
- 15
- 10
- 16
- 12
- 11
saves:
- wis: 3
skillsaves:
- arcana: 5
- sleight of hand: 4
senses: Darkvision 60 ft., passive Perception 11
languages: Common, Gnomish plus three other languages
cr: '3'
traits:
- name: Words of Reason
  desc: Allies in a 10-foot Emanation originating from the scribe have Advantage on saving throws to avoid or end the Charmed or Frightened condition. This trait doesn't function if the scribe has the Incapacitated condition.
- name: Spellcasting
  desc: |-
    The scribe casts one of the following spells, requiring no Material components and using Intelligence as the spellcasting ability (DC 13):
    At will: Comprehend Languages, Mage Armor (included in AC), Message
    1/day each: Sending
actions:
- name: Multiattack
  desc: The scribe makes two Bursting Sigil attacks.
- name: Bursting Sigil
  desc: 'm,r +5, reach 5 ft. or range 60 ft. Hit: 13 (3d6 + 3) Radiant damage.'
reactions:
- name: Word of Stasis (Recharge 5-6)
  desc: con DC 13, each creature in a 20-foot-radius Sphere centered on a point the scribe can see within 60 feet.  The target has the Incapacitated condition until the start of the scribe's next turn. While the target is Incapacitated, its Speed is 0 and can't increase.
---
